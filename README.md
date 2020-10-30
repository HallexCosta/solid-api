<h1 align="center">
  API REST with S.O.L.I.D Principle
</h1>

<p align="center">
  Project Pattern <a href="https://www.youtube.com/watch?v=vAV4Vy4jfkc&t=2466s">Package by Feature</a>
</p>


# TRADUÇÃO PARA INGLÊS (Em breve)

# Entities:
> Camada responsável pelos models (modelo/formato) do banco de dados.
---------------------------------------------------------------------------------------------------------

# Providers
> Camada responsável por fazer comunicação com storages, serviços e API's externas.
## implementations:
> Camada responsável pela implementação da comunicação com storages, serviçoes e API's esternas.

---------------------------------------------------------------------------------------------------------  
# Repositories:
> Camada responsável pelo forma de comunicação com banco de dados.
## implementations:
> Camda responsável pela implementação da forma de comunicação com banco de dados...

---------------------------------------------------------------------------------------------------------
# useCases:
> Camada responsável pela regra de negócio do caso de uso, Ou seja, toda ação que o usuário pode fazer na nossa aplicação requer um novo caso de uso/feature
## CreateUserController:
> Responsável por receber as requisições (request), solicitadas ao backend.
## CreateUserDTO:
> Os DTOs é responsável pelo formato dos dados da requisição (request) ao backend.
## CreateUserUseCase:
> Responsavel pela lógica e as regra de negócio do caso de uso (useCase).
## CreateUserUseCase.spec:
> Responsável por fazer os teste no nosso caso de uso.
## index.ts
> Executa a lógica e regra de negócio do caso de uso (useCase).
