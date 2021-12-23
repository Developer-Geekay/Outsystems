# Form Validator

Form Validator is a Javascript library for dealing with Validation in Outsystems.

## Getting Started

### Installation

Clone or Download From [Git](https://github.com/Developer-Geekay/Outsystems.git).

```bash
git clone https://github.com/Developer-Geekay/Outsystems.git
```
### Demo

Working code for this demo < <a href="https://developergeekay.outsystemscloud.com/OSDemo/validationtest" target="_blank">OSDemo</a> >

### Usage

#### Step 1

Download and import into your OS Reactive application. `Then attach script to SCREEN or UI level`

#### Step 2

Use OsValidator function as mentioned below

```javascript

#returns <boolean>

OsValidator(WidgetId).then(function(result) {
    // ... your logic here
    $resolve();
});

```
Pass target `widget #id` as param to this function.
`result` will return true or false based on basic form validation which elements has marked as mandatory

![Validation](https://user-images.githubusercontent.com/50963805/147228141-9b061ec2-9ca1-4139-9409-f6299001cedb.png)

![demo](https://user-images.githubusercontent.com/50963805/147230134-8471eb62-4a0b-451d-ab6d-7735eb658c12.gif)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Creators

**Developer Geekay**

* <https://github.com/Developer-Geekay>

## License
[MIT](https://choosealicense.com/licenses/mit/)
