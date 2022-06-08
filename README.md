# products
This repo contains the source code for a Grafbase project.

The schema (schema.graphql) in grafbase/
is for a simple ordering system,
with products, customers, and their orders (of the products).

## Code Examples

Initially there N code examples:

* Create a product, which we run three times to create three different products
* List the products
* Create a customer, which we run three times to create three different customers
* List the customers
* Order a product, which we run three times to create order a different product for each customer
* List the orders

The same code examples are written in three programming languages in code-examples:

* curl, with the code described in code-examples/curl/curl.txt
* JavaScript, in code-examples/javascript/Create[product | customer | order].mjs and List[products | customers | orders].mjs
* Go(lang), in code-examples/golang/create-[product | customer | order]/main.go and list-[products | customers | orders]/main.go
