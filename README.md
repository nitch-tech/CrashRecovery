# CrashRecovery
Your ship has crashed on a planet. It is your job to make the repairs and get back to space!

# Building and Running 

**1. Clone the repository**
```bash 
# using HTTP 
git clone https://github.com/nitch-tech/CrashRecovery.git
# then enter that directory 
cd CrashRecovery
```

**2. Compile Code** 
```bash
#to compile run 
javac -d bin -cp lib/lwjgl.jar;lib/jogg-0.0.7.jar;lib/jorbis-0.0.15.jar;lib/slick.jar src/crashRecovery/main/*.java
```
**3. Build Jar file**
```bash
#to build jar run
jar cfm CrashRecovery.jar manifest.mf -C bin . -C lib .
#to make sure all files are in the jar you can run 
jar tf CrashRecovery.jar
#if you do not see res folder within jar copy and paste res folder into bin and rebuild jar
```
**4. Running Game**
```bash
#to execute jar run
java -Djava.library.path=lib -jar CrashRecovery.jar
```



# Photos
![Example Photo](https://github.com/nitch-tech/CrashRecovery/blob/master/photos/CrashRecoverySnaps.PNG)
![Example Photo](https://github.com/nitch-tech/CrashRecovery/blob/master/photos/Cras.PNG)
![Example Photo](https://github.com/nitch-tech/CrashRecovery/blob/master/photos/CRASH.PNG)
![Example Photo](https://github.com/nitch-tech/CrashRecovery/blob/master/photos/wAVE.PNG)
