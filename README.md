# Chart maker
Tool that formats an image as a paper nautical chart that can be used for traditional chartplotting. Facilitates georeferencing by clicking to points and providing the latlong information for those points.

![image](https://user-images.githubusercontent.com/17980560/162079951-bb59a4f0-94f2-4653-be89-0e3fe05b9241.png)

## Usage 
- Download the file ChartMaker.html to your station, and open it in a browser.
- Paste an image of a map with CTRL-V
- Immediately after pasting the image, click in the image on two known locations. The (x, y) coordinates will be placed in the fields below.
- In the latlong fields, type or copy the lat long values for the two locations
- The values should be positive or negative degrees (negative for westerly or southerly locations). Minute notation is not supported.
- Click the generate button.
- Print the result to a PDF-file.

## Note
- In the lat fields, a composite, comma-separated latlong can be pasted (e.g. "60.5, 2.3" from right-clicking a location in Google maps). The lon is transferred automatically to the next field.
