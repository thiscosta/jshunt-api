# jshunt-api

Simple REST API with CRUD operations for products

<br />Running API:<br />
<ol>

<li>Clone this repo: <strong>git clone https://github.com/thiscosta/jshunt-api.git</strong></li>
<li>Inside the project folder, run <strong>npm install</strong></li>
<li>After the packages get installed, run <strong>npm run dev</strong></li>

</ol>

<strong>You must have mongodb running on 27017 port.</strong>


<br /> <br />
<h3>Endpoints</h3>
<ul>
  <li>List all products: <br /><strong>GET</strong> /api/products</li>
  <li>Store product: <br /> <strong>POST</strong> /api/products</li>
  <li>Show product: <br /><strong>GET</strong> /api/products/:id</li>
  <li>Update product: <br /><strong>PUT</strong> /api/products/:id</li>
  <li>Delete product: <br /><strong>DELETE</strong> /api/products/:id</li>
</ul>

<br />

<h3>Product object</h3>
<ul>
<li><strong>title</strong> : String </li>
<li><strong>description</strong> : String </li>
<li><strong>url</strong> : String </li>
</ul>

<h3>Example request</h3>
<strong>POST to /api/products</strong>
<p>{
<br />
"title":"NodeJS", <br />
"description":"Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine" <br />
"url":"https://nodejs.org/en/" <br />
}
</p>


