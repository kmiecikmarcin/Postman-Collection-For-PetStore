## Postman collection for Pet Store API
This is my own Postman collection for public Pet Store API: https://petstore.swagger.io/#/.

<br />

### Postman collection
Please take a look on collection in my workspace: [Postman collection Pet Store API](https://www.postman.com/marcin-kmiecik/workspace/petstore/overview)

<br />
<br />

### What is in collection?

In this collection you can find two types of tests:
  * [F] - for functional testing requests,
  * [E2E] - for testing a few requests bases on end to end testing.

Every request has:
  * environment variables - requests use a environment variables which could be re-useble in all request for that API,
  * collection variables - which are could be useble only fo that specific collection,
  * pre-request - in that scope request prepare all necessery data which must be send in a request,
  * post-response - here are tests which check that response has proper data and takes and sets data from response.
