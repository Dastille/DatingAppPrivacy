# PIPEDA letters (templates)

Copy, fill the bracketed fields. Do not attach government ID over email. Do not commit completed letters, exports, or ticket numbers to this repository.

Two templates:

1. **Access request** — send to the organization’s published privacy / DPO address **and** keep the headers.
2. **Investigator note** — send only if an OPC file is already open. Send it to the investigator, not to the company.

See [README.md](README.md) §8.2 for why the second letter exists.

---

## 1. Access request

Subject: PIPEDA access request — [full legal name] — [account email / phone / user id]

To the Privacy Officer / Data Protection Officer:

I am making a request for access to my personal information under Principle 4.9 of PIPEDA and section 8 of the Act.

Please provide, within thirty (30) days of receipt:

1. All personal information you hold about me, including but not limited to: account profile, messages metadata, photos, device identifiers, payment artifacts, advertising identifiers, inferred scores (desirability, fraud, safety, quality), moderation records, shadow restrictions, and vendor-shared copies.
2. The **sources** of that information.
3. The **uses** of that information, including automated decision-making.
4. The **names of third parties** to whom it has been disclosed, with data categories and purposes.
5. Retention periods and deletion logs for each class.
6. If any information is withheld, produce an **exemption log**: for each class of record, the **specific** PIPEDA subsection, why it is not severable, and why my personal information (inferred scores about me, inputs taken from my account, vendor names I was disclosed to) is confidential commercial information under s.9(3)(b). Access is the rule; withholding is the exception (*Bertucci v. Royal Bank of Canada*, 2016 FC 332). “Moderation integrity,” “proprietary algorithm,” “trade secret,” and “multiple threads” are not exemptions. A blanket covering inferred scores about me is not a response.

Do **not** ask me to send a government ID by email. If identity assurance is required, provide a secure portal and the minimum document set.

If you need an extension under s.8(4), you must notify me in writing within the original thirty days, with reasons.

Sincerely,
[name]
[email]
[date]
[optional: Office of the Privacy Commissioner of Canada — I will file a complaint if this request is ignored, answered with an empty export, or refused without a class-by-class exemption log.]

---

After you send it: save the original, every follow-up, timestamps, and Message-ID headers. Hash any export you receive (`sha256sum`). Empty exports are evidence, not closure. A final email saying no further information will be provided is evidence, not the end of the right.

---

## 2. Investigator note (OPC file already open)

Send to the investigator on the complaint. Fill the file number. Do not attach exports or ID.

Subject: PIPEDA complaint [file number] — request for exemption log and s.12.1 compulsion

I ask that the Office require the organization to produce a class-by-class exemption log for every withheld record: class, PIPEDA subsection, why it is not severable under s.9(3), and why inferred scores, account-derived inputs, and vendor disclosures about me are confidential commercial information.

s.9(3)(b) is a high-bar, specific exception (OPC Interpretation Bulletin: Access to Personal Information; *Bertucci v. Royal Bank of Canada*, 2016 FC 332). Principle 4.9.1 and 4.9.3 still require existence, use, disclosure, and third-party names even if model weights are withheld. Raw personal information about me is not a trade secret.

The Commissioner may summon and compel production (s.12.1). A posture that the Office does not force companies to respond, or that a blanket trade-secret claim is given the benefit of the doubt, inverts the Act: the organization must establish the exception. “Reasonable doubt” is not the test.

If the Office declines to use s.12.1, please record that decline in the s.13 report so the s.14 record is complete.

A blanket “trade secret” covering personal information about me is not a response.

Sincerely,
[name]
[email]
[date]
