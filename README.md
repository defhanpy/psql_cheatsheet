-- Mencari table berdasarkan nama
SELECT table_schema, table_name
FROM information_schema.tables
WHERE table_name ILIKE '%nama_table%';

-- Mencari Fungsi berdasarkan nama
SELECT routine_schema, routine_name
FROM information_schema.routines
WHERE routine_name ILIKE '%skripsi%';
