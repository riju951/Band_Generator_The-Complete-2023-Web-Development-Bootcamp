# Band Generator Project

This project was created by following the instructions provided in "The Complete 2023 Web Development Bootcamp by Angela Yu". It is a dynamic website developed using EJS, allowing users to generate a random band name by clicking the button.

![image](https://github.com/riju951/Band_Generator_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/72a26792-55f5-41f7-b703-3fc3c3745022)

## Steps to Set Up and Run the Project

Follow these steps to set up and run the project locally:

1. Clone the repository.
2. Run `npm i` to install the dependencies.
3. Execute `node index.js` to run the project on localhost.

## Project Overview

The project involves the following steps:

### Step 1 - Setting Up Routes and Rendering

- Configure the GET route to render the `index.ejs` file.

### Step 2 - Implementing Band Name Generation

- Create functionality for generating a band name.
- When the "Generate Name" button in `index.ejs` is clicked, randomly select an adjective from the `adj` constant and a noun from the `noun` constant.
- Send the `index.ejs` as a response and include the selected adjective and noun in the `res.render`.
- Test to ensure that the randomly chosen words display in the `<h1>` element in `index.ejs`.

### Step 3 - Styling the Website

- Utilize static CSS files to add styling.
- Include the CSS link in `header.ejs`.
- Implement header and footer as partials.

### Step 4 - Adding Dynamic Content

- Add the current year dynamically to the footer using JavaScript.
- Update the `<h1>` in `index.ejs` to display the chosen adjective and noun when sent.
- If no adjective and noun are sent initially, display a default `<h1>`.

## How to Use

Once the project is set up locally, access the website through the localhost URL. Click the "Generate Name" button to generate a random band name.

## Folder Structure

The structure of the project folders is as follows:

```
Band_Generator_Project/
├── views/
│   ├── partials/
│   │   ├── header.ejs
│   │   └── footer.ejs
│   └── index.ejs
├── public/
│   └── styles/
│       └── style.css
├── index.js
├── package.json
└── README.md
```

