# email-signatures

Email signatures matching [halffive.co](https://halffive.co): photo, an orange rule, the name in serif, and a "Book a free call" button styled like the one on the site.

| File                       | Use for                                                        |
| -------------------------- | -------------------------------------------------------------- |
| `half_five_signature.html` | Everyone. Sends as `fred@halffive.co`.                         |
| `moor_labs_signature.html` | Clients who know us as Moor Labs. Says Moor Labs and uses `fred@moorlabs.co.za`. |

The images are hosted on GitHub Pages, in the `signature/` folder of [fwmoor/fwmoor.github.io](https://github.com/fwmoor/fwmoor.github.io):

- https://fwmoor.github.io/signature/fred-moor.jpg (240×240, shown at 56px)
- https://fwmoor.github.io/signature/cta-chip.png (66×66, the clover circle on the button, shown at 22px)

To change an image, replace it there and push. Emails you've already sent use the same links, so they'll show the new image too.

## Install in Gmail

1. Open the signature file in Chrome.
2. Press `Cmd+A`, then `Cmd+C`.
3. In Gmail, go to **Settings → See all settings → General → Signature → Create new**, paste, and save at the bottom of the page.
4. Under **Signature defaults**, choose the signature for new emails and replies. If you send from both addresses, set a default for each one.
5. Tick **Insert signature before quoted text in replies and remove the "--" line**.

## Email client notes

- Everything is tables with inline styles. Gmail strips `<style>` blocks, and Outlook for Windows renders with Word.
- There's no background colour. Gmail on the web shows email bodies on white even in dark mode, and phone apps in dark mode flip the navy text to light.
- The button is live text on an orange table cell, not an image, so it still reads when images are blocked. Only the clover circle goes blank.
- Fonts fall back to Georgia (for Young Serif) and Helvetica/Arial (for Host Grotesk). Email clients don't load web fonts.
- Images are PNG or JPEG because Gmail and Outlook don't display SVG.
- Outlook for Windows shows square corners and hides images until the recipient allows them. The text still reads fine without them.
