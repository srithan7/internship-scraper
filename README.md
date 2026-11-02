# internship-scraper
A Java program that finds internships matching a keyword and exports the results to a CSV.

## Project Goal
Build a Java program that finds internships matching a user's keyword
and exports the results to a CSV file.

## MVP Scope
- Accept a keyword through the console.
- Fetch one page of internship listings from one website or API.
- Extract each listing's title, company, location, and job-posting link.
- Filter titles by keyword, ignoring capitalization.
- Export matching listings to a CSV file.

## Future Plans
- Add more websites or APIs for the user to have a wider range of opportunities
- Add location or other keyword filters
- Check for new internships automatically.

## Tech Stack
- Java
- Java HttpClient for API requests
- Gson for parsing JSON
