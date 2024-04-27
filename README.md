# workout_api
workout_api é uma API para gerenciar atletas, categorias e centros de treinamento.

## Instalação
Clone o repositório:
```bash
git clone https://github.com/seu-usuario/workout_api.git
```
Navegue até o diretório do projeto:
```bash
cd workout_api
```
Instale as dependências:
```bash
pip install -r requirements.txt
```
## Uso
### Executar o servidor
Para iniciar o servidor de desenvolvimento, execute o seguinte comando:

```bash
make run
```
Isso iniciará o servidor em http://localhost:8000/docs.

Iniciar PostgreSQL:
```bash
docker-compose up
```

Criar migrações
Para criar migrações com Alembic, use o seguinte comando:

```bash
make create-migrations d="sua_descricao"
```
Substitua sua_descricao pela descrição da migração.

## Executar migrações
Para aplicar as migrações ao banco de dados, execute:

```bash
make run-migrations
```
## Contribuição
Contribuições são bem-vindas! Se você quiser contribuir com este projeto, por favor, siga estas etapas:

1. Faça um fork do repositório
2. Crie um branch para a sua feature (git checkout -b feature/NomeDaFeature)
3. Faça commit das suas alterações (git commit -am 'Adiciona uma nova feature')
4. Faça push para o branch (git push origin feature/NomeDaFeature)
5. Crie um novo Pull Request

## Desenvolvimento
Este material foi desenvolvido como atividade de aprendizado com a plataforma DIO por [Nayanna](https://www.linkedin.com/in/nayannanara/).
   
### Licença
Este projeto está licenciado sob a MIT License.

Sinta-se à vontade para personalizar este README de acordo com as necessidades específicas do seu projeto, adicionando informações adicionais sobre a API, exemplos de uso, instruções de teste, entre outros.
