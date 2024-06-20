# Opossum-Search
Every time you make a search query, it should redirect you to a Google search with the same query, but with the word "opossum" added to it.

**Explanation:**

1. **HTML Structure:**
   - The HTML file has a basic structure with header, main content, and footer.
   - The header contains the opossum image logo.
   - The main content has a search bar with the form for submitting queries.
   - The footer displays "Powered by opossum search".

2. **CSS Styling:**
   - The CSS code is inline within the `<style>` tag.
   - It provides basic styling for the elements, including font, colors, layout, and spacing.
   - The search bar is centered, and the logo is centered in the header.

3. **Search Form:**
   - The form targets Google's search engine (`https://www.google.com/search`).
   - The `<input type="text">` element takes the user's search query.
   - The `<input type="hidden" name="q" value="opossum">` automatically adds "opossum" to the search query.
   - The `<button type="submit">` triggers the search.

4. **Opossum Image:**
   - The `src` attribute of the `<img>` tag is set to the provided URL of the opossum image.

5. **Footer:**
   - The footer is styled with a background color and a border.
   - It displays "Powered by opossum search" at the center.

**How it works:**

- When the user types a query and clicks "Search", the form submits the data to Google's search engine.
- The hidden input field ensures that the query sent to Google always includes the word "opossum".
- This results in a Google search with the user's query and the additional term "opossum".
