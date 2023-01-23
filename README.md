# POM.xml_for_MAVEN_projects

POM 파일에 꼭 들어가야 할 내용들



  <dependencies>
    <dependency>
      <groupId>org.apache.tomcat</groupId>
      <artifactId>tomcat-jsp-api</artifactId>
      <version>9.0.71</version>
	  </dependency>
  </dependencies>
  
  <build>
  	<plugins>
  		<plugin>
		  <artifactId>maven-compiler-plugin</artifactId>
		  <version>3.8.1</version>
		  <configuration>
			 <source>1.8</source>
			 <target>1.8</target>  
		  </configuration>
  		</plugin>
  		
  		<plugin>
		  <groupId>org.apache.maven.plugins</groupId>
		  <artifactId>maven-war-plugin</artifactId>
		  <version>3.3.2</version>
  		</plugin>
  		
  	</plugins>
  </build>  
