# wp-Sql-query

select prodcut meta by sku
SELECT post_id, meta_key, meta_value FROM wp_postmeta WHERE post_id IN ( SELECT post_id FROM wp_postmeta WHERE meta_value = 'B314' )
