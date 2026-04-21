# PrivacyImpactAssessment

#O que temos de fazer:
O que é este trabalho?
Não é para implementar código (apesar de teres estado a trabalhar com código ID3 noutra parte).
Este trabalho é sobre PIA (Privacy Impact Assessment) – uma análise documental/legal/técnica sobre privacidade e proteção de dados.

Resumo do que tens de fazer
És o responsável pelo tratamento de dados (PII controller/processor) num projeto chamado COP-MODE.
Tens de avaliar os riscos de privacidade de um sistema que recolhe dados de utilizadores (incluindo email e nomes de apps) e propor medidas corretivas (cifra, controlo de acessos, anonimização, etc.).

Entregável: relatório (não código)
O relatório deve conter:
- Descrição do sistema – que dados são recolhidos, quem são os titulares, como flui a informação.
- Avaliação de risco inicial (cenário sem medidas de segurança) – usando a ferramenta da CNIL.
- Plano de ação – medidas corretivas para mitigar os riscos identificados, incluindo uma tabela com os 4 riscos pedidos.
- Reavaliação dos riscos depois de aplicares as medidas – mostrar como os riscos diminuem.

E a ferramenta?
A CNIL disponibiliza uma ferramenta (Excel ou online) que te ajuda a:
- Identificar riscos
- Classificar a severidade e probabilidade de cada risco
- Construir a matriz de risco
- Ver o impacto das medidas corretivas

Os 4 riscos específicos que tens de tratar na tabela
- Escuta nas comunicações smartphone ↔ servidor	---> Ex de mitigação: TLS/HTTPS, VPN, certificados
- Acesso não autorizado ao servidor	---> Ex de mitigação: autenticação forte, firewall, apenas acesso remoto seguro
- Linkability dos dados (email associado aos dados) ---> Ex de mitigação: pseudonimização, hash do email + salt, separar identificadores
- Vazamento de nomes de apps (dados sensíveis) --->	Ex de mitigação: hashing determinístico ou cifra com chave secreta, mantendo consistência


