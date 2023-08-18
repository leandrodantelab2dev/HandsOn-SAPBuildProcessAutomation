# Exercicio 04 - Formulário de Aprovação

Neste Step realizaremos a crição do formulário de aprovação, no qual o gestor terá acesso aos dados da solicitação de forma expandida.

No fluxo do Process, depois do Decision, clique em mais, __Approvals__, __New Approval Form__.

![MDK](images/img1.png)

Darei o nome de:

```
frmVacationApproval
```

E clique em Create

![MDK](images/img2.png)

Como subject da solicitação, será feita a concatenação:

```
Vacation Approval - [NAME]
```

![MDK](images/img3.png)

E o usuário que irá receber a solicitação para aprovação, será o proprio requisitante, para podermos testar o end-to-end.

Em cenários de execução real, poderemos utilizar o email corporativo do gestor, para redirecionar a caixa do MyImbox cloud.

![MDK](images/img4.png)

Agora vamos editar visualmente, clique em __Edit Form__

![MDK](images/img5.png)

Adicione o Titulo H1

![MDK](images/img6.png)

Adicione 3 Inputs de Texto:
```
- Name
- Position
- Email
```

![MDK](images/img7.png)

Todos eles deixar com o flag de Read Only selecionado.

![MDK](images/img8.png)

Adicione 2 Inputs de Data para StartDate e EndDate.
E também marcar ReadOnly para ambos.

![MDK](images/img9.png)

Salve o Formulário.
 
![MDK](images/img10.png)

No Card de Approval Form, dentro do Process, Selecione a Tab __Inputs__

![MDK](images/img11.png)

Realize o preenchimento correto com base no Form de solicitação, conforme imagem abaixo.

![MDK](images/img12.png)

Agora com base na regra criada no Step anterior, configuraremos o tempo de duração daquela requisição.

Na Tab __General__, Altere os parametros de Due Date, com o DaysToApprove do nosso decision.

![MDK](images/img13.png)

Salve o processo! E formulário de configuração devidamente configurado!

![MDK](images/img14.png)

## Próximo Passo:
[Exercício 05 - Atualizar Tabela de Decisão](/exercises/ex5/README.md)