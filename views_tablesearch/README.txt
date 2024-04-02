INTRODUCTION
------------

  * Views table search can be used to create a views with javascript search enabled for records of the tables, it provides responsive search (javascript) and highlights the results where the search critiria is met, and hides the rows that don't contain the search keyword, it is heavily customizable: you may choose views table search settings for each View you create.
  
  * The javascript used is a plugin created for this project, and can be used independently inside a drupal porject or in any other application or website.


REQUIREMENTS
------------

  * Views table search requires Drupal & the core views module enabled.


INSTALLATION
------------
  * Install as you would normally install a contributed Drupal module. See the <a href='https://www.drupal.org/docs/extending-drupal/installing-modules'>Drupal Instructions On Installing Modules</a> if required in the Drupal documentation for further information. 


CONFIGURATION
-------------

  * Configuration is on a per view/display basis. Select 'Views table search' as the display format and then configure settings as desired under Format Settings.
	
  * The views table search template includes a "table" display for the result, however a template can be created for each view (or copied from the module templates folder to the theme) and table elements can be totally removed, however the js file (views_tablesearch.js) might need to be updated to still function under no table / tr / td elements. This feature might be added in future versions. As well as an option to display search found results (number of found results, number of found rows)