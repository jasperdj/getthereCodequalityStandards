# Intellij Setup Steps 
Dit zijn de IntelliJ stappen die je moet nemen om jouw intellij te configureren voor de Get There standaarden. 

## 1.	Installeer CheckStyle-IDEA Plugin

a.	Ctrl + Shift + a 

b.	Typ 'plugins' enter. 

c.	Klik Browse repositories 

d.	Zoek voor `CheckStyle IDEA` en installeer


## 2.	Configureer CheckStyle-IDEA plugin

a.	Ctrl + alt + s (settings) 

b.	Typ checkstyle in zoek balk links boven 

c.	Download deze configuration file (is op public GIT, lijkt me niet privacy gevoelig): https://github.com/jasperdj/getthereCodequalityStandards/blob/master/javaCheckstyleConfiguration.xml

d.	Voeg de configuration file van confluence lokaal toe door op groene plusje te klikken.


## 3.	Installeer TSLint

a.	Command-line `npm install -g tslint typescript` 

## 4.	Configureer TSLint  

a.	Ctrl + alt + s (settings)

b.	Typ `tslint` in zoekbalk.

c.	Navigeer naar Languages & Frameworks > TypeScript > TSLint 

d.	Klik op Enable. 

e.	Check of de volgende Velden gevuld/gechecked zijn ‘Node interpreter’, ‘TSLint package’, ‘Search for tslint.json’. 

f.	Download TSLint.json file: 
    https://github.com/jasperdj/getthereCodequalityStandards/blob/master/tslint.json 
    
g.	Voeg deze TSlint.json file toe aan de root van het desbetreffende project. 
