# Retro Terminal HTML Signature

A custom, retro-futuristic HTML email signature inspired by the "Alien" universe (Weyland-Yutani interface) and classic terminal aesthetics.

## Features

*   **Retro Aesthetic:** Monospace fonts, scanline vibe (simulated), and a high-contrast green-on-black color scheme.
*   **Email Safe:** Optimized for compatibility with major email clients like Outlook and Gmail.
    *   Uses solid background colors (`bgcolor`) instead of gradients to ensure dark mode rendering.
    *   Fixed width (550px) layout to prevent stretching on wide screens.
    *   Inline CSS for maximum compatibility.
*   **Responsive-ish:** Designed to look good on desktop and scale down gracefully on mobile devices (within the limits of HTML email tables).
*   **Animated Avatar:** Supports GIF images for a dynamic touch.
*   **Anti-Interference:** Includes `spellcheck="false"` and `translate="no"` attributes to prevent browser/client interference with the technical text.

## Usage

1.  **Open `firma.html`** in a web browser.
2.  **Select All** (Ctrl+A) and **Copy** (Ctrl+C).
3.  **Paste** into your email client's signature settings.
    *   *Note for Outlook:* You may need to paste it into the signature editor directly. If the background looks white in the editor, send a test email to yourself; the dark background usually renders correctly in the actual received email due to the `bgcolor` attribute.

## Customization

To modify the signature, edit `firma.html`:

*   **Links:** Update the `href` attributes in the `<a>` tags.
*   **Images:** Change the `src` URL of the `<img>` tag to your own hosted image (recommended size: 100x100px for the avatar).
*   **Colors:** The design uses `#00cc00` (Primary Green) and `#33cc33` (Secondary Green) on a `#000d00` (Dark) background.

## Compatibility Notes

*   **Outlook:** The layout uses HTML tables and specific attributes (`bgcolor`, `width`) specifically to ensure it renders correctly in Outlook's rendering engine.
*   **Images:** Ensure your images are hosted on a public server (like Postimages, Imgur, or your own hosting) so recipients can see them.
