# Web-Design-Challenge
Your website must consist of seven pages as follows:

A landing page that contains the following elements:

An explanation of the project.

A link to each visualisation page. For these, a sidebar should contain a preview image of each visualisation. Clicking an image should take the user to that visualisation.

Four visualisation pages, stored in the visualisations folder, each with the following elements:

A descriptive title and a heading tag.

The visualisation for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the assets/images folder.

A paragraph describing the visualisation and its significance.

A comparisons page that does the following:

Contains all the visualisations on the same page so that people can easily compare them.

Uses a Bootstrap grid for the visualisations. This grid must contain two visualisations across a medium or large screen and one visualisation across an extra-small or small screen.

A data page that displays a responsive table containing the data that the visualisations use, as follows:

The table must be a Bootstrap table component.

HINT
The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a to_html method that generates an HTML table from a Pandas DataFrame. To learn more, see pandas.DataFrame.to_htmlLinks to an external site. in the official Pandas documentation.

At the top of every page, your website must have a navigation bar that does the following:

Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.

Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualisation page.

Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.

Is responsive (via media queries). Note that the navigation bar must resemble the one in the screenshots in the Navigation Bar section. In particular, notice the background colour change.

Your website must be deployed to GitHub Pages:

As a result, the website must work at a live, publicly accessible URL. Save this URL for your later submission.
Bonus
For extra challenges, try any or all of the following:

Use the same requirements but a different dataset to make it your own.

Use the same requirements, but add a Bootstrap theme to customise your website. To do so, you can use a tool like BootswatchLinks to an external site..

Add extra visualisations.

Use meaningful glyphicons next to the links in the navigation bar.

On every visualisation page that has an active state, add visualisation navigation, as shown in the following images in the Screenshots section.