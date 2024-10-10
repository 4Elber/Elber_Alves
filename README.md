# Elber_Alves
Página da disciplina de Engenharia de Software

- [Elber\_Alves](#elber_alves)
- [1. Introdução](#1-introdução)
- [2. Descrição do sistema](#2-descrição-do-sistema)
  - [2.1. Descrição do cenario onde o sistema deverá funcionar:](#21-descrição-do-cenario-onde-o-sistema-deverá-funcionar)
- [3. Visão geral do sistema](#3-visão-geral-do-sistema)
  - [3.1. Descrição do sistema e suas relações](#31-descrição-do-sistema-e-suas-relações)
- [4. Diagrama ER](#4-diagrama-er)
- [5. Diagrama de classe](#5-diagrama-de-classe)
- [6. Casos de uso](#6-casos-de-uso)
  - [6.1. Casos de uso](#61-casos-de-uso)
  - [6.2. Historia de Usuario](#62-historia-de-usuario)
    - [Clínica Veterinária](#clínica-veterinária)
      - [1. Cadastro de Cliente e Animal](#1-cadastro-de-cliente-e-animal)
      - [2. Informar Condições do Animal](#2-informar-condições-do-animal)
      - [3. Informar Tipo de Ração do Animal](#3-informar-tipo-de-ração-do-animal)
      - [4. Informar Hábitos do Animal](#4-informar-hábitos-do-animal)
      - [5. Atendimento por Vários Veterinários](#5-atendimento-por-vários-veterinários)
      - [6. Atendimento Agendado](#6-atendimento-agendado)
      - [7. Ficha e Prontuário do Animal](#7-ficha-e-prontuário-do-animal)
      - [8. Agendar Atendimentos Futuros](#8-agendar-atendimentos-futuros)
      - [9. Receita Após o Atendimento](#9-receita-após-o-atendimento)
      - [10. Atendimento pelo Atendente](#10-atendimento-pelo-atendente)
      - [11. Fila de Espera](#11-fila-de-espera)
      - [12. Entrevista com o Dono do Animal](#12-entrevista-com-o-dono-do-animal)
      - [13. Preencher Formulário com Entrevista](#13-preencher-formulário-com-entrevista)
      - [14. Exame do Animal e Prontuário](#14-exame-do-animal-e-prontuário)
      - [15. Receita Dependendo do Exame](#15-receita-dependendo-do-exame)
    - [Petshop](#petshop)
      - [16. Venda de Ração para Pássaros](#16-venda-de-ração-para-pássaros)
      - [17. Venda de Sal para Boi](#17-venda-de-sal-para-boi)
      - [18. Venda de Vacina para Animais Adultos](#18-venda-de-vacina-para-animais-adultos)
      - [19. Banho e Tosa para Animais de Fazenda](#19-banho-e-tosa-para-animais-de-fazenda)
      - [20. Vacina para Animais com Raiva](#20-vacina-para-animais-com-raiva)
      - [21. Limpeza de Pata de Camelo](#21-limpeza-de-pata-de-camelo)
      - [22. Banho em Gansos da Finlândia](#22-banho-em-gansos-da-finlândia)
      - [23. Ajuda na Domesticação](#23-ajuda-na-domesticação)
      - [24. Preenchimento de Caderneta de Vacinação](#24-preenchimento-de-caderneta-de-vacinação)
      - [25. Design na Penugem](#25-design-na-penugem)
      - [26. Pagamento com Saco de Algodão](#26-pagamento-com-saco-de-algodão)
      - [27. Pagamento com Galinhas Vivas](#27-pagamento-com-galinhas-vivas)
    - [Clínica Veterinária](#clínica-veterinária-1)
      - [1. Cadastro de Cliente e Animal](#1-cadastro-de-cliente-e-animal-1)
      - [2. Informar Condições do Animal](#2-informar-condições-do-animal-1)
      - [3. Informar Tipo de Ração do Animal](#3-informar-tipo-de-ração-do-animal-1)
      - [4. Informar Hábitos do Animal](#4-informar-hábitos-do-animal-1)
      - [5. Atendimento por Vários Veterinários](#5-atendimento-por-vários-veterinários-1)
      - [6. Atendimento Agendado](#6-atendimento-agendado-1)
      - [7. Ficha e Prontuário do Animal](#7-ficha-e-prontuário-do-animal-1)
      - [8. Agendar Atendimentos Futuros](#8-agendar-atendimentos-futuros-1)
      - [9. Receita Após o Atendimento](#9-receita-após-o-atendimento-1)
      - [10. Atendimento pelo Atendente](#10-atendimento-pelo-atendente-1)
      - [11. Fila de Espera](#11-fila-de-espera-1)
      - [12. Entrevista com o Dono do Animal](#12-entrevista-com-o-dono-do-animal-1)
      - [13. Preencher Formulário com Entrevista](#13-preencher-formulário-com-entrevista-1)
      - [14. Exame do Animal e Prontuário](#14-exame-do-animal-e-prontuário-1)
      - [15. Receita Dependendo do Exame](#15-receita-dependendo-do-exame-1)
    - [Petshop](#petshop-1)
      - [16. Venda de Ração para Pássaros](#16-venda-de-ração-para-pássaros-1)
      - [17. Venda de Sal para Boi](#17-venda-de-sal-para-boi-1)
      - [18. Venda de Vacina para Animais Adultos](#18-venda-de-vacina-para-animais-adultos-1)
      - [19. Banho e Tosa para Animais de Fazenda](#19-banho-e-tosa-para-animais-de-fazenda-1)
      - [20. Vacina para Animais com Raiva](#20-vacina-para-animais-com-raiva-1)
      - [21. Limpeza de Pata de Camelo](#21-limpeza-de-pata-de-camelo-1)
      - [22. Banho em Gansos da Finlândia](#22-banho-em-gansos-da-finlândia-1)
      - [23. Ajuda na Domesticação](#23-ajuda-na-domesticação-1)
      - [24. Preenchimento de Caderneta de Vacinação](#24-preenchimento-de-caderneta-de-vacinação-1)
      - [25. Design na Penugem](#25-design-na-penugem-1)
      - [26. Pagamento com Saco de Algodão](#26-pagamento-com-saco-de-algodão-1)
      - [27. Pagamento com Galinhas Vivas](#27-pagamento-com-galinhas-vivas-1)
- [7. Diagrama de componentes](#7-diagrama-de-componentes)
- [8. Diagrama de Implantação](#8-diagrama-de-implantação)
- [9. Protótipo de telas](#9-protótipo-de-telas)
  - [9.1 Tela de Cadastro de Agenda](#91-tela-de-cadastro-de-agenda)
    - [9.1.1 Relatório de Agenda](#911-relatório-de-agenda)
    - [9.1.2 Detalhe de Agenda](#912-detalhe-de-agenda)
    - [9.1.3 Registro de Agenda](#913-registro-de-agenda)
  - [9.2 Tela de Cadastro de Animal](#92-tela-de-cadastro-de-animal)
    - [9.2.1 Relatório de Animal](#921-relatório-de-animal)
    - [9.2.2 Registro de Animal](#922-registro-de-animal)
    - [9.2.3 Detalhes de Animal](#923-detalhes-de-animal)
  - [9.3 Tela de Cadastro de Atendente](#93-tela-de-cadastro-de-atendente)
    - [9.3.1 Relatório de Atendente](#931-relatório-de-atendente)
    - [9.3.2 Registro de Atendente](#932-registro-de-atendente)
    - [9.3.3 Detalhes de Atendente](#933-detalhes-de-atendente)
  - [9.4 Tela de Cadastro de Atendimento](#94-tela-de-cadastro-de-atendimento)
    - [9.4.1 Relatório de Atendimento](#941-relatório-de-atendimento)
    - [9.4.2 Registro de Atendimento](#942-registro-de-atendimento)
    - [9.4.3 Detalhes de Atendimento](#943-detalhes-de-atendimento)
  - [9.5 Tela de Cadastro de Cliente](#95-tela-de-cadastro-de-cliente)
    - [9.5.1 Relatório de Cliente](#951-relatório-de-cliente)
    - [9.5.2 Detalhe de Cliente](#952-detalhe-de-cliente)
    - [9.5.3 Registro de Cliente](#953-registro-de-cliente)
  - [9.6 Tela de Cadastro de Pagamento](#96-tela-de-cadastro-de-pagamento)
    - [9.6.1 Relatório de Pagamento](#961-relatório-de-pagamento)
    - [9.6.2 Detalhes de Pagamento](#962-detalhes-de-pagamento)
    - [9.6.3 Registro de Pagamento](#963-registro-de-pagamento)
  - [9.7 Tela de Cadastro de Petshop](#97-tela-de-cadastro-de-petshop)
    - [9.7.1 Relatório de Petshop](#971-relatório-de-petshop)
    - [9.7.2 Registro de Petshop](#972-registro-de-petshop)
    - [9.7.3 Detalhes de Petshop](#973-detalhes-de-petshop)
  - [9.8 Tela de Cadastro de Petshop\_Produtos](#98-tela-de-cadastro-de-petshop_produtos)
    - [9.8.1 Relatório de Petshop\_Produtos](#981-relatório-de-petshop_produtos)
    - [9.8.2 Detalhes de Petshop\_Produtos](#982-detalhes-de-petshop_produtos)
    - [9.8.3 Registro de Petshop\_Produtos](#983-registro-de-petshop_produtos)
  - [9.9 Tela de Cadastro de Petshop\_Serviços](#99-tela-de-cadastro-de-petshop_serviços)
    - [9.9.1 Relatório de Petshop\_Serviços](#991-relatório-de-petshop_serviços)
    - [9.9.2 Detalhes de Petshop\_Serviços](#992-detalhes-de-petshop_serviços)
    - [9.9.3 Registro de Petshop\_Serviços](#993-registro-de-petshop_serviços)
  - [9.10 Tela de Cadastro de Produtos](#910-tela-de-cadastro-de-produtos)
    - [9.10.1 Relatório de Produtos](#9101-relatório-de-produtos)
    - [9.10.2 Detalhes de Produtos](#9102-detalhes-de-produtos)
    - [9.10.3 Registro de Produtos](#9103-registro-de-produtos)
  - [9.11 Tela de Cadastro de Prontuário](#911-tela-de-cadastro-de-prontuário)
    - [9.11.1 Relatório de Prontuário](#9111-relatório-de-prontuário)
    - [9.11.2 Detalhes de Prontuário](#9112-detalhes-de-prontuário)
    - [9.11.3 Registro de Prontuário](#9113-registro-de-prontuário)
  - [9.12 Tela de Cadastro de Receita](#912-tela-de-cadastro-de-receita)
    - [9.12.1 Relatório de Receita](#9121-relatório-de-receita)
    - [9.12.2 Detalhes de Receita](#9122-detalhes-de-receita)
    - [9.12.3 Registro de Receita](#9123-registro-de-receita)
  - [9.13 Tela de Cadastro de Serviços](#913-tela-de-cadastro-de-serviços)
    - [9.13.1 Relatório de Serviços](#9131-relatório-de-serviços)
    - [9.13.2 Detalhes de Serviços](#9132-detalhes-de-serviços)
    - [9.13.3 Registro de Serviços](#9133-registro-de-serviços)
  - [9.14 Tela de Cadastro de Veterinário](#914-tela-de-cadastro-de-veterinário)
    - [9.14.1 Relatório de Veterinário](#9141-relatório-de-veterinário)
    - [9.14.2 Detalhes de Veterinário](#9142-detalhes-de-veterinário)
    - [9.14.3 Registro de Veterinário](#9143-registro-de-veterinário)
  - [9.15 Tela de Gráfico](#915-tela-de-gráfico)
    - [9.15.1 Gráfico em Pizza](#9151-gráfico-em-pizza)
    - [9.15.2 Gráfico em Barra](#9152-gráfico-em-barra)
  - [9.16 Tela de Dashboard](#916-tela-de-dashboard)
- [10 Diagrama de navegação](#10-diagrama-de-navegação)
- [11. Pilha tecnológica](#11-pilha-tecnológica)
- [12. Requisitos de sistemas](#12-requisitos-de-sistemas)
- [13. Considerações sobre segurança](#13-considerações-sobre-segurança)
- [14. Manutenção e instalação](#14-manutenção-e-instalação)
- [15. Glossário](#15-glossário)
- [16. Script SQL](#16-script-sql)
  - [16.1 Comandos create](#161-comandos-create)
  - [16.2 Comandos INSERT gerando dados ficticios;](#162-comandos-insert-gerando-dados-ficticios)


# 1. Introdução

O projeto a seguir apresenta um sistema desenvolvido para uma pethop. A empresa é considerada micro e iniciou as atividades recentemente. Ao possuir serviços exclusivos, os sitemas presentes no mercado não se enquadra, desta forma, os proprietários decidiram desenvolver uma solução própria. Esta solução é detalhada a seguir:

---
# 2. Descrição do sistema

## 2.1. Descrição do cenario onde o sistema deverá funcionar:

1. Uma clínica veterinária atende apenas os animais: gatos e cachorros.

2. Os clientes devem fazer um cadastro de si e dos animais.

3. Os clientes devem informar as condições nas quais os animais chegam.

4. Os clientes devem informar o tipo de ração que o animal come.

5. O cliente deve informar hábitos do animal.

6. Para cada animal é possível que mais de um veterinário o atenda.

7. Os animais podem chegar e serem atendidos de acordo com uma agenda do dia. 

8. Cada animal atendido receberá uma ficha e um prontuário. 

9. Outros dono podem querer marcar horários de atendimento futuro. 

10. O atendimento gera uma receita para o animal. 

11. Quando um cliente chega na clínica veterinária ele é atendido por um atendente. 

12. O atendente deve verificar se existe agenda disponível com um veterinário. 

13. O atendente deve colocar o cliente e seu animal na fila de espera, se for o caso. 

14. O atendente deve levar o cliente e o animal até o veterinário. 

15. O veterinário deve realizar uma entrevista com o dono do animal. 

16. O resultado da entrevista deve ir para um formulário. 

17. O veterinário deverá examinar o animal e anotar em prontuário(ficha) suas observações. 

18. Dependendo da situação do animal este receberá uma receita.

19. O petshop vende ração de para passaros da especie gralha.

20. O petshop vende sal para boi.

21. O petshop vende vacina para animais adultos acima de 7 anos.

22. O petshop oferece banho e tosa para animais de fazendas.

23. O petshop oferece vacina de animais com raiva.

24. O petshop oferece limpeza de pata de camelo.

25. O petshop oferece banho a gansos da Finlandia.

26. O petshop ajuda o dono na domesticação.

27. O petshop preenche a cardeneta de vacinação.

28. O petshop faz designs na penugem.

29. Fazemos recebimento com saco de algodão.

30. Recebemos o pagamento com galinhas vivas.

---
# 3. Visão geral do sistema

## 3.1. Descrição do sistema e suas relações

---
# 4. Diagrama ER

```python
print("Meu Diagrama")
```

```mermaid
erDiagram
    %% Entidades principais da clínica veterinária
    CLIENTE {
      int id
      string nome
      string telefone
    }
    ANIMAL {
      int id
      string nome
      string especie
      string condicao
      string tipo_racao
      string habitos
    }
      VETERINARIO {
      int id
      string nome
      string especialidade
    }
    ATENDENTE {
      int id
      string nome
    }
    ATENDIMENTO {
      int id
      date data
      string hora
      string status
    }
    AGENDA {
      int id
      date data
      string hora_disponivel
    }
    PRONTUARIO {
      int id
      string observacoes
    }
    RECEITA {
      int id
      string descricao
      string medicamentos
    }
    CLIENTE ||--o{ ANIMAL : "possui"
    ANIMAL }o--o{ VETERINARIO : "atendido por"
    ATENDENTE ||--o{ ATENDIMENTO : "realiza"
    CLIENTE ||--o{ ATENDIMENTO : "solicita"
    ANIMAL ||--o{ ATENDIMENTO : "é atendido em"
    ATENDIMENTO ||--o{ PRONTUARIO : "gera"
    PRONTUARIO ||--o{ RECEITA : "pode gerar"
    AGENDA ||--o{ ATENDIMENTO : "relacionado a"
    PETSHOP {
      int id
      string nome
      string servico
    }
    CLIENTE ||--o{ PETSHOP : "utiliza serviços"
    PETSHOP }o--o{ ANIMAL : "oferece serviços para"
    PRODUTO {
      int id
      string nome
      string tipo
    }
    PAGAMENTO {
      int id
      string forma_pagamento
    }
    PETSHOP ||--o{ PRODUTO : "vende"
    CLIENTE ||--o{ PAGAMENTO : "realiza"
```

---
# 5. Diagrama de classe

```mermaid
classDiagram
    %% Classe Cliente
    class Cliente {
        +int id
        +string nome
        +string telefone
        +cadastrarAnimal(Animal)
        +informarCondicaoAnimal(Animal)
        +informarRacao(Animal)
        +informarHabitos(Animal)
    }

    %% Classe Animal
    class Animal {
        +int id
        +string nome
        +string especie  %% gato ou cachorro
        +string condicao
        +string tipo_racao
        +string habitos
        +registrarProntuario(Prontuario)
        +gerarReceita(Receita)
    }

    %% Classe Veterinario
    class Veterinario {
        +int id
        +string nome
        +string especialidade
        +atenderAnimal(Animal)
        +realizarEntrevista(Cliente)
        +registrarProntuario(Prontuario)
        +prescreverReceita(Receita)
    }

    %% Classe Atendente
    class Atendente {
        +int id
        +string nome
        +atenderCliente(Cliente)
        +verificarAgenda(Veterinario)
        +colocarNaFila(Cliente, Animal)
        +acompanharAoVeterinario(Cliente, Animal)
    }

    %% Classe Atendimento
    class Atendimento {
        +int id
        +date data
        +string hora
        +string status
        +agendarAtendimento(Cliente, Animal, Veterinario)
        +atender(Cliente, Animal)
    }

    %% Classe Agenda
    class Agenda {
        +int id
        +date data
        +string hora
        +verificarDisponibilidade(Veterinario)
    }

    %% Classe Prontuario
    class Prontuario {
        +int id
        +string observacoes
        +registrarObservacao(string)
    }

    %% Classe Receita
    class Receita {
        +int id
        +string descricao
        +string medicamentos
        +prescrever(string)
    }

    %% Classe Petshop
    class Petshop {
        +int id
        +string nome
        +venderProduto(Produto)
        +oferecerServico(Servico)
        +receberPagamento(string forma)
    }

    %% Classe Produto
    class Produto {
        +int id
        +string nome
        +string tipo
    }

    %% Classe Servico
    class Servico {
        +int id
        +string descricao
    }

    %% Relacionamentos
    Cliente "1" -- "many" Animal : "possui"
    Animal "many" -- "many" Veterinario : "é atendido por"
    Atendimento "1" -- "many" Animal : "realiza"
    Atendimento "1" -- "1" Veterinario : "é feito por"
    Atendimento "1" -- "1" Atendente : "é organizado por"
    Atendimento "1" -- "1" Prontuario : "gera"
    Prontuario "1" -- "1" Receita : "pode gerar"
    Cliente "1" -- "many" Atendimento : "solicita"
    Agenda "1" -- "many" Veterinario : "tem disponibilidade"
    Petshop "1" -- "many" Produto : "vende"
    Petshop "1" -- "many" Servico : "oferece"
```

---
# 6. Casos de uso

## 6.1. Casos de uso

![Casos de uso](Diagrama%20de%20casos%20de%20uso.png)

## 6.2. Historia de Usuario

### Clínica Veterinária

#### 1. Cadastro de Cliente e Animal
**Como** cliente,  
**Quero** cadastrar meus dados e os dados dos meus animais,  
**Para** que eu possa receber atendimento na clínica veterinária.

#### 2. Informar Condições do Animal
**Como** cliente,  
**Quero** informar as condições nas quais meu animal chega à clínica,  
**Para** que o veterinário saiba do estado de saúde do meu pet.

#### 3. Informar Tipo de Ração do Animal
**Como** cliente,  
**Quero** informar o tipo de ração que meu animal consome,  
**Para** garantir que o veterinário tenha informações completas sobre sua alimentação.

#### 4. Informar Hábitos do Animal
**Como** cliente,  
**Quero** fornecer informações sobre os hábitos do meu animal,  
**Para** que o veterinário tenha uma visão mais clara do seu comportamento e necessidades.

#### 5. Atendimento por Vários Veterinários
**Como** cliente,  
**Quero** que meu animal possa ser atendido por mais de um veterinário,  
**Para** garantir que ele receba o melhor cuidado possível.

#### 6. Atendimento Agendado
**Como** cliente,  
**Quero** agendar o atendimento do meu animal na clínica,  
**Para** garantir que ele seja atendido conforme a disponibilidade do veterinário.

#### 7. Ficha e Prontuário do Animal
**Como** veterinário,  
**Quero** criar uma ficha e prontuário para cada animal atendido,  
**Para** registrar as informações de saúde e histórico do animal.

#### 8. Agendar Atendimentos Futuros
**Como** cliente,  
**Quero** marcar horários de atendimento futuros para meu animal,  
**Para** garantir que ele tenha acompanhamento contínuo.

#### 9. Receita Após o Atendimento
**Como** veterinário,  
**Quero** gerar uma receita após o atendimento do animal,  
**Para** prescrever o tratamento adequado.

#### 10. Atendimento pelo Atendente
**Como** atendente,  
**Quero** verificar a disponibilidade na agenda dos veterinários,  
**Para** organizar os atendimentos e garantir que o animal seja atendido no horário correto.

#### 11. Fila de Espera
**Como** atendente,  
**Quero** colocar o cliente e seu animal na fila de espera,  
**Para** garantir que o atendimento ocorra quando o veterinário estiver disponível.

#### 12. Entrevista com o Dono do Animal
**Como** veterinário,  
**Quero** realizar uma entrevista com o dono do animal,  
**Para** entender melhor o histórico e as condições do animal.

#### 13. Preencher Formulário com Entrevista
**Como** veterinário,  
**Quero** registrar o resultado da entrevista em um formulário,  
**Para** documentar as informações fornecidas pelo dono do animal.

#### 14. Exame do Animal e Prontuário
**Como** veterinário,  
**Quero** examinar o animal e anotar minhas observações em seu prontuário,  
**Para** manter um registro completo do estado de saúde do animal.

#### 15. Receita Dependendo do Exame
**Como** veterinário,  
**Quero** prescrever uma receita conforme o exame do animal,  
**Para** garantir que ele receba o tratamento necessário.

---

### Petshop

#### 16. Venda de Ração para Pássaros
**Como** cliente,  
**Quero** comprar ração para pássaros da espécie gralha,  
**Para** alimentar adequadamente meu pássaro.

#### 17. Venda de Sal para Boi
**Como** cliente,  
**Quero** comprar sal para boi,  
**Para** suplementar a alimentação dos meus animais.

#### 18. Venda de Vacina para Animais Adultos
**Como** cliente,  
**Quero** comprar vacina para animais com mais de 7 anos,  
**Para** garantir a saúde dos meus pets.

#### 19. Banho e Tosa para Animais de Fazenda
**Como** cliente,  
**Quero** que meu animal de fazenda receba banho e tosa,  
**Para** garantir que ele esteja limpo e bem cuidado.

#### 20. Vacina para Animais com Raiva
**Como** cliente,  
**Quero** vacinar meus animais contra raiva,  
**Para** protegê-los de doenças.

#### 21. Limpeza de Pata de Camelo
**Como** cliente,  
**Quero** serviços de limpeza de pata de camelo,  
**Para** cuidar da higiene do meu camelo.

#### 22. Banho em Gansos da Finlândia
**Como** cliente,  
**Quero** dar banho em meus gansos da Finlândia,  
**Para** mantê-los limpos e saudáveis.

#### 23. Ajuda na Domesticação
**Como** cliente,  
**Quero** ajuda na domesticação do meu animal,  
**Para** melhorar seu comportamento e convivência.

#### 24. Preenchimento de Caderneta de Vacinação
**Como** cliente,  
**Quero** que o petshop preencha a caderneta de vacinação do meu animal,  
**Para** manter o controle das vacinas aplicadas.

#### 25. Design na Penugem
**Como** cliente,  
**Quero** que o petshop faça design na penugem do meu animal,  
**Para** deixá-lo com uma aparência única e estilosa.

#### 26. Pagamento com Saco de Algodão
**Como** cliente,  
**Quero** pagar com saco de algodão,  
**Para** usar um meio alternativo de pagamento aceito pela loja.

#### 27. Pagamento com Galinhas Vivas
**Como** cliente,  
**Quero** pagar com galinhas vivas,  
**Para** trocar produtos ou serviços do petshop por um meio de pagamento aceito.
### Clínica Veterinária

#### 1. Cadastro de Cliente e Animal
**Como** cliente,  
**Quero** cadastrar meus dados e os dados dos meus animais,  
**Para** que eu possa receber atendimento na clínica veterinária.

#### 2. Informar Condições do Animal
**Como** cliente,  
**Quero** informar as condições nas quais meu animal chega à clínica,  
**Para** que o veterinário saiba do estado de saúde do meu pet.

#### 3. Informar Tipo de Ração do Animal
**Como** cliente,  
**Quero** informar o tipo de ração que meu animal consome,  
**Para** garantir que o veterinário tenha informações completas sobre sua alimentação.

#### 4. Informar Hábitos do Animal
**Como** cliente,  
**Quero** fornecer informações sobre os hábitos do meu animal,  
**Para** que o veterinário tenha uma visão mais clara do seu comportamento e necessidades.

#### 5. Atendimento por Vários Veterinários
**Como** cliente,  
**Quero** que meu animal possa ser atendido por mais de um veterinário,  
**Para** garantir que ele receba o melhor cuidado possível.

#### 6. Atendimento Agendado
**Como** cliente,  
**Quero** agendar o atendimento do meu animal na clínica,  
**Para** garantir que ele seja atendido conforme a disponibilidade do veterinário.

#### 7. Ficha e Prontuário do Animal
**Como** veterinário,  
**Quero** criar uma ficha e prontuário para cada animal atendido,  
**Para** registrar as informações de saúde e histórico do animal.

#### 8. Agendar Atendimentos Futuros
**Como** cliente,  
**Quero** marcar horários de atendimento futuros para meu animal,  
**Para** garantir que ele tenha acompanhamento contínuo.

#### 9. Receita Após o Atendimento
**Como** veterinário,  
**Quero** gerar uma receita após o atendimento do animal,  
**Para** prescrever o tratamento adequado.

#### 10. Atendimento pelo Atendente
**Como** atendente,  
**Quero** verificar a disponibilidade na agenda dos veterinários,  
**Para** organizar os atendimentos e garantir que o animal seja atendido no horário correto.

#### 11. Fila de Espera
**Como** atendente,  
**Quero** colocar o cliente e seu animal na fila de espera,  
**Para** garantir que o atendimento ocorra quando o veterinário estiver disponível.

#### 12. Entrevista com o Dono do Animal
**Como** veterinário,  
**Quero** realizar uma entrevista com o dono do animal,  
**Para** entender melhor o histórico e as condições do animal.

#### 13. Preencher Formulário com Entrevista
**Como** veterinário,  
**Quero** registrar o resultado da entrevista em um formulário,  
**Para** documentar as informações fornecidas pelo dono do animal.

#### 14. Exame do Animal e Prontuário
**Como** veterinário,  
**Quero** examinar o animal e anotar minhas observações em seu prontuário,  
**Para** manter um registro completo do estado de saúde do animal.

#### 15. Receita Dependendo do Exame
**Como** veterinário,  
**Quero** prescrever uma receita conforme o exame do animal,  
**Para** garantir que ele receba o tratamento necessário.

---

### Petshop

#### 16. Venda de Ração para Pássaros
**Como** cliente,  
**Quero** comprar ração para pássaros da espécie gralha,  
**Para** alimentar adequadamente meu pássaro.

#### 17. Venda de Sal para Boi
**Como** cliente,  
**Quero** comprar sal para boi,  
**Para** suplementar a alimentação dos meus animais.

#### 18. Venda de Vacina para Animais Adultos
**Como** cliente,  
**Quero** comprar vacina para animais com mais de 7 anos,  
**Para** garantir a saúde dos meus pets.

#### 19. Banho e Tosa para Animais de Fazenda
**Como** cliente,  
**Quero** que meu animal de fazenda receba banho e tosa,  
**Para** garantir que ele esteja limpo e bem cuidado.

#### 20. Vacina para Animais com Raiva
**Como** cliente,  
**Quero** vacinar meus animais contra raiva,  
**Para** protegê-los de doenças.

#### 21. Limpeza de Pata de Camelo
**Como** cliente,  
**Quero** serviços de limpeza de pata de camelo,  
**Para** cuidar da higiene do meu camelo.

#### 22. Banho em Gansos da Finlândia
**Como** cliente,  
**Quero** dar banho em meus gansos da Finlândia,  
**Para** mantê-los limpos e saudáveis.

#### 23. Ajuda na Domesticação
**Como** cliente,  
**Quero** ajuda na domesticação do meu animal,  
**Para** melhorar seu comportamento e convivência.

#### 24. Preenchimento de Caderneta de Vacinação
**Como** cliente,  
**Quero** que o petshop preencha a caderneta de vacinação do meu animal,  
**Para** manter o controle das vacinas aplicadas.

#### 25. Design na Penugem
**Como** cliente,  
**Quero** que o petshop faça design na penugem do meu animal,  
**Para** deixá-lo com uma aparência única e estilosa.

#### 26. Pagamento com Saco de Algodão
**Como** cliente,  
**Quero** pagar com saco de algodão,  
**Para** usar um meio alternativo de pagamento aceito pela loja.

#### 27. Pagamento com Galinhas Vivas
**Como** cliente,  
**Quero** pagar com galinhas vivas,  
**Para** trocar produtos ou serviços do petshop por um meio de pagamento aceito.


---
# 7. Diagrama de componentes

---
# 8. Diagrama de Implantação

---
# 9. Protótipo de telas

## 9.1 Tela de Cadastro de Agenda

### 9.1.1 Relatório de Agenda

![agenda](Telas_prototipo/1.jpeg)

### 9.1.2 Detalhe de Agenda

![agenda](https://github.com/4Elber/Elber_Alves/blob/main/2.jpeg)

### 9.1.3 Registro de Agenda

![agenda](https://github.com/4Elber/Elber_Alves/blob/main/3.jpeg)

## 9.2 Tela de Cadastro de Animal

### 9.2.1 Relatório de Animal

![animal](https://github.com/4Elber/Elber_Alves/blob/main/4.jpeg)

### 9.2.2 Registro de Animal

![animal](https://github.com/4Elber/Elber_Alves/blob/main/5.jpeg)

### 9.2.3 Detalhes de Animal

![animal](https://github.com/4Elber/Elber_Alves/blob/main/6.jpeg)

## 9.3 Tela de Cadastro de Atendente

### 9.3.1 Relatório de Atendente

![atendente](https://github.com/4Elber/Elber_Alves/blob/main/7.jpeg)

### 9.3.2 Registro de Atendente

![atendente]https://github.com/4Elber/Elber_Alves/blob/main/(8.jpeg)

### 9.3.3 Detalhes de Atendente

![atendente]https://github.com/4Elber/Elber_Alves/blob/main/(9.jpeg)

## 9.4 Tela de Cadastro de Atendimento

### 9.4.1 Relatório de Atendimento

![atendimento](https://github.com/4Elber/Elber_Alves/blob/main/10.jpeg)

### 9.4.2 Registro de Atendimento

![atendimento](https://github.com/4Elber/Elber_Alves/blob/main/11.jpeg)

### 9.4.3 Detalhes de Atendimento

![atendimento](https://github.com/4Elber/Elber_Alves/blob/main/12.jpeg)

## 9.5 Tela de Cadastro de Cliente

### 9.5.1 Relatório de Cliente

![cliente](https://github.com/4Elber/Elber_Alves/blob/main/13.jpeg)

### 9.5.2 Detalhe de Cliente

![cliente](https://github.com/4Elber/Elber_Alves/blob/main/14.jpeg)

### 9.5.3 Registro de Cliente

![cliente](https://github.com/4Elber/Elber_Alves/blob/main/15.jpeg)

## 9.6 Tela de Cadastro de Pagamento

### 9.6.1 Relatório de Pagamento

![pagamento](https://github.com/4Elber/Elber_Alves/blob/main/16.jpeg)

### 9.6.2 Detalhes de Pagamento

![pagamento](https://github.com/4Elber/Elber_Alves/blob/main/17.jpeg)

### 9.6.3 Registro de Pagamento

![pagamento](https://github.com/4Elber/Elber_Alves/blob/main/18.jpeg)

## 9.7 Tela de Cadastro de Petshop

### 9.7.1 Relatório de Petshop

![petshop](https://github.com/4Elber/Elber_Alves/blob/main/19.jpeg)

### 9.7.2 Registro de Petshop

![petshop](https://github.com/4Elber/Elber_Alves/blob/main/20.jpeg)

### 9.7.3 Detalhes de Petshop

![petshop](https://github.com/4Elber/Elber_Alves/blob/main/21.jpeg)

## 9.8 Tela de Cadastro de Petshop_Produtos

### 9.8.1 Relatório de Petshop_Produtos

![pet_produtos](https://github.com/4Elber/Elber_Alves/blob/main/22.jpeg)

### 9.8.2 Detalhes de Petshop_Produtos

![pet_produtos](https://github.com/4Elber/Elber_Alves/blob/main/23.jpeg)

### 9.8.3 Registro de Petshop_Produtos

![pet_produtos](https://github.com/4Elber/Elber_Alves/blob/main/24.jpeg)

## 9.9 Tela de Cadastro de Petshop_Serviços

### 9.9.1 Relatório de Petshop_Serviços

![pet_serv](https://github.com/4Elber/Elber_Alves/blob/main/25.jpeg)

### 9.9.2 Detalhes de Petshop_Serviços

![pet_serv](https://github.com/4Elber/Elber_Alves/blob/main/26.jpeg)

### 9.9.3 Registro de Petshop_Serviços

![pet_serv](https://github.com/4Elber/Elber_Alves/blob/main/27.jpeg)

## 9.10 Tela de Cadastro de Produtos

### 9.10.1 Relatório de Produtos

![produtos](https://github.com/4Elber/Elber_Alves/blob/main/28.jpeg)

### 9.10.2 Detalhes de Produtos

![produtos](https://github.com/4Elber/Elber_Alves/blob/main/29.jpeg)

### 9.10.3 Registro de Produtos

![produtos](https://github.com/4Elber/Elber_Alves/blob/main/30.jpeg)

## 9.11 Tela de Cadastro de Prontuário

### 9.11.1 Relatório de Prontuário

![prontuario](https://github.com/4Elber/Elber_Alves/blob/main/31.jpeg)

### 9.11.2 Detalhes de Prontuário

![prontuario](https://github.com/4Elber/Elber_Alves/blob/main/32.jpeg)

### 9.11.3 Registro de Prontuário

![prontuario](https://github.com/4Elber/Elber_Alves/blob/main/33.jpeg)

## 9.12 Tela de Cadastro de Receita

### 9.12.1 Relatório de Receita

![receita](https://github.com/4Elber/Elber_Alves/blob/main/34.jpeg)

### 9.12.2 Detalhes de Receita

![receita](https://github.com/4Elber/Elber_Alves/blob/main/35.jpeg)

### 9.12.3 Registro de Receita

![receita](https://github.com/4Elber/Elber_Alves/blob/main/36.jpeg)

## 9.13 Tela de Cadastro de Serviços

### 9.13.1 Relatório de Serviços

![servicos](https://github.com/4Elber/Elber_Alves/blob/main/37.jpeg)

### 9.13.2 Detalhes de Serviços

![servicos](https://github.com/4Elber/Elber_Alves/blob/main/38.jpeg)

### 9.13.3 Registro de Serviços

![servicos](https://github.com/4Elber/Elber_Alves/blob/main/39.jpeg)

## 9.14 Tela de Cadastro de Veterinário

### 9.14.1 Relatório de Veterinário

![veterinario](https://github.com/4Elber/Elber_Alves/blob/main/40.jpeg)

### 9.14.2 Detalhes de Veterinário

![veterinario](https://github.com/4Elber/Elber_Alves/blob/main/41.jpeg)

### 9.14.3 Registro de Veterinário

![veterinario](https://github.com/4Elber/Elber_Alves/blob/main/42.jpeg)

## 9.15 Tela de Gráfico

### 9.15.1 Gráfico em Pizza

![graficos](https://github.com/4Elber/Elber_Alves/blob/main/43.jpeg)

### 9.15.2 Gráfico em Barra

![graficos](https://github.com/4Elber/Elber_Alves/blob/main/44.jpeg)

## 9.16 Tela de Dashboard

![dashboard](https://github.com/4Elber/Elber_Alves/blob/main/45.jpeg)

---
# 10 Diagrama de navegação

---
# 11. Pilha tecnológica

---
# 12. Requisitos de sistemas

---
# 13. Considerações sobre segurança

---
# 14. Manutenção e instalação

---
# 15. Glossário

---
# 16. Script SQL
## 16.1 Comandos create

```
-- Criação da tabela CLIENTE
CREATE TABLE Cliente (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    telefone VARCHAR(15) NOT NULL
);

-- Criação da tabela ANIMAL
CREATE TABLE Animal (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    especie ENUM('gato', 'cachorro') NOT NULL,
    condicao TEXT NOT NULL,
    tipo_racao VARCHAR(100),
    habitos TEXT,
    cliente_id INT,
    FOREIGN KEY (cliente_id) REFERENCES Cliente(id)
);

-- Criação da tabela VETERINARIO
CREATE TABLE Veterinario (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    especialidade VARCHAR(100)
);

-- Criação da tabela ATENDENTE
CREATE TABLE Atendente (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL
);

-- Criação da tabela AGENDA
CREATE TABLE Agenda (
    id INT AUTO_INCREMENT PRIMARY KEY,
    data DATE NOT NULL,
    hora TIME NOT NULL,
    veterinario_id INT,
    FOREIGN KEY (veterinario_id) REFERENCES Veterinario(id)
);

-- Criação da tabela ATENDIMENTO
CREATE TABLE Atendimento (
    id INT AUTO_INCREMENT PRIMARY KEY,
    data DATE NOT NULL,
    hora TIME NOT NULL,
    status ENUM('Em andamento', 'Concluído') NOT NULL,
    cliente_id INT,
    animal_id INT,
    atendente_id INT,
    agenda_id INT,
    FOREIGN KEY (cliente_id) REFERENCES Cliente(id),
    FOREIGN KEY (animal_id) REFERENCES Animal(id),
    FOREIGN KEY (atendente_id) REFERENCES Atendente(id),
    FOREIGN KEY (agenda_id) REFERENCES Agenda(id)
);

-- Criação da tabela PRONTUARIO
CREATE TABLE Prontuario (
    id INT AUTO_INCREMENT PRIMARY KEY,
    observacoes TEXT NOT NULL,
    animal_id INT,
    atendimento_id INT,
    FOREIGN KEY (animal_id) REFERENCES Animal(id),
    FOREIGN KEY (atendimento_id) REFERENCES Atendimento(id)
);

-- Criação da tabela RECEITA
CREATE TABLE Receita (
    id INT AUTO_INCREMENT PRIMARY KEY,
    descricao TEXT NOT NULL,
    medicamentos TEXT,
    prontuario_id INT,
    FOREIGN KEY (prontuario_id) REFERENCES Prontuario(id)
);

-- Criação da tabela PETSHOP
CREATE TABLE Petshop (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL
);

-- Criação da tabela PRODUTO
CREATE TABLE Produto (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    tipo VARCHAR(50) NOT NULL
);

-- Criação da tabela SERVICO
CREATE TABLE Servico (
    id INT AUTO_INCREMENT PRIMARY KEY,
    descricao TEXT NOT NULL
);

-- Criação da tabela PETSHOP_SERVICO
CREATE TABLE Petshop_Servico (
    petshop_id INT,
    servico_id INT,
    PRIMARY KEY (petshop_id, servico_id),
    FOREIGN KEY (petshop_id) REFERENCES Petshop(id),
    FOREIGN KEY (servico_id) REFERENCES Servico(id)
);

-- Criação da tabela PETSHOP_PRODUTO
CREATE TABLE Petshop_Produto (
    petshop_id INT,
    produto_id INT,
    PRIMARY KEY (petshop_id, produto_id),
    FOREIGN KEY (petshop_id) REFERENCES Petshop(id),
    FOREIGN KEY (produto_id) REFERENCES Produto(id)
);

-- Criação da tabela PAGAMENTO
CREATE TABLE Pagamento (
    id INT AUTO_INCREMENT PRIMARY KEY,
    forma_pagamento ENUM('dinheiro', 'cartão', 'galinhas vivas', 'saco de algodão') NOT NULL,
    cliente_id INT,
    FOREIGN KEY (cliente_id) REFERENCES Cliente(id)
);

-- Inserção dos dados dos produtos do petshop
INSERT INTO Produto (nome, tipo) VALUES 
('Ração para pássaros da espécie gralha', 'ração'),
('Sal para boi', 'sal'),
('Vacina para animais adultos acima de 7 anos', 'vacina');

-- Inserção dos dados dos serviços do petshop
INSERT INTO Servico (descricao) VALUES 
('Banho e tosa para animais de fazenda'),
('Vacina para animais com raiva'),
('Limpeza de pata de camelo'),
('Banho para gansos da Finlândia'),
('Auxílio na domesticação'),
('Preenchimento da caderneta de vacinação'),
('Designs na penugem');

-- Exemplo de ligação entre petshop e serviços/produtos
INSERT INTO Petshop (nome) VALUES ('Petshop AnimalCare');
INSERT INTO Petshop_Servico (petshop_id, servico_id) VALUES (1, 1), (1, 2), (1, 3);
INSERT INTO Petshop_Produto (petshop_id, produto_id) VALUES (1, 1), (1, 2), (1, 3);

```


## 16.2 Comandos INSERT gerando dados ficticios;
```SQL
-- Inserindo dados na tabela CLIENTE
INSERT INTO Cliente (nome, telefone) VALUES
('João Silva', '123456789'),
('Maria Oliveira', '987654321'),
('Carlos Pereira', '555555555'),
('Ana Souza', '444444444');

-- Inserindo dados na tabela ANIMAL
INSERT INTO Animal (nome, especie, condicao, tipo_racao, habitos, cliente_id) VALUES
('Rex', 'cachorro', 'Leve dor na pata', 'Ração Premium', 'Corre no parque todos os dias', 1),
('Luna', 'gato', 'Apatia e febre', 'Ração para gatos', 'Dorme o dia todo', 2),
('Max', 'cachorro', 'Problema respiratório', 'Ração natural', 'Brinca com outros cães', 3),
('Mimi', 'gato', 'Perda de apetite', 'Ração para gatos idosos', 'Costuma caçar ratos', 4);

-- Inserindo dados na tabela VETERINARIO
INSERT INTO Veterinario (nome, especialidade) VALUES
('Dr. Pedro Costa', 'Clínica geral'),
('Dra. Fernanda Lima', 'Dermatologia'),
('Dr. Ricardo Almeida', 'Cardiologia'),
('Dra. Laura Mendes', 'Neurologia');

-- Inserindo dados na tabela ATENDENTE
INSERT INTO Atendente (nome) VALUES
('Carla Santos'),
('Lucas Oliveira'),
('Mariana Silva'),
('Rafael Costa');

-- Inserindo dados na tabela AGENDA
INSERT INTO Agenda (data, hora, veterinario_id) VALUES
('2024-09-17', '10:00', 1),
('2024-09-17', '11:00', 2),
('2024-09-17', '14:00', 3),
('2024-09-18', '09:00', 4);

-- Inserindo dados na tabela ATENDIMENTO
INSERT INTO Atendimento (data, hora, status, cliente_id, animal_id, atendente_id, agenda_id) VALUES
('2024-09-17', '10:00', 'Concluído', 1, 1, 1, 1),
('2024-09-17', '11:00', 'Concluído', 2, 2, 2, 2),
('2024-09-17', '14:00', 'Em andamento', 3, 3, 3, 3),
('2024-09-18', '09:00', 'Agendado', 4, 4, 4, 4);

-- Inserindo dados na tabela PRONTUARIO
INSERT INTO Prontuario (observacoes, animal_id, atendimento_id) VALUES
('O animal apresenta leve inflamação na pata, recomendada fisioterapia.', 1, 1),
('Gato com febre, foi prescrito antibiótico.', 2, 2),
('Animal com dificuldade respiratória, diagnosticado com bronquite canina.', 3, 3);

-- Inserindo dados na tabela RECEITA
INSERT INTO Receita (descricao, medicamentos, prontuario_id) VALUES
('Fisioterapia semanal por 1 mês.', 'Anti-inflamatório 2x ao dia', 1),
('Antibiótico por 7 dias', 'Amoxicilina 50mg 2x ao dia', 2),
('Inalação diária por 2 semanas', 'Broncodilatador 3x ao dia', 3);

-- Inserindo dados na tabela PETSHOP
INSERT INTO Petshop (nome) VALUES
('Petshop AnimalCare');

-- Inserindo dados na tabela PRODUTO
INSERT INTO Produto (nome, tipo) VALUES
('Ração para pássaros da espécie gralha', 'ração'),
('Sal para boi', 'sal'),
('Vacina para animais adultos acima de 7 anos', 'vacina');

-- Inserindo dados na tabela SERVICO
INSERT INTO Servico (descricao) VALUES
('Banho e tosa para animais de fazenda'),
('Vacina para animais com raiva'),
('Limpeza de pata de camelo'),
('Banho para gansos da Finlândia'),
('Auxílio na domesticação'),
('Preenchimento da caderneta de vacinação'),
('Designs na penugem');

-- Inserindo dados na tabela PETSHOP_SERVICO
INSERT INTO Petshop_Servico (petshop_id, servico_id) VALUES
(1, 1), 
(1, 2), 
(1, 3), 
(1, 4), 
(1, 5), 
(1, 6), 
(1, 7);

-- Inserindo dados na tabela PETSHOP_PRODUTO
INSERT INTO Petshop_Produto (petshop_id, produto_id) VALUES
(1, 1), 
(1, 2), 
(1, 3);

-- Inserindo dados na tabela PAGAMENTO
INSERT INTO Pagamento (forma_pagamento, cliente_id) VALUES
('dinheiro', 1),
('cartão', 2),
('galinhas vivas', 3),
('saco de algodão', 4);
```
