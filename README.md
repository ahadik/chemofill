![ChemFill](https://github.com/ahadik/chemfill/blob/master/docs/banner-light.png)

# ChemFill

This Sketch Data Plugin fetches a random molecule from the ChEMBL (https://www.ebi.ac.uk/chembl/) API and returns a rendering of its structure as PNG image. This can be incredibly useful when designing software for the life sciences where chemical structures might be a common form of data rendered.

## Installation

_Requires Sketch >= 3_

* [Download](https://github.com/ahadik/chemfill/releases/latest) the latest release
* Un-zip
* Double click the plugin file to install.

## Features and Usage

Once you have installed the ChemFill plugin, you can access it from the Sketch Data menu.

### Inserting a Random Structure
A common use case is inserting a molecular structure into a shape:

Step 1: Select and right click on the shape you would like to insert a Chemical structure into.

![Step 1: Draw and select a rectangular shape](https://github.com/ahadik/chemfill/blob/master/docs/step-1.png)

Step 2: Select Data from the context menu.

<img src="https://github.com/ahadik/chemfill/blob/master/docs/step-2.png" width="200">

Step 3: Select the Random Structure action.

<img src="https://github.com/ahadik/chemfill/blob/master/docs/step-3.png" width="200">

Step 4: Enjoy your chemical mastery!

![Step 4: Enjoy your chemical mastery](https://github.com/ahadik/chemfill/blob/master/docs/step-4.png)

### Inserting Random Chemical Data
Another common set of use cases is generating and inserting chemical data as text. This is done much the same way:

Step 1: Select and right click on the text box, or collection of text boxes, you would like to fill.

Step 2: Select the type of data you would like to generate from the ChemFill Data menu.

![Step 2: Select the type of data you would like to generate from the ChemFill Data menu.](https://github.com/ahadik/chemfill/blob/master/docs/step-2b.png)

Step 3: Congratulate yourself for getting this far without a Chemistry PhD.

<img src="https://github.com/ahadik/chemfill/blob/master/docs/step-3b.png" width="400">

## Developing

### Getting Started

Install the dependencies

```bash
yarn install
```

Once the installation is done, you can run some commands inside the project folder:

```bash
yarn build
```

To watch for changes:

```bash
yarn run watch
```

Additionally, if you wish to run the plugin every time it is built:

```bash
yarn start
```

### Debugging

To view the output of your `console.log`, you have a few different options:

* Use the [`sketch-dev-tools`](https://github.com/skpm/sketch-dev-tools)
* Open `Console.app` and look for the sketch logs
* Look at the `~/Library/Logs/com.bohemiancoding.sketch3/Plugin Output.log` file

Skpm provides a convenient way to do the latter:

```bash
skpm log
```

The `-f` option causes `skpm log` to not stop when the end of logs is reached, but rather to wait for additional data to be appended to the input
