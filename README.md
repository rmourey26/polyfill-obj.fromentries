# `Object.fromEntries()` polyfill

Provides polyfill for `Object.fromEntries()`.

## Usage

Importing the module will automatically monkey-patch the Object class, adding the static method only if needed. If the functionality is already present, nothing is done.

    require('polyfill-object.fromentries');

    Object.fromEntries(...);

## License
This package is published under the MIT license. See the enclosed *LICENSE* file for further information.
