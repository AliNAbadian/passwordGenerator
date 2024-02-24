# Password Generator

This is a simple JavaScript password generator function that allows you to generate random passwords based on specified criteria such as length and character types.

## Features

- Generates random passwords with customizable length.
- Allows inclusion or exclusion of lowercase letters, uppercase letters, numbers, and symbols in the generated passwords.
- Provides error messages for invalid input parameters.

## Usage

To use the password generator function, follow these steps:

1. Ensure you have a JavaScript environment set up.
2. Copy the `generatePassword` function into your JavaScript project.
3. Configure the parameters of the function according to your requirements:
   - `length`: The desired length of the generated password.
   - `includeLowercase`: Whether to include lowercase letters in the password.
   - `includeUppercase`: Whether to include uppercase letters in the password.
   - `includeNumbers`: Whether to include numbers in the password.
   - `includeSymbols`: Whether to include symbols in the password.
4. Call the `generatePassword` function with the desired parameters.
5. The function will return a randomly generated password based on the specified criteria.

## Example

```javascript
const passwordLength = 12;
const includeLowercase = true;
const includeUppercase = true;
const includeNumbers = true;
const includeSymbols = true;

const password = generatePassword(
  passwordLength,
  includeLowercase,
  includeUppercase,
  includeNumbers,
  includeSymbols
);

console.log(`Generated Password: ${password}`);
```

## Contributions

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
