Question

    1. In one sentence: What does res.render(view, data) do?
    = It combines your EJS template file with data to generate a final HTML page and sends it to the browser.

    2. What is the difference between <%= %> and <%- %>?
    = <%= %> displays plain text safely (escapes special characters)
      <%- %> renders actual HTML code (used for including partials).

    3. Where does Express look for EJS templates (folder path)?
    = It looks in the views folder located in your project's main directory, as defined by code app.set("views", ...).
