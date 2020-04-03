# maven-unknown-error
  
### getting Unknown error in line 1 of pom.xml?

    Answer : 
      https://bugs.eclipse.org/bugs/show_bug.cgi?id=547340
      this is bug in Eclipse Cannot import any project into Eclipse with maven-jar-plugin 3.1.2
      
      Add 3.1.1 in to properties like below than fix issue
      <properties>
              <java.version>1.8</java.version>
              <maven-jar-plugin.version>3.1.1</maven-jar-plugin.version>
      </properties>
