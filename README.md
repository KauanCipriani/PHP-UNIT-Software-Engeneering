# Projeto de Testes em PHP

Repositório criado para realizar testes e simulações com PHP, conforme solicitações do time de produção.
Ideal para validar hipóteses, testar integrações ou implementar protótipos rápidos. 🚀

# ⚙️ Tecnologias
PHP 8+

Servidor Apache ou Built-in (CLI)

Composer (opcional)

PHPUnit para testes unitários

# 🚀 Como rodar o projeto

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nome-do-repo.git

# Acesse a pasta
cd nome-do-repo

# Rode com o servidor embutido do PHP
php -S localhost:8000

# Execute os testes (se o PHPUnit estiver instalado globalmente)
phpunit tests/FuncoesTest.php
```

# ✅ Funcionalidades testadas
A classe Funcoes contém métodos utilitários que foram testados com PHPUnit:

ehPar($numero)
Verifica se um número é par.

fatorial($numero)
Calcula o fatorial de um número (lança exceção para negativos).

ehPalindromo($texto)
Verifica se uma string é um palíndromo (ignora espaços e maiúsculas/minúsculas).

fahrenheitParaCelsius($f)
Converte de Fahrenheit para Celsius.

calcularDesconto($preco, $porcentagem)
Aplica um desconto ao valor original (lança exceção para valores inválidos).

# 🧪 Resultados dos Testes
Os testes abrangem diversos cenários:

✅ Números pares e ímpares

✅ Fatoriais com entradas válidas e negativas (tratamento de exceções)

✅ Palíndromos com diferentes formatações

✅ Conversões de temperatura conhecidas

✅ Aplicação de descontos com tratamento de erros

# 🤔 Reflexão Final
    Os testes ajudaram a identificar comportamentos inesperados?
Sim! Foram essenciais para garantir que os métodos lidassem corretamente com entradas inválidas, como números negativos no fatorial ou desconto com valores negativos, disparando exceções apropriadas.

    Algum teste falhou? Por quê?
Nenhum teste falhou durante a execução atual, indicando que os métodos estão funcionando conforme o esperado. Mas se houver alterações no futuro, os testes vão apontar qualquer quebra no comportamento.

    Como os testes podem ajudar na evolução segura do código?
Ter uma suíte de testes bem escrita proporciona segurança ao refatorar ou adicionar novas funcionalidades. Se algo for quebrado acidentalmente, os testes vão alertar de imediato, prevenindo bugs em produção.

# 👨‍💻 Autores
Kauan Amélio Cipriani, Guilherme Depiné e Gabriel Morin Werner
