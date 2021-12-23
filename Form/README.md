# Form Validator

Form Validator is a Javascript library for dealing with Validation in Outsystems Reactive Web and Mobile.

## Getting Started

### Installation

Clone or Download From [Git](https://github.com/Developer-Geekay/Outsystems.git).

```bash
git clone https://github.com/Developer-Geekay/Outsystems.git
```
### Demo

Working code for this demo [OSDemo](https://developergeekay.outsystemscloud.com/OSDemo/validationtest)

### Usage

#### Step 1

Download and import script into your OS Reactive application. `Then attach script to SCREEN or UI under required script property`

#### Step 2

Use OsValidator function as mentioned below

```javascript

#returns <boolean>

OsValidator(WidgetId).then(function(result) {
    // ... your logic here
    $resolve();
});

```
Pass `widget #id` as param to this function. Promise callback will return true or false via argument `result`.

![Validation](https://user-images.githubusercontent.com/50963805/147228141-9b061ec2-9ca1-4139-9409-f6299001cedb.png)

![demo](https://user-images.githubusercontent.com/50963805/147230134-8471eb62-4a0b-451d-ab6d-7735eb658c12.gif)

##### Key Points
    1. Target Form or Element should marked a `mandatory`.
    2. Trigger form validation from anywhere in the same screen.
    3. No restriction for Form which present in different blocks.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Creators

**Developer Geekay**

* <https://github.com/Developer-Geekay>

## License
[MIT](https://choosealicense.com/licenses/mit/)
