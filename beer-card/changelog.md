## 0.2.2
Added support for custom style so you can inject things like background image.

```yaml
- type: custom:beer-card
  title: Untappd Wishlist
  entity: sensor.untappd_wishlist
  icon: mdi:heart
  style: "background-image: url('/local/untapped.png')"
  attribute: list
```

## 0.1.2
Added support for images for icon. Supported images: png, jpg, svg, gif

```yaml
- type: custom:beer-card
  title: Untappd Wishlist
  entity: sensor.untappd_wishlist
  icon: /local/icons/untappd.png
```

## 0.0.2
Initial release that supports versioning