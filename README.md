# Brute-force
Este repositório contém scripts que servem para automatizar os processos de pesquisa de DNS, DNS reverso e pesquisa de subdomínios. O objetivo é facilitar a vida dos pentesters.

**DNS-reverso**: Para usar este código, digite: _./dnsreverse.txt 200.221.2._
Este script buscará nomes em todos os IPs dentro da faixa de IP começando em 200.221.2 e retornará o resultado completo na tela.

**Busca por subdomínios**: Para usar esse script, digite: _./subdomains.sh_ _site.com.br_
É útil ressaltar que sub-domains.txt é um arquivo de lista de palavras (wordlist), que pode ser baixado da internet ou criado por você. Você pode usar qualquer outra lista de palavras.

**Transferência de zona**: Este script consultará o NS do domínio especificado; depois disso, forçará a transferência em todos os NS encontrados. Para executar o script, digite: _./zone-transfer.sh _www.site.com.br__
