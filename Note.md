React Basics
=======

1.How to use React with a CDN(load React into an existing Webpage):
-------
1. Go to the official website ti copy the CDN links:
[React CDN Links](https://reactjs.org/docs/cdn-links.html)
The first one is the React library.
The second one is the dom which is the glue between React and the browse.If decided to deploy the website, use the production one. Then put them inside the head tags.

2. Go to the official website ti copy the CDN links:
[Babel Official website](babeljs.io)
Click Setup, then in Browser, then go to usage. Then copy and paste the babel.

3. Add script after the footer:
write React in that part.
Before the end of the script,write:

```Html
    ReactDOM.render(the component you wanna render, the place you wanna render the component to, it could be:document.get ElementById(''banner))
