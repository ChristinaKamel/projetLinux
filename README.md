# projetLinux
Transfert d'images entre entre client et serveur

Serveur:
```
gcc server.c
./a.out
```
Client: 
```
gcc client.c
./a.out "image.jpg" 100
```

image.jpg : "path" de l'image a envoyer
100 : cle de cryptage / decryptage

Puis donner  ` 100 ` comme cle de decryptage au serveur
