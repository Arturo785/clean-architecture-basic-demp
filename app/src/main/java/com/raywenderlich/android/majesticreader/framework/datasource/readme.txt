the datasource is the implementation of the data abstractions of and implemented here with the framework sdk
this and the UI layer are in the same layer so they can be related



The center circle is the most abstract, and the outer circle is the most concrete.
 This is called the Abstraction Principle.
  The Abstraction Principle specifies that inner circles should contain business logic,
   and outer circles should contain implementation details.


Another principle of Clean Architecture is the Dependency Rule.
This rule specifies that each circle can depend only on the nearest inward circle
 — this is what makes the architecture work.