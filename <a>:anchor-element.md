## Anchor Element
This creates hyperlinks to webpages,files, emails or anything else that the URl can address or point to.

### The attributes
* download:
This causes the browser to treat the linkded URL as a download.

* href:
This is the URL the hyperlink points to.
Eg.
        * telephone numbers with 
        tel:
        * Email addresses with mailto: URLs

* hreflang:
Hints at the human language of linked url (not so famously used)

* ping
 When the link is followed, the browser will send POST requests with the body PING to the URLs. Typically for tracking.

* referrerpolicy:
how much of the referrer to send when following the link.

* rel: 
The relationship of the linked URL as space-separated link types

* target:
Where to display the linked URL, as the name for a browsing context (a tab, window, or <iframe>). The following keywords have special meanings for where to load the URL:

* type:
Hints at the linked URL's format with a MIME type. No built-in functionality.



