# 🧩 QA Form Structure and Design Improvements Proposal

## 1. Attribute and Driver Framework
My form converts each attribute question into a written statement.  
Under each attribute, I list the related questions as **drivers** (or **behaviors**, if preferred).  

This approach makes the form easier to use, simplifies reporting, and allows feedback to be more precise.  
In the future, if any updates are needed, we can retain the main attribute and simply revise or replace the drivers — ensuring long-term scalability and consistency.

---

## 2️⃣ Reassurance & Issue Confirmation

This attribute sets clear parameters for how reassurance should be provided during a call.  
Specifically, it ensures that the **willingness to assist** is expressed **after confirming the issue**, but **before** giving information to resolve the caller’s concern.  

✅ Strengthens trust and clarity in the interaction.  


---

## 3️⃣ Professionalism

Created a **Professionalism** attribute that evaluates:  
- Background noise  
- Tone  
- Rude or abrupt behavior  

This ensures every call reflects a respectful, focused, and professional interaction.  


---

## 4️⃣ Patient Empathy & VIP Experience

Created a **Patient Empathy & VIP Experience** attribute that measures:  
- Tone adaptation  
- Personalization opportunities  
- Ownership  

Focuses on how well agents tailor communication, connect with the caller, and take responsibility for resolution.  

---

## 5️⃣ Emotional Regulation & De-escalation</summary>

Developed an **Emotional Regulation & De-escalation** attribute that addresses:  
- Emotional adaptation  
- Frustration acknowledgment  
- Conflict de-escalation  

Evaluates how effectively an agent manages emotions — both their own and the caller’s — to maintain calm, constructive conversations.  

---

## 6️⃣ Documentation: Phone Messages & Tasks

Created a **Documentation** attribute for **Phone Messages and Tasks** that maintains our current standards while adding flexibility.  

If a phone message or task was **not required** for the call type, it can be marked **N/A**, preventing unfair scoring deductions.  

---

## 7️⃣ Transfers & Escalations

Consolidated **Transfers** and **Escalations** into one attribute: **Transfers and Escalations**.  

- Scored **N/A** if no transfer or escalation was required.  
- Keeps evaluations relevant and concise.  

---

## 8️⃣ Scheduling & Coordination

Merged **Appointments, Transportation, Refills, and Referrals** into one attribute: **Scheduling & Coordination**.  

- Scored when those actions are required.  
- Mark **N/A** when not applicable.  

Ensures adaptability across multiple interaction types.  

---

## 9️⃣ Information Accuracy

Created an **Information Accuracy** attribute that ideally applies to **every interaction**.  

Evaluates:  
- Proper probing questions  
- Accuracy of provided information  
- Communication adjusted for the caller’s skill or comprehension level  


---

## 🔟 Compliance & Auto-Fails

Added a **Compliance & Auto-Fails** attribute that applies to **every single call**.  

- **Meets Expectations:** Agent follows all required protocols — points awarded.  
- **Auto-Fail:** Any breach of compliance standards automatically fails the form.  

Ensures accountability, consistency, and strict policy adherence.  

---

### ✅ Summary
This QA form design introduces a structured, behavior-based evaluation model that enhances clarity, fairness, and flexibility.  
By grouping related competencies, defining N/A scenarios, and ensuring compliance consistency, it strengthens data accuracy, coaching precision, and overall quality insights.

---
---
---

# The New ChenMed Scorecard

## 🧡 Patient Critical Attributes

<details>
<summary><strong>Greeting & Branding</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  

**Drivers:**  
- [ ] Fails to use approved greeting (center name or company name)  
- [ ] Omits self-introduction/name  
- [ ] Greets caller to incorrect Center or Company
- [ ] Answers call within 5 seconds

**Scoring Definition:**  
- **ME:** Opens with correct greeting, answers call within 5 seconds, includes name and Center brand  
- **NI:** Uses unapproved or missing greeting  

</details>

<details>
<summary><strong>Patient Identity Verification</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  

**Drivers:**  
- [ ] Fails to confirm full name  
- [ ] Fails to confirm date of birth  

**Scoring Definition:**  
- **ME:** Correctly verifies patient’s full name and DOB before providing information from chart  
- **NI:** Skips or inadequately performs identity verification steps  

</details>

<details>
<summary><strong>Reassurance & Issue Confirmation</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  

**Drivers:**  
- [ ] Does not paraphrase reason for call back to caller.
- [ ] Does not offer a willingness to help  
- [ ] Reassures the caller after addressing the issues  
- [ ] Reassures the caller before learning what the issue is


**Scoring Definition:**  
- **ME:** Paraphrase reason for call and provides reassurance (e.g., "I'll be happy to help with scheduling your transportation today.")  
- **NI:** Skips confirmation, leaving caller uncertain  

