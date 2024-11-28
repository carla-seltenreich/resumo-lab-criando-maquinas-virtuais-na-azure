# Resumo do Lab: Criando Máquinas Virtuais na Azure

Este repositório contém o resumo do laboratório "Criando Máquinas Virtuais na Azure" realizado no programa de Microsoft Azure da DIO. Durante a atividade, explorei como criar máquinas virtuais (VMs) e as estratégias para garantir alta disponibilidade e desempenho confiável.

## Principais Aprendizados

1. **O que é SLA (Service Level Agreement):**
   - O SLA é um compromisso formal da Microsoft em relação à disponibilidade dos serviços no Azure.
   - Ele garante percentuais de tempo de atividade, como 99,9% ou 99,99%, dependendo da configuração escolhida.
   - Caso o SLA não seja cumprido, o cliente pode ser ressarcido pela Microsoft, mas isso não inclui falhas causadas por erros de configuração do cliente.

2. **Níveis de Garantia de SLA:**
   - **Máquinas Virtuais Individuais com Disco Premium:** Garantia de 99,9% de disponibilidade ao usar discos gerenciados Premium SSD.  
   - **Availability Sets (Conjuntos de Disponibilidade):** Garantia de 99,95% ao distribuir VMs entre múltiplos domínios de falha e atualização.  
   - **Availability Zones (Zonas de Disponibilidade):** Garantia de 99,99% ao implementar VMs em diferentes zonas dentro da mesma região.

3. **Impacto das Customizações:**
   - Configurações avançadas, como **Availability Sets** e **Availability Zones**, aumentam o SLA, mas também podem elevar os custos.
   - Discos Premium SSD oferecem maior resiliência e desempenho, sendo recomendados para aplicações críticas.

4. **Considerações Importantes:**
   - O SLA cobre apenas problemas atribuíveis ao Azure; interrupções causadas por configurações incorretas do cliente não estão incluídas.
   - É essencial planejar estratégias de disponibilidade considerando o impacto financeiro e as necessidades do serviço.

## Conclusão

Criar máquinas virtuais na Azure exige atenção às configurações de SLA para atender às necessidades do negócio. A plataforma oferece várias opções para aumentar a disponibilidade e resiliência, mas é importante equilibrar os custos e benefícios dessas escolhas. Essa atividade reforçou a importância de entender as ferramentas disponíveis e planejar soluções robustas para aplicações em nuvem.
