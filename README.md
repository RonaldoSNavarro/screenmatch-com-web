## 🔖 Sobre

## ScreenMatch Web

Este projeto foi desenvolvido para criar uma API REST que fornece dados a uma aplicação front-end. Durante o desenvolvimento, foram utilizadas várias tecnologias e técnicas para criar uma aplicação robusta e funcional.

## Tecnologias Utilizadas

- **Spring Boot**: Para facilitar a configuração e o desenvolvimento da aplicação.
- **TomCat**: Servidor local que permite fazer requisições às rotas implementadas na aplicação.
- **Anotações do Spring**: Como `@RestController`, `@RequestMapping`, `@GetMapping` e `@Service`, para mapear requisições e rotas, e para definir classes de serviço.

## Estrutura do Projeto

O projeto contém os seguintes pacotes e classes:

### Pacote `br.com.alura.screenmatch.config`

- **Classe `CorsConfiguration`**: Configura as políticas de CORS (Cross-Origin Resource Sharing) para permitir que a API seja acessada por diferentes origens.

### Pacote `br.com.alura.screenmatch.controller`

- **Classe `SerieController`**: Responsável por receber e gerenciar as requisições relacionadas a séries. Mapeia as rotas e define os endpoints da API.

### Pacote `br.com.alura.screenmatch.dto`

- **Classe `SerieDTO`**: Define a estrutura dos dados das séries que serão transferidos entre o cliente e o servidor.
- **Classe `EpisodioDTO`**: Define a estrutura dos dados dos episódios que serão transferidos entre o cliente e o servidor.

### Pacote `br.com.alura.screenmatch.model`

- **Classe `Categoria`**: Representa as categorias das séries.
- **Classe `DadosEpisodio`**: Contém dados detalhados de um episódio específico.
- **Classe `DadosSerie`**: Contém dados detalhados de uma série específica.
- **Classe `DadosTemporada`**: Contém dados detalhados de uma temporada específica.
- **Classe `Episodio`**: Representa um episódio de uma série.
- **Classe `Serie`**: Representa uma série.

### Pacote `br.com.alura.screenmatch.repository`

- **Classe `SerieRepository`**: Interface que estende `JpaRepository` e permite operações CRUD (Create, Read, Update, Delete) na entidade `Serie`.

### Pacote `br.com.alura.screenmatch.service`

- **Classe `ConsumoApi`**: Responsável por consumir APIs externas para obter dados adicionais, se necessário.
- **Classe `ConverteDados`**: Contém lógica para converter dados entre diferentes formatos.
- **Classe `IConverteDados`**: Interface que define métodos para conversão de dados.
- **Classe `SerieService`**: Contém a lógica de negócios relacionada a séries. Fornece dados ao `SerieController`.

### Classe `ScreenMatchApplication`

- **Classe `ScreenMatchApplication`**: Classe principal do Spring Boot que inicia a aplicação.

## Funcionalidades Implementadas

- **API REST**: Implementação de uma API RESTful para fornecer dados ao front-end.
- **Rotas e Endpoints**: Definição de rotas e endpoints para acessar dados de séries e episódios.
- **Filtragem por Categorias**: Funcionalidade para filtrar séries por categorias.
- **Página de Detalhes**: Exibição de dados detalhados de todas as temporadas e episódios de uma série.

Com todas essas funcionalidades, o projeto está pronto para ser utilizado e expandido conforme necessário.

# Desenvolvedor

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/134724019?v=4" width=115><br><sub>Ronaldo Navarro</sub>](https://github.com/ronaldosnavarro)
