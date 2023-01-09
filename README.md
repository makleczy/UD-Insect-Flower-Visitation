# University of Delaware Insect-Flower Visitation Dataset

### Melinda Kleczynski

### Overview

I recorded this data for the purpose of obtaining a small bipartite network for illustrating relevant mathematical techniques. The dataset is not a comprehensive survey of all insect-flower interactions at the trial garden. A documented interaction required evidence of flower visitation but not successful pollination, so the network constructed from the data described here is a visitation network rather than a plant-pollinator network. No interactions were sought out or excluded with the goal of obtaining any particular network or topological properties. 

Photographs documenting every interaction in the dataset are [posted on iNaturalist](https://www.inaturalist.org/observations?d1=2022-09-05&d2=2022-09-15&place_id=any&user_id=melinda_k&verifiable=any). Three text files, one for each day of data collection, contain a full list of observed interactions.

### Methods

The data consists of insect-flower interactions at the  [University of Delaware Botanic Gardens](https://canr.udel.edu/udbg/)
Landscape Color Trial Garden during September 2022. I collected data on September 5, 10, and 15, following the same procedure on all three days. Insect-flower visitation networks change over time, but we will assume that the data collection dates were close enough that they represent multiple observations of the same network.

I monitored each plant genus for 15 minutes on each day, documenting insect-flower interactions using photographs. I did not include insects which were on a part of the plant other than the flower. I did not collect specimens. Signs in the garden identify the plants, and I identified the insects to at least the level of genus based on photographs.

It was always the intention to group individuals at the level of genus. If, for example, I observed one bumble bee species at a given plant on a given day, then I made no effort to document additional bumble bee species since the data already established the presence of the genus *Bombus*.

The dataset includes plants which were part of the trial garden, regardless of which plants were common in the surrounding area.  I did not include unmarked plants, such as clover growing in the grassy areas surrounding the flower beds, even if these plants may have attracted pollinators to the garden area. I selected eight plant genera which were actively flowering and had visible insect visitors to be part of the dataset. For each genus I designated a particular area of the garden to monitor, typically consisting of a continuous block of plants. See the photograph below for the survey area for genus *Helianthus*.

<img src = "https://github.com/makleczy/UD-Insect-Flower-Visitation/blob/main/Helianthus_readme_figure.JPG" width = "500">

### Discussion

Some plant survey areas were larger than others. Additionally, it was easier to photograph insects on certain plants, such as those which were located at the end of a flower bed. A given plant genus could correspond to one or multiple species in the dataset. For example, the only representative observed from genus *Gomphrena* was *Gomphrena pulchella*, but genus *Tagetes* included both *Tagetes erecta* and *Tagetes patula*. All these considerations may have affected the presence or observation of potential insect visitors.

For an insect-flower interaction to be included in the network, the following had to occur:
1. The insect visited a flower during the observation window for the given plant genus
2. I noticed the insect and recognized that it was likely to be a member of a genus not yet recorded for that plant and that day
3. I was able to obtain a photograph of the insect visiting a flower
4. The quality and content of the photograph allowed identification to the level of genus or better

Each requirement has the potential to discourage the inclusion of different insects in the network. Insects which are most active later in the day or at night were less likely to be observed. I may not have noticed insects that were small or well camouflaged. Insect genera that look similar to each other could be underrepresented. I may not have been able to obtain sufficient evidence of insects that moved quickly or are difficult to identify from photos. 

The abundance of different insect taxa varied considerably. For example, many Western honey bees (*Apis mellifera*) visited the trial garden, but I observed only one individual of the genus *Hemaris* over the course of all the data collection. A small population size makes it more difficult to reliably observe an insect taxon with all of its plant partners. Insects with large populations are more likely to be reliably documented in the dataset. 

The final dataset contains 20 insect genera. I observed 64 insect-flower interactions over the course of the three days of data collection, which yielded 39 unique interactions (see the network below). The high proportion of unique interactions may indicate that the system was under-sampled, and that additional days of data collection may have revealed additional unique interactions.

<img src = "https://github.com/makleczy/UD-Insect-Flower-Visitation/blob/main/bipart_readme_figure.png" width = 800>


