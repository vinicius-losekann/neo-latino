# 🗂️ Neo Latino — Decisões de projeto

Registro das decisões que moldaram a língua: o que foi decidido e por quê.
O resultado de cada decisão já está aplicado na [gramática](gramatica.md) e no [vocabulário](vocabulario.md).

---

## ⚠️ Pendentes

Nenhuma decisão pendente no momento.

### 📝 Backlog de vocabulário

Palavras que faltam e ainda não têm proposta aprovada.

Nenhuma no momento. "Curar" foi resolvido na P27 (`sani`).

---

## 🔎 Observações para revisão futura

Escolhas provisórias, que funcionam mas merecem ser revistas.

| Palavra | Observação |
|---|---|
| `onklo` (tio/tia) | Escolhido no lugar de `tio` (tío, tio, zio), que seria mais reconhecível para lusófonos e hispanófonos. Motivo: a raiz `ti-` coincide com o correlativo `ti` ("essa pessoa"), e o feminino `tino` ficaria ambíguo. Rever se o sistema de correlativos mudar ou se a colisão se mostrar inofensiva na prática. |
| `oro` (hora) | Em espanhol e italiano, "oro" é "ouro". Por isso "ouro" passou a ser `awro` (latim *aurum*, texto 6). |
| Raiz `port-` | `porti` (carregar) ocupa a raiz, então "porta" virou `doro` (germânico) e "porto"/"aeroporto" ficaram sem palavra. Rever se surgir uma solução românica melhor. |
| `teo` (chá) | Parece o correlativo `te` (lá) + `-o`. Como correlativos não recebem terminações de classe nesse sentido, não há ambiguidade gramatical, mas vale observar no uso. |
| `lasi` (deixar) | A raiz `las` coincide com o pronome `las` (elas). |
| `pose` × `posi` | `pose` (depois, do prefixo `pos-`) e `posi` (poder) compartilham a raiz `pos`; derivados como `poso` ficariam ambíguos. |
| `dirito` (direito) | Pode ser lido como `dir` (de `diri`, dizer) + `-ito` = "o que foi dito". |
| `meso` × `mezo` | `meso` (mês) e `mezo` (meio) diferem só por s/z. Funciona pela regra fonêmica, mas é um par fácil de confundir. |
| `robo` (vestido) | Ocupa a raiz `rob-`, então "roubar" terá de ser outra raiz (sugestão: `furti`, de furtar, furto). Base só no francês *robe* e no romeno *rochie*. |
| `jupo` (saia) | Pouco pan-românico (francês *jupe*). Alternativa: `fusto` (romeno *fustă*). |
| `kalsuro` (sapato) | Escolhido porque `sapato` colidiria com `sapi` + `-ato` ("o que sabe"). Menos reconhecível para lusófonos e hispanófonos. |
| `xapelo` (chapéu) | Usa `x` para não colidir com `kapelo` (cabelo). |
| `avokato`, `soldato` | Terminam como particípio ativo em `-ato`. Hoje não há ambiguidade, porque não existem os verbos `avoki` e `soldi`. Alternativa para advogado: `diritisto`. |
| `pari` × `parli` | `pari` (parecer) e `parli` (falar) diferem só pelo `l`: `paren` × `parlen`. |
| `korti` × `kurta` | `korti` (cortar) e `kurta` (curto) são parecidos, mas as raízes são diferentes. Pela P27, `kurti` seria "encurtar". |
| `famo` (fome) | Se um dia existir "fama", vai colidir. |
| `doloro` × `doro` | `doloro` (dor) e `doro` (porta) são parecidos, mas as raízes são diferentes. |

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
| P12 | Acentos gráficos e `yi` | **Mantidos `y`/`w`**, sem acentos. A alternativa de usar `i`/`u` contextuais com `í`/`ú` foi descartada: obrigaria a acentuar cerca de 20 palavras (`dío`, `blúa`, os dias da semana), mudaria a leitura do condicional `-ia` e quebraria o teclado ASCII (P11), em troca de um ganho só visual (`kual`, `audi`). O encontro **yi** passa a ser normal: `banyi` (banhar) = "banhi", `sonyi` (sonhar) = "sonhi". Não é mais preciso trocar de raiz para evitá-lo; `inseni` e `gani` ficam como estão, porque são raízes próprias. Com isso, `odi`/`odo` passaram a `odyi`/`odyo` (odiar/ódio), e entraram `sonyi` (sonhar) e `banyi` (banhar). |
| P13 | Conjunção "ou" | Passa a ser **o** (como no espanhol e no italiano), em vez de `ou`, que pela P10 teria duas sílabas. |
| P14 | Preposição "de" | Um único **de** para posse, conteúdo/matéria, assunto, origem e data, como no português, espanhol e francês. Datas com cardinal: `dek kin de sesameso`. Preposição e artigo nunca se contraem (`de li`, `a li`, `in li`). |
| P15 | Reflexivo e recíproco | Reflexivo **si** só na 3ª pessoa e no impessoal (*Le lavin si*); na 1ª e na 2ª usa-se o próprio pronome (*Me lavin me*). Possessivo reflexivo **siya**. Recíproco: *li unos … li altros*. O `se` continua sendo a conjunção condicional. Surgiu no teste de tradução. |
| P16 | Comparação | **pyu** (do italiano *più*) e **meno** + **ke**: *pyu forta ke*. Superlativo com artigo: *li pyu forta*. Igualdade com os correlativos *tant … kwant*. Surgiu no teste de tradução. |
| P17 | "Mas" e "até" | Conjunção **ma** (mas). **asta** (até), como preposição e em *asta ke* (até que). Surgiu no teste de tradução. |
| P18 | Nomes próprios e particípio anteposto | Nomes de pessoas e cidades mantêm a grafia original; nomes de países são adaptados + `-o` (*Brazilo*, *Portugalo*). Uma expressão com particípio pode vir no início da frase, separada por vírgula. Particípio + `-o` forma substantivo de agente (*viajato*, viajante). Surgiu no teste de tradução. |
| P19 | Correlativos e "cem" com vogal final | Os correlativos de tempo, modo e quantidade ganham vogal final, para soar mais românicos: `-an` → **-ando** (`kwando`, `tando`, `nenando`, `totando`), `-om` → **-omo** (`kwomo`, `tomo`), `-ant` → **-anto** (`kwanto`, `tanto`). O numeral 100 passa de `sent` a **sento** (`dusento`, `trisento`), e se comporta como raiz `sent-` + `-o` (ordinal `senta`, `sentanyo`). "Dezena" e "centena" passam a `dekaro` e `sentaro` (`-aro` = grupo), no lugar de `deko` e `sento`. Atualiza a P5 e a P7. |
| P20 | Orações sem sujeito | Os verbos de clima e o `esti` existencial não têm sujeito: *Pluven.* (Chove.), *Esten un libro.* (Há um livro.). É a única exceção à regra do sujeito explícito. Descartados: o sujeito vazio `to` e a paráfrase com sujeito real. Surgiu no teste de tradução (texto 4). |
| P21 | Meio e instrumento | **per** passa a cobrir, além do agente da passiva, o meio e o instrumento: *per buso* (de ônibus), *per kulyero* (com a colher), como em latim, italiano e esperanto. `kon` continua sendo só companhia. Surgiu no teste de tradução (texto 4). |
| P22 | Subjuntivo | O imperativo **-u** serve também de volitivo, em orações com `ke` depois de verbos de vontade, pedido ou preferência: *Me volen ke tu venu.* Não há sufixo novo. Nas outras subordinadas usa-se o tempo normal. Surgiu no teste de tradução (texto 4). |
| P23 | "Enquanto" | Conjunção **mentre** (*mentre*, *mientras*). Descartados: `dum` (pouco transparente) e `kwando` com particípio (perde o contraste). Surgiu no teste de tradução (texto 5). |
| P24 | Dupla negação | Não existe. Os correlativos **nen-** já negam a frase, então não levam `no`: *Me tenin neno.* (Eu não tinha nada.) A concordância negativa românica foi descartada porque criaria uma regra condicional. Surgiu no teste de tradução (texto 5). |
| P25 | "Pois", "portanto" | Conjunção **dunke** (*dunque*, *donc*), só no sentido de conclusão. O `tando` continua sendo só temporal. Surgiu no teste de tradução (texto 5). |
| P26 | "Todo o" × "cada" | `tota` + singular = cada (*tota estivo*); `tota` + plural = todos (*tota omos*); **li tota** + singular = inteiro (*li tota estivo*). Não foi preciso criar `intera`. Surgiu no teste de tradução (texto 5). |
| P27 | Adjetivo → verbo | Raiz de adjetivo + **-i** = "tornar X", transitivo: `kaldi` (aquecer), `sani` (curar), `liberi` (libertar). "Estar X" = `esti` + adjetivo; "ficar X" = `deveni` + adjetivo ou reflexivo (`kaldi si`). Foi descartado o sentido "estar X", que repetiria o que `esti` + adjetivo já faz. Resolve o "curar" do backlog. Surgiu no teste de tradução (texto 6). |
| P28 | Sotaques | Cada som tem uma pronúncia padrão e pode ter variantes toleradas, como já acontecia com o `r` (P3). **Critério:** a variante é aceita quando não faz dois sons distintos da língua soarem iguais. Toleradas: `e`/`o` abertos, as variantes do `r` e a vogal nasalizada antes de `m`/`n`. Não toleradas: reduzir o `o` e o `e` finais a "u" e "i" (confundiria `-o`/`-u` e `-e`/`-i`) e sonorizar o `s` entre vogais (confundiria `meso`/`mezo`). Ver [Sotaques](gramatica.md#sotaques). |
