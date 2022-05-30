# REST

REST stands for representational state transfer, which is just a fancy name for a set of rules that you can
follow to build a web app that provides access to data in a way that's reusable by multiple applications.

There are a few ides behind REST:

- You access data via URLs. For example, /users/Ada lets you access data about a user named Ada.
- You use HTTP methods to acces or change data. For example, you'd view Ada's data by issuing a
  GET request to /users/Ada, and you'd modity Ada's data by issuing a POST request to /users/Ada.
  You can use the other HTTP methods (like put and delete) to interact with the data as well.
- You can represent data however youy want.
