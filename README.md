# very_simple_cross-device_4x1_banner
### boilerplate code to further the idea of common breakpoints as part of the standard for IAB flex ads

These breakpoints were extracted from the size ranges mentioned in https://www.iab.com/wp-content/uploads/2017/08/IABNewAdPortfolio_FINAL_2017.pdf on pages 9 + 10.

##### index.html
uses the superset of size ranges for every horizontal aspect ratio ad format found in the table.
As a means of simplification, breakpoints would not deviate among horizontal aspect ratio ad formats. (Only image height would.)

##### index_S_XL.html 
uses only one breakpoint for width as listed for the two size ranges of the 2x1 in the table, labeled as "Small" and "X Large".

##### In any case the <img> tag serves as a fallback for IE.

As far as complexity of the creative workflow goes, less breakpoints would be desireable. So creating an image set for index_S_XL.html would be less intricate than for index.html. However, a batch process in e.g. Photoshop could close the gaps between these image sets easily, as long as that the ad's layout and readability do not necessarily need adjustments. 


##### for purposes of testing within an ad container use : 
<iframe src="https://s3.eu-central-1.amazonaws.com/iqdcdn/2a8c42d73d00128e/index.html" style="display: block;
border-style: none; width: 100%; height: 100%" scrolling="no"></iframe> 

##### Wherever creative suites, used for creating rich HTML5 ads, feature the import of templates, one should look into the possibility to offer similar markup for these programs accordingly.
