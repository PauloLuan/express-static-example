# Express Static Files Example

Cloning the project:

	git clone 

Install the dependencies:

	npm i

Run the application:

	npm start

Now you can access the static content by two different URL's:

``` javascript
app.use('/styles/', express.static(path.join(__dirname, 'static_example', 'stylesheets')));
``` 
Example: http://localhost:3000/styles/style.css


``` javascript
app.use('/images/', express.static(path.join(__dirname, 'static_example', 'images')));
```
Example: http://localhost:3000/images/1.jpg


## Useful resources: 

http://evanhahn.com/express-dot-static-deep-dive/
http://expressjs.com/en/starter/static-files.html
http://stackoverflow.com/questions/10434001/static-files-with-express-js
