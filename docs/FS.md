Functional Specification
========================
_Swing Paints Ltd._ is a family-owned business that has been operating in Canada since 1965. 
The company produces various products for do-it-yourself and industrial use in the areas of wood finishing, painting and cleaning.
 
The current [web site](http://www.swingpaints.com) was created in 2001 to provide direct internet access to product information, dealer locations, contacts, etc.  Over the years, an interactive forum and online purchasing option were added to the site.

The site is a gateway into the company for current and potential customers.  As such, the site must satisfy the following criteria:
- **BILINGUAL**:  Swing Paints is based in Canada.  Therefore, the web site must have all the information accessible in both English and French.  The potential for other languages would be useful.
- **COMPANY PROFILE**:  A brief overview of the company stressing the fact that it is a family-owned business based in Montreal.
- **CONTACTS**:  Information on telephone, fax, e-mail, etc.
- **PRODUCT INFORMATION**:  Detailed information on each product, including information specific to dealers as well as consumers.  The potential for links to videos and photo galleries would be beneficial.
- **eMAL**:  Most products should be made available for online purchase.  We currently work with a third party to securely collect credit card information
- **ONLINE FORUM**:  The site must continue to maintain a high quality online forum where customers can discuss specific issues that relate to projects in our field.

We propose to have the web site upgraded and redesigned to satisfy our current and future needs.
- Replace all SWF files (Shockwave Flash) to a format that provides for simple modification and support on all browsers and mobile platforms.
- Redesign the Home Page to allow for simple addition of new categories.
- Redesign the Product Page to allow for simple addition of new products.
- Redesign the Product Page to include tab views
 
The coder will coordinate with marketing to ensure the web site synchronizes with product packaging and other promotional tools.

Static Layout
-------------
Every page will include several elements standard throughout the site, for ease of modifications. These will include a header and footer with links to company information and &ldquo;category&rdquo; pages. In addition to these static elements, a generic space will be left, to be filled by whatever content is required for a certain page. URLs will be simplified so that they can be remembered easier, ie. no complicated page names or extensions.

### Header ###
The header will include links to the home, company information, FAQ, and resources for businesses or in-store purchase. It will also include drop-down sections by product category, producing links to the relevant products.

### Footer ###
The footer will contain links to miscellaneous pages such as the forum, newsletter sign-up, referring friends, and brochure request. It will also include copyright information, and last updated date.

Home Page
---------
The home page will show image examples of products and provide links to common pages, such as the FAQ, contact, and forum, in addition to the static elements. It will also provide links to the category pages.

About Page
----------
The about page will contain a short description of the company, which may be found in its current version [here](https://github.com/Youppi3/flaskexample/blob/master/docs/about.md#about-swing-paints), along with contact information, such as physical address, phone number, and support email.

FAQ
---
The FAQ will contain some frequently asked questions, which may be found in its current version [here](https://github.com/Youppi3/flaskexample/blob/master/docs/FAQ.md#swing-paints-faq).

Marketing Page
--------------
The marketing page will contain information to aid in marketing and sales assistance, including promotions, MSDS requests, sales support, packaging, and private label options. The current version can be found [here](https://github.com/Youppi3/flaskexample/blob/master/docs/marketing.md#marketing-and-sales-assistance).

Locations Page
--------------
The locations page will list all well-known retail locations where the products can be found. They will be grouped by region and have a short description on the products available at that particular store.

Forum
-----
The forum is a message board open to the public for discussion and questions on the products. It is written in ASP, and can be found [here](http://www.swingpaints.com/forum.asp). This page will not be modified in conjunction with this project.

Category Page
-------------
Each group of products, or category, will have its own page with pictures of all the corresponding products and links to the product pages. It will also possibly have a short description of what the category covers. This page will be dynamically produced based on the URL and all content will be shown based on the prodcuts in the category.

Product Page
------------
Each product page will be dynamically produced, showing a picture, a short description, an option to buy online, directions, more information including sizes and tips for choosing correctly, and possibly links to demonstrations. These will sections manifest themselves into tabs or some other easy-to-read layout. Visitors will only arrive at these pages through the category pages, or a direct link from another site.
