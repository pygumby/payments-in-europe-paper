# Payments in Europe: a review

Lucas Konstantin Bärenfänger<br>
[blockrookie.com](https://blockrookie.com)

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

1. [Introduction](#1-introduction)
2. [Institutions and legislation](#2-institutions-and-legislation)
3. [The Payment Services Directive](#3-the-payment-services-directive)
   1. [The PSD of 2007](#31-the-psd-of-2007)
   2. [The PSD2 of 2015](#32-the-psd2-of-2015)
4. [The Single Euro Payments Area](#4-the-single-euro-payments-area)
   1. [The SEPA project](#41-the-sepa-project)
   3. [Clearing and settlement](#42-clearing-and-settlement)
   4. [SEPA Credit Transfer](#43-sepa-credit-transfer)
   5. [SEPA Direct Debit](#44-sepa-direct-debit)
5. [Conclusion](#5-conclusion)
6. [References](#6-references)

## 1. Introduction

In banking and financial services, payments are increasingly becoming the focus of interest.
It can be argued that this trend is mainly attributable to two factors:
Payment services represent a steady source of profit for financial institutions in prolonged low-interest periods.
Moreover, the payments domain itself is being disrupted by all-digital payment solutions, based on, for example, blockchain technology.

The domain of payments is, however, an incredibly vast field that is all but trivial to understand.
Today’s payment systems are the cumulative result of many years of regulation, private initiatives, technological innovation and other influences.
It is, therefore, the goal of this paper to “cut through the noise” and provide a clear introduction into the existing payments landscape, providing innovators and entrepreneurs with the overview necessary to navigate this complex territory.
Accordingly, the main contribution of this paper lies in the selection of topics being discussed—or not.
This paper’s focus is the European payments sector—both because it can be considered fairly homogenized and, therefore, makes for a good subject of study as well as because most of what affects the payment markets of the individual European countries are, in fact, initiatives on a pan-European level.
Consequently, however, card payments are beyond the scope of this paper, as prominent card payment schemes, e.g., MasterCard and Visa, are international schemes.
Cash payments and other paper-based payment instruments such as cheques are excluded as well, as they are less relevant in the context of innovation and technology.

Section 2 provides an overview of institutions and legislation relevant in the context of payments in Europe.
The most important institutions of the European payments domain—public and private sector—are presented as well as the key EU Directives and Regulations.
Section 3 addresses the most important of these regulatory initiatives—the EU Directive known as the Payment Services Directive (PSD).
Both its original version of 2007 and the revised version of 2015 are discussed in terms of origin, goals and key provisions.
Section 4 covers the Single Euro Payments Area (SEPA), the most important private-sector initiative in European payments.
After the origins and objectives of the SEPA project are discussed, the two central payment instruments of the initiative, i.e., SEPA Credit Transfer (SCT) and SEPA Direct Debit (SDD), are introduced—only after briefly digressing into clearing and settlement systems, however, as is necessary to understand the aforementioned payment instruments.
Section 5 summarizes the findings.

### 2. Institutions and legislation

This section provides an overview of institutions and legislation relevant in the payments domain in Europe.
It is based on the respective chapters of the report on “Payment and Securities Settlement Systems in the European Union” [[1](#r01)] by the **European Central Bank (ECB)**, which was published as the fourth edition of their so-called “Blue Book” in 2007.
The information presented here has been updated and extended as necessary.

As part of the effort to provide a “general institutional background,” the report states that different names exist “to clarify which central banks are meant in which context.”
The name **Eurosystem** “comprises” the ECB as well as the **national central banks (NCBs)** of the “EU Member States which have adopted the euro,” i.e., the NCBs of the **euro area**.
The term **European System of Central Banks (ESCB)**, on the other hand, refers to the ECB as well as “the central banks of all EU Member States.”
It is noted that those NCBs that are not part of the Eurosystem “conduct an independent monetary policy.”

The report considers the promotion of the “smooth functioning of payment systems” as one of the “basic tasks” of the Eurosystem.
This is said to be “enshrined in the Treaty [establishing the European Community] and the Statute of the ESCB.”
The latter is quoted to state that “the ECB and NCBs may provide facilities, and the ECB may make regulations, to ensure efficient and sound clearing and payment systems within the [European] Community and with other countries.”
The Treaty is, further, interpreted as to also empower “[t]he Council of the European Union and the European Parliament [...] to adopt legal instruments,” including “rules relating to the banking industry and the provision of financial services.”
Then, “main directives and regulations which have [and have had] an impact on payment [...] settlement systems” are presented—none of which, it is worth noting, resulted from the aforementioned legal competence of the ECB but from that of the Council of the European Union and the European Parliament:

* The **Cross-Border Credit Transfers Directive**, formally, Directive 97/5/EC of 27 January 1997 on cross-border credit transfers, aimed at “enabling individuals and businesses to make credit transfers in euro rapidly, reliably and cheaply” throughout the EU.
  It was “repealed at the end of the transposition period” of the **Payment Services Directive (PSD)**, formally, Directive 2007/64/EC of 13 November 2007 on payment services in the internal market, which, in turn, was replaced by the **Revised Payment Services Directive (PSD2)**, formally, Directive 2015/2366 of 25 November 2015 of the same name.
  Due to its importance in the context of this paper, the PSD—which encompasses far more than cross-border credit transfers—is covered in detail later in this paper.
* The **Settlement Finality Directive (SFD)**, formally, Directive 98/26/EC of 19 May 1998 on settlement finality in payment and securities settlement systems, ensures that “the operations of payment and settlement systems are not stopped by the bankruptcy of a participant.”
  As such, one of the listed achievements of the SFD is the elimination of “the main legal risks to which payment [...] settlement systems are exposed.”
* The **E-Money Directive (EMD)**, formally, Directive 2000/46/EC of 18 September 2000 on the taking up, pursuit of and prudential supervision of the business of electronic money institutions, sets out to introduce “a minimum set of [...] rules for electronic money issuance” and safeguard “the financial integrity and the operations” of electronic money institutions (ELMIs), among other goals.
  The EMD was updated with, i.e., replaced by, Directive 2009/110/EC of 16 September 2009 of the same name.
* The **Regulation on Cross-Border Payments in Euro**, formally, Regulation (EC) No 2560/2001 on cross-border payments in euro, is credited with the stipulation of “the principle of equal charges by an individual credit institution for a cross-border transaction and a domestic transaction in euro within the European Union.”
  It has been replaced by Regulation (EC) No 924/2009 of 16 September 2009 on cross-border payments in the Community.
* The **Collateral Directive**, formally, Directive 2002/47/EC of 6 June 2002 on financial collateral arrangements, defines collateral as “an asset or third-party claim that is accepted by the collateral-taker to secure an obligation on the part of the collateral-provider vis-à-vis the collateral-taker.”
  The Directive aims to ensure “the protection, validity and enforceability of the collateral agreement”—“also in the event of the opening of insolvency proceedings.”
  Other goals include “the removal of the major obstacles to the (cross-border) use of collateral.”
* The **Markets in Financial Instruments Directive (MiFID)**, formally, Directive 2004/39/EC on markets in financial instruments, is credited with establishing—“for the first time”—“a comprehensive regulatory framework governing the organi[z]ed execution of investor transactions by exchanges, other trading systems and investment firms.”
  As such, it “imposes” an obligation to “execute client orders on the terms that are most fav[o]rable to the client.”
  It was replaced by the **Revised Markets in Financial Instruments Directive (MiFID2)**, formally, Directive 2014/65/EU of 15 May 2014 of the same name.
* The **SEPA Regulation**, formally, Regulation (EU) No 260/2012 of 14 March 2012 establishing technical and business requirements for credit transfers and direct debits in euro, is part of the legal framework of the **Single Euro Payments Area (SEPA)**, which is described in detail later in this paper.
  The European Union’s web site [[2](#r02)] summarizes that “[t]he SEPA regulation [...] sets the rules and a deadline in [...] 2014 [...] for euro area countries to make credit transfers and direct debits in euro under the same conditions.”

The report states that—in the effort of honoring the aforementioned tasks of the Eurosystem, specifically, the smooth functioning of payment systems—the ECB and the respective NCBs have “traditionally been involved in payment, clearing and settlement systems” in a variety of ways, including as “participants,” “operators,” “promoters” and “overseers.”
The fact that, on the one hand, “the payment and settlement services offered by the private sector are overseen by central banks,” and, on the other hand, they “also offer settlement services themselves and sometimes assume an operational role in payment systems,” is called the “dual role of regulator [...] and service provider,” which, in turn, is said to be “emphasi[z]ed” in the Statute of the ESCB.
With regards to the Eurosystem’s role as overseer, it is noted that “both large-value and retail payment systems” are covered by such oversight.
Furthermore, it is noted that both “[s]ystems managed by the Eurosystem and privately operated” ones are “subject to the same standards.”
With regards to the Eurosystem’s role as operator, it is stated that “[t]he main operational role of the Eurosystem lies in the provision of the TARGET system”—“the real-time gross settlement system for the euro.”
Due to its importance in the context of the topic this paper, the TARGET system is covered later in this paper.

The report proceeds to present “other public and private sector bodies” relevant in the payments domain in Europe.
Among the public sector bodies described are the three main institutions of the EU, i.e., the European Commission, the Council of the European Union and the European Parliament.
The tasks attributed to those in the context of payments include the “further harmoni[z]ation of the laws within the European Union, including those which have an impact on payment systems” as well as the creation of “a single market with a level playing-field and equal opportunities throughout the EU.”
As to the relevant private sector bodies, the following are introduced:

* The **European Association of Co-operative Banks (EACB)**, the **European Savings Banks Group (ESBG)** and the **European Banking Federation (EBF)** are considered European “banking federations and associations.”
  As “[m]ost banks in the EU are organi[z]ed into national federations or associations,” it is explained, these then “cooperate at the European level” in the aforementioned organizations.
* The **European Payments Council (EPC)** and the **Euro Banking Association (EBA)** are considered the “most prominent fora in the payments market.”
  The EPC is described to have been set up as a “self-regulatory body” by the “European banking industry” in order “to manage the SEPA project,” which is covered in detail later in this paper.
  The EBA is described as a “cooperative undertaking of over 190 member banks from EU countries” as well as the United States, China, India and others.
  It “established” **EBA Clearing** as a “separate entity,” which, as its name suggests, operates payment systems, some of which are covered later in this paper.
* The **Society for Worldwide Interbank Financial Telecommunication (SWIFT)** is introduced as an “industry-owned cooperative founded [...] by 239 banks from 15 countries.”
  As to the SWIFT organization’s goals, the supply of “secure messaging services and interface software,” the contribution to “greater automation of financial transaction processes” and the provision of a “forum for financial institutions” are mentioned.

It should be noted that there also is the **Bank for International Settlements (BIS)**, although the BIS is active globally—not just in Europe.
The BIS is a financial organization owned by central banks that is sometimes referred to as the central bank of central banks.

## 3. The Payment Services Directive

This section discusses the Payment Services Directive, as it is the most important regulatory initiative with regards to payments in Europe.
Both the original PSD of 2007 as well as the revised PSD2 of 2015 are addressed.

### 3.1. The PSD of 2007

This subsection introduces the PSD of 2007, formally, Directive 2007/64/EC of 13 November 2007 on payment services in the internal market.
It is intended to provide context with regards to what it is and what its goals are as well as to give an overview of its key provisions.
This subsection is, unless noted otherwise, based on the report “Banks Preparing for PSD” [[3](#r03)], which was released by the EBA in 2008.

The report states that the PSD provides—as its formal name suggests—“a legal framework for payment services in the internal market of the EU/EEA.”
As such, it was to be “implemented into national law by 1st November 2009 at the latest” by the “27 Member States” which, at the time, constituted the EU as well as the “three EEA countries” Iceland, Liechtenstein and Norway, which, at the time, have not been—and still are not—EU Member States.
The report considers the PSD to be “one additional step in the EU’s efforts to achieve a single payments market.”
Previous steps of such “[h]armoni[z]ation efforts” are mentioned, namely the “introduction of the euro (in 1999 and 2002),” the “implementation of new payments-related legislation at EU level”—likely referring to the Cross-Border Credit Transfers Directive—and the “launching of the Single Euro Payments Area (SEPA) instruments (in 2008).”

The report enumerates “main objectives” of the PSD, including “establishing a single payment market in the EU” as well as “providing the regulatory framework” to this end.
The creation of “a level playing field” and the subsequent enhancement of “competition” are also mentioned, as is the establishment of “consistent consumer protection and improv[ed] transparency.”
Finally, the creation of “potential for more efficiency of EU payment systems” is listed.

The report gives a short summary of each section of the Directive, which encompasses a total of 96 Articles:

* **Title I (“Subject Matter, Scope and Definitions”)**, encompassing Articles 1–4, is said to lay out “[w]hat the PSD covers” and provide “[d]efinitions” of “[r]egulated entities,” “[t]ransaction types,” etc.
* **Title II (“Payment Services Providers”)**, encompassing Articles 5–29, is described to cover the “regulatory regime” for payment service providers, “specifically [...] for payment institutions”—which are covered later in this subsection—, regarding “[r]egistration/authori[z]ation procedures,” “[c]apital requirements,” etc.
* **Title III (“Transparency of Conditions and Information Requirements for Payment Services”)**, encompassing Articles 30–50, is summarized to set such “[c]onditions” and “[r]equirements” with regards to “[s]ingle transactions” and “[f]ramework contracts.”
* **Title IV (“Rights and Obligations in Relation to the Provision and Use of Payment Services”)**, encompassing Articles 51–83, is said to define such “[r]ights and obligations” with a focus on the “[a]uthori[z]ation of payment transactions” as well as on “[r]efunds, refusal of payment orders” and the “[e]xecution of payment transactions.”
* **Title V (“Implementing Measures and Payments Committee”)**, encompassing Articles 84–85, is not further commented on in the report.
  However, the respective Articles of the PSD [[4](#r04)] can be quoted directly as “to ensure the uniform application of this Directive.”
* **Title VI (“Final Provisions”)**, encompassing Articles 86–96, is said to include stipulations on the PSD as a “[f]ull harmoni[z]ation Directive.”

At this point, the report goes on to present a selection of “key provisions of the PSD.”
In the course of this, a variety of terms that are explicitly defined in the PSD are used, yet the report does not cover such very definitions.
Therefore, the following definitions are taken from the PSD directly—specifically, **Article 4 (“Definitions”)**—and not the report:

* A **payment service** is defined as “any business activity listed in the Annex.”
  The Annex lists seven such activities, including the “[e]xecution of payment transactions,” i.e., “credit transfers,” “direct debits” and “payment transactions through a payment card”—including such transactions “where the funds are covered by a credit line”—, the “[i]ssuing and/or acquiring of payment instruments” as well as “[m]oney remittance” services.
* A **payment institution (PI)** is defined as “a legal person that has been granted authori[z]ation […] to provide and execute payment services.”
* A **payment service provider (PSP)** is defined as one of the “bodies referred to in Article 1(1)” as well as any legal or natural person “benefiting from the waiver under Article 26.”
  Article 1(1) lists “six categories of” PSPs, including “credit institutions,” “electronic money institutions,” “post office giro institutions,” “payment institutions” as defined above and the ECB and NCBs “when not acting in their capacity as monetary authority or other public authorities.”
  As Article 26 lists “[c]onditions” under which “persons […] shall be treated as payment institutions” instead, it can be inferred that PIs represent a category of PSPs as well.
* A **payment service user (PSU)** is defined as “a natural or legal person making use of a payment service in the capacity of either payer or payee, or both.”

As mentioned, the report presents a “selective” list of Articles of the PSD “to be aware of.”
The first set of such “key provisions,” including the following, are considered to be concerned with **execution time, value dating and charging**:

* **Article 64 (“Receipt of payment orders”)** is described to define the “point in time of receipt of a payment order” as well as to discuss “cut-off time.” It is summarized that the payer’s PSP is “allowed to set a cut-off time close to the end of a business day,” after which “payment orders” are to be treated as if they had been received the following day.”
* **Article 67 (“Amounts transferred and amounts received”)** is said to state that “[t]he payment service provider of the payer, the payee and any intermediary provider must transfer the full amount and refrain from deducting charges.” However, it is noted that—“subject to an agreement between the payee and the PSP”—“the payee’s PSP may deduct [its] charges from the payment.”
* **Article 69 (“Payment transactions to a payment account”)** is stated to define that “[a] payment transaction must be credited to the payee’s PSP’s account at the latest by the end of the next business day,” with exceptions applying to “paper-initiated transactions.”
* **Article 73 (“Value date and availability of funds”)** is said to stipulate that the debit value date for the payer‘s payment account is “not [to be] earlier than the point in time at which the amount of the payment transaction is debited to that payment account,” while the credit value date must “no[t be] later than the business day on which the amount of the payment transaction is credited.”

With regards to the “execution time specified in the PSD,” the report concludes that—in the case of all “cross-border transfer[s] in EUR”—the so-called **D+1 rule** applies, where “D” is the “[d]ebit value date for the payer’s payment account” and “D+1” the “[c]redit value date” for the payee’s payment account.
The report also covers the PSD’s stipulations on non-euro payments as well as on so-called **leg-in and leg-out transactions**, where either the payer’s or the payee’s bank is located outside the EU/EEA.
However, these scenarios go beyond the scope of this paper.

The next set of key provisions, including the following, are considered to be concerned with **information and transparency for customers**:

* **Article 32 (“Charges for information”)** is quoted to state that “PSPs must not charge customers for providing information.”
* Possibly in reference to **Articles 36–39 and 41–48**, it is said that “PSPs must provide full transparency to customers before and after a payment is executed,” including information on “maximum execution time, all charges payable,” etc.

Another set of key provisions, including the following, are considered to be concerned with **customer obligations and liabilities**:

* **Articles 58 and 60** are quoted to stipulate that the PSU must notify the PSP of “any unauthori[z]ed or incorrectly executed payment transaction” “without undue delay” and “no later than 13 months after the debit date.”
  Refunding must happen “immediately.”
* **Article 59 (“Evidence on authentication and execution of payment transactions”)** is summarized to state that, essentially, the “PSP must prove that [a] transaction was authenticated.”
* **Articles 62 and 63** are quoted to stipulate that—with regards to “[r]efund[s] of authori[z]ed direct debit[s]”—the PSP “is entitled to [such] a refund” if the “[a]uthori[z]ation did not specify [an] exact amount” and the “[a]mount of [the] transaction exceeded” what could have “reasonably” been expected.
  Refunding “can [be] request[ed] […] for a period of 8 weeks from the date on which the funds were debited.”
  The PSP must “[r]efund [the] full amount within 10 business days or provide justification for refusing” to do so.

Finally, the report also notes that the PSD defines **an entirely new category of PSP—the PI**.
PIs are described as having to be “[a]uthori[z]ed to provide and execute payment services” but then be “allowed to offer the same payment services throughout the EU/EEA.”
It is noted that the PSD “specifies” the “[a]uthori[z]ation” of and “[c]apital requirements” for PIs as well as their “[s]afeguarding […] requirements,” “[r]egistration, record-keeping,” the “[u]se of agents” and the “[s]upervision […] by authorities.”
The report does not further elaborate on PIs.
However, from the previously stated it can be inferred that PIs are PSPs, which enables them to offer payment services, while, at the same time, they do not correspond to any other type of PSP, e.g., they are not credit institutions, and, therefore, are less heavily regulated.

### 3.2. The PSD2 of 2015

This subsection introduces the PSD2 of 2015, formally, Directive 2015/2366 of 25 November 2015 on payment services in the internal market.
Similarly to the previous subsection, it is intended to provide context as to why the PSD2 came into existence and what its goals are as well as to present a selection of its key provisions.
This subsection is based on the report “The Second Payment Services Directive (PSD2)” [[5](#r05)], which was released in 2016 by the trade association Payments UK—which has since merged with other such organizations to form UK Finance.

As to why the PSD2 came into existence, the report states that upon “reviewing the PSD in 2012, the European Commission found [...] a number of benefits” that were introduced by the original PSD, including “[a]n increase in competition” due to the “market entrance” of “regulated non-bank players,” i.e., PIs, “[i]mproved economies of scale” due to the PSD having laid the “foundation for the operational implementation” of the SEPA as well as “[e]nhanced transparency” and “reinforced” “rights and obligations linked to payment services.”
However, it is also stressed that “legislation needs to remain relevant to the environment to which it relates” and that this very environment—”the payments sector”—”is experiencing rapid change.”
More concretely, it is resumed that the PSD needed to be “future proofed” to properly regulate “the new breed of PSPs that are becoming increasingly active in the pan[-]European market.”

The report provides an outline of the “PSD2’s main aims.”
Those—being fairly general in nature—include the contribution “to a more integrated and efficient European payments market,” the promotion of “competition,” the improvement of “consumer protection” and “lower prices.”
A more concrete statement on one of the PSD2’s most important goals can actually be found in one of the sidebars of the report:
“[The] PSD2 brings certain new payment services, and their providers, within the scope of the Directive.”

On a formal note, the report points out that the PSD2 had to be “transposed into national law by Member States by 13 January 2018.”
Consequently, “the majority of the legal provisions” of the PSD2 have been legally binding at least since then.
However, “a number of guidelines and technical standards” concerning “strong customer authentication and secure communication” ran “to a different timetable” and were to be implemented by 14 September 2019—the latter date was set after the report was published and, thus, not mentioned therein.
The report states that the PSD2 does—just like the original PSD—apply within the EEA, which still encompasses the EU as well as the three non-EU countries Iceland, Liechtenstein and Norway.
It is to be pointed out that in 2016, when the report was published, the EU still consisted of 28 Member States, as Croatia joined the EU in 2016, i.e., after the original PSD came into force, and the United Kingdom had not left the EU yet.
Whether or not the United Kingdom will remain part of the EEA is hotly debated at the time of this writing.

The PSD2, which encompasses a total of 117 Articles, “preserves the structure of the original PSD in terms of the split into sections (Titles) and content areas but has added a number of new or amended provisions.”
Although not mentioned in the report, one such Title has been renamed, i.e., **Title V (“Delegated Acts and Regulatory Technical Standards”)**.
Likewise, it should be pointed out that the PSD2 features a “correlation table,” which displays the numbers of the respective Articles of the original PSD and the PSD2 side by side.

The report finds that the PSD2’s “key changes” can be “grouped” into “four main but overlapping themes,” the first of which is **market efficiency and integration**.
Changes falling into this category include the following:

* The PSD2 is said to **extend the Directive’s scope with regards to currencies and one-leg transactions** as for it to not only apply to “all EEA currency payments where the PSPs of both the payer and payee are located within the EEA” but also to “[n]on-EEA currency payments between EEA-domiciled PSPs” and to “[o]ne-leg transactions”—as previously defined—”in any currency.”
  “In practice,” this can—according to the report—be interpreted to mean that “PSPs operating in Europe” “need to provide information and transparency” and are “held liable in the event of a problem attributable to them” with regards to all payments—”at least for the part of the transaction for which they are responsible.”
* The PSD2 is described to **change the scope of the Directive’s exclusions**, on the one hand, continuing “to allow certain business activities undertaken by non-bank organi[z]ations to remain outside the scope of its requirements,” on the other hand, including “the purchase of physical goods and services through a telecoms operator.”
* The PSD2 is stated to **add to the authorization requirements of PIs**, specifically, by introducing further “operational and security requirements.”
  Providers of new payment services that are introduced with the PSD2, which are presented as part of the third set of key changes, “also have to meet certain capital requirements and hold professional indemnity insurance.”
  
The second set of key changes presented in the report are grouped under the theme **consumer protection**.
Changes falling into this category include the following:

* The PSD2 is described to **reduce the amount for which a PSU should be liable in the case of unauthorized payment transactions** “from €150 to €50”—”except in cases of fraud or gross negligence by the payer.”
* The PSD2 is said to **introduce an unconditional refund right**, which can be invoked “for a period of 8 weeks from the date when the funds were debited.”
  It is noted that this “already applies under the SEPA Core Direct Debit [S]cheme.”
* The PSD2 is described to **limit ring fencing of funds to amounts that were approved by the payer**.
  Specifically, it is explained that—”[i]n the context of the pre-authori[z]ation of card payments, where the final amount of the transaction is not known”—the payee can only block “where the cardholder has approved the exact amount” for this purpose.
  Funds are “required to [be] unblocked [...] without undue delay once information about the exact final amount is received and, at the latest, after [...] the payment order” has been received by “the payer’s PSP.”
* The PSD2 is said to **do away with surcharging**—”the steering practice sometimes used by merchants [...] to compensate for [...] costs where interchange fees may be applied when certain payment instruments [...] are used”—at least if the type of payment is “covered by the Interchange
Fee Regulation” or “by the SEPA Regulation.”

The third set of key changes presented in the report are grouped under the theme **competition and choice** and mainly concern the introduction of “[n]ew providers and new payment services” as is described in the following paragraphs:

The report quotes Article 4 of the PSD2 to define a payment service as “any business activity set out in Annex I”—as was the case in the original PSD.
In the PSD2, however, that “list of business activities” is said to “include two new payment services,” the **payment initiation service (PIS)** and the **account information service (AIS)**.
The PSD2 is quoted to define a PIS as “a service to initiate a payment order at the request of the payment service user with respect to a payment account held at another payment service provider.”
An AIS is quoted to be defined as “an online service to provide consolidated information on one or more payment accounts held by the payment service user with either another payment service provider or with more than one payment service provider.”

The “[p]roviders of such services” are “termed” **payment initiation service providers (PISPs)** and **account information service providers (AISPs)**, respectively.
“[C]ollectively,” these are considered to be referred to as **third party providers (TPPs)**.
Furthermore, the PSD2 is said to define **account servicing payment service providers (AS PSPs)** “to distinguish the provider[s] where the customer’s payment account is held.”
A PIS—provided by a PISP—is described as to “typically” be integrated by “a merchant” into their “online checkout process to enable to offer the option of online credit transfers as an alternative to card payments.”
An AIS—provided by an AISP—is described to “allow consumers and businesses to obtain a consolidated view of their accounts [...] with one or more AS PSPs.”
It is stated that “any PSP”—”subject to having the appropriate authori[z]ation”—”could [...] offer PIS or AIS.”
It is also noted that the PSD2 “defines a lighter prudential regime for AISPs,” which “are treated as” PIs while being subject to “only [...] some of the provisions regarding transparency, information, rights and obligations.”

The introduction of TPPs is summarized to “reflect the market growth in e-commerce activities and use of internet and mobile payments as well as the rise of new technological developments and a trend towards customers having relationships with multiple account providers.”

The fourth and final set of key changes presented in the report are grouped under the theme **security**.
Changes falling into this category include the following:

* The PSD2 is said to **increase requirements with regards to operational and security risks and incident reporting**.
  It is stated that PIs are required “to provide a security policy document,” which includes a description of “the measures taken to protect customers from fraud and illegal use of sensitive and personal data.”
  With regards to “[a]ll PSPs,” it is stated that “a framework to manage operational and security risks” is to be established, which is described to encompass “incident management procedures” following “EBA [...] issue[d] guidelines.”
* The PSD2 is described to **strike a balance between openness and security with regards to authentication**.
  More precisely, it is noted that while “the AS PSP is obliged to allow PISPs and AISPs to rely on the authentication procedures it provides [...], all PSPs must ensure that security measures are in place to protect the [...] customers’ personali[z]ed security credentials.”
* The PSD2 is stated to **require strong customer authentication and secure communication** according to an “EBA [...] draft[ed]” Regulatory Technical Standard (RTS).
  It is noted that PSPs are “required to use strong customer authentication” when payment accounts are accessed, payment transactions are initiated and “action” is carried out “through a remote channel which may imply a risk.”
  It is, further, noted that “[i]f the payer’s PSP does not require strong customer authentication, the payer will only be liable [...] where the payer has acted fraudulently.”

### 4. The Single Euro Payments Area

This section discusses the Single Euro Payments Area, as it is the most important private-sector initiative with regards to payments in Europe.
After the SEPA project itself is addressed, the concepts of clearing and settlement are introduced, followed by an outline of the two main SEPA payment instruments, i.e., those for credit transfers and direct debits.

It should be noted that the EPC capitalizes certain terms when they have special meaning in the context of their payment instruments, e.g., when they refer to “Rulebook” rather than “rulebook.”
For consistency reasons, this paper follows their spelling.

### 4.1. The SEPA project

This subsection introduces the SEPA project, including its origins and goals.
It is based on Przemysław Nasiński’s master’s thesis “Payment Services Directive” [[6](#r06)] at Lund University from 2010.
The information presented here has been updated and extended as necessary.

Nasiński’s thesis introduces the SEPA as an “effort to harmonize national payment systems.”
It is, further, stated that this effort is “seen by some as the culmination of the introduction of the euro and the final stage in the creation of the single market.”
At the time of this writing, the SEPA comprised 36 countries, i.e., the 27 EU Member States, the four European Free Trade Association (EFTA) countries Iceland, Liechtenstein, Norway, and Switzerland as well as Andorra, Monaco, San Marino and Vatican City.
It is, furthermore, stated that in order to “coordinate its efforts, the banking industry has set up a self-regulatory body to manage the SEPA project,” namely the aforementioned organizations EPC and EBA.

As to the origins of the SEPA project, Nasiński considers the “Regulation 2560/2001,” i.e., the previously mentioned Regulation on Cross-Border Payments in Euro, to be “the source of this project.”
The Regulation’s “main objectives”—according to the thesis—include the reduction of “the level of charges levied on cross-border electronic payments in euro, [which, at the time, were] seen by the Commission as too high.”
Therefore, it—among other things—“introduced [...] that cross-border payments in euro should cost the same as corresponding national payments in euro.”
Nasiński stresses that the Regulation—“[w]hile being adopted”—“raised vigorous opposition from the banking sector.”
It can be argued, however, that it also sparked not only criticism but innovation, as it “created the need for the banking industry to deploy EU-wide infrastructures in order to cut the costs for cross-border payments.”
In fact, “[a] parallel process was [...] initiated by the private sector” as “European banks started working on the new project, called... SEPA.”
Nasiński paraphrases a Commission proposal on the Regulation to state that “the Regulation provided the impetus to the banking industry to undertake the SEPA.”

With regards to the interaction of public and the private initiatives in the European payments sector, Nasiński resumes that, at first, Regulation 2560/2001—a public initiative—“was the reason why the SEPA project”—a private initiative—“even started.”
“Afterwards, the SEPA influenced the introduction of the PSD”—a public initiative—which, in turn, “implicated the revision and substitution of the old Regulation with the new Regulation 924/2009”—another public initiative.

With regards to the scope of the SEPA project, it is stated that the EPC “has designed rulebooks for two payment schemes [...] and one framework,” namely **SEPA Credit Transfer (SCT)**, **SEPA Direct Debits (SDD)** and **SEPA Cards Framework (SCF)**, respectively.
It is noted that SCT and SDD can be considered “replacement strategies” in that they are “new common schemes” replacing their national predecessors.
SCF, on the other hand, is described as an “adoption strategy” that “allow[s] existing schemes and their operators to adjust” to it.
At the time of this writing, SCT and SDD are fully adopted and implemented, whereas SCF is not, leaving card payment schemes in Europe largely incompatible with each other.
It seems noteworthy that in 2016, the EPC first presented a draft of the **SEPA Credit Transfer Instant (SCT Inst)** Rulebook.
As the EPC web site [[7](#r07)] states, SCT Inst “enabl[es] pan-European credit transfers with the funds made available [...] in less than ten seconds.”
At the time of this writing, said Rulebook is available in version 1.1 and “2240 payment service providers have already joined the scheme: 56% of European PSPs.”
Due to their ubiquity, the following subsections will present the SEPA payment instruments SCT and SDD in detail.

In his thesis, Nasiński lists key differences between the SEPA and the PSD.
Whilst the former is a “[s]elf-regulatory” initiative, the latter is a EU Directive.
Furthermore, while the SEPA only concerns euro payments with the respective SEPA payment instruments, the PSD regulates all “[p]ayment services listed in the Annex to the PSD” and is also not limited to euro payments.

### 4.2. Clearing and settlement

This subsection introduces the terms clearing and settlement, as they are crucial to understanding the SEPA payment instruments that are presented in the next subsections.
It is based on the respective remarks made by Capgemini payments consultant Jean Paul Megue in his 2018-book “SEPA Credit Transfer” [[8](#r08)].

Megue starts out by quoting the BIS to define **clearing** as “the process of transmitting, reconciling and, in some cases, confirming transactions prior to settlement, including the netting of transactions and the establishment of final positions for settlement.”
According to Megue, **netting** is what is “key” to this definition, which the BIS is quoted to define as “the offsetting of obligations between or among participants in the netting arrangement, thereby reducing the number and value of payments or deliveries needed to settle a set of transactions.”

A simple example of **bilateral clearing**—which, in this case, can be understood as netting that only involves two parties—is presented.
It is assumed that a party A orders 100€ to be transferred to a party B, while party B orders 25€ to be transferred to party A.
75€ is what is considered the “final position after the netting.”
It is noted that if only this final position were to be transferred from A to B, “only one transfer [would have to be] made” and one transaction could be “save[d].” Megue describes **multilateral clearing** as “the same as […] bilateral clearing” in principle but with “a high number of financial institutions […] involved.”

In the absence of a central party, financial institutions performing multilateral clearing would have to “establish a point-to-point connection with each of them.”
In such a “fully connected network topology”—which is considered “extremely impractical”—“many bilateral clearings [would have to] be performed.”
This approach is described to be problematic for a variety of reasons, most prominently because “[e]ach bank in the system must take care of the netting […] itself” and “[i]t must do that for each of the bank[s] it is connected to.”
As a solution to these problems, Megue introduces the concept of a **clearing house**—a “third party” to which all participating institutions are connected.
A clearing house “implements the clearing mechanism” and enables participating banks “[t]o reach all [b]anks connected to the CSM” simply by being connected to it.
It is then pointed out that a participating bank does, in fact, not deal with the other banks connected to the clearing house but “considers the clearing system as a single counterparty.”
Concretely, this means that “[w]hen a bank receives a credit transaction, it considers […] the clearing system to [owe] it money,” whereas, conversely, in case of a debit transaction, “it owes money to the clearing system.”
According to Megue, clearing houses are—“[i]n reality”—“connected to the central [b]ank”, for two reasons:
Firstly, “[t]he central bank comes into play […] as overseer of the banking system,” and, secondly, because it is said to implement the settlement system.

Megue interprets the BIS’ definition of **settlement** like so:
“[S]ettlement is the funds transfer that is carried out by one party to fulfill its obligations towards the counterparty in a financial operation.”
This is said to generally happen after clearing.

Two mechanisms of settlement are introduced.
Firstly, a **gross settlement system** is defined as “a system in which the settlement or funds transfer occurs individually after each payment transaction is processed in the system.”
It is stated that banks use this method of settlement in case of “urgent” and/or “large” transfers.
Since the “instructions are executed instantaneously,” these systems are said to also be called **real-time gross settlement systems (RTGSs)**.
RTGSs are described to usually be operated by central banks.
Secondly, a **net settlement system** is described:
To begin with, “[t]ransactions are exchanged […] without transfers of funds.”
Then, at specific times, “the multilateral net settlement positions are calculated.”
The “actual moving of funds” is then said to happen at “settlement times,” presumably at the end of so-called “settlement cycles.”

Clearing houses and the settlement systems are oftentimes collectively referred to as **clearing and settlement mechanisms (CSMs)**.
Although Megue mentions CSMs continuously, the acronym is never actually defined in his book.

There are, according to Megue, numerous “clearing systems in the SEPA zone” that are SEPA-compliant, which can be differentiated into national, regional and pan-European ones.
While national clearing systems are described to serve banks within the scope of one country, regional and pan-European ones “interconnect” banks from “many” or “all” SEPA countries, respectively.
A pan-European, SEPA-compliant clearing house is said to be called a **pan-European Automated Clearing House (PE-ACH)**.
Currently, there “is only one” of those: **STEP2**, operated by EBA Clearing.
It is noted that not every bank has to be connected to STEP2 as a “[d]irect [p]articipant (DP).”
Instead, “[t]he national CSM can establish interoperability with STEP2 or with a CSM interoperable with STEP2.”
Megue considers a bank that is connected to STEP2 via an intermediary CSM an “indirect participant (IP).”
A mentioned example of an RTGS is **TARGET2**, the RTGS system for the euro, “owned and operated by the Eurosystem.”
In fact, according to the EBA Clearing web site [[9](#r09)], banks participating in STEP2 “settle their STEP2 obligations by paying a net calculated amount in TARGET2.”
To be more precise, “STEP2 first creates bilateral gross obligations and reports them to the banks,” “then calculates the multilateral net positions,” and, finally, “sends these multilateral net amounts to TARGET2.”

### 4.3. SEPA Credit Transfer

This subsection introduces SCT, the SEPA payment instrument for **credit transfers**.
It is intended to provide an overview of the SCT Scheme’s vision, objectives and scope as well as of its operating rules.
This subsection is based on version 1.1 of the “SEPA Credit Transfer Scheme Rulebook” [[10](#r10)], which was published by the EPC in March 2020.

With regards to the Scheme’s vision, the SCT Rulebook states that the Scheme “provides a set of inter[-]bank rules, practices and standards” allowing for “payment services providers in SEPA to offer a [...] basic euro credit transfer product.”
Among listed objectives of the Scheme is the removal of “disparities between national and cross[-]border payments in euro within SEPA,” aiming to make it “as easy and secure to make a payment within SEPA as it is within one national environment.”
It is, furthermore, highlighted that “SEPA Credit Transfers will be automated, based on the use of open standards and [...] without manual intervention.”
Lastly, it is noteworthy that a clear “[s]eparation of the Scheme from [i]nfrastructure” is emphasized.
In this regard, it is specified that the “rules, practices and standards” that make up SCT are “operated” by “potentially multiple infrastructure providers”—infrastructure is, thus, declared “an area where market forces operate.”

On the Scheme’s scope, the SCT Rulebook clarifies that the Scheme “is applicable in the countries listed in the EPC List of SEPA Scheme Countries,” which lists the same 36 countries that were previously mentioned in the subsection on the SEPA project.
It is pointed out that “[a] SEPA Credit Transfer is a payment instrument for the execution of credit transfers in euro between Customer payments accounts located in SEPA” and that such transfers are “executed on behalf of an Originator [..] in fav[o]r of a Beneficiary.”
Subsequently, the SCT Rulebook lists five “key elements [...] included within the scope of the Scheme.”
Firstly, it is reiterated that the Scheme includes “[a] set of interbank rules, practices and standards for the execution of credit transfer payments in euro within SEPA.”
Those Participants who “subscribe to the Scheme and its rules” are then defined “Adherents.”
The Scheme is, furthermore, said to provide “the basis for credit transfer products provided by Participants [i.e., financial institutions] to all users of mass-market, non-urgent payment services.”
Afterwards, it is repeated that “the inter[-]bank elements of the Scheme are always fully automated and electronic.”
The last of the listed key elements states that “a minimum set of data elements to be provided by the Originator” is specified by the Scheme.
Concerning the scope, it should also be pointed out that there is emphasis on the Participants’ ability to “provide complementary services based on the Scheme”—so-called Additional Optional Services (AOS)—presumably so they can stand out from the competition.

The SCT Rulebook names four “main actors” that are involved in “[t]he execution of a SEPA Credit Transfer payment”:

* The **Originator** is described as “the Customer who initiates [...] the SEPA Credit Transfer by providing the Originator Bank with an instruction.”
  The funds for the transaction are said to be debited from “a specified Payment Account of which the Originator is account holder.”
* The **Originator Bank** is described as “the Participant that receives the Credit Transfer Instruction from the Originator and acts on the payment instruction by making the payment to the Beneficiary Bank in fav[o]r of the Beneficiary’s account.”
* The **Beneficiary Bank** is described as “the Participant that receives the Credit Transfer Instruction from the Originator Bank and credits the account of the Beneficiary.”
* The **Beneficiary** is described as “the Customer identified in the Credit Transfer Instruction whom the Funds are sent to.”
  
It is noted that the Originator Bank and the Beneficiary Bank may be the same Participant.
Moreover, it is noted that there are “other parties” that are involved “indirectly,” i.e., CSMs, intermediary banks and PISPs.

Based on the fact that there are four main actors, the SCT Rulebook presents the “contractual relationships and interaction” between those in the form of a **four-corner model**.
As a side note, it should be mentioned that there are payment instruments that can be conceptualized as **three-corner models**, e.g., the card payment schemes American Express and Diner’s Club, where there are three main actors—the card holder, the merchant, and the card scheme.
The SCT four-corner model is illustrated as follows:

```
        ┌─────────────┐                                 ┌─────────────┐         
        │ Originator  │─────────────── 2 ───────────────│ Beneficiary │         
        │             │                                 │             │         
        └─────────────┘                                 └─────────────┘         
               │                                               │                
               3                ┌─────────────┐                4                
               │                │    CSMs     │                │                
        ┌─────────────┐    ┌────│             │────┐    ┌─────────────┐         
        │ Originator  │    5    └─────────────┘    5    │ Beneficiary │         
        │    Bank     │────┘                       └────│    Bank     │         
        └─────────────┘                                 └─────────────┘         
               │                ┌─────────────┐                │                
               │                │   Scheme    │                │                
               └────── 1 ───────│    Rules    │─────── 1 ──────┘                
                                └─────────────┘                                 
                                                                                
┌──────────────────────────────────────────────────────────────────────────────┐
│                       Figure 1: SCT four-corner model                        │
│                   (based on figure 2 of the SCT Rulebook)                    │
└──────────────────────────────────────────────────────────────────────────────┘
```

The relationships between the actors are described as follows:

1. The Participants, i.e., the Originator Bank and the Beneficiary Bank, are said to “[a]dhere to” the Scheme rules.
2. The Originator and the Beneficiary are described to form a relationship based on the “[p]rovision of goods and services and/or requirement to move money.”
  It is noted that “[t]his relationship does not form part of the operation of the Scheme.”
3. The Originator and the Originator Bank are described to be in a relationship based on the “[p]rovision of payment under terms and conditions agreed with [the] Originator Bank.”
  This relationship is also said to “not [be] governed by the Scheme,” except for the parts “relevant to the initiation and execution of a SEPA Credit Transfer.”
4. The Beneficiary and the Beneficiary Bank are described to be in a relationship based on the provision of payment services as well—just like the Originator and the Originator Bank.
  This relationship is also said to not be covered by the Scheme with the exception of those “elements [that are] relevant to the receipt of a SEPA Credit Transfer.”
5. The Originator Bank and Beneficiary Bank are said to be “[u]sing” CSMs.

With regards to the “governing laws of the agreements in the four-corner model,” it is stated that both the SCT Rulebook as well as the “Adherence Agreement” are “governed by Belgian law.”

The SCT Rulebook lists “business and operational rules,” which are to be “observed by Participants and by other actors as necessary such that the Scheme can function properly.”
To begin with, rules with regards to the “execution time cycle” are stipulated.
It is stated that “[t]he execution time for a SEPA Credit Transfer shall commence at the point in time of receipt of the Credit Transfer Instruction”—“as defined in the Payment Services Directive.”
Also based on the stipulations of the PSD are the rules on “[c]ut-off [t]imes,” “[m]aximum [e]xecution [t]ime” and “[c]harging [p]rinciples.”
Concerning said maximum execution time, it is, for example, stipulated that “Originator Banks are obliged to ensure that the amount of the SEPA Credit Transfer is credited to the account of the Beneficiary Bank within one Banking Business Day following the point in time of receipt of the Credit Transfer Instruction”—just as is required by the PSD’s D+1 rule.
For the crediting of the Beneficiary’s account, a maximum execution time is not specified, it is simply stated that this has to happen “in accordance with the provisions of the Payment Services Directive.”

The execution time cycle rules are followed by rules concerning the “[p]rocessing [f]low.”
These are presented in the form of diagrams, which lay out the Processes that make up the SCT Scheme step-by-step.
For the sake of brevity, this paper will only briefly summarize the **Credit Transfer Process (PR-01)**.
When leaving out those steps that deal with Rejects and Returns, PR-01 defines the following Process steps:

* **CT-01.01**: “The Originator completes and forwards the Credit Transfer Instruction.”
* **CT-01.02**: “The Originator Bank receives and checks” said Instruction.
* **CT-01.03**: The Originator Bank is described to debit the Originator’s account “[o]n or following D.”
  This is said to be followed by “the sending of the Credit Transfer Instruction to ensure receipt by the Beneficiary Bank via the selected CSM.”
* **CT-01.04**: The Beneficiary Bank is described to credit the Beneficiary’s account.

As said, the SCT Rulebook describes many more Processes—covering exception handling, corner cases, etc.—in much greater detail.
For the sake of brevity, these will not be described in this paper.

### 4.4. SEPA Direct Debit

This subsection introduces SDD, the SEPA payment instrument for **direct debits**.
It is intended to provide an overview of the SDD Scheme’s vision, objectives and scope as well as of its operating rules.
This subsection is based on version 1.1 of the “SEPA Direct Debit Core Scheme Rulebook” [[11](#r11)], which was published by the EPC in March 2020.

What is laid out in the SDD Rulebook with regards to the SDD Scheme’s vision and objectives is largely identical to the respective passages of the SCT Rulebook, although reference is made to direct debits and not credit transfers, obviously.
For instance, the SDD Scheme is described to provide “a set of inter-bank rules, practices and standards” as well, allowing “payment services providers in SEPA to offer a [...] basic [...] product”—a “direct debit product,” though.
Automation and open standards are mentioned, too, as is the objective to overcome disparities between national and cross-border payments, i.e., direct debits, in this case.
Expectedly, the “[s]eparation of the Scheme from [i]nfrastructure” is emphasized also.

The SDD Scheme’s scope, as described in the SDD Rulebook, is, however, partly different from that of the SCT Scheme.
Obviously, SDD is a different payment instrument altogether, i.e., one for “for making Collections in euro throughout SEPA from accounts designated to accept Collections.”
“Transactions for the Collection of Funds from a Debtor’s account” are described to be “initiated by a Creditor via the Creditor Bank as agreed between Debtor and Creditor,” although it is emphasized that these “are separate transactions from the underlying contract on which they are based.”
Transactions are, furthermore, described as being “based on an authori[z]ation for the Creditor and the Debtor Bank given to the Creditor by the Debtor”—the **Mandate**.
It is stipulated that both the Creditor’s and the Debtor’s account must be held “with a Participant located within SEPA.”
There is, according to the SDD Rulebook, “no difference in the legal nature” between “recurrent and one-off Collections,” and Debtors are said to be given “full discretion [...] to accept or refuse a Mandate.”
The rest of what is described regarding the SDD Scheme’s scope is largely similar to what has been stated with regards to the SCT Scheme.
For instance, it is also pointed out that “room for competition between Participants” is left as the latter are allowed to “develop their own products and offer AOS.”

The SDD Rulebook names four “main actors” that are involved in “[t]he execution of a SEPA Direct Debit payment”:

* The **Creditor** is described to receive and store “the Mandate from the Debtor to initiate Collections.”
  The Mandate is considered the “basis” for the Creditor’s collection of the “direct debits.”
* The **Creditor Bank** “is [...] where the Creditor’s account is held.”
  It is stated that an “agreement” between the Creditor and the Creditor Bank with regards to “a product based on the Scheme” has been “concluded.” 
  Based on the agreement, the Creditor Bank “receives and executes instructions from the Creditor to initiate the Direct Debit Transaction by forwarding the Collection instructions to the Debtor Bank.”
* The **Debtor Bank** “is [...] where the account to be debited is held.”
  Analogously to the relationship between the Creditor and the Creditor Bank, it is stated that an “agreement” between the Debtor and the Debtor Bank with regards to “a product based on the Scheme” has been “concluded.”
  Based on the agreement, the Debtor Bank “executes each Collection of the direct debit originated by the Creditor by debiting the Debtor’s account.”
* The **Debtor** is described to give “the Mandate to the Creditor to initiate Collections.”
  It is stressed that—“[b]y definition”—“the Debtor is always the holder of the account to be debited.”

Although not expressed explicitly, it can be assumed that the Debtor Bank and the Creditor Bank may be the same participant.
Furthermore, it is noted that there are “other parties” that are involved “indirectly,” i.e., CSMs and intermediary banks.

Analogously to SCT, the SDD Rulebook “gives an overview of the contractual relationships and interaction” between the main actors by presenting a four-corner model:

```
        ┌─────────────┐                                 ┌─────────────┐         
        │   Debtor    │─────────────── 2 ───────────────│  Creditor   │         
        │             │                                 │             │         
        └─────────────┘                                 └─────────────┘         
               │                                               │                
               3                ┌─────────────┐                4                
               │                │    CSMs     │                │                
        ┌─────────────┐    ┌────│             │────┐    ┌─────────────┐         
        │   Debtor    │    5    └─────────────┘    5    │  Creditor   │         
        │    Bank     │────┘                       └────│    Bank     │         
        └─────────────┘                                 └─────────────┘         
               │                ┌─────────────┐                │                
               │                │   Scheme    │                │                
               └────── 1 ───────│    Rules    │─────── 1 ──────┘                
                                └─────────────┘                                 
                                                                                
┌──────────────────────────────────────────────────────────────────────────────┐
│                       Figure 2: SDD four-corner model                        │
│                   (based on figure 1 of the SDD Rulebook)                    │
└──────────────────────────────────────────────────────────────────────────────┘
```

The relationships between the actors are described as follows:

1. The Debtor Bank and the Creditor Bank are said to be “bound” to the “contractual relationships underlying the Scheme” through what is called the “Adherence Agreement.”
2. The Debtor and the Creditor are described to form a relationship “regarding the requirement to make a payment,” which “will result in” in an agreed-upon Mandate.
  It is noted that—“[w]hilst the data elements required for the Mandate are specified by the Scheme,” the “underlying relationship” is outside the scope of the Scheme.
3. The Debtor and the Debtor Bank are described to be in a relationship based on “the direct debit service to be provided.”
  This relationship is also said to “not [be] governed by the Scheme,” except for the parts “relevant to execution of a SEPA Direct Debit.”
4. The Creditor and the Creditor Bank are described to be in a relationship based on the provision of direct debit services—just like the Debtor and the Debtor Bank.
  This relationship is also said to not be covered by the Scheme with the exception of those “elements [that are] relevant to the execution of a SEPA Direct Debit.”
5. The Debtor Bank and Creditor Bank are said to be “[u]sing” CSMs.

It is noted that “relationships” between “the Creditor Bank and/or the Debtor Bank and any Intermediary Bank” are “not governed by the Scheme.”

With regards to the “governing laws of the agreements in the four-corner model,” it is stated that both the SDD Rulebook as well as the “Adherence Agreement” are “governed by Belgian law,” as is the case with SCT.
“The Mandate” is, however, said to be “governed by the law of a SEPA country.”

Analogously to the SCT Rulebook, “business and operational rules” are listed.
Unlike the SCT Rulebook, however, the SDD Rulebook begins this section by providing “a schematic overview” of the “interaction” between the main actors with regards to the Mandate as well as the Collections.
With regards to the Mandate, three steps are outlined:

1. The process is initiated when “[t]he Debtor completes the Mandate and sends it to the Creditor.”
The Mandate is defined as “the expression of consent and authori[z]ation given by the Debtor to the Creditor to allow such Creditor to initiate Collections for debiting the specified Debtor’s account and to allow the Debtor Bank to comply with such instructions.”
2. The Creditor must transmit “Mandate-related data” to the Creditor Bank “along with each Collection of a recurrent SEPA Direct Debit or with the one-off Collection.”
3. After being “demateriali[z]ed” or “extracted” from a paper-based Mandate or an electronic Mandate, respectively, the “Mandate-related information must be transmitted [...] by the Creditor Bank to the Debtor Bank as part of the Collection in one single flow, using the selected CSM.”

With regards to the Collections, five steps are outlined—with enumeration starting at zero, for unknown reasons:

0. “The Creditor must send a Pre-notification [...] to the Debtor.”
1. “After receiving the signed Mandate, the Creditor may initiate Collections [through the Creditor Bank].”
2. “The Creditor Bank will send Collections to the Debtor Bank through a selected CSM.”
3. The CSM is said to “process the transaction” and “send the [...] Collections [to the Debtor Bank] in accordance with the Settlement Cycle,” making “the necessary arrangements for Settlement.”
4. “The Debtor Bank must debit the Debtor’s account if the account status allows this.”

Later in the section on business and operational rules, “time-cycle rules” are laid out.
These are preceded, however, by the definition of “Key dates,” all of which are assumed to fall on “the same date”:

* The **Settlement Date** is defined as “[t]he day on which Settlement takes place.”
* The **debit date** is defined as “[t]he day on which the Debtor’s account is debited.”
* The **Due Date (D)** is defined as “the day when the payment of the Debtor is due to the Creditor,” as is agreed upon in the “underlying contract.”

The time-cycle rules relevant to the previously listed steps include the following:

* **D - 14 CD or as agreed upon between Creditor and Debtor**: The Creditor is stipulated to be required to send the Pre-notification to the Debtor “at the latest 14 Calendar Days before the Due Date”—unless otherwise agreed upon between the two.
* **D - 14 CD or as agreed  upon between Creditor and Creditor Bank**: The Creditor is said to be “allowed to send the Collection to the Creditor Bank after the Pre-notification is sent to the Debtor, but not earlier than 14 Calendar Days before the Due Date”—unless otherwise agreed upon between the Creditor and the Creditor Bank.
* **D - 1 TD**: The Creditor Bank is stipulated to be required to “send a Collection to the Debtor Bank so that [...] the Collection” is received “via the CSM at the latest one Inter-Bank Business Day [...] before Due Date and not earlier than 14 Calendar Days before the Due Date.”
  Inter-Bank Business Days are defined as “TARGET Days.”
* **D + 1 TD**: The diagram presented in the SDD Rulebook can be interpreted to state that Settlement and the debiting of the Debtor’s Bank is to happen on the Due Date or—“[i]f [the] due date is not a banking business day”—one TARGET Day after that.

Similarly to the SCT Rulebook, the SDD Rulebook describes many more Processes and corresponding time cycle rules—covering exception handling, corner cases, etc.—in much greater detail.
For the sake of brevity, these will not be described in this paper.
On a final note, it should be emphasized that the rules stipulated by the SDD Rulebook consistently reflect the PSD, for example, when stipulating that “Debtors are entitled to request a Refund for any SEPA Direct Debit within eight weeks from the [debit] date,” which “will be provided to the Debtor by the Debtor Bank on a no-questions-asked basis.”

## 5. Conclusion

In the previous sections, the European payments sector has been examined.
Section 2 gave an overview of the institutions and legislation relevant in the domain of payments in Europe.
Among the institutions introduced were law-making bodies, e.g., the EU and the ECB, as well as private-sector institutions, e.g., the EPC and the EBA.
The regulations referred to include the PSD, the SEPA Regulation, the SFD and others.
As it is the central piece of European payments regulation, section 3 introduced both the original and the revised version of the PSD and also discussed their backgrounds.
The subsection on the original PSD covered, among other things, its key definitions—including those of PSPs and PIs—as well as a summary of its most important stipulations, e.g., the D+1 rule.
The subsection on the PSD2 covered its main innovations, i.e., the introduction of TPPs and various technological requirements, and more.
Section 4 introduced the SEPA, the most important private-sector initiative of the European payments market.
The first subsection elaborated on the project’s background as well as its interplay with public-sector initiatives.
Then, the concepts of clearing and settlement were explained in preparation for the following subsections, which presented the two most prominent SEPA payment instruments—SCT and SDD—at length.

At this point, the reader has been introduced to the key players, regulations, initiatives and instruments of the European payments market.
However, as the payments landscape in Europe—let alone globally—is, as mentioned before, vast, it should be noted that the knowledge presented here is by no means exhaustive and merely constitutes a subjective selection.
Nevertheless—from here, innovators and entrepreneurs are able to start their journey into the European payments sector, being able to draw on the knowledge presented in this paper.

## 6. References

1. <span id="r01">European Central Bank (2007):
  Blue Book: Payment and Securities Settlement Systems in the European Union, Volume 1<br>
  https://www.ecb.europa.eu/pub/pdf/other/ecbbluebookea200708en.pdf</span>
2. <span id="r02">European Commission Directorate-General for Communication (2020):
  Single euro payments area (SEPA)<br>
  https://ec.europa.eu/info/business-economy-euro/banking-and-finance/consumer-finance-and-payments/payment-services/single-euro-payments-area-sepa_en</span>
3. <span id="r03">Euro Banking Association (2008):
  Banks Preparing for PSD: A Guide for Bankers on the Payment Services Directive<br>
  https://www.abe-eba.eu/media/azure/production/1342/banks-preparing-for-psd.pdf</span>
4. <span id="r04">European Parliament and Council (2007):
  Directive 2007/64/EC on payment services in the internal market<br>
  http://data.europa.eu/eli/dir/2007/64/oj</span>
5. <span id="r05">Payments UK, now UK Finance (2016):
  The Second Payment Services Directive (PSD2): A briefing from Payments UK<br>
  https://static1.squarespace.com/static/5888b0436a496319031d1d45/t/5964d1562994ca141b2d3cfe/1499779436856/PSD2+impact+report.pdf</span>
6. <span id="r06">Nasiński, Przemysław (2010):
  Payment Services Directive: A New Legal Framework for Payments in the European Union<br>
  https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.926.2777&rep=rep1&type=pdf</span>
7. <span id="r07">European Payments Council (2020):
  SEPA Instant Credit Transfer<br>
  https://www.europeanpaymentscouncil.eu/what-we-do/sepa-instant-credit-transfer</span>
8. <span id="r08">Jean Paul Megue (2018):
  SEPA Credit Transfer: How to understand and add value to your SCT payment project<br>
  https://www.paiementor.com/sct-book/</span>
9. <span id="r09"> EBA Clearing (2020):
  STEP2 SCT<br>
  https://www.ebaclearing.eu/services/step2-sct/settlement-and-processing-cycles/</span>
10. <span id="r10">European Payments Council (2020):
  SEPA Credit Transfer Scheme Rulebook, Version 1.1<br>
  https://www.europeanpaymentscouncil.eu/document-library/rulebooks/2019-sepa-credit-transfer-rulebook-version-11</span>
11. <span id="r11">European Payments Council (2020):
  SEPA Direct Debit Core Rulebook, Version 1.1<br>
  https://www.europeanpaymentscouncil.eu/document-library/rulebooks/2019-sepa-direct-debit-core-rulebook-version-11</span>
