# Wiesjes Weather Website

## Installing the app
To install the app run
```bash
npm install
```

This will make npm look for `package-lock.json`, which specifies all the versions of all dependencies (and their dependencies) and install them.

## Running the app
To run the app run 
```bash
node app.js
```

This will make node (a JavaScript runtime) look for a file called `app.js` and run it.

Alternatively, run
```bash
npm start
```

or

```bash
npm run start
```

This will look for the "start" script in `package.json` (currently set to `node app.js`) and execute it.