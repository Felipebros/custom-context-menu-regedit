# Custom Context Menu Scripts (Regedit)

Este repositório contém uma coleção de arquivos de registro (`.reg`) e scripts para personalizar o menu de contexto do Windows (clique direito), adicionar atalhos úteis e restaurar o menu clássico no Windows 11.

## 📂 Conteúdo do Projeto

### Restauração do Menu Clássico (Windows 11)
- **`Ativar Menu de Contexto Classicas do Windows.reg`**: Restaura o menu de contexto clássico do Windows 10 no Windows 11 (remove a opção "Mostrar mais opções").
- **`Desativar Menu de Contexto Classicas do Windows.reg`**: Reverte a alteração, voltando para o menu de contexto moderno do Windows 11.

### Atalhos de Aplicativos
- **`MobaXterm.reg`**: Adiciona o **MobaXterm** ao menu de contexto para abrir terminais rapidamente.
- **`MobaXterm bookmark.reg`**: Adiciona atalhos específicos (bookmarks) do MobaXterm ao menu de contexto.
- **`config-Sublime-menu-contexto.reg`**: Adiciona a opção "Open with Sublime Text" ao menu de contexto de arquivos e pastas.
- **`config-Antigravity-menu-contexto.reg`**: Configuração personalizada para adicionar o **Antigravity** ao menu de contexto.
- **`wsl-context-menu.reg`**: Adiciona opções para abrir o **WSL** (Windows Subsystem for Linux) diretamente na pasta atual.

### Utilitários
- **`start-terminal.bat`**: Script simples para abrir o Windows Terminal (`wt.exe`) no diretório atual.

## 🚀 Como Usar

### Arquivos `.reg`
1. Baixe o arquivo desejado ou clone este repositório.
2. Dê um clique duplo no arquivo `.reg` que deseja aplicar.
3. Confirme a solicitação do Controle de Conta de Usuário (UAC) e a mensagem do Editor de Registro.
4. As alterações geralmente têm efeito imediato, mas em alguns casos pode ser necessário reiniciar o Windows Explorer ou o computador.

### Script `.bat`
- Execute o `start-terminal.bat` para abrir um terminal na pasta atual.

## ⚠️ Aviso Importante

**Modificar o Registro do Windows pode causar instabilidade no sistema se não for feito corretamente.**
- Recomenda-se criar um **Ponto de Restauração do Sistema** ou fazer um backup do registro antes de aplicar quaisquer alterações.
- Estes scripts são fornecidos "como estão", use por sua conta e risco.
