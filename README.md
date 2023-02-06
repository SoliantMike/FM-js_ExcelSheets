FM-js_ExcelSheets
===========
This file uses javascript to create an XLSX file. It can be easily adapted to your solutions as needed. There are minimal fields involved, and a couple scripts that drive the solution. 

To run the demo:

1. Check the boxes to select what sheets to include in your Worksheet.

2. Click the "Save as Excel" button

3. View the results. if "Automatically Open" was checked, a copy is exported to the desktop and launched.

The javascript used is in the Resources table, and can be modified for your use from there.

Uses the Javascript Library from Github here:
https://github.com/SheetJS/js-xlsx

Please view that for licensing information regard uses for that piece.

Now updated to support FileMaker 19 and uses the ability to call javascript functions in a web viewer and the ability to call FileMaker scripts from javascript and pass parameters. This avoids potential string limits in urls or the workaround of setting the clipboard in windows, since the resulting parameter can be passed directly from javascript to a FileMaker script.

Read more here:
http://www.soliantconsulting.com/blog/2017/06/filemaker-16-javascript-changes
