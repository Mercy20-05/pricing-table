# Pricing Table - Task 12

## Project Overview

This project implements a responsive pricing table using HTML5 and CSS3.

It contains three pricing plans:

- Basic
- Pro
- Premium

The Pro plan is visually highlighted as the **Most Popular** plan.

## Objective

The objective of this project is to practice:

- CSS Flexbox/Grid layouts
- Responsive web design
- Card-based UI design
- CSS hover effects
- CSS transitions
- Media queries

## Technologies Used

- HTML5
- CSS3
- CSS Flexbox
- CSS Media Queries
- CSS Transitions
- CSS Hover Effects

## Project Structure

```text
pricing-table/
│
├── index.html
├── style.css
└── README.md
```

## Approach

### 1. HTML Structure

A semantic HTML structure was created for the pricing section.

Three pricing cards were added:

- Basic
- Pro
- Premium

Each card contains:

- Plan name
- Description
- Price
- Feature list
- Call-to-action button

### 2. Flexbox Layout

CSS Flexbox is used to arrange the three cards horizontally on larger screens.

```css
.pricing-container {
    display: flex;
    justify-content: center;
    gap: 25px;
}
```

### 3. Popular Plan

The Pro plan is highlighted using:

- A blue border
- A shadow
- A scale effect
- A "MOST POPULAR" badge
- A highlighted button

### 4. Hover Effects

Hover effects are applied to the pricing cards.

When the mouse pointer moves over a card, it moves upward and its shadow becomes stronger.

Buttons also change their background and text colors on hover.

### 5. Responsive Design

CSS media queries are used to make the pricing table responsive.

On desktop screens, the cards are displayed side-by-side.

On smaller screens, the cards are automatically stacked vertically.

## Deliverables

The project satisfies the required deliverables:

- Three pricing cards
- Highlighted popular plan
- Responsive stacking on small screens
- Hover effect on cards
- Hover effect on buttons
- Flexbox-based layout

## Outcome

The completed project provides a clean, modern and responsive pricing table.

The three plans are clearly displayed and the Pro plan is visually distinguished as the popular plan.

The layout works across:

- Desktop
- Tablet
- Mobile

This project demonstrates practical knowledge of HTML5 and CSS3, especially Flexbox, responsive design, media queries, shadows, borders, transitions and hover effects.

## How to Run

1. Create a folder named `pricing-table`.
2. Create the following files:

```text
index.html
style.css
README.md
```

3. Paste the respective code into each file.
4. Open `index.html` in a web browser.

You can also use the **Live Server** extension in VS Code.

## Future Enhancements

The project can be extended by adding:

- Monthly/yearly pricing toggle
- JavaScript-based plan selection
- Login and registration
- Backend integration
- Payment integration
- Dark mode
- Additional pricing plans
- Accessibility improvements
- More advanced animations

## Conclusion

The Pricing Table project successfully demonstrates how HTML5 and CSS3 can be used to build a responsive and interactive pricing interface.

The project fulfills the requirements of Task 12 by providing three pricing cards, a highlighted popular plan, responsive stacking and hover effects.