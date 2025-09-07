# Don’t Do That! Hunting Down Visual Design Smells in Complex UIs against Design Guidelines
Yang, B.; Xing, Z.; Xia, X.; Hassan, A.E.; Li, S. "Don’t Do That! Hunting Down Visual Design Smells in Complex UIs against Design Guidelines." In: ICSE 2021. doi: [10.1109/ICSE43902.2021.00075](https://doi.org/10.1109/ICSE43902.2021.00075).

## 1. Fichamento de Conteúdo
O artigo estuda “cheiros” de *design* visual em UIs Android tomando as diretrizes “don’t” do *Material Design* como base e introduz a ferramenta UIS-Hunter para detecção automática. A partir de 93 diretrizes explícitas (17 componentes), os autores definem informações atômicas (metadados de componentes, tipografia, iconografia, cor, bordas) e condições de violação em lógica de primeira ordem. Avaliando 60.756 telas de 9.286 *apps*, mostram que 2.587 *apps* têm ao menos uma violação; a ferramenta obteve precisão 0,81 e revocação 0,90. Dois estudos de usuário indicam que a ferramenta supera avaliadores humanos e que os cheiros detectados são considerados severos pela maioria dos usuários. O trabalho fundamenta a priorização de problemas de usabilidade/estética com forte impacto perceptual e sugere integração “*just-in-time*” em *designers*/IDE para reduzir retrabalho – alinhado ao foco do TCC em classificar severidade e estimar custo/benefício de correções.

## 2. Fichamento Bibliográfico
* Definição de '*UI design smells*' baseada nas diretrizes '*don’t*' do *Material Design* (Seção I–II).
* UIS-Hunter: extração multi-modal e condições de violação em primeira ordem (Seção III).
* *Dataset*: 60.756 UIs de 9.286 *apps*; 2.587 *apps* com violações (Seção I/Resultados).
* Métricas: precisão 0,81; revocação 0,90; F1=0,87 (Resumo/Resultados).
* Aplicações: galeria de diretrizes; integração *just-in-time* para evitar retrabalho (Seções V e VIII).

## 3. Fichamento de Citações
* _"We design an automated UI design smell detector (UIS-Hunter).”_
* _"UIS-Hunter achieves a precision of 0.81 and a recall of 0.90.”_
* _"7,497 UIs of 2,587 apps have at least one violation of some Material Design guidelines.”_