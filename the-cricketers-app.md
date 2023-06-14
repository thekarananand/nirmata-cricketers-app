# The Cricketers App

## What are the requirements?

#### Screen: Cricketers

- Display the list of cricketers.
- The list should have pagination with page size of 10.
- Each item in the list should display below details
	- Name
	- Type
	- Points
	- Rank
	- Age
- The list should support sorted by
	- Name
	- Rank
	- Age
- The list should support filter by
	- Type
- The list should support search by Name
- Screen should retain the filter & search criteria on screen refresh
- Cricketer Name should be a link which should open the Cricketer Details screen

#### Screen: Cricketer Details

- The details screen should display below details
	- Name
	- Description
	- Type
	- Points
	- Rank
	- Date of Birth
	- Age
- The details screen should have a `Back to Cricketers` button/link

## How to get the list of players?

The list of Cricketers can be accessed from files `get-players.js` or `get-players.ts`. These files export a method which resolves a promise and returns the list of players.

## What tech stack to be used?

- React JS 16+
- The app can be setup using tools like CreateReactApp, Vite etc
- Bootstrap/AntD/MaterialUI or any other UI library

This is a minimum tech stack. You are free to add other stacks, like Icons, Styling etc.

## What gives bonus points?

- Typescript
- Unit tests

## What is assessed?

- Complete implementation of the requirements, ideally 100%
- Coding principals used
- Components/hooks structure
- Cleanliness of the code
- Appearance & aesthetics

**Use your own imagination to design the screens as you would like to!**