</details>

<details>
<summary><strong>Professionalism</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  

**Drivers:**  
- [ ] Background noise disrupts professionalism  
- [ ] Uses short, sarcastic, or rushed answers  
- [ ] Speaks too fast/slow or intentionally rudely interrupts the caller  
- [ ] Tone is not warm or welcoming  
- [ ] Belittling the caller  
- [ ] Condescending or impatient tone  

**Scoring Definition:**  
- **ME:** Maintains professional, polite, and welcoming tone throughout the interaction  
- **NI:** Uses inappropriate, rushed, or disengaged communication  

</details>

<details>
<summary><strong>Active Listening & Engagement</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  

**Drivers:**  
- [ ] Caller has to repeat information already provided multiple times  
- [ ] Agent appears distracted or inattentive  
- [ ] Misses cues in patient’s or caller’s request  

**Scoring Definition:**  
- **ME:** Demonstrates focus, acknowledges patient needs, avoids repetition  
- **NI:** Misses requests, requires caller to repeat  

</details>

<details>
<summary><strong>Holds</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Places caller on hold without asking for permission  
- [ ] Fails to thank patient upon return  

**Scoring Definition:**  
- **ME:** Requests permission for hold and thanks caller upon return  
- **NI:** Places caller on hold abruptly without acknowledgment  
- **N/A:** Holds not utilized on interaction  

</details>

<details>
<summary><strong>Call Closing</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Fails to summarize resolution or next steps  
- [ ] Does not set correct expectations for follow-up/turnaround time  
- [ ] Skips professional closing (e.g., “Thank you for choosing [Brand/Center]”)  

**Scoring Definition:**  
- **ME:** Summarizes resolution and expectations, uses professional closing, and selects correct disposition  
- **NI:** Ends call without clarity, skips closing  
- **N/A Applicable:** Only if the call disconnects prematurely or is otherwise out of the STC’s control  

</details>

<details>
<summary><strong>Patient Empathy & VIP Experience</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Fails to acknowledge or adapt to patient’s emotional tone, urgency, or sensitivity  
- [ ] Misses opportunities to personalize care (e.g., comfort language, positive reinforcement, name usage)  
- [ ] Responds robotically or without compassion  
- [ ] Does not demonstrate ownership or priority when interacting with high-need or VIP patients  

**Scoring Definition:**  
- **ME:** Demonstrates empathy, compassion, and attentiveness through tone, pace, and phrasing. Personalizes the experience, validates patient concerns, and adapts communication appropriately for high-sensitivity or VIP interactions. Balances warmth and professionalism to create a high-trust experience.  
- **NI:** Uses scripted or impersonal tone, overlooks patient emotion or urgency, or fails to provide reassurance and ownership.  
- **N/A:** Only if the call is fully transactional with no emotional or sensitive context.  

</details>

<details>
<summary><strong>Emotional Regulation & De-escalation</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Matches caller’s frustration or raises voice  
- [ ] Fails to remain calm, empathetic, or composed during emotional exchanges  
- [ ] Does not acknowledge patient frustration or concern appropriately  
- [ ] Misses opportunity to stabilize or de-escalate through tone and phrasing  

**Scoring Definition:**  
- **ME:** Maintains calm, patient-centered composure under pressure. Acknowledges emotion without defensiveness, uses tone modulation and empathy to reduce tension, and redirects the conversation toward a solution-focused path.  
- **NI:** Becomes reactive, impatient, or fails to de-escalate when the patient is upset. Misses verbal or emotional cues requiring tone adjustment.  
- **N/A:** Applicable only when no emotional escalation or conflict occurred during the interaction.  

</details>


---

## 💼 Business Critical Attributes

<details>
<summary><strong>Documentation</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Fails to use correct message templates/ProKeys  
- [ ] Did not create a Phone Message or Task when required  
- [ ] Selected inaccurate Message type or Priority (Phone Messages only)
- [ ] Created a Phone Message or Task when NOT required  
- [ ] Did not verbally confirm if message/task includes caller and relationship to the patient  
- [ ] Phone Message/Task does NOT include reason for the call or concern, accurate information, and all pertinent information provided by the caller  
- [ ] Did NOT verbally confirm message/task includes call back number  
- [ ] Did NOT verbally confirm or summarize message/task and set proper expectations for turnaround times.  

**Scoring Definition:**  
- **ME:** Message complete, accurate, follows Phone Message & Task SOP templates  
- **NI:** Message missing required details or incorrectly logged  
- **N/A:** Phone Message or Task was not required on interaction and STC did not create one  

</details>

