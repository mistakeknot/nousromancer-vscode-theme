# Nousromancer

Black, millennial pink, electric blue, and violet.

This package ships a VS Code color theme extension so Hermes Desktop users can install the palette from **Settings → Appearance → Theme** using the VS Code Marketplace installer.

## Hermes Desktop install

After the extension is published to the Visual Studio Marketplace, paste this id into Hermes Desktop's theme installer:

```text
mistakeknot.nousromancer-theme
```

Then click **Install**. Hermes Desktop reads the extension's contributed VS Code color themes and converts them into a desktop palette.

## VS Code install

Install the extension from the Visual Studio Marketplace, then select one of:

- **Nousromancer** — dark palette
- **Nousromancer Light** — light palette

## Palette

- Dark background: `#08060D`
- Millennial pink: `#F4A7C8`
- Electric blue: `#8BB8FF`
- Violet: `#A78BFA`

## Development

```bash
npm install
npm run package
```

The package command produces a `.vsix` file that can be installed locally in VS Code or published with `vsce publish`.
