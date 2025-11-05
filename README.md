# SkinMate : Your Skin Soulmate

## Repository Outline

```
1. README.md - Penjelasan gambaran umum project
2. P2M3_ade_widya_ddl.txt - Berisi URL dataset, DDL pembuatan tabel, dan DML/COPY insert ke PostgreSQL
3. P2M3_ade_widya_data_raw.csv - Dataset original sebelum proses cleaning
4. P2M3_ade_widya_data_clean.csv - Dataset yang sudah melewati proses data cleaning
5. P2M3_ade_widya_DAG.py - Script Apache Airflow untuk pipeline ETL (Fetch PostgreSQL → Cleaning → Load Elasticsearch)
6. P2M3_ade_widya_DAG_graph.jpg - Screenshot DAG yang menunjukkan semua task sukses
7. P2M3_ade_widya_GX.ipynb - Validasi data menggunakan Great Expectations
8. P2M3_ade_widya_conceptual.txt - Jawaban conceptual problem sesuai ketentuan tugas
9. /images  
   Folder berisi screenshot dashboard dan insight:
   - introduction & objective.png
   - plot & insight 01.png
   - plot & insight 02.png
   - plot & insight 03.png
   - plot & insight 04.png
   - plot & insight 05.png
   - plot & insight 06.png
   - kesimpulan.png
```