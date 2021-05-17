<h1 align="center">
  MUMBLE
</h1>

<p align="center">An Open Source Social Media Platform and Public Forum for Questions and Discussions, built for Developers.</p>

<div align="center">

<a href="https://discord.gg/9Du4KUY3dE">![Mumble Community](https://img.shields.io/discord/825371211399692308?label=Mumble%20Community&style=for-the-badge&logo=Discord)</a>
<a href="https://mumble.dev">![Mumble](https://img.shields.io/badge/Mumble-Live%20Demo-9cf?style=for-the-badge)</a>
<a href="https://github.com/divanov11/Mumble">![Mumble Repository](https://img.shields.io/badge/Mumble-Repository-orange?style=for-the-badge)</a>

</div>

## Directory Structure

You can find project information, licence, contribution guidelines, style guides and more on the root directory. However, the main source code for the Mumble project lives on the `frontend` folder. This project is create with `create-react-app` and we respect what `create-react-app` provides us by default. Although in future, the directory structures can be changed a bit, but for the most part the current directory structure looks like this:

```sh
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

```Shell
git clone https://github.com/divanov11/mumble
```

## Frontend Instructions (Create React App) :

---> Navigate to the `frontend/` directory

```Shell
cd Mumble && cd frontend
```

---> Install the project dependencies

```Shell
npm install
```

---> Start the development server on localhost:3000

```Shell
npm start
```

## Want to Contribute?

Check out the [contributing guide](https://github.com/divanov11/Mumble/blob/master/CONTRIBUTING.md).
Also if you are looking for a complete style guides, please refer to [**Mumble Style Guide**](STYLE_GUIDE.md).
We highly recommend to go through the guideline before start contributing.

