git bisect sirve para encontrar el commit que metio un bug en un proyecto, en vez de mirar todos los commits uno por uno. el problema que resuelve es  cuando antes todo funcionaba y despues de muchos commits, aparece un fallo y no sabes quien lo causo.

Lo usaria en la situacion que por ejemplo digamos que estoy haciendo una web y el login deja de funcionar tras 100 commits pues usaria git bisect

Para que funcione bien necesitas saber un commit donde iba bien y otro donde falla.
