# Quixote - CSS Unit Testing

This repository will contain the code for Quixote, a library for unit testing CSS. 

This project will developed live at starting on Oct 13, 2014 at 10am PDT (GMT-7). To watch or participate, go to http://hitbox.tv/jamesshore . 


## Contributing

To contribute to this project, please participate in the livestream.


### Setup

To work with this code on your own computer:

1. Install [Node.js](http://nodejs.org/download/).
2. Clone the GitHub repository into a convenient directory.
3. All commands must run from the root of the source tree: `cd <directory>`.

### Running the Tests

1. Run `./jake.sh karma` to start the Karma server.
2. Start the browsers you want to test and point each one at `http://localhost:9876`.
3. Run `./jake.sh` every time you want to build and test.

### Branches

The `master` branch is the known-good integration branch. This branch should always build and pass its tests.

The `dev` branch is for work in progress.

Use the `integrate.sh` script to automatically integrate changes in the dev branch back to the master branch. The `release.sh` script will perform a release.


## Credits

Created by James Shore for his [Let's Code: Test-Driven JavaScript](http://www.letscodejavascript.com) screencast. Let's Code JavaScript is a screencast series on professional, rigorous web development. 


## License

MIT License. See `LICENSE.TXT`.