<details>
<summary><strong>Transfers and Escalations</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Transfers/Escalates without offering assistance  
- [ ] Provides no explanation for transfer/Escalation  
- [ ] Fails to gather relevant info before transfer/escalation  
- [ ] Transfers/escalate to wrong department  
- [ ] Omits warm transfer/escalation introduction  
- [ ] Did NOT escalate when required by procedure  

**Scoring Definition:**  
- **ME:** Provides clear reason, gathers info, completes warm transfer  
- **NI:** Transfers/escalate abruptly, incorrectly, or without context  
- **N/A:** Transfer/escalattion did not happen on the call or was required by procedure 

</details>

<details>
<summary><strong>Scheduling & Coordination</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Skips clarifying questions for appointments/transportation/refills/referrals  
- [ ] Does not obtained all required or needed information as required for and by procedure  
- [ ] Incorrectly handles transportations, appointments, refills, or referrals, OR omits key steps found in corresponding SOP  
- [ ] Fails to verify eligibility or to use tools properly (e.g., ePrescribe check, checking appointments, checking Lyft/Uber, checking Leading Reach)  

**Scoring Definition:**  
- **ME:** Asks required questions, follows SOP, schedules accurately  
- **NI:** Skips verification or misses SOP steps, leading to errors  
- **N/A:** Does not manipulate transportation, appointments, referrals, or refills  

</details>

<details>
<summary><strong>Information Accuracy</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Skips clarifying questions needed to understand the patient’s request or the update in Dash  
- [ ] Provides information that is incomplete, inaccurate, or missing key details relevant to the patient’s needs  
- [ ] Communicates in a way that is unclear, overly technical, or confusing to the patient  

**Scoring Definition:**  
- **ME:** Asks clarifying/relevant questions, provides accurate and complete information, and communicates in a clear and understandable manner  
- **NI:** Misses critical questions, provides incomplete/inaccurate information, or escalates without fully understanding the issue  
- **N/A:** No clarification, updates, or escalations were required for the interaction that previous attributes covered. 

</details>

<details>
<summary><strong>Dispositions</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  
- [ ] N/A  

**Drivers:**  
- [ ] Fails to disposition the call in InContact  
- [ ] Selects incorrect disposition  

**Scoring Definition:**  
- **ME:** Selects the correct disposition and ensures it reflects the outcome of the call  
- **NI:** Skips disposition or selects an incorrect option, impacting record accuracy and care continuity  
- **N/A Applicable:** Only if system outage or technical error prevents disposition or SOP does not cover disposition 

</details>


---

## 🔏 Regulatory Critical Attribute

<details>
<summary><strong>Compliance & Auto-Fails</strong></summary>

**Scoring Options:**  
- [ ] Meets Expectation  
- [ ] Needs Improvement  

**Drivers:**   
- [ ] Profanity  
- [ ] Hanging up on a caller  
- [ ] Not answering the call    
- [ ] Providing any type of medical advice/opinion  

**Scoring Definition:**  
- **ME:** Answers a call while using professionally language throghout without hanging up or providing any form of medical advice or opinion.

</details>

---
---

# ⚙️ Scoring Methodology

Each **driver** within the scorecard contributes to the total evaluation score based on its assigned point value.  

- ✅ **Meets Expectation (ME):** Full points are retained — no deductions applied.  
- ⚠️ **Needs Improvement (NI):** Points for that attribute are deducted from the total score based on driver's worth.  
- 🚫 **Not Applicable (N/A):** Attribute is excluded from scoring — no points gained or lost.  

# 🔏 Compliance Auto-Fail

The **Compliance attribute** is non-negotiable.  
If any compliance driver is missed or marked **Needs Improvement**, the entire evaluation automatically receives a **0% score**. If Scored **Meets Expectation** Attribute's worth may or may not contribute to overall evaluation score. 

Agents should therefore always strive to meet expectations under this attribute to avoid triggering an auto-fail. 

# 🧠 General Scoring Principles

- **Default to Coaching, Not Penalizing:** If you’re torn between ME and NI, default to **ME** and add a coaching note instead of a deduction.
- **N/A Is Not a Shortcut:** Only mark N/A when an attribute genuinely didn’t apply to the call, not because the advisor missed the opportunity.
- **NI Requires Repetition or Impact:** Use NI when the issue clearly affects the patient experience, creates confusion, or breaks compliance.
- **Always Add Context:** Each score (especially NI or N/A) must include a brief comment explaining *why* it was chosen — this ensures calibration and transparency.

---

# 🧡 Patient Critical Attributes FAQ

## Greeting & Branding
**Q:** What if the agent forgets their name but uses the correct greeting?  
✅ **ME:** "Thank you for calling ABC Medical, how can I help?"  
⚠️ **Coaching:** Encourage adding their name.  
❌ **NI:** "Hello?" or missing greeting/brand reference.  

