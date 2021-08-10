<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the DuckVision and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** viciopoli01, DuckVision, twitter_handle, email, project_title, The goal of our “Duck Vision” project was the integration of the OAK-D device from OpenCV’s AI Kit into the Duckietown platform. We think that the integration of OAK-D in the Duckietown infrastructure can boost autonomous car software development and research, as well as expose students who are working in the Duckietown framework to spatial AI and stereo vision.
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Duck Vision</h3>
  <a align="center" href="https://github.com/viciopoli01/DuckVision">
    <img src="media/lanef_demo.gif" alt="Logo">

  </a>

  <p align="center">
    <br />
    <a href="https://github.com/viciopoli01/DuckVision"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/viciopoli01/DuckVision">View Demo</a>
    ·
    <a href="https://github.com/viciopoli01/DuckVision/issues">Report Bug</a>
    ·
    <a href="https://github.com/viciopoli01/DuckVision/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


The goal of our “Duck Vision” project was the integration of the OAK-D device from OpenCV’s AI Kit into the Duckietown platform. We think that the integration of OAK-D in the Duckietown infrastructure can boost autonomous car software development and research, as well as expose students who are working in the Duckietown framework to spatial AI and stereo vision.



<!-- GETTING STARTED -->
## Getting Started

1. Navigate to `~/.dt-shell/commands-multi/daffy/` and checkout to `daffy-oakd`.
2. Switch on you Duckiebot and disable the official camera: `dts duckiebot camera --stop`.
3. Mount the OAK-D on the robot using the [camera mount](camera_mount/).


### Beginners

To integrate the basics of the OAK-D on a Duckiebot (tested with DB21M), you need to:

1. Clone the [**OAKD-Tutorials**](https://github.com/viciopoli01/oakd-tutorials) repository: 
    `git clone git@github.com:viciopoli01/oakd-tutorials.git`
2. Run and use the notebooks we developed, navigate to `oakd-tutorials/oakd` and run:
    `dts oakd notebooks`.
    At this point a Jupyter lab starts and you will be redirected on a web page. Login with the password `quackquack`. 
3. You can find the folders `01-basic-integration`, `02-oakd-calibration`, `02-oakd-calibration`, `03-semantic-segmentation`. Each of these folders contains a notebook, follow the instructions and have fun!


### Advanced

To integrate the basics of the OAK-D on a Duckiebot (tested with DB21M), you need to:

1. Use the [**OAKD-template**](https://github.com/viciopoli01/oakd-template) to create your DepthAI application.
2. Create a ROS package that uses the DepthAI Library and DTROS to have a fll integration in the Duckietown ecosystem.
3. To build and run your application on the Duckiebot use the `dts devel run/build` commands. Refer to the [Duckietown docs](https://docs.duckietown.org/daffy/opmanual_developer/out/index.html) for more information.

### Camera Mount

For easily mount the OAK-D on your Duckiebot we designed a camera support you can print.
The files are in the folder [camera_mount](camera_mount/).


### Prerequisites

We assume you are familiar with the Duckietown environment and you have already you computer setup to work with a Duckiebot as showed [here](https://docs.duckietown.org/daffy/opmanual_duckiebot/out/laptop_setup.html).

### Installation

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- CONTACT -->
## Contact

Vincenzo Polizzi - [@linkedin](https://www.linkedin.com/in/vincenzo-polizzi-602089146/) - polivicio@gmail.com

Trevor Phillips - [@linkedin](https://www.linkedin.com/in/trevphil/) - trevphil3@gmail.com

Project Link: [DuckVision](https://viciopoli01.github.io/DuckVision/)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Thanks to:
* [**Duckietown**](https://github.com/duckietown), for letting us using the lab.
* **Microsoft Azure** and **intel** for sponsoring the [OpenCV AI Competition 2021](https://opencv.org/opencv-ai-competition-2021/). 
* [othneildrew](https://github.com/othneildrew/Best-README-Template) for the README template.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/viciopoli01/DuckVision.svg?style=for-the-badge
[contributors-url]: https://github.com/viciopoli01/DuckVision/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/viciopoli01/DuckVision.svg?style=for-the-badge
[forks-url]: https://github.com/viciopoli01/DuckVision/network/members
[stars-shield]: https://img.shields.io/github/stars/viciopoli01/DuckVision.svg?style=for-the-badge
[stars-url]: https://github.com/viciopoli01/DuckVision/stargazers
[issues-shield]: https://img.shields.io/github/issues/viciopoli01/DuckVision.svg?style=for-the-badge
[issues-url]: https://github.com/viciopoli01/DuckVision/issues
[license-shield]: https://img.shields.io/github/license/viciopoli01/DuckVision.svg?style=for-the-badge
[license-url]: https://github.com/viciopoli01/DuckVision/blob/master/LICENSE.txt
