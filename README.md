# Estagio-2021programa {
	funcao inicio() {
           inteiro senha 
    	   inteiro cpf
        inteiro deposito
	   inteiro saque
	   inteiro opcao
	   inteiro saldoatual
	   inteiro saldo
	   saldo=3000
    
            escreva("Digite o seu cpf: \n")
    leia(cpf)
    
    se ((cpf) != 106321462) {
        
        escreva("Cpf inválido, Digite novamente.\n")
        leia(cpf)
        
    }
    
    escreva("Digite sua senha: \n")
    leia(senha)
    
    se ((senha) != 543827) {
        
        escreva("Senha inválida, Digite novamente.\n")
        leia(senha)
        
	}

	escreva("Olá, esse é o seu menu:\n")
		escreva(" 1- Saque\n 2- Depósito\n 3- Consultar saldo\n 4- Sair\n")
		leia(opcao)
		
		
		se(opcao==1){ 
		    escreva("Quanto você quer sacar?\n")
		    leia(saque)
		    saldoatual=saldo-saque
		    escreva("Na sua conta sobrou: ", saldoatual)
		}
	
			senao se (opcao==2){
			escreva("Quanto você quer depositar?\n")
			leia(deposito)
			
			saldoatual=saldo + deposito
			escreva("Seu saldo atual é: \n", saldoatual)
			}
			senao se (opcao==3){
			escreva("Seu saldo é de: \n", saldo)
			}
			senao se (opcao==4){
			escreva("Você saiu da sua conta! \n")
			}



	}
}
