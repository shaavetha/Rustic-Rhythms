# Rustic-Rhythms
A multi-page music store website that showcases a catlog of record albums, an interactive storefront, and customer-facing pages like checkout and contact.
This website is structured as a multi-page front-end project that combines modern styling with data transformation techniques to present a curated collection of music products. 

* This is a front-end focused project. No backend or JavaScript functionality is included. 
* store.xml and album.xml require browser support for XML/XSL transformation.
* Optimized for Chrome, Firefox, Safari.
* 'Coursework Report.docx' is available for more details on the creation of this website

# Features
 - Multi-page HTML structure
 - Fully styled with consistent theme
 - Top nav bar + sticky menu
 - Side nav (Home, About Us, Contact Us)
 - Clickable logo (top left) + "RUSTIC RHYTHMS" banner both link back to the home page
 - XML album data transformed via XSLT
 - Table layout + scroll animations
 - About, Login, Checkout, Contact, and Thank You pages
 - DTD for XML validation


# Tools Used
- HTML
- HTML Table
- CSS (combination of external, internal, and inline)
- XML
- XSLT (with XPath)
- DTD

# Folder Structure
'index.html' — Home page with hero banner, featured albums, shop info, and opening hours.
'about.html' — "About Us" page with team profiles and shop objectives.
'contact.html' — Contact form and shop information.
'checkout.html' — Checkout form for shipping and payment details.
'thankyou.html' — Confirmation page after checkout.
'login.html' — Login interface for users.
'storefront/store.xml' — XML file transformed via XSL to display the product catalog.
'albumlist/store.xsl' - XSL file that transforms XML file using XPath to display the Store page
'albumlist/store.dtd' - Validates the XML file
'styles.css' — External CSS file for consistent layout and styling.
'images/' — All icons and logos.
'images/songs' -  All album images.

# CSS Styling Approach
- External css - 
    Most pages (like index.html, about.html, etc.) link to styles.css for consistent styling
- Internal css
    Used in individual pages like checkout.html, contact.html, login.html, thankyou.html to demonstrate internal styling
- Inline css
    Found in all pages except about.html for layout or quick styling on buttons or containers

*The use of all three CSS methods was intentional for learning purposes — to demonstrate proficiency with each styling technique.
In a real-world project, external CSS would typically be used exclusively for better maintainability and separation of concerns.*

# How to run

1. Download the RusticRhythms folder
2. Open index.html in a web browser.
3. To view the XML transformed 'Store' page:
     Open storefront/store.xml directly in Safari or Firefox
   **OR**
   
     1. Open terminal or the cmd prompt in the location of the saved project folder
     2. Run the command:
          python -m http.server 8080
     3. Then go to:
          http://localhost:8080/storefront/store.xml



# Notes
- The Login and Contact Us pages contain static buttons — they are visually styled but do not perform any actual login or message-sending operations.
- The Complete Order button on the Checkout page is clickable and redirects to a Thank You page, but this is purely for demonstration. No form data is processed or saved.
- All three pages are non-functional and serve UI/UX and layout demonstration purposes only.
