# ARVlib

## Build it

First build Z3's Java bindings [see
here](https://github.com/Z3Prover/z3/tree/master/src/api/java) and copy the following to
the `lib/` directory:

- "libz3*"
- "com.microsoft.z3.jar"

Then run `ant`.

You will have a `jar` file `dist/symaut.jar`
