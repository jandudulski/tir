# Validation and DDD

[link](https://enterprisecraftsmanship.com/posts/validation-and-ddd/)

## TL;DR

`Execute`/`CanExecute` - run a method and raise exception when validation failed + provide validation method that return plain errors, so caller can check them earlier (like `exists` and `insert unique` when playing with DB).
