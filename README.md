# MTB Demo

This is a demo website showcasing the capabilities of [MTB.js](https://github.com/DiegoVallejoDev/mtb), a lightweight, component-based static site generator.

## Features

- **Component-Based**: Build static sites using reusable HTML components.
- **Props Support**: Pass dynamic values to components.
- **Zero Dependencies**: Pure static HTML output.
- **Alpine.js Integration**: Seamlessly add interactivity.
- **Premium Design**: Modern, responsive UI with glassmorphism and animations.

## Getting Started

### Prerequisites

- Node.js installed
- `mtb` installed globally (`npm install -g mtb`) or use the local script.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/DiegoVallejoDev/mtb-demo.git
   ```
2. Install dependencies:
   ```bash
   pnpm install
   ```

### Usage

- **Development**: Watch for changes and rebuild automatically.
  ```bash
  pnpm run watch
  ```
- **Build**: Build the project for production.
  ```bash
  pnpm run build
  ```

## Project Structure

- `src/components/`: Reusable HTML components.
- `src/pages/`: Page templates.
- `src/assets/`: CSS, images, and other assets.
- `dist/`: Generated static site (after build).

## License

ISC
