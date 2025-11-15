# estrutura-objetos-python
📘 Trabalho de Programação Orientada a Objetos em Python

Este repositório contém todas as implementações solicitadas no trabalho da disciplina de Programação Orientada a Objetos, incluindo código em Python, testes, justificativas e a versão em notebook (.ipynb).
Os exercícios abordam desde validação robusta de classes até concorrência com threads.

📂 Conteúdo do trabalho
✔️ 1. Classe Produto com validação

Validação rígida do código no formato XXX-YYYY.

Verificação de preço e quantidade.

Métodos vender() e repor() com tratamento de exceções.

Testes com cenários de sucesso e erro.

✔️ 2. Herança vs Composição

Implementação de Veiculo, GPS e CruiseControl usando:

Herança múltipla

Composição

Mini benchmark comparando desempenho das duas abordagens.

Justificativa técnica discutindo clareza, manutenção e problemas clássicos (ex: diamante da morte).

✔️ 3. Polimorfismo e Coleções Heterogêneas

Hierarquia Documento, Relatorio, NotaFiscal e Carta.

Cada classe implementa seu próprio render().

Função processar_documentos() usando duck typing.

Contagem automática de cada tipo de documento.

Testes que demonstram polimorfismo real.

✔️ 4. Funcionário, Gerente e Programador

Implementação de aumentar_salario() com valores padrão:

Funcionário: 5%

Gerente: 10%

Programador: 20%

Sobrescrita usando super() corretamente.

Testes mostrando comportamento polimórfico.

✔️ 5. Conta e ContaEspecial

Implementação de transferência com rollback manual em caso de erro.

Histórico de operações (timestamp, tipo, valor, saldo final).

Limite especial de até 3× o salário.

Teste concorrente com ThreadPoolExecutor simulando 1000 transferências simultâneas.

Verificação da consistência final dos saldos.

✔️ 6. Classe Vetor2D

Métodos especiais:

__str__

__eq__ (com tolerância 1e-9)

__add__

Método angle_with() que retorna o ângulo entre vetores.

Testes validando:

Comutatividade da soma

Igualdade aproximada

Ângulo entre um vetor e ele mesmo igual a 0°

🧪 Testes incluídos

O notebook contém:

Casos de teste extras criados manualmente.

Comparações entre abordagens.

Testes de borda (valores negativos, formatos inválidos, etc).

Execução do benchmark de herança vs composição.

Teste de consistência estrutural nas transferências paralelas.

🛠 Tecnologias e Ferramentas

Python 3

concurrent.futures

datetime

math

threading

Google Colab

Arquivo .py final exportado do notebook
