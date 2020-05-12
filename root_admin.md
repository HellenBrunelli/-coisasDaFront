# ATIVANDO A CONTA ROOT NO UBUNTU

Essa dica é para habilitar a conta root no Ubuntu, não sendo mais necessário ficar usando o comando "sudo" toda vez que for necessário dar um comando como super usuário.

Mas porque habilitar ou desabilitar a conta de super-usuário? Essa pergunta pode ser respondida da seguinte forma: a conta vem desabilitada por padrão porque não é seguro trabalhar como root o tempo todo, pois algum arquivo poderá ser movido ou editado de forma equivocada, sendo assim a conta fica restrita a ser usada com o comando sudo antes de cada comando para justamente evitar equívocos, porém quando estamos trabalhando montando serviços, programando ou fazendo alguma outra tarefa que exija poder de super-usuário, é super desagradável ficar usando o sudo, por isso é viável a habilitação do root, sendo necessário somente abrir um terminal, digitar "su" e colocar a senha do root.

## **1A. FORMA**

Para habilitar dê o comando abaixo um terminal:

> $ sudo passwd root

Digite e confirme a senha.

Pronto, agora para utilizar o usuário root basta se logar em um terminal e:

$ su root

e digitar a senha escolhida.

Para desabilitar a conta do root basta:

$ sudo passwd -l root

Aí a conta será desabilitada.

## **2A. FORMA**

Outra forma de habilitar a conta é:

$ sudo su
$ passwd

Digite e confirme a senha.

(Essa segunda forma foi contribuída pelo moderador chemonz)

ATENÇÃO: Muito cuidado ao usar a conta de ROOT, tenha certeza do que você faz, pois pode estragar o sistema.

Muito obrigado pelo espaço. :)

Felicidades a todos.
