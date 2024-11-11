# Cloud Computing


```
mkdir key
docker run -p 22:22 -d -v key/:/home/alunno/ atmoz/sftp alunno:password:1001
```


```
printf '%s\n' {0..15} | xargs -I {} scp ./alunno-{}.json alunno@<ip>:/key/
```