**Q:** Can N/A be used here?  
🟡 **No.** Greeting is always expected unless the call was disconnected before the agent spoke.

---

## Patient Identity Verification
**Q:** What if only one identifier (name or DOB) is verified?  
⚠️ **NI:** Must confirm *both* full name and DOB before discussing PHI.  

**Q:** What if the patient refuses to verify information?  
✅ **ME:** If the agent followed protocol and documented refusal appropriately.  
💡 Add coaching note if tone or phrasing could improve compliance confidence.

---

## Reassurance & Confirmation of Assistance
**Q:** Does “How can I help?” count as reassurance?  
✅ **ME:** Yes, if tone is welcoming and agent sounds willing to assist.  
❌ **NI:** Robotic or abrupt transitions (e.g., “What’s the issue?”).  

**Q:** Is reassurance required after resolution?  
✅ **ME:** “I’m glad we got that sorted out!”  
⚠️ **NI:** Ending call coldly after issue resolution.

---

## Professionalism
**Q:** What if tone is fine but background noise exists?  
⚠️ **Coaching:** If minor noise.  
❌ **NI:** If noise repeatedly distracts or impacts comprehension.  

**Q:** How do I score sarcasm or rushed behavior?  
❌ **NI:** Even subtle impatience or abrupt phrasing undermines professionalism.

---

## Active Listening & Engagement
**Q:** When does repetition count against the agent?  
❌ **NI:** If the patient repeats info 2+ times due to agent distraction or inattention.  
✅ **ME:** Agent acknowledges details and clarifies without redundancy.  

**Q:** What if there was silence while checking info?  
✅ **ME:** Acceptable if explained (“Give me a moment while I check that.”).  

---

## Holds
**Q:** When is N/A appropriate?  
✅ **N/A:** When no hold occurred during the call.  

**Q:** What if the hold was brief but agent didn’t ask permission?  
❌ **NI:** Always obtain consent and thank the caller afterward.  
✅ **ME:** “May I place you on a brief hold while I check that?”  

---

## Call Closing
**Q:** When is N/A allowed?  
✅ **N/A:** Call dropped or disconnected beyond agent control.  

**Q:** What if they summarize but forget the branded close?  
⚠️ **ME + Coaching:** Brand reinforcement is important but not critical to pass.  
❌ **NI:** No summary or unclear next steps.

---

## Patient Empathy & VIP Experience
**Q:** What if the patient shows no emotion?  
✅ **ME:** Still assess tone and personalization — warmth and natural pacing count.  
❌ **NI:** Robotic or transactional delivery with no acknowledgment.  

**Q:** Can scripted empathy qualify as ME?  
✅ **Yes,** if it feels genuine and natural.  

**Q:** What defines a VIP or sensitive experience?  
🟣 **Examples:** High-anxiety callers, repeat medical issues, or high-priority patients.  

---

## Emotional Regulation & De-escalation
**Q:** What if the caller becomes frustrated but the agent ignores tone?  
❌ **NI:** Missed emotional cue — must acknowledge and stabilize.  

**Q:** What if no escalation occurred?  
✅ **N/A:** Attribute only applies when emotion or conflict is present.  

**Q:** What does successful de-escalation sound like?  
✅ **ME:** “I completely understand how frustrating that must be. Let’s take care of this together.”

---

# 💼 Business Critical Attributes FAQ

## Documentation
**Q:** When is N/A valid?  
✅ **N/A:** No Phone Message or Task required per SOP.  

**Q:** What counts as incomplete documentation?  
❌ **NI:** Missing callback number, reason, or patient details.  
✅ **ME:** Complete, accurate message following template.  

**Q:** What if the message was logged but missing small context?  
⚠️ **ME + Coaching:** Non-critical details can be handled via feedback, not deduction.

---

## Transfers & Escalations
**Q:** What if the agent transfers without explanation?  
❌ **NI:** Fails to set caller expectations or confirm receiving department.  

**Q:** Can I give ME if escalation was required but not initiated?  
❌ **NI:** Required escalations must occur.  

**Q:** What’s a “warm transfer”?  
✅ **Definition:** Introduces the caller, summarizes the issue, and ensures connection before disconnecting.  

---

## Scheduling & Coordination
**Q:** When can this be N/A?  
✅ **N/A:** Call didn’t involve scheduling, refills, referrals, or transport.  

**Q:** What if agent misses one small SOP step but outcome is correct?  
⚠️ **ME + Coaching:** Focus on patient impact; deduct only for process gaps that risk accuracy.  

**Q:** Example of NI?  
❌ **NI:** Fails to verify eligibility or schedules wrong time/location.

---

