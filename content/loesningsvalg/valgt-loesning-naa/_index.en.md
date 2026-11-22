---
id: eba7345b-b839-4551-bdc5-32a2ea18e17e
title: "Chosen solution now"
linkTitle: "Chosen solution now"
weight: 30

---

{{< i-arbeid >}}

The pilot has chosen to explore whether an AI model can help school staff select which documents in the pupil file to send to the new school. No solution has been built yet. Within the pilot's time frame, until the end of November 2026, the work consists of a legal assessment and contact with school communities. The technical work depends on a continuation, see [Roadmap](/en/pilotering/pilot-3/loesningsvalg/veikart/).

## What the pilot wants to achieve

- better quality in the selection of information that is sent, without documents that are not relevant
- decision support and less work for the staff at the school the pupil moves from
- a clearer selection for the staff at the school the pupil moves to
- that the pupil has a good transition, and that needs for adapted education are picked up and followed up quickly

Beyond the case itself, a categorisation of the documents in the pupil file can provide a basis for a standard, which would be a boost for seamless services in the education sector. A risk and privacy assessment (ROS and DPIA) for such a solution can also be useful beyond this case.

## How

- **Classical machine learning, not a large language model (LLM),** is considered most suitable. The model shall roughly sort and categorise the documents, not make decisions.
- **The model must run locally.** The documents are sensitive personal data about children and cannot be sent to an external service.
- **School staff with knowledge of the content of the pupil files** must take part. They define the categories the model is trained on, and quality-assure the training.
- **A human always makes the final decision** on what is sent.

## Training data

| Real pupil files | Synthetic data |
|---|---|
| Sensitive personal data | Can be made with AI, combined with domain knowledge about content and categories |
| The documents may also mention other pupils, for example in bullying cases, sometimes only by initials. This must be taken into account when anonymising and in the legal assessment | Requires a person with domain knowledge |
| In small places, anonymised documents may still be linkable to a person | The model can be trained in KS Digital's sandbox for AI solutions |

## Input from workshop with KI-Norge

The pilot presented the case at a workshop at KI-Norge on 7 October 2026. Important input:

- Start with the simplest thing that is still useful, for example the number of documents in the pupil file, history from earlier school changes, and a rough sorting into "requires consent" and "does not require consent". Refine the model over time.
- The categories can be made in advance or proposed by the model itself, preferably in an alternating process. A knowledge graph of the categories can be built up along the way.
- The shipment can include a description of which criteria the model has used for the selection.
- The model must know the rules that decide what can be sent.
- Data quality must be assessed. What happens if an incident is registered on the wrong pupil?
- It is unresolved whether the school or the school owner owns the data, and whether the parents get to see the actual documents they are asked to consent to being sent.
