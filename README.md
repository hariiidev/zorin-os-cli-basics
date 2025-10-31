# 🐧 Comandos Essenciais do Terminal Linux

**Guia Rápido e Minimalista para Iniciantes (Zorin OS / Debian-based)**

---

## 🧭 Navegação

| Comando | Descrição | Exemplo |
| :--- | :--- | :--- |
| `clear` | Limpa a tela. | `clear` |
| `pwd` | Mostra o caminho da pasta atual. | `pwd` |
| `ls` | Lista arquivos e pastas. | `ls -l` |
| `cd <pasta>` | Entra numa pasta. | `cd Documentos` |
| `cd ..` | Volta para a pasta anterior. | `cd ..` |
| `cd ~` | Vai para o diretório Home. | `cd ~` |

---

## 📁 Manipulação

**Cuidado:** `rm` apaga permanentemente.

| Comando | Descrição | Exemplo |
| :--- | :--- | :--- |
| `mkdir <nome>` | Cria uma nova pasta. | `mkdir Projeto` |
| `touch <nome>` | Cria um arquivo vazio. | `touch nota.txt` |
| `cat <arquivo>` | Exibe o conteúdo de um arquivo. | `cat nota.txt` |
| `cp <origem> <destino>` | Copia arquivos/pastas. | `cp a.txt b.txt` |
| `mv <origem> <destino>` | Move ou renomeia. | `mv a.txt novo.txt` |
| `rm <arquivo>` | Remove um arquivo. | `rm lixo.txt` |
| `rm -r <pasta>` | Remove uma pasta e seu conteúdo. | `rm -r Antiga` |

---

## ⚙️ Sistema & Ajuda

| Comando | Descrição | Exemplo |
| :--- | :--- | :--- |
| `sudo <comando>` | Executa como administrador (requer senha). | `sudo apt update` |
| `apt update` | Atualiza a lista de pacotes. | `sudo apt update` |
| `apt upgrade` | Atualiza os pacotes instalados. | `sudo apt upgrade` |
| `man <comando>` | Abre o manual do comando (pressione `q` para sair). | `man cd` |

---

## ⚡ Atalhos Úteis

* **`Tab`**: Autocompleta nomes de comandos e arquivos. Use sempre!
* **`Ctrl + C`**: Interrompe o comando atual.
* **`Seta para Cima`**: Repete o comando anterior.
