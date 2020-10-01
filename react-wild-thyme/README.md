# Wild Thyme Gourmet

A dynamic restaurant page

---------------

## Objectives

### Learning Objectives

After completing this assignment, you should:

- Understand how to design and execute a front end application given ambiguous requirements by a client
- Understand how React works to create a dynamic frontend application

### Performance Objectives

After completing this assignment, you should be able to:

- Create wireframes and an outline of objects needed as part of the planning process when making a complex front end application
- Execute client requirements to make a complete application

## Details

### Deliverables

* A repo containing a create-react-app project

## I'm a Full Stack Developer Mode

A "client" has approached you and asked you to help them build a web presence. They are a local restaurant called Wild Thyme Gourmet. They don't know anything about the Internet, but they know they need a web page. They want an interactive menu that displays all of their food choices with prices, descriptions, etc. They also want the customer to be able to select menu items and create an order with a total price. When the user saves the order, it should alert the user that their order was placed and empty the current order.

Use create-react-app to to create an updating menu page. See Additional Resources for an example of an actual restaurant page.

### Tasks

#### Getting Started (Thinking in React: Mock + Step 1)
- [ ] Setup the scaffolding
- [ ] Setup a mock of the page
- [ ] Produce static data for the menu items
- [ ] Produce a functional static mockup

#### Menu (Thinking in React: Step 2, 3, & 4)
- [ ] `console.log` the static JSON for the menu items
- [ ] Render a component for each menu item, not according to category.
- [ ] Define a FoodItem component
- [ ] Define a FoodList component that calls FoodItem
- [ ] `console.log` the food object when I click on its price button

#### Order view
- [ ] Define an Order component
- [ ] Render an instance of Order component
- [ ] Define an order object in your application state
- [ ] Pass the order to the Order component
- [ ] `console.log` the order when the user clicks on the food's price
- [ ] Add the food object to the order
- [ ] In Order, `console.log` the order
- [ ] In Order, `console.log` a food model every time a food model is added to the order
- [ ] Render the data from the order every time the order is updated
- [ ] In Order, define a `subtotal` function that calculates the total price
- [ ] `console.log`, then render, every time the order is updated

## Hey Mikey, I Think He Likes It Mode
- [ ] Organize menu items by category
- [ ] Add a navigation bar that allows the user to toggle between the Menu page and the Order page

## Additional Resources
- [Example of a real restaurant app](https://eatstreet.com/atlanta-ga/restaurants/the-flying-biscuit-cafe-midtown)
