BSC.json is the Yale bright star catalogue with HIP number and common names added with the included program MergeHIPandNames
The table below describes what each of these keys mean, and lists the files
that use them. From https://github.com/frostoven/BSC5P-JSON-XYZ/tree/primary/catalogs

| Key | Type     | Symbol | Used by | Description                  |
| --- | -------- | ------ | ------- | ---------------------------- |
| `i` | number, string | -- | `bsc5p_radec` `bsc5p_3d` `bsc5p_names` `bsc5p_spectral_extra` | Original BSC5P line ID, or 'Custom [n]' if added via the amendments mechanism. Used to link stars between files.
| `n` | string   | --     | `bsc5p_radec` `bsc5p_3d` | A single name given to star. Additional known names for each star stored in [bsc5p_names.json](catalogs/bsc5p_names.json).
| `p` | number   | `pc`   | `bsc5p_radec` `bsc5p_3d` | Distance in parsecs, ignoring uncertainty. 1 parsec ≈ 3.26 light-years.
| `r` | number   | `α`    | `bsc5p_radec` | Right ascension in **radians**.
| `d` | number   | `δ`    | `bsc5p_radec` | Declination in **radians**.
| `N` | number   | `L☉`   | `bsc5p_radec` `bsc5p_3d` | Naively calculated luminosity. 
| `K` | vector3  | `K`    | `bsc5p_radec` `bsc5p_3d` | Colour of star approximated from star temperature in kelvin (AKA blackbody temperature), converted to RGB. A lot of effort and research has gone into estimating this as physically accurately as humanly possible (while keeping in mind it's still an approximation nonetheless, and will vary by star class and observational quality).
| `hip` | string   | `hip`    | `bsc5p_radec` |HIP number.
| `name` | array   | `hip`    | `bsc5p_radec` |Common name(s).


FREE High Resolution Textures (2048 x 1024)

Made By:	Solar System Scope
URL:		http://www.solarsystemscope.com/textures

Pack by:	Stevelois
URL:		https://stevelois.wordpress.com

Distributed under Attribution 4.0 International license: You may use, adapt and share these textures for any purpose, even commercially.

Enjoy and please let us know when you create amazing project with these, we’re eager to hear all about it. Textures in this pack are based on NASA elevation and imagery data. Colors and shades of the textures are tuned accordng to true-color photos made by Messenger, Viking and Cassini spacecrafts, and, of course, the Hubble Space Telescope.

This pack contain the following textures:

Earth Day Map
Earth Night Map
Earth Clouds
Earth Normal Map
Earth Specular Map
Jupiter
Mars
Mercury
Moon
Neptune
Saturn
Saturn Ring
Stars
Stars + Milky Way
Sun
Uranus
Venus Surface
Venus Atmosphere
Ceres - fictional
Eris - fictional
Haumea - fictional
Makemake - fictional

Notes:

Some parts of the planets remain to be mapped. These “gaps” are filled with fictional terrain that corresponds with the rest of the landscape.

The colors are slightly more saturated in order to highlite a unique nature for each object.

Earth textures are the most precise part of the pack: They are a result of merging and adjusting large amount of geo-data, space photos and images from NASA’s Blue Marble (which might well be the 2nd best collection of Earth’s textures available, so check it out).

True Earth colors (as seen from space) may vary depending on the camera used, duration of exposure, lightning conditions and atmospheric conditions. Textures in our pack are sharp, bright and colorful.

Seasonal variations affect Earth’s flora and snow coverage. Earth in our textures has a lot of vegetation and less snow.
