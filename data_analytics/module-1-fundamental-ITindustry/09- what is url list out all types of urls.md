# What Is a URL?

A **URL (Uniform Resource Locator)** is the address used to locate a resource on a network, such as a web page, image, or file. A browser uses the URL to find and request the resource.

## Parts of a Web URL

Example: `https://www.example.com:443/products?id=25#details`

- **Scheme** — `https`; tells the client how to access the resource.
- **Host or domain** — `www.example.com`; identifies the server.
- **Port** — `443`; identifies a network service on the server. Standard ports are often omitted.
- **Path** — `/products`; identifies a resource or route on the site.
- **Query string** — `?id=25`; passes parameters to the server.
- **Fragment** — `#details`; points to a section or location within the resource.

Not every URL contains every part. A URL is one kind of URI (Uniform Resource Identifier): a URI identifies a resource, while a URL also tells where or how to access it.

## Common URL Types

URL types are often grouped in different ways, so these categories overlap rather than forming one exhaustive list.

### By How the Address Is Written

- **Absolute URL** — Includes the scheme and domain, giving the full address.  
  *Example: `https://www.example.com/about`*
- **Relative URL** — Gives a path relative to the current page or site; the browser resolves it using the current address.  
  *Example: `/about` or `images/logo.png`*

### By Scheme or Purpose

- **HTTP URL (`http://`)** — Requests a resource using HTTP; the connection itself is not encrypted.
- **HTTPS URL (`https://`)** — Uses HTTP protected by TLS, providing encryption and server authentication.
- **FTP URL (`ftp://`)** — Identifies a resource for the File Transfer Protocol; support varies by browser and system.
- **Mail URL (`mailto:`)** — Opens or prepares an email message in a mail application.  
  *Example: `mailto:info@example.com`*
- **Telephone URL (`tel:`)** — Represents a telephone number and may prompt a compatible device to call it.  
  *Example: `tel:+15551234567`*
- **File URL (`file://`)** — Refers to a file on a local device or accessible file system; access is subject to browser and operating-system security restrictions.
- **Data URL (`data:`)** — Embeds small data directly in the URL instead of referring to a separate file.

### By What the URL Points To

- **Web page URL** — Points to a page or route on a website.
- **File or media URL** — Points to a downloadable file or media resource, such as an image, PDF, audio, or video file.
- **API URL (endpoint)** — Points to a web service resource used by software, often returning structured data such as JSON.
- **Redirect URL** — Takes a visitor from one address to another.
- **Anchor or fragment URL** — Includes a fragment (such as `#contact`) to point to a location within a page.

### By How Content Is Served

- **Static URL** — Commonly serves a fixed resource, such as an image or a prebuilt page.
- **Dynamic URL** — May include query parameters or a route that a server uses to generate or select content.  
  *Example: `https://www.example.com/search?q=books`*

## URL Safety Tips

- Check the domain carefully; a familiar-looking page can use a misleading address.
- Prefer HTTPS when entering sensitive information, but remember that HTTPS alone does not prove a site is trustworthy.
- Treat unexpected links and URLs containing unfamiliar parameters with care.