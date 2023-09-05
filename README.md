# Desafio estagio

você terá uma semana para fazer esse desafio, isso a contagem se inicia quando você ganhar acesso ao repositorio, após ter acesso de fork nesse repositorio e faça-o, quando acabar envie para o leandro no discord.

## Contexto simplificado

Nesse desafio você construirá uma versão de compras e vendas de produtos, tambem devera existir um financeiro que será resposavel para visualizar/armazenar as entradas e saidas de valores.

## Avaliação

A avaliação será baseada na sua capacidade de escrever um código simples, de fácil manutenção, e pela quantidade de funcionalidades que você entregar.

1. ### Stack obrigatoria

- Front: React + Axios
- Back: Nestjs
- Banco: Escolha oque você quiser, recomendamos Mongo db!

- Deploy completo obrigatório.
- Deploy sugerido(free)(OPCIONAL): Netlify, Google Cloud Run, Atlas

presentação e/ou não entrega caracteriza a eliminação do candidato.
Entrega parcial serão aceitas, mas o objetivo eh que os requisitos obrigatórios sejam
cumpridos

# Back-end Requisitos

O seu desafio deverá isso.

1. Um CRUD Basico de Usuarios:
   - criar usuario
     - utilize bcrypt para transformar a senha em hash
   - atualizar usuario
   - listar varios usuarios.
     - (Opcional) Caso queria implemente um search
   - listar um usuario
   - atualizar um usuario.
     - Apenas o dono da conta poderá atualizar a sua conta.
   - deletar usuario.
     - Apenas o dono da conta poderá atualizar a sua conta.
2. Sistema de login com JWT.
   - [Crie um guard para proteger sua aplicação](https://docs.nestjs.com/guards).
3. Um CRUD de produtos
   - criar produtos.
     - o preço do produto não deve cadastrado abaixo de zero.
   - atualizar produtos.
   - listar varios produtos.
     - (Opcional) Caso queria implemente um search
   - listar um produtos
   - atualizar um produtos.
     - Apenas o dono da conta poderá atualizar a sua conta.
   - deletar produtos.
     - Apenas o dono da conta poderá atualizar o produto.
   - todos os produtos devem ser possiveis ser vendidos.
   - ao acontecer uma venda faça o registro dela na fatura, caso o status da venda seja aprovada faça a referencia da fatura para o financeiro.
4. (Opcional) Fatura.
   - a fatura fica antes do financeiro, ou seja caso o produto seja vendido mas o status dele seja diferente de aprovado ele será registrado apenas na fatura.
   - tente evitar dizimas periodicas no banco, exemplo, caso o produto seja 100 reais e o usuario que estiver comprando escolha um parcelamento de 3 vezes, o produto ficara com um valor de 99 reais apos o parcelamento.
5. Financeiro
   - registre a venda no financeiro.
   - (Opcional faça isso caso você faça a perte da fatura) O registro no financeiro deve existir somente quando a compra estiver com status aprovado.

#### Diferencial.

Implementação de testes.

# Front-end Requisitos

Criar um sistema que permita um gerente ter acesso a vendas de produtos do seu estabelecimento.

Requisitos Obrigatórios

1. Sistema de Login
   - Login com token JWT
   - Registrar
   - Permissionamento(Opcional)
   - Se possível, use ContextAPI para armazenar as informações do usuário
2. Design da aplicação
   - Em relação ao design, fique a vontade para fazer do jeito que preferi mas que seja claro e intuitivo.
   - Utilize MaterialUI
3. Tela para produtos
   - Usuário deve poder criar, editar, deletar e listar todos os produtos fornecidos do backend
4. Tela para financeiro

# IMPORTANTE

Caso tenha duvidas ou problemas com o projeto, NÃO EXITE EM TIRA-LAS NO NOSSO DISCORD.
