# GO WEBSERVER

```mermaid
graph LR
    A[Server] ---> B[/]
    A ---> C[/hello]
    A ---> D[/form]
    B ---> E[index.html]
    C ---> F[hello func]
    D ---> G[form func]
    G ---> H[form.html]
```