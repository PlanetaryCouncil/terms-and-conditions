# Consent and interaction protocol

**For “I could be yours for 1 night, the price is 1 BTC”**

**Version 0.7 — working draft — 14 November 2026**

This protocol makes physical interaction predictable while allowing the performance to evolve. It applies equally to the artist and every participant. The artwork’s quantum, shapeshifting, morphogenetic character leaves interpretation open; permission for an actual interaction must have an agreed scope.

## 1. Meaning of default consent to touch

**Default touch permission means advance, explicit, revocable permission for a defined class of contact during an agreed session.** Within that class, a person may initiate contact without asking the same question before each instance. Check-ins and the duty to notice withdrawal continue throughout.

Default permission starts only after the person being touched has actively chosen that mode, understood its scope, and communicated agreement. It cannot be established by a sign, the title, payment, entering the venue, remaining nearby, silence, or failing to object. Agreement to participate is separate from agreement to touch.

Until permission is established, the physical interaction state is **NO TOUCH**. A person may choose conversation or observation without choosing touch.

## 2. Permission is specific and directional

A permission must identify all of the following:

| Field | Required meaning |
| --- | --- |
| Giver | The person whose body may be touched. |
| Receiver | The named person allowed to initiate that touch. Permission does not extend to spectators or additional participants. |
| Mode | `NO_TOUCH`, `ASK_EACH_TIME`, `DEFAULT_TOUCH`, or the separately agreed `MASSAGE_SCOPE`. |
| Body areas | Exact permitted areas, including left/right where relevant and any exclusions. An unspecified area is excluded. |
| Contact | Permitted action, skin or clothing contact, maximum pressure, maximum duration, and repetition limits. |
| Context | The agreed activity and location. |
| Time | Session start and end; permission may end earlier. |
| Communication | A usable way to agree, check in, pause, and stop. Speech is optional. |

**Giver → initiator does not imply the reverse.** Each person gives their own permission. Nobody may give permission for someone else. A buyer cannot authorise touch of the artist on the artist’s behalf.

## 3. Interaction modes

| Mode | What may happen |
| --- | --- |
| `NO_TOUCH` | Conversation, observation, and agreed interaction without bodily contact. |
| `ASK_EACH_TIME` | Ask for a specific contact and receive a clear affirmative response before that instance. The permission ends when that contact ends. |
| `DEFAULT_TOUCH` | Initiate only contact already covered by the active permission, subject to the limits and stop rules below. |
| `MASSAGE_SCOPE` | Perform only massage contact covered by a separately agreed, currently active session scope. |

Selecting a mode does not fill in missing scope fields. No physical contact starts until the scope is complete. Choosing a more restrictive mode takes effect immediately; expanding permission requires a new affirmative agreement.

## 4. Proposed limited default scope

*This scope is a proposal for review, not permission from any actual person.*

If expressly selected, `DEFAULT_TOUCH` covers a brief, light, open-hand touch to an agreed hand, forearm, or shoulder. Each permitted area must be selected individually. Hand/forearm skin contact must be expressly included; shoulder contact is over clothing only. Maximum contact duration is **3 seconds per instance**. No gripping, squeezing, stroking, rubbing, pulling, or restricting movement. No continuous or repeated contact intended to bypass the duration limit; a new instance requires the other person’s active engagement or a check-in.

Hugs, massage, kissing, lifting, tickling, contact with intimate areas, contact under clothing, and touching the face, head, neck, torso, legs, or feet fall outside this proposed default. Clothing, mobility aids, and other personal belongings must not be moved or handled under a bodily-touch permission.

Anything outside the selected default requires a separate specific request and affirmative agreement. Some activities may remain outside the performance entirely; requesting them does not oblige anyone to negotiate.

### Separate massage scope

The [minimum service](SERVICE.md) proposes 24 one-hour Ultra Magic Session massage sessions, which can be delivered remotely under an agreed specification. The social-touch default above does not authorise massage. In-person massage needs a separately agreed scope covering technique, areas, pressure range, clothing or draping, duration, and exclusions. Within an active massage scope, permission can cover continuous contact rather than three-second instances. Reconfirm that scope and present willingness at the start of every session. The same pause, withdrawal, capacity, and check-in rules apply. Remote participation creates no physical-touch permission.

Expressly agreed alternatives include 24 one-hour live Zoom sessions of business consultancy, Reiki, self-guided participation, or an agreed mix, with the artist present. These formats require agreement on the actual activity and scope and create no physical-touch permission. Self-guided participation leaves the participant in control of their own actions. Recording, transcription, and AI-generated notes require separate explicit agreement.

The [artistic Independent Tribunal](TRIBUNAL.md), performed by the artist, cannot supply another person’s consent, reverse a withdrawal, or treat a disputed interaction as retrospectively authorised.

## 5. Establish permission before interaction

1. Explain the proposed interaction in plain language, including the actual contact and its limits. Make the protocol accessible in a form each person can understand.
2. Ask each person to choose a mode and specify their boundaries. No selection is pre-ticked or inferred from buying the work.
3. Agree a stop signal and test that everyone can recognise it without touching anyone. An example is saying “stop” or showing a raised palm; choose an alternative if either is inaccessible.
4. Read back the scope and ask for confirmation. Example: “For this session, may I briefly touch your right forearm, over your sleeve, with a light open hand for up to three seconds, without asking each time? You can pause or stop at any point.”
5. Receive a clear affirmative response through the agreed communication method. Accept a refusal without repeated persuasion. If the response is unclear, do not begin touch.
6. Establish the reverse direction separately if both people want to initiate touch.