## Information Accuracy
**Q:** What qualifies as NI?  
❌ **NI:** Wrong info, missing details, or confusion that impacts patient understanding.  
✅ **ME:** Clear, accurate, and confidently delivered info.  

**Q:** Can clarification questions impact the score?  
✅ **Yes:** Asking thoughtful clarifying questions often earns **ME** — it shows engagement and diligence.

---

## Dispositions
**Q:** When is N/A acceptable?  
✅ **N/A:** Technical issue or SOP explicitly excludes disposition step.  

**Q:** What if agent selects disposition but wrong category?  
❌ **NI:** Impacts data accuracy and care coordination.  
✅ **ME:** Correct disposition matching the call’s outcome.

---

# 🔏 Regulatory Critical Attribute FAQ

## Compliance & Auto-Fails
**Q:** When do auto-fails apply?  
🚨 **Always** for:  
- Profanity  
- Hanging up on a caller  
- Not answering calls  
- Providing medical advice or opinion  

**Q:** What if profanity came from the patient?  
✅ **ME:** As long as the agent remained professional and composed.  

**Q:** Can an agent recover from tone issues if compliance was intact?  
✅ **Yes,** professionalism and composure can offset tone missteps — but compliance violations are *never coachable.*

---

# 🧩 Evaluator Tips

- **Flag edge cases for calibration:** If unsure how to apply ME/NI/N/A, tag for review in calibration or QA sync.  
- **Use SOSA/OREO in comments:**  
  - **Situation:** Briefly summarize the scenario.  
  - **Observation:** Describe what was heard.  
  - **Suggestion:** Offer actionable improvement.  
  - **Appreciation:** Reinforce positives to end constructively.  
- **Consistency is key:** Apply same logic across calls, ensuring fairness and alignment with QA philosophy.  

---
# 🧮 Communication & Call Flow Equations

# 📐 Real-World Call Scenario Equations (3–5 per attribute)

---

## Greeting & Branding
- **Patient:** (call answered)  
  **STC:** “Thank you for calling [Center], this is [Name].” + **Action:** Answer within 5s = **Professional Start / Meets Expectation**

- **Patient:** (caller begins speaking before intro)  
  **STC:** “Hi — I’m [Name] with [Center], I’ll help you today. May I confirm who I’m speaking with?” = **Brand + Ownership**

- **Patient:** “Hello?”  
  **STC:** (No greeting) + **Action:** Jumps into question = **Needs Improvement (missing greeting/name)**

---

## Patient Identity Verification
- **Patient:** “This is John Smith.”  
  **STC:** “Thanks, John — can you confirm your date of birth for security?” + **Action:** Do not provide details from chart until confirmed = **Verified Identity / ME**

- **Patient:** (agent asks chart question before verifying)  
  **STC:** Provides info without verification = **NI (compliance risk)**

- **Patient:** “I’m calling on behalf of my mom.”  
  **STC:** “Can you confirm your mom's date of birth and full name please?” + **Action:** Record relationship = **Proper verification**

---

## Reassurance & Confirmation of Assistance
- **Patient:** “I need help with my meds.”  
  **STC:** “I’m happy to help — let me pull your chart and we’ll review together.” + **Action:** Sets expectation = **Reassurance + Ownership**

- **Patient:** “Will this take long?”  
  **STC:** “It should only take a few minutes, I’ll keep you updated.” = **Clear expectation setting**

- **Patient:** (explains problem)  
  **STC:** (no acknowledgement) + **Action:** Goes silent = **Needs Improvement (caller left uncertain)**


---

## Professionalism
- **Patient:** (speaks over agent)  
  **STC:** Calmly: “I hear that — allow me to finish so I can help you best.” + **Action:** Maintains polite tone = **Professional, ME**

- **Patient:** “You’re wrong.”  
  **STC:** “I understand your concern, allow me to find the right info for you.” + **Action:** Avoids sarcasm/defensiveness = **De-escalation + professionalism**

- **Patient:** (agent uses slang/sarcasm)  
  **STC:** “Whatever” or laughs inappropriately = **NI (unprofessional language/tone)**

---

## Active Listening & Engagement
- **Patient:** “I’ve been waiting for days for this refill.”  
  **STC:** “You’ve been waiting and I’m sorry. Let me confirm the refill status and next steps.” + **Action:** Paraphrases & asks clarifying Qs = **Active Listening / ME**

- **Patient:** (gives specific time/date)  
  **STC:** Repeats back: “So it was on June 12 at 2pm — is that right?” = **Clarify + confirmation**

- **Patient:** (agent interrupts repeatedly)  
  **STC:** Cuts off patient multiple times = **NI (missed cues / frustration)**


---

## Holds
- **Patient:** (during info check)  
  **STC:** “May I place you on a brief hold while I check?” → **Patient:** “Yes” → **STC:** Thanks patient on return = **Proper Hold / ME**

