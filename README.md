# Simple CMS with Node.js and Mustache

This is a simple CMS (Content Management System) project developed with Node.js and Mustache. The goal is to provide an easy-to-use platform for managing web page content.

## Features

1. **Login System**: The system has a login mechanism for the content administrator. The credentials are stored in a `.env` configuration file.

2. **Dynamic Page Creation**: Logged-in administrators can create new pages by specifying the URL and desired content. The content can include HTML.

3. **Content Editing**: Administrators can edit the content of any page, but the defined URL cannot be modified.

4. **Page Deletion**: Administrators can delete pages, permanently removing their content and route from the system.

5. **Home Page**: The home page lists all created pages and provides links to access them. No login required to view the home page.

6. **Page Viewer**: Anyone can access the content of a page from the URL defined when creating the page.

7. **Extra Feature**: Our CMS has an extra feature of adding multiple admin users.

## How to Use

1. Clone this repository.
2. Install the dependencies with `npm install`.
3. Configure the `.env` file with your admin credentials.
4. Start the server with `npm start`.
5. Access `http://localhost:3000` in your browser.
