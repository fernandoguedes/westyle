# WeStyle

[![Build Status](https://travis-ci.org/wedeploy/westyle.svg)](https://travis-ci.org/wedeploy/westyle)

> Style Guide built on top of Twitter Bootstrap.

## Setup

1. Make sure you have [Node.js and npm](https://nodejs.org/en/download/) installed:

	```sh
node -v && npm -v
	```

2. Install our global dependencies:

	```sh
npm i -g bower gulp
	```

3. Install our local dependencies:

	```sh
npm i && bower i
	```

## Usage

* Build the SASS files:

	```
gulp build
	```

	This will create a `build` folder with compiled styles.

* Generate webfonts:

	```
gulp fonts
	```

	This will create font files based on SVG icons.

* Watch for SASS file changes:

	```
gulp watch
	```

	This will trigger the `build` task everytime a SASS file is changed.

## License

[BSD License](./LICENSE.md) © Liferay, Inc.
