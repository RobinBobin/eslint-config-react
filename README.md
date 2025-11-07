# Installation

Install the following packages:

    pnpm i --save-dev @robinbobin/eslint-config-react eslint@^9.39.1

The script invoked during `postinstall` copies a sample ESLint config to your project root dir, naming the file `eslint.config.js_<number>`. Don't forget to delete the `_<number>` part from the file name. You can copy this sample config manually if you don't want to let `postinstall` execute:

    cp node_modules/@robinbobin/eslint-config-react/eslint.config.js_ ./eslint.config.js
