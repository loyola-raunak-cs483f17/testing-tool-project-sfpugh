Sydney Pugh

## Palus 
Palus is an automated testing tool for Java programs which utilizes both 
static and dynamic analysis to generate tests. The tool uses call sequence 
models and dependency relationships amongst methods to generate random tests.

Available at https://code.google.com/archive/p/tpalus/downloads

### Programs Under Test
1. [[ my simple program ]]
2. [[ a more complicated program ]]

### Usage
1. Download **palus-0.2-nodept.jar** from https://code.google.com/archive/p/tpalus/downloads
2. Run *java -javaagent:./palus-0.2-nodept.jar=<short-name> -cp ./palus-0.2-nodept.jar:$CLASSPATH <main-class>*
3. Run *java -cp ./palus-0.2-nodept.jar palus.main.OfflineMain --time_limit 10 --class_file <classes-to-test>.txt --trace_file <short-name>_trace.model*
4. Tests should be in a directory called *tests*
