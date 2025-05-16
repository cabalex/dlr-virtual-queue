# [dlr-virtual-queue](https://cabalex.github.io/dlr-virtual-queue)

This is a public archive of all existing virtual queue assets at DLR, since I don't think anyone has archived them in an easy-to-view way. Currently, it includes:

- Disneyland
  - Rise of the Resistance
  - Mickey and Minnie's Runaway Railway (`MMRR`)
  - Indiana Jones Adventure (`indy`)
  - Haunted Mansion Holiday (`villainsGrove`)
  - Tiana's Bayou Adventure (`TianasBA`)
- Disney California Adventure
  - Web Slingers: A Spider-Man Adventure (`webslingers`)
  - Generic DCA [World of Color, Rogers: The Musical] (`WILB_DCA`)
  - Unused variant for World of Color (`World_of_Color`)
- Other
  - RunDisney (`WIL.B_runDisney`)
  - "Generic" unused testing assets (`generic`)

_Note: Stages with duplicate animations and taglines are skipped during playback._

The animations are Lottie files that are played back on the Virtual Queue "confirmation" screen, showing the user how far they've progressed in the virtual queue and when their boarding group will be called.

### Archival notes

To archive this repository yourself, you can download the repository as ZIP:

- If the files are still up, you can open the `index.html` file in your browser, open the console (CTRL+SHIFT+J) and type `USE_LOCAL_FILES = false`. Then, select an animation to fetch from Disney's CDN.
- Otherwise, you will have to setup a local http server to serve the contents of this repository (due to security limitations).

All assets are property of Disney.
