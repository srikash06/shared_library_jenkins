# shared_library_jenkins

Shared library in Jenkins:
It is a file/code which is available on a common platform for all to access.
We can create a shared library and place it in github.
when writing the pipeline it will go to github and fetch that piece of code for my pipeline.
shared library = reusable code.

shared libraries are always put in the folder called - vars
Inside vars folder we will write groovy scripts.

The name of the file is
    for ex:- build.groovy
using 'build' we will call shared library in the pipeline.