- **Patient:** (agent places on hold without asking)  
  **STC:** Puts caller on hold abruptly = **NI**

- **Patient:** (hold required but lengthy)  
  **STC:** “This may take up to 3 minutes — can I place you on hold or call you back?” + **Action:** Offers alternative = **Patient-centered hold**

- **Patient:** (caller returned to)  
  **STC:** Forgetting to thank or recap after hold = **NI (missed courtesy)**

---

## Call Closing
- **Patient:** (issue resolved)  
  **STC:** “To recap, we scheduled your transportation for Thursday; you’ll get a confirmation text. Is there anything else?” + **Action:** “Thank you for calling [Center].” = **Clear close + ME**

- **Patient:** (no next steps given)  
  **STC:** Ends with “bye” and no summary = **NI (unclear closure)**

- **Patient:** (call dropped unexpectedly)  
  **STC:** System disconnects mid-call = **N/A (document and try callback per SOP)**


---

## Patient Empathy & VIP Experience
- **Patient:** “I’m not feeling well and I have an important appointment tomorrow.”  
  **STC:** “I’m so sorry you’re unwell. Let me prioritize this and see how we can expedite your request.” + **Action:** Escalates or documents VIP flag = **VIP Care / ME**

- **Patient:** “I’m anxious about this procedure.”  
  **STC:** “That’s completely understandable. I’ll walk you through what to expect and note your concern for the nurse.” = **Empathy + personalization**

- **Patient:** (repeat VIP caller)  
  **STC:** Uses name + references prior note + offers extra reassurance = **High-touch personalization / ME**

---

## Emotional Regulation & De-escalation
- **Patient:** (yells) “This has been terrible!”  
  **STC:** “I’m sorry you’ve had that experience. Let me make this right... here’s what I can do...” + **Action:** Calm tone + ownership = **De-escalation / ME**

- **Patient:** (accuses agent) “You didn’t call me back!”  
  **STC:** “I hear your frustration, let me check the notes and find the next steps.” + **Action:** No matching frustration = **Stabilizes call**

- **Patient:** (continues escalating)  
  **STC:** Matches tone or becomes defensive = **NI (escalation risk)**

- **Patient:** (quiet but upset)  
  **STC:** “I can tell this is upsetting, would it help if I summarized what I’ll do next?” = **Gentle validation + solution**

---

# 💼 Business Critical Attributes

## Documentation
- **Patient:** (reporting instructions)  
  **STC:** Logs phone message with reason + callback # + relationship = **Complete Documentation / ME**

- **Patient:** (agent forgets details)  
  **STC:** Creates note missing critical call reason or callback = **NI**

- **Patient:** (calls to request task)  
  **STC:** Uses correct template + tags priority + confirms turnaround time with patient = **SOP-aligned documentation**

- **Patient:** (agent documents, but wrong template)  
  **STC:** Uses incorrect message type = **NI (routing/priority risk)**

---

## Transfers & Escalations
- **Patient:** Requests specialty help  
  **STC:** “I will transfer you to [Specialty] with a brief summary, please hold.” + **Action:** Introduces caller to receiving clinician = **Warm Transfer / ME**

- **Patient:** (agent transfers cold)  
  **STC:** Puts caller through without context = **NI (bad handoff)**

- **Patient:** Needs escalation but agent fails to gather info  
  **STC:** Transfers without key details = **NI (inefficient escalation)**

---

## Scheduling & Coordination
- **Patient:** “I need an appointment next Tuesday.”  
  **STC:** Confirms date/time, verifies eligibility, and enters appointment per SOP = **Accurate Scheduling / ME**

- **Patient:** “Can I get transportation?”  
  **STC:** Checks Lyft/Uber SOP, confirms pickup details = **Complete coordination**

- **Patient:** (agent skips required verification)  
  **STC:** Schedules without confirming eligibility = **NI**

---

## Information Accuracy

- **Patient:** (agent guesses) “It should be next week” (no lookup) = **NI (avoid guessing)**

- **Patient:** (agent paraphrases to confirm)  
  **STC:** “So you mean the blood test from Oct. 1 — is that correct?” = **Confirm + accuracy**

---

## Dispositions

- **Patient:** Agent leaves wrong disposition (e.g., Resolved when escalation required) = **NI**

- **Patient:** System outage prevents disposition  
  **STC:** Documents in notes and flags for QA = **N/A with documentation**

---

# 🔏 Regulatory Critical Attribute

## Compliance & Auto-Fails
- **Patient:** Uses profanity toward agent  
  **STC:** Remains professional, does not respond with profanity = **ME (if agent stayed professional)**

