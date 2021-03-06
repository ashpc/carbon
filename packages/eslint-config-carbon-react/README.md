# `eslint-config-carbon`

> Provides a set of ESLint rules and plugins to be shared by Carbon Design System projects.

## Usage

Our default export contains all of our ESLint rules, including ECMAScript ES2015+ and React. It requires `eslint`, `eslint-plugin-import`, `eslint-plugin-react`, and `eslint-plugin-jsx-a11y`. By default, you can add this package to your project by running the following command:

```bash
npm i eslint-config-carbon --save-dev
```

You can install the correct versions of each peer Dependency by running the following command:

```bash
npm info "eslint-config-carbon@latest" peerDependencies
```

This typically gives you an output like:

```bash
{ eslint: '^3.19.0', 'eslint-plugin-import': '^2.2.0', 'eslint-plugin-jsx-a11y': '^4.0.0', 'eslint-plugin-react', '^6.10.3' }
```

Which you can then use like:

```bash
npm i eslint@^3.19.0 eslint-plugin-import@^2.2.0 eslint-plugin-jsx-a11y@^4.0.0 eslint-plugin-react@^6.10.3 --save-dev
```

Finally, just add `"extends": "carbon"` to your `.eslintrc`.