A signature, checkbox, or written note records an agreement; it does not prove present willingness or replace attention during the encounter. Do not begin or continue touch when someone is asleep, unable to communicate a choice, unable to understand the proposal, or appears too impaired to decide freely. If there is doubt, pause physical interaction.

## 6. Check every proposed contact

Before initiating contact, the initiator must establish that all conditions are true:

```text
permission is active for this giver and this initiator
AND the proposed area, action, pressure, and duration are in scope
AND the agreed context and session are still current
AND the person is able to choose and communicate
AND there is no refusal, withdrawal, distress, or uncertainty
AND (
    mode is DEFAULT_TOUCH
    OR mode is MASSAGE_SCOPE
    OR (mode is ASK_EACH_TIME AND this instance has a fresh affirmative agreement)
)
```

A purchase or an unused session balance never activates a massage scope or any other touch permission.

If any condition is false or unknown, do not initiate contact. This is a decision aid for people, not an automated consent detector. Body language, biometric signals, or an AI system cannot supply missing permission.

Check in after the first contact, after an interruption, and whenever comfort or understanding is uncertain. Ask again before changing the area, action, intensity, duration, person, or setting. Permission for one interaction does not extend to another because it feels like a natural progression.

## 7. Pause, stop, and withdrawal

“No,” “stop,” “pause,” the agreed signal, pulling away, or pushing a hand away means stop contact immediately. Freezing, sudden silence, hesitation, visible discomfort, or an unexpected loss of response triggers a pause and check-in. Do not demand a particular word or signal before responding to these signs.

End contact and create space. If someone is physically supporting another person, release that support safely; do not abruptly drop them. Do not block an exit or require an explanation. Ask whether they want space, help, conversation, or to leave, without pressuring them to answer.

| Current state | Event | Result |
| --- | --- | --- |
| `NO_TOUCH` | Complete scope and affirmative agreement | Enter the selected touch mode. |
| Active touch mode | Uncertainty, distress, interruption, or changed context | `PAUSED`: end contact; permission is inactive. |
| Any state | Refusal, withdrawal, or session end | `STOPPED`: permission ends. |
| `PAUSED` or `STOPPED` | Silence, elapsed time, payment, or an apology | No reactivation. |
| `PAUSED` or `STOPPED` | Person freely chooses to resume; scope is reviewed and affirmatively agreed again | Start a new active permission. |

Pausing the performance suspends all touch permissions. Withdrawal applies at least to the indicated contact; if its scope is unclear, stop all touch. Either person can end their participation. Stopping does not require justification, and payment must never be used to demand continued contact. Financial arrangements are addressed separately from bodily permission.

## 8. Other interactions and third parties

Agreement to touch does not authorise recording, publication, collecting personal information, sexual interaction, contact after the session, or introducing another person. Obtain separate permission for those interactions where relevant to the agreed performance. A spectator is not a participant merely because they are present.

Conversational boundaries also apply: a person may decline a topic, remain silent, request distance, or end an exchange. Do not treat a personal disclosure as permission to investigate, publish it, or demand more.

If an unagreed contact occurs, stop it, acknowledge what happened without argument, and ask what support or distance the affected person wants. Resume only through a fresh agreement; otherwise end the physical interaction. Any documentation of the incident should contain only necessary information and must not be published without a separate basis and permission where required.

## 9. Session scope record

Use a short private record if useful. Do not collect identity documents, medical histories, or recordings merely to establish this protocol. A record is optional; the permission fields and confirmation are required whether communicated orally, in writing, or through another accessible method.

```text
Protocol version:
Session context, location, start, end:
Permission giver / touch initiator (names or chosen identifiers):
Mode:
Permitted body areas and exclusions:
Permitted action; skin/clothing; pressure; duration; repetition limit:
Communication method; pause/stop signal:
Exact scope read back and affirmatively confirmed:
Changes, pauses, withdrawals, or fresh agreements:
Record retention/deletion, if a record is kept:
```

Never use a record to contradict someone’s current refusal. Do not impose a fee or penalty for choosing `NO_TOUCH`, declining an activity, or withdrawing touch permission.

## 10. Scope of this draft

These are proposed operational rules for the artwork. They do not establish that a particular act is lawful or that an agreement constitutes valid consent under applicable law. Venue rules and applicable law still apply. The artist must confirm the intended default scope and participation eligibility before this draft is used in a live performance. The [minimal disclaimer](MINIMAL-DISCLAIMER.md) is a short acknowledgement, not a substitute for this protocol or for specific massage permission.

For background on clear, voluntary, ongoing agreement and withdrawal, see [RAINN’s consent guidance](https://rainn.org/share-the-facts/consent-101-respect-boundaries-and-building-trust/). That source addresses sexual consent; this artwork adopts communication and withdrawal principles for its nonsexual touch protocol. The specific modes, contact limits, and session procedure above are proposed rules for this work.