- **Patient:** Asks for medical diagnosis (“What should I do?”)  
  **STC:** “I can’t provide medical advice; I’ll connect you with a clinician or schedule a call.” + **Action:** Escalate per SOP = **Compliance maintained / ME**

- **Patient:** Agent gives medical opinion or prescribes action = **Auto-Fail (NI)**

- **Patient:** Agent hangs up on caller intentionally = **Auto-Fail (0%)**
---

# 🧡 Patient Critical Attributes

<details>
<summary>Greeting & Branding 📐 Quality Equations</summary>

✅ **Equations**
- Proper Greeting + Self-Introduction + Center Name = Professional First Impression  
- Answer in ≤5 Seconds + Correct Brand Mention = Meets Expectation  
- No Greeting + No Name = Needs Improvement  
- Greeting + Name + Confirmation of Help = Trust Building  
- Delayed Answer + Missing Brand = Reduced Professionalism  

</details>

---

<details>
<summary>Patient Identity Verification 📐 Quality Equations</summary>

✅ **Equations**
- Confirm Name + Confirm DOB = Verified Identity  
- Skip Verification + Share Info = HIPAA Risk  
- Name Confirmation + Clarify Spelling = Accuracy  
- DOB Confirmation + Secure Tone = Trust  
- Verification + Chart Reference = Safe Disclosure  

</details>

---

<details>
<summary>Reassurance & Confirmation of Assistance 📐 Quality Equations</summary>

✅ **Equations**
- Offer Help + Positive Tone = Caller Confidence  
- “I’m happy to help” + Empathy Phrase = Reassurance  
- Caller Concern + Calm Confirmation = Emotional Stability  
- No Reassurance + Silence = Caller Uncertainty  
- Clarify Issue + Confirm Support = Call Control  

</details>

---

<details>
<summary>Professionalism 📐 Quality Equations</summary>

✅ **Equations**
- Warm Tone + Clear Pacing = Professional Delivery  
- Calm Voice + Active Engagement = Confidence  
- Sarcasm + Rushed Delivery = Needs Improvement  
- Respect + Politeness = Professional Experience  
- Interruptions – Patience = Quality Loss  

</details>

---

<details>
<summary>Active Listening & Engagement 📐 Quality Equations</summary>

✅ **Equations**
- Full Attention + Acknowledgment = Active Listening  
- Repetition Avoidance + Paraphrasing = Understanding  
- Eye Contact (tone equivalent) + Patience = Caller Trust  
- Distraction + Missed Cue = Needs Improvement  
- Clarify + Confirm + Respond = Engaged Communication  

</details>

---

<details>
<summary>Holds 📐 Quality Equations</summary>

✅ **Equations**
- Ask Permission + Thank on Return = Positive Hold Experience  
- Silent Hold – Acknowledgment = Caller Frustration  
- Short Hold + Polite Return = Professionalism  
- Explain Reason + Confirm Return = Call Control  
- Hold Properly + Smooth Transition = Efficiency  

</details>

---

<details>
<summary>Call Closing 📐 Quality Equations</summary>

✅ **Equations**
- Summary + Next Steps = Clarity  
- Proper Closing + Brand Mention = Professional Ending  
- “Thank You” + Confirmation = Customer Retention  
- Skipped Closing + Unclear Resolution = Needs Improvement  
- Recap + Verify Understanding = Confidence in Completion  

</details>

---

<details>
<summary>Patient Empathy & VIP Experience 📐 Quality Equations</summary>

✅ **Equations**
- Emotion Recognition + Validation = Empathy  
- Patient Name + Comfort Phrase = Personalization  
- Concern Acknowledgment + Ownership = VIP Care  
- Robotic Tone – Warmth = Needs Improvement  
- Empathy + Solution Orientation = Trust & Loyalty  

</details>

---

<details>
<summary>Emotional Regulation & De-escalation 📐 Quality Equations</summary>

✅ **Equations**
- Calm Tone + Empathy = De-escalation  
- Validation + Assurance = Emotional Stability  
- Escalation Cue + Composed Response = Professional Control  
- Matching Frustration + Raised Voice = Needs Improvement  
- Redirect + Positive Framing = Recovery  

</details>

---

# 💼 Business Critical Attributes

<details>
<summary>Documentation 📐 Quality Equations</summary>

✅ **Equations**
- Accurate Notes + SOP Template = Complete Message  
- Caller Info + Call Reason + Callback # = Full Documentation  
- Missing Template + No Summary = QA Deduction  
- Confirmation + Accuracy = Compliance  
- Organized Entry + Clarity = Operational Efficiency  

</details>

---

<details>
<summary>Transfers & Escalations 📐 Quality Equations</summary>

