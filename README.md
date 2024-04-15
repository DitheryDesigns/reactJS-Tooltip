# Tooltip React Component

## Overview

The `Tooltip` component provides a flexible and reusable way to add tooltips to elements in your React applications. Tooltips appear on hover and can display additional information, enhancing the user experience.

## Features

- **Custom Text**: Supports custom text content for the tooltip.
- **React Children**: Wraps around any React component to display the tooltip.
- **Stylable**: The tooltip is styled using a separate CSS file, allowing for easy customization.

## Installation

1. Download both `Tooltip.js` and its associated `Tooltip.css` files.
2. Place them into your project's appropriate directory.

## Usage

```jsx
import Tooltip from './path/to/Tooltip';

function App() {
  return (
    <Tooltip text="This is a tooltip">
      <button>Hover over me</button>
    </Tooltip>
  );
}
```

## Props

- `text` (String): The text to be displayed in the tooltip.
- `children` (ReactNode): The element that the tooltip will wrap around.
- `style` (Object): Optional inline styles for the tooltip wrapper.

## License

MIT License
