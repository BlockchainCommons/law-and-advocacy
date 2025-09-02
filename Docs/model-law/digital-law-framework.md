# [Draft Package] Digital Law Framework  
*(Prepared in the style of a Uniform Law Commission model law)*  
**Version: 2025-09-02**

This package contains three coordinated acts:
1. Digital Signature and Assent Act  
2. Cryptographically Verifiable Records Act  
3. Digital Identity Recognition Act  

Each act is independent but interoperable. A state may adopt them separately or together.  

---

## Policy Explainer: A Three-Layer Framework for Digital Law

### Why Layering?
Current laws (E-SIGN, UETA, various “digital identity” bills) blur together three distinct functions:
- **Assent** (“I agree”)  
- **Record integrity** (“Here is the unaltered version”)  
- **Identity** (“This is who agreed”)  

This package separates those functions into **independent, interoperable layers**, making the law clearer, future-proof, and easier to adopt incrementally.

---

### The Three Layers

```
+----------------------------------------+
|   Digital Identity Recognition Act     |
|   • Who agreed?                        |
|   • Agency law (principal/agent)       |
|   • Recognition of verifiable creds    |
|   • State does NOT monopolize ID       |
+----------------------------------------+
|   Cryptographically Verifiable Records |
|   Act                                  |
|   • Is the record authentic?           |
|   • Self-authentication & admissibility|
|   • Records are tamper-evident         |
|   • Defers identity questions upward   |
+----------------------------------------+
|   Digital Signature & Assent Act       |
|   • Did they agree?                    |
|   • All digital signatures valid       |
|   • Multi-sig, revocation recognized   |
|   • Identity questions not included    |
+----------------------------------------+
```

---

### Key Benefits

- **Separation of Concerns**  
  - Signatures = intent  
  - Records = authenticity  
  - Identity = authority  

- **Future-Proof**  
  - Works for blockchain, DIDs, verifiable credentials, post-quantum cryptography, and technologies not yet invented.  

- **Legal Continuity**  
  - Identity grounded in **agency law** (principal ↔ agent).  
  - Builds on familiar doctrines instead of inventing new ones.  

- **Government Restraint**  
  - Follows Utah’s model: the state recognizes, but does not control, digital identity systems.  

- **No Fiscal Mandate**  
  - These acts do **not** require the state to build or procure technology.  
  - Agencies may recognize standards and credentials **within existing resources**.  

- **Incremental Adoption**  
  - States can pass one layer at a time without overhauling their entire code base.  

---

### In Practice

- A **board resolution**: Signed digitally (Layer 1), stored in a verifiable log (Layer 2), with officers’ authority established by digital credentials (Layer 3).  
- A **real estate transaction**: Buyer and seller sign digitally (Layer 1); the deed is recorded on a verifiable system (Layer 2); each party’s identity/authority is validated by digital credentials (Layer 3).  
- A **university transcript**: Issued as a credential (Layer 3), preserved in a verifiable record system (Layer 2), and assented to by the registrar’s signature (Layer 1).  

---

### Takeaway

By **layering digital law**, states can modernize their evidence and identity frameworks:  
- without forcing a single technology,  
- without creating state-run identity monopolies,  
- without creating fiscal burdens,  
- while ensuring legal clarity and durability.  

---

## PART I. DIGITAL SIGNATURE AND ASSENT ACT

### SECTION 1. SHORT TITLE.
This [act] may be cited as the **Digital Signature and Assent Act**.  

> **Drafting Note:** This section provides a model short title for citation purposes. A state legislature may omit this section or adjust it to conform to local codification practices.  

---

