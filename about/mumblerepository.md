---
description: >-
  An Open Source Social Media Platform and Public Forum for Questions and
  Discussions, built for Developers.
---

# Mumble Repository

## Directory Structure

You can find project information, licence, contribution guidelines, style guides and more on the root directory. However, the main source code for the Mumble project lives on the `frontend` folder. This project is create with `create-react-app` and we respect what `create-react-app` provides us by default. Although in future, the directory structures can be changed a bit, but for the most part the current directory structure looks like this:

```bash
|-- cypress
|-- node_modules
|-- public
|-- src
    |-- __tests__
    |   |-- components
    |-- actions
    |-- assets
    |   |-- images
    |   |-- logo
    |-- common
    |-- components
    |-- constants
    |-- data
    |   |-- images
    |-- hooks
    |-- pages
    |-- reducers
    |-- services
    |-- styles
    |   |-- common
    |   |-- components
    |-- uikit
    |   |-- scripts
    |   |-- styles
    |       |-- modules
    |-- utilities
```

## Download & Setup Instructions :

Before downloading the project, check to make sure you meet the [project's requirements.](https://github.com/divanov11/Mumble/blob/master/REQUIREMENTS.md)

Clone the project. This will download the GitHub respository files onto your local machine.

```text
git clone https://github.com/divanov11/mumble
```

## Frontend Instructions \(Create React App\) :

---&gt; Navigate to the `frontend/` directory

```text
cd Mumble && cd frontend
```

---&gt; Install the project dependencies

```text
npm install
```

---&gt; Start the development server on localhost:3000

```text
npm start
```

## Want to Contribute?

Check out the [contributing guide](https://github.com/divanov11/Mumble/blob/master/CONTRIBUTING.md). Also if you are looking for a complete style guides, please refer to [**Mumble Style Guide**](https://github.com/MidouWebDev/Mumble-docs/tree/e7e8a918ac17a819790344c72d376133019cf9d5/About%20Mumble%20Project/STYLE_GUIDE.md). We highly recommend to go through the guideline before start contributing.

