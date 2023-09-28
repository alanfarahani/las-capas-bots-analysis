<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->


<h3 align="center">Analysis of Paleoethnobotanical Data from the Archaeological Site of Las Capas (ca. 1500 BCE - 730 CE)</h3>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#data-description">Data Description</a>
      <ul>
        <li><a href="#files">Files</a></li>
        <li><a href="#markdown">Markdown</a></li>
      </ul>
    </li>
    <li><a href="#prerequisites-and-use">Prerequisites and Use</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository contains the markdown and files needed to reproduce Figures 5c, 5d, 7a, 7b, and 7d in [Sinensky, R. J. and Farahani, A. 2018. Diversity-disturbance relationships in the Late Archaic Southwest: implications for farmer-forager foodways. American Antiquity 83: 281-301.](https://www.researchgate.net/profile/R-J-Sinensky/publication/323364157_Diversity-Disturbance_Relationships_in_the_Late_Archaic_Southwest_Implications_for_Farmer-Forager_Foodways/links/62244cef84ce8e5b4d0a33b9/Diversity-Disturbance-Relationships-in-the-Late-Archaic-Southwest-Implications-for-Farmer-Forager-Foodways.pdf).

The best explanation of the project is in the article abstract (which this summary cribs), but in brief, this research sought to understand how communities at the Las Capas site in southern Arizona responded to environmental disturbances  the during the San Pedro phase (1220–730 BC) through changes in their food production. Through the analysis of more than 1,300 archaeological sediment samples from thousands of excavated cultural features, we learned that moderate-intensity flood
events during the Middle San Pedro phase (930–800 BC) preceded the greatest richness and diversity of harvested plants,
while during periods with little environmental disturbance, maize was more dominant,  We interpreted these findings against the backdrop of several different competing paradigms in ecology that attempt to model the effect of environmental disturbance on species richness (= number of different kinds of biological taxonomic entities).

See the compiled analyses and figures **<a href = "http://thebalkarchaeology.com/markdowns/las_capas_figures.html" target = "_new"> here</a>**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Data Description

### Files

- `sinensky_and_farahani_2018_paleoethnobotanical_data.csv`
: Counts of the archaeological plant remains from previous and some more recent analyses at Las Capas.  Includes the volume of analyzed sediment and some contextual information (intramural y/n, locus, feature number, etc.).

- `sinensky_and_farahani_2018_estimates_output.csv`
: As the filename states, this is the output of analyses conducted in the very helpful [EstimateS](https://www.robertkcolwell.org/pages/1407-estimates) software managed by [Robert Colwell](https://www.robertkcolwell.org), which is used for "statistical estimation of species richness".  This program was used to infer (crop) species richness for each archaeological "stratum". The calculation was based on taxonomic abundance by sample.  Here richness refers to [the ecological concept](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/species-richness), namely the number of unique instances of some kind of biological entity (species, genus, etc.) in a defined area.  We have since [reanalyzed these data](https://www.google.com/books/edition/Defining_and_Measuring_Diversity_in_Arch/ruBdEAAAQBAJ?hl=en&gbpv=1&dq=info:h--rcHIujEUJ:scholar.google.com&pg=PA178&printsec=frontcover)) for a book chapter on the measurement of mathematical diversity in archaeology, and a future repository (link TBA) will contain those data..

### Markdown

- `supplement.Rmd`
: An (R) markdown that allows for interactive reproducibility of all of the figures and tables found in the manuscript, plus some additional analyses.

- `supplement.html`
: A compiled version of the markdown in the event you just wanted to <a href = "http://thebalkarchaeology.com/markdowns/las_capas_figures.html" target = "_new"> look at the analyses and figures </a>.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Prerequisites and Use

You will need:

- [Rstudio](https://posit.co/products/open-source/rstudio/)

- [R > v. 4.2.0](https://www.r-project.org/)

The packages needed for markdown compilation are listed at the beginning of the (R) markdown.

<!-- CONTRIBUTING -->
## Contributing

You can contribute to this repository by identifying coding errors, proposing more elegant syntax, or suggesting additional analyses / visualization. Any contributions you make are **very welcome**.

If you have a suggestion, first please open an issue with the tag "enhancement".  Depending on how much work you've already done, I might recommend that you fork the repo and create a pull request.

If so:

1. Fork the project

2. Create a branch (`git checkout -b enhancement/amazinganalysis`)

3. Commit your changes (`git commit -m 'Added an incredible new analysis'`)

4. Push to the branch (`git push origin enhancement/amazinganalysis`)

5. Open a pull request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Alan Farahani - alanfarahani@gmail.com

Project Link: [https://github.com/alanfarahani/dhiban-bots-analysis](https://github.com/alanfarahani/dhiban-bots-analysis)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [README template](https://github.com/othneildrew/Best-README-Template/tree/master)
* From the abstract: Archaeological research at Las Capas was made possible by funding provided by Pima County, Arizona. The 2008-2009 project was administered by the Tres Rios Reclamation Facility, and the Pima County Office of Sustainability and Conservation, Cultural Resources and Historical Preservation Division. We would like to thank James Vint, Fred Nials, William Doelle, Veronica Perez-Rodriguez, Francis Smiley, Christian Downum, and Kelley Hays-Gilpin for their support. Additional thanks to Karen Adams, Wolf Gumerman, and Mike Diehl for help with specimen identification.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
