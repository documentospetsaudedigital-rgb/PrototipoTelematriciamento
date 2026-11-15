# Telematriciamento

Apoio matricial a distância entre as UBS de uma Região e a Equipe de matriciamento dessa Região, no âmbito do PET-Saúde Digital.

## Pessoas e perfis

**Conta**:
Acesso de uma pessoa à plataforma; cada Conta tem exatamente um Perfil.
_Evitar_: usuário, usuário do sistema, utilizador, profissional (como termo genérico)

**Perfil**:
Papel fixo de uma Conta: Administrador do sistema, Coordenador da RAPS, Profissional da UBS, Profissional de Referência ou Matriciador.
_Evitar_: tipo de usuário, função

**Profissional da UBS**:
Perfil de quem atua na UBS e cadastra Usuários do SUS, Atendimentos e Casos da sua UBS.
_Evitar_: equipe local, profissional da equipe local

**Profissional de Referência**:
Perfil de quem coordena a Equipe de matriciamento de uma Região.
_Evitar_: referência, responsável pelo caso

**Matriciador**:
Perfil de quem integra uma Equipe de matriciamento e apoia a análise dos Casos.
_Evitar_: especialista, profissional executor, matriciado

**Usuário do SUS**:
Pessoa atendida na UBS cujo cuidado é discutido em um Caso; não possui Conta.
_Evitar_: usuário (sozinho), paciente, pessoa, cidadão, utilizador

**Convidado**:
Pessoa externa registrada em um Caso como participante esperado da Reunião de matriciamento; não possui Conta.
_Evitar_: participante externo, visitante

**Relator**:
Papel atribuído a uma pessoa com Conta, numa Reunião de matriciamento, para registrar as decisões; não é um Perfil.
_Evitar_: secretário, redator

## Organização

**Região**:
Território que agrupa UBS e CAPS e é atendido por uma única Equipe de matriciamento ativa.
_Evitar_: distrito, área, território (como sinônimo)

**Unidade de Saúde**:
UBS ou CAPS de uma Região.
_Evitar_: unidade (sozinha), estabelecimento

**Equipe de matriciamento**:
Grupo regional formado por um Profissional de Referência e seus Matriciadores, que recebe os Casos das UBS da Região. "Equipe", sozinha, sempre significa Equipe de matriciamento.
_Evitar_: equipe local, equipe matriciadora, equipe de referência

## Caso

**Atendimento**:
Registro feito pelo Profissional da UBS sobre um Usuário do SUS, com motivo, relato inicial e Classificação de risco; pode dar origem a um Caso.
_Evitar_: triagem, escuta inicial, consulta

**Classificação de risco**:
Grau de risco e vulnerabilidade atribuído no Atendimento: Não aguda (azul), Baixo (verde), Intermediário (amarelo) ou Alto (vermelho).
_Evitar_: risco médio, prioridade

**Caso**:
Situação de um Usuário do SUS levada por uma UBS à Equipe de matriciamento, acompanhada do cadastro até a conclusão.
_Evitar_: solicitação, pedido de matriciamento, compartilhamento do cuidado

**Fila**:
Lista dos Casos de uma UBS que ainda não foram enviados, na ordem definida pelos Profissionais da UBS.
_Evitar_: lista de espera, fila de casos passíveis de pré-matriciamento

**Envio**:
Ato de mandar um Caso da UBS para a Equipe de matriciamento da Região.
_Evitar_: encaminhamento, solicitação de matriciamento

**Encaminhamento**:
Indicação do Usuário do SUS para outro serviço, nível de atenção ou profissional. Nunca designa o Envio de um Caso.
_Evitar_: referenciamento, guia (como sinônimo)

**Pré-matriciamento**:
Etapa após o Envio na qual a Equipe de matriciamento analisa o Caso e decide se ele precisa de Reunião de matriciamento.
_Evitar_: triagem, análise prévia, pré-matriciamento como campo ou texto da UBS

**Desfecho do pré-matriciamento**:
Decisão da Equipe, ao fim do Pré-matriciamento, sobre o Caso: Requer Reunião ou Dispensa Reunião.
_Evitar_: indicação, parecer, triagem

**Documento de matriciamento**:
Texto único de cada Caso, no qual a UBS e a Equipe escrevem o relato, a análise, a discussão, as decisões e os Encaminhamentos. "Documento", sozinho, sempre significa Documento de matriciamento.
_Evitar_: ata, registro consolidado, documento textual, relatório

**Reunião de matriciamento**:
Encontro agendado entre a Equipe e as pessoas envolvidas, no qual um ou mais Casos são discutidos.
_Evitar_: encontro, sessão, agenda
