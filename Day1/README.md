# Notes

## Functions

* Params with same type `(int x, int y)` can be simplified like this `(x, y int)`
* `$ godoc -http=:6060` will open documentation of all installed modules. Custom examples will be listed here

## Loops

* There is only one `for`
* You don't need parenthesis in `for` and brackets are always required

## Benchmarks

```
func BenchmarkXXX(b *testing.B){
    for i := 0; i < b.N; i++ {
        // Call here...
    }
}
```

## Errorf

* `%t` for bool, `%q` for string inside quotes, `%v` is like `ToString`, `%d` for integers