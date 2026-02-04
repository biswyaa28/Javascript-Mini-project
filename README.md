# No‑Code Form Builder

A drag‑and‑drop visual editor for creating HTML forms without writing code. Built with vanilla JavaScript, it enables rapid form prototyping and live HTML generation.

## ✨ Features

- **Visual Drag‑and‑Drop** – Add form elements from a sidebar palette
- **Real‑Time Preview** – See form updates as you build
- **Nested Structures** – Support for sections with recursive nesting
- **Property Editor** – Customize labels, placeholders, and validation
- **HTML Export** – Copy clean, generated HTML code
- **No Dependencies** – Pure HTML, CSS, and JavaScript

## 🚀 Quick Start

1. **Clone or download** the project files
2. **Open `index.html`** in a modern browser
3. **Drag elements** from the sidebar onto the canvas
4. **Click any element** to edit its properties
5. **Use the Export button** to copy the generated HTML

## 🧩 Supported Elements

- Text input
- Email input
- Number input
- Textarea
- Checkbox
- Dropdown (Select)
- Button
- Section (container for nesting)

## 🏗️ Architecture

The builder follows a **model‑view‑controller (MVC)** pattern:

- **Model** – JavaScript objects representing form elements and their properties
- **View** – DOM representation in the canvas
- **Controller** – Event handlers and state management

### Key Technical Concepts

- **DOM Traversal** – Navigating and manipulating the document tree
- **Recursion** – Handling nested form structures
- **Event Delegation** – Efficient event handling for dynamic elements
- **Data‑First Design** – Form state stored as pure JavaScript objects

## 📖 How It Works

### Adding Elements
1. Drag an element from the sidebar
2. Drop it onto the canvas or into a section
3. The system creates both a data model and visual representation

### Editing Properties
1. Click any form element in the canvas
2. Edit properties in the right panel
3. Changes update both the visual form and underlying data model

### Nested Forms
1. Add a "Section" element to the canvas
2. Drag additional elements into the section's drop zone
3. Sections can be nested indefinitely using recursive data structures

## 🧠 Development Concepts Demonstrated

- **Separation of Concerns** – Clear division between data, presentation, and logic
- **State Management** – Single source of truth for form structure
- **Functional Programming** – Pure functions for HTML generation
- **Tree Data Structures** – Nested elements stored as parent‑child hierarchies

## 🔧 Extending the Builder

### Adding New Element Types
1. Add a draggable item to the sidebar with a unique `data-type`
2. Extend the `renderHTML()` function to handle the new type
3. Update the `buildHTML()` function for export rendering

### Custom Properties
1. Add input fields to the `showProperties()` function
2. Extend the element data model with new properties
3. Update the property update handler

## 📄 License

Open source – free for educational and commercial use.

## 🎯 Use Cases

- **Rapid prototyping** of web forms
- **Teaching web development** concepts visually
- **Internal tools** for non‑technical teams
- **Form template creation** for reuse

## 🤝 Contributing

This is a learning project. Suggestions and improvements are welcome through issues or pull requests.

---

**Built with pure web technologies** – no frameworks, no build steps, just clean code that demonstrates fundamental web development principles.
