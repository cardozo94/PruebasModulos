# PruebasModulos

This is a test project to get involve with new feature of Java called modules. I use Java 11.0.15 to it. But it should work since Java 9. It is related with [UsoModulos][link_UsoModulos] Project to see the full behaviuor. I define as public package *co.camcar.producto* to use in *UsoModulos* Project. If I don't specify as public with reserved word __exports__ on *module-info.java* the package will be as private for other projects or modules like the *co.camcar.descuento* package here. 

[link_UsoModulos]: https://github.com/cardozo94/UsoModulos