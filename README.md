# ChatCraft React UI Kit

This repository contains a set of React components for ChatCraft. It utilizes Vite for development and Storybook for showcasing and testing the components.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/YaraLash/chatcraft-ui-kit.git
```

2. Install dependencies:

```bash
cd chatcraft-ui-kit
yarn
```

## Running

To run the project locally for development, execute:

```bash
yarn run dev
```

This will start the project using Vite in development mode.

## Storybook

To run Storybook and view the components, execute:

```bash
yarn run storybook
```

Afterwards, you can open Storybook in your browser at [http://localhost:6006](http://localhost:6006).

## Building

To build the project, run:

```bash
yarn run build
```

To build Storybook, run:

```bash
yarn run build-storybook
```

## Husky

This project uses Husky to set up Git hooks. Husky is configured to run pre-commit hooks, which can be found in the `.husky/pre-commit` file. These hooks can be used to enforce code quality standards or perform other tasks before committing code changes.

## Documentation

Documentation for the components is available through Storybook. You can explore them there and utilize Storybook's various interactive features for testing.