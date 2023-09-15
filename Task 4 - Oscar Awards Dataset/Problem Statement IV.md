# Power BI Task IV

### Dataset
We use a data set, ‘the_oscar_award’, that illustrates Oscar nominations by year.
(sent as a .xls file)

### Problem Description:
- Get and Transform Data
  - Load data from the dataset
  - Keep only the rows and columns that you need (Filter data by ‘year_of_film’ to keep data only for the year 2023. Then drop all columns other than ‘category’, ‘name’, and ‘film’)
- Prepare Data and Get Images
  - Create two measures.
      1. Nominations by film (containing count of category column)
      2. Selected category (this will be used to display which category users have selected from the slicer)
  -  Get any background images you may want/need or create a custom theme/template.
      1. I used images from the Academy Awards site and used PowerPoint to create my background. Then exported the slide as an image and imported it into Power BI as the page background.
      2. I also customized fonts to make it seem more realistic.
- Create Report Visuals
  -  Create a bar chart of nominations by film.
  -  Add a slicer (for the category column) and style it to match the report.
  -  Make a button whose action will be to open the slicer. Add either a text box or a shape to add text that informs users which categories they have selected. I used a shape because it has more formatting options.
  -  Use buttons and bookmarks to make the slicer appear and disappear. A back button can also be added to make the slicer disappear (Be sure to de-select Data in the bookmark options.)
  -  Check your tab order and add alt text to ensure your report is accessible.
