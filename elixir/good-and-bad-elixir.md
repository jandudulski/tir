# Good and Bad Elixir

[link](https://keathley.io/blog/good-and-bad-elixir.html)

## TL;DR

* Use Access instead of `Map.get/2` and `Keyword.get/2`
* Don't pipe results
* Don't pipe into case
* Don't hide higher order functions
* Avoid `else` in `with`
* Follow green path
* Return tuples only when caller handle them
* Raise exceptions if you receive invalid data
* Use `for` in tests
