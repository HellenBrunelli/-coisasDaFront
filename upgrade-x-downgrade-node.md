### **Como atualizar (ou fazer o downgrade) o Node.js usando o npm**

Precisa atualizar sua versão do Node.js? Veja como você pode atualizar ou fazer o downgrade na linha de comando usando o npm.

**Upgrade vs DownGrade**

4r4er
Determinando sua versão do nó
Primeiro, vamos descobrir qual versão do Node está atualmente instalada.

> __node -v__


O número da versão exibido é o que está ativo no momento em sua máquina. Agora, vamos instalar um programa chamado n que nos permitirá alternar facilmente entre as versões do nó.

> __sudo npm install -g n__


Atualizando para a versão estável mais recente
Depois que o n for instalado, esse comando simples atualizará você para a versão estável mais recente do Node.

> __sudo n stable__


Mudando para uma versão específica
Se você precisar de uma versão específica, basta especificar o número da versão desejada.

> __sudo n 10.16.0__

<br>

[Versões NodeJs](https://nodejs.org/en/download/releases/)
