# Docker

Docker é uma plataforma de código aberto que automatiza a implantação de aplicações dentro de contêineres de software. Os contêineres são unidades leves e portáteis que incluem tudo o que a aplicação precisa para ser executada: código, runtime, bibliotecas e configurações do sistema.

## Vantagens do Docker

- **Portabilidade:** Os contêineres podem ser executados em qualquer sistema que suporte Docker.
- **Isolamento:** Cada contêiner tem seu próprio ambiente, isolado dos demais.
- **Eficiência:** Os contêineres compartilham o kernel do sistema operacional, permitindo um uso mais eficiente dos recursos.
- **Facilidade de Uso:** Docker fornece ferramentas para criar, distribuir e executar contêineres de maneira fácil e rápida.

## Principais Comandos do Docker

### `docker run`

Cria e executa um novo contêiner.

```bash
docker run [opções] imagem [comando]
