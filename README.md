# iwr / WasteLess

> In one sentence: use a scale to measure the net weight of a general waste bin, and charge the bin's rate payer on a per kg basis for this waste, in order to incentivize waste reduction, with some other improvements.

[![Twitter](https://img.shields.io/twitter/follow/IWRWasteLess.svg?style=social)](https://twitter.com/IWRWasteLess)

This document is intended for the general public,
in order to garner support for the proposal,
and trial it with a local council.
If you encounter jargon which you are not familiar with,
feel free to just skip over it.

Summary/abstract: Weight-based schemes have been implemented in Denmark, Sweden and Germany.
Incentivizing Waste Reduction (IWR) / WasteLess proposes to extend such schemes to more local councils,
with an initial focus on councils in the Greater Sydney metropolitan region, Australia.
The scheme involves using a scale to measure the net weight of a general waste bin,
and charge the bin's rate payer on a per kg basis for this waste, in order to incentivize waste reduction, with some other improvements and considerations. Benefits include fairer pricing of waste, and when likely reducing waste substantially due to incentivization, benefits extend to less landfill (the proposal could even be extended to the public being incentivized to remove waste from landfill), reduced greenhouse emissions (particularly from methane), reuse/recycling of resources (which is particularly important for non-renewable resources), and a more sustainable society. The scale can be mounted in a garbage truck, or a portable one could be used e.g. with garbage loader crews. The latter method would be better suited for rear and front loaders rather than automated side loaders) and would be less efficient, less capital-intensive, and more labour-intensive, but may be worth considering for developing countries. Bins could be locked to prevent dumping in others' bins, and unlocked efficiently with Bluetooth technology. Cryptographic database systems like [Holochain](https://holochain.org/) could be used for transparency, auditability, scalability, security, etc., while the data could also be used (after being anonymised and aggregated) to get insights into trends of waste with location and demographics, which could in turn be useful e.g. for more targeted education programs to reduce waste. The technology works best in tandem with multiple specialized waste collection bins, such as for recycling, organics, and recyclable soft plastics such as those found in [Redcycle](https://www.redcycle.net.au/) bins. To prevent illegal dumping and putting wastes into the wrong bins (e.g. putting non-biodegradable plastic bags into an organics bin), bins could be made transparent, and the scheme would work better with other initiatives such as monitoring, reporting and cleanup technology like [CleanApp](https://cleanapp.io/), as well as re-investing some of the funds generated from the scheme into cleaning up illegally dumped waste. Compassionate treatment of financially disadvantaged people is needed to ensure that they are not worse off with this scheme, such as ratepayer government assistance, coupled with other assistance to help them that is beyond the scope of this proposal.

Please sign [this petition](https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/) if you support this proposal. The petition is needed to show public support exists for the proposal, in order for councils to commit to trialing it, or investing in a full community consultation. Post an issue or message me via https://about.me/james.ray if you think it has issues or can be improved, tear it apart!

The following is modified from the 
[Blockchain Trust Accelerator Initiative Pilot Submission](
https://github.com/jamesray1/iwr/blob/master/intro-and-join-trust-accelerator-application.md)
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

The problem has been addressed in rural municipalities in Denmark,
in Sweden, and in Germany [[1](
http://ec.europa.eu/environment/waste/studies/pdf/financingmuncipalwaste_management.pdf)].

##### Denmark
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
viability of waste collection [2](
https://www.waste360.com/glass/focusing-economics-glass-recycling).

##### Sweden

##### Germany

##### Australia

TODO: finish notes on the above study and 
assess costs in a local council area(s)
in Australia.

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
such as leaching of chemicals into the land, water, and air (
note that of the air, this is
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

See e.g. [here](https://github.com/jamesray1/iwr/wiki/Contact-checklist).

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
[here](https://github.com/jamesray1/iwr/wiki/Contact-checklist)
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
they will probably want to see more public support for the idea.
Although, if councils fund consultation with their
communities, that would be
much appreciated!

## See also
For more information, see the [wiki](https://github.com/iwr-wasteless/iwr/wiki/Design-ideas-and-MVP), e.g.: [Design ideas](https://github.com/jamesray1/iwr/wiki/Design-ideas-and-MVP) and [Contact checklist](https://github.com/jamesray1/iwr/wiki/Contact-checklist).

Again, please sign [this petition](https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/) if you support this proposal.

## Acknowledgements
Thanks a lot to Sofia Max, Adam Ray, Marco Morky, Dean Cooling, and others for your feedback.
