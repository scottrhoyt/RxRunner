## Master

##### Breaking

* None

##### Enhancements

* None

##### Bug Fixes

* None

## 0.2.0

##### Breaking

* `stdin`, `stdout`, and `stderr` are now treated as raw `Data`.
  Encoding/Decoding is left to the user.

##### Enhancements

* `stdin` is now available when `launch`ing a `Task`.
* `Task` conforms to `CustomStringConvertible` and `Equatable`.

##### Bug Fixes

* None
