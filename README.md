# NER Dataset for Geology
### GEO_NER_DATA_casual.txt
A semi-manually annotated NER dataset containing geoscience-related non-academic texts from intro-level textbooks, blogs, wikipedia, and some other online resources.

### Labelled entities:

- **LOC**: geographic locations and specific tectonic plates, current and past (e.g., United States, eastern China, Michigan, Arctic Canada, Yangtze River, Pacific Ocean, Nazca Plate, Rocky Mountains, New York City, Gondwana...)
- **TIME**: geological intervals or specific events (e.g. Precambrian, Cretaceous, Eocene, K-Pg event, Last Glacial Maximum, PETM, OAEs, Acadian orogeny...)
- **LITH**: rock types (e.g. limestone, igneous rock, wackestone, metasedimentary rock, mafic rock, basalt, slate, marble...)
- **MINERAL**: minerals (e.g. quartz, feldspar, plagioclase, opal...)
- **PLANET**: planetary terms (e.g. plate tectonics, mantle, mantle convection, atmosphere, asthenosphere, Benioff zone...)
- **STRAT**: strata names (e.g. Hell Creek Formation, Morrison Formation, Dakota Sandstone, Mancos Shale, Fiftymile Member...)
- **FEAT**: major geological features (e.g. fold, fault, syncline, thrust, fjord, abyssal plain, foreland basin, xenolith, tidal flat, alluvial fan, moraine, lagoon...) 【Please note that this **FEAT** category is annotated subjectively and you may consider removing it for the NER studies if necessary】



_Note: The dataset may still need more rounds of proof-reading. It should be noted that annotation of some words is rather subjective. There may also be text errors caused by the encoding option when exporting. Feel free to PR if you find an labelling error._
