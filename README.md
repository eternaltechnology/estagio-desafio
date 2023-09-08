# Desafio estágio

Você terá 10 dias para fazer esse desafio, até 17/9/2023 (10 dias), inicie fazendo um FORK/CLONE, mude seu repositório para PRIVADO, e inicie seu desafio, quando acabar, marcaremos as proximas etapas...

Vou aumentar em 1 dia a entrega devido a algumas pessoas nao terem recebido as mensagens no whats
Entrega ate dia 18/10/2023

## Contexto simplificado

Nesse desafio você construirá um sistema simplificado de gerenciamento de compras e vendas de produtos, tambem devera existir um financeiro que será resposavel para visualizar/armazenar as entradas(COMPRAS) e saidas(VENDAS) de novos produtos.
O sistema deve conter um LOGIN usando JWT e possibilitar aos usuario criarem contas.

## Avaliação

A avaliação será baseada na sua capacidade de escrever um código simples, de fácil manutenção, e pela quantidade de funcionalidades que você entregar.

1. ### Stack obrigatoria

- Front: React + Axios
- Back: Nestjs
- Banco: Escolha oque você quiser, recomendamos Mongo db!
  
A não apresentação e/ou não entrega caracteriza a eliminação do candidato.
Entrega parcial serão aceitas, mas o objetivo eh que os requisitos obrigatórios sejam
cumpridos

# Back-end Requisitos

1. Um CRUD Basico de Usuários:
   - criar usuário
     - utilize bcrypt para transformar a senha em hash
   - atualizar usuário.
      - Apenas o dono da conta poderá atualizar a sua conta.
   - listar varios usuarios.
     - (Opcional) Caso queria implemente um search
   - listar todos usuários
   - deletar usuario.
     - Apenas o dono da conta poderá deletar a sua conta.
       
2. Sistema de login com JWT.
   - [Crie um guard para proteger sua aplicação](https://docs.nestjs.com/guards).
3. Um CRUD de produtos
   - criar produtos.
     - o preço dos produtos não deve cadastrado abaixo de zero.
   - atualizar produtos.
   - listar varios produtos.
     - (Opcional) Caso queria implemente um search
   - listar um produto
   - atualizar produtos.
   - deletar produtos.
        -SOFT DELETE
   - todos os produtos devem ser possiveis ser vendidos.
4. Financeiro
   - registre a vendas e compras no financeiro.


# Front-end Requisitos

Criar um sistema que permita aos usuarios terem acesso ao sistema

Requisitos Obrigatórios

1. Sistema de Login
   - Login com token JWT
   - Registrar
   - Permissionamento(Opcional)
   - Use ContextAPI para armazenar as informações do usuário
2. Design da aplicação
   - Em relação ao UIUX, fique á vontade para fazer do jeito que preferir mas que seja claro e intuitivo.
   - Utilize MaterialUI
3. Tela para produtos
   - Usuário deve poder criar, editar, deletar e listar todos os produtos fornecidos do backend
4. Tela para financeiro
5. Tela para criar novo usuário
6. Tela para login
7. Tela de controle de usuarios.

# Diferencial.

Implementação de testes.
Criar figma para UI/UX

# IMPORTANTE

Caso tenha dúvidas ou problemas com o projeto, PERGUNTE NO NOSSO DISCORD.
