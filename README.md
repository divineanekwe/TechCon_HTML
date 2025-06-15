# TechCon_HTML

This repository contains the HTML files for the TechCon 2024 conference website. The project focuses on building a multi-page website using semantic HTML5 elements, ensuring accessibility, and implementing standard web page structures.

## How to View

Since these are static HTML files, you can view them directly in any web browser. Simply navigate to the file in your local file system and open it.

**Example:**

Double-click `index.html` (or `about.html`, `schedule.html`, etc.) in your file explorer, or drag and drop the file into your browser.

## Directory Structure

* `techcon_website/`: Contains all the HTML files for the TechCon 2024 conference website.

## Tasks Overview

### 0. Building the Homepage for TechCon 2024 Conference Website

**Objective:**
Create the homepage (`index.html`) for the TechCon 2024 conference website, demonstrating effective use of HTML structure, embedding media, and designing with accessibility standards.

**Requirements:**
* **Header:**
    * Use a `<header>` tag to contain the top part of the page.
    * Include the conference name within an `<h1>` tag.
    * Implement a navigation menu using a `<nav>` tag with links (`<a>` tags) to other pages: About, Schedule, Register, and Contact. Ensure each link points to `about.html`, `schedule.html`, `register.html`, `contact.html` respectively.
* **Main Section:**
    * Utilize a `<main>` tag to define the dominant content of the webpage.
    * Within the main section, use a `<section>` tag to introduce the conference. This section should include:
        * A brief paragraph (`<p>`) describing the event.
        * An embedded promotional video using the `<video>` tag with controls enabled (ensure accessibility with subtitles/description).
* **Footer:**
    * Use a `<footer>` tag for the bottom part of the webpage.
    * Include copyright information relevant to the event and the current year, explicitly adding the text "copyright".

**File:** `techcon_website/index.html`

---

### 1. Creating the About Page for TechCon 2024 Conference Website

**Objective:**
Develop the About page (`about.html`) for the TechCon 2024 conference, highlighting the history, mission, and notable past speakers of the conference through well-structured HTML content and embedded media.

**Requirements:**
* **Header:**
    * Utilize a `<header>` tag to contain the top section of the page.
    * Place the page title “About TechCon 2024” within an `<h1>` tag.
    * Include the same navigation menu as the homepage using a `<nav>` tag, with links to Home, Schedule, Register, and Contact.
* **Main Content:**
    * Use a `<main>` tag to define the core content of the webpage.
    * Divide the content into multiple `<article>` sections, each dedicated to a different aspect of the conference:
        * **History:** An article detailing the origins and evolution of TechCon, enhanced with historical images (`<img>` tags with appropriate `alt` attributes).
        * **Mission:** A section that explains the goals and driving principles of the conference. Include any relevant motivational images or icons.
        * **Past Speakers:** Showcase notable speakers from previous years with short biographies and their contributions to the tech industry. Use `<img>` tags for speaker photos, ensuring each has an `alt` attribute.
* **Footer:**
    * The footer should be consistent across all pages, using a `<footer>` tag.
    * Include copyright information, mirroring the layout and content from the homepage.

**File:** `techcon_website/about.html`

---

### 2. Designing the Schedule Page for TechCon 2024 Conference Website

**Objective:**
Create the Schedule page (`schedule.html`) for TechCon 2024, providing a detailed and accessible timetable of events, sessions, and speakers, using a structured HTML table format.

**Requirements:**
* **Header:**
    * Include a `<header>` tag containing the page title “Schedule for TechCon 2024” displayed within an `<h1>` tag.
    * Implement a consistent navigation menu as in previous pages using a `<nav>` tag, linking to Home, About, Register, and Contact.
* **Main Content:**
    * Utilize a `<main>` tag to centralize the primary content of the schedule.
    * Construct a detailed schedule using a `<table>`:
        * **Headers:** Use `<th>` tags for columns such as “Time”, “Session”, and “Speaker”, applying `scope` attributes.
        * **Data Rows:** Populate with `<td>` tags containing the specifics of each session.
        * **Caption:** Include a `<caption>` that succinctly describes the table (e.g., “Detailed Schedule of Events for TechCon 2024”). This should be one line of code for checker purposes.
* **Footer:**
    * Use a `<footer>` tag consistent with the rest of the website.
    * Include copyright information similar to other pages.

**File:** `techcon_website/schedule.html`

---

### 3. Building the Register Page for TechCon 2024 Conference Website

**Objective:**
Create the Register page (`register.html`) for TechCon 2024, designing a user-friendly and accessible registration form that collects essential attendee information.

**Requirements:**
* **Header:**
    * Include a `<header>` tag with the page title “Register for TechCon 2024” encapsulated in an `<h1>` tag.
    * Implement the standard navigation menu using a `<nav>` tag, linking to Home, About, Schedule, and Contact.
* **Main Content:**
    * Use a `<main>` tag for the central content.
    * Design a registration form using a `<form>` tag:
        * **Field for Name:** Include an `<input>` `type="text"` for the attendee’s full name with a corresponding `<label>`.
        * **Field for Email:** Incorporate an `<input>` `type="email"` for email addresses, paired with a `<label>`.
        * **Password Fields:** Add fields for password and password confirmation using `<input>` `type="password"`, each with labels.
        * **Checkbox for Terms and Conditions:** Provide a checkbox `<input>` `type="checkbox"` for user agreement, clearly described alongside.
        * **Submit Button:** Place a `<button>` `type="submit"`, labeled appropriately (e.g., “Register Now”).
* **Footer:**
    * Consistently use a `<footer>` tag across all pages.
    * Repeat the copyright information found on other pages.

**File:** `techcon_website/register.html`

---

### 4. Constructing the Contact Page for TechCon 2024 Conference Website

**Objective:**
Develop the Contact page (`contact.html`) for TechCon 2024, featuring comprehensive contact details, interactive elements like an embedded map, and a “Contact Us” form, ensuring ease of communication for attendees.

**Requirements:**
* **Header:**
    * Incorporate a `<header>` tag that includes the page title “Contact Us” within an `<h1>` tag.
    * Feature the consistent navigation menu using a `<nav>` tag with links to Home, About, Schedule, and Register.
* **Main Content:**
    * Use a `<main>` tag to house the primary content of the page.
    * **Detail contact information, including:**
        * **Email Address:** Display an official conference email using `<a>` tags configured with `href="mailto:email@example.com"` (use the example email given as is - don’t modify it).
        * **Social Media Links:** List clickable icons or text linked to the conference’s social media profiles using `<a>` tags with `href` attributes and `target="_blank"`.
        * **Embedded Google Maps:** Location of the conference venue using an `<iframe>`. This map should be responsive and provide a clear view of the venue’s location.
    * **Contact Us Form:**
        * Include a form `<form>` that asks for the user’s name, email, and a message.
        * **Fields to include:**
            * Name: `<input type="text">` with a corresponding `<label>`.
            * Email: `<input type="email">` with a corresponding `<label>`.
            * Message: `<textarea>` with a corresponding `<label>`.
            * Submit Button: `<button type="submit">` labeled “Send Message”.
* **Footer:**
    * Employ a `<footer>` tag that is consistent across all pages.
    * Include copyright information, echoing the setup found on other pages.

**File:** `techcon_website/contact.html`
