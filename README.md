SELECT 
    event_date,
    AVG(is_attend) AS avg_attendance
FROM 
    data 
GROUP BY 
    event_date
ORDER BY 
    event_date;
