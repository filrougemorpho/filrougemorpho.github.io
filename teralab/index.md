# Cheat Sheet TeraLab

Connexion: 
``` 
ssh -p 2230 mguilouet@ws14.tl.teralab-datascience.fr
```

Connexion avec redirection (tensorbroad):   
```
ssh -p 2230 -L 6006:localhost:6006 mguillouet@ws14.tl.teralab-datascience.fr 
```

Copie fichiers:
```
scp -P 2230 -v /your/files mguillouet@ws14.tl.teralab-datascience.fr:/your/location
```


