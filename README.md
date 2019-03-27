# iwr / WasteLess

## Summary
Use a scale built into a garbage truck to measure the net weight of residual and organic waste bins (both 140 L by default, 240 L optionally at no extra fixed cost), which are collected weekly by default or optionally fortnightly. Note that residual waste may also be known as general waste, which is typically sent to landfill in Australia. Charge the rate payer on a per kg basis for this waste (e.g. 60 c/kg AUD and 20 c/kg, respectively), with an optional free service of 9 recyclable fractions in 100 L sacks, collected monthly or bimonthly. Fixed costs of equipment and collection would ideally be subsidized by federal or state funding and thus by taxes in order to deliver public benefits. However, where such subsidization is not provided, fixes fees, e.g. per pickup or per annum, may be necessary, but would increase the amount of residual waste if the price per kg is reduced. Such a scheme has been demonstrated successfully in Bjuv, Sweden, with similar weight-based pricing schemes in Denmark, Germany and Ireland. Other improvements include:
- promoting reusable/washable and/or biodegradable products such as for nappies and dialysis sacs (with which the non-biodegradable and/or disposable and non-washable forms tend to produce a lot of waste and may be financially disadvantageous to users of these products);
- cleaning up any dumped waste, although it may not actually increase after a year, as was found in Bjuv in Sweden, coupled with monitoring e.g. via [CleanApp](https://cleanapp.io/) and fines;
- possibly using transparent bins to make incorrectly sorted waste more visible, and education such as stickers, flyers, and talking to people to reduce incorrectly sorted waste. Fines could be used as a last resort.
- mechanical locked gate systems or systems like the Identify, Press, Weight (IPW) Centre may be preferable for
high-density apartments;
- Using cryptographic, scalable, public database systems such as [Holochain](https://holochain.org/) would have
benefits such as transparency, auditability, benefits of open data and open source software, and ease of scaling
the software to other demonstrations of a Bjuv-like weight-based residual, compost and 9 recyclable fractions scheme.

[![Twitter](https://img.shields.io/twitter/follow/IWRWasteLess.svg?style=social)](https://twitter.com/IWRWasteLess)

This document is intended for the general public,
in order to garner support for the proposal via
[this petition](
https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/),
and trial it with a local council.
The above sentence gives the general gist of this proposal,
so it is not really necessary to read the rest of it,
which just adds more improvements, information,
and considerations/handling of some concerns.
Given the scheme has already been successful in Sweden,
it should be fairly easy to see the value of the
proposal and sign the petition. The details below
are more intended for councils and those who may be
involved with implementing the scheme.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Abstract](#abstract)
- [The Problem / Challenge:](#the-problem--challenge)
    - [What type of social or governance challenge are you addressing? *](#what-type-of-social-or-governance-challenge-are-you-addressing-)
    - [Are there specific aspects of the problem that you want to see addressed? *](#are-there-specific-aspects-of-the-problem-that-you-want-to-see-addressed-)
    - [Is this problem currently being addressed? If so, in what ways and to what degree of success? *](#is-this-problem-currently-being-addressed-if-so-in-what-ways-and-to-what-degree-of-success-)
      - [Denmark](#denmark)
      - [Germany: Weight and volume-based systems at apartment blocks](#germany-weight-and-volume-based-systems-at-apartment-blocks)
      - [Sweden](#sweden)
  - [Ireland](#ireland)
      - [Australia](#australia)
  - [Other remarks](#other-remarks)
- [The Solution and Technology](#the-solution-and-technology)
    - [Describe your solution. How can blockchain technology address the problem? *](#describe-your-solution-how-can-blockchain-technology-address-the-problem-)
    - [Who are the actors involved/who is impacted by this pilot? *](#who-are-the-actors-involvedwho-is-impacted-by-this-pilot-)
    - [How many people would your solution be helping? *](#how-many-people-would-your-solution-be-helping-)
    - [What steps have you taken to validate the idea/market? *](#what-steps-have-you-taken-to-validate-the-ideamarket-)
    - [How complex will the application need to be for successful functionality? *](#how-complex-will-the-application-need-to-be-for-successful-functionality-)
    - [What challenges do you anticipate encountering were this pilot to be implemented? How can they be mitigated? *](#what-challenges-do-you-anticipate-encountering-were-this-pilot-to-be-implemented-how-can-they-be-mitigated-)
    - [To what extent does your idea have the potential to be scaled? *](#to-what-extent-does-your-idea-have-the-potential-to-be-scaled-)
- [Resources](#resources)
    - [What resources have already been dedicated to the project? *](#what-resources-have-already-been-dedicated-to-the-project-)
    - [What resources do you need? *](#what-resources-do-you-need-)
    - [What is the most important thing that can be done to support your work? *](#what-is-the-most-important-thing-that-can-be-done-to-support-your-work-)
- [Conclusions](#conclusions)
- [Q&A](#qa)
  - [How to solve dumping?](#how-to-solve-dumping)
  - [Why not start a business doing this rather than waiting for political will with councils?](#why-not-start-a-business-doing-this-rather-than-waiting-for-political-will-with-councils)
  - [Won't this scheme increase costs for people receiving government assistance / welfare payments?](#wont-this-scheme-increase-costs-for-people-receiving-government-assistance--welfare-payments)
  - [Don't we need more organic waste treatment infrastructure for this scheme to work?](#dont-we-need-more-organic-waste-treatment-infrastructure-for-this-scheme-to-work)
- [See also](#see-also)
- [Acknowledgements](#acknowledgements)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Abstract
Weight-based schemes have been implemented successfully in Denmark, Sweden and Germany
in tandem with multiple fractions of waste collection streams.
Incentivizing Waste Reduction (IWR) / WasteLess proposes to extend such schemes to more local councils,
with an initial focus on councils in the Greater Sydney metropolitan region, Australia.
The scheme involves using a scale to measure the net weight of a general waste bin,
and charge the bin's rate payer on a per kg basis for this waste, in order to incentivize waste reduction, with some other improvements and considerations. Benefits include fairer pricing of waste, and when likely reducing waste substantially due to incentivization, benefits extend to less landfill (the proposal could even be extended to the public being incentivized to remove waste from landfill), reduced greenhouse emissions (particularly from methane), reuse/recycling of resources (which is particularly important for non-renewable resources), and a more sustainable society. The scale can be mounted in a garbage truck, or a portable one could be used e.g. with garbage loader crews. The latter method would be better suited for rear and front loaders rather than automated side loaders) and would be less efficient, less capital-intensive, and more labour-intensive, but may be worth considering for developing countries. Bins could be locked to prevent dumping in others' bins, and unlocked efficiently with Bluetooth technology. Cryptographic database systems like [Holochain](https://holochain.org/) could be used for transparency, auditability, scalability, security, etc., while the data could also be used (after being anonymised and aggregated) to get insights into trends of waste with location and demographics, which could in turn be useful e.g. for more targeted education programs to reduce waste. The technology works best in tandem with multiple specialized waste collection bins, such as for recycling, organics, and recyclable soft plastics such as those found in [Redcycle](https://www.redcycle.net.au/) bins. To prevent illegal dumping and putting waste into the wrong bins (e.g. putting non-biodegradable plastic bags into an organics bin), bins could be made transparent, and the scheme would work better with other initiatives such as monitoring, reporting and cleanup technology like [CleanApp](https://cleanapp.io/), as well as re-investing some of the funds generated from the scheme into cleaning up illegally dumped waste. Compassionate treatment of financially disadvantaged people is needed to ensure that they are not worse off with this scheme, such as ratepayer government assistance, coupled with other assistance to help them that is beyond the scope of this proposal.

Please sign [this petition](
https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/)
if you support this proposal. The petition is needed to show public support exists for the proposal, in order for councils to commit to trialing it, or investing in a full community consultation. Post an issue or message me via https://about.me/james.ray if you think it has issues or can be improved, tear it apart!

The following is modified from the
[Blockchain Trust Accelerator Initiative Pilot Submission](
intro-and-join-trust-accelerator-application.md)
on
Feb 22 2019. I have decided to keep the overall structure, as it frames the
proposal well. The seed idea was first expressed
[here on Twitter](https://twitter.com/JamesCRay01/status/936992945173020672),
however the below information
should be more detailed.

## The Problem / Challenge:

In this section, please be prepared to explain what specific challenges you
wish to address.

#### What type of social or governance challenge are you addressing? *
- [ ] Corruption
- [ ] Economic Opportunity
- [ ] Property Rights
- [ ] Strengthening Civil Society
- [ ] Supply Chain Tracking
- [ ] Voting
- [ ] Financial Transaction
- [x] Other: Waste management and associated effects of waste, including
methane emissions, resource depletion, toxicity impacts in land, water and air;
and impacts on birds, aquatic life,
and other biota.

#### Are there specific aspects of the problem that you want to see addressed? *

My idea involves addressing the problem of incentivizing waste reduction,
i.e. addressing a lack of sufficient incentives for reducing waste.

#### Is this problem currently being addressed? If so, in what ways and to what degree of success? *

I don't think it is being addressed well because councils generally charge a
flat rate for collection. Some councils provide options of different bin
sizes, but still charge a flat rate per week in proportion to the bin's
capacity.

The problem has been addressed in rural municipalities in Denmark, in
cities in Germany, and
in Sweden [[1](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].

##### Denmark

A weight-based kerbside collection scheme as used in
Danish municipalities would work best for single-unit dwellings, while refer
to the German projects in cities below for multiple-unit dwellings.

In Denmark, residents may request an electronic lock
for their bin, but few have been
requested [[1, p. 16](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].
However, if this scheme was implemented in metropolitan areas,
more locks may be requested.

Denmark has a fixed and variable portions for their scheme.
"However, the fee varies from 594–1,066 DKK [127–229 AUD]
per household
per year [this appears to be referring to the fixed fee,
since the fixed fee in the Bogense municipality is 1,063 DKK
per household per year] between the municipalities, depending on the service
level in general, the quantity of waste effectively covered
by the fixed element of the overall fee, and the fee for the
waste exceeding the fixed waste quantity. In the municipality
of Bogense the fee for waste collection consists of a fixed
yearly fee and a variable weight-based fee…
The fixed fee for households covers 5 kg waste per collection…
The variable, weight-dependent fee is paid per kg waste
(i.e. residual and organic waste) above the 5 kg figure." [[1, p. 16
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
The variable fee in Bogense, 2000, is 3.75 DKK per kg organic/residual waste
(this applies to waste over the 5 kg limit). [[1, p. 16
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
The study compared two Danish municipalities, Bogense and Oelstykke,
with and without the weight-based scheme, respectively,
found that Bogense was cheaper, even with a four-person household,
but noting that the fee in Oelstykke is above average for Danish municipalities,
and also noting that "The municipality of Bogense uses e.g. approximately 960 hours
per year for administration compared to approximately 860 hours per year in the
municipality of Oelstykke."

The study found that the weight-based scheme reduced waste:
"On average, the amount of waste collected in municipalities
with weight-based schemes is 359 kg less per household compared
to municipalities withoutweight-based schemes. Taking composting
in private gardens into account,the difference is estimated as
279 kg per household." [[1, p. 18
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]

Furthermore: "A significant increase in the amount of paper and cardboard
collected has been registered compared to municipalities without
this scheme. However, the amount of glass collected is almost similar."
[[1, p. 18
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
The finding on glass may be because glass has to be "taken to
central containers… or to the municipal recycling station",
in Bogense, an inconvenience. [[1, p. 15
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
This may be because glass tends to reduce the economic
viability of waste collection [[2](
https://www.waste360.com/glass/focusing-economics-glass-recycling)].

The study also noted a higher degree of home composting was likely,
economic benefits for sorting/recycling,
and disadvantages including dumping, burning of waste (which
may have health impacts), no solidarity to households with
high amounts of waste e.g. families with babies, and
heavy administration [[1, p. 19–21
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].
As noted elsewhere in this proposal,
potential resolutions for dumping including monitoring
with CleanApp and funding from fines,
the scheme and/or tax, although the study
notes that the dumping "was especially a problem in the beginning when the
scheme was introduced, and in some of the municipalities, the dumping of waste
at lay-bys has fallen back to the initial level" [[1, p. 21
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]. Burning of waste is
difficult to negate, because it can be
done privately in one's own home,
but education about the impacts on
air quality, the environment, and
health would help to reduce this.
Administration can be reduced through the use of
IT, as discussed elsewhere in this proposal,
or if necessary funded through the scheme
(which is cheaper than the traditional one). The study also noted that
families with babies can use reusuable diapers, and this alternative can be
promoted [[1, p. 21
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].

The study noted that the scheme should only be implemented
in municipalities where the environmental consciousness/
duty/stewardship is relatively high, otherwise it would be more economical to
first concentrate on "information campaigns where the citizens are given
instructions on sorting and recycling of waste (with weight-based schemes
introduced subsequently)" [[1, p. 22
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].
At any rate, it may be best practice to have at least an information campaign,
before implementing a scheme in a municipality, regardless of how well environmentally-
dutiful citizens may be.

##### Germany: Weight and volume-based systems at apartment blocks

The study notes various problems for a weight-based system for multiple-unit
dwellings, including where tenants reside [[1, p. 23
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].
It examines the results of an Identify, Press, Weight (IPW) Centre [[1, p. 23–26
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
and a
simple mechanical lock gate system, using a chip card [[1, p. 26–29
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
(a tap and pay
card would be more efficient, but note the fraud concerns outlined below—CTRL+F
"debit card", which should nevertheless be manageable by not using debit cards.)

##### Sweden
Since the year 2000, the Swedish munipality of Bjuv, consisting
of single- and multiple-unit residences, has had 11 fractions for waste
with a weight-based scheme: "kerbside collection of residual waste, organic
waste, newspapers, 6 fractions of packaging waste (cardboard, hard and soft
plastics, coloured and uncoloured glass, metals), and an option for kerbside
collection of garden waste" [[1, p. 43 or 54 of 143 in the PDF)
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].
Variables fees apply for residual and organic waste (3.65 SEK/kg and 1.2
SEK/kg, or ~0.56 AUD/kg and ~0.18 AUD/kg, respectively,
ignoring inflation and forex fluctations), plus a fixed fee for residual
waste (560 SEK/annum, ~86 AUD/a).

"An on-vehicle weighing system is used. Containers are tagged with an
intelligent chip (to avoid switching, voluntary or involuntary, between
neighbours) and weighed both before and after emptying. The difference in
weight is the basis for the charge to the household… This change led to the
cost for the waste collection system almost doubling."  [[1, p. 44
](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].
in this proposal, to measure the weight of the bin after emptying it,
and deduct the weight of a bin to obtain the net weight.

Collection intervals are every week or fortnight for residual waste and
compostable waste; 12 times/annum for newspaper, cardboard, and hard
plastics; and 6 times/a for coloured and uncoloured glass, and soft plastics.
140 L bins are provided for residual waste, with a 240 L bin available at no
extra fixed cost, and a 140 L container for compostable waste.

Dramatic improvements resulted in Bjuv from this scheme: in the first two years,
the total waste was reduced by 30%, residual waste reduced by more than 70%,
and recycled fractions increased by 130%. [[1, p. 44–45](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)]
There was no observable increase in litter. 62 tonnes of dumped waste was collected
in 2001, compared to total waste in the municipality of 3 kilotonnes (p. 46).
The implementation for apartment blocks was no more difficult than for detached
houses, but this may be different for urban areas.

As noted on this page, it had been difficult to balance the budget, since
residual waste (which provides most of the
revenue) was reduced more than expected, but this can be offset by a higher
fixed fee, which was subsequently planned, while also reducing the variable
fee, which was also also planned.

The study noted that if replicating the scheme in Bjuv, costs would rise
considerably, especially if there are not as many alternative collection fractions
as in Bjuv (the cost of the equipment doubled in Bjuv).

### Ireland
Some notes / key findings on [3](
http://www.regions4recycling.eu/upload/public/Good-Practices/GP_Limerick_Pay-per-Weight-system-SWR.pdf):
"The study concluded that weight-based charges are the single most effective PBU system in terms of waste prevention, waste recycling and diversion of waste from landfill. These charges prompted the highest per household recycling levels (between 27% and 32%), highest  diversion rates  from landfill (between 28% and 35%) and the lowest total kerbside waste figures (between 800kg and 947kg per annum). The study projected that if the estimated 80% of those households across Ireland currently on pay per lift / tags and differential bin systems switched to ‘per kg’ based PBU system, it could lead to an annual diversion from landfill of approximately 446,000 tonnes of domestic waste per annum."—p. 6

Annual charges and per-lift charges are important to account for the cost of transport and labour. P. 10 highlights the
importance of a federally-led scheme, even if it is initially in a trial area, e.g. for preparing national legislation, strategy, coordination, education; as well as the responsibilities of the other organisations involved. It's best to read the paper directly.

The use of permits with the same conditions for private waste collectors ensure that "there was no competitive advantage for operators operatingin areas with less onerous requirements" (p. 11). However, waste collection in Ireland is financed mainly by the private sector, while in Australia it is financed by councils, with some subcontracting to private waste collectors (p. 11).

> A regulatory impact assessment undertaken by the DoECLG recognised the cost to industry in moving over to a pay by weight system, but, on the basis of the findings of the STRIVE research Study, asserted that "A  transition  to  weight  based  charging  on  a  national  basis  could  be achieved relatively cheaply, in view of the potential benefits." The  exact  investment  costs,  running  costs  and  savings  are  not  available  as  this  information  is commercially sensitive.

From the lessons learnt on p. 15, householders being able to switch between collectors that have
lower weight-based fees was a countermeasure against
actually reducing their waste, but this isn't really applicable in an
Australian residential context; as is the case
for
other problems with multiple collectors being available to households.

##### Australia

Quotes from [4](https://blog.mraconsulting.com.au/2015/08/03/weight-based-charging-the-sleeping-giant-stirs/)
> The key barrier is weighing technology on trucks that can meet the exacting standards of the National Measurement Institute (NMI), which is the regulator of weighing systems. All weight based transactions in Australia must be made on scales which have been “Approved for Trade” by NMI…
> Tony Khoury summarised the practical limitations of some weighing systems and commented that the systems needed to work consistently and robustly. It is no good if the systems do not work on wet days, sloping ground etc. It would do nothing to prevent overflowing bins or litter…

> - All systems that use scales to charge clients must be “Approved for Trade” by NMI;
> - Any private agreements based on weights, need to comply with the National Measurement legislation administered by NMI;
> - There is one accredited WBC system available and others in the process of being submitted to the NMI; and
> - The NMI would be working more closely with the waste sector on WBC weighing systems (but also on the accuracy of existing bin volumes and liquid waste volume measurements).

See also [5](https://www.veolia.com/anz/our-services/our-services/recycling-waste-services/service-delivery/pricing-management/weight-based-pricing).

### Other remarks
Weight-based charging for residual and compostable
has been found to have some elasticity [6](
https://www.sciencedirect.com/science/article/pii/S0928765516000269).
While higher fixed fees and lower weight-based fees may
help to recover costs of equipment and collection,
waste would increase proportionally with lower weight-based fees.
Therefore, subsidizing the cost of waste collection services,
e.g. via taxes, may be desirable for public benefits.
However, where there is insufficient for political will
to achieve this, having a standing charge / fixed fee
to cover the cost of transport, lift and equipment may
be the next most preferable option.

## The Solution and Technology

In this section, please be prepared to explain your pilot proposal in depth.

We will need to understand how your idea seeks to incorporate blockchain
technology to solve the problem(s) you described above.

#### Describe your solution. How can blockchain technology address the problem? *
Charge rate payers for the amount of mass that they add to general waste bins, e.g. by
having a weight machine built-in to garbage trucks, and/or into each general waste bin, or
measured by a portable scale used by garbage collection staff (this would work
for rear-loaders or front-loaders, but would be more labour intensive than the other two options).
A scale in each bin would be more expensive but scales aren't expensive,
and would allow for bin users to verify that the amounts measured and recorded
on their accounts are correct, like with water and electricity meters.

Which leads to other interesting ideas such as waste trading and markets
for waste (like with energy trading and markets projects like Grid+ and
Power Ledger). Got a full bin? No worries, just ask a neighbour in person
or via the dapp to use their bin, and pay them for it.

Scalable, distributed app frameworks
like
[Holochain](https://holochain.org) could be used to make the data transparent
and the app scalable and decentralised.

If there are dedicated bins for recycling (even for particular recyclable
materials like bins for glass, paper and cardboard, metals, soft plastics
and hard plastics), garden waste, and food waste (which
there should be, and this program should ideally only be implemented with
these), then there is no charge for using these. That way, people are
not only incentivized to reduce waste but it is more convenient to do so
and divert it to recycle or convert to other useful materials/products.
For instance, people in high-rise units don't have to use a worm farm
or bokashi bin to handle organic waste, or use a compost bin in houses
or boutique apartments.
Ideally, soft plastics that
are recyclable in [Redcycle](https://www.redcycle.net.au/)
bins would also be collected in kerbside bins,
since this would result in more soft plastics being recycled, due to convenience.
(I recycle soft plastics in Redcycle bins, but not everyone knows about them,
or can't be bothered to use them.) Note that rewarding users for
these bins would incentivize excess consumption,
or collecting biomass from forest to put in their own green waste bin,
both of which would be perverse behaviours and outcomes.
Others benefit from
the resources collected in these bins, so any cost to use these bins, if any,
should be discounted to account for such external benefits.

However, it should be noted that this technology, if not used with all the
above bins and collections of each of them, would add pressure on councils
to do so, since ratepayers would be more incentivized to reduce waste,
and thus pressure/lobby councils to invest in bins and collecting for
recycling, garden waste and organics (which can be collected together,
although collecting garden waste has been done more), soft recyclable
plastics as is done with Redcycle but not kerbside recycling, e-waste,
etc., or other technologies. While this may be an inconvenient consequence
for potential clients of this technology, councils, it would be a good
outcome for the environment and ratepayers' pockets. Additionally,
given that China is not accepting some post-consumer recycled materials,
there is an extra burden on councils from a local to federal level to
manage waste.

The truck follows a route,
and so can log the address of the house for each new bin unloaded into the
truck, with the additional weight measured. Coordinates of the truck via
GPS and mobile data
and the timestamp at the time of loading a bin
can also be
used as an extra verification. The accuracy of the weight machine
should probably be no more than 1 gram. Using Distributed Ledger Technology (DLT)
to store this data has
benefits including transparency, auditability, censorship-resistance, and
better scalability to different councils worldwide. Making the DLT
Free and Open Source Software (FOSS) has
benefits including auditability and better ability to improve it or adapt it
for other projects.

The project can be adapted for stationary public bins, etc., by having an
interface that involves needing to pay to use the bin, but this would be more
complex, and would need to be not much more inconvenient than putting waste in
a bin. E.g. put it on a weight balance externally on the bin, tap a card to
pay, put it in the bin. Even this would probably be too inconvenient, however.

People who waste less, pay less, and people who waste more are incentivized to
waste less, or the funds collected can be spent on better waste management
technology and outreach/education/raising of awareness.

As described below, bins should be locked to prevent dumping in others bins,
and should be unlocked by trucks and users with Bluetooth technology for
efficiency.

#### Who are the actors involved/who is impacted by this pilot? *
Everyone that puts waste in bins and is involved with waste,
or affected by it, which is really everyone and everything on this
Earth.

#### How many people would your solution be helping? *

Again, all biota. This is due to the far-reaching impacts of
reducing greenhouse gases such as methane, as well as reducing
resource depletion (e.g. petrochemically-derived products and associated
greenhouse gas emissions). While other effects can be more local,
such as leaching of chemicals into the land, water, and air
(note that of the air, this is
particularly due to the incineration of plastics), they can also still
have far-reaching impacts. Also, once waste enters oceans (outside of
EEZs), due to
oceans being a public commons, management of such waste becomes
a global problem.

Another benefit is that the data collected
could have broader uses
and help to understand waste trends by area, etc.
Users should have their data anonymised and aggregated by default,
unless they wish to opt out of doing so. Holochain and other
blockchains provide the ability to have anonymous accounts,
although it is possible for governments to identify accounts
e.g. due to KYC of exchanges, and tracing transactions.
Nevertheless, this possibility should not be a concern for
this particular use case, since users will need to specify
an account to debit from, and KYC would be needed to
prevent fraud, etc. Initially, it may be simpler to trial
with a simple centralized council-controlled database.

#### What steps have you taken to validate the idea/market? *

See e.g. [here](wiki/Contact-checklist).

#### How complex will the application need to be for successful functionality? *

An app for bin users would show the amounts debited with
each collection and the mass measured of the collected waste,
as well as charts per month, year, and total.
Councils could still send an invoice as per usual.
Bin users could have a blockchain account for debits, but
this could be opt-in. The currency for the transactions
should probably be the local fiat currency, represented by
a synthetic digital token pegged to the said currency.

#### What challenges do you anticipate encountering were this pilot to be implemented? How can they be mitigated? *

I'm not sure if there needs to be an app for end-users. Councils could still
send an invoice. Bin users could have a blockchain account for debits, but
this could be opt-in.

People could dump waste into neighbours bins, or any bin other than their own,
or anywhere else other than
their own bin. To prevent dumping into other bins, bins should have a lock
on them. However, bins would then need to be unlocked when collecting.
There might be ways to automate this, such as using RFID cards, but they add
complexity, costs, and would still take longer than the traditional
collection procedure. Using a master RFID card with the truck would also
be a security concern. Another option is to use Bluetooth technology,
where the truck has the ability to quickly unlock a bin when it comes in range.
If this solution was developed and worked, it would be quick, secure for bins.
There would still be an attack vector by hacking the technology and using it
in another device, or using the truck or device on it, but if the solution
can be fast enough to not add any noticeable lag to collection times,
then the overall technology seems to be worth sufficient merit to trial.

An alternative is to use [CleanApp](https://cleanapp.io), CCTVs,
[neighbourhood watch](
https://en.wikipedia.org/wiki/Neighborhood_watch), police, etc.,
to monitor and report on suspicious activity with dumping in bins.
Notably, these measures would be needed for dumping that is not in
bins.

Care needs to be taken that financially disadvantaged people are
not worse off with this scheme, and government assistance can
be increased if needed.

Who's going to pay for the waste in rental properties, including share
houses? The ratepayer pays, but in share houses, there is a similar
problem of who pays for utility bills like electricity, water, telecoms,
and gas. A tenant is even incentivized to reduce the waste of a shared
household and that
is produced by flatmates. They may do this anyway without this scheme,
but may get tired of doing so, particularly without an incentive.
Landlords may also sublet rooms, and while this is less common than
leasing a whole dwelling, in this arrangement it is common for
landlords to roll the cost of utilities into the rent, and
it can be expected that they will typically add a higher amount to the rent
than what is paid in bills, e.g. to account for risk.

Nevertheless, paying-by-weight seems fairer than a flat rate.
Dealing with the problem of not further disadvantaging
people facing financial hardships is a more systemic issue,
and can be handled with more government assistance
as needed.

What if councils decide to still charge a flat rate, in order to
be able to fund expenses of waste collection? This is
analogous to flat rates and c/kWh rates in the electricity
market. This should be less likely to occur, since they are a government,
not a for-profit business, and worst-case can cover the cost via
rates. Note that if people don't put their general waste bin out every week,
which wouldn't have a problem with smelliness, etc., if they don't
put organics in it, then the garbage truck doesn't have to stop
to pick it up, saving time and costs.

It would be more complicated, and not really worth the additional
complexity, to charge when a user unlocks the bin and adds waste.
Such a method would probably require a screen, human interface
and computer on and in the bin. It also isn't suitable for shared households
such as families and share housing, where people typically put waste
into a bin inside, then take it out every night or when it gets full.
Charging the person who puts the waste out would be unfair, and
organizing a roster of who puts the bins out would be inconvenient.
While more complicated, a user who takes waste out of the bin could
receive a credit for doing so, although they could then just
dump the waste elsewhere, rather than sort it to put recyclables in
the recycling bin, etc. This would be a perverse outcome.
This method could be used for public bins, but is inconvenient,
and could also disincentivize using them and increase litter,
which would again not be ideal. So it would probably be better
to continue using public bins as accessible without a charge.

Another problem is that people could put waste in the ‘free’,
or lower-cost bins
(e.g. recycling). There could be a fine to discourage this
behaviour, together with transparent recycling bins,
use of reporting such as via [CleanApp](https://cleanapp.io/)
or even from the garbage truck crew themselves (which would
be possible with transparent bins, since a one-person
crew (the driver) as with a side loader can see it
without even needing to get out of the vehicle.

Waste such as soft plastics
(the kinds that can be put in Redcycle bins, like plastic bags,
packaging, and low-density polyethylene) are problematic
since they are light, and so a charge by mass would not
incentivize proper management of this waste.
While having dedicated kerbside bins for soft plastic recycling
would certainly help, there are still people (I know from
personal experience with living in boarding houses) who
will see a bin and put anything in it, regardless of the colour
of the lid! Thus the above transparent bins, reporting, warnings,
education (talk with them, give them a pamphlet, etc.) and fines
would help to deal with this problem. Additionally,
fines for putting soft plastics in general waste bins is
probably extreme. They would need to be not a large amount if
done at all, although if too small or there's no fine
there's no incentive to change behaviour. Again,
I want to point out that financially disadvantaged people
should be treated compassionately in these cases.

If data is not automatically collected during collection,
and is instead manually entered e.g. by the driver,
that would be less efficient, and also be a potential
source of corruption. Residents could bribe the driver
to not enter the data, or enter a lower weight.
Hence, automating the data entry of masses collected
with the address and account is needed.

It would be an extra inconvenience to grab a Bluetooth chip
when you want to unlock your bin, but not too much, e.g.
if it's attached to a keyring, which you could grab on a
key-rack by the front door on your way out, then it could
automatically unlock and open as you walk up to it.
A bin user could also leave it unlocked, then if someone dumps
a lot of stuff in it you may want to lock it thereafter.

One person gave feedback that he lived in an apartment
of four units and two bins, so each bin was shared
between two units. While this is probably an edge case,
you would probably want to have four bins for each unit,
unless you were happy to split the cost with the person
you share with. As mentioned, having a scale in the bin
and charging when you put stuff in would be more inconvenient,
but maybe not too much with tapping a credit/debit card.
However, using a card would pose a [security/fraud risk](
https://www.fool.com/investing/general/2014/01/14/why-you-should-never-use-your-debit-card.aspx),
and is [particularly
vulnerable](
http://fossmotorsnews.com/2019-03/Why_You_Shouldnt_Use_a_Debit_Card_at_the_Gas_Pump.html)
for debit card theft since bins are usually unattended.

#### To what extent does your idea have the potential to be scaled? *

Theoretically it can scale worldwide, wherever
waste is generated and collected, provided that there is
support from local citizens and councils, funding, tech, etc.

## Resources
In this section, please elaborate on the state of your resources.

#### What resources have already been dedicated to the project? *

I, James Ray, have been working on this project since
Thursday 21 Feb 2019. No funding has been obtained as of yet.

#### What resources do you need? *

I need funding, technology, expertise, and local councils to trial with.

I should be able to develop the software myself, but I will need to
obtain clients (there
are logs of my efforts on that
[here](wiki/Contact-checklist)
or at least potential ones e.g. via an MoU, a partnership with a garbage truck
manufacturer (or funding to purchase a vehicle and modify it), and
expertise (likely from a garbage truck manufacturer) to modify a garbage truck
as a trial with the weight machine, plus additional technologies that would
improve security and efficiency, as mentioned above, like Bluetooth, and a
database, Holochain or blockchain (the last if universal consensus is needed,
which it may not be).

#### What is the most important thing that can be done to support your work? *

- [x] Connect with governments
- [ ] Connect with technology providers
- [ ] Connect with funders
- [ ] Other:

In the application I marked "Connect with funders" as the most important,
however, connecting with governments is probably most important to show
a market demand. However, in order to do a trial with a local council,
they will probably want to see more public support for the idea,
hence [the petition](
https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/)
Although, if councils fund consultation with their
communities, that would be
much appreciated!

## Conclusions

Weight-based pricing for both residual and compostable waste, coupled with
multiple fractions for sorting recycling, has been found to
most effectively reduce waste and increase recycling.
Pricing for compostable waste is necessary because
households with sufficient land (a bare patch of soil for a
compost bin), or even those without, can compost their own waste.
For the latter case, tumbler bins, worm farms and bokashi bins can be used.
The scheme in Bjuv in Sweden was very effective (apparently the most of demonstrations studied)
in reducing waste and increasing recycling. However, the cost of the system was high. Additionally,
the case in Bjuv is just one study, and further demonstrations would be needed,
with other considerations or improvements, for more statistically
reliable evidence and conclusions. Other
considerations for policy implementers and include:

- promoting reusable/washable and/or biodegradable products as for nappies and dialysis sacs (with which the non-biodegradable and/or disposable and non-washable forms) tend to produce a lot of waste and may be financially disadvantageous to users of these products);
- cleaning up any dumped waste, although it may not actually increase after a year, as was found in Bjuv in Sweden, coupled with monitoring e.g. via [CleanApp](https://cleanapp.io/) and fines;
- possibly using transparent bins to make incorrectly sorted waste more visible, and education such as stickers, flyers, and talking to people to reduce incorrectly sorted waste. Fines could be used as a last resort.
- mechanical locked gate systems or systems like the Identify, Press, Weight (IPW) Centre may be preferable for
high-density
apartments;
- Using cryptographic, scalable, public database systems such as [Holochain](https://holochain.org/) would have
benefits such as transparency, auditability, benefits of open data and open source software, and ease of scaling
the software to other demonstrations of a Bjuv-like weight-based residual, compost and 9 recyclable fractions scheme.

## Q&A
### Wouldn't it be simpler and better to have smaller bins with a lower fixed cost?
This has pros and cons. It is a simpler scheme. It doesn't allow for highly variable amounts of waste over time, e.g. in an extreme case creating 500 kg of residual waste in an atypical week vs 0.2 kg per week of residual waste normally. I produce around the latter of residual waste normally, but occassionally I might have something large that has to go to landfill, e.g. a fan. In such a case residents could call a kerbside collection, or store the waste and slowly fill the bin(s) up week by week. Offering more bin sizes isn't as cost-reflective as per kg pricing, however, the more bin sizes that are offered, the more cost reflective it can be, but you won't get as cost-reflective as per kg pricing. 

It also doesn't account for the benefits of having multiple additional fractions of recycling waste, collected less often, compared to one mixed recycling bin per week which doesn't allow for soft plastics recycling. It also doesn't provide organic waste. However, that is somewhat orthogonal as you can still have bins for residual waste and organic waste and recyclable fractions collected in the same way in each scheme, but just charge differently and provide more bin sizes.

### How to solve dumping?
The scheme in Sweden has found that dumping was initially a problem, then went back to former levels, and did not observe a noticeable increase in litter. Monitoring and reporting e.g. with CleanApp or just calling council plus cleanup would help to manage dumped waste. The fixed fee component of the scheme, if needed, could be used to fund cleanup of dumped waste. Funding could also be allocated for council officers to patrol public areas to monitor for dumping, graffitti, etc., if and as needed. Note also that federal funding via taxes and a nation-wide deployment in councils could also be used to fund the scheme, rather than decreasing variable weight fees and increasing fixed fees, which would increase residual waste.

### Why not start a business doing this rather than waiting for political will with councils?

I'm not sure what councils will do if people refuse to put council-provided bins out, not pay rates for waste collection, and put out a bin provided by a private waste collector and pay them instead. I'd have to ask councils to see what they think, but I can't imagine they would tolerate that. I'm not sure how viable such a business would be without support from government funding, as was the case in the above Irish study. Some form of deregulation or subsidies to private waste collectors may be needed for this to work. Introducing private enterprises, if successful, would result in increased costs due to profit-seeking (and funding growth and offseting risk, etc.), which would lead todisadvantaging poorer people, particularly without adequate support, which tends to be what occurs. Generally I am more in favour of a publicly funded scheme, and do not wish to pursue this as a business.

### Won't this scheme increase costs for people receiving government assistance / welfare payments?
It would not financially disadvantage poor Australians if landlords must pay for the rates and it is made illegal to mark up the rent with Centrelink recipients due to the cost of waste. This depends on the government implementing this scheme if and only if these conditions hold. It would be enforceable for private landlords since if they threatened to evict Centrelink recipient tenants if they reported them to the government, then Centrelink recipient tenants can take the matter up with NCAT, or analogous authorities in other states, NCAT would resolve the case in the tenants favour: they continue to reside where they are without a markup in the rent due to waste collection. The government would be incentivized to implement the scheme because it has been shown to reduce waste, which will deliver public benefits and be less costly in the long-run."
See more at https://www.facebook.com/groups/WarOnWasteAU/permalink/652769901843930/?comment_id=652775288510058&comment_tracking=%7B%22tn%22%3A%22R%22%7D

### Don't we need more organic waste treatment infrastructure for this scheme to work?
Yes. See more at: https://www.facebook.com/groups/1513152818777012/permalink/2177468449012109/?comment_id=2177647292327558&comment_tracking=%7B%22tn%22%3A%22R%22%7D

## See also
For more information, see the [wiki](wiki), e.g.: [Design ideas](wiki/Design-ideas-and-MVP) and [Contact checklist](wiki/Contact-checklist).

Again, please sign [this petition](https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/) if you support this proposal.

## Acknowledgements
Thanks a lot to Sofia Max, Adam Ray, Violet/Marco Morky, Dean Cooling, and others for your feedback.