### SECTION 2. DEFINITIONS.
(1) **“Electronic signature”** means an electronic sound, symbol, or process attached to or logically associated with a record and executed or adopted by a person with the intent to sign.  
(2) **“Digital signature”** means an electronic signature produced by cryptographic or other verifiable methods that ensure authenticity, integrity, and non-repudiation.  
(3) **“Composite signature”** means a signature created by combining multiple methods of verification, including but not limited to cryptographic keys, biometrics, passcodes, or devices.  
(4) **“Multi-party signature”** means a digital signature that requires approval or participation from more than one person or device, including threshold or quorum-based methods.  
(5) **“Principal”** means a person or entity granting authority to another person, device, or system to act on their behalf.  
(6) **“Agent”** means a person, device, or system authorized by a principal to affix a digital signature on the principal’s behalf.  

---

### SECTION 3. LEGAL EFFECT OF DIGITAL SIGNATURES.
(a) A digital signature has the same legal effect as a handwritten signature, provided that it is affixed with the intent to sign and is attached to, or logically associated with, the record being signed.  
(b) The validity of a digital signature establishes assent but does not by itself establish the signer’s identity. Questions of identity are governed by other applicable law.  

---

### SECTION 4. MULTI-PARTY AND COMPOSITE SIGNATURES.
(a) A record signed by a multi-party signature has the same legal effect as if each required signer had affixed an individual signature.  
(b) A composite signature is valid if the combined methods reliably demonstrate assent under the circumstances.  

---

### SECTION 5. AGENCY AND DELEGATED SIGNATURES.
(a) A digital signature affixed by an agent within the scope of authority granted by the principal binds the principal as if the principal had signed directly.  
(b) The law of agency, including rules concerning authority, ratification, and revocation, applies to the use of digital signatures by agents unless specifically displaced by this [act].  

---

### SECTION 6. REVOCATION AND EXPIRATION.
(a) A digital signature remains effective until:  
  (1) it is revoked by the signer or principal;  
  (2) it expires by its terms or by applicable agreement; or  
  (3) the method by which it was created is demonstrably compromised.  
(b) Revocation or expiration does not affect the validity of a digital signature affixed before revocation or expiration, unless otherwise agreed.  

---

### SECTION 7. RELIABILITY AND STANDARDS.
(a) In determining the validity of a digital signature, a court may consider whether the method used provides assurance of authenticity, integrity, and intent under the circumstances.  
(b) Compliance with standards widely recognized at the time the signature was affixed, including standards adopted by [federal agencies], [international bodies], or [state agencies], creates a presumption of validity.  

---

### SECTION 8. SAFE HARBORS.
A digital signature that meets technical standards designated by [the state’s appropriate authority] shall be conclusively presumed valid, subject to rebuttal only for fraud, duress, mistake, or lack of intent.  

---

### SECTION 9. NO EXCLUSIVE METHOD.
This [act] does not require or limit the use of any particular technology or standard for creating a valid digital signature.  

---

### SECTION 9A. NO APPROPRIATION; NO UNFUNDED MANDATE.
(a) This [act] does not of itself appropriate money.  
(b) Nothing in this [act] requires an agency to procure, deploy, or maintain any particular technology, system, or service.  

---

### [OPTIONAL] SECTION 9B. ADMINISTRATION AND RULEMAKING.
An agency may adopt rules to implement this [act] **within existing appropriations**, provided such rules are technology-neutral and nonexclusive.  

---

### SECTION 10. SEVERABILITY.
If any provision of this [act] or its application to any person or circumstance is held invalid, the invalidity does not affect other provisions or applications of this [act].  

---

#### COMMENTARY (Signatures Act)
- **Assent vs. Identity.** This act distinguishes the function of a signature (assent) from identity proof, which is handled separately.  
- **Agency Law.** Delegated signatures are handled under traditional principal–agent doctrine.  
- **Future-Proofing.** Multi-sig, composite methods, and revocation are explicitly recognized.  
- **Safe Harbors.** Allows states to name standards but avoids technological lock-in.  
- **Fiscal Note.** Adoption of this [act] is not expected to have a fiscal impact because it creates no duty to build or procure technology.  

---

## PART II. CRYPTOGRAPHICALLY VERIFIABLE RECORDS ACT

### SECTION 1. SHORT TITLE.
This [act] may be cited as the **Cryptographically Verifiable Records Act**.  

