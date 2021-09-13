1:

Pattern: (?'MM'\d{1,2}).(?'DD'\d{1,2}).+(?'YYYY'\d{4})

Substitute: $YYYY-$MM-$DD



2.a:

Pattern: (.+$)(\n|$)

Substitute: "$1",



2.b:

Pattern: "(\S+)"(, |$)

Substitute: $1\n



3:

Table always needs to be saved as raw text file (e.g. csv). This requires consistency such as ISO 8601 standard dates, tidy formats, "NA" instead of empty cells and only one value per cell. No graphs or math in the sheet that cannot be saved raw. Make backups or use version control. Reduce human error: Select good names, use data validation, remove automatic formatting, have a data dictionary for encoding which types of data is expected in each cell. Use Google Sheets or similar to allow shared editing, version control and proper data validation.



4:

Pattern: (?i)d ?m ?s |di[is] man\w+(?=\W)(sacrum)?



Hard to find the 6 invocations. I only found: DMS, DM, dis manes, dii manes, dis manibus, dis manibus sacrum, dii manes sacrum... I imagine I missed something here.