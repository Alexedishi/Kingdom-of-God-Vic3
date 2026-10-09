##################
# KINGDOM OF GOD #
##################
Mod Version: Initial Release
Game Version: 1.15.0

Mod Author: Alexedishi
Special Thanks: RationaLess, Bahmut|Chris


####---------- Mod Dependencies ----------####
- Community Mod Framework: https://steamcommunity.com/sharedfiles/filedetails/?id=3385002128


####---------- Version Compatibility ----------####
#		KoG Patch	....	Victoria 3 Patch
#		Release		....	1.15.0


####---------- Current Content Scope ----------####
++ Scripted Content Scope: ++
The following faiths are in-scope:
- Roman Catholicism
- Eastern Orthodoxy

The following faiths will eventually come into scope:
- Oriental Orthodoxy
- European Lutheranism (this will include content for Calvinism)
- Anglicanism

**Notes:
- American Protestantism is OUT OF SCOPE

++ Mechanical Scope: ++
The current mechanics are in-scope:
- Local metropolitan / national church content
- Subdivision of faiths via liturgical rites and languages on a per-country basis
- Canon laws managed on a per-faith basis
- Schism mechanics managed on a per-country basis
- Encyclicals as contextless journal entries on a per-faith basis
- Ecumenical councils as contextless journal entries on a per-faith basis
- College of Cardinals (or equivalent body) on a per-faith basis include Papal elections as appropriate
- Episcopal Seats as minor political entities separate from the overall church body

The following mechanics will eventually come into scope:
- The role of priests in colonization (particularly relevant for Russia)
- Mechanics for the preservation and veneration of Holy Sites by the state


####---------- Mod Structure and Organization ----------####
Scripted content is broadly divided into the following "modules" which can be identified by their prefixes:
- kog_general_: Framework content shared between multiple other modules
- kog_catholic_: Content relating to the Roman Catholic Church
- kog_orthodox_: Content relating to the Eastern Orthodox Churches
- kog_oriental_: Content relating to the Oriental Orthodox Churches
- kog_lutheran_: Content relating to the Lutheran Churches
- kog_anglican_: Content relating to the Anglican Communion
- kog_elysian_: Content relating to the Elysian Orthodox Churches (Basielia Romaion)
- kog_rite_: Content relating to Liturgical Rites
- kog_canon_law_: Content relating to Canon Laws
- kog_schism_: Content relating to Schism and Autocephaly
- kog_council_: Content relating to Ecumenical Councils
- kog_ecumenical_: Content relating to Ecumenism and Mending Schisms
- kog_collegium_: Content relating to the College of Cardinals
- kog_encyclical_: Content relating to Encyclicals
- kog_holy_site_: Content relating to Holy Sites
- kog_religious_communion_: Content relating to Religious Communions
- kog_epsicopal_seat_: Content relating to Episcopal Seats
- kog_pagan_: Content relating to Christian-Pagan Relations
- kog_event_: Content not otherwise specified or grouped into an existing module

GUI-specific script and frameworks are broadly divided into the following "modules" which can be identified by their prefixes:
- kog_technical_: Script implementing background and framework features
- kog_overview_: Script implementing the "Overview" tab of InterOrg journals
- kog_metropolis_: Script implementing the "Metropolis" tab of InterOrg journals
- kog_canon_law_: Script implementing the "Canon Laws" tab of InterOrg Journals
- kog_collegium_: Script implementing the "Collegium" tab of InterOrg Journals
- kog_episcopal_seat_: Script implementing the "Episcopal Seats" tab of InterOrg journals
- kog_ecumenical_council_: Script implementing the journal widgets for Ecumenical Council journals


####---------- Planned Updates ----------####
--Update 1.0.1--
- TBD


####---------- Published Updates ----------####
--Release 1.0.0-- **Initial Release**
- Released Mod "Kingdom of God" aiming to add flavor to the Christian faiths in Victoria 3
- Mod is dependent on Community Mod Framework
- Additional content is available when used in conjunction with Gates of the Bosphorus or Basielia Romaion

Initial Content:
- Contextless journal entries providing mechanics for the Catholic and Eastern Orthodox base game faiths, and the Elysian Orthodox faith of Basielia Romaion; These use the "Internation Organizations Framework" provided by CMF
- "Local Metropolis" mechanics to simulate the relationship between the state and church
- "Denomination"-level mechanics simulating intra-faith politics, canon laws, encyclicals, and ecclesial administration as appropriate per-faith
- "Collegium" mechanics simulating a "College of Cardinals" and election of a Pontifex as appropriate for each faith
- "Episcopal Seat" mechanics simulating specifical prominent archdiocese-level churches as minor political entities unto themselves
- Three new law groups: "Investiture", "Church Holdings", and "Church Tax"
- "Schism" mechanic to separate your national church from the larger church body