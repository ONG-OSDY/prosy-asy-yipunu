# prosy-asy-yipunu

# ALPHABET STANDARDISÉ DU YIPUNU (ASY)
## PROTOCOLE DE STANDARDISATION DE LA LANGUE YIPUNU (PROJET PROSY)

**Auteur :** Brice Alain MAMBINGA MBIBA  
**Porteur du projet :** Organisation pour la Sauvegarde et le Développement du Yipunu (ONG OSDY)

---

### 1. Introduction & Contexte
Le yipunu (ou punu) est l'une des langues bantu les plus parlées au Gabon, principalement ancrée dans les provinces de la Nyanga et de la Ngounié, ainsi qu'en République du Congo. Afin d'assurer la préservation, la transmission intergénérationnelle et la modernisation de cette langue, l'élaboration et la formalisation de l'Alphabet Standardisé du Yipunu (ASY) répondent au besoin impératif d'offrir une orthographe unifiée, rigoureuse et cohérence pour l'enseignement, l'édition, l'inclusion numérique et l'intégration dans les systèmes d'Intelligence Artificielle (IA).

### 2. Objectifs de l'ASY
### 2. Objectifs de l'ASY
* **[OBJ-01] Unification orthographique :** Harmoniser la transcription écrite du yipunu au Gabon, au Congo et dans la diaspora.
* **[OBJ-02] Pédagogie et Apprentissage :** Faciliter la rédaction d'ouvrages didactiques, de manuels scolaires et l'apprentissage de la lecture et de l'écriture.
* **[OBJ-03] Conservation du Patrimoine :** Archiver les contes, proverbes, récits historiques et traditions orales sous une forme écrite pérenne.
* **[OBJ-04] Numérisation & IA :** Permettre le codage informatique des caractères et l'intégration du yipunu dans les écosystèmes de traitement automatique des langues (TAL) et de traduction automatique.
* **[OBJ-05] Formalisation Grammaticale Stricte :** Établir un modèle informatique stable pour la classification nominale bantu et la conjugaison des lemmes sans ambiguïté morphologique.
* **[OBJ-06] Constitution de Corpus d'Entraînement :** Collecter, nettoyer et segmenter des ensembles de données textuelles brutes (datasets) standardisées pour l'apprentissage supervisé des modules de traduction.
* **[OBJ-07] Accessibilité Logicielle et Claviers :** Développer des configurations de claviers virtuels et physiques adaptées aux smartphones et ordinateurs pour faciliter la saisie quotidienne de l'ASY.
* **[OBJ-08] Vulgarisation et Formation des Formateurs :** Créer des guides techniques simplifiés pour permettre aux enseignants et aux chercheurs d'adopter immédiatement la charte graphique unifiée.
* **[OBJ-09] Plateforme Web Institutionnelle (Site OSLY) :** Développer le site web officiel servant de portail central pour présenter la vision, héberger les ressources didactiques et diffuser les standards de la langue.
* **[OBJ-10] Base de Données Lexicale (Dictionnaire A-Z) :** Modéliser et structurer un dictionnaire et un lexique bilingues Yipunu-French / French-Yipunu complets, standardisés sous formats JSON/CSV exploitables par l'homme et la machine.
* **[OBJ-11] Encyclopédie Numérique Collaborative :** Mettre en place un espace encyclopédique de référence pour documenter les variations dialectales, la culture, l'histoire et les savoirs traditionnels de la communauté Punu.
* **[OBJ-12] Agent Conversationnel (Chatbot IA Yipunu) :** Configurer et déployer un assistant IA et un module de traduction automatique basés sur les règles strictes de l'ASY pour interagir en langage naturel.
* **[OBJ-13] Application Mobile Applicative :** Concevoir une application smartphone interactive regroupant les cours, les dictionnaires et les outils d'apprentissage nomades pour les jeunes générations.

---

### 3. Structure Graphémique et Phonétique (ASY)

L'ASY s'appuie sur le système phonologique de la langue et le traduit en un ensemble de règles graphémiques strictes.

#### A. Le Système Vocalique
Le système vocalique repose sur 5 voyelles fondamentales. Les variantes d'ouverture et le schwa `[ə]` sont pris en compte graphiquement par les lettres de base, sans ajout de caractères spéciaux superflus.

