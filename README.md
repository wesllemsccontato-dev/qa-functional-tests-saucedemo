#  Projeto de Testes Funcionais - SauceDemo

##  Objetivo
Validar a funcionalidade de login da aplicação SauceDemo, garantindo que o sistema autentique corretamente os usuários e trate erros adequadamente.

##  Sistema testado
https://www.saucedemo.com/

##  Tipos de testes realizados
- Testes Funcionais
- Testes Negativos
- Testes de Usabilidade
- Testes de Segurança (básico)
- Testes Exploratórios

##  Casos de Teste
Foram criados 13 casos de teste cobrindo:
- Login válido
- Login inválido
- Campos vazios
- Comportamentos inesperados

Arquivo: `test-cases.xlsx`

## Bugs encontrados

### BUG001 - Sessão não persistida após refresh
- Usuário perde login ao atualizar página
- Severidade: Média

### BUG002 - Ausência de bloqueio após múltiplas tentativas
- Sistema não limita tentativas de login
- Severidade: Alta

## Teste Exploratório
Durante os testes foram identificados:
- Comportamento inconsistente ao atualizar página
- Falta de política de segurança clara

Arquivo: `exploratory-testing.md`

##  Ferramentas utilizadas
- Google Sheets
- Navegador Chrome (aba anônima)
- GitHub

##  Conclusão
O sistema apresenta funcionamento básico correto, porém possui pontos de melhoria em segurança e gerenciamento de sessão.

