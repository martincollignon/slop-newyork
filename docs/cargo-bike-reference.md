# Cargo bike reference calibration

Source: [Larry vs Harry EP801 manual, version 3.1](https://cdn.shopify.com/s/files/1/0860/2448/7248/files/eBullitt_EP801-EP801X_Manual_V3-1.pdf?v=1775638133), PDF page 6 (printed page 3), with cockpit and drivetrain details on the following two pages.

The side photograph was extracted from the PDF at its native 3115 × 1353 resolution. The approximate manual pixel picks below refer to that image displayed at 2048 pixels wide. These are modeling estimates, not engineering measurements. Perspective, tyre deformation, and pixel picking introduce small errors.

Scale: 2.43 m overall / (1910 − 183) px = 0.001407 m/px. Ground y = 807 px. Rear axle x = 423 px maps to model z = −0.92 m. Model axes are +Y up, +Z forward, +X drive side.

| Landmark | Image x, y (px) | Model z, y (m) |
| --- | --- | --- |
| Rear axle | 423, 571 | −0.920, 0.332 |
| Front axle | 1734, 631 | 0.925, 0.248 |
| Crank axle | 692, 609 | −0.542, 0.279 |
| Upper derailleur pulley | 390, 651 | −0.966, 0.219 |
| Lower derailleur pulley | 351, 703 | −1.021, 0.146 |
| Seat tube / top tube junction | 606, 320 | −0.663, 0.685 |
| Saddle | 571, 95 | −0.712, 1.002 |
| Steering column / top tube junction | 991, 278 | −0.121, 0.744 |
| Handlebar centre | 1009, 126 | −0.096, 0.958 |
| Front headset top | 1614, 340 | 0.756, 0.657 |
| Front headset bottom | 1630, 418 | 0.778, 0.547 |
| Front light | 1684, 383 | 0.854, 0.597 |

Rear tyre radius ≈ 236 px / 0.332 m; front ≈ 176 px / 0.248 m. Chainring radius ≈ 65 px / 0.0915 m. Largest cassette sprocket radius ≈ 80 px / 0.113 m. Brake rotors use the manual's 180 mm diameter specification. Frame width follows the 460 mm specification; tubing thickness and the open load board are interpreted from the three-quarter photos.

The in-game name is **Cargo bike**. This is a procedural game model inspired by the reference, without manufacturer logos. Existing cyclist controls, rider skinning, and camera integration are retained.
