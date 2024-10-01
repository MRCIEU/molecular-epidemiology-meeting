# molecular-epidemiology-meeting

The IEU Molecular Epidemiology Meeting is held every 2 weeks. Full meeting details, presenter history, and upcoming presenter rota held on the official course website: https://uob.sharepoint.com/teams/grp-IEUMolecularEpidemiology2

Meeting organization is shared by the below list of leads each representing a given special topic:

```
library(tidyverse)

# define the table of leads and associated special topics
molepi <-
	tribble(~name, ~topic,
		"Hannah Elliott", "Epigenetic Epidemiology",
		"Paul Yousefi", "Multi-omic disease prediction",
        "Matthew Suderman", "Multi-omic disease prediction",
		"Gibran Hemani", "Causal inference",
		"George Davey Smith", "Causal inference",
		"Carolina Borges", "Metabolomics",
		"Kaitlin Wade", "Microbiomic",
        "Josine Min", "Molecular assay technologies"
	)
```

The order in which special topics will covered in future meetings and responsibility for meeting organization is defined by the below random sample of special topic leads:

```
# sample reproducibly
set.seed(357424)
molepi[sample(nrow(molepi)),]
```

|order|name|topic|
|:-|:-|:-|
|1|George Davey Smith | Causal inference             |
|2|Carolina Borges    | Metabolomics                 |
|3|Gibran Hemani      | Causal inference             |
|4|Paul Yousefi       | Multi-omic disease prediction|
|5|Josine Min         | Molecular assay technologies |
|6|Matthew Suderman   | Multi-omic disease prediction|
|7|Kaitlin Wade       | Microbiomic                  |
|8|Hannah Elliott     | Epigenetic Epidemiology      |

* Order last generated **2024-10-01** to restart the rota for meeting on **2024-11-05**