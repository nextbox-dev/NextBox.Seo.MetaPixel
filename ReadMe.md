# NextBox.Seo.MetaPixel

> A package to integrate [Meta-Pixel](https://www.facebook.com/business/tools/meta-pixel) into Neos.

## Authors & Sponsors

Enes Erk - enes.erk@nextbox.dev  

## Installation

```
composer require nextbox/neos-seo-meta-pixel
```

## Configuration

Configure the tracking-id in Settings.yaml:

```yaml
NextBox:
  Seo:
    MetaPixel:
      metaPixelId: ''
```

Or add the mixin to your root page:

```yaml
'Foo.Bar:RootPage':
  superTypes:
    'NextBox.Seo.MetaPixel:Mixin.MetaPixelConfig': true
```
