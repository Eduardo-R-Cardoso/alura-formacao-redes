## Descrição do projeto

### Áreas da Empresa:

Em uma empresa, temos 2 setores:
* Vendas (Capacidade para 300 colaboradores)
* Financeiro (Capacidade para 100 colaboradores)

#### Requisitos:

* Cada setor deve ter sua sub-rede.
* A conexão deve ser possível através da rede cabeada ou sem-fio.
* Os setores devem possuir uma redundância com o Switch principal, e estar com o STP configurado para a melhor rota.
* O Gerente de cada setor (Vendas e Financeiro) trocaram de sala para aprenderem como o outro setor trabalha, porém, devem estar conectados nas suas respectivas sub-redes originais.

### Servidores da empresa:

A empresa possui 2 servidores:
* Administração
* IPv6

#### Requisitos:
* O servidor de Administração deve ser acessado apenas pelos gerentes.
* O Servidor IPv6 deve utilizar IPv6 e deve ser acessado por todos.

### Operadora A:

A Operadora A, deve possuir 1 servidor HTTP, onde deve possuir o site da Alura. A comunicação interna deve ser realizada utilizando o protocolo RIP.

### Operadora B:
A Operadora B, deve possuir 2 servidores (DNS, HTTP(Google)). A comunicação interna deve ser realizada utilizando o protocolo OSPF.

### Comunicação entre Operadoras:
A comunicação entre as Operadoras devem ser realizada utilizando o protocolo BGP.

## Endereços:

###  Servidores:

* Servidor Administração: 172.16.2.130
* Servidor IPv6: 2003:BAA::BBBB
* Servidor Alura: 150.1.1.10 (DNS: www.alura.com.br)
* Servidor DNS: 170.1.1.2
* Servidor Google: 190.1.1.2 (DNS: www.google.com)

 
