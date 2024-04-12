
A Shark Caminhões procurou a FourD para a Implementação do Salesforce em sua Companhia. A
grande preocupação da Shark Caminhões é que o Backoffce tenha uma experiência normal em
situações de alta demanda de uso. Para isto, no Processo de Captação de Leads e Conversão de Novos
Clientes eles gostariam de implementar um simples envio de mensagens para os Leads/Clientes
através da API do WhatsApp Web. Sendo assim:
Desenvolva uma VisualForce Page que execute uma chamada na API do WhatsApp Web com uma
simples mensagem para o número de Telefone do Lead.
A descrição da mensagem pode ser: “Olá –>Lead<—tudo bem? Informamos que já estamos
analisando seu cadastro para se tornar um de nossos clientes. Em breve retornaremos o contato”.
Validar através de Trigger em Lead, seguindo o padrão de triggerHandler (before insert / before
update) que valida o CEP informado no campo Lead.PostalCode, aceitando como entrada o formato
XXXXX-XXX ou XXXXXXXX apenas números, deverá emitir erro caso receba um outro tipo de
caracter e que padronize a saída no formato XXXXX-XXX.
Escrever rotina de teste, para sucesso e falha.
Obs.: Quanto a quais campos o objeto possui, pode utilizar a informação standard do objeto como
base.
