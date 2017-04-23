# ClauseIE 

Directly downloaded from their website, and mavenized to be used in a third party project. 

To add it as maven dependency: 
```xml 
    <dependencies>
         ...
        <dependency>
            <groupId>de.mpii.clausie</groupId>
            <artifactId>clausIE</artifactId>
            <version>0.0.1</version>
        </dependency>
        ...
    </dependencies>
    ...
    <repositories>
        <repository>
            <id>CogcompSoftware</id>
            <name>CogcompSoftware</name>
            <url>http://cogcomp.cs.illinois.edu/m2repo/</url>
        </repository>
    </repositories>
```

Now you can make calls to the system, just like how it's done in `de.mpii.clausie.Example.java`. 

 ## LICENSE

* Clausie is distributed under the Attribution-ShareAlike (ver. 3.0 or later) [http://creativecommons.org/licenses/by-sa/3.0/legalcode]

* This distribution includes libraries of the Stanford Parser v. 2.0.5 [http://www-nlp.stanford.edu/software/lex-parser.shtml] which is licensed under the GNU General Public License (v2 or later) [http://www.gnu.org/licenses/gpl-2.0.html]

As explained in the respective license codes both Clausie and the Stanford Parser come with absolutely no warranty.
