# NER Dataset for Geology
### GEO_NER_DATA_2020.txt
A semi-manually annotated NER (named entity recognition) dataset for the domain of geology. It contains **abstracts** of all _articles_ published in and before 2020 on the following journals:
- _Nature Geoscience_
- _Geology_
- _Earth and Planetary Science Letters_

Data source: Scopus

### GEO_NER_DATA_casual.txt
Another dataset containing annotated geoscience-related texts from blogs, wikipedia, k-12 science books, and intro-level textbooks.

### Labelled entities:

- **LOC**: geographic locations, current and past (e.g., United States, eastern China, Michigan, Arctic Canada, Yangtze River, Pacific Ocean, Nazca Plate, Rocky Mountains, New York City, Gondwana...)
- **TIME**: geological intervals or specific events (e.g. Precambrian, Cretaceous, Eocene, K-Pg event, Last Glacial Maximum, PETM, OAEs...)
- **LITH**: rock types (e.g. limestone, igneous rock,wackestone, metasedimentary rock, mafic rock, basalt, slate, marble...)
- **MINERAL**: minerals (e.g. quartz, feldspar, plagioclase, opal...)
- **PROC**: geological processes (e.g. transgression, uplifting, earthquake, weathering, calving, orogeny...) [Not available in the casual dataset]
- **PLANET**: planetary terms (e.g. plate tectonics, mantle, mantle convection, atmosphere, asthenosphere, Benioff zone...)
- **FEAT**: geological features (e.g. fold, fault, syncline, thrust, fjord, abyssal plain, foreland basin, xenolith, tidal flat, alluvial fan, moraine, lagoon...)
- **STRAT**: strata names (e.g. Hell Creek Formation, Morrison Formation, Dakota Sandstone, Mancos Shale, Fiftymile Member...)


_Note: The datasets (especially the Abstract dataset) may still need more rounds of check. It should be noted that annotation of some words is rather subjective. There may also be text errors caused by the encoding option when exporting. Feel free to PR if you find an labelling error._
