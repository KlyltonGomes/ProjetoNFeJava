# ProjetoNFeJava
Desenvolvimento de uma estrutura em Java, para a criação de um esqueleto da NFE( Nota Fiscal Eletrônica) usando Spring Boot
criando os campos da Nfe;
  
    ➤INDENTIFICAÇÃO  >> 📍CAMPO 
                        
    📍infNFe
      ↳ contêm os dados dos campos //  S  //   //TAG raiz da NF-e
        nomeados conforme manual
    📍ide 
      ↳ Nó de identificação da NFe
    📍emitente
      ↳ tag emit
    📍Destinatário
      ↳ tag dest   
    📍Local de Retirada
      ↳ tag retirada
    📍Local de Entrega
      ↳ tag entrega
➤ITENS DA NFE 📍📍

    📍Dado do Produto
    ↳🔗Detalhes Produto
            ↳ tag prod
    ↳🔗Detalhes Produto
            ↳ tag imposto
            Nó inicial dos Tributos incidentes no Produto ou Serviço do item da NFe
    
📍ICMS
  Todos os Campos
            ↳ Informações do ICMS da Operação própria e ST
📍
📍
📍
📍
📍
