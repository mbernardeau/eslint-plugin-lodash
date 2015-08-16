ESLint-plugin-lodash3
===================


Lodash3 specific linting rules for ESLint

# Installation

Install [ESLint](https://www.github.com/eslint/eslint) either locally or globally.

    npm install eslint

If you installed `ESLint` globally, you have to install lodash3 plugin globally too. Otherwise, install it locally.

    $ npm install eslint-plugin-lodash3

# Configuration

Add `plugins` section and specify ESLint-plugin-React as a plugin.

```json
{
  "plugins": [
    "lodash3"
  ]
}
```


Finally, enable all of the rules that you would like to use.

```json
{
  "rules": {
    "lodash3/prop-shorthand": 1,
    "lodash3/matches-prop-shorthand": 1,
    "lodash3/prefer-chain": 1,
    "lodash3/preferred-alias": 1
  }
}
```

# List of supported rules

* [prop-shorthand](docs/rules/prop-shorthand.md): Prefer property shorthand syntax
* [prop-shorthand](docs/rules/matches-prop-shorthand.md): Prefer matches property shorthand syntax
* [prop-shorthand](docs/rules/preferred-alias.md): Preferred aliases
* [prop-shorthand](docs/rules/prefer-chain.md): Prefer chain


# TODO
* no-single-chain prevent 1 length _().map().value()


# License

ESLint-plugin-lodash is licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

