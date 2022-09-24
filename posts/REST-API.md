---
title: 'What exactly is a REST / RESTful API?'
date: '2022-04-23'
---

If you're a human being on earth at this point in time and you're even slightly interested in tech, it would be surprising if you told me that you've never heard of the 3 letter acronym - API.

I'll be taking you through an introduction to the whole concept so that by the time your done reading this article you'll be in a good place to hold an intellectual conversation - to some point, with a professional. Better yet, you might even decide to pursue a career within the computer science ecosystem, who knows? definitely not me, I hope you do.

A RESTful (Representational State Transfer) API is an Application Programming Interface that conforms to the standards and rules that a software engineer should follow when building a web app so that the application's data can be accessed and reused by different applications.

From a Hierarchical organization point of view, the REST API rests on top of the database. It may use a language like SQL to interact with the database then all your other applications would communicate with the database through calling your REST API.

There are a few basic ideas concerning REST API's as illustrated in the following paragraphs;

- They've made it easy for cross - language communication since you can organize your code in such a way that data can be inferred from the Uniform Resource Locator    (URL) parameters using HTTP requests (GET, PUT, POST and DELETE)
- The same way you'd go to your phone and type a URL and GET a response from the server with the frontend and backend code mysteriously masked to be engaging content on your browser, that's also how API's work but the difference is that the URL returns data usually in JavaScript Object Notation (JSON) strings. Sometimes though, the data is usually in binary strings or xml form. It wholly depends on the programmer behind the API.
- Each request made to the server hosting the API should be standalone. The server should not store session information on the server.

The ideas around the REST architecture are designed to make it easier for a software engineer to work on the underlying data of his/her application without touching the view that the user interacts with. However, their implementations are entirely up to the programmer as nobody will arrest or penalize them if the REST architecture is not adhered to.
