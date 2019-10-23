# build source package
When you have such an error message when you try to build source package.
```
error: no currentversion entry in software/javasoft registry! try re-installing java 
and make sure r and java have matching architectures.
```
Try following solution:
1. re-install your java, try both 32-bit or 64-bit. After you finish installation, to make sure you use the right version of Java,
especially when you have multiple version of java in your computer. In Windows, you can modify `path` environment variable to achieve that.
Acoording to my enxprience, this is not the matching architecture problem. Even if you have the same architecture, e.g. x64 or x32, you 
could still have this problem. Try to install a 32-bit Java.
