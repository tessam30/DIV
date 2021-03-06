### PEPFAR BETWEEN THE SHEETS
#### Section 1: How to look at MER data in Excel

1.  [Your mission, should you choose to accept **(Imran)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#1-your-mission-should-you-choose-to-accept-it-imran)
    - aka background story, but fun!
    - sample 'real-life' question to solve
    - quick note on excel version
1.  [What is a pivot table? **(Aaron)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#2-what-is-a-pivot-table-aaron)
    - Appearance - could look similar, but purpose is different
    - Raw data compared to summary
    - Purpose/Benefits
      - summarize Data
      - unique values
      - dyanmic tables
      - filtering
      - updates with new datasets
1.  [Why and when to use a pivot table? **(Catherine)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#3-why-and-when-to-use-a-pivot-table-catherine)
    - difference between standard platforms
1.  [Data structure (tidy data) **(Aaron)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#4-data-structure-tidy-data-aaron)
    - standard/consistent way to organize data in datasets
    - facilitate data exploration
    - principles (Wickham)
      - Each variable must have its own column.
      - Each observation must have its own row.
      - Each value must have its own cell.
1. [Accessing and downloading data **(Shazad)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#5-accessing-and-downloading-data-shazad)
    - MSD (will use training dataset)- see release notes in Pano
    - Accessing through Panorama
    - Accessing throough DATIM Genie extracts
    - Unzipping downloaded dataset and renaming, if needed (for scripts)
    - Import text file steps
1. [How to create a pivot table  **(Shazad)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#6-how-to-create-a-pivot-table-shazad)
    - 'Insert pivot table' button
    - Ensure correct range is picked up
    - Mention conversion to excel table will be discussed in different vid
1. [Different parts of a pivot table  **(Katya)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#7-different-parts-of-a-pivot-table-katya)
1. [Structural options **(Katya)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#8-structural-options-katya)
    - different views - tabular, outline
1. [Filtering **(Shaylee)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#9-filtering-shaylee)
    - adding fields to "FILTER" box
1. [Building pivot charts **(Shazad)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#10-building-pivot-charts-shazad)
    - Benefits of pivot chart
    - Pivot chart button
    - Hiding all fields
1. [Including Slicers **(Shaylee)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#11-adding-slicers-shaylee)
    - SLICER button
    - reporting connections
1. [What are calculated indicators and how to create them **(Imran)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#12-what-are-calculated-indicators-and-how-to-create-them-imran)
    - percent achievement
    - yield

1. [Considerations when building an Excel tool **(Shazad)**](https://github.com/ICPI/DIV/blob/master/Training/PVA_PEPFARBetweentheSheets/PT_material_PEPFAR_Academy.md#13-considerations-when-building-an-excel-tool-shazad)
    - converting raw data to 'excel table' first
    - naming the pivot tables
    - tab structure of Excel tool
    - 'refresh' the data
1. Link to resources (ICPI Onboarding Training) **( )**


###  1. Your mission should you choose to accept it **(Imran)**

INTERIOR. LOCKED DOWN COMPUTER ROOM

A regular looking analyst is working on a computer in a secure computer room. 
ANALYST:
>Argh... I hate Excel pivot

The analyst rushes out anguished.There is no one left in the room. There is no sound except the sound of the gentle hum of the computer.  A person dressed in black stealthily descends down from the ceiling suspended by a rope onto the desk with the computer. The person in black starts working on the computer, while suspended horizontally. 

CLOSE ON COMPUTER SCREEN
>Your mission, should you choose to accept it, is to successfully create a pivot table in Excel using the MER Structured Datasets. As always, should you or any member of your team get the numbers wrong, the Ambassador will disavow any knowledge of your actions

CLOSE ON EXCEL VERSION


###  2. What is a pivot table? **(Aaron)**

Pivoting is the process of shifting something around with the aim of repositioning it for another use or for access.

Pivot tables are a built in feature or Excel that allow the user to start exploring larger datasets/tables. Setting up or working with a pivot table may seem like a daunting task for those unfamiliar but they are actually quite intuitive and user friendly.

What’s required is having Excel and data in it. To make your data more useable, you’ll want to have a long and tidy dataset which will better facilitate the process of exploring your data. We’ll get into this in later modules.

A pivot table is important because it takes large amounts of data and summarizes it for us, breaking into groups to better answer our questions.

For instance, we may have a partners dataset on testing over a 3 month period in a the districts it works in. Reviewing the raw data or trying to count it manually is highly inefficient and only become more inefficient the larger the data is.

We can use a pivot table to summarize this dataset. By using a pivot table, we can quickly see that there were X number of tests in the quarter. We can break this down and see that X were Males. We can even quickly see the positivity across the quarter is X% and X% for males and females respectively.

An additional benefit of pivot tables is their structure. If we get new data for the second quarter, we can pop that in and update or refresh the pivot tables. This allows us to setup our exploratory analysis once instead of repeating the same process each quarter.

In sum, pivot tables allow us to take raw data, aggregate it up, and summarize it across different groupings or filters.

### 3. Why and when to use a pivot table? **(Catherine)**
Now that we’ve reviewed the basics of what pivot tables are, we can consider when we should use them.

You might have used PEPFAR data platforms for viewing MER data such as Panorama or DATIM.  These platforms are very good for viewing MER data in standardized tables and visualizations.  But, for enhanced flexibility and control over the data, one can use the MER structured datasets, which are text files of MER data that can be read into excel or a statistical software package.

If you want the ability to conduct customized analyses with your MER data, then the MER structured datasets will help you in your work.
A key skill to using the MER structured datasets in excel is creating pivot tables.

Before jumping into pivot tables using the MER structured datasets, we will briefly review some important principles of data structure.



### 4. Data structure (tidy data) **(Aaron)**

Structure is important across any data used, but particularly important when using pivot tables. It create consistency, which makes it easy to use, understand, and explore the variables and their relationships.

As data consumers, we are mostly presented with summary tables in reports or graphics. It’s a bit difficult to get use to changing hats to be a data user and having to think about and use “raw.” To assist in our data exploration and usage, we need to structure the data in a (a) long and (b) tidy format.

Let start with long. We can think about this as a vertically oriented. This structure may seem foreign and more difficult for you, the human to read, but it facilitates manipulating via the computer. [show example of long v wide].

A more difficult piece for a newcomer to get their head around is tidy data. data tables can be structured a number of different ways and still contain the same underlying data. That said, we want to make the data easy to manipulate and use.

> A dataset is a collection of values, usually either numbers (if quantitative) or strings (if qualitative). Values are organised in two ways. Every value belongs to a variable and an observation. A variable contains all values that measure the same underlying attribute (like height, temperature, duration) across units. An observation contains all values measured on the same unit (like a person, or a day, or a race) across attributes....
> A general rule of thumb is that it is easier to describe functional relationships between variables (e.g., z is a linear combination of x and y, density is the ratio of weight to volume) than between rows, and it is easier to make comparisons between groups of observations (e.g., average of group a vs. average of group b) than between groups of columns.... -H.Wickham

I tidy data set then is defined as the following:

1. Each variable forms a column.
1. Each observation forms a row.
1. Each type of observational unit forms a table.

Tidy data makes it easy to scan the dataset as a human and analyze for the computer as “... the layout ensures that values of different variables from the same observation are always paired.”

Common problems we see with messy datasets:
- Column headers are values, not variable names.
- Multiple variables are stored in one column.
- Variables are stored in both rows and columns.
- Multiple types of observational units are stored in the same table.
- A single observational unit is stored in multiple tables.

[examples]

Structuring the data you’re using to be long and tidy, will make it much easier to use pivot tables.

[examples of messy v tidy data with a pivot table]

[Reference: Hadley Wickham’s Tidy Data](https://vita.had.co.nz/papers/tidy-data.pdf)


### 5. Accessing and downloading data **(Shazad)**  

Now that you have a sense of the type and quality of data you should be working with before creating pivot tables, let’s walk through the process of attaining your data and importing that data into excel. These steps will be general for any data you may work with in excel, outside of PEPFAR purposes. 

When deciding on which dataset to download, keep in mind there are at this time, several datasets to choose from including SIMS, ER and multiple versions of MSD datasets. As of this recording, there are also multiple locations to download datasets from, including Panorama and Genie app in DATIM.  

For this course, we will use a training MSD, where we have replaced actual PEPFAR names and data with artificial names and data. However, the structure of this training dataset mimics that of the actual MSD, published twice every quarter. And for the purpose of this course, you should access the training dataset through the Handouts section of the PEPFAR Virtual Academy. However, in the video we will simulate downloading a real non training dataset.  

The first location we will cover for downloading data is Panorama. Once logged into Panorama, clicking on the green download icon at the top right will take you to screen with several file options. Choose the dataset of your choice depending on your analytic needs. 

Another location is through the DATIM Genie app, which allows the option for downloading datasets that are frozen in time or datasets that show live data. Once logged into the Genie app, you can select which type of data you wish to view and download. An advantage of accessing the data through the Genie app is that you can use the filters to trim your dataset before downloading, which you can’t do through the Panorama route. 

Whether you download your dataset through Pano or Genie, you will receive a file that is zipped. You will need to unzip the file before being able to import into excel.

Once the dataset is unzipped, open up excel, and begin to import the dataset. Go to the Data tab, then to the “From Text” button at the top ticker. Select the file that is the MSD that was downloaded. Click on “next” twice to bring you to step 3 of the Import Wizard. Scroll to the right until you see the “modality” column in the menu. Press and hold the shift key on your keyboard, and click on the modality column with the mouse. This should highlight all columns leading up the modality column in black. At the top left box named Column data format, click on the option that says ‘text’ to convert the data into text. Click finish. Make sure the dataset starts in cell A1.   

:question: Do we know when the shift will happen to access the MSDs through Genie rather than Panorama? 
** Also - please include in your script/video that forthe purpose of this course, learners should access the training dataset through the Handouts section of the PEPFAR Virtual Academy. 

### 6. How to Create A Pivot Table **(Shazad)**
Once the dataset has been successfully imported into excel, you can finally create pivot table.

To do so, click on a cell in your dataset. You could also press “crtl + A” on the keyboard to select all cells of the dataset. 

Then, assuming your dataset is continuous and does not have any gaps in rows, go to the ‘Insert’ tab and then click on the ‘PivotTable’ button at the top left. 

Excel should automatically pick up the full range of the entire dataset in the Create PivotTable menu. 

You also have the options of specifying a cell range for the dataset and choosing where you want the pivot table to be placed. If you are building a tool, you may want to specify where to place the table, otherwise, Excel will create a new sheet for it. 

Once all options are agreed upon, click ‘OK’ and an empty pivot table shell will appear where specified. 

### 7. Different parts of a Pivot Table **(Katya)**
Once you've created your pivot table, you'll see two new items appear in the top menu "Analyze" and "Design". These are additional  options and settings that become available with pivot tables. You will also see a menu called "PivotTable Fields" appear. THis coincide with the column names in the raw dataset. 

Within the PivotTable Fields menu, there are sections that are important to understand how they function. 
- Filters: By dragging fields from the menu to filters, you can select for specific items of interest to be only displayed in the pivot table. For example, if you only want to see data for a particular country or indicator you can drag that Field to Filters.
- Columns:  You may wish to use columns to break down your data into multiple categories. For example, if you have two years of data under a Fiscal Year field, you may want to display data from both years side by side. 
- Rows: These are helpful also for breaking down data into categories or disaggregates. For example, if you are looking at data from more than country, you may want to drag the country field to rows or if you are looking at data within one country and want to see what the distribution of data is across regions or at a more granular geographic level, you could drag a geographic level to Rows too. 
- Values: These are the actual results, dollar amounts, measures, quantitative pieces of data that you want to see. These coul be results or targets, number of individuals reached, etc. 

As a reminder, there are many ways to use and repurpose the four sections (Filters, Columns, Rows, Values) in Pivot Tables, but this is just an example of one could use it with the training data set. You will find your own way to display data efficiently and logically within a Pivot Table with practice. 

### 8. Structural Options **(Katya)**
When creating a Pivot Table in Excel, the default setting for the Report Layout is in Compact form. You can change the layout of your pivot table as you wish. To change the layout of your Pivot Table, click on Design in the top menu, then click Report Layout. There you will see three options for a report layout: Compact, Outline, and Tabular. Click each one of them and see how your pivot table changes. 

Under Report Layout, you can also display item labels to repeat on rows that are blank but aligned with that row field. Two other menu items of interest are the Subtotals and Grand Totals, which can be turned on and off for your Pivot Table.


### 9. Filtering **(Shaylee)**
As mentioned previously, you can filter your pivot table by dragging your fields of interest into the section labeled “Filters”. You can add more than one filter to your table, and you can also select more than one filter per field. To do this:
1)	In the field list section, drag and drop the field(s) of your choice to the box labeled “Filters”. This will showcase the filter above your pivot table.
2)	Click on the drop-down for the field you want to filter by, and select the item you want to be displayed in your pivot table. 
a.	To select more than one item in a certain field, check the “Select Multiple Items” box, and then continue to select the items you want your pivot table to showcase with that field.

### 10. Building pivot charts **(Shazad)**

Often times, you will want to visualize the data being displayed in your pivot table. These can easily be done using the PivotCharts feature. 

This feature will automatically suggest which chart types are possible given the pivot table structure. Furthermore, once a chart is built, any changes to the pivot table will automatically update the visual. 

Once the pivot table configuration is complete, you can go to the analyze tab(you have to already be in the pivot table for this to appear) and then click on the PivotChart button at the top left. 

This will bring up the menu with all of the chart options. Once a chart is chosen, the visual will appear. 

By default, the fields chosen from the pivot table will appear as buttons on the chart. You should remove them. To do so, right-click on a button and select “hide all field buttons”. 

If right-clicking does not prompt this menu, then go to the analyze tab (may need to click on chat first) and then click on field buttons at the top right. Select the option to ‘hide all’.   

### 11. Adding slicers **(Shaylee)**
Another way to filter your pivot table is through slicers. Slicers are another quick way to filter your data, and remain visible with your table so you’re always aware of which fields and items are presented in the pivot table. To add slicers:
1)	Click anywhere in your pivot table and select “Design” under “Table Tools” by the menu bar.
2)	Select “Insert Slicer” and a small window will open that displays your data fields. 
3)	Select the field(s) you’d like to filter your table by, and click “OK”.
4)	Your slicer box will then appear and will be linked to that specific pivot table.

The default for a slicer will only allow you to select one item per field at a time. To filter by more than one item within a field:
1)	In the slicer box, select one item in the slicer you want to filter the table by.
2)	Go to the to right corner of the slicer box and click on the icon with multiple check marks. This will allow you to select additional items to filter.

To clear your slicer filters, simply click on the “FilterX” icon in the top right corner of your slicer.
You can also link your slicers to more than one pivot table and/or pivot chart at a time – if you want to filter these displays by similar fields and items. To do this:
1)	Right-click on the slicer you want to link to additional pivot tables/pivot charts.
2)	Select “Report Connections”. This will show you all the Pivot tables and pivot charts you can link the slicer to within your workbook.
3)	Check the intended tables/charts you want to link and click “OK”. This will now link the filters you select in that specific slicer to whichever tables/charts you selected.

*As a general reminder, no matter which method of filtering you choose, always be aware of what data is being displayed in your pivot table, as well as what filters are being applied.*

### 12. What are calculated indicators and how to create them **(Imran)**
INTERIOR. OFFICE

The BOSS pokes her/his into the office. 
>How are we doing on testing? 

Abruptly leaves.

The analysts thinking aloud. 
>I guess she/he wants to see percent achivement on targets... I can throw in some yield!

Voiceover: 
We don't have those ratios in the standardized datasets we are using. Additionally, since they are ratios, we cannot create them in the back-end of the raw data table. We would need to use the following:
`Calculated Field` and `Calculated Item`.

To get percent target achievement, we will use FY2018APR (as numerator) and FY2018_TARGETS (as denominator). They are separate columns in the raw dataset, so we can use the `calcluated field` option. Please follow the these steps to create a calculated field. On the Analyze tab, in the Calculations group, click Fields, Items & Sets. Then choose `Calculated Field`. In the dialogue box, enter a name for target achievement `Perf_achv` for example. Then use the forumla box to enter the formula for target achievement. `FY2018APR/FY2018_TARGETS`. Click okay. Viola! You've just created your calculated field. This option is less processing intensive, and the most commonly used way to get calculated indicators, especially ratios. 

Now for the hard part: Creating a calculated item, which uses categories within the same column in the raw data. In our case, we're calculating `yield`, which is the ratio of HTS_TST_POS/HTS_TST, both of which are in the same `Indicator` column. We're going to do it for `Total Numerator` values by filtering for it in the `StandardizedDisaggregate` column to keep it simple. Follow the same steps as above, but choose the `Calculated Item` option in the dropdown. A note of caution: Keep in mind that you should be in the pivot table in the row labels area, otherwise the `Calculated Item` option will be greyed-out. In the dialogue box for calculated item, write a name for your calculated indicator. For example `Yield`, and then enter the formula for yield choosing the appropriate indicators from the `items` list. `HTS_TST_POS/HTS_TST`. Woot, woot! You should see `Yield` in the pivot table as a ratio. Note of caution: `Calculated Item` can be more processing heavy than `Calculated Field`, and I wouldn't recommend using it for very large datasets. 

The BOSS pokes her/his head in again. 
>So... 

He's cut off by the ANALYST: 
>I'm done! 

BOSS: 
>Wow, that was really quick! I was coming by to tell you I changed my mind. I don't think targets make any sense to me!

FADE TO BLACK




### 13. Considerations when building an Excel tool **(Shazad)**

There are additional steps to consider with your pivot table if you are building a tool or dashboard, especially if the pivot table will be refreshed with new data in the future. 

#### Converting into an Excel Table ####
The first tip is to convert the raw data into an excel table. This step should precede the creation of any pivot tables, because you will want all of your pivot tables to talk to the excel table you are converting the raw data into. To convert to an excel table, select any cell in your raw data range, go to the insert tab and then click on the table button at the top left. After the conversion, you should see formatting on the raw data.  

#### Naming the Pivot Tables ####
If the tool will contain several sheets with multiple pivot tables, a good idea is name your pivot tables with unique names so management of the tables becomes easier. To do this, right-click on a pivot table, select Pivot table Options, and enter a name. This is helpful in keeping track of tables and in managing slicer connections. 

#### Tab/Sheet Structure ####
If building a tool with multiple sheets with multiple pivot tables, consider where pivot tables are placed in relation to the charts & graphs. It may be a good idea to store pivot tables on a hidden sheet while the graphs that are populated by the tables are visible on a separate sheet. You may want to store the pivot table on the same sheet as the graph as well. It depends on the needs and desired aesthetics for the tool.  

#### Refreshing the Data ####
If the tool you are creating will require routine or multiple updates, it is first important to first convert the raw data into an excel table. Then, when creating pivot tables, it is important to ensure they are all connected to the same raw data.  Then, whenever new data is imported into the raw data(which should be an excel table), you can hit ‘refresh all’ to refresh all pivot tables in one click. The ‘refresh all’ button is in the analyze tab once a pivot table is clicked on. 

### 14. Resources **(ALL)**
- Data Dictionary for MSD, SIMS, etc. + Katie O.
