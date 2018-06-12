# NO LONGER SUPPORTED , CHECK THE NEWEST VERION -> [jave2](https://github.com/goxr3plus/jave2)

[![HitCount](http://hits.dwyl.io/goxr3plus/JAVE.svg)](http://hits.dwyl.io/goxr3plus/JAVE)

# How to add it on your Maven Project ?

For them [follow this tutorial to add them to your Local Maven Repository](https://www.mkyong.com/maven/how-to-include-library-manully-into-maven-local-repository/) 


For example (for JAVASYSMON) in my computer i do the following :

> mvn install:install-file -Dfile=D:\GitHub\XR3Player\localLibraries\jave-1.0.2.jar -DgroupId=it.sauronsoftware.jave -DartifactId=jave -Dversion=1.0.2 -Dpackaging=jar

Then add it on the dependencies like this:

```XML
<!-- JAVE -->
<dependency>
	<groupId>it.sauronsoftware.jave</groupId>
	<artifactId>jave</artifactId>
	<version>1.0.2</version>
</dependency>
```

**Download the .jar file i added on releases** , because if you use JitPack you will get the wrong .jar which produces errors .


# JAVE
The **JAVE (Java Audio Video Encoder) library is Java wrapper on the [ffmpeg](https://www.ffmpeg.org/) project. Developers can take take advantage of JAVE to transcode audio and video files from a format to another. In example you can transcode an AVI file to a MPEG one, you can change a DivX video stream into a (youtube like) Flash FLV one, you can convert a WAV audio file to a MP3 or a Ogg Vorbis one, you can separate and transcode audio and video tracks, you can resize videos, changing their sizes and proportions and so on. Many other formats, containers and operations are supported by JAVE.**

Requirements
JAVE requires a J2SE environment 1.4 or later and a Windows or Linux OS on a i386 / 32 bit hardware architecture. JAVE can also be easily ported to other OS and hardware configurations, see the JAVE manual for details.

License
JAVE is Free Software and it is licensed under GPL (you will find a copy of the license bundled into the downloadable software distribution).

Feedback
You can send comments and requests to Carlo Pelliccia.

Make a donation
JAVE is free, but if you find it useful please make a donation via PayPal.

#### Original Website
http://www.sauronsoftware.it/projects/jave/index.php

#### Documentation
http://www.sauronsoftware.it/projects/jave/manual.php

#### Installation and requirements
In order to use JAVE in your Java application, you have to add the file jave-1.0.jar in your application CLASSPATH.

JAVE runs on a Java Runtime Environment J2SE v.1.4 or later.

JAVE includes and uses a ffmpeg executable built for Windows and Linux operating systems on i386/32 bit hardware platforms. In order to run JAVE on other platforms you have to replace the built-in ffmpeg executable with another one suitable for your needs. 
