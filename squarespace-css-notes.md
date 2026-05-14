# How To Use The Squarespace CSS

File:
`squarespace-custom.css`

In Squarespace:
1. Go to **Website**.
2. Open **Pages** and then **Website Tools** or **Settings**, depending on your Squarespace version.
3. Open **Custom CSS**.
4. Paste the full contents of `squarespace-custom.css`.
5. Save.

## Optional Custom Classes

Use these in Squarespace if you add code blocks or if your template lets you add section/block custom classes:

- `gc-section-cream`
- `gc-section-dark`
- `gc-eyebrow`
- `gc-brand-line`
- `gc-card`
- `gc-chip-list`
- `gc-chip`
- `gc-service-list`
- `gc-service-row`
- `gc-price`
- `gc-hours-list`
- `gc-hours-row`
- `gc-social-grid`
- `gc-social-link`
- `gc-portfolio-grid`
- `gc-feature-credit`

## Example Service Row HTML Block

```html
<div class="gc-service-list">
  <div class="gc-service-row">
    <div>
      <strong>Full Highlight</strong>
      <p>Mostly for first time clients or someone looking for a big change.</p>
    </div>
    <div class="gc-price">$235</div>
  </div>
</div>
```

## Example Portfolio Grid HTML Block

```html
<div class="gc-portfolio-grid">
  <img src="IMAGE_URL" alt="Portfolio image description">
  <img src="IMAGE_URL" alt="Portfolio image description">
  <img src="IMAGE_URL" alt="Portfolio image description">
</div>
```
