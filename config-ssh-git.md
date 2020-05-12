## Configurar ssh para git *Linux



Abra um novo terminal e rode o comando:

```
ssh-keygen
```

Dê enter 3 vezes para criar sua ssh.

Serão criadas duas ssh:

| chave | Description |
| --- | --- |
| `id_rsa` | Chave privada |
| `id_rsa.pub` | Chave pública|

Rode os cmd 
```
ssh-add ~/ssh/id_rsa.pub
```

cat < ~./ssh/id_rsa


