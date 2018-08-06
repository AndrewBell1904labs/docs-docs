# Creating a Spring Boot Thymeleaf Project

Sometimes getting started is the hardest part. Here's a quick rundown to starting a Spring Boot project using Thymeleaf.

## How To

* Open https://start.spring.io/
* Select 'Gradle' and '1.5.15' from the top dropdowns
* Provide a 'group name'
  * Java uses the group name to namespace packages. You likely won't run into this problem, but standard conventions is to use an inverse of your domain. For example, a project by the Google Image Search hosted at images.google.com, might use a package name of "com.google.images"
  * If you don't have your own domain, you can use something like "io.github.<yourGitHubName>"
* Provide an 'artifact name', which usually is your project name, all lowercase, with `-`s as needed.
* Add the following dependencies: "Web", "MySQL", "DevTools", "JPA", "Thymeleaf"
* Download and unzip the file to your directory of projects
* Open IntelliJ, and select "Import Project"
* Navigate to your new project directory
* Select "Gradle" and follow the prompts
  * You likely will want to select "Auto Import" and "Use Gradle Wrapper"

## Notes

[Maven - Guide to Naming Conventions](https://maven.apache.org/guides/mini/guide-naming-conventions.html)

Spring Boot 2.0 is now out, but if you're not ready to tackle some of the changes, stick to 1.5.15

[GitHub Pages](https://pages.github.com/) - If you don't have a website, you might check out setting up a free GitHub Pages repository.
