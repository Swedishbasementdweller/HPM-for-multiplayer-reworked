# HPM for Multiplayer Reworked

Current Checksum:

Special thanks to:
-Tuplavee
-Hgramofficial
-Klink

Hotpatch:

Fixed defines.lua and issues.txt


New Update Features:

-Localization of German Alsace-Lorraine has been fixed (Elsass-Lothringen, Strassburg) (NationalUnification.txt)
-Removed the decision for Ukraine and Belarus to remove their main culture group from other countries (UKR.txt)
-Fixed Central American integration decision, now requiring 50K, having a province with Central American pops and that the USCA does not exist (Thesedecisionsimbeingforcedtomod.txt)
-Dominions start sphered now (ENG_oob.txt), and allied to the UK (alliances.txt)
-Dominions do not start as vassals now (PuppetStates.txt)
-Added South Africa as a playable 1836 (Africa folder) 
-The UK can choose which dominions (SAF, CAN, AST) to release and which to keep via event (HPMMRFlavour)
-The UK may now annex each respective dominion via decision, if need be (Thesedecisionsimbeingforcedtomod.txt)
-The UK may now puppet each respective dominion via decision, if need be (Thesedecisionsimbeingforcedtomod.txt)
-NV changes have been moved to CivNV_changes.txt
-Prussian generals have been nerfed: (PRU_oob.txt) 
(Von Moltke 4ATK --> 3ATK, ORG 15%, RELI 5%) 
(Von Roon 5ATK, ORG 15% --> 4ATK, ORG 10%)
(Von Wrangel 5ATK --> 4ATK)
-All of the problematic localization has been fixed! (00_HPM_decisions.csv)
-Doctrine of Lapse has been re-increased (50 --> 150) (CivilizationAndGunBoats.txt)
-Freeing vassals does not cost any prestige anymore (gtfo.txt)
-Dominions will not ask for independence anymore (trigger date has been changed to 1950) (BritishDominions.txt) (CANFlavor.txt)
-Added Bulgarian integration decision for the Ottomans, requiring 500K, having a province with Bulgarian pops and that Bulgaria does not exist


Version 0.5 Features:

-Rebalanced the national values
-Problematic localization has been fixed
-Removed the 0.001 from the commerce inventions, instead added an extra 0.001 pop growth flat for reasearching the market techs in the commerce tab (Futures stayed, but have been repurposed to add throughput)
-The speedboats stay!
-The texture pack has been returned back to HPM
-Mobilization size impact has been adjusted
-All healthcare reforms now give a flat 0.001 pop growth modifier
-Rebel war exhaustion updated! No more WE from colonial rebels


Version 0.4 Features:

