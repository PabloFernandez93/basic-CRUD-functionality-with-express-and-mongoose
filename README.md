Topics covered:

- Working with EJS
- Making an index route (Products Index)
- Making a show route (Product Details) and linking it to the index route.
- Making a create route (for creating Products with a form)
- Parsing the request body with app.use(express.urlencoded({ extended: true }));
- Using Express redirect
- Updating Products with edit.ejs and prepopulating the form
- Using method-override and adding the query string in our form (to be able to make a put request)
- Deleting products
- Filtering by Category with a query string


How to run it:

- (you need to have node installed and mongodb running in the background)
- npm init -y
- npm i express ejs mongoose method-override
- node index.js (to run the file)
