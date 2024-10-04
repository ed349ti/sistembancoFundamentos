# sistembancoFundamentos
Sistema de banco com a utilização de todos os fundamento do modulo.
o programa cria funçoes para as operaçoes existentes: sacar, depositar e visualizar historico. 
precisamos criar usuario (cliente do banco ) e criar contat corrente (vincular com usuario)criar funçoes para todas as operaçoes do sistema. 
cada função terá uma regra na passagem de argumentos. a função saque, recebe argumentos keyword only, sugestao de argumentos: saldo , valor, extrato, limite, numero _saques, limite_saques. 
sugestao de retorno: saldo e extrato. 
Função deposito recebe argumentos por (positional only). 
sugestao de argumento: saldo, valor, extrato. 
Sugestao de retorno: saldo e extrato. 
função extrato recebe argumentos por (positional only e keyword only).argumentos posicionais: saldo, argumentos nomeados: extrato. 
criar duas funçoes: criar usuario, criar conta corrente e listat contas. 
cadastro do usuario deve ter : nome, data de nascimento, cpf, endereço. deve ser armazenado somente os numeros de cpf, nao podemos cadastrar 2 usuarios com o mesmo cpf . 
conta corrente, deve armazenar contas em uma lista, uma conta é commposta por: agencia, numero da conta e usuario. 
o numero da conta e sequencial, iniciando em 1. o numero da agencia e fixo: "0001". 
o usuario pode ter mais de uma conta, mas uma conta pertence a somente um usuario. 
a lista deve ser filtrada pelo cpf.

