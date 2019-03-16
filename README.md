# iwr / WasteLess

Organization name: Incentivizing Waste Reduction (IWR), or WasteLess.

WasteLess proposes to use a weight machine to measure the net weight of a general waste bin, and charge the bin's rate payer on a per kg basis for this waste, in order to incentivize waste reduction. The weight machine can be mounted in a garbage truck, or a portable one could be used e.g. with garbage loader crews (which would be better suited for rear and front loaders rather than side loaders). The latter method would be less efficient, less capital-intensive, and more labour-intensive (probably with an associated higher operational cost), but may be worth considering for developing countries. Bins could be locked to prevent dumping in others' bins, and unlocked efficiently e.g. with Bluetooth technology. Cryptographic database systems like [Holochain](https://holochain.org/) could be used for transparency, auditability, scalability, security, etc. The technology works best in tandem with multiple specialized waste collection bins, such as for recycling, organics, and recyclable soft plastics such as those found in [Redcycle](https://www.redcycle.net.au/) bins. To prevent illegal dumping, the scheme would work well with other initiatives such as [CleanApp](https://cleanapp.io/), as well as re-investing some of the funds generated from the scheme into cleaning up illegally dumped waste.

Please sign [this petition](https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/) if you support this proposal. The petition is needed to show public support exists for the proposal, in order for councils to commit to trialing it, or investing in a full community consultation. Post an issue if you think it has issues or can be improved.

The following is modified from the 
[Blockchain Trust Accelerator Initiative Pilot Submission](
https://github.com/jamesray1/iwr/blob/master/intro-and-join-trust-accelerator-application.md)
on
Feb 22 2019. The seed idea was first expressed 
[here on Twitter](https://twitter.com/JamesCRay01/status/936992945173020672), however the below information
should be more detailed.

It is intended to set up WasteLess as a non-profit, before receiving any funding.

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
materials like bins for glass, paper and gardboard, metals, soft plastics
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
outcome for the environment and ratepayer's pockets. Additionally,
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

Again, all biota. This is due to the far-reaching impacts of e.g.
reducing greenhouse gases such as methane, as well as reducing
resource depletion (e.g. petrochemically-derived products and associated
greenhouse gas emissions). While other effects can be more local,
such as leaching of chemicals into the land, water, and air (
note that of the air, this is
particularly due to the incineration of plastics), they can still
have far-reaching impacts. Also, once waste enters oceans (outside of
EEZs), due to
oceans being a public commons, management of such waste becomes
a global problem.

#### What steps have you taken to validate the idea/market? *

Not much as of yet.

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

#### To what extent does your idea have the potential to be scaled? *

Theoretically it can scale worldwide, wherever
waste is generated and collected, provided that there is
support from local citizens and councils, funding, tech, etc.

## Resources
In this section, please elaborate on the state of your resources.

#### What resources have already been dedicated to the project? *

I, James Ray, have been working on this project since
Thursday 21 Feb 2019. No funding has been obtained as of yet.

#### What resources do you need from the Trust Accelerator? *

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

## Working with the Trust Accelerator
#### What is the most important thing that the Trust Accelerator can do to support your work? *

- [x] Connect with governments
- [ ] Connect with technology providers
- [ ] Connect with funders
- [ ] Other:

In the application I marked "Connect with funders" as the most important,
however, connecting with governments is probably most important to show
a market demand.

## See also
For more information, see the [wiki](https://github.com/iwr-wasteless/iwr/wiki/Design-ideas-and-MVP), e.g.: [Design ideas](https://github.com/jamesray1/iwr/wiki/Design-ideas-and-MVP) and [Contact checklist](https://github.com/jamesray1/iwr/wiki/Contact-checklist).

Again, please sign [this petition](https://secure.avaaz.org/en/community_petitions/Local_councils_Incentivize_waste_reduction_by_weighing_general_waste_and_charging_for_the_weight/) if you support this proposal.
