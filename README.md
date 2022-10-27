The technical/ directory is a subdirectory of
https://anc.org/data/oanc/download/

cmds:
javac -cp ".;lb/hamcrest-core-1.3/jar;lib/junit-4.13.2.jar" *.java
java -cp ".;lib/junit-4.13.2.jar;lib/hamcrest-core-1.3.jar" org.junit.runner.JUnitCore TestDocSearch 
scp TestDocSearch.java cs15lfa22ni@ieng6.ucsd.edu:~/skill-demo1/TestDocSearch.java
FileHelpers.readfile()to f.getAbsolutePath()
/search?q="arg"
/search?q=technical
/search?q=technical/
/search?q=rr74

