# Automated and Context-Aware Repair of Color-Related Accessibility Issues for Android Apps (IRIS)
Zhang, Yuxin; Chen, Sen; Fan, Lingling; Chen, Chunyang; Li, Xiaohong. "Automated and Context-Aware Repair of Color-Related Accessibility Issues for Android Apps." In: ESEC/FSE 2023. doi: [10.1145/3611643.3616329](https://doi.org/10.1145/3611643.3616329).

## 1. Fichamento de Conteúdo
O trabalho apresenta o IRIS, primeira abordagem automatizada voltada a reparar problemas de contraste de texto e de imagem em apps Android, preservando o estilo visual original. Os autores argumentam que, apesar do avanço em detecção de acessibilidade, a reparação ficou atrás, e contrastes inadequados são recorrentes e severos. A solução constrói uma base de referência de cores extraída de 9.978 *apps* e usa critérios contextuais para selecionar substituições que mantêm consistência estética. Em seguida, localiza atributos a reparar no código de *layout* e aplica *patches*, gerando um APK corrigido. A avaliação em 100 *apps* reais reporta taxa de sucesso de 91,38% e tempo médio de 2,27 minutos por app; além disso, submetem 40 PRs, com 9 aceitos, e um estudo com usuários (visão normal e baixa visão) indica preservação do estilo e melhora de legibilidade. Entre limitações, o IRIS depende de relatórios de ferramentas de detecção e tem restrições com *Jetpack/compose*. O artigo evidencia que reparo automatizado orientado a contexto pode reduzir custo de retrabalho e acelerar conformidade com diretrizes (p.ex., WCAG).

## 2. Fichamento Bibliográfico
* Definição do problema: reparo de contraste (texto e imagem) em *apps* Android; foco em manter o estilo (Seções 1–2).
* Técnica de seleção de cores baseada em contexto + base de referência construída a partir de 9.978 *apps* (Seção 2.1/Metodologia).
* Localização de atributos nos arquivos de *layout* e geração de APK reparado (Seção 3–4).
* Resultados: 91,38% de sucesso e 2,27 min/*app*; 40 PRs enviados, 9 aceitos; estudo com usuários (Seção 4).
* Limitações: dependência de *reports* de detecção; restrições com *bounds* e *Jetpack* (Seção 5.1–5.2).

## 3. Fichamento de Citações
* _"We propose Iris, an automated and context-aware repair method to fix the color-related accessibility issues.”_
* _"Iris performs a high repair success rate of 91.38% and costs 2.27 minutes per app on average.”_
* _"The visual presentation of text … has a contrast of at least 4.5:1 … large-scale text … at least 3:1 (WCAG).”_