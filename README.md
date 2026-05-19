# Zinara Digital - Website Source Code

## Overview
This is the complete source code for the Zinara Digital Marketing Agency website, built with React 19, Tailwind CSS 4, and shadcn/ui components.

## Design Philosophy: Afro-Modern Minimalism
- **Typography**: Syne (bold display) + DM Sans (clean body)
- **Color Palette**: Warm off-white backgrounds, deep charcoal text, orange (#E85D04) for CTAs
- **Layout**: Asymmetric split layouts, diagonal section dividers
- **Animations**: Pure CSS fade-up animations on component mount

## Pages Included

### 1. **Home.tsx** (19KB)
- Hero section with trust signals
- Stats band (3× More Leads, 50+ Businesses Served, etc.)
- 6-service grid with icons
- "Why Zinara" split section with analytics image
- Industry tags (Real Estate, Healthcare, Schools, etc.)
- Client testimonials (3 cards with star ratings)
- Team section with image
- Final CTA section (orange background)

### 2. **Services.tsx** (16KB)
- Services hero with call-to-action
- 6 detailed service cards with "What's Included" sections
- Service numbering (01-06)
- Pricing tiers table (KSh 15k / 35k / 65k)
- Industry-specific recommendations
- WhatsApp and contact CTAs

### 3. **About.tsx** (11KB)
- Brand story section
- Core values grid (4 values)
- 5-step process breakdown
- Team introduction
- Trust-building copy focused on Kenyan market
- Call-to-action

### 4. **Contact.tsx** (14KB)
- Contact form with Formspree integration
- WhatsApp CTA (fastest response)
- Phone and email contact options
- Business hours
- "What Happens Next" trust block
- Form validation and submission

### 5. **NotFound.tsx** (1KB)
- 404 error page with branding

## Components

### Global Components
- **Navbar.tsx** - Sticky navigation with mobile menu
- **Footer.tsx** - Full footer with links, social media, contact info
- **WhatsAppButton.tsx** - Floating WhatsApp button (green, bottom-right)
- **AnimSection.tsx** - Reusable fade-up animation wrapper

## Styling

### **index.css** (10KB)
- Global design tokens (Syne + DM Sans fonts)
- Color variables (off-white, charcoal, orange)
- Keyframe animations (@keyframes fadeUp)
- Responsive container utilities
- Tailwind 4 configuration with OKLCH color format

### **index.html**
- Google Fonts integration (Syne, DM Sans)
- SEO meta tags
- Analytics script placeholder
- Favicon configuration

## Key Features

✅ **CRO Optimized**
- Clear value proposition above the fold
- Multiple CTAs (WhatsApp, Contact form, "Get a Free Quote")
- Trust signals (stats, testimonials, team)
- Industry-specific messaging

✅ **SEO Ready**
- Meta tags for all pages
- Semantic HTML structure
- Open Graph tags for social sharing
- Mobile-first responsive design

✅ **Accessibility**
- Semantic heading hierarchy
- ARIA labels where needed
- Keyboard navigation support
- High contrast text colors

✅ **Performance**
- Pure CSS animations (no JavaScript overhead)
- Optimized image loading
- Minimal dependencies
- Fast initial page load

## Installation & Setup

```bash
# Install dependencies
pnpm install

# Start development server
pnpm run dev

# Build for production
pnpm run build

# Preview production build
pnpm run preview
```

## Configuration

### Formspree Integration (Contact Form)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form
3. Replace `YOUR_FORM_ID` in `Contact.tsx` with your form ID

### Contact Details
Update these placeholders across all files:
- Phone: `+254 700 000 000`
- Email: `hello@zinara.co.ke`
- WhatsApp: `+254 700 000 000`

### Brand Customization
Edit `index.css` to customize:
- Primary color (currently orange #E85D04)
- Font families (Syne, DM Sans)
- Spacing scale
- Animation timing

## File Structure

```
pages/
├── Home.tsx           # Homepage with hero, services, testimonials
├── Services.tsx       # Detailed services and pricing
├── About.tsx          # Brand story and team
├── Contact.tsx        # Contact form and information
└── NotFound.tsx       # 404 page

components/
├── Navbar.tsx         # Navigation bar
├── Footer.tsx         # Footer
├── WhatsAppButton.tsx # Floating WhatsApp button
└── AnimSection.tsx    # Animation wrapper component

index.css              # Global styles and design tokens
index.html             # HTML template with meta tags
package.json           # Dependencies and scripts
```

## Dependencies

- **React 19** - UI framework
- **Tailwind CSS 4** - Utility-first CSS
- **shadcn/ui** - Component library
- **Wouter** - Client-side routing
- **Framer Motion** - Animation library (optional)
- **Lucide React** - Icon library

## Deployment

### Manus (Recommended)
- Click "Publish" in the Manus Management UI
- Get automatic domain: `zinara-digital.manus.space`
- Custom domain support available

### Vercel
```bash
vercel deploy
```

### Netlify
```bash
netlify deploy --prod --dir=dist
```

## Next Steps

1. **Connect Formspree** - Enable contact form submissions
2. **Update contact details** - Replace placeholders with real info
3. **Add blog section** - Create a resources/blog page for SEO
4. **Set up analytics** - Connect Google Analytics or Umami
5. **Custom domain** - Bind your own domain (zinara.co.ke)

## Support & Customization

- Modify colors in `index.css` (search for `--primary`, `--accent`)
- Update copy in individual page files
- Add new pages in `pages/` directory
- Create reusable components in `components/`

## License

© 2026 Zinara Digital. All rights reserved.

---

**Built with:** React 19 + Tailwind CSS 4 + shadcn/ui  
**Design:** Afro-Modern Minimalism  
**Target Market:** Kenyan SMBs and digital marketing agencies
