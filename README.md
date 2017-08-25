# getthereCodequalityStandards
Get There's global code quality standards used by coworkers within the company. 

## Java CheckStyle Configuration 
This configuration file enforces a proper use of the Java programming language. 

This is a duplicate of Google Checkstyle's document, with a few changes to the original. 
- Line-length is 120 characters.
- Indentation-length is 4 spaces. 
- All import checks are deleted; imports can be used in random order and can include wildcards.  
- Catch exception naming convention changed from ^[a-z][a-z0-9][a-zA-Z0-9]*$ to ^[a-z][a-zA-Z0-9]*$; name convention allows for names like 'e'. 

One can import this configuration over HTTP in IntelliJ by downloading the 'checkstyle-IDEA' plugin. 
`https://raw.githubusercontent.com/jasperdj/getthereCodequalityStandards/master/javaCheckstyleConfiguration.xml`

