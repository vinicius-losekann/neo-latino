# 🗂️ Neo Latino — Decisões de projeto

Registro das decisões que moldaram a língua: o que foi decidido e por quê.
O resultado de cada decisão já está aplicado na [gramática](gramatica.md) e no [vocabulário](vocabulario.md).

---

## ⚠️ Pendentes

| # | Tema | Problema | Opções em discussão |
|---|---|---|---|
| P12 | Acentos gráficos e `y` | Reanálise futura: avaliar se vale trocar `y`/`w` por `i`/`u` contextuais com acento nas exceções (`í`/`ú`), que deixa a grafia mais românica (`kual`, `audi`). Incluir o caso `yi`, que surge quando raízes em `y` viram verbo (`sonyo` → `sonyi`) e soa estranho; por isso o lote de verbos usou `inseni` e `gani` | manter `y`/`w`, ou `i`/`u` contextuais + `í`/`ú` |

---

## 🔎 Observações para revisão futura

Escolhas provisórias, que funcionam mas merecem ser revistas.

| Palavra | Observação |
|---|---|
| `onklo` (tio/tia) | Escolhido no lugar de `tio` (tío, tio, zio), que seria mais reconhecível para lusófonos e hispanófonos. Motivo: a raiz `ti-` coincide com o correlativo `ti` ("essa pessoa"), e o feminino `tino` ficaria ambíguo. Rever se o sistema de correlativos mudar ou se a colisão se mostrar inofensiva na prática. |
| `oro` (hora) | Em espanhol e italiano, "oro" é "ouro". Se adotado, "ouro" terá de ser `awro` (latim *aurum*). |
| Raiz `port-` | `porti` (carregar) ocupa a raiz, então "porta" virou `doro` (germânico) e "porto"/"aeroporto" ficaram sem palavra. Rever se surgir uma solução românica melhor. |
| `teo` (chá) | Parece o correlativo `te` (lá) + `-o`. Como correlativos não recebem terminações de classe nesse sentido, não há ambiguidade gramatical, mas vale observar no uso. |
| `lasi` (deixar) | A raiz `las` coincide com o pronome `las` (elas). |
| `pose` × `posi` | `pose` (depois, do prefixo `pos-`) e `posi` (poder) compartilham a raiz `pos`; derivados como `poso` ficariam ambíguos. |
| `dirito` (direito) | Pode ser lido como `dir` (de `diri`, dizer) + `-ito` = "o que foi dito". |
| `meso` × `mezo` | `meso` (mês) e `mezo` (meio) diferem só por s/z. Funciona pela regra fonêmica, mas é um par fácil de confundir. |

---

## ✅ Tomadas

