# mvn-pacakge

fix https://github.com/spring-projects/spring-boot/commit/e743d5fe66302feca910f81a7285ca0caf3e1b84

Andy Wilkinson
@wilkinsona
16:27
It's an annotation processor so it's only used at compile time. Spring Boot's Maven plugin automatically filters it out of the jar that it builds: spring-projects/spring-boot@e743d5f

Thanks Andy Wilkinson 
