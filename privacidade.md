# Política de Privacidade — Disciplinum

**Última atualização:** 28 de junho de 2026

O **Disciplinum** valoriza a sua privacidade. Esta Política de Privacidade explica como coletamos, usamos, armazenamos e protegemos seus dados pessoais, em **conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018 - LGPD)**.

Ao utilizar o Disciplinum, você concorda com as práticas descritas nesta política.

---

## 📋 1. Dados que Coletamos
Coletamos **apenas os dados necessários** para o funcionamento do aplicativo e melhoria da experiência do usuário.
   **Tipo de Dado** | **Exemplos** | **Finalidade** | **Base Legal (LGPD)** |
 |------------------|--------------|---------------|------------------------|
 | **Dados de Identificação** | Nome, E-mail, **Foto de Perfil (opcional, via Google Auth ou upload manual)** | Criação de conta, login e personalização do perfil | Execução de Contrato (Art. 7º, V) |
 | **Dados de Uso** | Hábitos criados, registros de "check-ins", medalhas, tempos de uso | Funcionalidade principal do app (monitoramento de disciplina) | Execução de Contrato (Art. 7º, V) |
 | **Identificadores de Dispositivo** | ID de Publicidade (AdID), Modelo do aparelho, Versão do Android | Exibição de anúncios (apenas com consentimento explícito) | **Consentimento (Art. 7º, I)** |
 | **Logs de Falhas** | Relatórios de erros (via Firebase Crashlytics) | Correção de bugs e estabilidade do app | Consentimento (Art. 7º, I) |
 | **Dados de Sincronização** | Configurações do app, progresso dos hábitos | Sincronização entre dispositivos | Execução de Contrato (Art. 7º, V) |
   **Dados de Análise** | Eventos de uso (telas acessadas, interações), relatórios de erros | Melhoria do app e correção de bugs | **Consentimento (Art. 7º, I)** |

*A foto de perfil é opcional e pode ser adicionada via upload ou sincronizada do Google (se usar login com Google).*

> ⚠️ **Não coletamos diretamente:**
> - Dados de localização GPS
> - Número de telefone
> - **Informações de pagamento** (as compras no aplicativo são processadas pelo **Google Play Billing**)

---

