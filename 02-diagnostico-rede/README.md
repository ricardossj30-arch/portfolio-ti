# Projeto 2 — Diagnóstico de Conectividade de Rede

## Objetivo

Verificar o funcionamento básico da conexão de rede utilizando ferramentas nativas do Windows.

## Ferramentas utilizadas

- `ipconfig /all`
- `nslookup`
- `ping`
- `tracert`

## Procedimentos realizados

1. Consulta das configurações do adaptador de rede.
2. Verificação da comunicação com o gateway local.
3. Teste de conectividade com endereços IP externos.
4. Verificação da resolução de nomes DNS.
5. Análise de perda de pacotes e tempo de resposta.

## Resultados observados

- O adaptador Wi-Fi Realtek RTL8852BE estava identificado no sistema.
- As configurações de rede apresentavam endereço IPv4, gateway e servidores DNS.
- Os testes realizados com `ping` para o gateway e endereços externos receberam respostas.
- O teste com 20 pacotes para `1.1.1.1` apresentou 0% de perda.
- O teste com 10 pacotes para `8.8.8.8` apresentou média de 7 ms e 0% de perda.
- Os testes de resolução DNS também retornaram resultados.
- O `tracert` apresentou alguns saltos sem resposta, o que não comprova, isoladamente, uma falha de conexão.

## Conclusão

Durante os testes, a conexão apresentou comunicação com o gateway e com destinos externos, além de resolução de nomes DNS funcional.

Não foi identificada uma falha conclusiva de conectividade durante as verificações realizadas. Os resultados representam apenas o período dos testes e não garantem estabilidade contínua da rede.

## Aprendizados

- Interpretação de configurações de rede no Windows.
- Verificação de conectividade com `ping`.
- Consulta de DNS com `nslookup`.
- Análise básica de rotas com `tracert`.
- Registro e interpretação de resultados técnicos.

---

*Projeto prático desenvolvido para fins de aprendizado em Tecnologia da Informação.*
