# Neo-Brutalism CSS Library Documentation

A comprehensive CSS library for creating neo-brutalist style websites with clean, modular components.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Core Concepts](#core-concepts)
3. [Variables](#variables)
4. [Typography](#typography)
5. [Neo-Brutalism Components](#neo-brutalism-components)
6. [Layout System](#layout-system)
7. [Components](#components)
8. [Animations](#animations)
9. [Utilities](#utilities)
10. [Responsive Design](#responsive-design)
11. [Examples](#examples)

## Getting Started

### Installation

Include the main CSS file in your HTML:

```html
<link rel="stylesheet" href="css/main.css">
```

Or import individual modules as needed:

```html
<link rel="stylesheet" href="css/variables.css">
<link rel="stylesheet" href="css/neo-brutalism.css">
<!-- Add other modules as needed -->
```

## Core Concepts

Neo-brutalism is characterized by:

- Bold, thick borders
- Strong drop shadows
- Vibrant colors
- Simple geometric shapes
- Raw, unpolished aesthetics

This library implements these principles through:

- Consistent border widths (3-4px)
- Box shadows with horizontal and vertical offsets
- A carefully selected color palette
- Clean typography with Space Grotesk and Inter fonts

## Variables

All design tokens are stored in CSS variables for easy customization.

### Colors

```css
--primary: #FF6B35;
--secondary: #3A86FF;
--accent: #8338EC;
--dark: #141414;
--light: #F8F9FA;
--yellow: #FFBE0B;
--green: #06D6A0;
```

### Background Card Colors

```css
--bg-card-1: #FFE6D8;
--bg-card-2: #D8EEFE;
--bg-card-3: #E9D8FF;
--bg-card-4: #D8FFF1;
--bg-card-5: #FFEFD8;
--bg-card-6: #D8FFEA;
```

### Typography

```css
--font-primary: 'Inter', sans-serif;
--font-heading: 'Space Grotesk', sans-serif;
```

### Spacing

```css
--space-xs: 10px;
--space-sm: 15px;
--space-md: 20px;
--space-lg: 30px;
--space-xl: 40px;
--space-xxl: 80px;
```

### Borders & Shadows

```css
--border-width: 3px;
--border-width-bold: 4px;
--shadow-offset: 4px;
--shadow-offset-large: 8px;
```

## Typography

The library includes a comprehensive typography system:

- Headings (h1-h6) use Space Grotesk (bold)
- Body text uses Inter
- Section titles with decorative underlines
- Text highlight utilities

### Example

```html
<h1 class="highlight highlight-yellow">Bold Heading</h1>
<p class="section-description">Detailed description text here.</p>
```

## Neo-Brutalism Components

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

## Layout System

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

### Sections

```html
<section class="section">
  <div class="container">
    <h2 class="section-title">Section Title</h2>
    <!-- Content -->
  </div>
</section>

<section class="section section-colored neo-border-top neo-border-bottom">
  <!-- Colored section with borders -->
</section>
```

## Components

### Navigation

```html
<nav class="navbar">
  <div class="container nav-container">
    <a href="#" class="logo">
      <div class="logo-icon">N</div>
      Brand
    </a>
    <ul class="menu">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
    <button class="mobile-menu-button">☰</button>
  </div>
</nav>
```

### Hero Section

```html
<section class="hero">
  <div class="container">
    <div class="hero-content">
      <div class="hero-text">
        <h1>Your Bold Headline</h1>
        <p>Supporting text that explains your value proposition.</p>
        <div class="neo-button-group">
          <a href="#" class="neo-btn">Primary CTA</a>
          <a href="#" class="neo-btn neo-btn-secondary">Secondary CTA</a>
        </div>
      </div>
      <div class="hero-image">
        <div class="hero-img-container">
          <img src="hero.jpg" alt="Hero" class="hero-img">
        </div>
      </div>
    </div>
  </div>
</section>
```

### Service Cards

```html
<div class="services-grid">
  <div class="service-card">
    <div class="service-icon">🚀</div>
    <h3>Service Title</h3>
    <p>Service description goes here explaining the value.</p>
  </div>
  <!-- More service cards -->
</div>
```

### CTA Section

```html
<section class="cta">
  <div class="container">
    <h2>Ready to Get Started?</h2>
    <p>Join thousands of satisfied customers using our product.</p>
    <a href="#" class="neo-btn">Get Started</a>
  </div>
</section>
```

### Footer

```html
<footer class="footer">
  <div class="container">
    <div class="footer-content">
      <div class="footer-column">
        <a href="#" class="footer-logo">
          <div class="footer-logo-icon">N</div>
          Brand
        </a>
        <p>Short description about your company.</p>
        <div class="social-links">
          <a href="#" class="social-link">🐦</a>
          <a href="#" class="social-link">📱</a>
          <a href="#" class="social-link">📸</a>
        </div>
      </div>
      <div class="footer-column">
        <h3>Links</h3>
        <ul class="footer-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
      <div class="footer-column">
        <h3>Contact</h3>
        <div class="contact-item">
          <div class="contact-icon">📍</div>
          <span>123 Street Name, City</span>
        </div>
        <div class="contact-item">
          <div class="contact-icon">📞</div>
          <span>+1 234 567 890</span>
        </div>
        <div class="contact-item">
          <div class="contact-icon">✉️</div>
          <span>hello@example.com</span>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <p>&copy; 2025 Your Company. All rights reserved.</p>
    </div>
  </div>
</footer>
```

## Animations

The library includes several animation utilities:

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

## Utilities

The library includes a comprehensive set of utility classes:

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

## Responsive Design

The library includes a responsive system with breakpoints:

- Large screens: max-width 1200px
- Medium screens: max-width 992px
- Small screens: max-width 768px
- Extra small screens: max-width 576px

Media queries handle:
- Typography scaling
- Layout adjustments
- Mobile navigation
- Grid columns

### Mobile Navigation Example

```html
<script>
  document.querySelector('.mobile-menu-button').addEventListener('click', function() {
    document.querySelector('.menu').classList.toggle('active');
  });
</script>
```

## Examples

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
        <div class="shape1 pulse-shape" style="position: absolute; width: 80px; height: 80px; background-color: var(--primary); border: 4px solid var(--dark); top: 20%; left: 30%;"></div>
        <div class="shape2" style="position: absolute; width: 120px; height: 120px; background-color: var(--yellow); border: 4px solid var(--dark); bottom: 20%; right: 20%;"></div>
        <div class="shape3" style="position: absolute; width: 60px; height: 60px; background-color: var(--accent); border: 4px solid var(--dark); bottom: 30%; left: 20%;"></div>
        <div class="rotate-circle" style="position: absolute; width: 100px; height: 100px; border: 4px solid var(--dark); border-radius: 50%; top: 30%; right: 30%;"></div>
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

### Technology Bubbles

```html
<section class="section section-colored neo-border-top neo-border-bottom">
  <div class="container text-center">
    <h2 class="section-title">Technologies</h2>
    <div class="tech-bubbles">
      <span class="tech-bubble">HTML5</span>
      <span class="tech-bubble">CSS3</span>
      <span class="tech-bubble">JavaScript</span>
      <span class="tech-bubble">React</span>
      <span class="tech-bubble">Node.js</span>
      <span class="tech-bubble">Python</span>
      <span class="tech-bubble">Figma</span>
      <span class="tech-bubble">Illustrator</span>
    </div>
  </div>
</section>
```
