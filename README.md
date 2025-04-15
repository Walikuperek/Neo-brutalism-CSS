# Neo-Brutalism CSS Library

![img](showcase_img.png)

<p align="center">
  <img src="https://img.shields.io/github/license/walikuperek/qtheme" />
</p>
<p align="center">
  DEMO <a href="https://quak.com.pl/lib/neo-brutalism/" target="_blank">https://quak.com.pl/lib/neo-brutalism/</a>
</p>

A comprehensive CSS library for creating stunning websites with a neo-brutalist aesthetic. This library provides ready-to-use components, utilities, and layout systems to build modern, bold web designs.

## 🚀 Features

- **Bold Typography** with Space Grotesk and Inter fonts
- **Neo-Brutalist Components** with thick borders and distinctive shadows
- **Vibrant Color System** with carefully selected palette
- **Flexible Layout System** using modern CSS Grid and Flexbox
- **Animation Utilities** to bring your interfaces to life
- **Responsive Design** that works across all devices
- **Zero Dependencies** - pure CSS solution

## 📦 Installation

### Quick Start

Download and include the main CSS file in your HTML:

```html
<link rel="stylesheet" href="css/main.css">
```

### Modular Approach

Import only the modules you need:

```html
<link rel="stylesheet" href="css/variables.css">
<link rel="stylesheet" href="css/typography.css">
<link rel="stylesheet" href="css/neo-brutalism.css">
<!-- Add other modules as needed -->
```

### Fonts

The library uses Space Grotesk for headings and Inter for body text:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&family=Space+Grotesk:wght@400;700&display=swap" rel="stylesheet">
```

## 🎨 Core Concepts

Neo-brutalism in web design is characterized by:

- **Bold, thick borders** (3-4px)
- **Strong drop shadows** with noticeable offsets
- **Vibrant colors** and high contrast
- **Simple geometric shapes**
- **Raw, unpolished aesthetics**

## 🧩 Components

### Buttons

```html
<!-- Primary Button -->
<button class="neo-btn">Click Me</button>

<!-- Secondary Button -->
<button class="neo-btn neo-btn-secondary">Secondary Action</button>

<!-- Button Variations -->
<button class="neo-btn neo-btn-accent">Accent</button>
<button class="neo-btn neo-btn-yellow">Yellow</button>
<button class="neo-btn neo-btn-green">Green</button>

<!-- Size Variations -->
<button class="neo-btn neo-btn-lg">Large Button</button>
<button class="neo-btn neo-btn-sm">Small Button</button>
```

### Cards

```html
<div class="neo-card">
  <h3>Card Title</h3>
  <p>Card content goes here.</p>
</div>
```

### Icons

```html
<div class="neo-icon">
  <i class="icon-name"></i>
</div>

<div class="neo-icon neo-icon-sm">
  <i class="icon-name"></i>
</div>
```

### Bubbles/Tags

```html
<span class="neo-bubble">Tag Name</span>
```

### Images

```html
<img src="image.jpg" alt="Description" class="neo-image">
```

## 📏 Layout System

### Container

```html
<div class="container">
  <!-- Content here -->
</div>

<!-- Sizes -->
<div class="container-sm">Smaller max-width</div>
<div class="container-lg">Larger max-width</div>
```

### Flexbox

```html
<div class="flex items-center justify-between">
  <div>Left side</div>
  <div>Right side</div>
</div>

<!-- Column Layout -->
<div class="flex flex-col gap-md">
  <div>Item 1</div>
  <div>Item 2</div>
</div>
```

### Grid

```html
<div class="grid grid-cols-3 gap-grid-md">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<!-- Auto-fill Grid -->
<div class="grid grid-cols-auto gap-grid-md">
  <!-- Items here -->
</div>
```

## 🎭 Animations

```html
<!-- Float animation -->
<div class="float">This element will float up and down</div>

<!-- Shape animations -->
<div class="shape1">Moving shape 1</div>
<div class="shape2">Moving shape 2</div>
<div class="shape3">Moving shape 3</div>

<!-- Pulse animation -->
<div class="pulse-shape">This will pulse</div>

<!-- Rotate animation -->
<div class="rotate-circle">This will rotate</div>

<!-- Hover effects -->
<div class="hover-lift">Lifts on hover</div>
<div class="hover-scale">Scales on hover</div>

<!-- Loading animation -->
<div class="spin">Spinning loader</div>

<!-- Entrance animations -->
<div class="fade-in">Fades in</div>
<div class="slide-up">Slides up</div>
```

## 🛠 Utilities

### Display
```html
<div class="block">Block element</div>
<span class="inline-block">Inline block element</span>
```

### Spacing
```html
<div class="mt-lg mb-md">Margin top (large) and bottom (medium)</div>
<div class="p-lg">Padding large</div>
<div class="mx-auto">Horizontally centered</div>
```

### Colors
```html
<div class="bg-primary text-light">Primary background with light text</div>
<div class="bg-light text-dark">Light background with dark text</div>
```

### Text Alignment
```html
<p class="text-center">Centered text</p>
<p class="text-right">Right-aligned text</p>
```

### Borders & Shadows
```html
<div class="border shadow-neo">Element with border and shadow</div>
<div class="border-bold shadow-neo-lg">Bold border and large shadow</div>
```

## 📱 Responsive Design

The library includes a responsive system with breakpoints:

- Large screens: max-width 1200px
- Medium screens: max-width 992px
- Small screens: max-width 768px
- Extra small screens: max-width 576px

## 📚 Examples

Check out the [showcase page](https://quak.com.pl/lib/neo-brutalism/) for a complete demonstration of all components and features.

### Complete Hero Section

```html
<section class="hero">
  <div class="container">
    <div class="hero-content">
      <div class="hero-text">
        <h1>Bold, Brutalist <span class="highlight highlight-yellow">Design</span></h1>
        <p>Create stunning neo-brutalist websites with our comprehensive CSS library.</p>
        <div class="neo-button-group">
          <a href="#" class="neo-btn">Get Started</a>
          <a href="#" class="neo-btn neo-btn-secondary">Learn More</a>
        </div>
      </div>
      <div class="hero-animation">
        <div class="shape1 pulse-shape"></div>
        <div class="shape2"></div>
        <div class="shape3"></div>
        <div class="rotate-circle"></div>
      </div>
    </div>
  </div>
</section>
```

### Services Grid

```html
<section class="section">
  <div class="container">
    <h2 class="section-title">Our Services</h2>
    <p class="section-description">We offer a range of services to help your business stand out.</p>
    
    <div class="services-grid">
      <div class="service-card">
        <div class="service-icon">🎨</div>
        <h3>Web Design</h3>
        <p>Bold, brutalist designs that make your brand stand out from the crowd.</p>
      </div>
      
      <div class="service-card">
        <div class="service-icon">💻</div>
        <h3>Development</h3>
        <p>Clean, efficient code that brings your designs to life.</p>
      </div>
      
      <div class="service-card">
        <div class="service-icon">📱</div>
        <h3>Mobile Apps</h3>
        <p>Cross-platform applications with distinctive brutalist aesthetics.</p>
      </div>
    </div>
  </div>
</section>
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspired by the neo-brutalist design trend
- Thanks to all contributors and supporters
- Typography powered by Google Fonts

---

Made with ❤️ by QuaK