| # | Tema | Decisão |
|---|---|---|
| P1 | Sons "nh" e "lh" | Os dígrafos `ni`/`li` foram eliminados, porque conflitavam com `li`, `libro`, `nigra` e `nonino`. Criou-se a semivogal **y** = /j/; "nh"/"lh" são aproximados por `ny`/`ly`, lidos letra por letra. O `i` é sempre vogal plena. |
| P2 | Pronomes | Mantidos `me/tu/nos/vos`, com plurais como palavras próprias. A proposta `nó/vó` foi descartada (acentos fora do alfabeto). O impessoal `on` não tem plural. |
| P3 | `r` × `rr` | O `rr` foi eliminado. Existe um único `r`, com pronúncia tolerante: tepe [ɾ] por padrão, mas também se aceitam [r], [ʁ] ou [h]. |
| P4 | Possessivos | Pronome + **-ya** (`meya`, `tuya`, `laya`, `nosya`…): terminam em -a, como adjetivos, e não variam. Com -o viram substantivo (`li meyo` = o meu). Evita o `laa` que surgiria com -a direto. |
| P5 | Numerais | Raízes curtas de base latina sem terminação (`un, du, tri, kwar, kin, ses, sep, ok, nwev, dek, sent, mil`). Compostos: multiplicação colada (`dudek`), soma separada (`dudek un`). Ordinais em -a (`dua`, `dudek-una`). Parentesco com `pra-` repetível (`pranono`). Palavras gramaticais curtas ficam isentas das terminações de classe. |
| P6 | Sintaxe | Ordem **SVO** fixa (pronomes objeto depois do verbo). Determinantes antes do substantivo, adjetivos depois. `no` antes do que nega. Perguntas de sim/não só por entonação e `?`, sem inversão. `ke` é o relativo universal. |
| P7 | Correlativos | Tabela regular: séries **kw-** (interrogativa/relativa), **t-** (demonstrativa), **al-** (indefinida), **nen-** (negativa), **tot-** (universal) × categorias **-i** (pessoa), **-o** (coisa), **-a** (qualidade), **-e** (lugar), **-an** (tempo), **-om** (modo), **-ant** (quantidade). Proximidade com **ik** (`to ik` = isto). Causa com a preposição **pro** (`pro kwo?`, `pro ke`). `kwal` foi substituído por `kwa`/`kwom`. |
| P8 | Substantivos abstratos | Raiz + **-o** = coisa ou instância com a qualidade (`bono`, um bem). Raiz + **-ezo** = a qualidade abstrata (`bonezo`, bondade). O `-eco` foi substituído por `-ezo` (de beleza, tristeza), evitando o "boneco". `velocidato` → `rapidezo`; `feliso`, `tristo`, `forto`, `alto`, `klaro`, `liberto`, `justiso`, `sapo` → formas em `-ezo`. |
| P9 | Léxico | Revisão pelo critério da P11. Trocadas: `ruga` → `ruja` (rouge, rojo), `jelba` → `amarila` (amarelo, amarillo), `varma`/`varmo` → `kalda`/`kaldo` (caldo, chaud, cald). Mantidas como exceções justificadas: `blua`, `griza`, `suno`, `bruna`, `nigra`, `frosto`, `vespero`, `tondro`, `domo`, `lakto`, `arbo`, `nubo`. |
| P10 | Semivogais e silabação | `i` e `u` são sempre vogais plenas. As semivogais são escritas **y** = /j/ e **w** = /w/ (`kual` → `kwal`, `audi` → `awdi`, `softuero` → `softwero`). Os acentos gráficos serão reanalisados na P12. |
| P11 | Identidade | Língua auxiliar internacional, público pan-românico. Princípios: 100% regular, gênero neutro por padrão, vocabulário de base latina (outra origem só quando mais lógica ou muito popular) e teclado ASCII. Ver [Identidade](gramatica.md#-identidade). |
| P13 | Conjunção "ou" | Passa a ser **o** (como no espanhol e no italiano), em vez de `ou`, que pela P10 teria duas sílabas. |
| P14 | Preposição "de" | Um único **de** para posse, conteúdo/matéria, assunto, origem e data, como no português, espanhol e francês. Datas com cardinal: `dek kin de sesameso`. Preposição e artigo nunca se contraem (`de li`, `a li`, `in li`). |
| P15 | Reflexivo e recíproco | Reflexivo **si** só na 3ª pessoa e no impessoal (*Le lavin si*); na 1ª e na 2ª usa-se o próprio pronome (*Me lavin me*). Possessivo reflexivo **siya**. Recíproco: *li unos … li altros*. O `se` continua sendo a conjunção condicional. Surgiu no teste de tradução. |
| P16 | Comparação | **pyu** (do italiano *più*) e **meno** + **ke**: *pyu forta ke*. Superlativo com artigo: *li pyu forta*. Igualdade com os correlativos *tant … kwant*. Surgiu no teste de tradução. |
| P17 | "Mas" e "até" | Conjunção **ma** (mas). **asta** (até), como preposição e em *asta ke* (até que). Surgiu no teste de tradução. |
| P18 | Nomes próprios e particípio anteposto | Nomes de pessoas e cidades mantêm a grafia original; nomes de países são adaptados + `-o` (*Brazilo*, *Portugalo*). Uma expressão com particípio pode vir no início da frase, separada por vírgula. Particípio + `-o` forma substantivo de agente (*viajato*, viajante). Surgiu no teste de tradução. |
| P19 | Correlativos e "cem" com vogal final | Os correlativos de tempo, modo e quantidade ganham vogal final, para soar mais românicos: `-an` → **-ando** (`kwando`, `tando`, `nenando`, `totando`), `-om` → **-omo** (`kwomo`, `tomo`), `-ant` → **-anto** (`kwanto`, `tanto`). O numeral 100 passa de `sent` a **sento** (`dusento`, `trisento`), e se comporta como raiz `sent-` + `-o` (ordinal `senta`, `sentanyo`). "Dezena" e "centena" passam a `dekaro` e `sentaro` (`-aro` = grupo), no lugar de `deko` e `sento`. Atualiza a P5 e a P7. |
