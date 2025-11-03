# WedePortfolioOfEvidence
This is the third part of my wede poe
Some changes I made include:
Navigation & Structural Fixes
Corrected the previous broken Contact Us navigation link so it correctly redirects to contact.html.
Corrected the previous wrong FAQ page link so it now consistently points to faq_reviews.html.
Ensured the Enquiry page link appears on all pages, not only Home and About Us.
Made sure all pages use the exact same navigation bar for consistency.
Applied consistent active states across navigation so the current page is clearly visible.

User Interface (UI) Improvements
Replaced the banner title and slogan with a full-banner logo, while still retaining the text in the HTML as hidden content for accessibility and SEO.
Updated the Home page product images to match the layout and styling of the Products page, ensuring a consistent user experience across the site.
Applied glowing hover effects to navigation links, using gold and pink brand colors to enhance interaction and styling.
Ensured images, text, and card layouts are clean, visually consistent, and professional.
Added smooth animations and improved visual feedback for user interaction.

Responsive Design Improvements
Implemented responsive typography using clamp() to ensure headings and body text resize correctly on different devices.
Improved layout scaling across desktop, tablet, and mobile views.
Ensured images resize proportionally and maintain proper spacing on smaller screens.
Verified that navigation becomes a responsive stacked layout on smaller displays.

JavaScript Enhancements
Added sticky navigation bar functionality so the menu becomes visible, glowing, and fixed at the top while scrolling.
Added JavaScript form validation and confirmation messages for both the Enquiry and Contact forms.
Implemented feedback messages when forms are submitted so users clearly know their action succeeded.
Included fail-safe logic in JavaScript using optional chaining to prevent script errors if a form does not exist on a specific page (?.addEventListener()).
Prepared structure for future enhancements like image modals and dynamic loading.

Forms & User Experience
Created a fully functioning Enquiry form with fields for name, email, inquiry type, and message.
Updated the Contact page form to collect name, email, and a detailed message.
Added client-side validation for required fields.
Contact form now triggers the user's default email client with the message content using a mailto: link.
Displayed form success messages to improve user feedback and UX.

SEO Improvements
Added meta descriptions to each page to improve search engine visibility.
Applied meaningful page titles and consistent SEO-friendly naming conventions.
Added descriptive alt text to all images to support accessibility and search indexing.
Created a robots.txt file to guide search engine crawlers.
Built a sitemap.xml file so search engines can easily discover and index all pages.
Ensured internal linking across pages to improve crawl efficiency and navigation flow.
Maintained semantic HTML structure using section, nav, footer, figure, and figcaption.

File & Folder Structure
Ensured script.js, style.css, robots.txt, and sitemap.xml are correctly placed in the main project directory.
Confirmed ALL image assets are placed inside the _images directory.
Linked all files properly without changing original folder structure.

Accessibility & Semantic Improvements
Added hidden but accessible text (.visually-hidden) for screen readers where visual text was removed.
Used semantic tags (main, nav, footer, details, summary, figure, figcaption) to improve structure.
Ensured contrast ratios were appropriate and readable, particularly in the header and navigation.







