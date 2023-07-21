<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
-->

<!-- ABOUT THE PROJECT -->
## About The GTSMip Project
Within GTSMip we produced global projections of extreme sea levels, including tides and storm surges. The projections cover the period from 1950-2050 and are derived with the Global Tide and Surge Model forced with a ~25km-resolution HighResMIP climate model ensemble. The resolution of climate models is important to accurately simulate the extra-tropical storms and tropical cyclones that drive storm surges and this is is the first time that such a high-resolution ensemble is used to assess changes in future storm surges across the globe. Validation against ERA5 reanalysis (1985-2014) shows that the model performs well globally, but also reveals a clear spatial bias. The median-ensemble change of the 1 in 10-year storm surge levels from 2021-2050 compared to 1951-1980 shows changes up to 0.1 m or 20%. These changes are not uniform across the globe with decreases along the coast of Mediterranean and northern Africa and southern Australia and increases along the south coast of Australia and Alaska. There are also increases along (parts) of the coasts of northern Caribbean, eastern Africa, China and the Korean peninsula, but with less agreement among the HighResMIP ensemble. Information resulting from this study can be used to inform broad-scale assessment of coastal impacts under future climate change.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started
This pages provides the scripts that we used to produce the figures for Muis et al. (2023). We provide brief instructions on how you could access the data and run this scripts. 
To get a local copy up and running follow these simple example steps.

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Access to GTSMip dataset
The datset, including full documentation, can be found on the C3S Climate Data Store: [https://doi.org/10.24381/cds.6edf04e0]. It provides provides statistical indicators of tides, storm surges and sea level that can be used to characterize global sea level in present-day conditions and also to assess changes under climate change. The indicators calculated include extreme-value indicators (e.g. return periods including confidence bounds for total water levels and surge levels), probability indicators (e.g. percentile for total water levels and surge levels). You can use the API to download with Python.

<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Sanne Muis - [@MuisSanne](https://twitter.com/MuisSanne) - sanne.muis@vu.nl

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

More about GTSM: [https://www.deltares.nl/en/expertise/projects/global-modelling-of-tides-and-storm-surges]

<p align="right">(<a href="#readme-top">back to top</a>)</p>
