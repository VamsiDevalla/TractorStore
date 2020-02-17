# TractorStore
Tractor store is an web application for a tractor company. I am taking micro front ends approach to develop this application.

# Phase 1
In the first phase I have divided the project in two components which are developed by individual teams and are integrated using Links.
# Team-Decide: Develops the product details page.
To serve Team-Decide project run: npx mfserve --listen 3001 team-decide
# Team-Inspire: Develops the recommendations for each product. 
To serve Team-Inspire project run: npx mfserve --listen 3001 team-inspire

# Phase 2
Integration of Team-Decide and Team-Inspire will be done using iframes instead of links. so that entire tractor store can be seen as one application.

# Phase 3
Integration of Team-Decide and Team-Inspire will be done using ajax instead of iFrames.

# Team-Inspire: To avoid cor when team-decide requests for recommendations we should start our server to allow cors
npx mfserve --listen 3002 --cors team-inspire