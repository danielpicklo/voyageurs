# Voyageurs HubSpot Theme

A modern, glassmorphism-inspired HubSpot theme designed by WebScouts for creating visually rich, engaging websites with a blend of retro aesthetics and contemporary design elements.

## Overview

Voyageurs is a lightweight HubSpot theme that combines glassmorphism effects with bold, saturated colors inspired by 1970s and 1980s retro design. The theme features translucent elements, rounded edges, and frosted panels that create depth.

## Theme Features

### Design System
- **Glassmorphism Effects**: Translucent elements with backdrop blur and subtle borders
- **Retro Color Palette**: Bold, saturated colors with warm rainbow palettes
- **Typography**: PT Sans (body) and PT Serif (headings) from Google Fonts
- **Responsive Design**: Mobile-first approach with breakpoints at 767px
- **Animation Support**: AOS (Animate On Scroll) library integration

### Global Theme Settings

#### Colors
- **Primary**: #F1622B (Orange)
- **Secondary**: #0078F0 (Blue)
- **Tertiary**: #F452B8 (Pink)
- **Accent**: #FAF6EB (Cream)
- **Light**: #FFF5FB (Light Pink)
- **Dark**: #3E2C47 (Dark Purple)
- **Alternative Colors**: Additional secondary, tertiary, and accent variations

#### Typography
- **Primary Font**: PT Sans (sans-serif)
- **Secondary Font**: PT Serif (serif)
- **Heading Hierarchy**: H1-H6 with customizable transforms
- **Body Text**: 16px default size

#### Spacing & Layout
- **Vertical Spacing**: 144px default
- **Maximum Content Width**: 1224px
- **Border Radius**: Customizable for buttons, cards, and menus

## Modules

### 1. Button Module
**Purpose**: Flexible button component with multiple styles and effects
- **Features**:
  - Multiple button styles (Primary, Secondary, Tertiary, Accent, Light, Dark, Link)
  - Icon support with FontAwesome 5.14.0
  - Gradient and ghost button options
  - Animation types (fade-up, fade-down, fade-left, fade-right)
  - Custom styling (fonts, backgrounds, borders, spacing, alignment)
- **Default**: Primary style with chevron-right icon

### 2. Content Block Module
**Purpose**: Rich content display with glassmorphism effects
- **Features**:
  - Eyebrow text, title, and rich content
  - Icon or image display options
  - Multiple button styles with gradient/ghost options
  - Glass effect toggle
  - Orientation options (stacked/row)
  - Animation and spin effects
  - Scroll lock functionality
- **Styling**: Customizable colors, fonts, backgrounds, borders, spacing

### 3. Glass Form Module
**Purpose**: HubSpot form integration with glassmorphism styling
- **Features**:
  - HubSpot form embedding (v2 and v4)
  - Glass effect styling
  - Animation options
  - Customizable background colors and borders
- **Default**: Inline response type with thank you message

### 4. Glass Image Module
**Purpose**: Image display with glassmorphism effects
- **Features**:
  - Responsive image support
  - Glass effect styling
  - Animation options
  - Customizable background colors
- **Default**: Lazy loading enabled

### 5. Hero Module
**Purpose**: Full-width hero sections with advanced layout options
- **Features**:
  - Eyebrow, header, and content text
  - Multiple button styles with icons
  - Background image support
  - Glass effect toggle for images
  - Accent image positioning (top-left, top-right, bottom-left, bottom-right)
  - Orientation options (normal/inverted)
  - Column split control (1-100%)
  - Overlay and animation options
- **Styling**: Customizable spacing, colors, borders, circular image option

### 6. Mega Menu Module
**Purpose**: Advanced navigation with rich content display
- **Features**:
  - HubSpot menu integration
  - Image and heading text support
  - Column groups with headings and items
  - Icon or image support for menu items
  - Shortcuts section (up to 3 items)
  - Heading order inversion
- **Content**: Rich text headings, external links, image support

### 7. Menu Module
**Purpose**: Standard navigation menu with dropdown support
- **Features**:
  - HubSpot menu integration
  - Configurable menu levels (1-3)
  - Dropdown styling options
  - Text and background color customization
  - Border styling for dropdowns

## Templates

### Page Templates
- **Home**: Landing page with hero, scrolling content, cards, and CTA sections
- **Blog Index**: Blog listing page
- **Blog Post**: Individual blog post template
- **Contact**: Contact page template
- **Landing Page**: Generic landing page template
- **Inner**: Standard inner page template

### System Templates
- **404**: Error page
- **500**: Server error page
- **Search Results**: Search functionality
- **Membership**: Login, register, password reset pages
- **Subscription**: Preferences and confirmation pages

## Sections

### Available Sections
- **Hero Banner**: Full-width banner with animated image accents
- **Scrolling Content Block**: Content with scroll effects
- **Cards**: Card-based content layout
- **Call to Action**: CTA section
- **Form**: Form integration section

## CSS Architecture

### File Structure
```
css/
├── components/
│   ├── _default-modules.css
│   ├── _footer.css
│   └── _header.css
├── elements/
│   ├── _buttons.css
│   ├── _forms.css
│   ├── _tables.css
│   └── _typography.css
├── generic/
│   ├── _normalize.css
│   └── _reset.css
├── objects/
│   ├── _containers-dnd.css
│   └── _layout.css
├── templates/
│   ├── blog.css
│   └── system.css
├── utilities/
│   ├── _animation.css
│   └── _helper.css
├── main.css
└── theme-overrides.css
```

## JavaScript Features

### Main Functionality
- **AOS Integration**: Animate On Scroll library for smooth animations
- **jQuery Support**: Optional jQuery inclusion
- **Custom Scripts**: Theme-specific JavaScript functionality

## Browser Support

- **Responsive Breakpoints**: Mobile (max-width: 767px)
- **Modern Browsers**: Chrome, Firefox, Safari, Edge
- **Mobile Optimization**: Touch-friendly interactions

## Installation & Usage

1. **Upload to HubSpot**: Import the theme files to your HubSpot portal
2. **Configure Theme Settings**: Customize colors, fonts, and spacing in the theme editor
3. **Create Content**: Use the available modules and sections to build pages
4. **Customize**: Modify CSS and JavaScript as needed for your brand

## Development

### Prerequisites
- HubSpot CMS access
- Knowledge of HubL templating language
- CSS/JavaScript customization skills

### Customization
- **Theme Settings**: Modify `fields.json` for new theme options
- **Module Development**: Create new modules in the `modules/` directory
- **Styling**: Update CSS files in the `css/` directory
- **Templates**: Modify or create new templates in the `templates/` directory

## Support & Documentation

- **Author**: WebScouts
- **Website**: https://thewebscouts.com
- **Email**: hello@thewebscouts.com
- **Documentation**: https://developers.hubspot.com/docs/cms/building-blocks/themes/hubspot-cms-boilerplate

## License

See `license.txt` for detailed licensing information.

---

*Voyageurs Theme - Where retro meets modern, creating unforgettable digital experiences.*
