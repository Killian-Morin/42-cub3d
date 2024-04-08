
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="textures/eagle.png" alt="Logo" width="" height="80">

<h3 align="center">cub3d</h3>

  <p align="center">
    Summary:
This project is inspired by the world-famous Wolfenstein 3D game, which was the first FPS ever.
You must create a “realistic” 3D graphical representation of the inside of a maze from a first-person perspective. You have to create this representation using the Ray-Casting principles.
    <br/>
    <br/>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

- [About The Project](#about-the-project)
- [Usage](#usage)
- [Authors](#authors)
- [Sources](#sources)

<!-- ABOUT THE PROJECT -->
## About The Project
This is the second graphic design project of the 42 Cursus, it is done in teams of 2 ([@mdanchev](https://github.com/mariyagd) and I) and must be coded using C and the graphic library developed by 42: MiniLibX.

In addition to the mandatory part we did the wall collisions, a minimap system and the rotation of the point of view with the mouse.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Before launching the program you need to do a <strong>make</strong> or <strong>make bonus</strong> if you want to enable the minimap and the rotation with the mouse (the wall collisions are by default).

After the executable named <strong>cub3d</strong> is created you can execute it by adding a path to the file that will be used as the map.

We have a bunch of different maps in the <strong>maps</strong> folder including some that do not meet the requirements of the subject (in <strong>invalid</strong>).

Those file contain the path to the texture for each direction (NO for North, SO for South, WE for West and EA for East), the color of the floor and the ceiling.
After that, and it is necessary that it is after those informations, the map is declared. The '1' represent the walls while the '0' are for the open spaces.

You can customize as you like the colors for the floor and ceiling (modify their RGB values), change the textures with the other one available in the <strong>textures</strong> folder and change the aspect of the map as you like, but the map must always be closed by walls, there must be no gap around the map.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Authors -->
## Authors

* [@mdanchev](https://github.com/mariyagd)
* [@kmorin](https://github.com/Killian-Morin)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SOURCES -->
## Sources

* For the raycasting
  * https://lodev.org/cgtutor/raycasting.html
  * https://www.youtube.com/watch?v=gYRrGTC7GtA
  * https://www.youtube.com/watch?v=PC1RaETIx3Y
  * https://www.youtube.com/watch?v=w0Bm4IA-Ii8
  * https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/

* For the MiniLibX
  * https://harm-smits.github.io/42docs/libs/minilibx

* For the mac virtual keycodes
  * https://gist.github.com/eegrok/949034

<p align="right">(<a href="#readme-top">back to top</a>)</p>