| Graphe ASY | Valeurs Phonétiques (API) | Description & Remarques |
| :--- | :--- | :--- |
| **a** / **aa** | [a] / [a:] | Voyelle ouverte antérieure non arrondie. Le redoublement marque la voyelle longue. |
| **e** / **ee** | [e], [ɛ], [ə] / [e:] | Voyelle antérieure ; inclut les réalisations fermée, ouverte et le **schwa `[ə]`** selon le contexte. |
| **i** / **ii** | [i] / [i:] | Voyelle fermée antérieure non arrondie. Le redoublement marque la voyelle longue. |
| **o** / **oo** | [o], [ɔ] / [o:] | Voyelle postérieure arrondie ; inclut les réalisations fermée et ouverte. |
| **u** / **uu** | [u] / [u:] | Voyelle fermée postérieure arrondie. Le redoublement marque la voyelle longue. |

* **Règle de Quantité Vocalique :** Le redoublement de la voyelle (**aa, ee, ii, oo, uu**) est obligatoire pour marquer graphiquement les voyelles longues, ce qui permet de distinguer les paires minimales à l'écrit.
  
#### B. Les Graphèmes Consonantiques (27 unités atomiques)
**RÈGLE D’INTÉGRITÉ ABSOLUE (PROSY) :** Les graphèmes simples et complexes ci-dessous constituent les unités consonantiques indivisibles du yipunu. Les digraphes complexes se comportent rigoureusement comme des consonnes uniques. Ils sont strictement indissociables en syllabation, en segmentation informatique (tokenisation) et en analyse morphologique.

| Graphe ASY | Valeur Phonétique (API) | Nature & Spécificités PROSY |
| :--- | :--- | :--- |
| **B** | /b/ | Occlusive bilabiale sonore. |
| **D** | /d/ | Occlusive alvéolaire sonore. |
| **F** | /f/ | Fricative labiodentale sourde. |
| **G** | /ɣ/ | Fricative vélaire stricte (le phonème [ɡ] dur n'existe pas de manière autonome). |
| **J** | /d͡ʒ/ | Affriquée sonore (la fricative [ʒ] n'existe pas). |
| **K** | /k/ | Occlusive vélaire sourde. |
| **L** | /l/ | Latérale. |
| **M** | /m/ | Nasale bilabiale. Elle sert également de base morphologique aux prénasales bilabiales et labiodentales. |
| **MB** | /ᵐb/ | Séquence pré-nasalisée indissociable. |
| **MF** | /ᶬf/ | Séquence nasale fricative sourde. |
| **MP** | /ᵐp/ | Séquence pré-nasalisée indissociable. |
| **MV** | /ᶬv/ | Séquence nasale fricative sonore . |
| **N** | /n/ | Nasale alvéolaire. |
| **ND** | /ⁿd/ | Séquence pré-nasalisée indissociable. |
| **NG** | /ᵑɡ/ | Séquence pré-nasalisée indissociable. |
| **NK** | /ᵑk/ | Séquence pré-nasalisée indissociable. |
| **NT** | /ⁿt/ | Séquence pré-nasalisée indissociable. |
| **NY** | /ɲ/ | Nasale palatale indissociable. |
| **NZ** | /ⁿz/ | Séquence pré-nasalisée indissociable (seule occurrence du caractère z). |
| **P** | /p/ | Occlusive bilabiale sourde. |
| **R** | /r/ | Rhétique (réservée aux emprunts). |
| **S** | /s/ | Fricative sourde. |
| **T** | /t/ | Occlusive alvéolaire sourde. |
| **TS** | /t͡s/ | Affriquée sourde indissociable. |
| **V** | /β/ | Fricative bilabiale sonore (choix standardisé du PROSY). |
| **W** | /w/ | Approximante labio-vélaire. |
| **Y** | /j/ | Approximante palatale. |

#### C. Principes Directeurs d'Univocité Graphique
1. **Élimination des ambiguïtés :** Le son `[ɣ]` s'écrit exclusivement **g** (le digraphe *gh* historique est formellement proscrit). Le son `[d͡ʒ]` s'écrit exclusivement **j**.
2. **Standardisation du V :** Le caractère **v** est officiellement choisi pour représenter de manière stable le phonème fricatif bilabial sonore `/β/`.
3. **Intégrité des digraphes :** Tout algorithme de traitement automatique des langues (TAL) appliqué au yipunu doit configurer ses expressions régulières (Regex) et ses tokeniseurs pour traiter les 11 digraphes et prénasales comme des caractères uniques insécables.

---
### 4. Fichiers Techniques du Projet
Les configurations strictes pour les outils informatiques et l'Intelligence Artificielle sont stockées dans cet atelier :
* **Configuration Maîtresse :** La loi informatique de l'alphabet (format machine) est disponible ici : `standards/asy_master_config.json`.
* **Outil d'Automatisation :** Le script de segmentation et de génération automatique du tokeniseur IA est disponible ici : `tools/generate_tokenizer.py`.

---


