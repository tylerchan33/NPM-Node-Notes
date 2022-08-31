# NPM-Node-Notes

---

- node has a function that allows your to import code from one file to another
- module means snippet of code
- three different types of modules  
    1. Core Modules - ones that are built into the system
    2. Local Modules - one that you make
    3. Third Party Modules - ones that you can download and use

1. Create your modules
    - make sure to export your module so that it can be used

2. use the require function to import the module to new file

3. run node ${filename}.js to import the module


You can download new NPMs by typing: 

```npm -i -g ${npm package}```

do not push modules to github, use gitignore to hide the files when pushing to github

be wary of packages you download from NPM.  It is possible to download viruses/malware.  Properly vet them first.
