<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dylan751/booking-app-front-end">
  </a>

<h3 align="center">Booking App Front End</h3>

  <p align="center">
    The front-end part of the Booking app (Clone from <b>https://booking.com</b> project)
    <br />
    <a href="https://github.com/dylan751/booking-app-front-end"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/dylan751/booking-app-front-end">View Repo</a>
    ·
    <a href="https://github.com/dylan751/booking-app-front-end/issues">Report Bug</a>
    ·
    <a href="https://github.com/dylan751/booking-app-front-end/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

<p>Live domain: <strong>https://booking-app-front-end.vercel.app/</strong></p>

<img src="public/images/project-screenshot.png" />

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

### Built With

- [![React][react.js]][react-url]
- [![Node][node.js]][node-url]
- [![Express][express.js]][express-url]
- [![Module SASS][sass]][sass-url]
- [![AWS][aws]][aws-url]

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```
- yarn
  ```sh
  npm install --global yarn
  ```

### Installation

1. Get a API Domain, maybe using [AWS](https://aws.amazon.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/dylan751/booking-app-front-end.git
   ```
3. Install packages and dependencies (yarn)
   ```sh
   yarn install
   ```
4. Create a `.env.local` file, enter your API in `.env.local`
   ```js
   REACT_APP_API_ENDPOINT = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

How this project can be used. Additional screenshots, code examples and demos. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://booking.com)_

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Authentication / Users
- [x] Booking Feature
  - [x] Hotel Booking
  - [x] Room Booking
- [ ] Writting Blog Feature
- [ ] Comment Feature

See the [open issues](https://github.com/dylan751/booking-app-front-end/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
