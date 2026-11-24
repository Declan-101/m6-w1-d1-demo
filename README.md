# Module 6 Week 1 Day 1 Demo (Week 5 Day 1)

Declan Wilde - WEB 403

## Run

`node ./factory/index.js` or `npm start`. No dependency installation is needed.

## What it does

The Laptop and Tablet constructor functions build objects with their supplied specifications. gadgetFactory maps the requested type to the corresponding constructor and returns a new instance. index.js uses that common API to create and print both devices. CommonJS module.exports and require connect the files.

The starter data is preserved: Laptop with 8 GB RAM and 256 GB SSD, and Tablet with 4 GB RAM, 128 GB HDD and 4G. Missing attributes use the defaults specified in the exercise.

The starter package scripts required a PATTERN environment variable and nodemon. This demo uses a direct start script and needs no third-party packages.

## Explain in class

“I created two constructors, one for laptops and one for tablets. The factory receives a device type and its attributes, chooses the correct constructor, and returns the new device. This gives the rest of the app one function for creating different types of gadget.”
