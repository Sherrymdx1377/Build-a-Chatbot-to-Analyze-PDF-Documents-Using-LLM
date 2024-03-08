## Build-a-Chatbot-to-Analyze-PDF-Documents-Using-LLM

# Introduction

This project is about creating a chatbot for your pdf files using Flask, a popular web framework, and the Langchain, another popular framework for working wtih Large Language Models (LLMs). The chatbot will not just interact with users via text but also comprehend and answer questions related to the content of a specific document. 

# Flask

Flask is a lightweight and flexible web framework for Python, known for its simplicity and speed. A web framework is a software framework designed to support the development of web applications, including the creation of web servers, and managing HTTP requests and responses. Flask is used to create the server side or back-end of our chatbot. This involves handling incoming messages from users, processing these messages, and sending appropriate responses back to the user.

# Langchain

Langchain is a versatile tool for building AI-driven language applications. It provides various functionalities such as text retrieval, summarization, translation, and many more, by leveraging pre-trained language models. In this project, we will be integrating Langchain into our chatbot, empowering it to understand and respond to diverse user inputs effectively.

# Chatbots

Chatbots are software applications designed to engage in human-like conversation. They can respond to text inputs from users and are widely used in various domains, including customer service, eCommerce, and education. In this project, you will build a chatbot capable of not only engaging users in a general conversation but also answering queries based on a particular document.

# Routes in Flask

Routes are an essential part of web development. When your application receives a request from a client (typically a web browser), it needs to know how to handle that request. This is where routing comes in.
In Flask, routes are created using the @app.route decorator to bind a function to a URL route. When a user visits that URL, the associated function is executed. In our chatbot project, we will use routes to handle the POST requests carrying user messages and to process document data.

# HTML - CSS - Javascript

We’ve provided a ready-to-use chatbot front-end, built with HTML, CSS, and Javascript. HTML structures web content, CSS styles it, and Javascript adds interactivity. These technologies create a visually appealing and interactive chatbot interface.

