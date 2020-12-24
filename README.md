# React Redux Typescript Webpack Starter Kit

## Requirements

- node `8.9.0`
- npm `^6.0.1`

## Installation

Create a new project based on `react-redux-typescript-webpack-starter-kit` by doing the following:

```bash
$ git clone https://github.com/sayeed09/React-Redux-Typescript-Webpack-Starter-App.git <my-project-name>
$ cd <my-project-name>
```

Create your .env file and populate the relevant values based on the sample file .env-sample

Install dependencies

```bash
$ npm install
$ npm run start      # Compiles and launches application
```


## Project Structure

The project structure presented in this starter kit is outlined below. This structure is only meant to serve as a guide.

```
├── public                # Transpiled react source code
└──src                    # React-redux related files
   ├── assets             # Assests - Images, stylesheets and
   │   ├── fonts          # Custom fonts for the application
   │   ├── images         # Images
   │   └── sass           # CSS files
   ├── components         # Collections of components
   ├── redux              # Collections of reducers/constants/actions
   │   ├── actions        # Actions
   │   ├── reducers       # Reducers
   │   ├── constants.js   # Constants file
   │   └── store.js       # Redux store instance
   └── utils              # Utitily functions used in the application
```

## Contributing

I am more than happy to accept contributions to the project. Contributions can be in the form of feedback, bug reports or even better - pull requests :)
