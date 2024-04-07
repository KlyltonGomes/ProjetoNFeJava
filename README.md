# ProjetoNFeJava
Desenvolvimento de uma estrutura em Java, para a criação de um esqueleto da NFE( Nota Fiscal Eletrônica) usando Spring Boot
criando os campos da Nfe;
  
  ➤INDENTIFICAÇÃO  >> 📍CAMPO 
                        
    📍infNFe
            ↳ tag infNFe
                      >> contêm os dados dos campos
                                  
    📍ide 
         ↳ Nó de identificação da NFe
                                    >> nomeados conforme manual
    📍emitente
              ↳ tag emit
                        >> Nó com os dados do emitente             
    📍Destinatário
                  ↳ tag dest
                            >> Nó com os dados do destinatário
    📍Local de Retirada
                      ↳ tag retirada
                                     >> Nó indicativo de local de retirada diferente do endereço do emitente
    📍Local de Entrega
                      ↳ tag entrega
                                    >> Node indicativo de local de entrega diferente do endereço do destinatário
      
➤ITENS DA NFE

    📍Dado do Produto
    ↳🔗Detalhes Produto
            ↳ tag prod
                      >> Nó de dados do produto/serviço
    ↳🔗Detalhes Produto
            ↳ tag imposto
                      >> Nó inicial dos Tributos incidentes no Produto ou Serviço do item da NFe
    
📍ICMS
  Todos os Campos
            ↳ Informações do ICMS da Operação própria e ST
📍
📍
📍
📍
📍
