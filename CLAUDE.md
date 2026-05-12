# Agentic AI - Styles Documentation

## Design System

### Color Palette
- **Primary Pink**: `#ff69b4` - Main brand color
- **Pink Variants**: Light (`#ffb6d9`), Dark (`#d4477e`), Pale (`#fff0f5`), Accent (`#ff1493`)
- **Text**: Dark (`#2d2d2d`), Light (`#666`)
- **Background**: White (`#ffffff`)

### Spacing Scale
Uses CSS custom properties: `xs(8px)`, `sm(16px)`, `md(24px)`, `lg(32px)`, `xl(48px)`, `xxl(80px)`

### Typography
- **Primary Font**: Poppins (sans-serif) - body text
- **Display Font**: Playfair Display (serif) - headings and logo
- **Base Line Height**: 1.6

## Layout Structure

### Components
1. **Navbar**: Fixed, translucent with backdrop blur, pink shadow
2. **Hero**: Split-screen grid (1fr 1fr), gradient background, full viewport height
3. **Features**: 3-column grid, hover lift effect, pink pale cards
4. **Collection**: 4-column product grid, image cards with hover animations
5. **About**: 2-column text/image layout
6. **Testimonials**: 3-column card grid on pale pink background
7. **Newsletter**: Gradient pink background, centered form with rounded inputs
8. **Footer**: Dark background, 3-column layout

### Interactions
- Smooth transitions (0.3s ease) on hover states
- Transform effects: `translateY` for lift animations
- Box shadows with pink tints for depth
- Gradient buttons with enhanced shadows on hover

## Responsive Design
Mobile breakpoint at 768px:
- All grids collapse to single column
- Hero image reduces to 50vh
- Typography scales down
- Newsletter form stacks vertically

## Key Patterns
- Rounded corners (15-50px border-radius)
- Pink-tinted shadows for brand consistency
- Gradient overlays for visual interest
- Card-based content presentation with hover states
