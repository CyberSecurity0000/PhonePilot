# Bot_Telefone

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## ⚠️ AVISO IMPORTANTE: Propósito Educacional

**Este software foi desenvolvido exclusivamente para fins de estudo, laboratório (lab) e revisão acadêmica em um ambiente seguro e controlado. O uso desta ferramenta para atividades ilícitas, invasão de sistemas ou qualquer propósito malicioso é estritamente proibido e de total responsabilidade do usuário.**

## Descrição

O **Bot_Telefone** é um projeto desenvolvido em Python com o objetivo de extrair números de telefone de anúncios classificados no site [django-anuncios.solyd.com.br](https://django-anuncios.solyd.com.br/). Utilizando as bibliotecas `requests`, `BeautifulSoup` e `threading`, o bot realiza requisições HTTP, analisa o conteúdo HTML das páginas e coleta os números de telefone presentes nos anúncios.

## Funcionalidades

- **Extração de Números de Telefone**: Coleta números de telefone de anúncios classificados no site especificado.
- **Processamento Paralelo**: Utiliza múltiplas threads para acelerar o processo de extração.
- **Armazenamento de Dados**: Salva os números de telefone encontrados em um arquivo CSV para posterior análise.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **requests**: Para realizar requisições HTTP ao site alvo.
- **BeautifulSoup**: Para parsing e extração de dados HTML.
- **threading**: Para implementar processamento paralelo e otimizar a extração de dados.

## Estrutura do Repositório


## Instalação

1. **Clone o Repositório**:

   ```bash
   git clone https://github.com/LightProgrammer000/Bot_Telefone.git
   cd Bot_Telefone
