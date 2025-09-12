Roteiro
(x) Criar o pacote
(x) Criar o projeto

Projeto SEGW: ZOV
Pacote: ZFIORI_001
Projeto GitHub: https://github.com/vcd94xt10z/youtube...

(x) Criar as entidades
Entidade: OVCab (Cabeçalho)
OrdemId (Número)(Chave)
DataCriacao (Data e Hora)
CriadoPor (Texto 20)
ClienteId (Número)
TotalItens (Decimal 15,2)
TotalFrete (Decimal 15,2)
TotalOrdem (Decimal 15,2)
Status (Texto 1)(N=Novo,L=Fornecido,F=Faturado,C=Cancelado)

Entidade: OVItem (Item)
OrdemId (Número)(Chave)
ItemId (Número)(Chave)
Material (Texto 18)
Descricao (Texto 100)
Quantidade (Número)
PrecoUni (Decimal 15,2)
PrecoTot (Decimal 15,2)

Entidade: Mensagem (DDIC BAPIRET2)

(x) Gerar os objetos
(x) Redefinir os métodos
(x) Registrar o serviço
(x) Atualizar Projeto no GitHub
