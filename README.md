# Calender-Custom-Library
Creating a calendar that can change the start of the week and can change the font color and size.

# Gradle
Step 1 Add the JitPack repository to your build file. Add it in your build.gradle at the end of repositories.

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step-2 Add the dependency in the form
  
  	dependencies {
	        implementation 'com.github.asadej0951:Calender-Custom-Library:Tag'
	}
  
  # Maven
  
  	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
  
  Step 2. Add the dependency
  
  	<dependency>
	    <groupId>com.github.asadej0951</groupId>
	    <artifactId>Calender-Custom-Library</artifactId>
	    <version>Tag</version>
	</dependency>
