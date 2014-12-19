## Mstruct

Mutable [cstruct](https://github.com/mirage/ocaml-cstruct) buffers.

```ocaml
# #require "mstruct";;
# let b = Mstruct.create 9;;
val b : Mstruct.t = <abstr>
# Mstruct.set_string b "hello";;
- : unit = ()
# Mstruct.set_uint32 b 32l;;
- : unit = ()
```