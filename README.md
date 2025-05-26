# How to deploy new htwml files (e.g. SCORM export) as a github page:

- create a new repo which is using this one as a 'template' (from dropdown choose github-page-template). make it public.
- say new repo is called 'banana'. copy the url like https://github.com/DDI-Talent/banana
- still on that github page click Settings > Pages (or go to https://github.com/DDI-Talent/banana/settings/pages) and in the Bramch header select 'main' and '/docs'.
- Now let's head to github desktop app, to create a local copy of that repo (clone it). In github desktop go File > Clone Repository > Url, use the url from above like https://github.com/DDI-Talent/banana
- click the 'current repository' in top left and 'open/reveal in File Exporer/Finder'
-  you will see the folder called 'banana'. Drag-and-drop the files you want into the /docs sub-folder in there
- among the files you want to publish there will most likely be one calledn index.html - that's how you know you're copy-pasting the right thing.
- back in github desktop, on the bottom left there is a window for your commit message. Write a short note there what you are uploading (e.g. 'new version of course X'). And the press a large blue COMMIT TO MAIN buttom.
- a new big blue button called PUSH ORIGIN will show up. Click that.
- in a few minute yoru cntent will be uploaded to https://ddi-talent.github.io/banana
- if for whatever reason you're unsure if things worked, go to https://github.com/DDI-Talent/banana/actions and you should see a green tick next to 'pages build and deployment' e.g. 2 minutes ago. If it's still in progress, orange spinner will spin. 
