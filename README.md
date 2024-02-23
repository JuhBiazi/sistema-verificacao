# sistema-verificacao
 Verificação de conta
 --------------------

 Uma parte dos códigos feitos por mim para o site: 
 <p align="left">
 <a href="https://www.p2win.com.br" target="_blank" rel="noreferrer"><img src="https://imgur.com/Uq2xQiG.gif" width="36" height="36" alt="P2Win" /></a>
 </p>

### Acc verification 
    * Adicionei campo CPF (campo obrigatório e depois que aprovado, é exibido apenas como   vizualização, não podendo ser alterado);
    * Alterei Layout pra ficar mais bonito e compreensivel.
  
### Withdraw 
    * Criei um método de verificação para que somente pessoas verificadas por nós possam fazer o  pedido de retirada de saldo;
    * Após o pedido feito, o saque é feito para a chave pix, sendo essa o CPF informado no centro de verificação, esse pedido é enviado par aum painel de adm informando todos os dados do solicitante;
    * No histórico de saque é exibido a chave pix, o valor e o status do pedido.
