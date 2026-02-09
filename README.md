# Professional Email Decision Support

This repository documents a project exploring how structured analysis and AI-assisted reasoning can help professionals decide **what to do next** when replying to difficult, high-stakes emails.

The focus is not on writing better emails, but on **reducing risk** in situations involving clients, managers, HR, suppliers, or other stakeholders where wording, timing, and tone matter.

---

## The Problem

Difficult professional emails often trigger:
- emotional reactions
- overthinking and multiple drafts
- second-guessing and delays
- defensive or apologetic replies
- accidental concessions or escalation

In high-pressure situations, a “polite” or “helpful” reply can unintentionally make things worse.

---

## The Approach (High Level)

Instead of generating generic responses, this project focuses on:
- identifying what an incoming email is *really doing* (pressure, assumptions, escalation, blame)
- determining the **safest next step**
- suggesting a reply that improves the recipient’s position without escalating or conceding unnecessarily

The goal is to help professionals move from uncertainty to clarity before replying.

---

## Example Scenarios

### Example 1: Compliance Pressure with Implied Escalation

**Incoming email:**

> Hi David,  
>  
> We’ve noticed that the information you provided doesn’t fully align with our standard compliance requirements. This should normally be resolved before proceeding further.  
>  
> At this stage, we need you to confirm that you’ll adjust your process accordingly so we can avoid any delays or escalation on our side.  
>  
> Please confirm how you plan to address this.

---

**Facts**
- The sender noticed the information provided does not align with standard compliance requirements.
- The sender states this should be resolved before proceeding.
- The sender is asking for confirmation that the process will be adjusted.
- The sender mentions avoiding delays or escalation.

**What This Email Represents**  
A request for compliance adjustment with an underlying threat of escalation.

**Why This Is the Next Best Step**
- The sender has not specified which requirements are unmet, making it impossible to respond substantively.
- Requesting specific details shifts the burden of proof to the sender and prevents a premature commitment to changing processes.
- It replaces a vague demand for “confirmation” with a concrete request for information.

**Suggested Reply**
> In order to address this accurately, please provide the specific compliance requirements or sections you are referencing. Once I have those details, I can review the alignment of the information provided and determine the necessary adjustments.

---

**Outcome Assessment**
- ✔ No admission of non-compliance  
- ✔ Does not agree to adjust process blindly  
- ✔ Shifts burden to specify requirements  
- ✔ Neutralizes escalation pressure  
- ✔ Moves from vague demand to concrete verification

---

### Example 2: Angry Customer Escalation with Refund Ultimatum

**Incoming email:**

> I’m extremely frustrated with this product. It hasn’t worked as advertised, and I’ve wasted a lot of time trying to make it usable. This is not what I expected when I signed up.  
>  
> At this point, I don’t want excuses — I want this resolved immediately. Either you fix this right away or issue a full refund. Please let me know how you plan to handle this.  
>  
> — Mark

---

**Facts**
- The sender is frustrated with the product performance.
- The sender feels the product does not work as advertised.
- The sender has spent time trying to make the product usable.
- The sender is demanding an immediate fix or a full refund.

**What This Email Represents**  
A high-pressure escalation with an ultimatum for a fix or a refund.

**Why This Is the Next Best Step**
- It shifts the burden of proof to the sender, requiring them to provide technical details before any concessions are made.
- It replaces the demand for an “immediate” resolution with a requirement for documentation.
- It prevents an emotional reaction by focusing strictly on technical and procedural facts.

**Suggested Reply**
> I have received your email. To ensure this is handled correctly, please provide a list of the specific features failing to perform as expected and the troubleshooting steps you have attempted so far. Having these details in writing will allow for a concrete review of the technical issues and the refund request.


### Example 3: Project Alignment Pressure with Imposed Deadline

**Incoming email:**

> I’m a bit concerned after reviewing the latest update. Some of the decisions reflected there don’t seem to align with what we discussed earlier, and it’s creating confusion on our side.  
>  
> At this point, leadership is asking whether we should continue in the current direction or reconsider the approach altogether. We need to be careful here, as timelines and accountability are now being reviewed.  
>  
> Please confirm today how you intend to proceed so we can decide next steps.  
>  
> — Anna

---

**Facts**
- The sender is concerned about recent updates.
- The sender states the updates do not align with previous discussions.
- Leadership is questioning the current direction versus reconsidering the approach.
- Timelines and accountability are under review.
- The sender has requested confirmation by the end of the day.

**What This Email Represents**  
Pressure and potential escalation regarding project alignment and accountability.

**Why This Is the Next Best Step**
- It shifts the burden of proof back to the sender to identify specific discrepancies.
- It avoids committing to a direction without concrete clarification.
- It neutralizes the imposed deadline by requiring documentation before proceeding.

**Suggested Reply**
> I have received your email. To ensure I address leadership’s concerns accurately, please provide the specific points from the latest update that you believe do not align with our previous discussions. Having these details in writing will allow for a proper review before any decision is made.




---

## What This Repository Is (and Isn’t)

**This repository is:**
- a public explanation of the problem and approach
- a collection of anonymized examples
- a demonstration of decision-focused thinking

**This repository is not:**
- the implementation
- the AI prompt or system instructions
- a deployable tool or service

The working system is maintained separately.

---

## Purpose

This project is intended for professionals who regularly deal with:
- clients
- managers
- HR or legal teams
- suppliers or partners

It is designed to support clearer decision-making under pressure, not to provide legal or HR advice.

---

*Designed for professional workplace communication.*
