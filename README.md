<a href="https://www.offen.dev/">
  <img src="https://offen.github.io/press-kit/avatars/avatar-OFWA-header.svg" alt="Offen Fair Web Analytics logo" title="Offen Fair Web Analytics" width="60px"/>
</a>

# DigitalOcean
DigitalOcean Marketplace image for Offen Fair Web Analytics

## Building the image

### Prerequisites

To build the Image, you will need to have [Packer][packer] installed and have a valid DigitalOcean API Token exported as `DOTOKEN`.

[packer]: https://packer.io/

### Building the image on DigitalOcean

Use `packer build`:

```
packer build marketplace-image.json
```
