# Modelação Ecológica Aplicada à Ria Formosa

Simulador interativo de construção progressiva (4 níveis de complexidade) desenvolvido para a palestra de **Mestrado em Biologia Marinha**.

🔗 **Acesso direto à aplicação (GitHub Pages):**  
`https://jmjaneiro.github.io/ria-formosa-ecosim/`

---

## Estrutura Pedagógica (4 Níveis Progressivos)

1. **Nível 1 • Bioenergética Individual (Modelo DEB — Kooijman, 2000):**
   * Simulação anual do crescimento de **1 único indivíduo** de amêijoa-boa (*Ruditapes decussatus*) em gramas ($\text{g}$) e comprimento de concha ($\text{mm}$, relação alométrica de Gaspar et al., 2001), desde semente comercial ($3.5\text{ g}$, $\sim 22\text{ mm}$) sob disponibilidade alimentar não limitante.
   * Permite analisar a depressão metabólica estival quando a temperatura intertidal excede o limiar térmico superior ($26.8\,^\circ\text{C}$; Sobral & Widdows, 1997).
2. **Nível 2 • Acoplamento Físico-Biológico (Prisma de Maré e Microfitobentos):**
   * Integra o tempo de residência hidrodinâmico ($\tau$) e a densidade de sementeira ($\text{ind/m}^2$).
   * Reflete o efeito tampão do elevado prisma de maré da Ria Formosa ($50\text{–}75\%$ de renovação por ciclo semidiurno) e a ressuspensão de diatomáceas bênticas (**microfitobentos — MPB**; Brito et al., Newton & Mudge).
3. **Nível 3 • Escala Populacional e Ostreicultura ($\text{kg/m}^2$):**
   * Transição da escala individual ($\text{g/ind.}$) para a biomassa populacional por unidade de área ($\text{kg/m}^2 = \text{Densidade} \times \text{Peso Individual} / 1000$), avaliando a partilha trófica entre *Ruditapes decussatus* e mesas de ostra-do-pacífico (*Magallana gigas*).
4. **Nível 4 • Acoplamento Pelágico-Bentónico e Conservação (*Zostera noltei*):**
   * Simula o efeito da biodeposição (fezes e pseudofezes) e da excreção de amónia ($\text{NH}_4^+$) pelos bivalves em conjunto com cargas externas de azoto ($\text{DIN}$), modelando a competição entre pradarias marinhas protegidas (*Zostera noltei*) e macroalgas oportunistas (*Ulva* spp.) e o regime de oxigénio dissolvido noturno.

---

## Execução Local

Basta abrir o ficheiro `index.html` em qualquer navegador moderno (sem dependências externas).
