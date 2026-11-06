<p align="center">
  <a href="https://morphe.software/add-source?github=ahmetxa/piko-newx">
    <img src="assets/add-to-morphe.svg" alt="Add to Morphe" height="48">
  </a>
</p>

Builds and publishes the NewX patch bundle from [ahmetxa/piko `x-lite`](https://github.com/ahmetxa/piko/tree/x-lite), a fork of the [Piko `x-lite` branch](https://github.com/crimera/piko/tree/x-lite).

## Root mount support

Upstream marks nearly every patch as unavailable when Morphe's root **mount** install is selected,
because a mount keeps the stock manifest and the Piko settings screen (and the downloader folder
picker and notification actions) are components added to the manifest. This fork routes those
components through a registered stock component at runtime, so every patch except **NewX: Clone**
(which changes the package name and cannot be mounted) can be selected in mount mode.

# Credits
- [morphe](https://github.com/MorpheApp) - patcher
- [revanced](https://github.com/ReVanced) - previous patcher
- [j-hc](https://github.com/j-hc) - Project is inspired by j-hc's revanced builder template.
