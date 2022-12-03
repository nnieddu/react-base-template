# Simple react template to start a project faster  
  
All packages in package.json up to date (last version at the last commit time).  
Add open graph and other SEO friendly things, add max favicon / logo compatibily for all browser / webapp (ex: saved signet on iphone desktop).  
Add /styles/ , /assets/ and /components/ folders in src by default  
Add SASS by default for styling.  
  
Remvoved : react default logo, unused css and tsx/jsx.  
  
Add scripts to package.json  
- "mybuild" : "npm run sass && npm run prefix && react-scripts build"  
automatic sass compile and add css prefixs for all browser then build  
- "prefix": "postcss ./src/styles/*.css --use autoprefixer -d ./src/styles/",   
add css prefixs to all css files (default in src/styles/).  
  
Just go to /public/ and search for the `$` character and modify for your needs. Modify all logo for your project need.   
  
#### TS template  
The outdated ```ReportHandler``` is modified to ```ReportCallback``` in reportWebVitals.ts  