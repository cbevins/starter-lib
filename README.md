# cbevins/starter-lib

A custom starter package for projects that produce an NPM library package.

Produces a new project folder with configuration files and NPM packages installed for:
- Babel
- Eslint
- Jest, Coveralls
- Rollup


## setup-lib.bat

`setup-lib.bat` is a Windows batch file that creates a new project folder structure and copies starter configuration files and development packages into it.  Copy the `setup-lib.bat` file to the folder that will contain the new project folder, and run it as follows:
```
> setup-lib my-project-folder
```

## package.json

Change into the new my-project-folder and edit the following fields within the `package.json` file:
- name
- version
- description
- keywords
- repository
- publishConfig
- bugs
- homepage

## Scripts
```
npm run test
npm run test:coverage
npm run test:watch
npm run build
```
