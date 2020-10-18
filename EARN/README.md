<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


  <h3 align="center">Equation Attention Relationship Network (EARN): A Geometric Deep Metric Framework for Learning Similar Math Expression Embedding</h3>

  <p align="center">
  This is the official code repository for our ICPR 2020 accepted paper with the above title. 
    We have proposed a method for encoding math expressions and  their  similarity  in  latent  space.  Our  experiments  provide the  groundwork  for  leveraging  the  rapid  advancements  in geometric deep learning and deep metric learning. Improving the  underlying  graph  embedding,  message  passing  network, aggregation  techniques  or  updated  criterion  functions  can easily be implemented as a plug-and-play updates to improve the results that we have achieved.
<!--     <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p> -->
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Updates](#updates)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
Representational   Learning   in   the   form   of   high dimensional  embeddings  have  been  used  for  multiple  pattern recognition applications. There has been a significant interest in building  embedding  based  systems  for  learning  representations in  the  mathematical  domain.  

At  the  same  time,  retrieval  of structured  information  such  as  mathematical  expressions  is  an important   need   for   modern   IR   systems.   
In   this   work,   our motivation   is   to   introduce   a   robust   framework   for   learning representations  for  similarity  based  retrieval  of  mathematical expressions.  Given  a  query  by  example,  the  embedding  can find  the  closest  matching  expression  as  a  function  of  euclidean distance  between  them.  We  leverage  recent  advancements  in image-based and graph-based deep learning algorithms to learn our   similarity   embeddings.   

We   do   this   first,   by   using   uni-modal  encoders  in  graph  space  and  image  space  and  then,  a multi-modal  combination  of  the  same.
To  overcome  the  lack  of training  data,  we  force  the  networks  to  learn  a  deep  metric using  triplets  generated  with  a  heuristic  scoring  function.  We also  adopt  a  custom  strategy  for  mining  hard  samples  to  train our  neural  networks.  

Our  system  produces  rankings  similar  to those  generated  by  the  original  scoring  function,  but  using  only a fraction of the time. Our results establish the viability of using such  a  multi-modal  embedding  for  this  task. 

Index   Terms — Mathematical   Information   retrieval;   Semi-supervised  learning;  Graph  matching



### Built With

All dependancies go here


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites


### Installation


<!-- USAGE EXAMPLES -->
## Usage


<!-- ROADMAP -->
## Updates
#### Update 1 (Oct 18 2020) 
Added blank repository for camera ready version of accepted paper.


<!-- LICENSE -->
## License
This is a sofware in early stage development. It is distributed without any warranties (as is), under a GNU public license version 3.0. A copy of the license is included in the package. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

[Saleem Ahmed](https://www.linkedin.com/in/saleem4/) : saleem[Dot]ahmed[Dot][one one two thre five eight - in  digits without space]@gmail.com 


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
This research was  supported by the National Science Foundation under Grant No. 1640867 (OAC/DMR). We thank our colleagues Bhargava, Nishant, Deen and Nagashri who provided insight and expertise that greatly assisted the research, although they may not agree with all of the interpretations/conclusions of this paper.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=flat-square
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=flat-square
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=flat-square
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=flat-square
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=flat-square
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[product-screenshot]: images/screenshot.png
