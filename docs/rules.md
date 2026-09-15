# BHARTI MODERN CODE (BMC) — SYSTEM SPECIFICATION & RULES

---

## 1. CONJUNCTION ENGINE

### [A] Core Conjunctions (8 Connectors)
1. `and` : Used to join two words, ideas, or clauses (Addition).
2. `or`  : Used to present a choice between options (Alternative).
3. `but` : Used to connect contrasting or opposing ideas (Contrast).
4. `so`  : Used to show the result or outcome of an action (Consequence).
5. `bec` : Used to explain the reason for an action (Causal) `<Shortened from 'because'>`.
6. `if`  : Used to initiate a condition (Conditional Starter).
7. `then`: Used to indicate the result or next step of a condition (Conditional Responder).
8. `els` : Used to define an alternative outcome or condition (Otherwise/Else).

### Structural Examples:
* **Addition & Choice:**
  * Code: `Ram and Shyam`
  * Code: `Chai or Coffee`
* **Contrast & Cause:**
  * Code: `Va padh-ha-pura but na-pass-ha.` (He studied but did not pass.)
  * Code: `Main andar raag-ha bec baarish ho-ha-pura.` (I stayed inside because it was raining.)
* **Conditional Logic:**
  * Code: `if tu padh-ha then tu pass-ha els tu fail-ha.` (If you study, then you will pass, else you will fail.)

### Guidelines & Instructions:
* **[Rule 1] INFIX PLACEMENT RULE:** Except for `if`, all other 7 conjunctions must be placed directly between two words, clauses, or sentences (Infix position).  
  * *Syntax:* `[Clause 1] + [Conjunction] + [Clause 2]`
* **[Rule 2] IF-THEN-ELS STRUCTURE:** Conditional sentences must strictly follow this order:
  * `if [Condition]`
  * `then [Positive Outcome]`
  * `els [Alternative/Negative Outcome]`
* **[Rule 3] WHITESPACE MANDATE:** Exactly one space (whitespace) is required before and after every conjunction code so AI parsers can distinguish them from root words.
* **[Rule 4] ZERO SYNONYM RULE:** Words like 'although', 'however', 'moreover', or 'therefore' do not exist in the dictionary. All complex relationships must be constructed exclusively using these 8 core conjunction codes.

---

## 2. INTERROGATIVE ENGINE (`ki-`)

### [A] Core Interrogative Operator
* `ki-` : Universal Interrogative Marker

### [B] Yes / No Questions
* **Rule:** Place `ki-` at the very beginning of the clause.
* **Syntax:** `ki- + [Subject] + [Verb Root] + [Aspect Suffix] + [Tense Suffix]`
* **Examples:**
  * `ki- tu kar-ra-ha?` (Are you doing?)
  * `ki- va likh-ra-ga?` (Will he/she be writing?)

### [C] Specific WH-Questions
* **Rule:** Attach `ki-` directly as a prefix to core conceptual roots.
1. **Who?** -> `ki-jan kar-ra-ha?` (`ki-` + `jan`/person)
2. **What?** -> `ki-kriy tu kar-ra-ha?` (`ki-` + `kriy`/action or object)
3. **Why / For What?** -> `ki-hetu tu kar-ra-ha?` (`ki-` + `hetu`/reason)
4. **When?** -> `ki-at tu kar-ra-ha?` (`ki-` + `at`/time)
5. **Where?** -> `ki-agr tu kar-ra-ha?` (`ki-` + `agr`/location)
6. **How?** -> `ki-rit tu kar-ra-ha?` (`ki-` + `rit`/method)

### [D] Combined Question & Negation
* **Rule:** Use `ki-` at the sentence/clause level for questions, and prefix `na-` directly before the verb root for negation.
* **Examples:**
  * `ki-hetu tu na-kar-ra-ha?` (Why are you not doing?)
  * `ki- tu na-kar-ra-ha?` (Are you not doing?)

### Guidelines & Instructions:
* **[Rule 1] SINGLE OPERATOR MANDATE:** Eliminates the need to memorize distinct interrogative words (who, where, when, why, how, what). A single prefix, `ki-`, attaches to fundamental roots to form all question types seamlessly.
* **[Rule 2] FIXED WORD ORDER (NO INVERSION):** Unlike natural languages that alter word positions or introduce auxiliary verbs, BMC maintains a strictly unified word order.
* **[Rule 3] ZERO AMBIGUITY:** Phrases with identical underlying logic merge into a single precise form (e.g., `ki-hetu`).

---

## 3. UNIFIED SUFFIX & ENGINE REGISTRY
*(Version: Final Zero-Exception Release)*

### 1. CORE ENGINE REGISTRY

* **[ENGINE 01] INTERROGATIVE ENGINE**
  * Syntax Prefix: `[ki-]`
  * Placement: Sentence prefix (Appended to the very beginning of the sentence)
  * Description: Converts any declarative sentence into a question.
  * Example: `ki- tum padh-ha?` (Are you reading?)

* **[ENGINE 02] UNIVERSAL NEGATION ENGINE**
  * Syntax Prefix: `[na-]`
  * Word Negation: `[na-] + [Root Word]` -> Negates only the specific Noun/Adjective (e.g., `na-gyan-ik` = Unwise / Ignorant).
  * Sentence Negation: `[na-] + [Auxiliary Verb]` -> Negates the action or overall statement (e.g., `na-ha` = Is not / Does not).

