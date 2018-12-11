How do you enable spring to scan for declaration of MVC layer beans in spring?
Single Choice - Select one correct answer from the options list.
<mvc:annotation-init/>
<mvc.annotation-load/>
<mvc:annotation-driven/>
None of the above
Q2

 
What is the difference bean @Configuration and @Component in spring?
Single Choice - Select one correct answer from the options list.
Both are same and can be used with any class
@Configuration is not an annotation in Spring, @Component is used to define a Spring Controller
@Configuration is alternative to declaring beans in XML, @Component is just a spring bean
@Configuration is used for resources while @Component is to create custom component
Q3

 
How to reference a bean from another bean in Spring?

Single Choice - Select one correct answer from the options list.
We use the <property> element to set the properties that reference other beans. The <ref> subelement of <property> like this:

 <bean id="foo"
   class="com.Foo">
  <property name="bar">
   <ref bean="bar"/>
  </property>
 </bean>

We use the <properties> element to set the properties that reference other beans. The <ref> subelement of < properties > like this:

 <bean id="foo"
   class="com.Foo">
  <properties name="bar">
   <ref bean="bar"/>
  </ properties >
 </bean>

We use the <parent> element to set the properties that reference other beans. The <ref> subelement of < parent > like this:

 <bean id="foo"
   class="com.Foo">
  < parent name="bar">
   <ref bean="bar"/>
  </ parent >
 </bean>

We use the <child> element to set the properties that reference other beans. The <ref> subelement of < child > like this:

 <bean id="foo"
   class="com.Foo">
  < child name="bar">
   <ref bean="bar"/>
  </ child >
 </bean>