-Further reduced the prestige required for Gran Colombia and La Plata from 10 to 5
-Lowered militancy from failed CB's from 2.5 to 1
-Added prestige hits from failed CB's from 0 to base -10
-The texture pack has been changed to Belle Cartographie (https://www.moddb.com/mods/belle-cartographie)
-Max steam transporter speed has been increased to 30 (from 16, Dreadnoughts are on 31)
-No more artillery needed for clipper transports (YES FINALLY)
-National value change decision has been added. It can only be activated once, including for uncivs
-National values have been rebalanced (https://github.com/SteelRyan/IGoRS/releases/tag/IGoRS-10.2.1)
-The golden law decision for Brazil can now be taken even after slavery has been outlawed
-Protecting the natives decision (Getting their cultures accepted), has been made easier, now only requiring limited citizenship and can be done without the national value of equality
-No more earrape when the game is started
-Doctrine of Lapse has been reduced from a mean time of 500 months to 50
-Removed the Kurdish countries from the 1836 start date (istg why were them provinces in the balkans and south america file)
-Added South American Union formable
-Fixed Portugal-Brazil's flags and names (btw tag: EOP)
-Healthcare reforms now all only give a flat 0.001 modifier, with the newly added increasing factor being the supply limit, starting on 5%, and then, 10%, 15,% 20% and lastly 25%
-Fully funding your healthcare on every level will now give you only 0.001 extra pop growth, except for the last two giving 0.002 and 0.003 at full funding respectively
-The input effeciency tech modifier of -0.01 in every economic though tech has been changed to -0.02 
-Market Regulations in the commerce tab now offers an additional 10% increase in iron output
-Added an invention to three commerce techs (business regulations, market structure and marketregulations), that each add another 0.001 pop growth


Version 0.3 Features:

 -Forming Scandinavia does not require great power status anymore
 -Removed jingoism being required to add wargoals
 -Removed prestige and infamy loss from removing someone from your sphere
 -Removed prestige loss from freeing a dominion/satellite
 -Made not fulfilling wargoals not cost prestige but raises militancy by 2.5
 -Lowered the loss of plurality of dissolving the upper house from -10 to -2
 -Added a decision to allow France to receive Walloon as an accepted culture
 -Added a decision that allows Portugal to reabsorb Brazil and form the Empire of Portugal
 -Increased the life rating of every French province below 34 up to 34
 -Canada and Australia can now be annexed as colonies into the UK instead of as states (fix)
 -Hyperborean Social Healthcare
 -Infamy reduction to 0.20 at peace, 0.10 at war (from 0.13 & 0.5)
 -Reduced war exhaustion gain by 75%
 -Reduced total war WE reduction from -3/-2/-1 to -2/-1,5/-1
 -Increased unciv rp by .25 points
 -Removed conquest RP debuff on isolationism
 -Reduced the New World immigration penalty at war to 10% (from 130%)
 -Reduced regency penalties, added social refrom desire to compensate
 -Restored homestead & Statue of Liberty assimilation to 100% from 50%, reconstruction to 60%
 -Increased Jizya tax efficiency from 10% to 15%
 -Increased French minorities assimilation speed from 200% to 300%
 -Reduced diplomacy delay to 1 day (would do 0 but AI might react weird)
 -Slightly increased global assimilation rate
 -Starting republics have anti-military and pacifist parties swapped to pro-military (not all, playables)
 -Soldiers shouldn't rebel now
 -Constitutional crisis plurality loss to 1, prestige loss to 15
 -Ottomans can accept Greek with Nat & Imp
 -Doubled naval supply range
 -Can increase conscription via decision without being at war (still need military policy)
 -Swiss culture has been replaced by the historically accurate cultures found in Switzerland
 -Increased the chance of getting gas defence & gas attack
 -Reduced machine parts factory machine parts cost by 90% (from 200 to 20)
 -NGF & Italy can be formed with state & government
 -Forming Scandi needs 50 prestige (From 150)
 -Forming Iberia, Gran Colombia and La Plata needs only 10 prestige now (From 25)
 -Tweaked industry inventions (you can now actually get the coal & iron inventions woop woop)
 

Version 0.2 Features:

 -New Belgium-Netherlands formable (taken from GFM)
 -Removed the extra infamy modifier, returning to the basegame (-0.1/month)
 -Iberia can now be formed without fantasy nations having to be enabled
 -Iberia can now be formed without having to be a great power
 -Added a decision that allows Sweden to annex Norway after having researched Nationalism and Imperialism
 -Made Canada and Australia playable 1836 as dominions, the UK can then wish to reannex either both, only one of them or keep them as dominions
 -Renamed Palestine to Israel
 -Changed Palestinian province names to their Hebrew versions
 -The Netherlands can now get the Walloons as an accepted culture


First Update Features:

 -Added Minor Conquest 
 -Added Demand Capital (taken from DOD)
 -Added Demand Capital concession (taken from DOD)
 -Removed that joke at the start of the game
 -Increased the amount of militancy needed for pops to rise up 
 -Communist Germany turns red now
 -Germany now has the colour of Prussia (its not perfectly the same)
 -Iberia now has a dark orange colour
 -Iberia now has a new monarchist flag (a mix of DODs Spain and the basegames Iberia flag)
 -Cotton RGO in Jaffa instead of fruits
 -Oil RGO event in Jaffa starting 1870
 -Requirements to form Scandinavia lowered from 300 to 150 prestige
 -Requirements to form Gran Colombia lowered from 50 to 25 prestige
 -Requirements to form La Plata lowered from 50 to 25 prestige
 -Higher liferatings in Stockholm (40-45), Gothenburg (35-40), Malmoe (35-40) and Christinia (40-42)
 
