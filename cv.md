# Olya Dubodel

## Contact information
* **Location:** Minsk, Belarus
* **Phone:** +375 (29) 607-86-01
* **Email:** dubodel.olya@gmail.com
* [Telegram](https://t.me/olydbd)
* [GitHub](https://github.com/olydbd)

## About me

## Skills
* HTML
* CSS
* JavaScript (Basics)
* Git, GitHub
* VS Code
* Figma

## Code Example
**First non-repeating character:** write a function named first_non_repeating_letter that takes a string input, and returns the first character that is not repeated anywhere in the string. If a string contains all repeating characters, it should return an empty string ("") or None -- see sample tests.
```
function firstNonRepeatingLetter(s) {
  let copy = s.toLowerCase();
  let ind = [...copy].findIndex((item, index, arr) => arr.indexOf(item) === arr.lastIndexOf(item));
  return (ind !== -1) ? s[ind] : '';
}
```

## Education
* Belarusian State University, Faculty of Applied Mathematics and Computer Science

## Languages
* English - Intermediate (B1)
* Russian - Native
* Belarusian - Intermediate (B1)