# Exceptions for flow control in C#

[link](https://enterprisecraftsmanship.com/posts/exceptions-for-flow-control/)

## TL;DR

* Throw an exception to state an unexpected situation in your software.
* Use return values for input validation.
* If you know how to deal with exceptions a library throws, catch them at the lowest level possible.
* If you have an unexpected exception, discard current operation completely. Don’t pretend you know how to deal with them.


