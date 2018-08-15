# Senior-X Integration API 

A API permite integração REST -> SOAP entre o Senior X Platform e Sistemas G5/G6.
Mais informações em https://dev.senior.com.br/documentacao/integracao-com-g5/

# Ambiente de testes

Para a API autenticar em ambientes de teste, é necessário passar o parâmetro "serverAuth".
Por exemplo:
http://10.1.27.183:8080/SXI/GenericConsult?consult=wf_endereco_cidades_do_estado&serverAuth=https://pcbnu002050.interno.senior.com.br:8243

Com isso, será chamada a primitiva ObterMeus dados no servidor informado, exemplo: "https://pcbnu002050.interno.senior.com.br:8243/t/senior.com.br/bridge/1.0/rest/usuarios/userManager/queries/obterMeusDados"
