# SKY TRAVEL COMPANION - React Storybook libraries

Assigned from:
[GA users only](https://git.generalassemb.ly/dc-wdi-react-redux/component-library-project)

## Description w/ Features
Sky travel companion UI design is built using React and Storybook. There are three pages: Home, SIGN UP, and LOG IN. The Home page includes the logo and the buttons to the two other pages. The SIGN UP page includes  the logo and 4 text boxes for the user to enter their Full Name, Email, Password and password confirmation. Lastly, the LOG IN page incldes the logo and two text boxes to gather the user's Full Name and Password.


## Mock App - Sky Travel Companion
  ![image](https://i.imgur.com/EOFHA37.png)

## Technologies
> React, Storybook, and other front-end frameworks

### Prerequisites to Build - React, Storybook, and Vanilla php

Requirements for the software and other tools to build, test and push 
- [HTML, CSS, Javascript, and the DOM](https://www.w3schools.com/js/js_htmldom.asp)
- [React](https://reactjs.org/)
- [Storybook](https://storybook.js.org/docs/react/get-started/introduction)

## REACT 

React allows developers to spend less time making tedious and/or repetitive codes and adjustments across projects by allowing pieces of code to be stored into a library.
Some major features included in the HTML is: 
> 1. button
> 2. headers
> 2. pages
> 4. text-input (collect password from users)


### What are Components?
React lets you define components as classes or functions. Components defined as classes currently provide more features which are described in detail on this page. To define a React component class, you need to extend React.Component. For example:

    class Welcome extends React.Component {
      render() {
        return <h1>Hello, {this.props.name}</h1>;
      }
    }

Ways components can be utilized
> 1. 
> 2. 
> 3. 
> 4. 

## Storybook
### What are Stories?
A story captures the rendered state of a UI component. Developers write multiple stories per component that describe all the “interesting” states a component can support. The CLI created example components that demonstrate the types of components you can build with Storybook: Button, Header, and Page.

### An Example from the component-library
One of the disnguishing features of Storybook is that things cannot be exported more than once. For example, a button can only be imported once, but more buttons can be added to the page by binding the button template. See the example below:

    export const Home= Template.bind({});

    export const SignUp = Template.bind({});

    SignUp.play = async ({ canvasElement }) => {
      const canvas = within(canvasElement);
      const loginButton = await canvas.getByRole('button', { name: /Log in/i });
      await userEvent.click(loginButton);
    };

    export const LogIn = Template.bind({});


### Installation Instructions / Getting Started
To set up Sofware Star Trivia application, follow these steps:
>(1) FORK this repository
>(2) CLONE this repository to your local
>(3) NEW local branch
>(4) OPEN, edit, and commit

### CONTRIBUTION GUIDELINES
Follow these Links:
> 1. Main repository: ([https://github.com/TREYCSE/triviaGame](https://github.com/TREYCSE/component-library/blob/main/README.md))
> 2. Issue Tracker: ([https://docs.google.com/spreadsheets/d/1h3rOtnA9zg10dT5oqklCbmK6vP9EDftnQArKYl7rBWg/edit#gid=0](https://docs.google.com/spreadsheets/d/1h3rOtnA9zg10dT5oqklCbmK6vP9EDftnQArKYl7rBWg/edit#gid=1699520055))





#### Built With
  - [Contributor Covenant](https://www.contributor-covenant.org/) - Used for the Code of Conduct
  - [Creative Commons](https://creativecommons.org/) - Used to choose the license

#### Versioning
We use [Semantic Versioning](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/PurpleBooth/a-good-readme-template/tags).

#### Authors
  - **Billie Thompson** - *Provided README Template* - [PurpleBooth](https://github.com/PurpleBooth)

