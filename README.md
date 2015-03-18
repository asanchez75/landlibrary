# LandLibrary

- Add the dependent modules (apachesolr_descr) to the sites/all/modules folder.
- Download the file http://jsonpath.googlecode.com/files/jsonpath-0.8.1.php and copy it in the sites/all/modules/feeds_jsonpath_parser folder.
- Follow the standard procedure to install LandLibrary as a feature. 
- Create a new LandLibrary menu. Name it 'Consult the Library' and use 'menu-landlibrary' as a machine name (important).
- Create the following Drupal basic pages with the respective URL aliases:
	- Browse: library
	- Data Sources: library/sources
	- Data Reuse: library/reuse
	- Contribute: library/contribute
- Create the following menu items:
	- Browse: library
	- Search: library/search
	- Data Sources: library/sources
	- Data Reuse: library/reuse
	- Contribute: library/contribute 
- Add the LandLibrary menu as a block to the template's section header and make it visible only for the following paths:
	- library
	- library/search
	- library/sources
	- library/reuse
	- library/contribute
- Append the CSS code from includes/css/library.css to your site's template CSS code. Tweak the code so that CSS classes match the actual Drupal nodes.
- Import taxonomies from the files in includes/taxonomies.
