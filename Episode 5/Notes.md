# Episode 5 - Key points

<details><summary><font size=5>Key Points </font></summary>

  - ### `Meta tag` : <font size=3>The meta tag defines metadata about an HTML document. Metadata is data (information) about data. Meta tags always added inside the head tag. Meta tags are used to provide additional information about a page to search engines and other clients. Metadata will not be displayed on the page, but it's used by browsers (how to display content or reload page), search engines (Google, Yahoo!, Bing etc.), and other web services.</font>

  - ### Attributes used in Meta tag
    - #### `charset` : The charset attribute specifies the character encoding for the HTML document. UTF-8 character set covers almost all of the characters and symbols in the world.
    - #### `name` : used to take properties name
    - #### `content` : used to specify properties value
    - #### `http-equiv` : used to get the HTTP response message header

  - ### Properties used in Meta tag
    - #### `description` : Define a description of your web page. This is used by search engine while indexing your page/site.
    - #### `keywords` : Define keywords for search engines. Search engine uses this while indexing your page/site.
    - #### `author` : Define the author of a page
    - #### `revised` : Used to tell Search Engine the Last Modified Date and Time of page
    - #### `refresh` : It is used to specify the HTTP header Refresh, which refresh the page every x seconds
    - #### `viewport` : Setting the viewport to make your website look good on all devices
    - #### `Content-Type` : It is used to specify the HTTP header content type

    ```
      <meta charset="UTF-8">
      <meta name = "keywords" content = "HTML, Meta Tags, Metadata" />
      <meta name = "description" content = "Learning about Meta Tags." />
      <meta name = "author" content = "Vishwas chauhan" />
      <meta name = "revised" content = "Tutorialspoint, 3/7/2014" />
      <meta http-equiv = "refresh" content="1">
      <meta http-equiv = "refresh" content = "5; url = https://www.google.co.in" />
      <meta http-equiv = "Content-Type" content = "text/html; charset = UTF-8" />
    ```
  
</details>