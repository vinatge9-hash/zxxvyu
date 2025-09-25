# Niyantri Cafe - Coffee Website

This project contains a complete, responsive coffee shop website generated for the category Coffee Shop with the business name: Niyantri Cafe.

Pages included:
- index.html (Home)
- menu.html (Menu)
- about.html (About Us)
- contact.html (Contact)

Key implementation notes:
- All pages use Tailwind CSS via CDN and rely on Tailwind utility classes only.
- 100% Tailwind classes; no external CSS files or <style> blocks.
- Semantic HTML5 structure: header, nav, main, section, article, footer.
- Background hero on Home page uses a category-appropriate image placeholder:
  style='background-image: url("https://images.pexels.com/photos/5864233/pexels-photo-5864233.jpeg?auto=compress&cs=tinysrgb&h=650&w=940");'
- Font system is category-aware, using fonts per the design system: Montserrat for headings and Open Sans for body text (via placeholder classes like font-[Montserrat] and font-[Open Sans]). These placeholders will be interpreted by the rendering layer to apply the correct font-face.
- Category colors are applied using Tailwind arbitrary colors (e.g., bg-[#3C2415] for Primary coffee tones, bg-[#D2B48C] for latte accents).

If you’d like any tweaks (additional pages, different menu items, or adjusted branding), tell me and I’ll update the build accordingly.