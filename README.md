# GoTab Coding Assessment

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
