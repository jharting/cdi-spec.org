Contexts and Dependency Injection for Java EE (CDI) 1.0 was introduced as part of the Java EE 6 platform, and has quickly become one of the most important and popular components of the platform. 

CDI defines a powerful set of complementary services that help improve the structure of application code.

* A well-defined lifecycle for stateful objects bound to lifecycle contexts, where the set of contexts is extensible
* A sophisticated, typesafe dependency injection mechanism, including the ability to select dependencies at either development or deployment time, without verbose configuration
* Support for Java EE modularity and the Java EE component architecture?the modular structure of a Java EE application is taken into account when resolving dependencies between Java EE components
* Integration with the Unified Expression Language (EL), allowing any contextual object to be used directly within a JSF or JSP page
* The ability to decorate injected objects
* The ability to associate interceptors to objects via typesafe interceptor bindings
* An event notification model
* A web conversation context in addition to the three standard web contexts defined by the Java Servlets specification
* An SPI allowing portable extensions to integrate cleanly with the container