* **[ENGINE 03] TENSE SYSTEM ENGINE**
  * Present Tense: `[-ha]` -> `padh-ha` (reads / is reading)
  * Past Tense: `[-qi]` -> `padh-qi` (read / had read)
  * Future Tense: `[-ga]` -> `padh-ga` (will read)

* **[ENGINE 04] STACK HIERARCHY ENGINE**
  * Structural Limit: Maximum of two (2) Suffixes stacked on a single Root Word.
  * Standard Order: `[Root Word] -> [-ji] -> [-s] -> [Case Marker]`
  * Example: `manushya-ji-s-ne` (Respected people [Subject Case])

---

### 2. MASTER SUFFIX REGISTRY

* **[SUFFIX 01] ADJECTIVE MARKER `[-ik]`**
  * Category: Grammar Modifier (Adjective)
  * Usage: Converts a Root Word/Noun into an Adjective.
  * Code Spec: `[Root] + [-ik]`
  * Example: `gyan-ik` (Wise / Knowledgeable)

* **[SUFFIX 02] ADVERB MARKER `[-vat]`**
  * Category: Grammar Modifier (Adverb)
  * Usage: Modifies a Verb; placed directly before the Main Verb.
  * Code Spec: `[Root] + [-vat]`
  * Example: `dhyan-vat` (Carefully / Attentively)

* **[SUFFIX 03] STUDY / SCIENCE MARKER `[-vid]`**
  * Category: Domain Classification
  * Usage: Denotes a discipline, field of study, or scientific domain.
  * Code Spec: `[Root] + [-vid]`
  * Example: `jeev-vid` (Biology / Life Science)

* **[SUFFIX 04] PLURAL MARKER `[-s]`**
  * Category: Number Marker
  * Usage: Pluralizes a Noun.
  * Code Spec: `[Root] + [-s]`
  * Example: `ghar-s` (Houses)

* **[SUFFIX 05] HONORIFIC MARKER `[-ji]`**
  * Category: Formal / Respect Marker
  * Usage: Denotes respect; attached exclusively to Nouns/Pronouns.
  * Rule Note: `'ji'` as an independent verb root is deprecated to eliminate overlap.
  * Code Spec: `[Noun/Pronoun] + [-ji]`
  * Example: `Ram-ji` (Respected Ram)

* **[SUFFIX 06] CONTINUOUS ASPECT MARKER `[-rah]`**
  * Category: Aspect System
  * Usage: Denotes progressive/ongoing action (-ing form).
  * Code Spec: `[Root Verb] + [-rah]`
  * Example: `padh-rah` (Reading / In progress)

* **[SUFFIX 07] PERFECT ASPECT MARKER `[-siddh]`**
  * Category: Aspect System
  * Usage: Denotes completed action (Perfect aspect).
  * Code Spec: `[Root Verb] + [-siddh]`
  * Example: `kriy-siddh` (Completed / Has done)

---

### 3. CASE MARKER SUFFIXES

* **[CASE 01] ERGATIVE (Subject):** `[-ne]` -> Example: `Ram-ji-ne` (Ram [Subject])
* **[CASE 02] ACCUSATIVE (Direct Object):** `[-ko]` -> Example: `pustak-ko` (Book [Object])
* **[CASE 03] INSTRUMENTAL / ABLATIVE:** `[-se]` -> Example: `pen-se` (By/With pen)
* **[CASE 04] GENITIVE (Possessive):** `[-ka]` -> Example: `Ram-ka` (Ram's)
* **[CASE 05] LOCATIVE-IN (Position In):** `[-me]` -> Example: `ghar-me` (In house)
* **[CASE 06] LOCATIVE-ON (Position On):** `[-par]` -> Example: `miz-par` (On table)

---

## 4. HONORIFIC MARKER SYSTEM (`-ji`)

### Formal vs Informal Register:
* Informal: `tu go-ha` (You go)
* Formal: `tu-ji go-ha` (You go - Respected)
* Informal: `Ram`
* Formal: `Ram-ji` (Ram - Respected)

### Guidelines & Instructions:
* **[Rule 1] TARGET SPECIFICITY RULE:** The honorific marker `-ji` must strictly attach to the specific noun or pronoun being respected using a hyphen (`-`). It must not be attached to inanimate objects or placed at the end of a sentence. (Example: `Ram-ji aa-ha`)
* **[Rule 2] SELECTIVE HONORIFIC RULE (Multiple Nouns / Pronouns):** When a sentence contains two nouns or pronouns and only one person requires respect, attach `-ji` strictly to that specific individual. If both require respect, attach `-ji` to each independently.
  * *Single Respect:* `Ram-ji aur Shyam aa-ha` (Respected Ram and Shyam are coming)
  * *Dual Respect:* `Ram-ji aur Shyam-ji aa-ha` (Respected Ram and Respected Shyam are coming)
* **[Rule 3] PRONOUN IMMUTABILITY:** Core pronouns never alter their base form (`tu` or `wo`). Simply appending `-ji` shifts the sentence from Informal to Formal register seamlessly.
* **[Rule 4] 1:1 HYPHEN ATTACHMENT RULE:** To ensure 1:1 error-free NLP parsing and AI algorithmic accuracy, `-ji` must always be appended to the root word using a hyphen (`-`).
