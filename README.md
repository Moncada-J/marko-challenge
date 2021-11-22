# GoTab Coding Assessment

## Technologies Used

Marko.js, JavaScript, CSS, Bootstrap 

## Application Features

- A clean and user friendly UI with GoTab's complimentary color scheme
- Cards displaying gross, net and autogratuity total figures
- Monetary values have been converted to the appropriate decimal/cent format to display figures more accurately 
- A sortable and searchable data table that tracks product inventory and sales
- Responsive and flexible design that is friendly on all devices including: Desktops, Mobile Phones and Ipads/Tablets.

## Future Enhancements 
* Full Stack/Back End integrations (server-side routing, server and database connection, etc)
*  Light Mode/Dark Mode toggle for a better UI
*  "Export" option for a user to export the shown data in pdf or excel format
*  Report generation (on a different page/part of routing), breaking down net and gross, on a quarterly and yearly basis
*  A more developed dashboard set up with figures, graphs, charts for rendered data

## Approx. Time Spent
1-2 days

## Made with 💜 by Jessalynn Moncada

---
## Instructions
Develop a responsive web app that displays sales data (the target audience would be restaurant/bar/venue managers, operators, servers, etc.).
You are free to style it however you want and display the data in any way you want but you must meet at least one of the following requirements:

### 1. Display the following totals (these should be a sum from the entire list of data)
- "Gross Sales" (total amount spent by customer)
- "Net Sales" (total amount spent by customer minus tips)
- "Autogratuity"
- "Tax"
- "Tips"

### 2. Display a breakdown of aggregated items sold
- This should at least show quantity and revenue for each item


---


## Technical Requirements
- Page must be responsive and legible on mobile, tablet, and desktop screen of varying sizes.
- Use the provided seed data (`./src/seed.json`).
  - NOTE: All monetary amounts are represented in cents (i.e. 500 is $5.00).

## Optional
- Use bootstrap classes for styling; CDN is already provided (see additional notes below for documentation).


---


# Installation
```
npm install
npm run dev
```

### Requirements
node v12+  
npm v6+

## Overview
This project is powered by `@marko/serve` and `@marko/build`.

- Run `npm run dev` to start the development server
- Run `npm run build` to build a production-ready node.js server
- Run `npm start` to run the production server
- Remove any unnecessary boilerplate code before submitting your assessment

## Additional Notes

- Pages map to the directory structure. You can add additional pages by creating files/directories under `src/pages` with `.marko` files.  Learn more in the [`@marko/serve` docs](https://github.com/marko-js/cli/blob/master/packages/serve/README.md).
- For adding state see [this marko documentation](https://markojs.com/docs/getting-started/#adding-state).
- For more information regarding bootstrap see [this bootstrap documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/).
