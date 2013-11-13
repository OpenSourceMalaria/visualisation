Visualisation project
=============

This project is concerned with the general purpose visualisation of OSM compounds. This has been raised [here](https://github.com/OpenSourceMalaria/OSM_To_Do_List/issues/99)

The first step before implementing this system is to outline a minimum set of requirements that the system should meet, this document is initally designed to do so.

##Requirements##

The requirements outlined below are based on the comments raised in [#99](https://github.com/OpenSourceMalaria/OSM_To_Do_List/issues/99) and [#112](https://github.com/OpenSourceMalaria/OSM_To_Do_List/issues/112)

- [ ] Visualisation (2D or 3D) of each structure
- [ ] Informatics data (InChI at a bare minimum)
- [ ] Potencies/other relevant biological data
- [ ] Associated identication numbers (including OSM number)
- [ ] Simple links to relevant documentation (blog posts, summaries)
- [ ] Molecules must contain a status label (Synthesised, Under investigation etc.)
- [ ] The ability to filter molecules based on properties (Series, status, alternate informatics data)
- [ ] The ability to search molecules (by name, identifier)
- [ ] Sorting(?) sort by name, identifier, potency (if available)
- [ ] Integration with ChEMBL API(?) ability to retrieve more information, or at the very least links out
- [ ] Indexable by search engines

Substructure searches and in depth analysis are probably out of scope at this stage for a minimum working project. These features should certainly be considered at a later date.

##Infrastructure##

Information about the infrastructure required to run the visualisation.

Given that the visualisation should not require the user to install any additional software (other than what is typically available in the browser) we should aim for a serverside web application. The serverside application should be easy to fork from this repo, and setup independently of the OSM project.

##Contributing##

If the contribution you would like to make is of a technical nature, feel free to fork this repo, make the changes in your branch and then submit a pull request.

If the contribution is non-technical, such as a suggestion or feature request submit an [issue](https://github.com/OpenSourceMalaria/visualisation/issues) and tag it with the appropriate label.

