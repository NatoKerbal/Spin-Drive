# SpinDrive

"Following on from Dr. Grace's discovery, we've built an IR emitter set to the wavelength of CO2, which attracts the astrophage to this revolver face. The drive then rotates outwards, yeah? We increase the IR, the astrophage get excited, thrust the ship forward, and so on and so on." — Dr. Narender Sood, *Project Hail Mary (2026)*

A Kerbal Space Program parts mod inspired by Andy Weir's *[Project Hail Mary](https://en.wikipedia.org/wiki/Project_Hail_Mary)*.
Adds astrophage-powered propulsion and related parts to the game.

![The SpinDrive on a KSP model of the movie's Hail Mary.](Media/screenshot81.png)

(This is an unofficial fan-made mod and is not affiliated with Andy Weir or any Project Hail Mary production.)

## Parts

- **TC-96 "Komarov" Spin Drive**
- **TC-96-950 "DuBois" Spin Drive Cluster**
- **DuBois Astrophage Generator**

A custom **EnrichedAstrophage** resource is added alongside B9 Part Switch support for
fuel-switching it into compatible tanks.

## Dependencies

These mods are **required**. There is no CKAN support yet; you'll need to install each one (and their own dependencies) before installing SpinDrive in order for the mod to work.

- [Far Future Technologies](https://github.com/post-kerbin-mining-corporation/FarFutureTechnologies)
- [B9 Part Switch](https://github.com/blowfishpro/B9PartSwitch)

## Compatibilities
These mods are **not required**. These will probably go in as recommendations in CKAN. You should still get these installed, though.

- [Waterfall](https://github.com/KSPModStewards/Waterfall)
- [Community Tech Tree](https://github.com/post-kerbin-mining-corporation/CommunityTechTree)

## Installation

Download the ZIP from this repository and extract it. Inside the extracted folder you will find a `GameData` folder.
**Copy the `SpinDrive` folder from inside it directly into your KSP installation's own `GameData` folder.**

When done correctly, the path should look like this:
```
KerbalSpaceProgram/
└── GameData/
    ├── SpinDrive/
    │   ├── SpinDrive.cfg
    │   ├── SpinDriveCluster.cfg
    │   └── ...
    ├── Squad/
    ├── YourOtherMods/
    └── ...
```

## Known Issues

<!-- **Astrophage tank model path**: The standalone astrophage tank part references a model path from an unrelated mod (`KODS/Parts/Astra/...`). Without that mod installed, the part renders as a placeholder mesh.-->
- *Issues will  be listed here as they are found.*

## Credits

- **[NoLifeJordan](https://github.com/nolifejordan)**, original mod author
- **[NatoKerbal](https://github.com/NatoKerbal)**, repository owner
- **[QuantumsHevy](https://github.com/QuantumsHevy)**, contributor
- ***Project Hail Mary (2026)***, main inspiration

![A rear view of a KSP model of the movie's Hail Mary.](Media/screenshot78.png)

## License

[MIT License](./LICENSE)
