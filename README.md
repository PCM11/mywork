# My Work

<a target="_blank" href="https://colab.research.google.com/github/PCM11/mywork/blob/main/penguins.ipynb">

  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In 
Colab"/>
</a>

![Image](https://miro.medium.com/v2/resize:fit:786/format:webp/0*V1ED9g49d51KpYv9.png)

This dataset is available for more exploration [on Github](https://allisonhorst.github.io/palmerpenguins/).

## About the data

The [Palmer penguins Dataset](https://allisonhorst.github.io/palmerpenguins/) by Allison Horst, Alison Hill and Dr Kristen Gorman contains data for 344 adult penguins of 3 different species (Adelie, 
Gentoo and Chinstrap), from 3 differrent islands (Biscoe, Torgeesen and Dream) in the Palmer Archipelago, Antarctica.

It contains two datasets, one called *penguins* and the other called *penguins_raw*.

*Penguin* is a simplified version of the raw data,and more information can be found [here](https://allisonhorst.github.io/palmerpenguins/reference/penguins.html).

*Penguin Raw* includes nesting observations, penguin size data, and isotope measurements from blood samples for adult Adélie, Chinstrap and Gentoo penguins.
More details can be found [here](https://allisonhorst.github.io/palmerpenguins/reference/penguins_raw.html)

## Installation

I used [openincolab.com](https://openincolab.com/) to generate the following clickable link.
It opens the `penguins.ipynb` notebook in [Google Colab](https://colab.research.google.com/).

To further explore this dataset you need to download python, which can be installed through [anaconda](https://www.anaconda.com/download), and notebook editor, which can be found in [Visual Studio Code](https://code.visualstudio.com/)

## Analysis

 I imported Python libraries to anlyse the data.

- Pandas - for data manipulation and analysis. It allows us to investigate CSV files, amongst other features.

- Matplotlib - for data visualisation and graphical plotting

- Seaborn - built on top of matplotlib with similar functionalities

- Numpy - to perform  wide variety of mathematical operations on arrays

- Warnings - to manipulate warnings details.

The dataset consists of 7 columns.

**species**, a factor denoting penguin species (Adélie, Chinstrap and Gentoo).

**island**, a factor denoting islands in Palmer Archipelago, Antarctica (Biscoe, Dream or 
Torgersen).

**bill_length_mm**, a number denoting bill length (millimeters).

**bill_depth_mm**, a number denoting bill depth (millimeters).

**flipper_length_mm**, an integer denoting flipper length (millimeters).

**body_mass_g**, an integer denoting body mass (grams).

**sex**, a factor denoting penguin sex (female, male).

## Usage

It provides a rich dataset for exploration and visualisation of data, offering an alternative to a highly over used Iris dataset.

## License

This data is available in accordance with the [Palmer Station LTER Data Policy](https://pallter.marine.rutgers.edu/data/) and the [LTER Data Access Policy for Type I data](https://lternet.edu/data-access-policy/), by [CCO](https://creativecommons.org/public-domain/cc0/).

## Additional Information

The following publications and citations offer a well detailed information about penguins.

- Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins [(Genus Pygoscelis)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0090081).

 Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Adélie, Gentoo and Chinstrap penguins.

- [Pygoscelis adeliae](https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-pal.219.5)

- [Pygoscelis papua](https://portal.edirepository.org/nis/mapbrowse?scope=knb-lter-pal&identifier=220&revision=7).

- [Pygoscelis antarcticus](https://portal.edirepository.org/nis/mapbrowse?scope=knb-lter-pal&identifier=221&revision=8).

## Author

Phumi Tshidi
