# Getthere Code quality Standards
Get There's global code quality standards used by coworkers within the company. 

## Git strategy 
We use the GIT flow strategy. For simplification and automation one can use `Git Flow integration` plugin for IntelliJ. 

## Optional IntelliJ plugins
`.ignore` for intelligent .ignore file integration with git.  

## Java CheckStyle Configuration 
This configuration file enforces a proper use of the Java programming language. 

This is a duplicate of Google Checkstyle's document, with a few changes to the original. 
- Line-length is 120 characters.
- Indentation-length is 4 spaces. 
- All import checks are deleted; imports can be used in random order and can include wildcards.  
- Catch exception naming convention changed from ^[a-z][a-z0-9][a-zA-Z0-9]*$ to ^[a-z][a-zA-Z0-9]*$; name convention allows for names like 'e'. 

One can import this configuration file in IntelliJ by downloading and using the 'checkstyle-IDEA' plugin. 

## Typescript linter (TSLint.json)
This configuration file enforces a proper use of the Typescript programming language. 

It is a duplicate from release v5.6.0 repo https://github.com/palantir/tslint/blob/master/tslint.json.

One can import this configuration by downloadig the file and adding it to the project root and then activate IntelliJ's TSLint plugin in the settings. (Ctrl + alt + s - search for 'tslint'). Note: make sure you install TSLint (`npm install -g tslint typescript`) 



