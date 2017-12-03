# Serialization
* http://javarevisited.blogspot.com/2011/04/top-10-java-serialization-interview.html
* https://java-questions.com/Serialization-interview-questions.html
* What is Serialization in Java?
  *Changes to a serializable class can be compatible or incompatible. Following is the 
    * list of changes which are compatible:
        * Add fields
        * Change a field from static to non-static
        * Change a field from transient to non-transient
        * Add classes to the object tree
      List of incompatible changes:
        * Delete fields
        * Change class hierarchy
        * Change non-static to static
        * Change non-transient to transient
Change type of a primitive field
* How to make a Java class Serializable?
* What is the difference between Serializable and Externalizable interface in Java?
* How many methods Serializable has? If no method then what is the purpose of Serializable interface?
* What is serialVersionUID? What would happen if you don't define this?
* While serializing you want some of the members not to serialize? How do you achieve it?
* What will happen if one of the members in the class doesn't implement Serializable interface?
* If a class is Serializable but its super class in not, what will be the state of the instance variables inherited from super class after deserialization?
* Can you Customize Serialization process or can you override default Serialization process in Java?
* Suppose super class of a new class implement Serializable interface, how can you avoid new class to being serialized?
* Which methods are used during Serialization and DeSerialization process in Java?
* Suppose you have a class which you serialized it and stored in persistence and later modified that class to add a new field. What will happen if you deserialize the object already serialized?
* What are the compatible changes and incompatible changes in Java Serialization Mechanism?
* Can we transfer a Serialized object vie network?
* Which kind of variables is not serialized during Java Serialization?
