#  Flow Flowers – Changelog

All notable changes to the website will be documented here.

---

## 2025-09-16
### Improved
- Buttons now styled with yellow background and hover effect.
- Flower cards now have shadows and hover animation.

---

## 2025-09-15
### Added
- Embedded Google Map on **About Us** and **Contact** pages.
- Made map responsive for mobile users.

---

## 2025-09-14
### Added
- Social media icons (Facebook, Instagram, WhatsApp, Email) in footer.
- Hover effects for social icons.

---

## 2025-09-13
### Changed
- Moved inline styles into a central `style.css`.
- Improved design with consistent green background and white/yellow text.
- Added hover effects for links and buttons.

---

## 2025-09-12
### Added
- Initial website pages: Home, About Us, Contact, Enquiry, Flower Types.
- Inline CSS with green background and blue links.
- Images and flower descriptions.

| File(s) | Change | 
## 2025-11-18
### Added
📝 Changelog: POE Checklist Development
1. General Fixes & SEO

- (style.css)  Removed the extra closing curly brace (}) at the end of the file that was causing the footer styles to be ignored.  
-  Implemented and documented changes/improvements based on part 2 feedback. 
  Fixed Social Icons Class Mismatch: Changed CSS selector from .social-icons to the correct HTML class .socials-icons to apply styling. 
 -  Implemented and documented changes/improvements based on part 2 feedback. 
| About Us Page | Fixed Navigation Link: Corrected the "Home" link from index.html to ../index.html to correctly navigate to the index page from the nested pages directory. 

- Implemented and documented changes/improvements based on part 2 feedback. 
All HTML Pages | Implemented SEO Meta Tags: Added <meta name="description"> and <meta name="keywords"> tags to the <head> section of all 

five pages (Index, Flower Types, Contact, Enquiry, About Us). 
| Implemented SEO meta tags (keywords, description) |
2. Interactive JavaScript Elements
 

| Flower Type Page | Gallery Lightbox Activation: Added the required class="thumbnail" to all six flower images to correctly trigger the existing JavaScript lightbox functionality. 
 - Implemented and documented Gallery lightbox. 

| Flower Type Page | Accordion Implementation (Partial): Added the necessary CSS styling, JavaScript logic, and HTML structure (.accordion-button and .accordion-content) to the page. This was demonstrated by converting the "Growing & Care" and "Symbolism & Uses" sections of the English Rose into expandable accordions. 
- Implemented and documented Javascript interactive elements (accordions, tabs, modals, etc...) 

| About Us Page | Full Accordion Implementation: Applied the accordion structure and JavaScript logic to the "Our Story," "Our Mission," and "Where to find us" sections, making them collapsible. 


- Implemented and documented Javascript interactive elements (accordions, tabs, modals, etc...) 
| Flower Type Page | Search Feature: Added a <input type="text" id="flowerSearch"> to the navigation and implemented the filterFlowers() JavaScript function to dynamically hide/show flower articles based on the input text. | Implemented the search feature. |

| Index Page | Dynamic Content: Added a <div> element with id="real-time-content" and implemented the updateClock() JavaScript function using setInterval to display the current date and live time in the footer, updating every second. | Implemented and documented dynamic (real-time) content. |

| About Us Page | New Founders Section: Added a new founders section with placeholder images (.founder-img) and accompanying CSS to display two founder profiles with circular images and brief descriptions. | Development Documentation (New Feature) |


🚀 New Features & Major Updates
3. Interactive Elements & User Interface (Accordion, Search)
| Description | Files Affected |


| Implemented and documented Javascript interactive elements (Accordions) | Added an Accordion structure to the flower cards on the Flower Types page. This allows users to expand/collapse sections for "Growing & Care Tips" and "Symbolism & Uses," improving content density and user experience. | Flower Types.html, style.css |

| Implemented the search feature | Introduced a real-time Search Feature on the Flower Types page navigation. The accompanying JavaScript filters the flower cards dynamically as the user types, based on the flower's title and description. | Flower Types.html |

| Implemented and documented dynamic (real-time) content | Added a script to the homepage footer to display the Current Date and Time for Polokwane, South Africa (Africa/Johannesburg timezone), providing a dynamic content element that updates every second. | index.html |
4. Form Validation & User Feedback
| Description | Files Affected |


| Enquiry form with Javascript input validation and user feedback | Implemented client-side JavaScript validation for Name, Email (regex check), and Message length. The form prevents submission on failure and provides inline error messages and a general feedback banner. | enquiry.html, style.css |

| Contact form with Javascript input validation, email recipient processing and feedback | Implemented client-side JavaScript validation for Name, Email, and Message length. Logic includes simulated successful submission feedback. Note: Email recipient processing requires server-side code (e.g., PHP), which is documented as the next server-side implementation step. | Contact.html, style.css |

| CSS Styles for Feedback | Added .error-message and .success-message classes to style.css to visually handle feedback for both the Enquiry and Contact forms. | style.css |

5. Search Engine Optimization (SEO)
|  Description | Files Affected |

| Implemented SEO meta tags (keywords, description) | Added specific <meta name="description" ...> and <meta name="keywords" ...> tags to the <head> section of every page, ensuring search engines can better categorize the website content. Descriptions are unique and tailored to the content of each page (Home, About Us, Flower Types, Enquiry, Contact). | index.html, About Us.html, Flower Types.html, enquiry.html, Contact.html |

6. Code Maintenance and Structure
| Change | Description | Files Affected |


| Form Element Identification | Added unique id attributes to form elements (<form>, <input>, <p> for errors) in both enquiry.html and Contact.html to facilitate non-conflicting JavaScript manipulation. | enquiry.html, Contact.html |

| Interactive Element Documentation | Added clear comments within the <script> tags to separate and document the new interactive logic (Search, Accordion, Dynamic Time) from existing or other planned scripts. | All relevant HTML files |
