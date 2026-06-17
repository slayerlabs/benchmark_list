# Benchmarki Bielika

Tabela benchmarków, na których raportowano wyniki modeli z rodziny Bielik, wraz ze statusem dostępności, linkiem do ewaluatora, linkiem do danych oraz źródłem potwierdzającym ewaluację Bielika.

## Legenda statusów

| Status     | Znaczenie                                                                                                                                             |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| `open`     | Dane i/lub harness są publiczne, więc benchmark można praktycznie pobrać i uruchomić.                                                                 |
| `partial`  | Część benchmarku jest publiczna, ale pełna reprodukcja może zależeć od dodatkowej konfiguracji, modelu-sędziego, subsetu albo niedostępnego elementu. |
| `closed`   | Nie znaleziono publicznych danych/testów/scoringu pozwalających samodzielnie przeliczyć wynik.                                                        |
| `archived` | Benchmark albo leaderboard jest publiczny, ale archiwalny lub nieutrzymywany.                                                                         |

## Tabela benchmarków

| Benchmark                                      | Kategoria | Model                         | Wynik/Maks                | Ewaluator                                                                                | Dane                                                                                               | Źródło                                                                            |
| ---------------------------------------------- | --------- | ----------------------------- | ------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Open PL LLM Leaderboard                        | open      | Bielik-11B-v3.0-Instruct      | 65.93 / 100               | [ewaluator](https://huggingface.co/spaces/speakleash/open_pl_llm_leaderboard)            | [dane / taski](https://huggingface.co/spaces/speakleash/open_pl_llm_leaderboard/tree/main)         | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| Polish MT-Bench                                | partial   | Bielik-11B-v2.3-Instruct      | 8.56 / 10                 | [ewaluator](https://huggingface.co/spaces/speakleash/mt-bench-pl)                        | [dane](https://huggingface.co/spaces/speakleash/mt-bench-pl/tree/main/data/mt_bench)               | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| Polish EQ-Bench                                | closed    | Bielik-11B-v3.0-Instruct      | 71.20 / 100               | [ewaluator](https://huggingface.co/spaces/speakleash/polish_eq-bench)                    | N/A                                                                                                | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| CPTU-Bench / CPTUB                             | closed    | Bielik-11B-v3.0-Instruct      | 3.73 / 5                  | [ewaluator](https://huggingface.co/spaces/speakleash/cptu_bench)                         | N/A                                                                                                | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| Polish Medical Leaderboard                     | closed      | Bielik-11B-v3.0-Instruct      | 50.21 / 100               | [ewaluator](https://huggingface.co/spaces/speakleash/polish_medical_leaderboard)         | [dane](https://huggingface.co/datasets/speakleash/PES-2018-2022)                                   | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| PLCC                                           | open      | Bielik-11B-v3.0-Instruct      | 71.83 / 100               | [ewaluator](https://huggingface.co/spaces/sdadas/plcc)                                   | [dane](https://huggingface.co/spaces/sdadas/plcc/blob/main/data.json)                              | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| LLMzSzŁ                                        | open      | Bielik-11B-v2.1-Instruct      | 57.52 / 100               | [ewaluator](https://huggingface.co/spaces/amu-cai/LLMZSZL_Leaderboard)                   | [dane](https://huggingface.co/datasets/amu-cai/llmzszl-dataset)                                    | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| European LLM Leaderboard                       | open      | Bielik-11B-v2.3-Instruct      | 0.66 / 1.00               | [ewaluator](https://huggingface.co/spaces/speakleash/european_leaderboard_bielik)        | [dane](https://huggingface.co/collections/openGPT-X/eu20-benchmarks-67093b13db8ff192dc39312d)      | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| EuroEval                                       | open      | Bielik-11B-v2.3-Instruct      | rank 2.22; PL 1.41        | [ewaluator](https://euroeval.com/leaderboards/Multilingual/european/)                    | [dane](https://euroeval.com/datasets/)                                                             | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| Open LLM Leaderboard v1                        | archived  | Bielik-11B-v3.0-Instruct      | 72.45 / 100               | [ewaluator](https://huggingface.co/spaces/open-llm-leaderboard-old/open_llm_leaderboard) | [dane / opis](https://huggingface.co/docs/leaderboards/en/open_llm_leaderboard/archive)            | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| MMLU                                           | open      | Bielik-11B-v3.0-Instruct      | 71.11 / 100               | [dataset](https://huggingface.co/datasets/cais/mmlu)                                     | [dane](https://huggingface.co/datasets/cais/mmlu)                                                  | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| ARC Challenge                                  | open      | Bielik-11B-v3.0-Instruct      | 64.59 / 100               | [dataset](https://huggingface.co/datasets/allenai/ai2_arc)                               | [dane](https://huggingface.co/datasets/allenai/ai2_arc)                                            | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| GSM8K                                          | open      | Bielik-11B-v3.0-Instruct      | 85.60 / 100               | [dataset](https://huggingface.co/datasets/openai/gsm8k)                                  | [dane](https://huggingface.co/datasets/openai/gsm8k)                                               | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| HellaSwag                                      | open      | Bielik-11B-v3.0-Instruct      | 81.96 / 100               | [dataset](https://huggingface.co/datasets/Rowan/hellaswag)                               | [dane](https://huggingface.co/datasets/Rowan/hellaswag)                                            | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| TruthfulQA                                     | open      | Bielik-11B-v3.0-Instruct      | 54.25 / 100               | [dataset](https://huggingface.co/datasets/domenicrosati/TruthfulQA)                      | [dane](https://github.com/sylinrl/TruthfulQA)                                                      | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| WinoGrande                                     | open      | Bielik-11B-v3.0-Instruct      | 77.19 / 100               | [dataset](https://huggingface.co/datasets/allenai/winogrande)                            | [dane](https://huggingface.co/datasets/allenai/winogrande)                                         | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| Open LLM Leaderboard v2                        | partial   | Bielik-11B-v2.3-Instruct      | 28.33 / 100               | [ewaluator](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard)     | [harness](https://github.com/EleutherAI/lm-evaluation-harness/tree/main/lm_eval/tasks/leaderboard) | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| MixEval / MixEval-Hard                         | open      | Bielik-11B-v2.1-Instruct      | 74.6 / 100; 45.0 / 100    | [ewaluator](https://mixeval.github.io/)                                                  | [dane / repo](https://github.com/JinjieNi/MixEval)                                                 | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| BFCL                                           | partial   | Bielik-11B-v2.5-Instruct FC   | brak jednego wyniku       | [ewaluator](https://gorilla.cs.berkeley.edu/leaderboard.html)                            | [dane](https://huggingface.co/datasets/gorilla-llm/Berkeley-Function-Calling-Leaderboard)          | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| FLORES / FLORES200                             | open      | Bielik-11B-v3.0-Instruct      | 19.22 BLEU                | [ewaluator](https://huggingface.co/spaces/speakleash/european_leaderboard_bielik)        | [dane](https://huggingface.co/datasets/facebook/flores)                                            | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| BenCzechMark                                   | open      | Bielik-11B-v2.3-Instruct      | 49.5 / 100                | [ewaluator](https://huggingface.co/spaces/CZLC/BenCzechMark)                             | [dane](https://huggingface.co/datasets/CZLC/LLM_benchmark_data)                                    | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| Open PT LLM Leaderboard / Portuguese Benchmark | open      | Bielik-11B-v2.1/v2.2-Instruct | 73.45 / 100               | [ewaluator](https://huggingface.co/spaces/eduagarcia/open_pt_llm_leaderboard)            | [harness](https://github.com/eduagarcia/lm-evaluation-harness-pt)                                  | [raport](https://arxiv.org/html/2505.02410v2)                                     |
| INCLUDE-base-44                                | open      | Bielik-11B-v3.0-Instruct      | 64.8 / 100; PL 69.0 / 100 | [ewaluator](https://huggingface.co/spaces/speakleash/include-base-european-leaderboard)  | [dane](https://huggingface.co/datasets/CohereLabs/include-base-44)                                 | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| Belebele                                       | open      | Bielik-11B-v3.0-Instruct      | 82.98 / 100               | [ewaluator](https://huggingface.co/spaces/speakleash/belebele-european-leaderboard)      | [dane](https://huggingface.co/datasets/facebook/belebele)                                          | [raport](https://arxiv.org/pdf/2601.11579)                                        |
| COMPL-AI                                       | partial      | Bielik-11B-v2.3-Instruct      | N/A                       | [ewaluator](https://compl-ai.org/)                                                       | [repo](https://github.com/compl-ai/compl-ai/tree/main/src/compl_ai/tasks)                                                       | [ewaluacja](https://compl-ai.org/evaluations/SpeakLeash-Bielik-11B-v2.3-Instruct) |

## Opisy benchmarków

### Open PL LLM Leaderboard

Oficjalny polski leaderboard mierzący ogólne kompetencje NLP/LLM w języku polskim. Obejmuje m.in. analizę sentymentu, NER, klasyfikację tematów, czytanie ze zrozumieniem, QA/RAG, podobieństwo semantyczne, mowę nienawiści i streszczanie.

**Uwagi:** Wynik 5-shot; raport v3 podaje 65.93 dla wersji instruction-tuned. Benchmark składa się z wielu publicznych datasetów HF; dane nie są jednym plikiem w repo Space. Reprodukcja przez speakleash/lm-evaluation-harness branch polish4.

### Polish MT-Bench

Polska wersja benchmarku konwersacyjno-instrukcyjnego. Sprawdza m.in. pisanie, odgrywanie ról, ekstrakcję informacji, rozumowanie, matematykę, kodowanie, STEM i humanistykę. Ocena opiera się na modelu-sędzi.

**Uwagi:** `partial`, bo pełna reprodukcja zależy od modelu-sędziego i dokładnej konfiguracji oceny.

### Polish EQ-Bench

Polska adaptacja EQ-Bench. Mierzy inteligencję emocjonalną modelu: rozpoznawanie emocji, interpretowanie sytuacji interpersonalnych i rozumowanie o emocjach w kontekście rozmowy.

**Uwagi:** Oznaczone jako `closed`, ponieważ nie znaleziono jednoznacznego publicznego zestawu danych/testów i scoringu pozwalającego samodzielnie przeliczyć wynik.

### CPTU-Bench / CPTUB

Benchmark złożonego rozumienia tekstów po polsku. Sprawdza znaczenia ukryte, sarkazm, idiomy, frazeologię, wieloznaczność, podchwytliwe pytania i odporność na halucynacje.

**Uwagi:** Oznaczone jako `closed`, ponieważ nie znaleziono jednoznacznego publicznego zestawu danych/testów i scoringu pozwalającego samodzielnie przeliczyć wynik.

### Polish Medical Leaderboard

Polski benchmark medyczny oparty na pytaniach z Państwowego Egzaminu Specjalizacyjnego z lat 2018–2022. Sprawdza wiedzę medyczną i rozumowanie kliniczne po polsku.

**Uwagi:** Wynik 5-shot. Publiczny data.json zawiera 60 pytań; paper opisuje 600. Wygląda na subset, więc pełny oficjalny wynik nie jest w pełni odtwarzalny.

### PLCC

Benchmark polskiej kompetencji językowej i kulturowej. Obejmuje historię, geografię, kulturę i tradycję, sztukę i rozrywkę, gramatykę oraz słownictwo.

**Uwagi:** Raport v3 podaje 71.83%; raport v2 podaje 63.00% dla Bielik-11B-v2.2-Instruct.

### LLMzSzŁ

Benchmark oparty na polskich egzaminach krajowych, szkolnych i zawodowych z archiwów CKE. Sprawdza wiedzę i rozumowanie w wielu dziedzinach edukacyjnych i zawodowych.

### European LLM Leaderboard

Wielojęzyczny europejski benchmark używający zadań takich jak ARC, GSM8K, HellaSwag, MMLU i TruthfulQA w różnych językach europejskich.

**Uwagi:** Wynik 0.66 dotyczy polskich tasków. Raport podaje też wyniki dla języka niemieckiego i czeskiego.

### EuroEval

Europejski framework ewaluacyjny dla modeli językowych w wielu językach europejskich. Raportuje ranking; niższa wartość oznacza lepszy wynik.

**Uwagi:** Niższy wynik oznacza lepszą pozycję rankingową.

### Open LLM Leaderboard v1

Angielski zestaw benchmarków obejmujący ARC Challenge, HellaSwag, TruthfulQA, MMLU, WinoGrande i GSM8K. Sprawdza rozumowanie, wiedzę ogólną, prawdziwość odpowiedzi i matematykę.

**Uwagi:** Leaderboard jest archiwalny. Wynik instruction-tuned z raportu v3; raport v2 podaje 71.42 dla Bielik-11B-v2.5-Instruct.

### MMLU

Massive Multitask Language Understanding: szeroki test wiedzy i rozumowania z wielu dziedzin akademickich. W Bieliku raportowany jako komponent Open LLM Leaderboard v1.

### ARC Challenge

Zbiór pytań wielokrotnego wyboru z nauk ścisłych. Sprawdza logiczne rozumowanie i wiedzę naukową. W Bieliku raportowany jako komponent Open LLM Leaderboard v1.

### GSM8K

Grade School Math 8K: zadania tekstowe z matematyki szkolnej. Sprawdza rozumowanie krok po kroku i obliczenia. W Bieliku raportowany jako komponent Open LLM Leaderboard v1.

### HellaSwag

Test zdroworozsądkowego rozumienia scenariuszy: model wybiera najbardziej prawdopodobne zakończenie zdania lub historii. W Bieliku raportowany jako komponent Open LLM Leaderboard v1.

### TruthfulQA

Benchmark mierzący odporność modelu na popularne fałszywe przekonania i halucynacje. W Bieliku raportowany jako komponent Open LLM Leaderboard v1.

**Uwagi:** Metryka w tabeli: `truthfulqa_mc2`.

### WinoGrande

Benchmark rozwiązywania zdań z luką wymagających rozumienia kontekstu i zależności referencyjnych. W Bieliku raportowany jako komponent Open LLM Leaderboard v1.

### Open LLM Leaderboard v2

Trudniejsza wersja Open LLM Leaderboard. Obejmuje m.in. IFEval, BBH, MATH, GPQA, MuSR i MMLU-Pro, czyli instruction following, rozumowanie, matematykę i zaawansowaną wiedzę.

**Uwagi:** `partial`, ponieważ dostęp do GPQA jest ograniczony przez gating.

### MixEval / MixEval-Hard

Angielski benchmark złożony z wielu istniejących zadań. Ma dawać wyniki skorelowane z Chatbot Areną, ale w tańszy i bardziej odtwarzalny sposób.

**Uwagi:** Raport v2 podaje kilka wersji Bielika; w tabeli wpisano najlepszy wynik Bielika w tej tabeli.

### BFCL

Benchmark wywoływania narzędzi i funkcji/API. Sprawdza, czy model potrafi wygenerować poprawne wywołania funkcji. Używa m.in. metryk opartych na AST i zadań live/non-live.

**Uwagi:** `partial`, bo w raporcie Bielik był oceniany tylko na wybranych podzbiorach i nie podano jednego globalnego wyniku.

### FLORES / FLORES200

Benchmark tłumaczenia maszynowego dla wielu języków. W Bieliku użyty głównie do tłumaczeń między polskim a innymi językami europejskimi.

**Uwagi:** Wynik BLEU nie jest accuracy; maksimum 100 jest tylko teoretyczne.

### BenCzechMark

Benchmark skoncentrowany na języku czeskim. Zawiera 50 zadań w 8 kategoriach i sprawdza m.in. język czeski, matematykę, wiedzę faktograficzną, NER, NLI, czytanie ze zrozumieniem i sentyment.

**Uwagi:** Benchmark nie jest polski, ale raport v2 używa go do sprawdzenia transferu na język czeski.

### Open PT LLM Leaderboard / Portuguese Benchmark

Portugalski zestaw benchmarków obejmujący m.in. ENEM, BLUEX, OAB, ASSIN2, FAQUAD, HateBR, PT Hate Speech i tweetSentBR.

**Uwagi:** Benchmark nie jest polski; w raporcie pokazuje transfer cross-lingual.

### INCLUDE-base-44

Wielojęzyczny benchmark wiedzy i rozumowania z pytaniami wielokrotnego wyboru w 44 językach. W raporcie Bielika użyto podzbioru 20 języków europejskich.

**Uwagi:** Raport v3 podaje średnią po 20 językach europejskich i osobny wynik dla języka polskiego.

### Belebele

Wielojęzyczny benchmark czytania ze zrozumieniem oparty na fragmentach FLORES-200. Zadania mają formę pytań wielokrotnego wyboru do tekstu.

**Uwagi:** Raport v3 używa 28 europejskich wariantów językowych.

### COMPL-AI

Zbiór testujący zgodność generowanych treści z wymogami bezpieczeństwa i etyki według EU AI Act.

**Uwagi:** COMPL-AI jest publicznym frameworkiem benchmarkowym, ale dane nie są jednym centralnym datasetem w repo. Poszczególne taski są wrapperami na zewnętrzne benchmarki, np. BBQ jest importowany z inspect_evals. Pełna reprodukcja zależy od dostępności danych i implementacji konkretnych tasków. Znaleziono ewaluację dla Bielik-11B-v2.3-Instruct, nie dla Bielik v3 11B.

