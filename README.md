# WorkoutAPI
Desafio de código do DIO.me.

Instruções:
 
- Adicionar **query parameters** nos endpoints
      - atleta
            - nome
            - cpf
- Personalizar a resposta de retorno de endpoints
      - get all
            - atleta
                  - nome
                  - centro_treinamento
                  - categoria
- Manipular a exceção de integridade dos dados em cada módulo/tabela
      - sqlalchemy.exc.IntegrityError e devolver a seguinte mensagem: “Já existe um atleta cadastrado com o cpf: x”
      - status_code: 303
- Adicionar paginação utilizando a lib: fastapi-pagination
      - limit e offset
