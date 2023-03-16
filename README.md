# Regex
1. Pencocokan Username
/^[a-z0-9_-]{3,16}$/

2. Pencocokan Password
/^[a-z0-9_-]{6,18}$/

3. Pencocokan Nilai Hex
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

4. Pencocokan Slug
/^[a-z0-9-]+$/

5. Pencocokan Email:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

6. Pencocokan URL
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\
