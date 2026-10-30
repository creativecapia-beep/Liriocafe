---
name: Lirio Café Artisanal System
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#50453e'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#82746d'
  outline-variant: '#d4c3ba'
  surface-tint: '#79573f'
  primary: '#553722'
  on-primary: '#ffffff'
  primary-container: '#6f4e37'
  on-primary-container: '#eec1a4'
  inverse-primary: '#eabda0'
  secondary: '#7b43af'
  on-secondary: '#ffffff'
  secondary-container: '#c78cfe'
  on-secondary-container: '#551889'
  tertiary: '#583610'
  on-tertiary: '#ffffff'
  tertiary-container: '#734d25'
  on-tertiary-container: '#f4c08e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc6'
  primary-fixed-dim: '#eabda0'
  on-primary-fixed: '#2d1604'
  on-primary-fixed-variant: '#5f402a'
  secondary-fixed: '#f1dbff'
  secondary-fixed-dim: '#deb7ff'
  on-secondary-fixed: '#2d0050'
  on-secondary-fixed-variant: '#622895'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#f0bd8b'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#623f18'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Outfit
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Outfit
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Outfit
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  margin: 1.25rem
  margin-md: 2rem
  margin-lg: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses the warmth, indulgence, and intimate nostalgia of a boutique Argentine patisserie and specialty coffee roastery. It balances Rioplatense warmth—characterized by leisurely afternoon meriendas, sweet dulce de leche pairings, and genuine hospitality—with a clean, contemporary specialty coffee sensibility.

The visual style blends refined editorial elegance with tactile warmth:
- **Atmosphere**: Velvety, inviting, and comforting. The interface evokes porcelain coffee cups, warm steamed milk, fresh laminated pastries, and fragrant lavender sprigs.
- **Editorial Contrast**: Sophisticated high-contrast serifs bring artisanal credibility, while geometric modern sans-serifs ensure rapid ordering speed, legible menus, and tactile thumb taps.
- **Emotional Intent**: Evoke cravings, relaxation, and bespoke craftsmanship without clinical stiffness.

## Colors

The palette establishes an appetizing balance between deep roasted espresso beans and botanical pastel lilac, supported by velvety creams and toasted pastry tones:

- **Primary (`#6F4E37` - Roast Espresso)**: Anchors structural hierarchy, primary action items, key headers, and core brand moments. Provides robust contrast and earthy sophistication.
- **Secondary (`#B47AEA` - Pastel Lilac)**: Directly drawn from the brand identity, used for expressive highlights, interactive badges, special combo highlights, selection chips, and delicate romantic touches.
- **Tertiary (`#D4A373` - Honey / Toasted Medialuna)**: Accents seasonal specials, pricing tags, rating badges, and warm promotional highlights.
- **Neutral Surface (`#FAF6F0` - Whipped Crema)**: A creamy off-white canvas that replaces harsh digital whites with warm, milk-steamed tactile comfort.
- **Deep Espresso Neutral (`#3D271D`)**: Used for maximum legibility body copy and crisp subtext against cream containers.

## Typography

The typographic system creates an interplay between historic patisserie tradition and clean, mobile-first operational clarity:

- **Playfair Display**: Applied to narrative hero banners, collection headers, signature menu drink titles, and section greetings. Its pronounced thick-to-thin transitions and graceful curves mirror artisanal craft.
- **Outfit**: Powers menus, item modifiers, cart drawers, prices, and tactile interactive elements. Its open apertures, geometric precision, and balanced proportions ensure quick scannability during busy morning orders.
- **Numbers & Prices**: Rendered consistently in `Outfit` semibold or bold to maintain numeric clarity, tabular alignment, and immediate price recognition.

## Elevation & Depth

Visual depth is achieved through warm, diffused ambient shadows infused with coffee pigments, avoiding harsh artificial grays:

- **Level 0 (Flat Canvas)**: Neutral surface `#FAF6F0` (crema).
- **Level 1 (Cards & Menu Containers)**: Raised via `#FFFDF9` surface with a subtle tinted shadow: `0 2px 10px rgba(61, 39, 29, 0.04)` and an ultra-subtle border `rgba(111, 78, 55, 0.08)`.
- **Level 2 (Interactive Floating Bars & Sticky Filters)**: Elevated with `0 8px 24px rgba(61, 39, 29, 0.08)`.
- **Level 3 (Modal Sheets, Pastry Customization Drawer)**: Backdrop blur `8px` overlaid with `rgba(61, 39, 29, 0.25)` and drawer elevation `0 -8px 32px rgba(61, 39, 29, 0.12)`.

## Shapes

The shape system embraces soft, pillowy contours inspired by porcelain saucers, round baked alfajores, and the circular mark of the brand:

- **Base Radius (`0.5rem` / 8px)**: Applied to input elements, small counters, and utility controls.
- **Container Radius (`1rem` / 16px)**: Applied to product cards, combo promo boxes, and category tiles.
- **Signature Radius (`1.5rem` / 24px - `rounded-xl`)**: Applied to bottom sheets, feature dialogs, and hero image frames.
- **Pill Radius (`9999px`)**: Reserved exclusively for category filter chips, action pills, quantity steppers, and floating bottom order buttons.

## Components

### Buttons
- **Primary Action**: Solid roasted coffee background (`#6F4E37`) with whipped white text (`#FFFDF9`), rounded pill shape, min-height `48px` for generous thumb targets, lifting gently on tap.
- **Secondary / Combo Action**: Pastel lilac background (`#B47AEA`) with deep roast text (`#3D271D`) or white text, communicating delightful specialty pairings.
- **Ghost / Tertiary**: Transparent base with hairline espresso border (`rgba(111, 78, 55, 0.2)`) and coffee-toned typography.

### Chips & Category Tabs
- **Default State**: Soft crema surface (`#FFFDF9`) with delicate coffee border and `#3D271D` text.
- **Active State**: Pastel lilac fill (`#F6EEFF`) with deep lilac border (`#9353D3`) and lilac bold text, accompanied by smooth sliding transition indicator.

### Menu Cards & Combos
- **Card Surface**: Pure whipped cream surface (`#FFFDF9`) framed by subtle rounded borders (`rounded-lg`).
- **Media Presentation**: Aspect ratio 4:3 with soft inner corners, displaying baked pastries and latte art.
- **Price Presentation**: Emphasized in `Outfit` bold with optional honey-gold badge (`#D4A373`) for combos (e.g., "Café con 2 Medialunas").

### Form Fields & Steppers
- **Inputs**: Cream filled (`#FAF6F0`) with a smooth 0.5rem radius, shifting to a lilac outline (`#B47AEA`) upon focus.
- **Quantity Steppers**: Pill-shaped counter blocks with deep coffee circular buttons (`+` and `-`) flanking high-contrast center numbers.

### Lists & Menu Items
- Clean divided rows utilizing dotted or soft dividers (`rgba(111, 78, 55, 0.1)`), aligning product name and dietary tags on the left with prominent pricing on the right.