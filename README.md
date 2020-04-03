# digitalocean
DigitalOcean Marketplace image for Offen

## Building the image

### Prerequisites

To build the Image, you will need to have [Packer][packer] installed and have a valid DigitalOcean API Token exported as `DOTOKEN`.

[packer]: https://packer.io/

### Building the image on DigitalOcean

Use `packer build`:

```
packer build marketplace-image.json
```
