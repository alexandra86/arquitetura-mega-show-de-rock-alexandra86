<h1 align="center" font-family="pattaya">Arquitetura do projeto Mega Show de Rock em Rio</h1><br>
<h2 font-family="pattaya">Desafio técnico - BigDataCorp</h2>

<h2 font-family="pattaya">Descrição</h2><br>
<p font-family="robotto" font-size="16px" line-height="34px" align="justify">
A imagem abaixo fará referência ao projeto Mega Show Rock em Rio, onde os clientes poderão ter acesso à uma aplicação de compra de ingressos.
</p><br>

<h2 font-family="pattaya">Composição Páginas</h2><br>
- Login; <br>
- Cadastro; <br>
- Dashboard; <br>
- Compra de Ingressos; <br>
- Pagamentos de Ingressos. 

<h2 font-family="pattaya">Arquitetura do Projeto</h2><br>
![Arquitetura do Projeto - Mega Show de Rock em Rio](show_rock.jpeg)

<h2 font-family="pattaya">Regras de Negócio</h2><br>
- Haverá uma fila de espera para a compra de ingressos. Enquanto um cliente inicia o processo de compra, o próximo deverá aguardar a sua liberação para acesso à página de compras.<br>
- O Cliente somente poderá comprar 1 ingresso por cada CPF informado.<br>
- Caso não haja ingresso disponível, o cliente será notificado na página que não é possível realizar a compra de ingressos, pois estão esgotados.<br>
- Após a confirmção da compra dos ingressos na página de pagamentos, o Cliente receberá no seu e-mail cadastrado a confirmação dos ingressos comprados.<br>
