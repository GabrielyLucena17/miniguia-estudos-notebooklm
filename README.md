# miniguia-estudos-notebooklm
# Caderno Temático: Inside One Direction - A Trajetória dos Integrantes e Carreiras Solo

> *Projeto de curadoria, pesquisa e engenharia de prompts utilizando a Inteligência Artificial do NotebookLM para analisar a formação do One Direction e a transição dos integrantes para o cenário solo.*

**Link do Caderno no NotebookLM:** [Inside One Direction: The Journey of Louis, Niall, and Zayn](https://notebooklm.google.com/notebook/57a21ba8-9524-4ace-9d94-4d41a7e064b8)

---

## Contexto e Objetivos

### Contexto
O fenômeno pop **One Direction** marcou uma geração desde a sua formação no *The X Factor UK* em 2010. Com a pausa do grupo em 2016 e os desdobramentos recentes na vida e carreira de cada ex-membro, este projeto utiliza a IA generativa para organizar a cronologia do grupo, entender os momentos cruciais de transição e mapear a evolução artística individual de integrantes como Louis Tomlinson, Niall Horan, Zayn Malik, Harry Styles e Liam Payne.

### Objetivos de Estudo
- [x] Mapear o surgimento do One Direction no *The X Factor* até a fase de hiato e carreira solo.
- [x] Analisar os caminhos artísticos e diferenciais de cada ex-integrante em suas fases individuais.
- [x] Utilizar a engenharia de prompts no NotebookLM para consolidar resumos estruturados e um glossário sobre a cultura pop e indústria musical.

---

## Curadoria de Fontes

O projeto foi construído com base em uma curadoria rica de **30 fontes abertas** carregadas no NotebookLM, incluindo vídeos do YouTube, biografias e notícias da imprensa internacional e brasileira:

1.  **[MAKING of ONE DIRECTION: all FIVE Auditions and FIRST as a group!](https://www.youtube.com/watch?v=VclS_bw2oRo)** — *The X Factor UK (Vídeo)*
   - *Resumo:* Registra o momento histórico da audição individual de cada integrante e a formação do grupo pelos jurados.
2. **[One Direction: veja por onde andam ex-integrantes](https://www.cnnbrasil.com.br/pop/one-direction-veja-por-onde-andam-ex-integrantes/)** — *CNN Brasil (Notícia)*
   - *Resumo:* Panorama completo sobre as conquistas recentes e os rumos de cada integrante após 15 anos de formação da banda.
3. **[One Direction - Wikipédia](https://pt.wikipedia.org/wiki/One_Direction)** — *Wikipédia (Artigo)*
   - *Resumo:* Base histórica com a discografia, turnês globais e prêmios conquistados pelo grupo ao longo da carreira.
4. **[A HISTÓRIA do LOUIS TOMLINSON | FATOS E CURIOSIDADES](https://www.youtube.com/watch?v=F19D-lOlz3g)** — *YouTube (Vídeo)*
   - *Resumo:* Análise focada na trajetória de superação, composições e carreira solo de Louis Tomlinson.
5. **[A HISTÓRIA do ZAYN MALIK | FATOS E CURIOSIDADES](https://www.youtube.com/watch?v=qO-tvoRUDBg)** — *YouTube (Vídeo)*
   - *Resumo:* Detalha a saída bombástica de Zayn do grupo em 2015 e a construção de sua identidade R&B solo.

---

## Engenharia de Prompts & Troubleshooting ("Cicatrizes")

Nesta seção estão registradas as estratégias de instrução utilizadas no NotebookLM e os refinamentos efetuados durante a pesquisa:

### Prompt 1: Mapeamento de Transição
- **Prompt Inicial:** `"Me fale sobre a história do One Direction."`
- **Resultado Obtido:** Uma resposta genérica que focou apenas nos prêmios da banda e não detalhou a fase solo.
- **Troubleshooting / Ajuste:** Foi necessário especificar o recorte temporal e os membros de interesse.
- **Prompt Refinado:** `"Com base EXCLUSIVAMENTE nas fontes fornecidas, faça uma comparação entre a sonoridade e o estilo do OneDirection como grupo e a carreira solo de Zayn Malik e Louis Tomlinson, destacando motivos citados para as mudanças."`

### Prompt 2: Extração de Linha do Tempo
- **Prompt Inicial:** `"Quais foram as datas mais importantes?"`
- **Resultado Obtido:** A IA misturou datas de álbuns com datas de lançamentos de singles solo sem ordem cronológica.
- **Troubleshooting / Ajuste:** Adicionada instrução de formato estruturado (tabela e ordem cronológica).
- **Prompt Refinado:** `"Crie uma linha do tempo em formato de lista cronológica destacando os 5 momentos mais importantes do One Direction: formação, saídas de integrantes, hiato e marcos de carreira solo."`

---

## Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **A Formação (2010):** Niall Horan, Zayn Malik, Liam Payne, Harry Styles e Louis Tomlinson fizeram audições individuais no *The X Factor UK*. Unificados por Simon Cowell e Nicole Scherzinger, formaram o One Direction e tornaram-se um fenômeno global de boyband.
* **A Ruptura e o Hiato (2015-2016):** Zayn Malik deixou o grupo em março de 2015 buscando um estilo de vida e música mais pessoal. Em janeiro de 2016, o grupo iniciou um hiato indeterminado.
* **Carreiras Solo e Identidade Artística:** Cada membro seguiu gêneros musicais distintos — Harry Styles no Pop/Rock Psicodélico, Zayn Malik no R&B/Pop, Niall Horan no Folk Pop, Louis Tomlinson no Indie/Britpop e Liam Payne no Pop/Urban.

### 2. Glossário de Conceitos Aprendidos
| Termo | Definição Consolidada |
| :--- | :--- |
| **Boyband** | Grupo vocal masculino jovem montado geralmente por audições para focar em harmonias e apelo pop. |
| **Hiato (Indefinido)** | Pausa temporária nas atividades do grupo sem anúncio formal de término definitivo. |
| **X Factor UK** | Reality show britânico de talentos musicais que serviu de berço para a formação da banda em 2010. |
| **Directioners** | Nome oficial dado ao fã-clube global dedicado ao One Direction. |

### 3. Conjunto de Prompts Reutilizáveis
Estes prompts podem ser reusados no NotebookLM para futuras análises sobre o tema:

1.  **Para Análise de Discografia:**
   `"Com base nas fontes, liste todos os álbuns citados do One Direction e aponte qual foi o impacto de cada um no topo das paradas."`
2. **Para Estudo de Membro Específico:**
   `"Resuma a trajetória de [Nome do Integrante], citando sua participação em composições no grupo e seu primeiro single solo de sucesso."`
3.  **Para Teste de Conhecimento (Quiz):**
   `"Elabore 5 perguntas de múltipla escolha com gabarito ao final sobre curiosidades das audições do X Factor contidas nas fontes."`
