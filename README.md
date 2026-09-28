# email-signatures

Email signatures matching [halffive.co](https://halffive.co): navy card, cream type, orange accent.

| File                       | Use for                                                        |
| -------------------------- | -------------------------------------------------------------- |
| `half_five_signature.html` | Everyone. Sends as `fred@halffive.co`.                         |
| `moor_labs_signature.html` | Clients who know us as Moor Labs. Says Moor Labs and uses `fred@moorlabs.co.za`. |

The photo and logo mark are hosted on GitHub Pages, in the `signature/` folder of [fwmoor/fwmoor.github.io](https://github.com/fwmoor/fwmoor.github.io):

- https://fwmoor.github.io/signature/fred-moor.jpg (240×240, shown at 64px)
- https://fwmoor.github.io/signature/half-five-mark.png (72×72, shown at 17px)

To change an image, replace it there and push. Emails you've already sent use the same links, so they'll show the new image too.

## Install in Gmail

1. Open the signature file in Chrome.
2. Press `Cmd+A`, then `Cmd+C`.
3. In Gmail, go to **Settings → See all settings → General → Signature → Create new**, paste, and save at the bottom of the page.
4. Under **Signature defaults**, choose the signature for new emails and replies. If you send from both addresses, set a default for each one.
5. Tick **Insert signature before quoted text in replies and remove the "--" line**.

## Email client notes

- Everything is tables with inline styles. Gmail strips `<style>` blocks, and Outlook for Windows renders with Word.
- The card has its own navy background, so it looks the same in light and dark mode instead of being recoloured by the client.
- Fonts fall back to Georgia (for Young Serif) and Helvetica/Arial (for Host Grotesk). Email clients don't load web fonts.
- The logo mark is a PNG because Gmail and Outlook don't display SVG.
- Outlook for Windows shows square corners and hides images until the recipient allows them. The text still reads fine without them.
