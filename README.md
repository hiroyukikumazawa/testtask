### Test Task: TypeScript Array Manipulation

#### Objective:
Create a TypeScript function that processes an array of objects representing book data. The function should accomplish several tasks including filtering, sorting, and data transformation, then output the final results.

#### Instructions:
1. **Define the Book Interface:**
   - `Book` should have the following properties:
     - `id`: number
     - `title`: string
     - `author`: string
     - `yearPublished`: number
     - `genre`: string

2. **Create a sample array of books:**
   - Populate an array named `books` with at least 5 sample book objects.

3. **Function Requirements:**
   - The function `processBooks` should take an array of `Book` objects as an argument.
   - The function should perform the following operations:
     1. **Filter**: Keep only the books published after the year 2000.
     2. **Sort**: Sort the filtered books by year published, from newest to oldest.
     3. **Map**: Transform the sorted array into an array of strings formatted as `"Title by Author (Year)"`.

4. **Output:**
   - Log the final array of strings to the console.

5. **Additional Criteria:**
   - Use TypeScript correctly for all variable and function type definitions.
   - Ensure your code is well-documented with comments explaining the purpose and functionality of each section.
   - Consider edge cases (e.g., empty arrays, incorrect types).
