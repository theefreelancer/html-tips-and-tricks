These are attributes that are used to specify the relationship between the document and the linked resource

Forexample
1. Stylesheet:
Indicates that the linked resource is a stylesheet, typically a CSS file. Example: <link rel="stylesheet" href="styles.css">

2. Icon:
Specifies a favicon for the webpage, typically a small image displayed in the browser's tab or bookmark bar. Example: <link rel="icon" href="favicon.ico" type="image/x-icon">

3. preload:
uggests to the browser to preload the linked resource for later use, potentially improving performance. Example: <link rel="preload" href="image.jpg" as="image">

4. dns-prefetch:
Hints to the browser to establish an early connection to a specific domain before the resource is needed. Example: <link rel="preconnect" href="//api.example.com">

5. canonical:
Specifies the preferred version of a webpage to avoid duplicate content issues in search engines. Example: <link rel="canonical" href="https://www.example.com/page">

6. alternate:
 Indicates an alternative version of the current document, such as translated versions or different formats (e.g., RSS feed). Example: <link rel="alternate" href="rss.xml" type="application/rss+xml" title="RSS Feed">

 7. preconnect: 
 Hints to the browser to establish an early connection to a specific domain before the resource is needed. Example: <link rel="preconnect" href="//api.example.com">

 8. next and prev:
 Suggests the relationship between a series of documents, indicating the next or previous page. Example: <link rel="next" href="page2.html">

 9. author:
 Indicates the author of the linked document or resource. Example: <link rel="author" href="author-profile.html">

 10. license: 
 Specifies the license under which the current document is published. Example: <link rel="license" href="https://creativecommons.org/licenses/by/4.0/">