# TPrompter — instaladores

**Versão atual: 2.1.1** — baixe em **[Releases](https://github.com/EstudiosBrad/tprompter-releases/releases/latest)**.
O que mudou em cada versão está nas notas de cada release.

O **TPrompter** é o teleprompter dos Estúdios Bradesco. Aqui ficam só os arquivos de
instalação; o código-fonte é privado.

## O que o app faz

- **Duas janelas:** a do operador, onde se escreve e formata o roteiro, e a do vidro do TP,
  espelhada, em tela cheia na outra tela. Com duas telas abre também o **monitor do
  operador**, a cópia do vidro com os comandos.
- **O editor é o vidro:** mesma fonte, tamanho, largura e quebra de linha do TP. Dá para
  **corrigir no ar** sem tirar do ar, com desfazer.
- **Roteiros:** abre Word (`.docx`), PDF, `.txt`, `.rtf` e `.md`, com cores; biblioteca,
  **eventos e cenas** (um texto por apresentador), **marcas** para pular no roteiro,
  localizar e substituir, presets de palavras coloridas, pasta dos textos.
- **Leitura:** guia de leitura, **faixa de leitura**, **contagem antes do Play**, **tempo
  no vidro** (cronômetro e o que resta), espaço entre letras, espelho horizontal e vertical.
- **Controle:** roda do mouse como acelerador, teclado, **pedal, passador de slides e
  Stream Deck** (a tecla de cada comando é escolhida por máquina), velocidades fixas.
- **Celular:** controle remoto com fader, shuttle e retorno do vidro, pela rede do estúdio
  ou pela nuvem — até sem computador, só com celulares.

## Qual arquivo pegar

| Você usa | Arquivo |
|---|---|
| Mac com chip Apple (M1, M2, M3…) | `TPrompter-x.y.z-arm64.dmg` |
| Mac com chip Intel | `TPrompter-x.y.z.dmg` |
| Windows do trabalho (que barra instalador) | `TPrompter-x.y.z-win.zip` |
| Windows, um arquivo só | `TPrompter-x.y.z-portatil.exe` |
| Windows que deixa instalar | `TPrompter.Setup.x.y.z.exe` |

## Na primeira abertura

O app não é assinado digitalmente, então o sistema reclama uma vez:

- **Mac** — abra o `.dmg`, arraste o TPrompter para Aplicativos e tente abrir. Quando o
  macOS bloquear, vá em **Ajustes do Sistema → Privacidade e Segurança** e clique em
  **Abrir Mesmo Assim**. Da segunda vez em diante abre direto. Se aparecer **"está
  danificado e não pode ser aberto"**, não apague: rode no Terminal
  `xattr -dr com.apple.quarantine /Applications/TPrompter.app`.
- **Windows** — no `.zip`, extraia a pasta onde quiser (Documentos, Área de Trabalho,
  pendrive) e abra o `TPrompter.exe`. Nada vai para o registro e não há instalador
  rodando. Se aparecer o aviso azul do Windows, clique em **Mais informações → Executar assim mesmo**.

Depois, o app abre na tela de **licença**: **COMEÇAR TESTE** (7 dias grátis) ou **JÁ
TENHO UMA LICENÇA** (cole a chave que você recebeu). Em rede que bloqueia o servidor de
licenças, use a **chave sem internet** (começa com `TPO.`): ela ativa sem internet e não
expira.

Nos dois, se o firewall perguntar, **permita o acesso em redes privadas** — sem isso os
celulares não conectam no computador.

## Depois disso, não precisa voltar aqui

O próprio app avisa quando há versão nova e se atualiza sozinho: é só clicar em
**Atualizar e reabrir**. Na rede que bloqueia a nuvem do app, ele se atualiza por aqui,
pelo GitHub. Você só volta a esta página numa máquina nova, ou quando o app pedir para
**Baixar** — é quando a atualização mexe no programa inteiro e não dá para trocar com ele
aberto.

A 2.0 é a versão final do app: as próximas seguem dela (2.0.3, 2.1…), e cada uma tem
instaladores e notas aqui.
