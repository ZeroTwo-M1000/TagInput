# Vue Tag Input

**A simple and customizable tag input component for Vue 3.**

## Overview

The Vue Tag Input component allows users to easily create and manage tags within a form. It is designed to be intuitive and easy to integrate into any Vue 3 project. The component supports adding new tags by pressing Enter and removing tags by clicking on them. The styling is handled using Tailwind CSS, making it easy to customize the appearance to match your project's design.

## Features

-   **Add Tags**: Input new tags by typing and pressing Enter.
-   **Remove Tags**: Easily remove tags by clicking on the tag.
-   **Custom Styling**: Built with Tailwind CSS for easy customization.
-   **Vue 3 Compatible**: Fully compatible with Vue 3, leveraging the latest features and improvements.

## Installation

To install the Vue Tag Input component, run the following command:

```bash
bun i
```

## Development

### Start Dev Server

To start the development server, use the following command:

```bash
bun --bun run dev
```

### Format Code

Ensure your code is properly formatted by running:

```bash
bun --bun run format
```

### Lint Code

Check your code for potential issues with:

```bash
bun --bun run lint
```

### Build for Production

Compile and build the project for production using:

```bash
bun --bun run build
```

## Usage

To use the Vue Tag Input component in your project, follow these steps:

1. **Import the Component**: Import the `TagInput` component into your Vue file.
2. **Use the Component**: Add the `<TagInput />` component to your template.
3. **Customize**: Adjust the props and styles as needed to fit your project's requirements.

## Customization

The Vue Tag Input component is built with Tailwind CSS, making it highly customizable. You can easily adjust the styles by modifying the Tailwind CSS classes or by adding custom styles directly to the component.

### Props

-   **placeholder**: Sets the placeholder text for the input field.
-   **maxlength**: Limits the maximum length of the input text.

### Events

-   **@keydown**: Handles the keydown event to add tags when Enter is pressed.
-   **@click**: Handles the click event to remove tags.

---

**Happy Coding!** 🚀
