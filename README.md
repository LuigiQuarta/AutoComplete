# AutoCompleteType
A more accurate typing for the HTML input autocomplete attribute

## The problem
The autocomplete attribute is often typed as 'string' in a lot of framework/libraries; this means that the IDE doesn't provide any suggestion/check when you specify a value for the attribute and errors can happen.
Maintaining an up-to-date list of all the possible values for the autocomplete attribute is something that shouldn't be done in specific projects cause it means that you should periodically check for updates and apply the same changes over and over.


## The solution (getting started)
You can type the autocomplete attribute with the AutoComplete type provided by this package. In this way devs will have suggestions while they type the autocomplete values and will be notified by the IDE in case of typos/incorrect values.
You don't need to check for updates, the AutoComplete package do this for you (monthly).

## Getting started

Install the library using npm:

    npm i -D autocomplete-type

or yarn:

    yarn add -D autocomplete-type

Import the AutoComplete type and use it when you need:

    import { AutoComplete } from 'autocomplete-type'

    // ...

    type TextInputProps = {
      // ...
      autoComplete?: AutoComplete
    }
