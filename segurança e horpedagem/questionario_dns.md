

## 🧠 Questões Teóricas sobre DNS

**1.** O que significa a sigla DNS e qual é sua principal função?

DNS significa *Domain Name System* (Sistema de Nomes de Domínio). Sua principal função é traduzir nomes de domínio (como [www.google.com](http://www.google.com)) em endereços IP, que são usados pelos computadores para se comunicarem na rede.

**2.** Por que o DNS foi criado? Qual problema ele resolveu na Internet?

O DNS foi criado para facilitar o uso da Internet, pois memorizar endereços IP numéricos era difícil para os usuários. Ele resolveu o problema de associar nomes fáceis de lembrar a endereços IP.

**3.** O que é um nome de domínio? Dê um exemplo.

Um nome de domínio é o endereço textual que identifica um site na Internet.
Exemplo: [www.example.com](http://www.example.com)

**4.** Qual é a função de um servidor DNS?

A função de um servidor DNS é responder às consultas de resolução de nomes, informando o endereço IP correspondente a um nome de domínio.

**5.** Cite dois tipos de registros DNS e explique brevemente um deles.
Registros A e MX.
O registro **A** associa um nome de domínio a um endereço IPv4.

---

## 🪟 Questões sobre DNS no Windows

**6.** Qual comando do Windows é utilizado para testar a resolução de nomes DNS?

O comando `nslookup`.

**7.** Para que serve o comando `ipconfig /all` em relação ao DNS?

Ele exibe informações detalhadas da configuração de rede, incluindo os servidores DNS configurados no sistema.

**8.** Qual comando pode ser usado para limpar o cache DNS no Windows?

O comando `ipconfig /flushdns`.

**9.** Onde o Windows armazena temporariamente as informações de DNS?

No cache DNS do sistema operacional.

**10.** Ao acessar um site no Windows e ocorrer erro de DNS, cite uma possível causa.

Uma possível causa é o servidor DNS estar indisponível ou mal configurado.

---

## 🐧 Questões sobre DNS no Linux

**11.** Qual arquivo do Linux contém os servidores DNS configurados no sistema?

O arquivo `/etc/resolv.conf`.

**12.** Qual comando pode ser usado no Linux para consultar registros DNS de um domínio?

O comando `dig` (ou `nslookup`).

**13.** Para que serve o comando `ping` em relação ao DNS?

Ele verifica se um nome de domínio está sendo resolvido corretamente para um endereço IP e testa a conectividade.

**14.** Qual a função do arquivo `/etc/hosts` no processo de resolução de nomes?

Ele permite mapear manualmente nomes de domínio para endereços IP, sendo consultado antes do DNS.

**15.** Cite uma diferença básica entre a configuração de DNS no Windows e no Linux.

No Windows, o DNS é configurado principalmente pela interface gráfica ou `ipconfig`, enquanto no Linux é configurado por arquivos de texto como `/etc/resolv.conf`.


