# ACCESS Publication Analysis (2022-2025)

This report examines the publication output of the 
[ACCESS program](https://access-ci.org) from 2022 to 
present (Feb 2025).  The 
publications were extracted from self-reported 
data provided by active ACCESS users.  The data
represents publications that are _linked_ to an
ACCESS resource, and in many cases _directly used_
ACCESS resources.  It should be noted that 
spurious results may exist, for example, in the
case where a researcher listed _all_ publications
in their CV over the requested period, regardless
of whether they used ACCESS resources directly or not. 

## Methodology

The original data was extracted from the database
of self-reported publications.  This data
was cleaned and DOIs were extracted directly 
from the self-reported data.  DOIs were 
normalized and metadata was extracted
from [Crossref](https://crossref.org) and [OpenAlex](https://openalex.org).  

Crossref metadata contains a number of fields of interest,
but the most significant are the _journal name_
and _times cited_.  The _times cited_ data is
used throughout this report and **whenever
citation counts are provide, it is the Crossref
_times cited_ data**.  To learn more about 
how Crossref calculates this data, please
see [this](https://www.crossref.org/documentation/cited-by/retrieve-citations/#00275). Generally, Crossref 
citation counts are lower, updated less frequently and more conservative than many other services, but they also tend to be very reliable, even though the direct link back to the citing resource is not provided.

OpenAlex metadata is used to extract topical information 
about the publications and while it contains citation
counts along with backlinks to citing resources, 
for consistency of reporting, we use Crossref in this
report.  For future reports, it we may use both.

[Altmetric](https://altmetric.com) data is used only for the publications with between 8 and 15
citation counts.  The decision for this was two-fold: (1) there 
are _many_ publications with fewer than 8 citations, and while
they are interesting to explore, the volume of publications did
not align with the goal of highlighting the balance between citations and
altmetric attention, (2) publications with more than 
15 citations, are already well on their way to gaining attention and interest
_within_ their respective communities, thus a high citation count
_and_ high altmetric score overshadows those less
cited but notable where altmetrics are concerned.
 
## Key Questions Addressed

This report is **not** exhaustive in scope, but it 
is intended to highlight and explore the important
scholarly work that the ACCESS infrastructure 
supports.  The report does try to explore a few of the 
questions below:

1. How many publications have been associated with the ACCESS project since its 2022 inception?
2. Which publications have yielded the highest citations?
4. What fields of study do these publications fall into?
5. Which are noteworthy Altmetric publications?
6. What are the trends and other insights about the publications produced during this timeframe?

