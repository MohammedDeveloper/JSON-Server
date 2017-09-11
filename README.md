## JSON-Server: Create a Fake REST API with JSON-Server

# GET SINGLE RECORD
http://localhost:3000/companies/2

# GET RECORD(s) by Reference
http://localhost:3000/companies/2/users

# Filter by column
http://localhost:3000/users?firstName=tst-usr-fst-101

# Pagination & Limit
http://localhost:3000/users?_page=2&_limit=2

# Sorting
http://localhost:3000/users?_sort=companyId&_order=asc

# Full Text Search
http://localhost:3000/users?q=1