✅ **Equations**
- Clear Explanation + Warm Transfer = Seamless Handoff  
- Gathered Info + Correct Department = Efficiency  
- Cold Transfer + No Context = Poor Experience  
- Offer Help + Explain Reason = Transparency  
- Right Channel + Proper Tone = Smooth Escalation  

</details>

---

<details>
<summary>Scheduling & Coordination 📐 Quality Equations</summary>

✅ **Equations**
- Verify Info + Follow SOP = Accurate Scheduling  
- Confirm Date + Time + Location = Complete Coordination  
- Missed Steps + Inaccurate Info = Needs Improvement  
- Clarify + Document + Confirm = Seamless Process  
- Double-Check Eligibility + Confirmation = Trust  

</details>

---

<details>
<summary>Information Accuracy 📐 Quality Equations</summary>

✅ **Equations**
- Clarify Question + Confirm Detail = Accuracy  
- Verified Info + Clear Delivery = Quality Communication  
- Guesswork + No Clarification = Error Risk  
- Transparency + Simplicity = Caller Understanding  
- SOP + Fact Check = 100% Accuracy  

</details>

---

<details>
<summary>Dispositions 📐 Quality Equations</summary>

✅ **Equations**
- Correct Outcome + Matching Disposition = Accuracy  
- Follow SOP + Confirm End Result = QA Compliance  
- Skipped Dispo + Wrong Label = Incomplete Record  
- Technical Error + Documentation = N/A Use  
- Clear Resolution + Accurate Coding = Data Integrity  

</details>

---

# 🔏 Regulatory Critical Attribute

<details>
<summary>Compliance & Auto-Fails 📐 Quality Equations</summary>

✅ **Equations**
- Professional Language + Courtesy = Compliance  
- Answer Call + Avoid Advice = Safety  
- Medical Opinion + Non-Clinician Role = Auto-Fail  
- Respect + Proper Boundaries = Regulation Alignment  
- HIPAA Awareness + Tone Control = Patient Trust  

</details>

---

# Example Additions to the CallFlow and Scripts SOP

## Professionalism in Communication

**Did STC maintain a professional, warm, and welcoming tone throughout the call?**  
*(Refer to Evaluation Form Question 2.1)*

### Sample Scripts
- “Thank you for calling [Chen Senior / JenCare / Dedicated / InTune Health]. My name is [Name]. How may I assist you today?”
- “It’s my pleasure to help you today. Let’s get started.”
- “I’ll be happy to take care of that for you.”
- “I appreciate your patience. Let’s work through this together.”
- “I’m here to help however I can.”

### Avoid
- Speaking too quickly or slowly  
- Interrupting the caller  
- Using sarcasm or sounding rushed  
- Dismissive phrases like “That’s not my job” or “You’ll have to call someone else”

---

## Active Listening & Engagement

**Did STC demonstrate attentiveness and avoid requiring the caller to repeat themselves?**  
*(Evaluation Form Question 2.2)*

### Best Practices
- Take notes during the call to avoid asking for repeated information  
- Paraphrase or repeat back key points to confirm understanding  
- Acknowledge the caller’s concerns before responding

### Sample Scripts
- “Just to make sure I understand, you’re calling about [summarize issue]. Is that correct?”
- “Thank you for sharing that. Let me confirm I have everything right…”
- “I hear that this has been frustrating for you. Let’s see how we can resolve it.”
- “I understand you’ve already explained this. Let me take it from here.”

---

## Patient Empathy & VIP Experience

**Did STC personalize the interaction and demonstrate empathy and compassion?**  
*(Evaluation Form Question 2.3)*

### Sample Scripts
- “I’m so sorry you’ve had to deal with this. Let’s make sure we get it resolved today.”
- “I completely understand how important this is to you.”
- “You’ve been through a lot — thank you for your patience.”
- “I’ll make this a priority and follow up to ensure it’s taken care of.”
- “We truly value you as a patient, and I want to make sure you feel supported.”

### Personalization Tips
- Use the caller’s name naturally throughout the call  
- Match tone and pace to the caller’s emotional state  
- Offer reassurance and ownership of the issue

---

## Emotional Regulation & De-escalation

**Did STC remain calm, composed, and solution-focused during emotional or escalated interactions?**  
*(Evaluation Form Question 2.4)*

### Sample Scripts
- “I hear your frustration, and I want to help make this right.”
- “Let’s take this one step at a time — I’m here with you.”
- “I understand this has been upsetting. Let’s work together to find a solution.”
- “Thank you for sharing that with me. I’m going to do everything I can to help.”
- “I’m here to support you, and I appreciate you staying on the line with me.”

### Avoid
- Raising your voice or matching the caller’s frustration  
- Saying “calm down” or “you’re overreacting”  
- Ignoring emotional cues or brushing off concerns

