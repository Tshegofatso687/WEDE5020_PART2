# The Second Chance Youth Foundation

## Project Description

The Second Chance Youth Foundation is a non-profit organisation website designed to support young adults who are leaving children's homes, foster care, and other forms of alternative care.

The website provides information about the organisation, the services it offers, how young adults can get involved, and how users can contact the organisation or make an enquiry.

The website was created using HTML5 and CSS3. The design focuses on being clear, simple, consistent, user-friendly, and responsive across different screen sizes.

---

## Website Pages

The website consists of five main pages:

### Home Page
**File:** `index.html`

The Home page introduces The Second Chance Youth Foundation and provides information about its purpose and how people can become involved.

### About Us Page
**File:** `about.html`

The About Us page provides information about the organisation, including its history, mission, vision, and values.

### Services Page
**File:** `services.html`

The Services page describes the support provided by the organisation. These services include:

- Accommodation Support
- Career Guidance
- Educational Support
- Life-Skills Training
- Mentorship
- Employment Assistance

### Enquiry Page
**File:** `enquiry.html`

The Enquiry page contains a form that allows users to provide their details and submit an enquiry.

### Contact Page
**File:** `contact.html`

The Contact page provides contact information and a contact form for users who would like to communicate with the organisation.

---

## Technologies Used

The following technologies were used to develop the website:

- HTML5
- CSS3
- CSS Flexbox
- CSS Grid
- CSS Media Queries
- Responsive Web Design
- GitHub for version control

---

# Part 1 Feedback and Changes

Feedback received from Part 1 was used to improve the website for Part 2.

The following changes were made:

1. The website file structure was improved by creating a separate `css` folder for the external stylesheet.
2. An external `style.css` file was created and linked to all five HTML pages.
3. Inline CSS styling was removed and replaced with external CSS.
4. The navigation was made consistent across all five pages.
5. An active navigation style was added to show which page the user is currently viewing.
6. Unnecessary `<br>` elements were removed and spacing was handled using CSS.
7. The irrelevant price table on the Home page was removed because it was not relevant to the purpose of the organisation.
8. Semantic HTML elements such as `header`, `nav`, `main`, `section`, `article`, and `footer` were used to improve the page structure.
9. Comments were added to the HTML code to make different sections easier to identify.
10. The styling and layout were made consistent across all pages.
11. Forms were given a consistent structure and styling.
12. The website was improved to work on different screen sizes.

---

# Part 2 CSS Design

## External Stylesheet

An external CSS stylesheet named `style.css` was created inside the `css` folder.

The stylesheet is linked to all five HTML pages using:

`style.css`

Using an external stylesheet allows the same styling to be applied consistently throughout the website.

## Base Styles

The CSS includes a reset for margins, padding, and box sizing.

Default styles were also added for:

- Body text
- Font family
- Font size
- Line height
- Background colour
- Text colour
- Headings
- Images

## Typography

Typography was added to make the website readable and consistent.

The stylesheet includes:

- Font families
- Font sizes
- Font weights
- Line heights
- Letter spacing
- Different heading sizes

Relative units such as `rem` were used for several typography values.

## Layout

CSS Flexbox and CSS Grid were used to create the website layouts.

Flexbox was used for areas such as:

- Header content
- Navigation
- Button groups

CSS Grid was used for areas such as:

- Service cards
- Contact cards

The layouts were designed to change when the screen size becomes smaller.

## Colour and Decoration

A consistent colour scheme was applied throughout the website.

The CSS includes:

- Background colours
- Text colours
- Borders
- Border radius
- Box shadows
- Button styling
- Card styling

These styles help create a consistent appearance across the different pages.

## Interactive States

Pseudo-classes were added to improve interaction with the website.

The stylesheet includes:

- `:hover`
- `:focus`
- `:active`

These states are used mainly for navigation links and buttons.

---

# Responsive Design

Responsive design was added to allow the website to adjust to different screen sizes.

The website includes layouts for:

- Desktop
- Tablet
- Mobile

Media queries were used to change the layout when the screen becomes smaller.

## Desktop

On larger screens, content such as service cards and contact cards can be displayed in multiple columns.

## Tablet

At tablet sizes, the number of columns is reduced and spacing and typography are adjusted to fit the smaller screen.

## Mobile

At mobile sizes:

- Content changes to a single-column layout.
- Navigation items are adjusted to fit the smaller screen.
- Buttons can take up the available width.
- Font sizes are reduced where necessary.
- Header elements are stacked.
- Cards are displayed in a single column.

Images are also styled so that they scale within their containers and do not overflow the page.

---

# Testing

The website was tested in a web browser to check that the pages, navigation, forms, styling, and responsive layouts work correctly.

The following were tested:

- Home page
- About Us page
- Services page
- Enquiry page
- Contact page
- Navigation links
- Buttons
- Form fields
- CSS styling
- Desktop layout
- Tablet layout
- Mobile layout

Browser developer tools were used to check how the website changes at different screen sizes.

## Responsive Testing Evidence

Screenshots of the website at different screen sizes are included as evidence of responsive testing.

The screenshots show:

- Desktop view
- Tablet view
- Mobile view

---

# File and Folder Structure

The project uses the following structure:

```text
Second-Chance-Youth-Foundation/
│
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
├── logo.png
│
├── css/
│   └── style.css
│
└── README.md

---

**# References**
```text
Stockcake, no date. *Children holding hands*. No city of publication: Stockcake.


