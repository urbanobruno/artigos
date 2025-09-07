# AccessiText: Automated Detection of Text Accessibility Issues in Android Apps
Alshayban, Abdulaziz; Malek, Sam. "AccessiText: Automated Detection of Text Accessibility Issues in Android Apps." In: ESEC/FSE 2022. doi: [10.1145/3540250.3549118](https://doi.org/10.1145/3540250.3549118).

## 1. Fichamento de Conteúdo
Os autores estudam empiricamente cinco classes de problemas de acessibilidade de texto em apps móveis relacionados ao uso do Serviço de Redimensionamento de Texto (TSAS) e propõem o AccessiText para detectá-los automaticamente. A partir de mais de 600 relatos de usuários (*reviews* e Twitter), categorizam padrões como visões irrespondíveis, elementos sobrepostos, partes recortadas e truncamento. A técnica combina *screenshots* e metadados obtidos via análise dinâmica para aplicar heurísticas que refletem as classes identificadas. Em 30 apps reais, a ferramenta alcança precisão média de 88,27% e revocação de 95,76% na detecção. O estudo discute causas (ex.: uso indevido de `dp` em vez de `sp`) e impactos (p. ex., impossibilidade de completar tarefas). O trabalho destaca que compatibilidade com TSAS exige não só habilitar fontes escaláveis, mas também projetar *layouts* resilientes e testá-los com tamanhos grandes. A contribuição posiciona a detecção automatizada como etapa essencial antes do reparo automatizado e fornece base taxonômica útil ao tema do TCC.

## 2. Fichamento Bibliográfico
* TSAS (*Text Scaling Assistive Service*) e classes de problemas: *unresponsive, overlapping, cropped, truncated, missing views* (Seções 1 e 3.2).
* Metodologia: mineração de *reviews* (Android/iOS) e Twitter; análise manual para taxonomia (Seção 3.1–3.2).
* AccessiText: análise dinâmica + heurísticas sobre *screenshots* e metadados (Seção 4).
* Resultados: precisão 88,27% e revocação 95,76% em 30 *apps* (Resumo/Seção 5).
* Boas práticas: uso de `sp` em vez de `dp`; conformidade WCAG e *guidelines* Android/iOS (Seções 2 e 3).

## 3. Fichamento de Citações
* _"This paper presents AccessiText, an automated testing technique for text accessibility issues arising from incompatibility between apps and TSAS.”_
* _"identify five different types of text accessibility [issues] by analyzing more than 600 candidate issues reported by users.”_
* _"achieving 88.27% precision and 95.76% recall on average in detecting text accessibility issues.”_