> **Drafting Note:** A state may omit this section if codification practices do not include short titles.  

---

### SECTION 2. DEFINITIONS.
(1) **“Verifiable record system”** means any system that uses cryptographic methods to establish the authenticity, integrity, and chronological order of digital records.  
(2) **“Verifiable record technology”** means computer software, hardware, or both, that enable or utilize a verifiable record system.  
(3) **“Digital record”** means information stored in electronic form, including data, documents, contracts, or communications.  

---

### SECTION 3. SELF-AUTHENTICATION OF RECORDS.
(a) A digital record registered in a verifiable record system is self-authenticating under [the rules of evidence of this state concerning authentication of records], if accompanied by a written declaration of a qualified person stating:  
  (1) the date and time the record entered the system;  
  (2) the date and time the record was retrieved;  
  (3) that the record was maintained as part of a regularly conducted activity; and  
  (4) that the system’s method of verification was regularly relied upon in such activity.  

(b) A record that is self-authenticating under subsection (a) is admissible without further foundation, subject to the discretion of the court.  

(c) A digital record that includes a digital signature recognized under the [Digital Signature and Assent Act] is admissible under this [act], subject to the rules of evidence of this state.  

---

### SECTION 4. BUSINESS RECORDS PRESUMPTION.
A digital record registered in a verifiable record system and accompanied by the declaration described in Section 3(a) is presumed admissible as a record of regularly conducted activity, unless the source of information or method indicates a lack of trustworthiness.  

---

### SECTION 5. DEFAULT PRESUMPTIONS.
Unless rebutted, the following presumptions apply:  
(1) A fact or record verified through a valid application of verifiable record technology is authentic.  
(2) The recorded date and time is the date and time the record was added.  
(3) A digital record may indicate the originator of the record, but questions of whether that originator was authorized to act for a principal or agent are governed by applicable law, including the [Digital Identity Recognition Act].  
(4) A presentation of such a record in a format agreed by the parties is sufficient to demonstrate its contents.  

---

### SECTION 6. LIMITATIONS.
(a) Presumptions under this [act] extend only to authenticity, integrity, and chronology.  
(b) Presumptions do not establish the truth or legal status of the record’s contents.  
(c) A person challenging a record bears the burden of producing evidence of inauthenticity, but the burden of persuasion remains with the proponent.  

---

### SECTION 7. SCOPE OF APPLICATION.
This [act] applies to digital records used to establish, without limitation:  
(1) contracts;  
(2) property ownership and transfer;  
(3) organizational governance and participation;  
(4) private or public identity interactions;  
(5) authenticity or integrity of records or communications.  

---

### SECTION 8. RECOGNITION ACROSS JURISDICTIONS.
A digital record authenticated under this [act] in another jurisdiction has the same legal effect in this state, unless contrary law applies.  

---

### SECTION 9. NO MANDATE OR VALIDATION.
(a) Nothing in this [act] requires adoption of verifiable record technology.  
(b) Nothing in this [act] validates the legality of underlying activity merely because it is recorded.  

---

### SECTION 9A. NO APPROPRIATION; NO UNFUNDED MANDATE.
(a) This [act] does not of itself appropriate money.  
(b) Nothing in this [act] requires an agency or person to adopt or operate a verifiable record system.  

---

### [OPTIONAL] SECTION 9B. ADMINISTRATION AND RULEMAKING.
An agency may recognize formats or evidentiary presentation methods **within existing appropriations**, provided such recognition remains technology-neutral and nonexclusive.  

---

### SECTION 10. SEVERABILITY.
If any provision of this [act] or its application to any person or circumstance is held invalid, the invalidity does not affect other provisions or applications of this [act].  

---

#### COMMENTARY (Records Act)
- **Connection to Signature Law.** Section 3(c) ensures smooth interplay with the Signature Act.  
- **Connection to Identity Law.** Section 5(3) explicitly defers authorization questions to the Identity Act.  
- **Focus.** Covers admissibility and evidentiary presumptions only, not identity or assent.  
- **Fiscal Note.** This [act] has no fiscal impact; it governs evidentiary presumptions only and imposes no operational obligations on the state.  

