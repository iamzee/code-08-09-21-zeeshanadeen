# BMI Calculator

## Requirements

[Nodejs](https://nodejs.org/en/) and a node package manager, [npm](https://www.npmjs.com/) are required to run the application.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install dependencies.

```bash
git clone https://github.com/iamzee/code-08-09-21-zeeshanadeen
cd code-08-09-21-zeeshanadeen
npm install
```

## Configure app

Place your JSON data in **/dist/data.json** file. A sample **data.json** file is provided in the **dist** folder.

## Build an app

Build the application.

```bash
npm run build
```

## Run

Run the application.

```bash
npm start
```

## Result

After a successful run, the resultant JSON data (with 3 new columns - **BMI**, **BMICategory** and **HealthRisk**) will get stored in **/dist/result.json** file. (Problem 1)

Result related to Problem 2, will get displayed on the console.

## Testing

Unit Testing the application.

```bash
npm run test
```

## Continuous Integration

**Build** and **Test** process is automated using [CircleCI](https://circleci.com/) pipeline. CircleCI configuration file is included in the application.

## Remarks

The application is tested on 1 million JSON objcts and it works fine.
