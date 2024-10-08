# Projeto 01 IMC - Aplicativo Móvel

## FECAP - Ciência da Computação - 2024/2

### Programação de Dispositivos Móveis
### Professor: Vinícius Heltaí

---

## Descrição do Projeto

Este é o primeiro projeto de programação de dispositivos móveis para a disciplina de Programação de Dispositivos Móveis, lecionada pelo Prof. Vinícius Heltaí. O objetivo principal deste projeto é aprimorar um aplicativo de cálculo do Índice de Massa Corporal (IMC) que foi iunbiciado com todos juntos em sala de aula, mas aprimorando em grupo como desfio do projeto. A aplicação atual será modificada para fornecer classificações de IMC e validar as informações inseridas pelo usuário.

## Requisitos do Projeto

- **Classificação do IMC de acordo com a internet**:
  - IMC < 18,5 kg/m²: Baixo peso.
  - IMC entre 18,5 e 24,9 kg/m²: Peso normal.
  - IMC entre 25 e 29,9 kg/m²: Sobrepeso.
  - IMC entre 30 e 34,9 kg/m²: Obesidade grau 1.
  - IMC entre 35 e 39,9 kg/m²: Obesidade grau 2.
  - IMC > 40 kg/m²: Obesidade extrema.

- **Validação das Informações**:
  - Caso o usuário insira valores incorretos, o aplicativo deverá exibir:
    - `"resultado1" -> ERRO`
    - `"resultado2" -> ENTRADA NÃO VÁLIDA`

## Equipe

- **Membro 1**: Aleff Souza - 23025514
- **Membro 2**: Matheus Zimmer - 23025264
- **Membro 3**: Claudio Endo - 23025546
- **Membro 4**: Luiz Felipe Sparrapan - 23025521

## Estrutura do Repositório

- `app/`: Diretório contendo o código-fonte do aplicativo.
- `gradle/`: Diretório contendo scripts de configuração do Gradle.
- `build.gradle`: Arquivo de configuração do projeto.
- `settings.gradle`: Arquivo de configuração do Gradle para o projeto.
- `gradlew`: Script para executar o Gradle no Linux/Mac.
- `gradlew.bat`: Script para executar o Gradle no Windows.
- `README.md`: Arquivo README do projeto.
- `.gitignore`: Arquivo que define os arquivos que não devem ser versionados pelo Git.
- `.idea/`: Diretório do IntelliJ IDEA.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/AleffSSouza/Projeto01-PDM-imc.git
   
*Como Executar o Projeto
**Clone o repositório:

bash
Copiar código
git clone https://github.com/AleffSSouza/Projeto01-PDM-imc.git
Navegue até o diretório do projeto:

bash
Copiar código
cd nome_do_repositorio
Construa e execute o aplicativo:

Importe o projeto para o Android Studio.
Construa o aplicativo e execute-o em um dispositivo Android ou emulador.