---

## PART III. DIGITAL IDENTITY RECOGNITION ACT

### SECTION 1. SHORT TITLE.
This [act] may be cited as the **Digital Identity Recognition Act**.  

> **Drafting Note:** States may rename or omit the short title as appropriate.  

---

### SECTION 2. DEFINITIONS.
(1) **“Digital identity”** means a set of attributes, credentials, or identifiers representing a principal in electronic form.  
(2) **“Credential”** means a verifiable digital attestation or token issued to establish or support a digital identity.  
(3) **“Principal”** means the person or entity whose identity is represented.  
(4) **“Agent”** means a person, device, or system authorized by a principal to present or use a digital identity.  
(5) **“Issuer”** means an entity that creates and provides a credential.  
(6) **“Verifier”** means an entity that relies on a credential in a transaction or proceeding.  

---

### SECTION 3. LEGAL RECOGNITION.
(a) A cryptographically verifiable digital identity or credential has the same legal effect as a physical identification, subject to applicable law.  
(b) A digital identity need not be issued or controlled by this state to be recognized.  
(c) This [act] does not authorize the state to establish or mandate a single, centralized identity system.  

---

### SECTION 4. AGENCY BASIS.
(a) The law of agency applies to digital identity.  
(b) A principal may authorize an agent, including a device or system, to use a digital identity on the principal’s behalf.  
(c) Acts within authority bind the principal; unauthorized acts do not, unless ratified.  

---

### SECTION 5. ISSUERS AND RELIANCE.
(a) An issuer represents that a credential was issued to the stated principal.  
(b) A verifier relying in good faith on a cryptographically verifiable credential may treat it as valid unless circumstances suggest untrustworthiness.  
(c) An issuer may be liable for knowingly or negligently issuing a false credential.  

---

### SECTION 6. REVOCATION AND EXPIRATION.
(a) A credential may be revoked or expire according to its terms.  
(b) Revocation or expiration does not affect past valid uses unless otherwise provided.  

---

### SECTION 7. INTEROPERABILITY AND RECOGNITION.
(a) This state recognizes digital identities consistent with widely adopted open standards, as designated by [appropriate authority].  
(b) A credential recognized in another jurisdiction has the same legal effect in this state, unless contrary law applies.  

---

### SECTION 8. NO MANDATE OR EXCLUSIVE CONTROL.
(a) Nothing in this [act] requires adoption of a digital identity.  
(b) Nothing in this [act] grants exclusive control of identity systems to this state or any provider.  

---

### SECTION 8A. NO APPROPRIATION; NO UNFUNDED MANDATE.
(a) This [act] does not of itself appropriate money.  
(b) Nothing in this [act] requires the state to create, procure, or operate a digital identity system.  

---

### [OPTIONAL] SECTION 8B. ADMINISTRATION AND RULEMAKING.
An agency may designate open standards or recognition criteria for credentials **within existing appropriations**, provided such designations remain technology-neutral and nonexclusive.  

---

### SECTION 9. SEVERABILITY.
If any provision of this [act] or its application to any person or circumstance is held invalid, the invalidity does not affect other provisions or applications of this [act].  

---

#### COMMENTARY (Identity Act)
- **Agency Foundation.** Digital identity is framed as an agent acting for a principal, grounding it in longstanding law.  
- **Utah Influence.** Section 3(c) follows Utah’s approach of state recognition without centralization.  
- **Issuer & Verifier Duties.** Balances liability for issuers with good-faith reliance protection for verifiers.  
- **Future-Proofing.** Covers DIDs, verifiable credentials, federated IDs, and future cryptographic attestations.  
- **Fiscal Note.** This [act] creates no fiscal obligation. It clarifies recognition of credentials and authority under existing law and forbids a state-run monopoly identity system.  
```
