Assignment 15.2
Explain the working and the differences between Maven, Gradle and SBT in detail.
Ans : Maven is an attempt to apply patterns to a project's build infrastructure in order to promote comprehension and productivity by providing a clear path in the use of best practices. It is similar to Apache Ant or Gradle. It does everything on its own we don’t need any additional tools or scripts incorporating other common tasks like downloading & installing necessary libraries etc.
Maven primary goal is to provide developer
•	A comprehensive model for projects which is reusable, maintainable, and easier to comprehend.
•	plugins or tools that interact with this declarative model.
Maven project structure and contents are declared in an xml file, pom.xml referred as Project Object Model (POM), which is the fundamental unit of the entire Maven system. Maven is essentially a project management and comprehension tool and as such provides a way to help with managing:
	Builds
	Documentation
	Reporting
	Dependencies
	SCMs
	Releases
	Distribution
Maven can provide benefits for your build process by employing standard conventions and practices to accelerate your development cycle while at the same time helping you achieve a higher rate of success. Maven’s dependency mechanism help to download all the necessary dependency libraries automatically, and maintain the version upgrade as well.
Maven uses Convention over Configuration which means developers are not required to create build process themselves. Developers do not have to mention each and every configuration detail. Maven provides sensible default behavior for projects. When a Maven project is created, Maven creates default project structure. Developer is only required to place files accordingly and he/she need not to define any configuration in pom.xml. It should be noted that there should be a single POM file for each project. All POM files require the project element and three mandatory fields: groupId, artifactId,version.
Gradle 



