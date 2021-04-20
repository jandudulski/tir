# Domain services vs Application services

[link](https://enterprisecraftsmanship.com/posts/domain-vs-application-services/)

## TL;DR

* Domain services carry domain knowledge; application services don’t (ideally).
* Domain services hold domain logic that doesn’t naturally fit entities and value objects.
* Introduce domain services when you see that some logic cannot be attributed to an entity/value object because that would break their isolation.


