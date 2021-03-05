# innodb_buffer_stats_by_schema

SELECT 
    object_schema,
    allocated,
    data,
    pages,
    pages_hashed,
    pages_old,
    rows_cached
FROM
    sys.innodb_buffer_stats_by_schema;
