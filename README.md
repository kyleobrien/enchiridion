# The Enchiridion
A handbook.

## Internet

-   Born in the '80s.

## WWW
World Wide Web

-   Born in the '90s and layered atop of the Internet; resources identified by URLs and connected by hyperlinks.
-   Resources (like HTML documents) are hosted on a web server.
-   Communication between web server and client (probably a web browser) via HTTP.
    -   Client can request documents that should be returned from the server (GET).
    -   Client can send information to the server (POST)
    -   Client can upload (PUT) documents on the server.
    -   Client browser styles the HTML document with CSS, gets functionality from JavaScript.

## URL
Uniform Resource Locator

## HTTP

## HTML
Hypertext Markup Language 

-   A standard made up of elements and attributes.
-   Use .html file extension.
-   Here's a really simple template:
    ```
    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8" />
            <title>This is the Title!</title>
        </head>
        <body>
            <p>This is some text...</p>
        </body>
    </html>
    ```
-   Tags
    -   audio: play soem audio
    -   video: play some video
    -   canvas: paint stuff
    -   form: accept data from user and send it to the server
    

## CSS
Cascading Style Sheets

-   A language that describes the presentation of a document.
-   It has selectors, properties, and attributes.
-   Cab be inline, in the html header, or in an external file.
    ```
    <link rel="stylesheet" href="path/to/stylesheet.css">
    ```
-   Selector: targets one or more elements in the html.
    -   Selectors can be nested.
-   Example:
    ```
    p {
        background-color: purple;
        border: 1px solid orange;
    }
    ```
-   Media queries can target specific device settings )like screen width).
-   CSS libraries are cool.
-   There are things called preprocessors. They seem like garbage.
-   [Basic concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) was really useful.

## JavaScript

-   A terrible, interpreted programming langauge.
-   Can interact with the browser, HTML, and even make calls to servers.
-   Same as CSS; can be inline, in header, or an external file.
-   AJAX = Asynchoronous JavaScript and XML. A technique for calling an API, returning data, and process/displaying it without refreshing the page.
## Node

## SQL
-   Structured Query Language, a way to interact with a database.
-   A basic query to read data:
    ```
    SELECT <column1>, <column2>, ...
      FROM <table>
     WHERE <boolean expression>;
    ```
-   Ordering the results: `ORDER BY <order type>`
    -   ASC = Ascending (the default)
    -   DESC = Descending
-   Operators:
    -   =, equals
    -   <>, not equals
    -   AND, logical and
    -   OR, logical or
-   A basic query to create data:
    ```
    INSERT INTO <table> (<column1>, <column2>, ...)
         VALUES (<value1>, <value2>, ...);
    ```
-   A basic query to update data:
    ```
    UPDATE <table>
       SET <column1> = <some value>, <column2> = <some value>, ...
     WHERE <boolean expression>;
     ```

## Linux
