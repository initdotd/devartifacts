# Dev Artifacts  

## Initial Setup

Extract and copy the contents of the <b>DevArtifacts.zip</b> to the root of your project  
1. Run npm install  
   You have to have npm installed on your machine for that to work  
   A new node_modules will be added with dev tool dependencies.  
   That folder is ignored already by .gitignore  
2. Run sfdx plugins:install @salesforce/sfdx-scanner  
3. Run git init  
   Will initialize a local git repository for you  
4. Run git add .  
5. Run git commit -am “Initial commit  
  
## Tips
  
- Check the “scripts” section of package.json for npm aliases  
- To run a command using npm, issue “npm run <alias>”  
- Use git to branch and handle parallel development   
- You can stash, merge, commit, etc. like normal  
- You do not push to a remote  
- Handy to do a pull from org and commit to see what has changed by others  
- Use pmd “npm run pmd:report” to generate the csv  

## Notes/Agenda from the Dev Weekly Checkin

1. npm "npm install"  
   npm install    
   npm install -g shane-sfdx-plugins    
   sfdx plugins:install @salesforce/sfdx-scanner  
   
2. git "git init"  
   optionally branch like you normally would to isolate your changes  
   compare files  
   compare directories  
   sync down from team org before ever change  
   git hooks to autoformat  
  
3. pmd "npm run pmd:report"  
   Run from IDE (Analyze)  
   Run from command line "npm run pmd"  
   Run from CLI and report "npm run pmd:report"  
   Use excel  
   Suppressions  
     

