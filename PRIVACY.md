# Política de Privacidade / Privacy Policy — FlocoBar

_Atualizada em 24/11/2026 · Updated 2026-11-24_

## Português

O FlocoBar é um programa para Windows que roda no seu computador. Esta política explica o que acontece com os seus dados quando você usa a função opcional **Google Tarefas**.

**O que o FlocoBar acessa.** Se (e somente se) você clicar em "Conectar ao Google", o FlocoBar pede permissão para ver e editar as **suas tarefas** do Google Tarefas (escopo `https://www.googleapis.com/auth/tasks`). Ele usa isso apenas para mostrar na ilha as tarefas da sua lista padrão ("Minhas tarefas") e enviar para lá o que você criar, concluir ou apagar na ilha.

**Onde os dados ficam.** Tudo acontece entre o seu computador e o Google. O FlocoBar **não tem servidor próprio**, **não envia seus dados a nós nem a terceiros** e não usa suas tarefas para publicidade, análise ou treinamento de qualquer sistema. As tarefas ficam num arquivo local no seu PC (`%AppData%\FlocoBar\todo.json`). O token de acesso fica no seu PC, protegido pelo Windows (DPAPI); a sua senha do Google nunca passa pelo FlocoBar.

**Como parar.** Em Configurações > Google Tarefas, clique em "Desconectar": o token é apagado do computador e revogado no Google. Você também pode remover o acesso em https://myaccount.google.com/permissions.

**Uso de dados do Google.** O uso e a transferência de informações recebidas das APIs do Google pelo FlocoBar seguem a [Política de Dados do Usuário dos Serviços de API do Google](https://developers.google.com/terms/api-services-user-data-policy), incluindo os requisitos de Uso Limitado.

**Contato.** Abra uma issue em https://github.com/katsuuzin/FlocoBar/issues.

## English

FlocoBar is a Windows program that runs on your computer. This policy explains what happens to your data when you use the optional **Google Tasks** feature.

**What FlocoBar accesses.** Only if you click "Connect to Google", FlocoBar asks for permission to view and edit **your tasks** in Google Tasks (scope `https://www.googleapis.com/auth/tasks`). It uses this only to show the tasks of your default list ("My Tasks") in the island and to send there what you create, complete or delete in the island.

**Where data lives.** Everything happens between your computer and Google. FlocoBar has **no server of its own**, **does not send your data to us or to third parties**, and does not use your tasks for advertising, analytics or training any system. Tasks are kept in a local file on your PC (`%AppData%\FlocoBar\todo.json`). The access token stays on your PC, protected by Windows (DPAPI); your Google password never goes through FlocoBar.

**How to stop.** In Settings > Google Tasks, click "Disconnect": the token is deleted from the computer and revoked at Google. You can also remove access at https://myaccount.google.com/permissions.

**Google user data.** FlocoBar's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

**Contact.** Open an issue at https://github.com/katsuuzin/FlocoBar/issues.
