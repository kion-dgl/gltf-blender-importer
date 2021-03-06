<p align="center">
<img src="doc/hero.png" alt="Fox model by PixelMannen, rigging by Tom Kranis">
</p>

<h2 align=center>
gltf-blender-importer
<a href="https://travis-ci.org/ksons/gltf-blender-importer"><img src="https://travis-ci.org/ksons/gltf-blender-importer.svg?branch=master" alt="Build status"/></a>
</h1>

<p align=center>Un-official Blender importer for glTF 2.0.</p>

<p align=center>
<a href="https://github.com/ksons/gltf-blender-importer/releases/download/v0.5.0/io_scene_gltf_ksons-0.5.0.zip"><img src="./doc/download_button.png"></a>
</p>

### Installation
Click the "Download Add-on" button above to download the ZIP containing the
add-on. In Blender, navigate to **File > User Preferences... > Add-ons** (or
**Edit > User Preferences... > Add-ons**) and install that ZIP with the
**Install Add-on from File...** button (or **Install...** button). Then type
'glTF' in the search bar and tick the checkbox next to **KSons' glTF 2.0
Importer** to enable it.

You can now import glTFs with **File > Import > KSons' glTF 2.0 (.glb/.gltf)**.

<p align="center"><img src="doc/addon-install.png"></p>

See [INSTALL.md](INSTALL.md) for further installation instructions.

### Supported Extensions
* KHR_materials_pbrSpecularGlossiness
* KHR_lights_punctual
* KHR_materials_unlit
* KHR_texture_transform
* MSFT_texture_dds
* EXT_property_animation (extension abandoned upstream)

### Unsupported Features
* Inverse bind matrices are ignored

### Samples Renderings
![BoomBox](doc/boom-box.jpg)
![Corset](doc/corset.jpg)
![Lantern](doc/lantern.jpg)

### See also
Official Importer-Exporter: [glTF-Blender-IO](https://github.com/KhronosGroup/glTF-Blender-IO)
