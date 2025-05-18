# [dlr-virtual-queue](https://cabalex.github.io/dlr-virtual-queue)

This is a public archive of all existing Virtual Queue (VQ) assets at the DLR, since I don't think anyone has archived them in an easy-to-view way. Currently, it includes:

| Name                                 | ID                       | Animation ID      | Park | Last Updated (CDN) | Last Updated (App) |
| ------------------------------------ | ------------------------ | ----------------- | ---- | ------------------ | ------------------ |
| Rise of the Resistance               | `rise-of-the-resistance` | _(none)_          | DL   | April 18, 2019     | August 5, 2021     |
| Mickey and Minnie's Runaway Railway  | `mmrr`                   | `MMRR`            | DL   | January 17, 2023   | January 27, 2023   |
| Indiana Jones Adventure              | `indiana-jones`          | `indy`            | DL   | May 10, 2021       | May 11, 2021       |
| Haunted Mansion Holiday              | `haunted_mansion`        | `villainsGrove`   | DL   | July 16, 2024      | July 30, 2024      |
| Tiana's Bayou Adventure              | `tiana_grand`            | `TianasBA`        | DL   | May 30, 2024       | November 7, 2024   |
| Web Slingers: A Spider-Man Adventure | `webslingers`            | `webslingers`     | DCA  | May 21, 2021       | August 5, 2021     |
| World of Color                       | `woc-sol`                | `WILB_DCA`        | DCA  | April 13, 2022     | September 25, 2023 |
| Rogers: The Musica l                 | `hyperion`               | `WILB_DCA`        | DCA  | April 13, 2022     | August 21, 2023    |
| World of Color (un used)             | `woc-blue`               | `World_of_Color`  | DCA  | January 3, 2025    | January 15, 2025   |
| RunDisney                            | `run-disney`             | `WIL.B_runDisney` |      | September 22, 2023 | January 22, 2025   |
| Generic                              | `default`                | `generic`         |      | July 18, 2020      | January 31, 2021   |
| Generic (DL)                         | _(not used)_             | `dlr`             | DLR  | November 12, 2020  | _(not in app)_     |
| Generic (DCA)                        | _(not used)_             | `dca`             | DCA  | November 12, 2020  | _(not in app)_     |

_Note: Stages with duplicate animations and taglines are skipped during playback._

The animations are Lottie files that are played back on the Virtual Queue "confirmation" screen, showing the user how far they've progressed in the virtual queue and when their boarding group will be called.

Along with transition and looping animations, they can also include "idle" and "humor" animations to add additional variety to the queue waiting experience (though this is only used on Rise of the Resistance's VQ).

### Omitted entries

Disney also uses virtual queues at events such as D23, but they don't make unique assets for them. I have omitted these entries from the archive since they use static images, and aren't particularly interesting. They are:

- D23
  - Disney Studio Store Hollywood (`d23-dssh`) [Uses this image](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23/disney-store-studio-hollywood/dhs-4x.jpg)
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy D23: The Ultimate Disney Fan Event 2024 while you wait._
    - (5) _Success! You’re ready to enter._
  - Disney Munchlings (`d23-ml`) [Uses this Lottie file](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23-4/VQ_D23_Munchlings_v2.json), but it's a static image for all stages
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy the D23 Expo while you wait_
    - (5) _Success! You’re ready to enter._
  - Mickey's of Glendale (`d23-mog`) [Uses this image](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23/mog/mog-store-4x.jpg)
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy D23: The Ultimate Disney Fan Event 2024 while you wait._
    - (5) _Success! You’re ready to enter._
  - Mickey's of Glendale x D23 Expo Shop (`d23-moge`) [Uses this Lottie file](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23-3/VQ_D23_D23ExpoShop_v1.json), but it's a static image for all stages
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy the D23 Expo while you wait_
    - (5) _Success! You’re ready to enter._
  - Mickey's of Glendale Pin Store (`d23-mogp`) [Uses this image](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23/mog-pin-store/mog-pin-4x.jpg)
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy D23: The Ultimate Disney Fan Event 2024 while you wait._
    - (5) _Success! You’re ready to enter._
  - D23 Marketplace (`d23-mp`) [Uses this image](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23/marketplace/d23-marketplace-progress-4x.jpg)
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy D23: The Ultimate Disney Fan Event 2024 while you wait._
    - (5) _Success! You’re ready to enter._
  - D23 Expo Marketplace - 3rd Floor Limited Edition Annex (`d23-mple`) [Uses this Lottie file](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23-6/VQ_D23_D23ExpoMarketplace3rdFloor_v1.json), but it's a static image for all stages
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy the D23 Expo while you wait_
    - (5) _Success! You’re ready to enter._
  - The Walt Disney Company Store (`d23-wdc`) [Uses this image](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23/the-walt-disney-co-store/twdc-store-4x.jpg)
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy D23: The Ultimate Disney Fan Event 2024 while you wait._
    - (5) _Success! You’re ready to enter._
  - The Walt Disney Company Pin Store (`d23-wdcp`) [Uses this image](https://cdn1.parksmedia.wdprapps.disney.com/vision-dam/digital/parks-platform/parks-standard-assets/virtual-que/d23/the-walt-disney-co/twdc-pin-4x.jpg)
    - (0) _You're in the virtual queue!_
    - (1-4) _Enjoy D23: The Ultimate Disney Fan Event 2024 while you wait._
    - (5) _Success! You’re ready to enter._
  - Magic Key merchandise pickup at Hyperion Theater Courtyard (`magic-key`)
    - Uses the same animations and taglines as World of Color (`WILB_DCA`)
  - Tiana's Bayou Adventure Cast Previews (`tiana-cast-V2`) and Tiana's Bayou Adventure Magic Key Previews (`tiana-magic-key`)
    - Uses the same animations and taglines as the public VQ (`tiana-grand`)
  - World of Color, Yellow entrance (`woc-yellow`)
    - Uses the same animations and taglines as the Yellow/Blue entrance (`woc-sol`)
    - Directions point to "Head to the yellow section by the Golden Zephyr" instead of "Head to either the Yellow or Blue entrance".

## Archival notes

To archive this repository yourself, you can download the repository as ZIP:

- If the files are still up, you can open the `index.html` file in your browser, open the console (CTRL+SHIFT+J) and type `USE_LOCAL_FILES = false`. Then, select an animation to fetch from Disney's CDN.
- Otherwise, you will have to setup a local http server to serve the contents of this repository (due to security limitations).

All assets are property of Disney.

## Interesting quirks

Each Virtual Queue asset contains a relative path URL (`/lottie/...`) and an absolute URL (`https://cdn1.parksmedia...`). However, only the absolute path URL is used. This means that sometimes the relative path URL can be completely different from the used path:

- The unused generic DCA assets are located in the relative paths for Haunted Mansion Holiday. However, the second and third stages are located in the `/dlr/` folder instead, and vice versa for the generic DLR assets.
- MMRR was copied from Web Slinger's virtual queue, and maintains its relative path URLs.
- Rise of the Resistance is the only Virtual Queue to use "ambient" animations (differentiated into `humorAnimUrls` and `idleAnimUrls`), of which there are 6 "humor" animations and 9 "idle" animations. You can view them under "Rise of the Resistance - Ambient".
- World of Color naming conventions imply they tested having VQ use Yellow and Blue entrances for Season of Light, the holiday version (`woc-sol`), and found it worked well enough to keep using it.
- All virtual queues have an unused second tagline that does not change.
  - (0) _Your virtual wait has begun._
  - (1-4) _Boarding group waiting to be called_
  - (5) _Your boarding group has been called and you can enter attraction._ (sic)
