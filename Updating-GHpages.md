# Use this guide if you want to update GitHub Pages preview
1. The first step is to build the app using Ionic
`npm run ionic:build --prod`

2. Make sure you copy the `/www` directory into the `/docs` directory using
`cp -r www docs/` from the the MIM-2018 direcotry

3. Afer making changes, don't forget to use the normal *git* repo process:
    - `git add <whatever you're committing>` to put the updates into the queue
    - `git commit -m <commit message>` to set up the commitment 
    - `git push origin <branch>` to push the update up to the proper branch
    - `git push ionic <channel>` to push the update to the proper branch on Ionic Pro
    
4. At this point, you should be able to go to [the GitHub Pages site for this app](https://mrh250.github.io/MIM-2018/www/# "MIM 2018 Companion App") to see any changes made.
