# University & Course Data Scraping

This project scrapes university information from Wikipedia using Python.

## Tools Used
- Python
- Requests
- BeautifulSoup
- Pandas
- OpenPyXL

## Data Structure

Sheet 1: Universities
- university_id (Primary Key)
- university_name
- country
- city
- website

Sheet 2: Courses
- course_id (Primary Key)
- university_id (Foreign Key)
- course_name
- level
- discipline
- duration
- fees
- eligibility

Each course is linked to its university using university_id.