# instalando-php-windows10
guia de como instalar o php globalmente no windowns 10 

# Instalação do PHP no Windows 10

Este guia fornece instruções detalhadas sobre como instalar o PHP globalmente no Windows 10 e configurar as variáveis de ambiente.

## Passo 1: Download do PHP
Baixe o Arquivo zip contido nesse repositório 
<br>
**ou**
<br>
Baixe a versão mais recente do PHP para Windows no [site oficial do PHP](https://windows.php.net/download/). 

Extraia o arquivo baixado para um diretório de sua escolha. Por exemplo, `C:\PHP`.

## Passo 3: Configuração das Variáveis de Ambiente

1. Clique com o botão direito em "Este PC" e selecione "Propriedades".
2. Clique em "Configurações avançadas do sistema".
3. Clique em "Variáveis de Ambiente".
4. Em "Variáveis do Sistema", clique em "Novo" para adicionar uma nova variável.

   - **Nome da Variável:** `PHP_HOME`
   - **Valor da Variável:** O caminho completo para o diretório onde o PHP foi extraído (por exemplo, `C:\PHP`).

5. Selecione a variável `Path` em "Variáveis do Sistema" e clique em "Editar".
6. Clique em "Novo" e adicione o caminho para a pasta `bin` dentro do diretório PHP (por exemplo, `C:\PHP\bin`).

## Passo 4: Verificação da Instalação

Abra o Prompt de Comando e digite:

```bash
php -v
