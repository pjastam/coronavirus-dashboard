
<!-- README.md is generated from README.Rmd. Please edit that file -->

**The Coronavirus Dashboard: the case of the Netherlands**

[The Coronavirus Dashboard: the case of the
Netherlands](https://pietstam.nl/coronavirus_dashboard/) provides an
overview of the 2019 Novel Coronavirus COVID-19 (2019-nCoV) epidemic for
the Netherlands. It is built with R using the R Markdown framework and
is based on the
[dashboard](https://www.antoinesoetewey.com/files/coronavirus-dashboard.html)
by Antoine Soetewey, who uses data from Belgium. His dashboard is an
adaptation of the original
[dashboard](https://ramikrispin.github.io/coronavirus_dashboard/) by
Rami Krispin.

**New feature**

\[2020-04-27\] We changed the scales of two out of three figures to a
logarithmic one. In addition some formatting was done.

\[2020-04-06\] We compare the number of deaths instead of the number of
infected cases on the comparison tab of the dashboard. The reason is
that we assume that bias in the country comparison because of
measurement errors is smaller in this case.

\[2020-03-29\] We denoted the numbers in the left figure on the
Comparison tab of the dashboard in terms of 100.000 inhabitants living
in the respective countries. The total number of inhabitants are copied
from the [Wikipedia](https://en.wikipedia.org/wiki/Main_Page) [List of
countries and dependencies by
population](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population)
(visited at 2020-04-06).

**Code**

The code behind this dashboard is available on
[GitHub](https://github.com/pjastam/coronavirus_dashboard).

**Data**

The input data for this dashboard is from the
[`{coronavirus}`](https://github.com/RamiKrispin/coronavirus) R package.
The data and dashboard are refreshed on a daily basis. The raw data is
pulled from the Johns Hopkins University Center for Systems Science and
Engineering (JHU CCSE) Coronavirus
[repository](https://github.com/RamiKrispin/coronavirus-csv).

**Contact**

For any question or feedback, you can either open an
<a href="https://github.com/pjastam/coronavirus_dashboard/issues">issue</a>
or contact me on <a href="https://twitter.com/pjastam">Twitter</a>. More
information about this dashboard can be found in this
[article](https://www.statsandr.com/blog/how-to-create-a-simple-coronavirus-dashboard-specific-to-your-country-in-r/).

**Update**

The dashboard has been updated on Monday April 27, 2020.
