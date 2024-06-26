# Data Science

## Visão Geral

Este projeto analisa dados de influenciadores coletados de diversas plataformas, como Instagram, YouTube e TikTok. O projeto está organizado em três diretórios principais:

## Estrutura do Projeto

- **DataScrap**: Nesta etapa, os dados brutos são extraídos dos seguintes sites:
  - [Top Instagram](https://hypeauditor.com/pt/top-instagram/)
  - [Top YouTube](https://hypeauditor.com/pt/top-youtube/)
  - [Top TikTok](https://hypeauditor.com/pt/top-tiktok/)
  
- **DataAnalytics**: Aqui, os dados processados são analisados e visualizados. Passos importantes incluem:
  - Mapeamento dos IDs dos influenciadores para seus respectivos nichos.
  - Criação de gráficos para entender o engajamento e outras métricas.
  - Aplicação de métodos de clusterização, como os métodos Cotovelo e Silhueta, para extrair insights sobre nichos.

- **DataPopulateScripts**: Nesta etapa, scripts são criados para popular o banco de dados. Problemas de CRUD são resolvidos, e os dados são enviados para o banco de dados por meio de uma API, eliminando a necessidade de scripts SQL.

## Instalação

Para executar este projeto, siga estas etapas:

1. **Python 3.11.9**: Certifique-se de ter o Python 3.11.9 instalado. Você pode baixá-lo em [python.org](https://www.python.org/).

2. **Ambiente Virtual (venv)**: Crie um ambiente virtual para isolar as dependências do projeto:
   ```sh
   python -m venv myenv
   ```

3. **Ative o Ambiente Virtual**:
   - No Windows:
     ```sh
     myenv\Scripts\activate
     ```
   - No macOS e Linux:
     ```sh
     source myenv/bin/activate
     ```

4. **Instale as Dependências**: Instale as dependências necessárias usando:
   ```sh
   pip install -r requirements.txt
   ```

## Executando o Projeto

1. **DataScrap**: Dados brutos estao nessa pasta.
2. **Análise de Dados**: Analise os dados no diretório `DataAnalytics`.
3. **População do Banco de Dados**: Popule o banco de dados usando os scripts no diretório `DataPopulateScripts`.

## Instruções Adicionais

- Abra o arquivo `Storytelling_Influenciadores_Digitais` na pasta de **Análise de Dados** .
- Certifique-se de selecionar o kernel Python 3.11.9 para executar o notebook e ter as dependencias instaladas.

## Contato

Para mais informações ou dúvidas, entre em contato:

- **WhatsApp**: [24 99280-4547](https://wa.me/5524992804547)
- **Email**: [zuvanovm@gmail.com](mailto:zuvanovm@gmail.com)

Sinta-se à vontade para entrar em contato se tiver alguma dúvida ou precisar de mais assistência. 
