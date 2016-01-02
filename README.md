# Common Lisp Script

Common Lisp Script provides isomorphism between browser side and server side to Common Lisp as javascript's node.js and Clojure's ClojureScript.

## To be achieved

- Isomorphism in Common Lisp between browser side and server side.
- Proper interbridging between Common Lisp and javascript.
- Separate compilation and dependency management.
- Integration management into HTML files.
- Ease of debugging.
- Profiling.

## Scoping

Common Lisp Script targets the second of following considerable scopes.

- Abstraction including HTML and CSS, not only javascript.
- **Isomorphism in Common Lisp between browser side and server side.**
- Expressing javascript in S-expression (Parenscript).

## Milestones

1. Compiling a file
  - Compile a Common Lisp source file to a javascript source file.

2. Compiling multiple files
  - Compile multiple Common Lisp source files to a javascript source file.

3. Compiling a system
  - Compile a ASDF system to a javascript source file with resolving dependency.

4. Compiling multiple systems
  - Compile multiple ASDF systems to a javascript source file with resolving dependency.

5. Bridging from Common Lisp to javascript
  - Invoke javascript functions from Common Lisp.

6. Bridging from javascript to Common Lisp
  - Invoke Common Lisp functions from javascript.

7. Integration into web application framework
 -  - Integrate into web application framework.

8. Optimization
 - Dead code elimination.

9. Increasing specification compatibility
 - Better Common Lisp specification compliance.

## Approaches

a. Based on jscl
  - Based on [jscl](https://github.com/davazp/jscl), a Lisp to javascript compiler working on javascript.
  - The browser loads the compiler as javascript source file.
  - The compiler on javascript VM evaluates jscl source codes.

b. Another Common Lisp to javascript compiler
  - Provide another Common Lisp to javascript compiler working on Common Lisp.
  - The browser loads compiled javascript source files.

## Futher more

- ReactCL
  - Facebook's React interface like ClojureScript's Om.
