# Description

This is a school project website, featuring a packaging company brand (TÓKI) selling b2b and b2c solutions.

## Development

We have used the frontend framework Astro and the open source database system Supabase.
Within Astro we have used:

- HTML: Edit the structure and content in .html files

- CSS: Customize styling in .css files

- JavaScript: Change interactivity in .js files

We have build our site in Visual Studio Code.

## Authors

Signe Storgaard (https://github.com/sist0002)

Kia Vinther (https://github.com/kivi0001)

Kamilla Christiansen (https://github.com/kach0006)

Ida Petersen (https://github.com/idax3451)

## Project structure

Images, icons and fonts are kept in separate folders within the "assets" folder.

CSS documents are kept in the "css" folder.

Components are kept in the 'components' folder.

Layouts are kept in the 'layouts' folder.

Pages are kept in the 'pages' folder.

## Script linking

Javascript will be placed locally within each component, page or layout inside a <script/> tag in the following order:

- fences
- html
- css
- javascript

## Naming structure

With the exception of index.astro, all pages should be named the same as the intended
landing page title. Example: produkter.astro

Components will be named with upper camel case according to what component it is.
Example: component for a case section will be named CaseSection.astro.

English is our technical working language, and all classes and IDs should have English names.

The README.md should also be written in English.

In HTML, names consisting of multiple words should be connected with a hyphen symbol. Example:
product-container

In Javascript, names should be written in lower camel case. Example: productContainer

## API endpoints

We are fetching data from:
https://fhhfqfljilcjaaakodhw.supabase.co/rest/v1/cases (contains cases)
and
https://twfzmayntvnffeuqxncv.supabase.co/rest/v1/people (contains quote reviews)

## Git branches

The name of the Git branches published should reflect the feature or specific document worked on by
the developer. For example: product-cards-update

If the entire group has verbally agreed that an individual is setting up a specific feature or
document, branch names may be more vague.

## Workflow

Most work is divided into feature branches.

All team members must sync to the most recent copy of main before changes are made to shared across
several documents, such as general.css.

Team members must align on tasks, so that no more than one person is making changes to a document at
the same time.

When a push is made, the developer must leave a short description of the features or documents
added, or impacted by their changes.
