# University of California Admissions by Source School

This data package presents data scraped from a Tableau vizualization on the
Univerity of California's data system, for the admissions to UC Campuses by the
source high school. The dataset provides the number of students that applied from each high school to each UC Campus, as well as the number admitted and enrolled. 


The UC data was collected by manually "scraping" the Tableau vizualiztion; each
combination of UC campus and year was selected and downloaded to a file, and
these files were combined into a single dataset. Then, the UC records were
matched to California Department of Education records using a fuzzy match on
the names. Only about 83% of the records could be relabily matched, with a
score of .8 or greater. See the ``matches`` file for all of the matches and
their scores.


