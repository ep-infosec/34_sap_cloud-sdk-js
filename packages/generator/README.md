<!-- sap-cloud-sdk-logo -->
<!-- This block is inserted by scripts/replace-common-readme.ts. Do not adjust it manually. -->
<a href="https://sap.com/s4sdk"><img src="https://help.sap.com/doc/2324e9c3b28748a4ae2ad08166d77675/1.0/en-US/logo-with-js.svg" alt="SAP Cloud SDK for JavaScript Logo" height="122.92" width="226.773"/></a>
<!-- sap-cloud-sdk-logo-stop -->

# @sap-cloud-sdk/generator

This packages contains the generator to create your own service module using a service specification (`.edmx` file).

## Installation

```sh
$ npm install @sap-cloud-sdk/generator
```

## Usage (CLI)

The generator is primarily meant to be used on the command line:

```sh
generate-odata-client --inputDir path/to/your/service-specification(s) --outputDir path/where/the/modules/are/stored
```

Run `generate-odata-client --help` for further options.

## Usage (programatically)

You can also use the generator programmatically. You will have to provide the options anyways.

```ts
import { generate } from '@sap-cloud-sdk/generator';

// initialize generator options based on what you want to do
const options: GeneratorOptions = initializeOptions();

// generate the client using the provided options
generate(options);
```

For more detailed overview visit our [generator documentation](https://sap.github.io/cloud-sdk/docs/js/features/odata/generate-odata-client).

<!-- sap-cloud-sdk-common-readme -->
<!-- This block is inserted by scripts/replace-common-readme.ts. Do not adjust it manually. -->
## Support

The recommended way to get in touch with us is to create an issue on [GitHub](https://github.com/SAP/cloud-sdk-js/issues).
Select the issue category `Bug`, `Feature` or `Question` depending on the nature of your request.
We try to provide fixes, features and answers as soon as possible.

## Contribute

If you would like to contribute to the SAP Cloud SDK, please make yourself familiar with our [contributing guidelines](https://github.com/SAP/cloud-sdk-js/blob/main/CONTRIBUTING.md) and follow the given instructions.

## Links
- [Official support channel](https://github.com/SAP/cloud-sdk-js/issues/new/choose)

<br>

- [Github](https://github.com/SAP/cloud-sdk-js)

<br>

- [SAP Cloud SDK Documentation portal](https://sap.github.io/cloud-sdk)
- [SAP Cloud SDK Documentation portal - Getting started guide](https://sap.github.io/cloud-sdk/docs/js/getting-started)
- [SAP Cloud SDK Documentation portal - API documentation](https://sap.github.io/cloud-sdk/api/latest)
- [SAP Cloud SDK Documentation portal - Error handling](https://sap.github.io/cloud-sdk/docs/js/features/error-handling)
- [SAP Cloud SDK Documentation portal - Release notes](https://sap.github.io/cloud-sdk/docs/js/release-notes-sap-cloud-sdk-for-javascript-and-typescript)

<br>

- [Sample repository](https://github.com/SAP-samples/cloud-sdk-js)

## License

The SAP Cloud SDK is released under the [Apache License Version 2.0.](http://www.apache.org/licenses/)
<!-- sap-cloud-sdk-common-readme-stop -->