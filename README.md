# **Random Quotes**
## It’s an application that fetches a new random quote each time a button is pressed and displays it in the browser. Here’s a screenshot of what the finished application looks like:

![Front image](https://github.com/PriyanshuPatel02/Random-Quotes-/blob/main/quotes.png)
![gif](https://github.com/PriyanshuPatel02/Random-Quotes-/blob/main/quote-gif-modified.gif)
Let’s take our application to the next level by displaying a loading indicator each time a new quote is requested. This signifies to a user that an operation is currently in progress. We’ll also disable the quote button so that only one request can be made at a time.
![Quotes GIF](https://github.com/PriyanshuPatel02/Random-Quotes-/blob/main/quote-gif.gif)
![Donald Trump](https://github.com/PriyanshuPatel02/Random-Quotes-/blob/main/tweet-Quote%20Screenshot.jpg)
<br>

One of the most basic uses of JavaScript is for making interactive wepbages. This allows the page to change slightly or totally when a user performs an action. JavaScript is used for just about everything these days, including, but not limited to, server infrastructure, desktop and mobile apps.

We have two buttons: the first one for fetching a new **random quote** and displaying it on the page, and second for **sharing the quote on Twitter.** At the moment, clicking on either button has no effect and that’s because we haven’t written any JavaScript code yet.

Our task is to fetch a new quote when the quote button is clicked and display it to the user. We’ll be making use of the [What Does Trump Think](https://whatdoestrumpthink.com/api-docs/index.html#introduction) **API** to accomplish this.

A better approach is to get the data using an API. This could be an API that we build for ourselves or one that is made by someone else and provided for public used. Most web APIs transfer data in a format called JSON which stands for JavaScript Object Notation.

There are several public APIs that provide random quotes. As mentioned earlier, we’ll be working with the What Does Trump Think API which provides generic Donald Trump quotes.

To use an API effectively, you need to know the URL, HTTP method, query parameters and authentication requirements for receiving the specific data that you need. You will usually find this information in the documentation of the API you wish to use. 
(https://api.whatdoestrumpthink.com/api/v1/quotes/random)
