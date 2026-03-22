# Teardown: Rivian AXM 1.0

![header_image](rivian_axm_1.0_teardown_header_photo_v2.png)

This repository holds notes and info about my teardown of the Rivian Autonomy eXperience Module (AXM) 1.0. The module was removed from a 2022 Rivian R1S.

If you'd like to read it, the main blog post can be found here: https://www.hakstuff.net/blog/teardown-rivian-r1s-axm-module

## Component Listings

I've created four separate markdown files to list the components present on each of the device's PCBs. While it's not _all_ of the components, I listed a majority of the ICs that I could read.

- XMM PCB components: [components_XMM.md](components_XMM.md)
- ACM PCB components: [components_ACM.md](components_ACM.md)
  - VLM PCB components: [components_VLM.md](components_VLM.md)
  - VPM PCB components: [components_VPM.md](components_VPM.md)

## PCB Photos

The 'pcb_photos' directory includes a number of labeled PCB photos that coincide with the component listings.

The images that are named "Labeled-Named" have each of the components named and color-coded to their general category of use. Serial bus components, storage, processors, ethernet, video decoding, etc.

The images that are just named "Labeled" and use the black-and-green color scheme only identify the silkscreen component markings for each labeled component. For example, these diagrams show that component U33 on the ACM PCB is the NXP Cortex-A72 microcontroller.

I'm hoping the set of images proves useful to someone - I included the PCB markings so that it's easier to talk about components. Ex: "My ACM's Micron RAM has a hole burned in it." -> "Oh no, which RAM though?" -> "It's marked U9 on the PCB".