Q4

 
What is the purpose of @Qualifier annotation?
Multiple Choice - This may have multiple correct answers. Select required answer(s) from the options list.
Spring doesn’t support this annotation
It helps specify object with multiple dependency which dependency to inject
It is used in conjunction with @Autowired
Annotation used to qualify the normal bean as spring bean
Q5

 
In BeanFactory interface, what is the purpose of the getBean(String, Class) method?
Single Choice - Select one correct answer from the options list.
It is used to cast a bean from a subtype to a supertype
It is a convenience method used to retrieve a collection from the container and have that collection cast to the correct type.
It is equivalent to the getBean(String) method, but will throw a BeanNotOfRequiredTypeException if the supplied class does not match the class of the bean.
It allows a bean to be managed by Spring programmatically by creating a bean using the name and class supplied.
Q6

 
@RequestMapping and ___________ are RequestMapping annotations, can be used to handle dynamic URIs where one or more of the URI value works as a parameter.
Single Choice - Select one correct answer from the options list.
@PathVariable
@PathValues
@RequestParam
@QueryParam
Q7

 
When injecting values using a constructor, what attributes are required within the <constructor-arg> element if no bean definition is embedded within the <constructor-arg> element?
Single Choice - Select one correct answer from the options list.
value and type
value or index
value and ref
value or ref
Q8

 
What are the different modes of autowiring?
Multiple Choice - This may have multiple correct answers. Select required answer(s) from the options list.
By name
By type
By constructor
By proxy
Q9

 
In Spring's Web MVC framework : a _____that dispatches requests to handlers
Single Choice - Select one correct answer from the options list.
FrontController
DispatcherServlet
WebServlet
Resolver
Q10

 
Select the lifecycle interfaces in spring?(Choose Two)
Multiple Choice - This may have multiple correct answers. Select required answer(s) from the options list.
InitializingBean.
DisposableBean.
InitBean.
DestroyBean.
Q11

 
Is spring beans “singleton” by default?
Single Choice - Select one correct answer from the options list.
TRUE
FALSE
Q12

 
Constructor Injection specified in a configuration file using ______ tag
Single Choice - Select one correct answer from the options list.
<ref>
<property>
<bean>
<constructor-arg>
Q13

 
What is the purpose of @CookieValue annotation in Spring?
Single Choice - Select one correct answer from the options list.
To read html cookies
To bind cookie values send in request to a parameter
To enable Javascript cookies in Spring
There is no such annotation in Spring
Q14

 
How can you define alias to a bean?
Multiple Choice - This may have multiple correct answers. Select required answer(s) from the options list.
defining the ref tag
using the alias tag
using the name attribute
using the parent attribute
Q15

 
What is returned if one invokes getBean() specifying the same bean id multiple times when scope of the bean is not defined?
Single Choice - Select one correct answer from the options list.
Same class every time
Same instance of the bean
Different instance of the bean
None of them
Q16

 
Setter Injection can be specified in a configuration file using ______ tag
Single Choice - Select one correct answer from the options list.
Constructor
Property
Setter
Getter
Q17

 
What do you mean by Dependency Injection?
Single Choice - Select one correct answer from the options list.
Design pattern like Singleton and it checks if all dependencies are loaded and throws Exception if they are not loaded
It is a framework like Spring, Struts
We configure the dependencies for the objects and at runtime they are injected
Dependency Injection is a new feature in Spring that enables AOP
Q18

 
In Spring, the basic IOC container is called as ___________.
Single Choice - Select one correct answer from the options list.
Package
Web container
Bean factory
EJB container
Q19

 
Select the common implementations of ApplicationContext?
Single Choice - Select one correct answer from the options list.
ClassPathXmlApplicationcontext.
FileSystemXmlApplicationcontext.
XMLWebApplicationContext.
All the above.
Q20

 
Is it mandatory to give a name or id to a bean defined in XML?
Single Choice - Select one correct answer from the options list.
No
Yes
Q21

 
Which of the following injection can invoke a parameterized constructor?
Single Choice - Select one correct answer from the options list.
Setter injection
Constructor injection
Dependency injection
Injection
Q22

 
Which of the following interface is implemented for all Spring-based web controllers?
Single Choice - Select one correct answer from the options list.
org.springframework.web.servlet.mvc.AbstractFormController
org.springframework.web.servlet.mvc.AbstractCommandController
org.springframework.web.servlet.mvc.AbstractController
org.springframework.web.servlet.mvc.WebContentInterceptor
Q23

 
What is the use of @PathVariable annotation in Spring REST?
Single Choice - Select one correct answer from the options list.
No such annotation exist in Spring
Used to bind the REST url parameters
Configuration annotation used to configure relative and absolute path
None of the above
Q24

 
Choose the scope which is added in Spring5 version?
Single Choice - Select one correct answer from the options list.
Session
WebSocket
Singleton
Prototype
Q25

 
Which of the following scopes are used for web based applications? (Choose three)
Multiple Choice - This may have multiple correct answers. Select required answer(s) from the options list.
Request
Session
Global session
Singleton
Q26

 
Annotation @RequestMapping can be used on both class and method level?
Single Choice - Select one correct answer from the options list.
TRUE
FALSE
Q27

 
Which of the following statements are true about Spring DAO Support? (Choose 3)
Multiple Choice - This may have multiple correct answers. Select required answer(s) from the options list.
Data Access Support module provides a JDBC-abstraction layer that reduces the need to do  tedious JDBC coding.
Data Access Support for integration of Java Database Connectivity.
JDBC package doesn’t support declarative transcation management.
GethibernateTemplate is used to return the Hibernate Template in DAO
Q28

 
Can you call getBean() method for a bean whose class is abstract?
Single Choice - Select one correct answer from the options list.
No
Yes
Yes, but only if you are using lookup method injection.
Q29

 
What is the difference between POST and PUT?
Single Choice - Select one correct answer from the options list.
There is no difference, you can use either based on convinence
POST handle update while PUT handles create
POST handles create while PUT handles update
None of the above
Q30

 
________________ bean serves static resoutrces in Spring.
Single Choice - Select one correct answer from the options list.
@Configuration
@EnableWebMvc
public class MvcConfig implements WebMvcConfigurer {
    @Override
    public void addResourceHandlers(ResourceHandlerRegistry registry) {
        registry
          .addResourceHandler("/resources/**")
          .addResourceLocations("/resources/"); 
    }
}
org.springframework.mvc.configuration
@Configuration
@EnableWebMvc
public class MvcConfig implements WebMvcConfigurer {
    @Override
    public void addViewResolver(ViewResolver registry) {
        registry
          .addResourceHandler("/resources/**")
          .addResourceLocations("/resources/"); 
    }
}
None of the above.
