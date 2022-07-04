# searchLite3

**An add-on that will allow users of your site to quickly and easily find the right resource**


The module accepts a normal request from the form and compares with the names of the resources, if the name matches, the resource is shown in the results:

- only published resources participate in the search;
- Resources hidden in the menu do not participate in the search;
- When adding the searchLiteTV variable to the SearchLite3 snippet, you can search for words in the TV fields



*After installing the add-on, you will need to create a resource with search results and send a request to this resource.*


[link for demo:](http://modxthree.sait-modx.by/instrukcziya-search-lite-3.html)

###Examples:

an example of a normal snippet call on the search results page:

```php
[[!searchLite3
]]
```

пример  вызова снипета на странице результатов поиска с поиском в ресурсах и в TV-поле('bio'):

```php
[[!searchLite3?
&searchLiteTV=`bio`
]]
```
