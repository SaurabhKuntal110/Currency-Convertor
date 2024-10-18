# Currency-Convertor
<p>
The Currency Converter is a web application built using HTML, CSS, and JavaScript that allows users to convert between different currencies in real-time. The interface includes input fields for the amount and dropdowns for selecting the base and target currencies.<br><br>

JavaScript is used to handle conversions, while the Fetch API retrieves live exchange rates from a third-party API. The conversion is triggered automatically when users enter an amount or change currencies, ensuring real-time updates with accurate rates.<br><br>

CSS is used to create a responsive, user-friendly design, ensuring the app looks and works well on various devices, from desktops to mobile phones.<br><br>

Features:<br>
Live exchange rates via Fetch API.<br>
Automatic conversions based on user input.<br>
Responsive design for all devices.<br>
This project showcases the practical application of APIs in modern web development.</p><br><br>
<h2>Note-</h2>
URL Structure:<br>
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@{date}/{apiVersion}/{endpoint}<br>
<br>
Formats:<br>
<h3>Date</h3>
<br>
The date should either be latest or in YYYY-MM-DD format<br>
<br>
The Endpoints Supports HTTP GET Method and returns the data in two formats:<br>
<br>
/{endpoint}.json
<br>
/{endpoint}.min.json
<br>
<h3>Endpoints:</h3><br>
<h3>/currencies</h3><br>
Lists all the available currencies in prettified json format:<br>
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies.json<br><br>

Get a minified version of it:<br>
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies.min.json<br>
<br>

<h3>/currencies/{currencyCode}</h3>
Get the currency list with EUR as base currency:<br>
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/eur.json<br><br>

Get the currency list with EUR as base currency on date 2024-03-06:<br>
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@2024-03-06/v1/currencies/eur.json<br><br>
