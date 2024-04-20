# Fedora Cloud images built with KIWI

This project builds various derivative Fedora Cloud images using kiwi.

## Image variants

Please look at [`VARIANTS`](/VARIANTS.md) for details on the available
configurations that can be built.

## Image build quickstart

Set up your development environment and run the image build (substitute `<image_type>` and `<image_profile>` for the appropriate settings):

```bash
# Install kiwi
[]$ sudo dnf --assumeyes install kiwi
# Run the image build
[]$ sudo ./kiwi-build --image-type=<image_type> --image-profile=<image_profile> --output-dir ./outdir
```

## Licensing

These descriptions are licensed under the Apache Software License, version 2.0. See `LICENSE` for details.
