# CommonUI - Reusable UI Component Library

A comprehensive collection of reusable UI components built with React, TypeScript, and Tailwind CSS, designed to accelerate development across multiple projects with consistent design patterns.

## Features

- **40+ UI Components**: Extensive library of pre-built, customizable components
- **Accessibility Focused**: WCAG compliant components with proper ARIA attributes
- **Responsive Design**: Mobile-first approach ensuring compatibility across devices
- **Theme Customization**: Easy styling customization through Tailwind configuration
- **TypeScript Support**: Full type safety with comprehensive TypeScript definitions

## Components

This library includes:
- Navigation components (Navbar, Footer, etc.)
- Form elements (Input, Select, Checkbox, etc.)
- Layout components (Card, Accordion, Tabs, etc.)
- Feedback components (Toast, Alert, Dialog, etc.)
- Data display components (Table, Chart, etc.)

## Tech Stack

- React 18+
- TypeScript
- Tailwind CSS
- Shadcn UI
- Vite

## Getting Started

```bash
# Clone the repository
git clone https://github.com/nish340/Ui_Library.git

# Navigate to the project directory
cd CommonUi

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Usage

Import components directly from the library:

```tsx
import { Button, Card, Input } from '@/components/ui';

function MyComponent() {
  return (
    <Card>
      <h2>Login Form</h2>
      <Input placeholder="Username" />
      <Button>Submit</Button>
    </Card>
  );
}
```

## Project Structure

- `/src/components/ui`: Core UI components
- `/src/hooks`: Custom React hooks
- `/src/lib`: Utility functions

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## Author

Nishchay Sharma

## License

MIT
