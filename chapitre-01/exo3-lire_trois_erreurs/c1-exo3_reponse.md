## ERREUR1: Retirer un point virgule

```
    c1-exo3_main.cpp:5:39: error: expected ';' after
        expression
        5 |     std::cout<<" AZEMFACK"<< "YAOUNDE"
        |                                       ^
        |                                       ;
    1 error generated.
```

## ERREUR2: Printf au lieu de printf
```
    c1-exo3_main.cpp:6:5: error: use of undeclared identifier
      'Printf'; did you mean 'printf'?
    6 |     Printf(" AZEMFACK YAOUNDE");
      |     ^~~~~~
      |     printf
    C:/msys64/ucrt64/include/stdio.h:350:5: note: 'printf' declared
        here
    350 | int printf (const char *__format, ...)
        |     ^
    1 error generated.
```

## ERREURE3: Retirer la ligne #include <cstdio>
```
    c1-exo3_main.cpp:5:5: error: use of undeclared identifier 'printf'
        5 |     printf(" AZEMFACK YAOUNDE");
        |     ^
    1 error generated.
```