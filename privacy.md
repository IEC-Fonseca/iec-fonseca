# Política de Privacidade — IEC Fonseca Tesouraria

**Última atualização: 18 de Maio de 2026**

Esta Política de Privacidade descreve como o aplicativo **IEC Fonseca
Tesouraria** ("o Aplicativo") coleta, utiliza, armazena e protege as
informações dos seus usuários.

O Aplicativo é mantido pela **Igreja Evangélica Congregacional Fonseca** ("nós", "nossa
organização") e destinado exclusivamente ao uso interno dos tesoureiros
autorizados da igreja, para registro e acompanhamento da movimentação
financeira interna.

---

## 1. Quem usa o Aplicativo

O Aplicativo é de **acesso restrito**. Apenas pessoas explicitamente
autorizadas pela administração da igreja (com os papéis de Tesoureiro ou
Super Administrador) conseguem fazer login e utilizar suas funcionalidades.

Não é um aplicativo de uso público. A distribuição ocorre via Google Play em
faixa de teste fechado (Closed Testing), com lista de e-mails autorizados.

---

## 2. Quais dados coletamos

### 2.1 Dados de identificação obtidos via Google Sign-In

Quando você faz login com sua conta Google, recebemos:

- **Nome completo**
- **Endereço de e-mail**
- Identificador único do Google (`sub`) — usado internamente para vincular
  sua conta às permissões

Não recebemos sua senha do Google. A autenticação ocorre integralmente
dentro da infraestrutura do Google (Firebase Authentication).

### 2.2 Dados gerados pelo uso do Aplicativo

Ao registrar lançamentos financeiros da igreja, você gera os seguintes
dados que ficam atrelados à sua conta:

- **Lançamentos**: tipo (entrada ou saída), valor, data, categoria,
  descrição, forma de pagamento, responsável e e-mail de quem registrou
- **Comprovantes**: imagens (JPG, PNG) ou arquivos PDF enviados como
  anexo a cada lançamento

### 2.3 Dados que NÃO coletamos

- Localização do dispositivo
- Lista de contatos
- Identificadores publicitários
- Dados de navegação ou comportamento fora do Aplicativo
- Informações de pagamento pessoais (cartão de crédito, conta bancária etc.)

O Aplicativo **não exibe anúncios** e **não envia dados para redes de
publicidade** ou ferramentas de análise comportamental.

---

## 3. Como utilizamos os dados

Os dados coletados são utilizados exclusivamente para:

- Permitir o login e identificar o usuário no Aplicativo
- Autorizar o acesso conforme o papel atribuído (Tesoureiro / Super
  Administrador)
- Registrar e exibir os lançamentos financeiros da tesouraria
- Apresentar relatórios consolidados da movimentação interna da igreja

Não utilizamos os dados para nenhum tipo de marketing, perfilamento ou
venda a terceiros.

---

## 4. Onde os dados são armazenados

- **Autenticação**: Firebase Authentication (Google LLC), com servidores
  globais sob padrões do Google
- **Lançamentos**: banco de dados MongoDB Atlas, hospedado em
  infraestrutura Google Cloud Platform na região `us-east4` (Estados
  Unidos)
- **Comprovantes (arquivos)**: Firebase Storage (Google Cloud Storage),
  no projeto da igreja

Todos os dados são transmitidos entre o Aplicativo e a infraestrutura por
conexões criptografadas (HTTPS / TLS).

---

## 5. Compartilhamento com terceiros

**Não compartilhamos seus dados com terceiros para fins comerciais.**

Os únicos provedores que processam dados em nosso nome são:

- **Google LLC** (Firebase Authentication, Firebase Storage, Google Cloud
  Platform) — atuando como operador da infraestrutura técnica
- **MongoDB, Inc.** (MongoDB Atlas) — atuando como operador do banco
  de dados

Esses provedores estão contratualmente vinculados às suas próprias
políticas de privacidade e padrões de segurança.

Não vendemos, alugamos ou cedemos seus dados a qualquer outra entidade.

---

## 6. Segurança

Adotamos as seguintes medidas de segurança:

- Autenticação obrigatória via Google Sign-In, com verificação de
  permissões a cada requisição ao servidor
- Transmissão criptografada (HTTPS) em todas as comunicações
- Armazenamento de credenciais via Firebase Auth, sem que o Aplicativo
  tenha acesso a senhas
- Acesso ao banco e ao storage restrito por chaves de serviço, mantidas
  em ambiente fechado da igreja

Nenhum método de transmissão ou armazenamento eletrônico é 100% seguro.
Em caso de incidente de segurança, comprometemo-nos a comunicar os
usuários afetados conforme a Lei Geral de Proteção de Dados (LGPD).

---

## 7. Retenção e exclusão

Os lançamentos financeiros e seus respectivos comprovantes são mantidos
**enquanto necessários para a finalidade contábil interna** da igreja,
podendo ser retidos por períodos definidos pela legislação aplicável a
entidades religiosas e contábeis.

Os dados pessoais de identificação (nome, e-mail) são mantidos enquanto
você tiver autorização ativa para acessar o Aplicativo.

### Direito de exclusão

Você pode solicitar a exclusão dos seus dados pessoais ou da sua conta
escrevendo para o e-mail de contato listado ao final desta política.
Atenderemos no prazo previsto pela LGPD.

Observação: lançamentos financeiros já registrados podem ser
desvinculados da sua identificação pessoal, mas não removidos, em razão
de exigência de manutenção dos registros contábeis da igreja.

---

## 8. Direitos do titular (LGPD)

Conforme a Lei nº 13.709/2018 (LGPD), você tem direito a:

- Confirmar a existência de tratamento dos seus dados
- Acessar os dados que mantemos sobre você
- Corrigir dados incompletos, inexatos ou desatualizados
- Solicitar a exclusão de dados desnecessários ou tratados em
  desconformidade
- Solicitar a portabilidade dos seus dados
- Revogar consentimentos
- Obter informações sobre o compartilhamento dos seus dados

Para exercer qualquer desses direitos, entre em contato pelo e-mail
abaixo.

---

## 9. Crianças

O Aplicativo é destinado exclusivamente a adultos com responsabilidade
sobre a tesouraria da igreja. **Não coletamos intencionalmente dados de
menores de 18 anos.** Caso identifiquemos coleta acidental de dados de
menores, removeremos as informações prontamente.

---

## 10. Alterações nesta política

Esta política pode ser atualizada periodicamente. A versão vigente
sempre estará disponível no mesmo endereço público. Quando houver
mudanças relevantes (por exemplo, novas categorias de dados coletados ou
novos compartilhamentos), comunicaremos os usuários por meio do próprio
Aplicativo na próxima atualização ou por e-mail.

A data da última atualização aparece no topo deste documento.

---

## 11. Contato

Para dúvidas, solicitações ou exercício dos direitos da LGPD:

- **Responsável**: Tesouraria da Igreja Evangélica Congregacional Fonseca
- **E-mail**: contato.gabriel@outlook.com

Responderemos em até 15 dias úteis.

---

_Este aplicativo não tem qualquer vínculo comercial ou de patrocínio com
o Google LLC ou MongoDB, Inc. Suas marcas e nomes citados pertencem aos
respectivos titulares e são mencionados apenas para fins de transparência
sobre a infraestrutura técnica utilizada._
