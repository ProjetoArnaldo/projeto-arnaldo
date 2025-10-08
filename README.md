# 📧 Gmail – Funcionalidades do Aplicativo -----

Este repositório apresenta as *principais funcionalidades* do aplicativo *Gmail*, abordando como o sistema permite a comunicação por e-mail de forma rápida, segura e organizada.  
O conteúdo faz parte do estudo desenvolvido na disciplina *Engenharia de Software I*, com foco em análise de funcionalidades e usabilidade.

# 🌐 Visão Geral

O *Gmail* é um serviço de e-mail desenvolvido pela *Google*, que permite ao usuário se comunicar de forma eficiente, segura e integrada a outras ferramentas, como Google Drive e Agenda.  
Nesta análise, foram consideradas as principais funcionalidades envolvidas no processo de *composição e envio de e-mails*.

---

## 🧭 Funcionalidades Baseadas nas Histórias de Usuário

### 📝 1. Compor Novo E-mail  
*História de Usuário:*  
	⁠Como um usuário, eu quero compor um novo e-mail com destinatário, assunto e corpo, para que eu possa preparar uma comunicação escrita.  

*Descrição da Funcionalidade:*  
•⁠  ⁠Permite ao usuário criar uma nova mensagem.  
•⁠  ⁠Exibe campos para *destinatário (Para), **assunto* e *corpo do e-mail*.  
•⁠  ⁠Inclui opções de *formatação de texto* (negrito, itálico, lista, links, etc.).  
•⁠  ⁠O rascunho é salvo automaticamente enquanto o usuário digita.  

---

### 🚀 2. Enviar E-mail  
*História de Usuário:*  
	⁠Como um usuário, eu quero enviar o e-mail que preparei, para que ele chegue corretamente ao destinatário.  

*Descrição da Funcionalidade:*  
•⁠  ⁠Após compor a mensagem, o usuário pode clicar em *“Enviar”*.  
•⁠  ⁠O sistema valida o endereço do destinatário antes do envio.  
•⁠  ⁠A mensagem é processada via *protocolo SMTP* e movida para a pasta *“Enviados”*.  
•⁠  ⁠Caso o envio falhe, o Gmail exibe uma *notificação de erro* ou *tentativa de reenvio*.  

---

### 📎 3. Anexar Arquivos  
*História de Usuário:*  
	⁠Como um usuário, eu quero poder anexar arquivos ao meu e-mail, para que eu possa compartilhar documentos importantes.  

*Descrição da Funcionalidade:*  
•⁠  ⁠Permite adicionar *imagens, PDFs, documentos, links do Drive* e outros formatos.  
•⁠  ⁠O sistema mostra o *nome e tamanho dos anexos* antes do envio.  
•⁠  ⁠Caso o anexo exceda o limite permitido, o Gmail oferece a opção de *enviar via Google Drive*.  
•⁠  ⁠Os anexos são verificados automaticamente quanto à segurança (antivírus do Google).  

---

## ⚙️ Fluxo do Usuário

1.⁠ ⁠O usuário acessa o botão *“Escrever”*.  
2.⁠ ⁠Digita o *destinatário, o **assunto* e o *corpo da mensagem*.  
3.⁠ ⁠(Opcional) Adiciona *anexos* relevantes.  
4.⁠ ⁠Clica em *“Enviar”*.  
5.⁠ ⁠O Gmail processa o envio e confirma com a mensagem *“E-mail enviado com sucesso”*.

---

## 👩‍💻 Projeto:

*Participantes: Ana Laura Amoroso, Ana Carolina, Silvia Helena e Larissa.
*Disciplina:* Engenharia de Software I  


