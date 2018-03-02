Query Builder Extension
=================

Welcome to the Query Builder Extension source code repository. "Query Builder Extension" is an Extension for the Lucee Server & web.

Building from source
--------------------

### 1. Before you get started

Before you can start building Query Builder Extension from source, you will need a few things installed on your machine:

 **Apache ANT** - the source code contains a build script that will automate the build process for you. you will need ANT installed in order to run these build scripts. http://ant.apache.org/bindownload.cgi


### 2. Get the source code

If you are familiar with GIT, then by all means, clone the repository and grab all the branches at once.

### 3. Run ANT

Open a Command Prompt (or Shell) and change the working directory to the directory where the file build.xml is located and run ant by simply typing 

    ant 

The build process should only take a couple of seconds.  Once it's finished, you can find the newly built extension in **/dist/querybuilder-extension-xxx-ALPHA.lex

After the Build you may install through server or web. If you installed extension CFC available in 

For Server:
{lucee-server}\components\org\lucee\cfml\QueryBuilder.cfc
{lucee-server}\components\org\lucee\cfml\QB.cfc

For Web:
{lucee-server}\components\org\lucee\cfml\QueryBuilder.cfc
{lucee-web}\components\org\lucee\cfml\QB.cfc

