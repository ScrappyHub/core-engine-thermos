# ENGINE GOVERNANCE — THERMOS (THERMAL DYNAMICS)

Authority Level: Engine Governance (Binding)  
Engine Role: TRUTH_ENGINE  
Status: ✅ BINDING | ✅ NON-OPTIONAL  

---

## 1. GOVERNANCE INHERITANCE

THERMOS is permanently bound by CORE platform governance:

- CORE_CONSTITUTIONAL_STOP_LAYER.md  
- CORE_PLATFORM_CONSTITUTION.md  
- CORE_ENGINE_REGISTRY_AND_VERTICAL_INHERITANCE_LAW.md  
- CORE_ENGINE_REGISTRY_CONTRACT.md  
- CORE_GOVERNANCE_INDEX_CHAIN_OF_AUTHORITY.md  

If any content in this repository conflicts with CORE governance →  
**CORE governance prevails immediately.**

---

## 2. ENGINE ROLE & SCOPE

THERMOS computes **thermal domain truth only**, including:

- temperature fields  
- thermal gradients  
- heat flux  
- conduction, convection, and radiative transfer (as declared)  
- phase-state indicators (if modeled)  

THERMOS outputs physical quantities only.

---

## 3. NON-SCOPE (PROHIBITIONS)

THERMOS MUST NOT:

- issue medical, biological, or safety verdicts  
- infer exposure safety or treatment thresholds  
- access network or external systems  
- manage identity, permissions, or billing  
- publish or export independently  
- call other engines directly  

---

## 4. DETERMINISM & REPRODUCIBILITY

THERMOS runs MUST be reproducible under identical:

- material thermal properties  
- geometry and boundaries  
- heat sources/sinks  
- solver parameters  
- engine version  

Any nondeterministic mode must be explicitly declared and gated by CORE.

---

## 5. OUTPUT & SEALING

THERMOS MUST emit sealed artifacts only, including:

- canonical input/output JSON  
- SHA-256 hashes  
- artifact index  

THERMOS MUST NOT mutate artifacts post-emission.

---

## 6. SAFETY CONSTRAINTS

THERMOS MUST:

- label units and coordinate frames  
- expose uncertainty and modeling limits  
- prohibit clinical or operational interpretation  

---

## 7. CHANGE CONTROL

Schema or artifact changes require:
- manifest version increment  
- registry update  
- Git audit record  

---

## 8. FINAL DECLARATION

THERMOS produces **thermal physics truth only**.  
Meaning and action are assigned by CORE lenses.
