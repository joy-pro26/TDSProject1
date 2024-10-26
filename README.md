# Summary of the Project
# •	Approach: 
Using Python’s requests library, I paginated through GitHub's REST API to gather all Chicago-based users with 100+ followers, collected their repositories, saved the data in CSV on Google Drive, and performed data cleaning on fields like company names and boolean data types.
# •	Surprising  Insights: 
Public Repos vs. Followers Discrepancy: 
Users like "eddelbuettel" and "mattgodbolt" demonstrate that a high repository count (471 and 84, respectively) doesn’t guarantee popularity, as follower numbers are often influenced more by the specificity of contributions or niche expertise than by sheer repository volume.
# •	Recommendation: 
Consider gradual transition from JavaScript to TypeScript by migrating certain projects, training developers, and standardizing TypeScript for new initiatives. Leverage TypeScript’s tooling and refactor shared modules to improve code quality, maintainability, and stay aligned with evolving development trends.
# •	Additional Help
Using github api https://docs.github.com/en/rest/using-the-rest-api/getting-started-with-the-rest-api?apiVersion=2022-11-28
# •	Tips
Boolean value to be stored in lower case, null value should be traeted as false.
Browser caching to be considred while testing.
