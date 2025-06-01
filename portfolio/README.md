# Personal Portfolio Website

This project creates a foundational personal portfolio website using semantic HTML5, designed to showcase a software engineer's skills and projects.

## Project Structure

The main file for this project is index.html, located in the portfolio directory.

## Page Structure and Semantic HTML

The index.html file adheres to modern web standards, utilizing semantic HTML5 elements for clear structure and accessibility.

### Document Declaration: Starts with <!DOCTYPE html>.

### Language Definition: The <html> tag includes lang="en".

## Head Section:

meta charset="utf-8" for proper character encoding.

<title> element formatted as [Your Full Name] - Personal Portfolio.

### Body Structure: The <body> of the document is organized with the following semantic HTML5 elements, in order:

<header>

<nav>

<section> (for Introduction, Projects, About Me, Contact)

<article> (nested within the Projects section for individual projects)

<footer>

## Content Breakdown
### Header

Contains an <h1> element displaying your name.

Includes a <p> tag with the professional statement: "A software engineer solving real-world problems using tech."

Navigation Bar (<nav>)
A <ul> list containing <li> elements.

Each <li> holds an <a> tag linking to different sections of the webpage using href attributes pointing to corresponding section IDs (e.g., #introduction, #projects, #about, #contact).

Content Sections
Each major content area is encapsulated within a <section> element, identified by a unique id for navigation.

## Introduction Section (<section id="introduction">)

<h2> heading: "Introduction"

<p> tag: A brief description of yourself.

## Projects Section (<section id="projects">)

<h2> heading: "Projects"

Each individual project is wrapped in an <article> tag with the class project.

Each <article> contains:

<h3> for the project title.

<p> for the project description.

<a> tag linking to the project, with target="_blank" to open in a new tab.

## About Me Section (<section id="about">)

<h2> heading: "About Me"

Paragraphs or lists detailing your background, skills, or hobbies.

## Contact Section (<section id="contact">)

<h2> heading: "Contact"

An email link using <a href="mailto:your.email@example.com">.

Links to your LinkedIn and GitHub profiles, both opening in a new tab (target="_blank").

# Footer
Contains a <p> element with copyright information (e.g., &copy; 2024 Your Name).
