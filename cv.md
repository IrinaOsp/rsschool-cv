# Irina Osipova
## Contact Info
Telegram: [osipova_ira](https://t.me/osipova_ira)

GitHub: [github.com/IrinaOsp](https://github.com/IrinaOsp)

Email: [osipova_irina@hotmail.com](mailto:osipova_irina@hotmail.com)

## Summary
I completed the Russian version of the JS/Frontend course in September and applied for the English version to improve my skills, close knowledge gaps, gain experience in English interviews, and add a couple of new projects to my portfolio.

## Skills
- HTML
- CSS/SCSS
- TS/JS
- Git, Github
- Jest
- Postman
- basic knowledge of React

## Code example

```
function validateDateOfBirth(inputDate) {
    const userDate = new Date(inputDate);
    const currentDate = new Date();

    const userAge = currentDate.getFullYear() - userDate.getFullYear();
    const isValidAge = userAge >= 18 && userAge <= 120;
    return isValidAge;
}

// Usage example
const inputDate = "1990-05-15";
const isDateValid = validateDateOfBirth(inputDate);

if (isDateValid) {
    console.log("Birth date is valid");
} else {
    console.log("Invalid date of birth or age is outside the acceptable range.");
}
```
