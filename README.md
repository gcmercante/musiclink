# Musiclink Backend

## Requisitos funcionais
 - [ ] Deve ser possível criar um usuário
 - [ ] Deve ser possível realizar o login
 - [ ] 

## Requisitos Não funcionais
 - [ ] Todas as funcionalidades diponiveis na tela deverão ser intuitivas, de modo que o usuário consiga explora-las sem ajudar de terceiros
 - [ ] A app deve ser responsiva
 - [ ] Deve ser criado um token de autenticação no momento do login
 - [ ] Deve existir avisos informando que está faltando informações para o usuário criar a conta
 - [ ] A app deve ser desenvolvida pensando nos principios do SOLID para facilitar a manutenibilidade
 - [ ] Informação de email ou senha incorreto deve ser ambiguo, sem informar qual dos dois estão incorretos
 - [ ] Não deve ser possível acessar páginas que requerem um token de autenticação sem esse token

## Regras de negócio
### Criação de usuário
 - [ ] Deve ser validado o formato do email
 - [ ] Deve ser validado o tamanho e conteudo da senha
 - [ ] Deve ser selecionada uma data de nascimento válida
 - [ ] Não deve ser possível criar a conta com um email no formato inválido
 - [ ] Não deve ser possível criar uma conta com uma senha no formato inválido
 - [ ] Não deve ser possível criar uma conta com informações faltando
 - [ ] Não deve ser possível criar uma conta com um email já sendo utilizado

### Login
 - [ ] Deve ser possível realizar o login com o usuário criado
 - [ ] Não deve ser possível realizar o login com um email incorreto
 - [ ] Não deve ser possível realizar o login com uma senha incorreta

