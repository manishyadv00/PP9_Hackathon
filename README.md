# PP9_Hackathon
Title of the Project : - WebScraping To get Cryptocurrency prices using Cheerio.

Aim - To get the top 10 cryptocyrrency with their all details from the site https://coinmarketcap.com 

Tech Stack: JavaScript, NodesJs & cheerio.

Working - In this i have used 3 differnt libraries i.e axios,cheerio,express
=> Axios for to make request on browser and supports promises API and Intercept request and response.
=>Express this app starts a server and listens on port 3000 for connections.
=>I use the async function and use the promises method i.e (try () catch () ).
=> Go to the site url and fetch data using $ i.e cheerio is notated with this sign .
=> and i didn't use any class or id to go to the element i use the css selector that will target the elements.
=> to pass the selector .each() and .children() It allows us to search through the children of themselves in the DOM.
=>This method optionally accepts a selector expression of the same type that we can pass to the function.
=> by using the express libraray our program will show output on "https://localhost:3000/api/price-feed"

Result - Project is working properly

Refrences - https://stackabuse.com/making-asynchronous-http-requests-in-javascript-with-axios/ 

https://www.npmjs.com/package/express 

https://api.jquery.com/children/ 
