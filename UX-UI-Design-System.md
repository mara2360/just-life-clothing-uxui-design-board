# Design System

## Brand Direction

Just Life should feel clean, warm, and wearable. The UI balances editorial clothing imagery with practical shopping controls.

## Color Tokens

| Token | Value | Use |
| --- | --- | --- |
| Cream | `#f7f2e8` | Main page background |
| Paper | `#fffaf0` | Cards, panels, forms |
| Ink | `#101820` | Primary text, header actions, dark sections |
| Muted | `#6f655d` | Secondary copy and metadata |
| Clay | `#9b5c47` | Sale, active highlights, warm accent |
| Olive | `#66745f` | Newsletter and subtle badge moments |
| Sage | `#dfe7d7` | Soft hover states |
| Blush | `#f3d7c6` | Soft secondary accent |
| Line | `rgba(16, 24, 32, 0.14)` | Borders |

## Typography

- Brand and display headings: Georgia or another classic serif.
- Body and UI text: Arial or another neutral sans serif.
- H1: large editorial scale on home hero and collection toppers.
- H2: section scale, used sparingly.
- Buttons, tabs, badges, and labels: uppercase, bold, compact.

## Spacing

- Page horizontal padding: `clamp(20px, 5vw, 72px)`.
- Section vertical spacing: `72px` desktop, `40px` to `56px` mobile.
- Product grid gap: `18px` to `24px`.
- Card radius: `8px` maximum.
- Form and button height: `46px` minimum.

## Components

### Header

- Sticky top navigation.
- Brand at left, navigation centered, cart actions at right.
- Mobile navigation wraps below the brand row.

### Announcement Bar

- Short value statements.
- Dark background for contrast.
- On mobile, reduce to the strongest single message.

### Hero

- Full-bleed apparel photography.
- Text overlays directly on image.
- Primary department CTAs.

### Product Grid

- Four columns on wide screens.
- Three columns on medium screens.
- Two columns on small tablets.
- One column on narrow phones.

### Product Card

- Product image first.
- Wishlist button at top right.
- Badge at top left only when useful.
- Product type, name, price, sizes, and quick add.

### Cart Panel

- Opens from the bag button.
- Shows item name, size, price, remove action.
- Empty state uses short plain text.

## Interaction Rules

- Hover states should increase contrast, not create layout shift.
- Add-to-cart requires size selection.
- Cart total and count update immediately.
- Form submission should provide visible confirmation.
- Tap targets should be at least `38px` high, with primary actions at least `46px`.

## Accessibility Notes

- Product images need descriptive alt text.
- Icon-only buttons require `aria-label`.
- Cart button should keep `aria-expanded` updated.
- Use visible focus states for keyboard users.
- Avoid text over low-contrast image areas without an overlay.
