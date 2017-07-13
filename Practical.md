# Practical Question

## Use Case

### Relationship

- Extend relationship
  - used when one use case provides additional functionality that may be required in another use case 
  - there may be multiple ways of extending a use case, which represent variations in the way that actors interact with the use case
  - extension points show when the extension occurs
  - a condition can be placed in a note joined to the dependency arrow (Note that it is not put in square brackets, unlike conditions in other diagrams.)
- Include relationship
  - used when one use case always includes the functionality of another use case
  - a use case may include more than one other
  - can be used to separate out a sequence of behaviour that is used in many use cases
  - should not be used to create a hierarchical functional decomposition of the system
- Generalization
  - shows that one use case provides all the functionality of the more general use case and some additional functionality
  - shows that one actor can participate in all the associations with use cases that the more general actor can plus some additional use cases

### Use case scenario / Use case description

1. Name
1. Participating actor
1. Flow of events
1. Entry condition / pre-condition
1. Exit condition / post-condition
1. Special requirement
