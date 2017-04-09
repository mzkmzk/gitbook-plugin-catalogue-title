# gitbook-plugin-catalogue-title

Change the title tag content for this article title + parent title + book title

gitbook .html default title is `page_title · book_name`

catalogue-title .html title is `page_title [...parent title] · book_name`

# Example

Frontend
    Javascript
        basic_knowledge

book_name is Frontend blog

the page title is basic_knowledge Javascript Frontend Frontend blog

inLine Demo: <http://blog.404mzk.com>

# Install

npm install --save gitbook-plugin-catalogue-title

or 

change book.json

```javascript
{
    "plugins": [
        ...
        "catalogue-title"
    ]
}
```

