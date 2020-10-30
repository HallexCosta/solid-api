<h1 align="center">
  API REST with S.O.L.I.D Principle
</h1>

<p aling="center">
  Project Pattern: <a href="https://www.youtube.com/watch?v=vAV4Vy4jfkc&t=2466s">Package by Feature</a>
</p>


# TRADUZIR PARA INGLÊS

# entities:
  **Armazena o models(modelo) do banco de dados.**

# providers:
  **Responsável por fazer comunicação com storages, serviços e APIs externas.** 
  ## implementations:
  **Onde ficará toda a implementação para a comunicação de com os storages, serviços ou APIs externas.**
  
# repositories:
  **Responsável pelo formato do banco de dados...**
  ## implementations:
  **Responsável pela implementação do formato do banco de dados...**

# useCases:
  **Responsável pela regra de negócio da aplicação<br />**
  **Ou seja, toda ação que o usuário pode fazer na nossa aplicação**
  ## CreateUserController:
  **Responsável por receber as requisições (request), solicitadas ao backend**
  ## CreateUserDTO:
  **Os DTOs é o formato da requisição (request).**
  ## CreateUserUseCase:
  **Executa a logica e as regra de negócio do caso de uso (useCase)**
  ## CreateUserUseCase.spec:
  **Responsável por fazer os teste nossa lógica e regra de negócio**
  ## index.ts
  **Lida com toda a lógica e regra de negócio do caso de uso (useCase) e a executa.**
