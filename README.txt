used tinyos-1.x


DEPENDENCIES: (JFUGUE) http://www.jfugue.org/jfugue-2.1.zip

The javafile is for hooking into OscilloscopeRF 
you will need to recompile the OscilloscopeRF with the jfugue library
cmd: javac GraphPanel.java

you may need to export the classpath
ie: (from cygwin)
export CLASSPATH=\;c:\\tinyos\\cygwin\\opt\\tinyos-1.x\\tools\\java\\jfugue.jar

Then load the OscilloscopeRF program into your sensors.
Load TOSBase into your computer's sensor node