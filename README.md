programa {
	funcao inicio() {
	    inteiro op, opd
	    real doce1 = 4.00, doce2 = 2.50, doce3 = 3.0, doce4 = 4.00, doce5 = 2.50, doce6 =  3.00, somadoce = 0.0, somadoce2 = 0.0
	    cadeia opd2
	    
	    
		escreva("============================================\n")
		escreva("              Seja Bem Vindo\n")
		escreva("============================================\n")
		
		escreva("Temos diversas opções, escolha a sua \n")
		escreva("1. Doces\n")
		escreva("2. Salgados\n")
		escreva("3. Pratos prontos\n")
		escreva ("4. Açaí\n")
		escreva("Digite sua opção: ")
		leia(op)
		
		    se (op == 1) {
		        limpa()
		            escreva("======================================================\n")
		            escreva("            Temos as seguintes opções: \n")
		            escreva("1. Brownie\n")
		            escreva("2. Brigadeiro\n")
		            escreva("3. Beijinho\n")
		            escreva("Digite sua opção de doce:\n ")
		            leia(opd)
		        se ( opd == 1) {
		                limpa()
		                somadoce = 4.0
		                escreva("Compra realizada, brownie custa 4,00 reais\n")
		        }
		        senao se (opd == 2) {
		                limpa()
		                somadoce = somadoce + doce2
		                escreva("Compra realizada, brigadeiro custa 2,50 reais\n")
		                somadoce = 2.50

		        }
		         senao se (opd == 3) {
		                limpa()
		                somadoce = somadoce + doce3
		                escreva("Compra realizada, beijinho custa 3,00 reais\n")
		                somadoce = 3.0
		         }
		         
                  escreva("Deseja realizar mais alguma compra ? (s/n)\n")
		            leia(opd2)
		            
		                se (opd2 == "s") {
		                    limpa()
		                        escreva("======================================================\n")
		                        escreva("            Temos as seguintes opções: \n")
		                        escreva("1. Brownie\n")
		                        escreva("2. Brigadeiro\n")
		                        escreva("3. Beijinho\n")
		                        escreva("Digite sua opção de doce:\n ")
		                        leia(opd)
		                se ( opd == 1) {
		                    escreva("Compra realizada, brownie custa 4,00 reais\n")
		                    somadoce2 =  4.0
		                   }
		                senao se (opd == 2) {
		                    escreva("Compra realizada, brigadeiro custa 2,50 reais\n")
		                    somadoce2 = 2.50
		                }
		                senao se (opd == 3) {
		                    escreva("Compra realizada, beijinho custa 3,00 reais\n")
		                    somadoce2 = 3.0
		                }
		  
		                escreva("========================================\n")
		                escreva("        Comanda\n")
		                escreva("========================================\n")
                            escreva("1................",somadoce)
                            escreva("\n2................",somadoce2)
		                }
		                
		                se (opd2 == "n") {
		                    limpa()
		               escreva("==================================\n")
		               escreva("      Monte seu pedido\n")
		               escreva("==================================\n")
		               escreva("1...........", somadoce)
		                }
		            }
		            
		          se (op == 4) {
		              limpa()
		               escreva("==================================\n")
		               escreva("      Monte seu pedido\n")
		               escreva("==================================\n")
		               
		               escreva("| 1. Açaí                   |\n")
		               escreva("| 2.creme de ninho          |\n")
		               escreva("| 3. creme de morango       |\n")
		               escreva("| 5. Cereja                 |\n")
		               escreva("| 6. Gotas de chocolate     |\n")
		               escreva("=========================================\n")
		            }
	       }
		}