## 🔄 2. Compartilhamento com Terceiros
**Não vendemos seus dados pessoais.** Compartilhamos dados **apenas com serviços essenciais** para a infraestrutura, monetização e processamento de pagamentos do aplicativo.
 | **Serviço** | **Dados Compartilhados** | **Finalidade** | **Política de Privacidade** |
 |-------------|------------------------|---------------|-----------------------------|
 | **Supabase** (Banco de Dados e Auth) | E-mail, hábitos, progresso, configurações, **fotos de perfil** | Armazenamento seguro e autenticação | [supabase.com/privacy](https://supabase.com/privacy) |
 | **Google AdMob** | ID de Publicidade (AdID) | Exibição de anúncios **apenas com consentimento** | [policies.google.com/privacy](https://policies.google.com/privacy) |
 | **Firebase Crashlytics** | Logs de erros (anônimos) | Monitoramento de falhas e estabilidade | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
 | **Google Play Billing** | Dados de transação (sem informações de cartão) | Processamento de compras no aplicativo | [payments.google.com](https://payments.google.com) |

> 🔹 **Google Play Console:** Declaração de dados preenchida conforme [Política de Privacidade do Google Play](https://play.google.com/console/u/0/developers/policy).

---
## 🗃️ 3. Retenção e Exclusão de Dados
Seus dados são mantidos **enquanto você tiver uma conta ativa** no Disciplinum.

- **Exclusão de Conta:** Você pode solicitar a exclusão da sua conta e de todos os dados associados:
  - Diretamente nas **configurações do aplicativo** (em desenvolvimento)
  - Ou enviando um e-mail para [disciplinum.app@gmail.com](mailto:disciplinum.app@gmail.com)
- **Prazo para exclusão:**
  - **Dados ativos:** Removidos em até **7 dias** após a solicitação
  - **Backups:** Podem ser mantidos por até **90 dias** (conforme política do Supabase)
  - **Obrigação legal:** Dados podem ser retidos se exigido por lei

---
## ⚖️ 4. Seus Direitos (LGPD)
Como titular dos dados, você tem direito a:

1. **Confirmar** a existência de tratamento de dados.
2. **Acessar** os dados que possuímos sobre você.
3. **Corrigir** dados incompletos, inexatos ou desatualizados.
4. **Solicitar a anonimização, bloqueio ou eliminação** de dados desnecessários.
5. **Revogar o consentimento** a qualquer momento (o que pode impedir o uso de certas funções do app).

**Como exercer seus direitos:**
Envie um e-mail para [disciplinum.app@gmail.com](mailto:disciplinum.app@gmail.com) com:
- Assunto: **"LGPD - Solicitação de [direito]"**
- Cópia do **RG/CPF** (para verificação de identidade)
- Descrição detalhada da solicitação

**Prazo para resposta:** Até **15 dias** (conforme LGPD).

---
## 🔐 5. Segurança
Adotamos as seguintes medidas para proteger seus dados:

- **Criptografia em trânsito:** Todas as comunicações com nossos servidores usam **SSL/TLS (HTTPS)**.
- **Criptografia em repouso:** **Não disponível no plano atual** (dados são armazenados em servidores seguros do Supabase).
- **Controle de acesso:** **Row Level Security (RLS)** ativo no banco de dados para restringir acesso não autorizado.
- **Backups automáticos:** Dados são copiados diariamente para prevenir perda acidental.
- **Autenticação segura:** Login via **Google Auth (OAuth 2.0)** ou **E-mail/Senha**.

> ⚠️ **Importante:** Nenhum sistema é 100% seguro. Recomendamos que você **não compartilhe suas credenciais** e mantenha seu dispositivo com senha.

---
## 🌍 6. Transferência Internacional
Alguns serviços utilizados (Supabase, Google AdMob, Firebase, Google Play Billing) têm servidores **localizados fora do Brasil** (ex: EUA, Europa).

- Ao usar o app, você **consente** com essa transferência.
- Garantimos que nossos parceiros **seguem padrões adequados de segurança** (ex: GDPR, CCPA).

---
## 📱 7. Anúncios e Consentimento
O Disciplinum exibe **anúncios do Google AdMob** para sustentar seu desenvolvimento.

### **Seu controle sobre anúncios:**
- **Anúncios personalizados:** Baseados em seus interesses (requer **consentimento explícito**).
- **Anúncios não personalizados:** Baseados apenas no contexto do app (padrão se não consentir).

**Como gerenciar:**
- **No aplicativo:** Você será solicitado a consentir na primeira abertura (via **Google UMP SDK**).
- **A qualquer momento:** Acesse [Configurações de Anúncios do Google](https://adssettings.google.com) para ajustar suas preferências.

> 💡 **Nota:** Optar por anúncios não personalizados **não remove os anúncios**, apenas os torna menos relevantes.

### 🎛️ Controle de Dados de Uso e Erros
Você pode **ativar ou desativar a coleta de dados de uso e relatórios de erros** a qualquer momento:
- **No aplicativo:** Acesse **Configurações > Análise de uso e erros** e desative o toggle.
- **Efeito:** Ao desativar, **Firebase Analytics e Firebase Crashlytics** pararão de coletar dados.
- **Impacto:** Isso pode limitar nossas melhorias no app, mas não afeta o funcionamento básico.

---
## 💳 8. Compras no Aplicativo (In-App Purchases)
O Disciplinum é **gratuito**, mas pode oferecer **funcionalidades extras, premium ou exclusivas** mediante compra no aplicativo.

- **Processamento de pagamentos:** Todas as compras são processadas pelo **Google Play Billing** (Google).
- **Dados de pagamento:** **Não temos acesso** a informações de cartão de crédito ou outros dados financeiros. Esses dados são gerenciados **exclusivamente pelo Google**.
- **Política de reembolso:** Reembolsos estão sujeitos à [Política de Reembolso do Google Play](https://support.google.com/googleplay/workflow/13426663).
- **Cancelamento de assinaturas:** Assinaturas podem ser canceladas nas configurações da Google Play Store.

> ⚠️ **Importante:** Compras no aplicativo são **não reembolsáveis**, exceto conforme exigido por lei.

---
## 👶 9. Uso por Menores
- O aplicativo é **destinado a usuários com 13 anos ou mais**.
- **Menores de 18 anos** devem ter o consentimento dos responsáveis legais.
- **Não coletamos dados de menores de 13 anos intencionalmente.**
- Se tomarmos ciência de coleta acidental, **excluiremos os dados imediatamente**.

---
## 📞 10. Contato
Para dúvidas sobre esta política ou gestão de dados:

- **E-mail:** [disciplinum.app@gmail.com](mailto:disciplinum.app@gmail.com)
- **Documentos legais:** [https://github.com/BatataNativs/disciplinum-legal](https://github.com/BatataNativs/disciplinum-legal)

---
**Disciplinum — 2026**
*Desenvolvido por Douglas Natividade*
