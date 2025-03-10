# insider-bootcamp

# Project Overview

This repository contains two web-based projects that utilize HTML, CSS, JavaScript, and jQuery for dynamic interactivity.

## 1. **Student Table Management (day1-hw.html)**
This project implements a simple student management system where users can:
- View a list of students in a table.
- Add new students with their names and class information.
- Highlight student rows by clicking on them.
- Delete students from the table dynamically.
- Input validation to prevent empty submissions.

The project utilizes **jQuery** to manipulate the DOM, handle user interactions, and dynamically update the student list.

## 2. **Post Loader (day2-hw.html)**
This project fetches and displays posts from a remote API (`jsonplaceholder.typicode.com`). It features:
- Automatic loading of the first 5 posts on page load.
- Infinite scrolling: More posts load dynamically when the user reaches the bottom of the page.
- A loading indicator while data is being fetched.
- Error handling to alert users if the data request fails.

The project makes use of **AJAX (jQuery's `.get()` method)** for fetching posts and updating the page dynamically.

### Requirements
- A modern web browser
- Internet connection (for API requests in `day2-hw.html`)
- No additional dependencies (jQuery is included via CDN)
