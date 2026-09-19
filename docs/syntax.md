# BHARTI MODERN CODE (BMC) — SYNTAX & STRUCTURAL SPECIFICATION

====================================================================
Designed by EMPEROR AD | Zero-Exception Syntax Engine
Project Handle: bharti_modern_code
====================================================================

## 1. FIXED SOV WORD ORDER (निश्चित वाक्य संरचना नियम)
* **Rule:** BMC follows a strict and immutable **Subject + Object + Verb (SOV)** word order.
* **Purpose:** Eliminates word-order permutations and guarantees 0% syntactic ambiguity for human readers and AI/NLP parsers.
* **Syntax Formula:** `[Subject] + [Object] + [Verb Root] + [Aspect] + [Tense]`

---

## 2. CASE MARKER SYSTEM (विभक्ति चिह्न प्रणाली)
* **Rule:** Grammatical relationships are explicitly defined by placing dedicated case markers after nouns or pronouns, separated by a single space.
* **Structural Formula:** `[Noun / Pronoun] + [Case Marker] + [Position Word (if applicable)]`
* **Core Case Markers:**
  1. `ne` : Agentive / Subject (कर्ता कारक)
  2. `ko` : Accusative / Direct Object (कर्म कारक)
  3. `se` : Instrumental / Means / Ablative Source (करण / अपादान कारक)
  4. `vaat` : Dative / Recipient (संप्रदान कारक)
  5. `te` : Ablative / Origin (अपादान कारक)
  6. `ka` : Genitive / Possessive (संबंध कारक)
  7. `me` : Locative Inside (अधिकरण: अंदर)
  8. `pe` : Locative Surface (अधिकरण: सतह)
  9. `ti` : Temporal / Time Position (कालिक स्थिति)
  10. `saatq` : Comitative / Companion (सहचर)

---

## 3. TENSE & ASPECT STACK ORDER (काल और पक्ष पदानुक्रम नियम)
* **Rule:** Aspect and tense markers are completely independent words separated by a single space, following a strict structural hierarchy where the tense marker always appears at the very end.
* **Structural Formula:** `[Verb Root] + [Aspect Marker] + [Tense Marker]`
* **Aspect Markers:**
  * `rah` : Continuous Aspect (निरंतरता पक्ष)
  * `si` : Perfect Aspect (पूर्ण पक्ष)
* **Tense Markers:**
  * `ha` : Present Tense (वर्तमान)
  * `qi` : Past Tense (भूत)
  * `ga` : Future Tense (भविष्य)
  * *Example:* `padh-rah-ha` (Is reading / Reading present)

---

## 4. HONORIFIC & PLURAL INTEGRATION (आदरसूचक और बहुवचन एकीकरण)
* **Universal Plural Rule:** Plurality is indicated by attaching the universal suffix `['s]` directly to the root noun without any whitespace.
  * *Formula:* `[Root Noun]['s]` *(e.g., ghar's)*
* **Honorific Marker Rule:** Respect is indicated using the independent marker `ji`, written as a standalone word separated by a single space immediately after the specific living entity.
  * *Formula:* `[Noun / Pronoun] + [ji]` *(e.g., Ram ji)*
* **Stack Hierarchy Rule:** When combining multiple suffixes/markers on a single root word, a strict maximum limit of two stacked layers is enforced in this exact sequence:
  * *Standard Order:* `[Root Word] -> [-ji] -> ['s] -> [Case Marker]`
  * *Example:* `manushya-ji-s-ne` (Respected people [Subject Case])

---

## 5. CONJUNCTION & CONDITIONAL FLOW (संयोजक और शर्त प्रवाह)
* **Core Conjunction Infix Rule:** Except for `if`, all core conjunctions (`and`, `or`, `bat`, `so`, `bek`) must be placed strictly between two words, ideas, or clauses as an infix with a single whitespace on both sides.
  * *Formula:* `[Clause 1] + [Conjunction] + [Clause 2]`
* **Subordinating Conditional Flow:** Conditional structures begin with `if` at the very absolute start of the clause, followed by the condition and the responder (`den` or `els`).
  * *Formula:* `[if] + [Condition Clause] + [den / els] + [Result Clause]`

---

## 6. INTERROGATIVE STRUCTURE (प्रश्नवाचक संरचना नियम)
* **Yes / No Questions:** Formed by placing the universal interrogative operator `ki` at the very beginning of the clause.
  * *Formula:* `ki + [Subject] + [Verb Root] + [Aspect] + [Tense]`
* **Specific WH-Questions:** Formed by prefixing `ki` directly to core conceptual roots (1 Sound = 1 Symbol):
  * `kijan` (Who - Person)
  * `kivastu` (What - Thing)
  * `kijaga` (Where - Place)
  * `kitem` (When - Time)
  * `kihetu` (Why - Reason)
  * `kirit` (How - Manner)
  * `kimatra` (How much/many - Quantity)
* **Negation in Questions:** The negative prefix `na-` is prefixed directly before the verb root.
  * *Formula:* `ki + [Subject] + [na-] + [Verb Root] + [Aspect] + [Tense]`

====================================================================
Designed by EMPEROR AD | Zero-Exception Framework
====================================================================
