# Exercicio 03 - Tabela de Decisão 

Neste Step criaremos uma tabela de decisão com base nos dados inputados no formulário criado no passo anterior.

A regra será a seguinte:

> Para do solicitações com o Cargo __TI__, serão 10 dias para aprovação.
> Para do solicitações com o Cargo __Admin__, serão 5 dias para aprovação.

Assim balizando a agilidade e urgência para o time de aprovação.

Depois da caixa de Trigger, selecione o botão mais, __Decision__, __New Decision__

![MDK](images/img1.png)

Darei o nome da minha Decision de:

```
dcsPositionVerification
```

![MDK](images/img2.png)

Clique em Edit Decision

![MDK](images/img3.png)

Vamo começar com os Inputs, clique em __Add Input Parameter__

![MDK](images/img4.png)

Preencha os parametros de position.

![MDK](images/img5.png)

Adicione o Output Parameter, clicando em __Add Output Parameter__

![MDK](images/img6.png)

Preencha os parametros conforme à seguir para correto output dos dados de DaysToApprove

![MDK](images/img7.png)

Com os dados de entrada e saida mapeados, podemos criar nossa regra, clique em __Add Rule__

![MDK](images/img8.png)

Nesse processo criaremos a tabela de regra, nomeada como:

```
tablePosition
```

Clique em Next Step

![MDK](images/img9.png)

Na condition coloque Position

![MDK](images/img10.png)

E no results coloque DaysToApprove

![MDK](images/img11.png)

Finalize o processo de parametrização da tabela de regra

![MDK](images/img12.png)

Agora com a tabela criada, podemos criar as regras efetivamente através de algarismos lógicos.

Com base na nossa regra de negócio, foi criada a seguinte tabela:

| Position | DaysToApprove |
|----------|---------------|
| ='TI'    | 10            |
| ='Admin' | 5             |

Salve sua Tabela

![MDK](images/img13.png)

E também Salve o seu Process

![MDK](images/img14.png)

## Próximo Passo:
[Exercício 04 - Formulário de Aprovação](/exercises/ex4/README.md)