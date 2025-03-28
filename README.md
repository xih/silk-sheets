# Silk Sheets

A collection of beautiful, interactive sheet components for modern web applications. This repository contains various implementations of sheets (bottom sheets, top sheets, side sheets) with different behaviors and use cases.

## 🚀 Live Demo

Visit [https://3-28-2025-siolk-xihs-projects.vercel.app](https://3-28-2025-siolk-xihs-projects.vercel.app) to see all components in action.

## 📦 Available Sheets

### Bottom Sheet

A sheet that slides up from the bottom of the screen. Perfect for mobile-first interfaces and action menus.

- Location: `src/components/examples/BottomSheet`
- Features:
  - Smooth animations
  - Touch-friendly
  - Customizable height

### Top Sheet

A sheet that slides down from the top of the screen. Ideal for notifications or context-specific toolbars.

- Location: `src/components/examples/TopSheet`
- Features:
  - Responsive design
  - Customizable content
  - Easy to integrate

### Sheet with Detent

A sheet with specific snap points (detents) that users can drag to.

- Location: `src/components/examples/SheetWithDetent`
- Features:
  - Multiple snap points
  - Smooth snapping behavior
  - Customizable detent positions

### Sheet with Keyboard

A sheet that handles keyboard interactions gracefully.

- Location: `src/components/examples/SheetWithKeyboard`
- Features:
  - Keyboard-aware
  - Adjusts for virtual keyboards
  - Accessibility support

### Sheet with Stacking

Multiple sheets that can be stacked on top of each other.

- Location: `src/components/examples/SheetWithStacking`
- Features:
  - Z-index management
  - Independent sheet controls
  - Nested sheet support

### Long Sheet

A sheet designed for scrollable content.

- Location: `src/components/examples/LongSheet`
- Features:
  - Smooth scrolling
  - Overflow handling
  - Pull-to-refresh capability

### Page Sheet

A full-page sheet that can be used as a modal or secondary view.

- Location: `src/components/examples/Page`
- Features:
  - Full-screen coverage
  - Custom transitions
  - Rich content support

### Page from Bottom

A variation of the page sheet that animates from the bottom.

- Location: `src/components/examples/PageFromBottom`
- Features:
  - Bottom-up animation
  - Mobile-friendly
  - Customizable transitions

### Detached Sheet

A floating sheet that isn't anchored to any edge of the screen.

- Location: `src/components/examples/DetachedSheet`
- Features:
  - Free-floating positioning
  - Draggable
  - Resizable

### Sidebar Sheet

A sheet that slides in from the side of the screen.

- Location: `src/components/examples/Sidebar`
- Features:
  - Left/right positioning
  - Responsive breakpoints
  - Collapsible content

### Toast Sheet

A minimal notification sheet for temporary messages.

- Location: `src/components/examples/Toast`
- Features:
  - Auto-dismiss
  - Stack management
  - Different severity levels

## 🛠 Installation

1. Clone the repository:

```bash
git clone git@github.com:xih/silk-sheets.git
```

2. Install dependencies:

```bash
pnpm install
```

3. Run the development server:

```bash
pnpm dev
```

## 🎨 Customization

Each sheet component is highly customizable through props and can be styled using CSS modules or your preferred styling solution. Check the individual component directories for specific customization options.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

MIT License - feel free to use these components in your projects.
