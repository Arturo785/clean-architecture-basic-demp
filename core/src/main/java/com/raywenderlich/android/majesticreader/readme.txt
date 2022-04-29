all of these files do not rely on the android sdk and work separate from it
the framework and UI implementations belong to the app module because it does need the android sdk


The center circle is the most abstract, and the outer circle is the most concrete.
 This is called the Abstraction Principle.
  The Abstraction Principle specifies that inner circles should contain business logic,
   and outer circles should contain implementation details.


Another principle of Clean Architecture is the Dependency Rule.
This rule specifies that each circle can depend only on the nearest inward circle
 — this is what makes the architecture work.