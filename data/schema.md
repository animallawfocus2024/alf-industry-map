# Data schema (draft)

Each facility record should include:

- id (string)
- name (string, optional)
- company (string, optional)
- species (string: chicken/pig/fish/etc.)
- region (string)
- commune (string, optional)
- latitude (number)
- longitude (number)
- infrastructure_type (string, optional)
- sanction_count (number, optional)
- last_sanction_date (date, optional)
- sources (array of links/ids)
- notes (string, optional)

Future fields (v2+):
- estimated_capacity
- estimated_animals
- satellite_area_m2
- land_use_category
