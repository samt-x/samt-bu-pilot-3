---
title: "Legal matters"
linkTitle: "Legal matters"
weight: 60

---

{{< i-arbeid >}}

What schools can share with each other when a pupil changes school, when consent is needed, and which legal questions an AI solution for the pupil file raises. The basis is the pilot's memo on consent. A final report on privacy and digital security is being prepared.

## The rules do not stop us, but the tools are missing

| Myth | Fact |
|---|---|
| We must have consent when we process personal data | The public sector very often has other legal grounds that allow us to process personal data without consent |
| When we need consent, it is because of the GDPR | Many of the laws municipalities must follow have their own consent requirements, for example the Education Act (opplæringslova) |

The municipalities ask for common routines and a digital consent solution, so that the path from the statute book to practice is less heavy.

## What the school can share without consent

Both the data protection rules and the rules on the duty of confidentiality in public administration set limits on what schools can share. The starting point is that the school cannot share information about individual pupils without a legal basis.

When a pupil changes to another school at the same level, the school can share this information with the new school without consent, under section 25-1 of the Education Act (opplæringslova) and section 20-3 of the Education Regulations (opplæringsforskrifta):

- education previously completed, with subject combination
- grades to be entered on the diploma or certificate of competence
- absence to be entered on the diploma or certificate of competence
- assessments of pupils with the right to special language education
- personal data necessary to prevent behaviour that significantly harms the school environment of fellow pupils or the working environment of the staff (new from 1 August 2026)

## What requires consent

Everything else requires consent from the pupil or the parents. The school can only ask for consent to share information that is necessary to adapt the pupil's education. Examples are information about reading or writing difficulties, illness or allergies, decisions on individually adapted education and statements from the educational-psychological service (PPT).

If the school shares more than there is a legal basis for, it violates the pupil's privacy. This must therefore be handled as a risk in the data protection impact assessment (DPIA).

## The consent is not a legal basis for processing under the GDPR

It is important to distinguish between consent as a legal basis for processing in the General Data Protection Regulation (GDPR) and consent under other rules.

GDPR Article 6, and for health data and other special categories also Article 9, requires a legal basis for processing in order to share information. Consent is only one of several possible bases. When a pupil changes school, the basis is section 25-1 of the Education Act, which is a supplementary legal basis to Article 6(1)(c) and (e) and Article 9: it is lawful to process personal data when it is necessary to fulfil a legal obligation or perform a task in the public interest.

So the school obtains consent to meet the conditions in the Education Act and to avoid breaching the duty of confidentiality, not as a legal basis for processing under the GDPR. These consents are not covered by the requirements the GDPR sets for consent, but must be valid under general administrative law.

## Legal questions for an AI solution

The chosen track, an AI model that helps select documents in the pupil file (see [Chosen solution now](/en/pilotering/pilot-3/loesningsvalg/valgt-loesning-naa/)), requires a thorough legal assessment before it can go further. Among the questions:

- **Legal basis for processing to train the model:** which data shall it be trained on, and what is the basis for that?
- **Legal basis for processing to use the model** on the pupil file, cf. GDPR Articles 6 and 9. The principles of data minimisation and purpose limitation may speak against it, because it is a clean-up processing that would not have been necessary if the documents had been structured from the start.
- **Automated decisions:** can the solution conflict with the prohibition in GDPR Article 22, and how great is the effect if a human must go through all the documents anyway?
- **DPIA:** a data protection impact assessment will probably have to be carried out, and the outcome may be that the processing is not lawful.
- **Discrimination:** see the Equality and Anti-Discrimination Ombud's guide on built-in protection against discrimination in AI.

KS Digital's lawyer is looking at the legal basis for processing for training and use. The pilot has also asked the Norwegian Tax Administration (Skatteetaten) whether it has made assessments that can be reused.

## Further follow-up

- clarify how the consent requirements under section 25-1 of the Education Act can be met in practice, and which consent solutions can be used
- assess and document risk related to the legal basis for processing and consent in the DPIA
- complete the final report on privacy and digital security ([samt-bu-pilot-3#25](https://github.com/samt-x/samt-bu-pilot-3/issues/25))

## Sources

- [The Public Administration Act section 13 (duty of confidentiality)](https://lovdata.no/lov/1967-02-10/§13)
- [The Education Act (opplæringslova) section 25-1](https://lovdata.no/lov/2023-06-09-30/§25-1)
- [The Equality and Anti-Discrimination Ombud: Built-in protection against discrimination (PDF, in Norwegian)](https://ldo.no/content/uploads/2024/06/Innebygd-diskrimineringsvern-2023.pdf)
