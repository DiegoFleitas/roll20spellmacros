[[TOC]]

# Spell Macros (mine):

## Orisons/cantrips:

Create Water:

 /em casts Create Water.

She creates up to [[2*@{casterlevel}]] gallons of water at a location within [[d1*25+5*floor(@{casterlevel}/2)]] feet.  The water can either be created in as small an area as will actually contain it, filling one or more small (or larger) receptacles, or in an area 3 times as large, creating a brief downpour.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Create Water](http://www.dandwiki.com/wiki/Create_water ).}} {{check=She creates up to [[2*@{casterlevel}]] gallons of water }} {{checkroll= at a location within [[d1*25+5*floor(@{casterlevel}/2)]] feet. }} {{notes= The water can either be created in as small an area as will actually contain it, filling one or more small (or larger) receptacles, or in an area 3 times as large, creating a brief downpour. }}

Cure Minor Wounds:

/em casts Cure Minor Wounds, granting 1 heath to ?{Recipient's name|herself}.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Minor Wounds](http://www.dandwiki.com/wiki/Cure_minor_wounds ).}} {{check=@{target|token_name} receives }} {{checkroll= [[1d1]] heath. }}

/em casts Cure Minor Wounds (L0 Conj(Healing); V,S; 1 std action; Touch; Creature touched; Instantaneous; Will Save(half) when used vs Undead; Undead can use spell resistance.), granting 1 heath (or causing 1 point of damage to an undead creature) to ?{Recipient's name|himself}.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Minor Wounds](http://www.dandwiki.com/wiki/Cure_minor_wounds ).}}  {{School:= Conj(Healing)}} {{Level:= Cleric 0}} {{Cmp’nts:=V,S}} {{Casting Time:=1 std action}} {{Range:= Touch}} {{Target:= Creature touched}} {{Duration:= Instantaneous}} {{Saving Throw:= Will Save(half) when used vs Undead}} {{Spell Resist.:= Undead can use spell resistance}} {{   Caster level check: = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|16}]] }} {{succeedcheck=Success! She casts her spell!}} {{failcheck=She fails :( }}  {{notes= ?{Recipient's name|@{character_name}} receives 1 heath (or 1 point of damage if an undead creature) }} 

Flare:

 /em casts Flare.

A burst of light erupts at a location within [[d1*25+5*floor(@{casterlevel}/2)]] feet.  One creature facing that location must make a DC [[10 + 0 + @{wis-mod}]] Fortitude save or be dazzled (-1 to attack rolls, search/spot checks) for 1 minute.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Flare](http://www.dandwiki.com/wiki/SRD:Flare ).}} {{check=A burst of light erupts at a location within [[d1*25+5*floor(@{casterlevel}/2)]] feet. }} {{checkroll= One creature facing that location must make a DC [[10 + 0 + @{wis-mod}]] Fortitude save or be dazzled (-1 to attack rolls, search/spot checks) for 1 minute.. }}

Light

 /em casts Light on ?{target's name|a small rock} which glows like a torch. ([[d1*10*@{casterlevel}]] min duration)

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Light](http://www.dandwiki.com/wiki/SRD:Light ) on ?{target's name|a small rock}}} {{check=It }} {{checkroll= glows like a torch.  }} {{notes=([[d1*10*@{casterlevel}]] min duration) }}

Mending

 /em casts Mending (Lvl 0 Transmutation)

One object of up to 1 lb. within 10' has small breaks/tears repaired.  Takes 1 standard action to cast.  Cannot be cast on creatures; will not restore magical properties.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Mending](http://www.dandwiki.com/wiki/SRD:Mending ).}} {{check=One object within 10 feet of up to 1 lb. is repaired of small breaks or tears.}} {{checkroll=broken metallic objects such as a ring, a chain link, a medallion, or a slender dagger, are welded providing but one break exists. }} {{notes=Ceramic or wooden objects with multiple breaks can be invisibly rejoined to be as strong as new. A hole in a leather sack or a wineskin is completely healed over by mending. The spell can repair a magic item, but the item’s magical abilities are not restored. The spell cannot mend broken magic rods, staffs, or wands, nor does it affect creatures (including constructs). }}

Purify Food and Drink:

 /em purifies [[d1*1*@{casterlevel}]] cu. ft of food or water.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{check=[purifies](http://www.dandwiki.com/wiki/SRD:Purify_Food_and_Drink ) [[d1*1*@{casterlevel}]]  }} {{checkroll=  cu. ft of food or water. }}

Read Magic

 /em can read magic for the next [[d1*10*@{casterlevel}]] min.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Read Magic](http://www.dandwiki.com/wiki/SRD:Read_Magic ).}} {{check=She can read magic for}} {{checkroll= the next [[d1*10*@{casterlevel}]] min. }}

## Level 1:

Cure Light Wounds:

/em casts Cure Light Wounds, channeling [[1d8+{@{casterlevel},5}dh1]] points of positive energy to ?{Recipient's name|herself}.

Undead creatures take damage instead of gaining healing; DC [[10+1+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Light Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Light_Wounds ).}} {{check=@{target|token_name} receives }} {{checkroll= [[1d8+{@{casterlevel},5}dh1]] heath. }} {{notes=Undead creatures take damage instead of gaining healing; DC [[10+1+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

Entangle

/em casts Entangle.

Grasses, weeds, bushes, roots, even trees wrap, twist, and entwine around creatures in an area up to [[d1*400+40*@{casterlevel}]] feet away, for up to @{casterlevel} minutes.  The creatures are held fast and entangled (Full round DC20 Str or Escape Artist check to break free and move at half speed).  Creatures who make a DC [[10 + 1 + @{wis-mod}]] Reflex check are not entangled, but still move at only half speed.  Each round, the plants once again attempt to entangle all creatures which have avoided or escaped entanglement.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Entangle](http://www.dandwiki.com/wiki/SRD:Entangle ).}} {{check=Grasses, weeds, bushes, roots, even trees wrap, twist, and entwine around creatures in a 40' r area up to [[d1*400+40*@{casterlevel}]] feet away, for up to @{casterlevel} minutes. }} {{checkroll= The creatures are held fast and entangled (Full round DC20 Str or Escape Artist check to break free and move at half speed).  Creatures who make a DC [[10 + 1 + @{wis-mod}]] Reflex check are not entangled, but still move at only half speed.  Each round, the plants once again attempt to entangle all creatures which have avoided or escaped entanglement. }}

Doom

/em casts Doom on ?{Recipient's name|the BBEG}

Necromancy(Fear, Mind affecting); Level 1; Components: V, S, DF; Casting Time: 1 std action; Range: Medium ([[100+10*@{casterlevel}]]ft; Target: 1 living creature; Duration: @{casterlevel} min.; Saving Throw: Will negates (DC=@{spelldc1}); Spell Resistance: Yes; Caster level check = [[1d20+@{casterlevel2}+@{spellpen}]] vs spell resistance.

Concentration check = [[{1d20+@{concentration}}>?{DC=15+Spell Level or 10+Damage Received|16}]] success.

Target is filled with a feeling of horrible dread that causes it to become shaken (-2 on attack rolls, saves, skill checks, ability checks).

&{template:DnD35StdRoll} {{spellflag=true}} {{name= @{character_name} casts Doom on @{target|token_name} }} {{School:=Necromancy (Fear, Mind affecting)}} {{Level: =Cleric 1}} {{Comp'nts:=V, S, DF}} {{Casting Time:= 1 std action}} {{Range:= Medium ([[100+10*@{casterlevel}]]ft)}} {{Target:= 1 living creature}} {{Duration:= [[@{casterlevel}]] min.}} {{Saving Throw:= Will negates (DC=[[@{spelldc1}]]) }} {{Spell Resist.:= Yes }} {{   Caster level check: = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|16}]] }} {{succeedcheck=Success! She casts her spell!}} {{failcheck=She fails :( }} {{notes=Target is filled with a feeling of horrible dread that causes it to become shaken (-2 on attack rolls, saves, skill checks, ability checks).}}

Longstrider

 /em casts Longstrider on herself.

Her land speed is increased by 10 feet for the next @{casterlevel} hours.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Longstrider](http://www.dandwiki.com/wiki/SRD:Longstrider ) on herself.}} {{check=Her land speed is increased by 10 feet for the next }} {{checkroll= @{casterlevel} hours. }}

Obscuring Mist:

 /em casts an Obscuring Mist.

A 20' tall bank of mist rises in a 20' r around her, lasting for @{casterlevel} minutes.  The vapor obscures all sight, including darkvision, beyond 5'.  A creature 5' away has concealment (20% miss chance); creatures farther away have total concealment (50% miss chance and attacker cannot use sight to locate target).  A moderate (11+mph) wind such as from Gust of Wind disperses fog in 4 rnds, a strong (21+mph) disperses it in 1 rnd.  A Fireball, Flame Strike or similar spell burns away the fog in the explosive or fiery spell's area; Wall of Fire burns away the fog in the area in which it deals damage; does not function underwater.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts an [Obscuring Mist](http://www.dandwiki.com/wiki/SRD:Obscuring_Mist ).}} {{check=A 20' tall bank of mist rises in a 20' r around her, lasting for @{casterlevel} minutes. }} {{checkroll= The vapor obscures all sight, including darkvision, beyond 5'.  A creature 5' away has concealment (20% miss chance); creatures farther away have total concealment (50% miss chance and attacker cannot use sight to locate target). }} {{notes=A moderate (11+mph) wind such as from Gust of Wind disperses fog in 4 rnds, a strong (21+mph) disperses it in 1 rnd.  A Fireball, Flame Strike or similar spell burns away the fog in the explosive or fiery spell's area; Wall of Fire burns away the fog in the area in which it deals damage; does not function underwater. }}

Produce Flame:

/em gestures and flames as bright as a torch appear in her hand!

The flames last for @{casterlevel} minutes and can be hurled 120 feet as a thrown weapon (ranged touch attack; no range penalty) or used to strike with a melee touch attack.  No sooner are the flames hurled than a new set appears in her hand.  Each attack reduces the remaining duration by 1 minute.  Does not function underwater.

She throws the flames, hitting touch AC [[d20+@{rangedattackbonus}+?{-2 for melee?|0}]] for [[1d6+{@{casterlevel},5}dh1]] fire damage.

?{Add att?|!} She throws again, hitting touch AC [[d20+@{rangedattackbonus}+?{-2 for melee?|0}-5]] for [[1d6+{@{casterlevel},5}dh1]] fire damage.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=gestures and [flames](http://www.dandwiki.com/wiki/SRD:Produce_Flame ) as bright as a torch appear in her hand!}} {{check=The flames last for @{casterlevel} minutes and can be hurled 120 feet as a thrown weapon  }} {{checkroll= (ranged touch attack; no range penalty) or used to strike with a melee touch attack. }} {{notes= No sooner are the flames hurled than a new set appears in her hand.  Each attack reduces the remaining duration by 1 minute.  Does not function underwater. }}

&{template:DnD35Attack} {{pcflag=true}} {{name=@{character_name}}} {{subtags=throws the flames. }} {{attack1=She hits touch AC [[d20+@{rangedattackbonus}+?{-2 for melee?|0} +?{Addt'l attack bonus?|0}]]}} {{critconfirm1=Crit!:[[d20+@{rangedattackbonus}+?{-2 for melee?|0} +?{Addt'l attack bonus?|0}]]}} {{fumbleroll=Fumble:[[d20]]}} {{damage1=for [[1d6+?{Addt'l damage bonus?|0}+{@{casterlevel},5}dh1]] fire damage.}} {{critdmg1=+[[1d6+?{Addt'l damage bonus?|0}+{@{casterlevel},5}dh1]] adt'l fire damage.}} {{fullattackflag=[[?{Full Attack? (hit space for full attack else hit return) |0}d1]]}} {{attack2=She throws again, hitting touch AC [[d20+@{rangedattackbonus}+?{-2 for melee?|0}-5 +?{Addt'l attack bonus?|0}]] }} {{critconfirm2=Crit!:[[d20+@{rangedattackbonus}+?{-2 for melee?|0}-5 +?{Addt'l attack bonus?|0}]] }} {{damage2=for [[1d6+?{Addt'l damage bonus?|0}+{@{casterlevel},5}dh1]] fire damage. }} {{critdmg2=+[[1d6+?{Addt'l damage bonus?|0}+{@{casterlevel},5}dh1]] adt'l fire damage. }}

Magic Missile:

/em casts Magic Missile!

Concentration check = [[{1d20+@{concentration}}>?{DC=15+Spell Level or 10+Damage Received|16}]] success.

 [[{(d1*((@{casterlevel2}-1-((@{casterlevel2}-1)%2))/2)+1),d1*5}dh1}]] missiles hit for [[1d4+1]]|[[1d4+1]]|[[1d4+1]]|[[1d4+1]]|[[1d4+1]] damage. May hit multiple creatures; no 2 can be more than 15' apart from each other and all must be within [[100+10*@{casterlevel2}]] ft of the caster. Components: V,S. Casting time: 1 std action. Duration: instant. No save allowed. Caster level check = [[1d20+@{casterlevel2}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Magic Missile!](http://www.dandwiki.com/wiki/SRD:Magic_Missile ).}}  {{School:= Evo (Force)}} {{Level:= Sor/Wiz 1}} {{Cmp’nts:=V,S}} {{Casting Time:=1 std action}} {{Range:= Medium ( [[100+10*@{casterlevel2}]] ft)}} {{Target:= Up to five creatures, no two of which can be more than 15 ft. apart }} {{Duration:= Instantaneous}} {{Saving Throw:= None}} {{Spell Resist.:= Yes}} {{Caster level check: = [[1d20+@{casterlevel2}+@{spellpen}]] vs spell resistance.}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|16}]] }} {{succeedcheck=Success! She casts her spell!}} {{failcheck=She fails :( }}  {{check= [[{(d1*((@{casterlevel2}-1-((@{casterlevel2}-1)%2))/2)+1),d1*5}dh1}]] missiles fly from the caster’s fingers,}} {{checkroll=hitting for [[{{(@{casterlevel2}/2)d1cf0cs2, 0d0}kh1, 1d1cf0cs2}kl1*(1d4+1)]]|[[{{(@{casterlevel2}/2-1)d1cf0cs2, 0d0}kh1, 1d1cf0cs2}kl1*(1d4+1)]]|[[{{(@{casterlevel2}/2-2)d1cf0cs2, 0d0}kh1, 1d1cf0cs2}kl1*(1d4+1)]]|[[{{(@{casterlevel2}/2-3)d1cf0cs2, 0d0}kh1, 1d1cf0cs2}kl1*(1d4+1)]]|[[{{(@{casterlevel2}/2-4)d1cf0cs2, 0d0}kh1, 1d1cf0cs2}kl1*(1d4+1)]] force damage.}} {{notes= The missile strikes unerringly, even if the target is in melee combat or has less than total cover or total concealment. Specific parts of a creature can’t be singled out. Inanimate objects are not damaged by the spell.  If you shoot multiple missiles, you can have them strike a single creature or several creatures. A single missile can strike only one creature. You must designate targets before you check for spell resistance or roll damage.   }}

## Level 2:

Barkskin:

 /em casts Barkskin on  @{target|token_name}

 @{target|token_name}'s skin toughens, granting a [[d1*{floor((@{casterlevel}-3)/3)+2,5}dh1]] enhancement bonus to existing natural armor for the next [[10*@{casterlevel}]] minutes.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Barkskin](http://www.dandwiki.com/wiki/SRD:Barkskin ) on ?{Recipient's name?|@{character_name}}. }} {{check=?{Recipient's name?|@{character_name}}'s skin toughens, }} {{checkroll= granting a [[d1*{floor((@{casterlevel}-3)/3)+2,5}dh1]] enhancement bonus to existing natural armor for the next [[10*@{casterlevel}]] minutes. }}

Bear's Endurance:

/em grants  @{target|token_name} Bear's Endurance!

For the next @{casterlevel} mins,  @{target|token_name} gains greater vitality and stamina, receiving a +4 enh bonus to Constitution with the usual benefits to hit points(these temp hit points go away when spell ends), fortitude saves, constitution checks, etc.

/em grants ?{target|himself} Bear's Endurance!

Transmutation; Lvl 2; Components: V, S, DF; Casting Time: 1 std action; Range: Touch; Target: 1 creature touched; Duration: @{casterlevel2} mins. Saving Throw: Will negates(harmless);  Spell Resistance: Yes

?{target|himself} gains greater vitality and stamina, receiving a +4 enh bonus to Constitution with the usual benefits to hit points(these temp hit points go away when spell ends), fortitude saves, constitution checks, etc.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags= grants ?{target|@{character_name}} [Bear's Endurance](http://www.dandwiki.com/wiki/SRD:Bear%27s_Endurance )!}} {{check=For the next @{casterlevel} mins, ?{target|@{character_name}} gains greater vitality and stamina, }} {{checkroll= receiving a +4 enh bonus to Constitution with the usual benefits to hit points(these temp hit points go away when spell ends), fortitude saves, constitution checks, etc. }}

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags= grants ?{target|@{character_name}} [Bear's Endurance](http://www.dandwiki.com/wiki/SRD:Bear%27s_Endurance )!}}  {{School:= Transmutation}} {{Level:= Clr 2, Drd 2, Rgr 2, Sor/Wiz 2}} {{Cmp’nts:=V, S, DF}} {{Casting Time:=1 std action}} {{Range:= Touch}} {{Target:= 1 creature touched }} {{Duration:=  @{casterlevel2} mins.}} {{Saving Throw:= Will negates(harmless)}} {{Spell Resist.:= Yes}} {{Caster level check: = [[1d20+@{casterlevel2}+@{spellpen}]] vs spell resistance.}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|16}]] }} {{succeedcheck=Success! She casts her spell!}} {{failcheck=She fails :( }} {{check=For the next @{casterlevel2} mins, ?{target|@{character_name}} gains greater vitality and stamina, }} {{checkroll= receiving a +4 enh bonus to Constitution with the usual benefits to hit points(these temp hit points go away when spell ends), fortitude saves, constitution checks, etc. }}

Body of the Sun:

/em casts Body of the Sun and bursts into flame.

Flames extend 5' in all directions illuminating the area. [[(@{casterlevel}/2)d4]] points of fire damage are taken by all around her.

The flames last for @{casterlevel} rnds, DC [[10+2+@{wis-mod}]] reflex save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Body of the Sun]( ) and bursts into flame.}} {{check=Flames extend 5' in all directions illuminating the area. }} {{checkroll=[[(@{casterlevel}/2)d4]] points of fire damage are taken by all around her. }} {{notes=The flames last for @{casterlevel} rnds, DC [[10+2+@{wis-mod}]] reflex save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

Bull's Strength:

/em grants  @{target|token_name} Bull's Strength!

For the next @{casterlevel} mins,  @{target|token_name} is stronger, receiving a +4 enh bonus to Strength with the usual benefits to melee attack rolls, melee damage rolls, and other uses of the Str modifier.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=grants ?{target|@{character_name}} [Bull's Strength](http://www.dandwiki.com/wiki/SRD:Bull%27s_Strength )!}} {{check=For the next @{casterlevel} mins, }} {{checkroll= ?{target|@{character_name}} is stronger, receiving a +4 enh bonus to Strength with the usual benefits to melee attack rolls, melee damage rolls, and other uses of the Str modifier. }}

Owl's Wisdom:

/em grants  @{target|token_name} Owl's Wisdom!

For the next @{casterlevel} mins,  @{target|token_name} becomes wiser, receiving a +4 enh bonus to Wisdom with the usual benefits.  Does not grant additional bonus spells, but wis-based spell casters have their save DC's increase.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=grants ?{target|@{character_name}} [Owl's Wisdom](http://www.dandwiki.com/wiki/SRD:Owl%27s_Wisdom )!}} {{check=For the next @{casterlevel} mins, ?{target|@{character_name}} becomes wiser, receiving a +4 enh bonus to Wisdom with the usual benefits. }} {{checkroll=  Does not grant additional bonus spells, but wis-based spell casters have their save DC's increase. }}

Resist Energy:

 /em casts Resist Energy (?{Energy type to resist? (choose Acid, Cold, Electricity, Fire, or Sonic)|Fire}) on  @{target|token_name}

 @{target|token_name} gains energy resistance 20 (30 at 11th lvl) against ?{Energy type to resist? (choose Acid, Cold, Electricity, Fire, or Sonic)|Fire} for the next [[10*@{casterlevel}]] minutes, reducing incoming ?{Energy type to resist? (choose Acid, Cold, Electricity, Fire, or Sonic)|Fire} damage by 20.  This spell protects equipment as well.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Resist Energy](http://www.dandwiki.com/wiki/SRD:Resist_Energy ) (?{Energy type to resist? (choose Acid, Cold, Electricity, Fire, or Sonic)|Fire}) on ?{Recipient's name|@{character_name}}}} {{check=?{Recipient's name|@{character_name}} gains energy resistance 20 (30 at 11th lvl) against ?{Energy type to resist? (choose Acid, Cold, Electricity, Fire, or Sonic)|Fire} }} {{checkroll= for the next [[10*@{casterlevel}]] minutes, reducing incoming ?{Energy type to resist? (choose Acid, Cold, Electricity, Fire, or Sonic)|Fire} damage by 20.  This spell protects equipment as well. }}

Lesser Restoration:

 /em takes 3 rnds and casts Lesser Restoration on  @{target|token_name}.

 @{target|token_name} is cured of any magical effects reducing one ability score or cured of [[d4]] points of temporary ability damage to one ability score.  It also eliminates any fatigue suffered and improves an exhausted condition to fatigued.  Does not restore permanent ability drain.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=takes 3 rnds and casts [Lesser Restoration](http://www.dandwiki.com/wiki/SRD:Lesser_Restoration ) on ?{target?|@{character_name}}.}} {{check=?{target?|@{character_name}} is cured of any magical effects reducing one ability score or cured of [[d4]] points of temporary ability damage to one ability score. }} {{checkroll= It also eliminates any fatigue suffered and improves an exhausted condition to fatigued.  Does not restore permanent ability drain. }}

Continual Flame

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Continual Flame](http://www.dandwiki.com/wiki/SRD:Continual_Flame) }} {{School:=Evo [Light]}} {{Level:= Clr 3, Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Effect:= Magical, heatless flame}} {{Dur:= Permanent}} {{Save:= None }} {{SR:= No }} {{notes= A flame, equivalent in brightness to a torch, springs forth from an object that you touch. The effect looks like a regular flame, but it creates no heat and doesn’t use oxygen. A *continual flame *can be covered and hidden but not smothered or quenched.

Light spells counter and dispel darkness spells of an equal or lower level.

PHB p.213}}

Darkvision

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Darkvision](http://www.dandwiki.com/wiki/SRD:Darkvision) }} {{School:=Trans}} {{Level:= Rgr 3, Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] hours }} {{Save:= Will negates (harmless; DC: [[@{selected|spelldc2} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless; [[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= The subject gains the ability to see 60 feet even in total darkness. Darkvision is black and white only but otherwise like normal sight. *Darkvision *does not grant one the ability to see in magical darkness.

*Darkvision *can be made permanent with a[ permanency](http://www.dandwiki.com/wiki/SRD:Permanency)* *spell.

PHB p.216}}

Daze Monster

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Daze Monster](http://www.dandwiki.com/wiki/SRD:Daze_Monster) }} {{School:=Enchant (Compulsion) [Mind-Affecting]}} {{Level:= Brd 2, Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Medium ([[100+10*(@{selected|casterlevel})]]ft) }} {{Target:= One living creature of 6 HD or less }} {{Dur:= 1 rnd}} {{Save:= Will Negates

(DC: [[@{selected|spelldc2} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{notes= This enchantment clouds the mind of a living creature with 6 or fewer[ Hit Dice](http://www.dandwiki.com/wiki/SRD:Hit_Dice) so that it takes no actions. Creatures of 7 or more[ HD](http://www.dandwiki.com/wiki/SRD:Hit_Dice) are not affected. A[ dazed](http://www.dandwiki.com/wiki/SRD:Dazed) subject is not[ stunned](http://www.dandwiki.com/wiki/Stunned), so attackers get no special advantage against it. 

PHB p.217}}

Invisibility

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Invisibility]([http://www.dandwiki.com/wiki/SRD:Invisibility_(Spell)](http://www.dandwiki.com/wiki/SRD:Invisibility_(Spell)) ) }} {{School:=Illusion (Glamer)}} {{Level:= Asn 2, Brd 2, Sor/Wiz 2, Trickery 2}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Personal or touch }} {{Target:= You or a creature or object weighing no more than [[100*(@{casterlevel})]] lbs. }} {{Dur:= [[@{selected|casterlevel}]] min (D)}} {{Save:= Will negates (harmless, object; DC: [[@{selected|spelldc2} + @{selected|sf-illusion}]]) }} {{SR:= Yes (harmless, object: [[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{notes= The creature or object touched and carried gear becomes[ invisible](http://www.dandwiki.com/wiki/SRD:Invisible), vanishing from sight, even from darkvision. 

Items dropped or put down become visible; items picked up disappear if tucked into clothing or pouches. Light never becomes[ invisible](http://www.dandwiki.com/wiki/SRD:Invisible), although a source of light can become so. Any part of an item carried that extends more than 10 feet becomes visible.

Does not silence subject. The spell ends if the subject attacks any creature. Actions directed at unattended objects do not break the spell. Causing harm indirectly is not an attack; can open doors, talk, summon monsters and have them attack, cut the ropes holding a rope bridge while enemies are on the bridge, remotely trigger traps, and so forth. Spells such as *bless *that specifically affect allies but not foes are not attacks for this purpose.

See full description for more details.

PHB p.245}}

Knock

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Knock](http://www.dandwiki.com/wiki/SRD:Knock) }} {{School:=Trans}} {{Level:= Sor/Wiz 2}} {{Comp:=V}} {{Cast Time:= 1 std action}} {{Range:= Medium ([[100+10*(@{selected|casterlevel})]]ft) }} {{Target:= One door, box, or chest with an area of up to [[10*@{casterlevel}]] sq ft.}} {{Dur:= Instantaneous; see text }} {{Save:= None }} {{SR:= No }}  {{notes= The *knock* spell opens stuck, barred, locked,[ held](http://www.dandwiki.com/wiki/SRD:Hold_Portal)*,* or[ arcane locked](http://www.dandwiki.com/wiki/SRD:Arcane_Lock) doors. It opens secret doors, as well as locked or trick-opening boxes or chests. It also loosens welds, shackles, or chains (provided they serve to hold closures shut). If used to open an *arcane locked* door, the spell does not remove the *arcane lock* but simply suspends its functioning for 10 minutes. In all other cases, the door does not relock itself or become stuck again on its own. *Knock* does not raise barred gates or similar impediments (such as a portcullis), nor does it affect ropes, vines, and the like. The effect is limited by the area. Each spell can undo as many as two means of preventing egress. 

PHB p.246}}

Melf’s Acid Arrow

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Melf’s Acid Arrow](http://www.dandwiki.com/wiki/SRD:Acid_Arrow) }} {{School:=Conj (Creation) [Acid]}} {{Level:= Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Long ([[400+40*(@{selected|casterlevel})]]ft) }} {{Effect:= One arrow of acid }} {{Dur:= [[1+floor([[{@{selected|casterlevel},18}kl1]]/3)]] rnds}} {{Save:= None }} {{SR:= No }}  {{checkroll= A magical arrow of acid springs from your hand and speeds to its target, hitting touch AC [[d20+@{rangedattackbonus}+?{Addt'l attack bonus?|0}]]. The arrow deals [[2d4]] points of acid damage with no splash damage. For the next [[floor([[{@{selected|casterlevel},18}kl1]]/3)]] rounds, the acid, unless somehow neutralized, deals another 2d4 points of damage per round. }} {{notes= PHB p.253}}

Scorching Ray

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Scorching Ray](http://www.dandwiki.com/wiki/SRD:Scorching_Ray) }} {{School:=Evo [Fire]}} {{Level:= Sor/Wiz 2}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One or more rays }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{checkroll= You blast your enemies with [[1+[[{[[floor((@{selected|casterlevel}-3)/4)]],2}kl1]] ]] fiery rays. }} {{notes= The rays may be fired at the same or different targets, but all bolts must be aimed at targets within 30 feet of each other and fired simultaneously.  

PHB p.274}}

&{template:DnD35Attack} {{pcflag=true}} {{attack1=Ray1 hits touch AC [[d20+@{rangedattackbonus} +?{Addt'l attack bonus?|0}]]}} {{critconfirm1=Crit!:[[d20+@{rangedattackbonus} +?{Addt'l attack bonus?|0}]]}} {{fumbleroll=Fumble:[[d20]]}} {{damage1=for [[4d6+?{Addt'l damage bonus?|0}]] fire damage.}} {{critdmg1=+[[4d6+?{Addt'l damage bonus?|0}]] adt'l fire damage.}} {{fullattackflag=[[0d1]]}} {{attack2=Ray2 hits touch AC [[d20+@{rangedattackbonus}+?{Addt'l attack bonus?|0}]] }} {{critconfirm2=Crit!:[[d20+@{rangedattackbonus} +?{Addt'l attack bonus?|0}]] }} {{damage2=for [[4d6+?{Addt'l damage bonus?|0}]] fire damage. }} {{critdmg2=+[[4d6+?{Addt'l damage bonus?|0}]] adt'l fire damage. }} {{attack3=Ray3 hits touch AC [[d20+@{rangedattackbonus}+?{Addt'l attack bonus?|0}]] }} {{critconfirm3=Crit!:[[d20+@{rangedattackbonus} +?{Addt'l attack bonus?|0}]] }} {{damage3=for [[4d6+?{Addt'l damage bonus?|0}]] fire damage. }} {{critdmg3=+[[4d6+?{Addt'l damage bonus?|0}]] adt'l fire damage. }}

See Invisibility

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [See Invisibility](http://www.dandwiki.com/wiki/SRD:See_Invisibility) }} {{School:=Div}} {{Level:= Brd 3, Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[10*@{casterlevel}]] minutes (D)}} {{checkroll=You can see any objects or beings that are[ invisible](http://www.dandwiki.com/wiki/SRD:Invisible) within your range of vision, as well as any that are ethereal, as if they were normally visible. Such creatures are visible to you as translucent shapes, allowing you easily to discern the difference between visible, invisible, and ethereal creatures. }} {{notes=The spell does not reveal the method used to obtain invisibility. It does not reveal illusions or enable you to see through opaque objects. It does not reveal creatures who are simply hiding, concealed, or otherwise hard to see.

*See invisibility *can be made permanent with a[ permanency](http://www.dandwiki.com/wiki/SRD:Permanency)* *spell.

PHB p.275}}

Spider Climb

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Spider Climb](http://www.dandwiki.com/wiki/SRD:Spider_Climb) }} {{School:=Trans}} {{Level:= Asn 2, Druid 2, Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[10*@{selected|casterlevel}]] minutes }} {{Save:= Will Negates (harmless; DC: [[@{selected|spelldc2} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless; [[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= The subject can climb and travel on vertical surfaces or even traverse ceilings as well as a spider does. The affected creature must have its hands free to climb in this manner. The subject gains a climb speed of 20 feet; furthermore, it need not make[ Climb](http://www.dandwiki.com/wiki/SRD:Climb_Skill) checks to traverse a vertical or horizontal surface (even upside down). A *spider climbing *creature retains its[ Dexterity](http://www.dandwiki.com/wiki/SRD:Dexterity) bonus to[ Armor Class](http://www.dandwiki.com/wiki/SRD:Armor_Class) (if any) while climbing, and opponents get no special bonus to their attacks against it. It cannot, however, use the run action while climbing. }} {{notes= PHB p.283}}

Summon Monster II

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Summon Monster II](http://www.dandwiki.com/wiki/SRD:Summon_Monster_II) }} {{School:=Conj (Summ) [see text]}} {{Level:= Brd 2, Clr 2, Sor/Wiz 2}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One or more summoned creatures, no two of which can be more than 30 ft apart }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell functions like[ ](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I)[Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) *, *except that you can summon one creature from the 2nd-level list or 1d3 creatures of the same kind from the 1st-level list. 

See [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) for more details.

PHB p.285}}

Web

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Web](http://www.dandwiki.com/wiki/SRD:Web) }} {{School:=Conj (Creation)}} {{Level:= Sor/Wiz 2}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Medium ([[100+10*(@{selected|casterlevel})]]ft) }} {{Effect:= Webs in a 20-ft-radius spread }} {{Dur:= [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= Reflex negates*

(DC: [[@{selected|spelldc2} + @{selected|sf-conjuration}]]) }} {{SR:= No }}  {{checkroll= *Web *creates a mass of strong, sticky strands trapping those caught in them. These masses must be anchored to two or more solid and diametrically opposed points or the web collapses and disappears.

All in the effect’s area when the spell is cast must make a[ Reflex](http://www.dandwiki.com/wiki/SRD:Saving_Throw) save. If save succeeds, subject is[ entangled](http://www.dandwiki.com/wiki/SRD:Entangled), but not prevented from moving (see below). If the save fails, subject is[ entangled](http://www.dandwiki.com/wiki/SRD:Entangled) and can’t move from its space, but can break loose by spending 1[ ](http://www.dandwiki.com/wiki/SRD:Round)rnd and making a[ DC](http://www.dandwiki.com/wiki/SRD:DC) 20[ Strength](http://www.dandwiki.com/wiki/SRD:Strength) or a[ DC](http://www.dandwiki.com/wiki/SRD:DC) 25[ Escape Artist](http://www.dandwiki.com/wiki/SRD:Escape_Artist_Skill) check. Once loose, a creature moves through the *web *very slowly; each[ ](http://www.dandwiki.com/wiki/SRD:Round)rnd devoted to moving allows one to move 5’ for each full 5 points by which a new[ Strength check](http://www.dandwiki.com/wiki/SRD:Strength_Check) or[ Escape Artist](http://www.dandwiki.com/wiki/SRD:Escape_Artist_Skill) check exceeds 10.}} {{notes=At least 5’ of web provides[ cover](http://www.dandwiki.com/wiki/SRD:Cover); 20’ of web provides total[ cover](http://www.dandwiki.com/wiki/SRD:Cover).

The strands are flammable.  All within flaming webs take 2d4 points of fire damage.

See full description for more details.

PHB p.301}}

Pseudo Template(do not use as is) 

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Alarm](http://www.dandwiki.com/wiki/SRD:Alarm) }} {{School:=Evo}} {{Level:= Brd 3, Rgr 3, Sor/Wiz 3}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= something}} {{Area:= 20-ft-radius emanation centered on a point in space }} {{Dur:= [[2*@{selected|casterlevel}]] hours (D)}} {{Save:= Reflex half

(DC: [[@{selected|spelldc2} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{notes= Alarm 

See full description for more details.

PHB p.197}}

## Level 3:

Call Lightning:

/em Calls Lightning down from the skies.

For the next [[@{casterlevel}]] minutes, she can take a standard action to call one 5' wide, 30' long vertical bolt of lightning that deals [[3d6]] points of electrical damage to a location within [[100+@{casterlevel}*10]]'.  She can call [[{@{casterlevel},10}dh1]] bolts total.  If outdoors and in a stormy area (rain, clouds and wind, hot and cloudy, even a large+ air elemental's whirlwind), the bolt deals [[3d10]] points of electrical damage.  Does not function underwater.  DC [[10+@{wis-mod}+3]] reflex save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=[calls Lightning](http://www.dandwiki.com/wiki/SRD:Call_Lightning ) down from the skies.}} {{check=For the next [[@{casterlevel}]] minutes, @{character_name} can take a standard action to call one 5' wide, 30' long vertical bolt of lightning that deals [[3d6]] points of electrical damage to a location within [[100+@{casterlevel}*10]]'. }} {{checkroll= She can call [[{@{casterlevel},10}dh1]] bolts total.}} {{notes=If outdoors and in a stormy area (rain, clouds and wind, hot and cloudy, even large+ air elemental's whirlwind), the bolt deals [[3d10]] points of electrical damage.  Does not function underwater.  DC [[10+@{wis-mod}+3]] reflex save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

Cure Moderate Wounds:

/em casts Cure Moderate Wounds, channeling [[2d8+{@{casterlevel},10}dh1]] points of positive energy in to  @{target|token_name}.

Undead creatures take damage instead of gaining healing; DC [[10+3+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Moderate Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Moderate_Wounds ).}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|17}]] }} {{succeedcheck=Success! She casts her spell!}} {{failcheck=She fails :( }}  {{check=@{target|token_name} receives }} {{checkroll= [[2d8+{@{casterlevel},10}dh1]] heath. }} {{notes=Undead creatures take damage instead of gaining healing; DC [[10+3+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Moderate Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Moderate_Wounds ).}} {{School:= Conj(Healing)}} {{Level:= Blg 2, Brd 2, Clr 2, Drd 3, Healing 2, Pal 3, Rgr 3 }} {{Cmp’nts:=V,S}} {{Casting Time:=1 std action}} {{Range:= Touch}} {{Target:= Creature touched}} {{Duration:= Instantaneous}} {{Saving Throw:= Will Save(half) when used vs Undead}} {{Spell Resist.:= Undead can use spell resistance}} {{Caster level check: = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|17}]] }} {{succeedcheck=Success! She casts her spell!}} {{failcheck=She fails :( }}  {{check=@{target|token_name} receives }} {{checkroll= [[2d8+{@{casterlevel},10}dh1]] heath. }} {{notes=Undead creatures take damage instead of gaining healing. }}

Dispel Magic:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Dispel Magic](http://www.dandwiki.com/wiki/SRD:Dispel_Magic) }} {{School:=Abj}} {{Level:= Brd 3, Clr 3, Drd 4, Magic 3, Pal 3, Sor/Wiz 3 }} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Medium ([[100+10*(@{selected|casterlevel})]]ft) }} {{Target, or Area:= One spellcaster, creature, or object; or 20-ft.-radius burst. }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= No }}  {{checkroll= Ends or suppresses ongoing spells on a creature or object or in an area, or counters another caster’s spell. }} {{notes= Targeted Dispel: One object, creature, or spell. Dispel check ([[1d20 + {@{casterlevel},10}kl1]] vs DC of 11 +caster level against the spell(s).

Area Dispel: Affects a 20-foot radius.

Counterspell: Target a spellcaster and cast as a counterspell. Must make a dispel check to counter.

See full description for more details.

PHB p.223}}

Fireball:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Fireball](http://www.dandwiki.com/wiki/SRD:Fireball) }} {{School:=Evo [Fire]}} {{Level:= Sor/Wiz 3}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Long ([[400+40*(@{selected|casterlevel})]]ft) }} {{Area:= 20-ft radius spread }} {{Dur:= Instantaneous}} {{Save:=  Reflex half (DC: [[@{selected|spelldc3} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{checkroll= A glowing, pea-sized bead streaks from your finger and blossoms into the fireball.  If the bead is sent through a narrow passage, such as an arrow slit, you must "hit" the opening with a ranged touch attack, or the bead strikes the barrier and detonates early. }} {{notes= Fireball sets fire to combustibles and damages objects. It can melt metals with low melting points. If damage caused to a barrier shatters or breaks through, the fireball may continue; otherwise it stops at the barrier.

See full description for more details.

PHB p.231}}

&{template:DnD35Attack} {{pcflag=true}} {{attack1=An explosion of flame detonates with a low roar and deals }} {{damage1=[[([[{@{selected|casterlevel},10}kl1]])d6]] points of fire damage to every creature within the area.}} {{fullattackflag=[[d1]]}} {{attack2=Unattended objects also take damage. The explosion creates almost no pressure. }}

Flame Arrow:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Flame Arrow](http://www.dandwiki.com/wiki/SRD:Flame_Arrow) }} {{School:=Trans [Fire]}} {{Level:= Sor/Wiz 3}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Fifty projectiles, all of which must be in contact with each other at the time of casting }} {{Dur:= [[10 * @{casterlevel}]] min}} {{Save:=  None }} {{SR:= No }}  {{checkroll=You turn ammunition (such as arrows, bolts, shuriken, and stones) into fiery projectiles. Each piece of ammunition deals an extra 1d6 points of fire damage to any target it hits. A flaming projectile can easily ignite a flammable object or structure, but it won’t ignite a creature it strikes. }} {{notes= Material Component: A drop of oil and a small piece of flint. 

PHB p.231}}

Fly:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Fly](http://www.dandwiki.com/wiki/SRD:Fly) }} {{School:=Trans}} {{Level:= Sor/Wiz 3, Travel 3}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched}} {{Dur:= [[@{selected|casterlevel}]] mins}} {{Save:= Will negates

(Harmless, DC: [[@{selected|spelldc2} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (Harmless, [[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{checkroll= The subject can fly at 60 feet (40 feet if wearing medium/heavy armor, or carrying medium/heavy load). Ascend at half speed, descend at double speed, maneuverability is good. Using a fly spell requires only as much concentration as walking, so the subject can attack or cast spells normally. The subject of a fly spell can charge but not run, and cannot carry aloft more weight than its maximum load, plus any armor it wears. }} {{notes=If expires while the subject is still aloft, the magic fails slowly; subject floats downward 60 ft per rnd for [[1d6]] rnds. If it reaches the ground in that amount of time, it lands safely. If not, it falls the rest of the distance, taking 1d6 points of damage per 10 feet of fall.

See full description for more details.

PHB p.232}}

Lightning Bolt:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Lightning Bolt](http://www.dandwiki.com/wiki/SRD:Lightning_Bolt) }} {{School:=Evo [Electricity]}} {{Level:= Sor/Wiz 3}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= 120 ft }} {{Area:= 120-ft line }} {{Dur:= Instantaneous}} {{Save:=  Reflex half

(DC: [[@{selected|spelldc3} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{checkroll= You release a powerful stroke of electrical energy that deals damage to each creature within its area. The bolt begins at your fingertips.  }} {{notes= Lightning bolt sets fire to combustibles and damages objects in its path. It can melt metals with a low melting point. If the damage caused to an interposing barrier shatters or breaks through it, the bolt may continue beyond the barrier if the spell’s range permits; otherwise, it stops at the barrier just as any other spell effect does.

PHB p.248}}

&{template:DnD35Attack} {{pcflag=true}} {{attack1=A bolt of electricity deals }} {{damage1=[[([[{@{selected|casterlevel},10}kl1]])d6]] points of electrical damage to every creature within the area.}} {{fullattackflag=[[d1]]}}

Major Image

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Major Image](http://www.dandwiki.com/wiki/SRD:Major_Image) }} {{School:=Ill (Figment)}} {{Level:= Brd 3, Sor/Wiz 3}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Long ([[400+40*(@{selected|casterlevel})]]ft) }} {{Effect:= Visual figment that cannot extend beyond [[4+@{selected|casterlevel}]] 10-ft. cubes (S)  }} {{Dur:= Concentration + 3 rounds }} {{Save:= Will disbelief (if interacted with; DC: [[@{selected|spelldc3} + @{selected|sf-illusion}]]) }} {{SR:= No }}  {{checkroll= This spell creates the visual illusion of an object, creature, or force, as visualized by you. While concentrating, you can move the image within the range. Sound, smell, and thermal illusions are included in the spell effect. }} {{notes=The image disappears when struck by an opponent unless you cause the illusion to react appropriately.

PHB p.252}}

Protection from Energy:

 /em casts Protection from Energy (?{energy type?(acid, cold, electricity, fire, sonic)|Fire}) on  @{target|token_name}.

 @{target|token_name} is immune to ?{energy type?(acid, cold, electricity, fire, sonic)|Fire} damage for the next [[10*@{casterlevel}]] mins or until [[{(12*@{casterlevel}),120}dh1]] points of ?{energy type?(acid, cold, electricity, fire, sonic)|Fire} damage are absorbed. (If warded with both Prot. from Energy and Resist Energy, this spell is impacted first; once exhausted, then the Resist spell comes into play.)

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Protection from Energy](http://www.dandwiki.com/wiki/SRD:Protection_from_Energy ) (?{energy type?(acid, cold, electricity, fire, sonic)|Fire}) on ?{target|@{character_name}}.}} {{check=?{target|@{character_name}} is immune to ?{energy type?(acid, cold, electricity, fire, sonic)|Fire} damage }} {{checkroll= for the next [[10*@{casterlevel}]] mins or until [[{(12*@{casterlevel}),120}dh1]] points of ?{energy type?(acid, cold, electricity, fire, sonic)|Fire} damage are absorbed. }} {{notes=If warded with both Prot. from Energy and Resist Energy, this spell is impacted first; once exhausted, then the Resist spell comes into play. }}

Stone Shape:

 /em casts Stone Shape.

Stone or stone object touched, up to [[10+@{casterlevel}]] cu. ft. of stone, is shaped into any form she desires.  Fine details are not possible; 30% chance any moving parts don't work.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Stone Shape](http://www.dandwiki.com/wiki/SRD:Stone_Shape ).}} {{check=Stone or stone object touched, up to [[10+@{casterlevel}]] cu. ft. of stone is shaped into any form she desires. }} {{checkroll= Fine details are not possible; 30% chance any moving parts don't work. }}

Summon Monster III:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Summon Monster III](http://www.dandwiki.com/wiki/SRD:Summon_Monster_III) }} {{School:=Conj (Summ) [see text]}} {{Level:= Brd 3, Clr 3, Sor/Wiz 3}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One or more summoned creatures, no two of which can be more than 30 ft apart }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell functions like [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) , except that you can summon one creature from the 3rd-level list, 1d3 creatures of the same kind from the 2nd-level list, or 1d4+1 creatures of the same kind from the 1st-level list.

See [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) for more details.

PHB p.285}}

Vampiric Touch (from Justin L.):

&{template:DnD35StdRoll} {{spellflag=true}} {{name= @{character_name} casts Vampiric Touch }} {{School:=Necromancy}} {{Level: =Duskblade 3}} {{Comp'nts:=V, S }} {{Casting Time:= 1 std action}} {{Range:=Touch}} {{Target:= living creature}} {{Duration:=Instant (1 hour (See text)}} {{Saving Throw:= None }} {{Spell Resist:= Yes }} {{ Caster level check: = [[1d20+@{casterlevel2}+@{spellpen}]] vs SR.}} {{compcheck= Conc:[[{1d20+@{concentration} }>?{Concentration DC=15+Spell Level or 10+Damage Received|18}]]: }} {{succeedcheck=**Streams of dark energy wreath his hand.**}} {{failcheck=Spell fails, AoO provoked! }} {{notes=Your touch deals 1d6 per 2 caster levels ( [[5d6]] ) damage. You gain temporary hit points equal to the damage you deal. However, you can’t gain more than the subject’s current hit points +10, which is enough to kill the subject. The temporary hit points disappear 1 hour later.}}

Pseudo Template(do not use as is) 

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Alarm](http://www.dandwiki.com/wiki/SRD:Alarm) }} {{School:=Evo}} {{Level:= Brd 3, Rgr 3, Sor/Wiz 3}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= something}} {{Area:= 20-ft-radius emanation centered on a point in space }} {{Dur:= [[2*@{selected|casterlevel}]] hours (D)}} {{Save:= Reflex half

(DC: [[@{selected|spelldc3} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{notes= Alarm 

See full description for more details.

PHB p.197}}

## Level 4:

Cure Serious Wounds:

/em casts Cure Serious Wounds, channeling [[3d8+{@{casterlevel},15}dh1]]  points of positive energy in to  @{target|token_name}.

Undead creatures take damage instead of gaining healing; DC [[10+4+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Serious Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Serious_Wounds ).}} {{check=@{target|token_name} receives }} {{checkroll= [[3d8+{@{casterlevel},15}dh1]] heath. }} {{notes=Undead creatures take damage instead of gaining healing; DC [[10+4+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

Flame Strike:

/em smites her foes with a Flame Strike!

A 10' r column of divine flame roars downwards at a location within [[100+@{casterlevel}*10]] feet of her.  [[(@{casterlevel})d6]] points of damage are dealt to all within the flames.  Reflex save, DC=[[10+4+@{wis-mod}]] for half damage; half of damage is flame, half is divine power and not subject to resistance to fire-based attacks. (caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance for fire half).

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=smites her foes with a [Flame Strike](http://www.dandwiki.com/wiki/SRD:Flame_Strike )!}} {{check=A 10' r column of divine flame roars downwards at a location within [[100+@{casterlevel}*10]] feet of @{character_name}. }} {{checkroll=  [[(@{casterlevel})d6]] points of damage are dealt to all within the flames. }} {{notes=Reflex save, DC=[[10+4+@{wis-mod}]] for half damage; half of damage is flame, half is divine power and not subject to resistance to fire-based attacks. (caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance for fire half).}}

Hold Monster:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Hold Monster](http://www.dandwiki.com/wiki/SRD:Hold_Monster) }} {{School:=Ench (Compulsion) [Mind-Affecting] }} {{Level:= Brd 4, Law 6, Sor/Wiz 5}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:=  Medium ([[100+10*(@{selected|casterlevel})]]ft) }} {{Effect:= One living creature }} {{Dur:= [[@{casterlevel}]] rnds (D); see text}} {{Save:= Will negates (see text; DC: [[@{selected|spelldc5} + @{selected|sf-enchantment}]])  }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR)  }} {{checkroll= The subject becomes paralyzed and freezes in place. It is aware and breathes normally but cannot take any actions, even speech. Each round on its turn, the subject may attempt a new saving throw to end the effect. (This is a full-round action that does not provoke attacks of opportunity.)}} {{notes= A winged creature who is paralyzed cannot flap its wings and falls. A swimmer can’t swim and may drown.

PHB p.270}}

Last Breath: (Complete Divine version)

/em casts Last Breath on @{target|token_name}.

@{target|token_name} is returned to life at 0 hit points (50% chance spells are lost).

/w gm @{selected|token_name} takes [[@{target|hitdie}d4]] points of damage.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Last Breath]( ) on ?{target|@{character_name}}. }} {{check=?{target|@{character_name}}  is returned to life at 0 hit points  }} {{checkroll= (50% chance spells are lost).}}

/w gm @{character_name} takes [[?{target HD|@{target|HD}}d4]] points of damage.

Mordenkainen’s Faithful Hound:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Mordenkainen's Faithful Hound](http://www.dandwiki.com/wiki/SRD:Mage%27s_Faithful_Hound) }} {{School:=Conj (Creation) }} {{Level:= Sor/Wiz 5}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Phantom Watchdog }} {{Dur:= [[@{casterlevel}]] hours or until discharged, then [[@{casterlevel}]] rnds.}} {{Save:= None }} {{SR:= No }} {{checkroll= Conjures up a phantom watchdog that is invisible to everyone but yourself. It guards the area where conjured (does not move). It starts barking loudly if any Small or larger creature approaches within 30 feet of it.  It sees invisible and ethereal creatures. If intruder approaches within 5 feet, it bites (+10 attack bonus, 2d6+3 points of piercing damage) once per round. The dog also gets the bonuses appropriate to an invisible creature. Its bite is the equivalent of a magic weapon for the purpose of damage reduction. The hound cannot be attacked, only dispelled.  }} {{notes= The spell lasts for @{casterlevel} hours, but once the hound begins barking, it lasts only @{casterlevel} rnds.. If you are ever more than 100 feet distant from the hound, the spell ends.

PHB p.255}}

Cure Critical Wounds:

/em casts Cure Critical Wounds, channeling [[4d8+{@{casterlevel},20}dh1]] points of positive energy in to @{target|token_name}.

Undead creatures take damage instead of gaining healing; DC [[10+5+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Cure Critical Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Critical_Wounds ).}} {{check=@{target|token_name} receives }} {{checkroll= [[4d8+{@{casterlevel},20}dh1]] heath. }} {{notes=Undead creatures take damage instead of gaining healing; DC [[10+5+@{wis-mod}]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

Deathward:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Deathward](http://www.dandwiki.com/wiki/SRD:Death_Ward ).}}{{notes=For the next @{casterlevel} minutes, @{target|token_name} is immune to all death spells, magical death effects, energy drain, and any negative energy effects. }}

Rejuvenation Cocoon:

/em cast Rejuvenation Cocoon on @{target|token_name}.

Golden-green tendrils coalesce to form a cocoon around @{target|token_name}, encasing him/her in a somewhat flexible (from the inside) cocoon a few inches from his/her body.  @{target|token_name} cannot leave the square he/she is in, but can get to his/her feet, draw weapons, get something from his/her backpack, cast a spell, etc.

The cocoon lasts for 2 rounds.  It has a hardness of 10 and [[@{casterlevel}*10]] hit points.  After it forms, it heals @{target|token_name} of [[@{casterlevel}d10]] points of damage and purges him/her of diseases and poisons.  At the end of the second round, it dissipates, leaving him/her able to move and act freely.

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Rejuvenation Cocoon]( ).}} {{check=Golden-green tendrils coalesce to form a cocoon around ?{target?|@{character_name}}, }} {{checkroll=encasing ?{him/her?|him} in a somewhat flexible (from the inside) cocoon a few inches from ?{his/her?|his} body.  ?{target?|@{character_name}} cannot leave the square ?{he/she?|he} is in, but can get to ?{his/her?|his} feet, draw weapons, get something from ?{his/her?|his} backpack, cast a spell, etc. }} {{notes=The cocoon lasts for 2 rounds.  It has a hardness of 10 and [[@{casterlevel}*10]] hit points.  After it forms, it heals ?{target?|@{character_name}} of [[@{casterlevel}d10]] points of damage and purges ?{him/her?|him} of diseases and poisons.  At the end of the second round, it dissipates, leaving ?{him/her?|him} able to move and act freely. }}

Summon Monster V:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Summon Monster V](http://www.dandwiki.com/wiki/SRD:Summon_Monster_V) }} {{School:=Conj (Summ) [see text]}} {{Level:= Brd 3, Clr 3, Sor/Wiz 3}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One or more summoned creatures, no two of which can be more than 30 ft apart }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell functions like [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) , except that you can summon one creature from the 5th-level list, 1d3 creatures of the same kind from the 4th-level list, or 1d4+1 creatures of the same kind from a lower-level list.

See [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) for more details.

PHB p.285}}

Telekinesis:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Telekinesis](http://www.dandwiki.com/wiki/SRD:Telekinesis) }} {{School:=Trans }} {{Level:= Sor/Wiz 5}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Long ([[400+40*(@{selected|casterlevel})]]ft) }} {{Targets:= See text }} {{Dur:= Concentration (up to @{selected|casterlevel} rnds or instantaneous; see text}} {{Save:= Will negates (object; DC: [[@{selected|spelldc5} + @{selected|sf-transmutation}]]) or None  }} {{SR:= Yes (object; [[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR); see text  }} {{checkroll= You move objects or creatures by concentrating on them. Depending on the version selected, the spell can provide a gentle, sustained force, perform a variety of combat maneuvers, or exert a single short, violent thrust.. }} {{notes= See spell description for more information.

PHB p.292}}

Teleport:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Teleport](http://www.dandwiki.com/wiki/SRD:Teleport) }} {{School:=Conj (Teleportation) }} {{Level:= Sor/Wiz 5, Travel 5}} {{Comp:=V}} {{Cast Time:= 1 std action}} {{Range:= Personal and Touch }} {{Target:= You and touched objects or other touched willing creatures }} {{Dur:= Instantaneous}} {{Save:= None and Will negates (object; DC: [[@{selected|spelldc4} + @{selected|sf-conjuration}]])  }} {{SR:= No and Yes (object; [[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR)  }} {{checkroll= This spell instantly transports you to a location, up to [[100*@{selected|casterlevel} ]] miles away. Interplanar travel is not possible. You can bring along objects under max load as well as [[floor(@{selected|casterlevel}/3)]] additional willing  Medium or smaller creatures (loaded up to max load) or equivalent. All creatures transported must be in contact. Objects held or in use (attended) by another person receive saving throws and spell resistance.}} {{notes= Must have clear idea of the location and layout of destination. The clearer your mental image, the more likely the teleportation works. Consult the Teleport table; roll =[[d100]].

See spell description for more information.

PHB p.292}}

Pseudo Template(do not use as is) 

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Alarm](http://www.dandwiki.com/wiki/SRD:Alarm) }} {{School:=Evo}} {{Level:= Brd 4, Rgr 4, Sor/Wiz 4}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= something}} {{Area:= 20-ft-radius emanation centered on a point in space }} {{Dur:= [[2*@{selected|casterlevel}]] hours (D)}} {{Save:= Reflex half

(DC: [[@{selected|spelldc4} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }}  {{notes= Alarm 

See full description for more details.

PHB p.197}}

## Other:

Bard Song, Inspire Courage:

/em Inspires Courage in all allies within earshot!

As long as the bard sings and for 5 rounds after, affected allies receive a +[[ceil((@{casterlevel}-7)/6)+1]] morale bonus on saving throws vs charm and fear attacks as well as a +[[ceil((@{casterlevel}-7)/6)+1]] morale bonus on attack and weapon damage rolls.  (mind-affecting ability)

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=[Inspires Courage](http://www.dandwiki.com/wiki/SRD:Bard#Inspire_Courage ) in all allies within earshot!}}{{notes=As long as the bard sings and for 5 rounds after, affected allies receive a +[[ceil((@{casterlevel}-7)/6)+1]] morale bonus on saving throws vs charm and fear attacks as well as a +[[ceil((@{casterlevel}-7)/6)+1]] morale bonus on attack and weapon damage rolls.  (mind-affecting ability) }}

Cleric, Turn Undead

/me holds forth a glowing holy symbol and turns or rebukes a total of [[2d6 + @{casterlevel} + @{cha-mod}]] hit die of creatures up to [[ @{casterlevel} + {{(ceil((1d20 +@{cha-mod})/3) -4) , 0d0+4}kl1,0d0-4}kh1 ]] hit die each. All affected creatures with [[floor(@{casterlevel}/2)]] hit die or less explode!

&{template:DnD35StdRoll} {{name=@{character_name} }} {{initflag=true}} {{subtags=holds up a [glowing holy symbol and channels Holy energy](http://www.dandwiki.com/wiki/Turn_undead).}} {{ Up to [[ 2d6 + @{casterlevel} +@{cha-mod}]] hit die of undead of up to [[ @{casterlevel} + {{(ceil((1d20 +@{cha-mod})/3) -4) , 0d0+4}kl1,0d0-4}kh1 ]] hit die each within 60 feet can be turned. }}  {{notes= Turned undead will flee for 10 rnds; if they cannot flee, they will cower (+2 to attacks on them).  If the cleric approaches within 10ft, the effect will break; others may approach, damage will not break the effect.  Affected undead with [[floor(@{casterlevel}/2)]] hit die or less are destroyed instead of turned.}}

-------------------------

# My All-in-one macros:

### Saving Throws:

&{template:DnD35StdRoll}{{name=@{selected|character_name} }} {{saveflag=true}} ?{Which resistance?|Fortitude ,{{subtags=braces against the attack&#125;&#125; {{check=Fortitude check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|fortitude}]] ]]&#125;&#125; {{notes=@{selected|fortitudenote} &#125;&#125;|Reflex ,{{subtags=tries to dodge&#125;&#125; {{check=Reflex check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|reflex}]] ]]&#125;&#125; {{notes=@{selected|reflexnote} &#125;&#125;|Will ,{{subtags=tries to resist&#125;&#125; {{check=Will check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|will}]] ]]&#125;&#125; {{notes=@{selected|willnote} &#125;&#125; }

### Ability stat checks:

((old; does not use notes fields)):   

&{template:DnD35StdRoll} {{abilityflag=true}} {{name=@{selected|character_name} }} {{check=}} {{checkroll= ?{Which Stat?|Strength,Strength check: [[1d20 + [[@{selected|str-mod}]] ]] |Dexterity,Dexterity check: [[1d20 + [[@{selected|dex-mod}]] ]] |Constitution,Constitution check: [[1d20 + [[@{selected|con-mod}]] ]] |Intelligence,Intelligence check: [[1d20 + [[@{selected|int-mod}]] ]] |Wisdom,Wisdom check: [[1d20 + [[@{selected|wis-mod}]] ]] |Charisma,Charisma check: [[1d20 + [[@{selected|cha-mod}]] ]] } }}

New; uses notes fields:

&{template:DnD35StdRoll}{{name=@{selected|character_name} }} {{abilityflag=true}} ?{Which stat?|Strength ,{{check=Strength check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|str-mod}]] ]]&#125;&#125; {{notes=@{selected|strnote} &#125;&#125;|Dexterity ,{{check=Dexterity check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|dex-mod}]] ]]&#125;&#125; {{notes=@{selected|dexnote} &#125;&#125;|Constitution ,{{check=Constitution check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|con-mod}]] ]]&#125;&#125; {{notes=@{selected|connote} &#125;&#125;|Intelligence ,{{check=Intelligence check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|int-mod}]] ]]&#125;&#125; {{notes=@{selected|intnote} &#125;&#125;|Wisdom ,{{check=Wisdom check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|wis-mod}]] ]]&#125;&#125; {{notes=@{selected|wisnote} &#125;&#125;|Charisma ,{{check=Charisma check:&#125;&#125; {{checkroll= [[1d20 + [[@{selected|cha-mod}]] ]]&#125;&#125; {{notes=@{selected|chanote} &#125;&#125; }

### Knowledge checks:

((old; does not include notes fields)):

/w gm &{template:DnD35StdRoll} {{checkroll= ?{Which skill?|Knowledge (Arcana), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Arcana)* check: [[1d20 + [[@{knowarcana}]] ]] |Knowledge (Engineering), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Engineering)* check: [[1d20 + [[@{knowengineer}]] ]] |Knowledge (Dungeoneering), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Dungeoneering)* check: [[1d20 + [[@{knowdungeon}]]; ]] |Knowledge (Geography), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Geography)* check: [[1d20 + [[@{knowgeography}]] ]] |Knowledge (History), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (History)* check: [[1d20 + [[@{knowhistory}]] ]] |Knowledge (Local), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Local)* check: [[1d20 + [[@{knowlocal}]] ]] |Knowledge (Nature), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Nature)* check: [[1d20 + [[@{knownature}]] ]] |Knowledge (Nobility), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Nobility)* check: [[1d20 + [[@{knownobility}]] ]] |Knowledge (Religion), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Religion)* check: [[1d20 + [[@{knowreligion}]] ]] |Knowledge (The Planes), [Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (The Planes)* check: [[1d20 + [[@{knowplanes}]] ]] } }} {{skillflag=true}} {{name=@{selected|character_name}}} {{check= }}

New; includes notes fields:

/w gm &{template:DnD35StdRoll} {{skillflag=true}} {{name=@{selected|character_name}}} ?{Which skill?|Knowledge (Arcana), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Arcana)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowarcana}]] ]]&#125;&#125; {{notes=@{selected|knowarcananote} &#125;&#125;|Knowledge (Engineering), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Engineering)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowengineer}]] ]]&#125;&#125; {{notes=@{selected|knowengineernote} &#125;&#125; |Knowledge (Dungeoneering), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Dungeoneering)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowdungeon}]]; ]]&#125;&#125; {{notes=@{selected|knowdungeonnote} &#125;&#125;|Knowledge (Geography), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Geography)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowgeography}]] ]]&#125;&#125; {{notes=@{selected|knowgeographynote} &#125;&#125;|Knowledge (History), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (History)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowhistory}]] ]]&#125;&#125; {{notes=@{selected|knowhistorynote} &#125;&#125;|Knowledge (Local), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Local)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowlocal}]] ]]&#125;&#125; {{notes=@{selected|knowlocalnote} &#125;&#125;|Knowledge (Nature), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Nature)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knownature}]] ]]&#125;&#125; {{notes=@{selected|knownaturenote} &#125;&#125;|Knowledge (Nobility), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Nobility)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knownobility}]] ]]&#125;&#125; {{notes=@{selected|knownobilitynote} &#125;&#125;|Knowledge (Religion), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (Religion)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowreligion}]] ]]&#125;&#125; {{notes=@{selected|knowreligionnote} &#125;&#125;|Knowledge (The Planes), {{check=[Knowledge](http://www.dandwiki.com/wiki/SRD:Knowledge_Skill ) (The Planes)* check:&#125;&#125; {{checkroll= [[1d20 + [[@{knowplanes}]] ]]&#125;&#125; {{notes=@{selected|knowplanesnote} &#125;&#125; }

### Other skill checks:

((old; does not include notes fields)):

?{Which skill?|Appraise,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Appraise](http://www.dandwiki.com/wiki/SRD:Appraise_Skill ) check: [[1d20 + [[@{appraise}]] ]] &#125;&#125; |Balance,&{template:DnD35StdRoll&#125; {{checkroll=[Balance](http://www.dandwiki.com/wiki/SRD:Balance_Skill ) check: [[1d20 + [[@{balance}]] ]] &#125;&#125; |Bluff,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Bluff](http://www.dandwiki.com/wiki/SRD:Bluff_Skill ) check: [[1d20 + [[@{bluff}]] ]] &#125;&#125; |Climb,&{template:DnD35StdRoll&#125; {{checkroll=[Climb](http://www.dandwiki.com/wiki/SRD:Climb_Skill ) check: [[1d20 + [[@{climb}]] ]] &#125;&#125; |Concentration,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Concentration](http://www.dandwiki.com/wiki/SRD:Concentration_Skill ) check: [[1d20 + [[@{concentration}]] ]] &#125;&#125; |Craft (@{craft1name}),&{template:DnD35StdRoll&#125; {{checkroll=[Craft](http://www.dandwiki.com/wiki/SRD:Craft_Skill ) (@{craft1name}) check: [[1d20 + [[@{craft1}]] +(?{Artisan&#39;s Tools? &#124;Masterwork&#44;1 &#124;No&#44;-1 &#124;Normal&#44;0 &#125;*2)[Tool Circumstance Bonus] ]] &#125;&#125; |Craft (@{craft2name}),&{template:DnD35StdRoll&#125; {{checkroll=[Craft](http://www.dandwiki.com/wiki/SRD:Craft_Skill ) (@{craft2name}) check: [[1d20 + [[@{craft2}]] +(?{Artisan&#39;s Tools? &#124;Masterwork&#44;1 &#124;No&#44;-1 &#124;Normal&#44;0 &#125;*2)[Tool Circumstance Bonus] ]] &#125;&#125; |Craft (@{craft3name}),&{template:DnD35StdRoll&#125; {{checkroll=[Craft](http://www.dandwiki.com/wiki/SRD:Craft_Skill ) (@{craft3name}) check: [[1d20 + [[@{craft3}]] +(?{Artisan&#39;s Tools? &#124;Masterwork&#44;1 &#124;No&#44;-1 &#124;Normal&#44;0 &#125;*2)[Tool Circumstance Bonus] ]] &#125;&#125; |Decipher Script,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Decipher Script*](http://www.dandwiki.com/wiki/SRD:Decipher_Script_Skill ) check: [[1d20 + @{decipherscript} ]]&#125;&#125;  {{notes=If fail&#44; [[1d20 + @{wis-mod} ]] vs dc5 to avoid drawing a false conclusion.&#125;&#125; |Diplomacy,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Diplomacy](http://www.dandwiki.com/wiki/SRD:Diplomacy_Skill ) check: [[1d20 + [[@{diplomacy}]] ]] &#125;&#125; |Disable Device,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Disable Device*](http://www.dandwiki.com/wiki/SRD:Disable_Device_Skill ) check: [[1d20 + [[@{disabledevice}]] ]] &#125;&#125; |Disguise,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Disguise](http://www.dandwiki.com/wiki/SRD:Disguise_Skill ) check: [[1d20 + [[@{disguise}]] ]] &#125;&#125; |Escape Artist,&{template:DnD35StdRoll&#125; {{checkroll=[Escape Artist](http://www.dandwiki.com/wiki/SRD:Escape_Artist_Skill ) check: [[1d20 + [[@{escapeartist}]] ]] &#125;&#125; |Forgery,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Forgery](http://www.dandwiki.com/wiki/SRD:Forgery_Skill ) check: [[1d20 + [[@{forgery}]] ]] &#125;&#125; |Gather Information,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Gather Information](http://www.dandwiki.com/wiki/SRD:Gather_Information_Skill ) check: [[1d20 + [[@{gatherinformation}]] ]] &#125;&#125; |Handle Animal,&{template:DnD35StdRoll&#125; {{checkroll=[Handle Animal*](http://www.dandwiki.com/wiki/SRD:Handle_Animal_Skill ) check: [[1d20 + [[@{handleanimal}]] ]] &#125;&#125; |Heal,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Heal](http://www.dandwiki.com/wiki/SRD:Heal_Skill ) check: [[1d20 + [[@{heal}]] +(?{Healer&#39;s Kit? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Healer&#39;s Kit Circumstance Bonus] ]] &#125;&#125; |Hide,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Hide](http://www.dandwiki.com/wiki/SRD:Hide_Skill ) check: [[1d20 + [[@{hide}]] ]] &#125;&#125; |Intimidate,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Intimidate](http://www.dandwiki.com/wiki/SRD:Intimidate_Skill ) check: [[1d20 + [[@{intimidate}]] ]] &#125;&#125; |Jump,&{template:DnD35StdRoll&#125; {{checkroll=[Jump](http://www.dandwiki.com/wiki/SRD:Jump_Skill ) check: [[1d20 + [[@{jump}]] ]] &#125;&#125; |Listen,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Listen](http://www.dandwiki.com/wiki/SRD:Listen_Skill ) check: [[1d20 + [[@{listen}]] ]] &#125;&#125; |Move Silently,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Move Silently](http://www.dandwiki.com/wiki/SRD:Move_Silently_Skill ) check: [[1d20 + [[@{movesilent}]] ]] &#125;&#125; |Open Lock,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Open Lock*](http://www.dandwiki.com/wiki/SRD:Open_Lock_Skill ) check: [[1d20 + [[@{openlock}]] +(?{Thieves&#39; Tools?&#124;No&#44;-1 &#124;Normal&#44;0 &#124;Masterwork&#44;1&#125;*2))[Tool Circumstance Bonus] ]] &#125;&#125; |Perform (@{perform1name}),&{template:DnD35StdRoll&#125; {{checkroll=[Perform](http://www.dandwiki.com/wiki/SRD:Perform_Skill ) (@{perform1name}) check: [[1d20 + [[@{perform1}]] +(?{Masterwork Instrument? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Instrument Circumstance Bonus] ]] &#125;&#125; |Perform (@{perform2name}),&{template:DnD35StdRoll&#125; {{checkroll=[Perform](http://www.dandwiki.com/wiki/SRD:Perform_Skill ) (@{perform2name}) check: [[1d20 + [[@{perform2}]] +(?{Masterwork Instrument? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Instrument Circumstance Bonus] ]] &#125;&#125; |Perform (@{perform3name}),&{template:DnD35StdRoll&#125; {{checkroll=[Perform](http://www.dandwiki.com/wiki/SRD:Perform_Skill ) (@{perform2name}) check: [[1d20 + [[@{perform3}]] +(?{Masterwork Instrument? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Instrument Circumstance Bonus] ]] &#125;&#125; |Profession (@{profession1name}),&{template:DnD35StdRoll&#125; {{checkroll=[Profession](http://www.dandwiki.com/wiki/SRD:Profession_Skill ) (@{profession1name})* check: [[1d20 + [[@{profession1}]] ]] &#125;&#125; |Profession (@{profession2name}),&{template:DnD35StdRoll&#125; {{checkroll=[Profession](http://www.dandwiki.com/wiki/SRD:Profession_Skill ) (@{profession2name})* check: [[1d20 + [[@{profession2}]] ]] &#125;&#125; |Profession (@{profession3name}),&{template:DnD35StdRoll&#125; {{checkroll=[Profession](http://www.dandwiki.com/wiki/SRD:Profession_Skill ) (@{profession3name})* check: [[1d20 + [[@{profession3}]] ]] &#125;&#125; |Ride,&{template:DnD35StdRoll&#125; {{checkroll=[Ride](http://www.dandwiki.com/wiki/SRD:Ride_Skill ) check: [[1d20 + [[@{ride}]] ]] &#125;&#125; |Search,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Search](http://www.dandwiki.com/wiki/SRD:Search_Skill ) check: [[1d20 + [[@{search}]] ]] &#125;&#125; |Sleight of Hand,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Sleight of Hand*](http://www.dandwiki.com/wiki/SRD:Sleight_of_Hand_Skill ) check: [[1d20 + [[@{sleightofhand}]] ]] &#125;&#125; |Spellcraft,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Spellcraft*](http://www.dandwiki.com/wiki/SRD:Spellcraft_Skill ) check: [[1d20 + [[@{spellcraft}]] ]] &#125;&#125; |Spot,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Spot](http://www.dandwiki.com/wiki/SRD:Spot_Skill ) check: [[1d20 + [[@{spot}]] ]] &#125;&#125; |Survival,&{template:DnD35StdRoll&#125; {{checkroll=Survival check: [[1d20 + [[@{survival}]] ]] &#125;&#125; |Swim,&{template:DnD35StdRoll&#125; {{checkroll=[Swim](http://www.dandwiki.com/wiki/SRD:Swim_Skill ) check: [[1d20 + [[@{swim}]] ]] &#125;&#125; |Tumble,&{template:DnD35StdRoll&#125; {{checkroll=[Tumble*](http://www.dandwiki.com/wiki/SRD:Tumble_Skill ) check: [[1d20 + [[@{tumble}]] ]] &#125;&#125; |Use Magic Device,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Use Magic Device*](http://www.dandwiki.com/wiki/SRD:Use_Magic_Device_Skill ) check: [[1d20 + [[@{usemagicdevice}]] ]] &#125;&#125; |Use Rope,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Use Rope](http://www.dandwiki.com/wiki/SRD:Use_Rope_Skill ) check: [[1d20 + [[@{userope}]] ]] &#125;&#125; } {{skillflag=true}} {{name=@{selected|character_name}}} {{check= }}

New; includes notes fields:

?{Which skill?|Appraise,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Appraise](http://www.dandwiki.com/wiki/SRD:Appraise_Skill ) check: [[1d20 + [[@{appraise}]] ]] &#125;&#125; {{notes=@{selected|appraisenote} &#125;&#125;|Balance,&{template:DnD35StdRoll&#125; {{checkroll=[Balance](http://www.dandwiki.com/wiki/SRD:Balance_Skill ) check: [[1d20 + [[@{balance}]] ]] &#125;&#125; {{notes=@{selected|balancenote} &#125;&#125;|Bluff,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Bluff](http://www.dandwiki.com/wiki/SRD:Bluff_Skill ) check: [[1d20 + [[@{bluff}]] ]] &#125;&#125; {{notes=@{selected|bluffnote} &#125;&#125;|Climb,&{template:DnD35StdRoll&#125; {{checkroll=[Climb](http://www.dandwiki.com/wiki/SRD:Climb_Skill ) check: [[1d20 + [[@{climb}]] ]] &#125;&#125; {{notes=@{selected|climbnote} &#125;&#125;|Concentration,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Concentration](http://www.dandwiki.com/wiki/SRD:Concentration_Skill ) check: [[1d20 + [[@{concentration}]] ]] &#125;&#125; {{notes=@{selected|concentrationnote} &#125;&#125;|Craft (@{craft1name}),&{template:DnD35StdRoll&#125; {{checkroll=[Craft](http://www.dandwiki.com/wiki/SRD:Craft_Skill ) (@{craft1name}) check: [[1d20 + [[@{craft1}]] +(?{Artisan&#39;s Tools? &#124;Masterwork&#44;1 &#124;No&#44;-1 &#124;Normal&#44;0 &#125;*2)[Tool Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|craft1note} &#125;&#125;|Craft (@{craft2name}),&{template:DnD35StdRoll&#125; {{checkroll=[Craft](http://www.dandwiki.com/wiki/SRD:Craft_Skill ) (@{craft2name}) check: [[1d20 + [[@{craft2}]] +(?{Artisan&#39;s Tools? &#124;Masterwork&#44;1 &#124;No&#44;-1 &#124;Normal&#44;0 &#125;*2)[Tool Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|craft2note} &#125;&#125;|Craft (@{craft3name}),&{template:DnD35StdRoll&#125; {{checkroll=[Craft](http://www.dandwiki.com/wiki/SRD:Craft_Skill ) (@{craft3name}) check: [[1d20 + [[@{craft3}]] +(?{Artisan&#39;s Tools? &#124;Masterwork&#44;1 &#124;No&#44;-1 &#124;Normal&#44;0 &#125;*2)[Tool Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|craft3note} &#125;&#125;|Decipher Script,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Decipher Script*](http://www.dandwiki.com/wiki/SRD:Decipher_Script_Skill ) check: [[1d20 + @{decipherscript} ]]&#125;&#125;  {{notes=If fail&#44; [[1d20 + @{wis-mod} ]] vs dc5 to avoid drawing a false conclusion.  @{selected|decipherscriptnote} &#125;&#125; |Diplomacy,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Diplomacy](http://www.dandwiki.com/wiki/SRD:Diplomacy_Skill ) check: [[1d20 + [[@{diplomacy}]] ]] &#125;&#125; {{notes=@{selected|diplomacynote} &#125;&#125;|Disable Device,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Disable Device*](http://www.dandwiki.com/wiki/SRD:Disable_Device_Skill ) check: [[1d20 + [[@{disabledevice}]] ]] &#125;&#125; {{notes=@{selected|disabledevicenote} &#125;&#125;|Disguise,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Disguise](http://www.dandwiki.com/wiki/SRD:Disguise_Skill ) check: [[1d20 + [[@{disguise}]] ]] &#125;&#125; {{notes=@{selected|disguisenote} &#125;&#125;|Escape Artist,&{template:DnD35StdRoll&#125; {{checkroll=[Escape Artist](http://www.dandwiki.com/wiki/SRD:Escape_Artist_Skill ) check: [[1d20 + [[@{escapeartist}]] ]] &#125;&#125; {{notes=@{selected|escapeartistnote} &#125;&#125;|Forgery,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Forgery](http://www.dandwiki.com/wiki/SRD:Forgery_Skill ) check: [[1d20 + [[@{forgery}]] ]] &#125;&#125; {{notes=@{selected|forgerynote} &#125;&#125;|Gather Information,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Gather Information](http://www.dandwiki.com/wiki/SRD:Gather_Information_Skill ) check: [[1d20 + [[@{gatherinformation}]] ]] &#125;&#125; {{notes=@{selected|gatherinformationnote} &#125;&#125;|Handle Animal,&{template:DnD35StdRoll&#125; {{checkroll=[Handle Animal*](http://www.dandwiki.com/wiki/SRD:Handle_Animal_Skill ) check: [[1d20 + [[@{handleanimal}]] ]] &#125;&#125; {{notes=@{selected|handleanimalnote} &#125;&#125;|Heal,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Heal](http://www.dandwiki.com/wiki/SRD:Heal_Skill ) check: [[1d20 + [[@{heal}]] +(?{Healer&#39;s Kit? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Healer&#39;s Kit Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|healnote} &#125;&#125;|Hide,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Hide](http://www.dandwiki.com/wiki/SRD:Hide_Skill ) check: [[1d20 + [[@{hide}]] ]] &#125;&#125; {{notes=@{selected|hidenote} &#125;&#125;|Intimidate,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Intimidate](http://www.dandwiki.com/wiki/SRD:Intimidate_Skill ) check: [[1d20 + [[@{intimidate}]] ]] &#125;&#125; {{notes=@{selected|intimidatenote} &#125;&#125;|Jump,&{template:DnD35StdRoll&#125; {{checkroll=[Jump](http://www.dandwiki.com/wiki/SRD:Jump_Skill ) check: [[1d20 + [[@{jump}]] ]] &#125;&#125; {{notes=@{selected|jumpnote} &#125;&#125;|Listen,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Listen](http://www.dandwiki.com/wiki/SRD:Listen_Skill ) check: [[1d20 + [[@{listen}]] ]] &#125;&#125; {{notes=@{selected|listennote} &#125;&#125;|Move Silently,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Move Silently](http://www.dandwiki.com/wiki/SRD:Move_Silently_Skill ) check: [[1d20 + [[@{movesilent}]] ]] &#125;&#125; {{notes=@{selected|movesilentnote} &#125;&#125;|Open Lock,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Open Lock*](http://www.dandwiki.com/wiki/SRD:Open_Lock_Skill ) check: [[1d20 + [[@{openlock}]] +(?{Thieves&#39; Tools?&#124;No&#44;-1 &#124;Normal&#44;0 &#124;Masterwork&#44;1&#125;*2))[Tool Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|openlocknote} &#125;&#125;|Perform (@{perform1name}),&{template:DnD35StdRoll&#125; {{checkroll=[Perform](http://www.dandwiki.com/wiki/SRD:Perform_Skill ) (@{perform1name}) check: [[1d20 + [[@{perform1}]] +(?{Masterwork Instrument? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Instrument Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|perform1note} &#125;&#125;|Perform (@{perform2name}),&{template:DnD35StdRoll&#125; {{checkroll=[Perform](http://www.dandwiki.com/wiki/SRD:Perform_Skill ) (@{perform2name}) check: [[1d20 + [[@{perform2}]] +(?{Masterwork Instrument? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Instrument Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|perform2note} &#125;&#125;|Perform (@{perform3name}),&{template:DnD35StdRoll&#125; {{checkroll=[Perform](http://www.dandwiki.com/wiki/SRD:Perform_Skill ) (@{perform2name}) check: [[1d20 + [[@{perform3}]] +(?{Masterwork Instrument? &#124;No&#44;0 &#124;Yes&#44;1&#125;*2)[Instrument Circumstance Bonus] ]] &#125;&#125; {{notes=@{selected|perform3note} &#125;&#125;|Profession (@{profession1name}),&{template:DnD35StdRoll&#125; {{checkroll=[Profession](http://www.dandwiki.com/wiki/SRD:Profession_Skill ) (@{profession1name})* check: [[1d20 + [[@{profession1}]] ]] &#125;&#125; {{notes=@{selected|profession1note} &#125;&#125;|Profession (@{profession2name}),&{template:DnD35StdRoll&#125; {{checkroll=[Profession](http://www.dandwiki.com/wiki/SRD:Profession_Skill ) (@{profession2name})* check: [[1d20 + [[@{profession2}]] ]] &#125;&#125; {{notes=@{selected|profession2note} &#125;&#125;|Profession (@{profession3name}),&{template:DnD35StdRoll&#125; {{checkroll=[Profession](http://www.dandwiki.com/wiki/SRD:Profession_Skill ) (@{profession3name})* check: [[1d20 + [[@{profession3}]] ]] &#125;&#125; {{notes=@{selected|profession3note} &#125;&#125;|Ride,&{template:DnD35StdRoll&#125; {{checkroll=[Ride](http://www.dandwiki.com/wiki/SRD:Ride_Skill ) check: [[1d20 + [[@{ride}]] ]] &#125;&#125; {{notes=@{selected|ridenote} &#125;&#125;|Search,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Search](http://www.dandwiki.com/wiki/SRD:Search_Skill ) check: [[1d20 + [[@{search}]] ]] &#125;&#125; {{notes=@{selected|searchnote} &#125;&#125;|Sleight of Hand,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Sleight of Hand*](http://www.dandwiki.com/wiki/SRD:Sleight_of_Hand_Skill ) check: [[1d20 + [[@{sleightofhand}]] ]] &#125;&#125; {{notes=@{selected|sleightofhandnote} &#125;&#125;|Spellcraft,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Spellcraft*](http://www.dandwiki.com/wiki/SRD:Spellcraft_Skill ) check: [[1d20 + [[@{spellcraft}]] ]] &#125;&#125; {{notes=@{selected|spellcraftnote} &#125;&#125;|Spot,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Spot](http://www.dandwiki.com/wiki/SRD:Spot_Skill ) check: [[1d20 + [[@{spot}]] ]] &#125;&#125; {{notes=@{selected|spotnote} &#125;&#125;|Survival,&{template:DnD35StdRoll&#125; {{checkroll=[Survival](http://www.dandwiki.com/wiki/SRD:Survival_Skill ) check: [[1d20 + [[@{survival}]] ]] &#125;&#125; {{notes=@{selected|survivalnote} &#125;&#125;|Swim,&{template:DnD35StdRoll&#125; {{checkroll=[Swim](http://www.dandwiki.com/wiki/SRD:Swim_Skill ) check: [[1d20 + [[@{swim}]] ]] &#125;&#125; {{notes=@{selected|chanote} &#125;&#125;|Tumble,&{template:DnD35StdRoll&#125; {{checkroll=[Tumble*](http://www.dandwiki.com/wiki/SRD:Tumble_Skill ) check: [[1d20 + [[@{tumble}]] ]] &#125;&#125; {{notes=@{selected|tumblenote} &#125;&#125;|Use Magic Device,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Use Magic Device*](http://www.dandwiki.com/wiki/SRD:Use_Magic_Device_Skill ) check: [[1d20 + [[@{usemagicdevice}]] ]] &#125;&#125; {{notes=@{selected|usemagicdevicenote} &#125;&#125;|Use Rope,/w gm &{template:DnD35StdRoll&#125; {{checkroll=[Use Rope](http://www.dandwiki.com/wiki/SRD:Use_Rope_Skill ) check: [[1d20 + [[@{userope}]] ]] &#125;&#125; {{notes=@{selected|useropenote} &#125;&#125; } {{skillflag=true}} {{name=@{selected|character_name}}} {{check= }}

### Skill checks using Buttons

/w @{selected|character_name} &{template:DnD35StdRoll} {{ name = Skill List }} {{ [Appraise](~selected|appraisecheck) = [Balance](~selected|balancecheck) }} {{ [Bluff](~selected|bluffcheck) = [Climb](~selected|climbcheck) }} {{ [Concentration](~selected|concentrationcheck) = [Craft (@{selected|craft1name})](~selected|craft1check) }} {{ [Craft (@{selected|craft2name})](~selected|craft2check) = [Craft (@{selected|craft3name})](~selected|craft3check) }} {{ [Decipher Script](~selected|decipherscriptcheck) = [Diplomacy](~selected|diplomacycheck) }} {{ [Disable Device](~selected|disabledevicecheck) = [Disguise](~selected|disguisecheck) }} {{ [Escape Artist](~selected|escapeartistcheck) = [Forgery](~selected|forgerycheck) }} {{ [Gather Information](~selected|gatherinformationcheck) = [Handle Animal](~selected|handleanimalcheck) }} {{ [Heal](~selected|healcheck) = [Hide](~selected|hidecheck) }} {{ [Intimidate](~selected|intimidatecheck) = [jump](~selected|jumpcheck) }} {{ [Knowledge (Arcana)](~selected|knowarcanacheck) = [Knowledge (Engineering)](~selected|knowengineercheck) }} {{ [Knowledge (Dungeoneering)](~selected|knowdungeoncheck) = [Knowledge (Geography)](~selected|knowgeographycheck) }} {{ [Knowledge (History)](~selected|knowhistorycheck) = [Knowledge (Local)](~selected|knowlocalcheck) }} {{ [Knowledge (Nature)](~selected|knownaturecheck) = [Knowledge (Nobility)](~selected|knownobilitycheck) }} {{ [Knowledge (Religion)](~selected|knowreligioncheck) = [Knowledge (the Planes)](~selected|knowplanescheck) }} {{ [Listen](~selected|listencheck) = [Move Silently](~selected|movesilentcheck) }} {{ [Open Lock](~selected|openlockcheck) = [Perform (@{selected|perform1name})](~selected|perform1check) }} {{ [Perform (@{selected|perform2name})](~selected|perform2check) = [Perform (@{selected|perform3name})](~selected|perform3check) }} {{ [Profession (@{selected|profession1name})](~selected|profession1check) = [Profession (@{selected|profession2name})](~selected|profession2check) }} {{ [Profession (@{selected|profession3name})](~selected|profession3check) = [Ride](~selected|ridecheck) }} {{ [Search](~selected|searchcheck) = [Sense Motive](~selected|sensemotivecheck) }} {{ [Sleight of Hand](~selected|sleightofhandcheck) = [Spellcraft](~selected|spellcraftcheck) }} {{ [Spot](~selected|spotcheck) = [Survival](~selected|survivalcheck) }} {{ [Swim](~selected|swimcheck) = [Tumble](~selected|tumblecheck) }} {{ [Use Magic Device](~selected|usemagicdevicecheck) = [Use Rope](~selected|useropecheck) }}

### Weapon attacks 

(for first 4 slots; adjust for personalization of attack description ie: swings a.  Also add notes about the attack/weapon in {{notes= &#125;&#125; section):

&{template:DnD35Attack} {{pcflag=true}} {{fullattackflag=[[?{Full Attack?|No, 0d1|Yes, d1}]]}} {{name=@{character_name}}} ?{Flank|No, 0|Yes, 1} ?{Other Attack Bonus|0} ?{Other Damage Bonus|0} {{fumbleroll=**Fumble:[[d20]]**}} ?{Which weapon? |@{weapon1name}, {{subtags=swings a @{weapon1name} &#125;&#125; {{attack1=A1:[[@{selected|weapon1attackcalc|max} ]] &#125;&#125; {{critconfirm1=Crit?:[[@{selected|weapon1attackcalc|max} ]] &#125;&#125; {{damage1=D1:[[@{selected|weapon1damage|max} ]] &#125;&#125; {{critdmg1=+[[@{selected|weapon1damage|max} ]] &#125;&#125; {{attack2=A2:[[@{selected|weapon1attackcalc|max}-5 ]] &#125;&#125; {{critconfirm2=Crit?:[[@{selected|weapon1attackcalc|max}-5 ]] &#125;&#125; {{damage2=D2:[[@{selected|weapon1damage|max} ]] &#125;&#125; {{critdmg2=+[[@{selected|weapon1damage|max} ]] &#125;&#125; {{notes= &#125;&#125; |@{weapon2name}, {{subtags=swings a @{weapon2name} &#125;&#125; {{attack1=A1:[[@{selected|weapon2attackcalc|max} ]] &#125;&#125; {{critconfirm1=Crit?:[[@{selected|weapon2attackcalc|max} ]] &#125;&#125; {{damage1=D1:[[@{selected|weapon2damage|max} ]] &#125;&#125; {{critdmg1=+[[@{selected|weapon2damage|max}]] &#125;&#125; {{attack2=A2:[[@{selected|weapon2attackcalc|max}-5]] &#125;&#125; {{critconfirm2=Crit?:[[@{selected|weapon2attackcalc|max}-5]] &#125;&#125; {{damage2=D2:[[@{selected|weapon2damage|max} ]] &#125;&#125; {{critdmg2=+[[@{selected|weapon1damage|max}]] &#125;&#125; {{notes= &#125;&#125; |@{weapon3name}, {{subtags=swings a @{weapon3name} &#125;&#125; {{attack1=A1:[[@{selected|weapon3attackcalc|max} ]] &#125;&#125; {{critconfirm1=Crit?:[[@{selected|weapon3attackcalc|max} ]] &#125;&#125; {{damage1=D1:[[@{selected|weapon3damage|max} ]] &#125;&#125; {{critdmg1=+[[@{selected|weapon3damage|max}]] &#125;&#125; {{attack2=A2:[[@{selected|weapon3attackcalc|max}-5 ]] &#125;&#125; {{critconfirm2=Crit?:[[@{selected|weapon3attackcalc|max}-5]] &#125;&#125; {{damage2=D2:[[@{selected|weapon3damage|max}]] &#125;&#125; {{critdmg2=+[[@{selected|weapon3damage|max}]] &#125;&#125; {{notes= &#125;&#125; |@{weapon4name}, {{subtags=swings a @{weapon4name} &#125;&#125; {{attack1=A1:[[@{selected|weapon4attackcalc|max}]] &#125;&#125; {{critconfirm1=Crit?:[[@{selected|weapon4attackcalc|max}]] &#125;&#125; {{damage1=D1:[[@{selected|weapon4damage|max}]] &#125;&#125; {{critdmg1=+[[@{selected|weapon4damage|max} ]] &#125;&#125; {{attack2=A2:[[@{selected|weapon4attackcalc|max}-5]] &#125;&#125; {{critconfirm2=Crit?:[[@{selected|weapon4attackcalc|max}-5]] &#125;&#125; {{damage2=D2:[[@{selected|weapon4damage|max}]] &#125;&#125; {{critdmg2=+[[@{selected|weapon4damage|max} ]] &#125;&#125; {{notes= &#125;&#125; }

It ought to be added as a token action because it requires the token to be selected since it uses the max field for the weapon attack calculations and damage calculations.  Copy the weapon attack and damage calculations (on the Attributes and Abilities tab) and edit them so that any closing braces of any queries are replaced by the html entity for it ie:

1d20cs>@{weapon1critmin} +@{bab}[BAB] +[[@{weapon1stat}]][Ability] +@{size}[size] +@{weapon1enh}[Weapon1 Enh] +@{weapon1focus}[Weapon1 Focus] + ?{Flank|No, 0|Yes, 1}*2[Flank] +?{Other Attack Bonus?|0}[Other Attack Bonus]

and

1d6cs>7 +[[@{weapon1damagestat}]][Weapon1DamageStat] +@{weapon1enh}[Weapon1 Enh] +@{weapon1specialize}[Weapon1 Specialization] +?{Other Damage Bonus}[Other Damage Bonus]

needs to be:

1d20cs>@{weapon1critmin} +@{bab}[BAB] +[[@{weapon1stat}]][Ability] +@{size}[size] +@{weapon1enh}[Weapon1 Enh] +@{weapon1focus}[Weapon1 Focus] + ?{Flank&#125;*2[Flank] +?{Other Attack Bonus&#125;[Other Attack Bonus]

and

1d6cs>7 +[[@{weapon1damagestat}]][Weapon1DamageStat] +@{weapon1enh}[Weapon1 Enh] +@{weapon1specialize}[Weapon1 Specialization] +?{Other Damage Bonus?&#125;[Other Damage Bonus]

Note the &#125; replacement for the closing brace on the Flank, Other Attack Bonus, and Other Damage Bonus queries  (I've removed the queries for Power Attack in this version since the particular character this comes from does not use Power Attack, but it would be treated the same way).

These adjusted attack and damage calculations need to be pasted into the max field for the appropriate attribute for this macro to function properly.

### Choose a Cure:

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{check=**@{target|token_name}** receives }}  ?{Which Cure? |Moderate, {{subtags=casts [Cure Moderate Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Moderate_Wounds ). &#125;&#125; {{checkroll= [[2d8+[[{@{casterlevel}&#44;10&#125;dh1]] ]] heath. &#125;&#125; |Minor, {{subtags=casts [Cure Minor Wounds](http://www.dandwiki.com/wiki/Cure_minor_wounds ). &#125;&#125; {{checkroll= [[1d1]] heath.  &#125;&#125; |Light, {{subtags=casts [Cure Light Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Light_Wounds ). &#125;&#125; {{checkroll= [[1d8+[[{@{casterlevel}&#44;5&#125;dh1]] ]] heath. &#125;&#125; |Serious, {{subtags=casts [Cure Serious Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Serious_Wounds ). &#125;&#125; {{checkroll= [[3d8 +[[{@{casterlevel}&#44;15&#125;dh1]] ]] heath.  &#125;&#125; |Critical, {{subtags=casts [Cure Critical Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Critical_Wounds ). &#125;&#125; {{checkroll= [[4d8 +[[{@{casterlevel}&#44;20&#125;dh1]] ]] heath.  &#125;&#125; } {{notes=Undead creatures take damage instead of gaining healing; DC [[10+5 +[[@{wis-mod}]] ]] Will save for half damage; caster level check = [[1d20+@{casterlevel}+@{spellpen}]] vs spell resistance. }}

--------------------------

# Chell’s Grouped macros:

&{template:DnD35Attack} {{saveflag=true}} {{name=@{character_name} }} {{subtags=**Saves**}} {{attack1=**Fortitude check:**}} {{damage1=[[1d20 + @{fortitude}]] }} {{fullattackflag=[[d1]]}} {{attack2=*+[[7]] vs Spells*}} {{damage2=*+[[4]] vs Poison*}} {{attack3=**Reflex check:**}} {{damage3=[[1d20 + @{reflex}]] }} {{attack4=*+[[7]] vs Spells*}}  {{attack5=**Will check:**}} {{damage5=[[1d20 + @{will}]] }}  {{attack6=*+[[7]] vs Spells*}} {{damage6=*-[[2]] vs Fear*}} {{attack7=*+[[2]] vs Sleep/Charm*}} {{notes= immune to disease & fire}}

&{template:DnD35StdRoll} {{skillflag=true}} {{name=@{character_name} }} {{subtags=**Senses**}} {{**Spot **=[[1d20 + @{spot}]] }} {{**Listen **=[[1d20 + @{listen}]] }} {{**Search**=[[1d20 + @{search}]] }}

&{template:DnD35StdRoll} {{skillflag=true}} {{name=@{character_name} }} {{subtags=**Sneak**}} {{**Hide**=[[1d20 + @{hide} +@{int-mod}]] }} {{**Move Silent**=[[1d20 + @{movesilent}]] }} {{notes=While within 10ft of shadows, besides her own, +[[20]] Hide}}

&{template:DnD35StdRoll} {{skillflag=true}} {{name=@{character_name} }} {{subtags=**Trapfinding**}} {{**Search**=[[1d20 + @{search}]] }} {{**Disable Device**=[[1d20 + @{disabledevice}]] }}

&{template:DnD35StdRoll} {{skillflag=true}} {{name=@{character_name} }} {{subtags= **Knowledge Check**}} {{Arcana | Dungeoneering  Religion | The Planes=[[1d20 + @{knowarcana}]] }}  {{Engineering | Geography  Local | Nature | Nobility=[[1d20 + @{knowengineer}]] }} {{History=[[1d20 + @{knowhistory}]] }} {{**Lore Check** =[[1d20 + @{int-mod} + {@{casterlevel}+@{casterlevel2}, @{level}}kl1 +11]]}}

-------------------------

# Rabulius’ Macros:

Sor/Wiz Level 0:[ http://pastebin.com/h2CHRs4E](http://pastebin.com/h2CHRs4E)

Sor/Wiz Level 1:[ http://pastebin.com/dHbRK2iu](http://pastebin.com/dHbRK2iu)

## Sorcerer/Wizard Spells - Level: 0 ver 20150806

==============================================

 

Acid Splash

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Acid Splash]([http://www.dandwiki.com/wiki/SRD:Acid_Splash](http://www.dandwiki.com/wiki/SRD:Acid_Splash)) }} {{School:=Conj (Creat) [Acid]}} {{Level:= Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One missile of acid }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= No }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|rangedattackbonus}]] for [[1d3]] point(s) of acid damage. }} {{notes= PHB p.196}}

 

Arcane Mark

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Arcane Mark](http://www.dandwiki.com/wiki/SRD:Arcane_Mark) }} {{School:=Univ}} {{Level:= Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 0 ft }} {{Effect:= One personal rune or mark, all of which must fit within 1 sq ft }} {{Dur:= Permanent}} {{Save:= None }} {{SR:= No }} {{notes= This spell allows you to inscribe your personal rune or mark, which can consist of no more than six characters. The writing can be visible or invisible. An arcane mark spell enables you to etch the rune upon any substance (even stone or metal) without harm to the material upon which it is placed.

See full description for more details.

PHB p.201}}

 

Dancing Lights

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Dancing Lights](http://www.dandwiki.com/wiki/SRD:Dancing_Lights) }} {{School:=Evoc [Light]}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Effect:= Up to 4 lights, all within a 10-ft-radius area }} {{Dur:= 1 minute (D)}} {{Save:= None }} {{SR:= No }} {{notes= You create up to four lights that resemble lanterns or torches (and cast that amount of light), or up to four glowing spheres of light (which look like will-o'-wisps), or one faintly glowing, vaguely humanoid shape. The dancing lights must stay within a 10-foot-radius area in relation to each other but otherwise move as you desire (no concentration required): forward or back, up or down, straight or turning corners, or the like. The lights can move up to 100 feet per round. A light winks out if the distance between you and it exceeds the spell's range.

PHB p.216}}

 

Daze

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Daze](http://www.dandwiki.com/wiki/SRD:Daze) }} {{School:=Ench (Comp) [Mind-Aff]}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One humanoid creature of 4 HD or less }} {{Dur:= 1 round}} {{Save:= Will negates

(DC: [[@{selected|spelldc0} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Clouds the mind of a humanoid creature with 4 or fewer Hit Dice so that it takes no actions. Humanoids of 5 or more HD are not affected. A dazed subject is not stunned, so attackers get no special advantage against it.

PHB p.217}}

 

Detect Magic

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Magic](http://www.dandwiki.com/wiki/SRD:Detect_Magic) }} {{School:=Div}} {{Level:= Brd 0, Clr 0, Drd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of magical auras.

 

2nd Round: Number of different magical auras and the power of the most potent aura.

 

3rd Round: The strength and location of each aura. If the items or creatures bearing the auras are in line of sight, you can make Spellcraft skill checks to determine the school of magic involved in each. (Make one check per aura; DC 15 + spell level, or 15 + half caster level for a nonspell effect.)

 

Each round, you can turn to detect magic in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.219}}

 

Detect Poison

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Poison](http://www.dandwiki.com/wiki/SRD:Detect_Poison) }} {{School:=Div}} {{Level:= Clr 0, Drd 0, Pal 1, Rgr 1, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target or Area:= One creature, one object, or a 5-ft cube }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= No }} {{notes= Tell if a creature, object, or area has been poisoned or is poisonous. You can determine the exact type of poison with a DC 20 Craft (alchemy) check or a DC 20 Wisdom check.

 

The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

PHB p.219}}

 

Disrupt Undead

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Disrupt Undead](http://www.dandwiki.com/wiki/SRD:Disrupt_Undead) }} {{School:=Necro}} {{Level:= Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Ray }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|rangedattackbonus}]] for [[1d6]] point(s) of positive energy damage. }} {{notes= PHB p.223}}

 

Flare

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Flare](http://www.dandwiki.com/wiki/SRD:Flare) }} {{School:=Evoc [Light]}} {{Level:= Brd 0, Drd 0, Sor/Wiz 0}} {{Comp:=V}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Burst of light }} {{Dur:= Instantaneous}} {{Save:= Fortitude negates

(DC: [[@{selected|spelldc0} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= This cantrip creates a burst of light. If you cause the light to burst directly in front of a single creature, that creature is dazzled for 1 minute unless it makes a successful Fortitude save. Sightless creatures, as well as creatures already dazzled, are not affected by flare.

PHB p.232}}

 

Ghost Sound

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Ghost Sound](http://www.dandwiki.com/wiki/SRD:Ghost_Sound) }} {{School:=Ill (Figment)}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Illusory sounds }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= Will disbelief (if interacted with)

(DC: [[@{selected|spelldc0} + @{selected|sf-illusion}]]) }} {{SR:= No }} {{notes= Ghost sound allows you to create a volume of sound that rises, recedes, approaches, or remains at a fixed place. You choose what type of sound ghost sound creates when casting it and cannot thereafter change the sound's basic character.

 

You can produce as much noise as [[{4*floor(@{selected|casterlevel}), 20}dh1]] normal humans. Thus, talking, singing, shouting, walking, marching, or running sounds can be created. The noise a ghost sound spell produces can be virtually any type of sound within the volume limit. A horde of rats running and squeaking is about the same volume as eight humans running and shouting. A roaring lion is equal to the noise from sixteen humans, while a roaring dire tiger is equal to the noise from twenty humans.

See full description for more details.

PHB p.235}}

 

Light

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Light](http://www.dandwiki.com/wiki/SRD:Light) }} {{School:=Evoc [Light]}} {{Level:= Brd 0, Clr 0, Drd 0, Sor/Wiz 0}} {{Comp:=V, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Object touched }} {{Dur:= [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell causes an object to glow like a torch, shedding bright light in a 20-foot-radius (and dim light for an additional 20 feet) from the point you touch.

See full description for more details.

PHB p.248}}

 

Mage Hand

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Mage Hand](http://www.dandwiki.com/wiki/SRD:Mage_Hand) }} {{School:=Trans}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One nonmagical, unattended object weighing up to 5 lb. }} {{Dur:= Concentration}} {{Save:= None }} {{SR:= No }} {{notes= You point your finger at an object and can lift it and move it at will from a distance. As a move action, you can propel the object as far as 15 feet in any direction, though the spell ends if the distance between you and the object ever exceeds the spell's range.

PHB p.249}}

 

Mending

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Mending](http://www.dandwiki.com/wiki/SRD:Mending) }} {{School:=Trans}} {{Level:= Brd 0, Clr 0, Drd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 10 ft }} {{Target:= One object of up to 1 lb }} {{Dur:= Instantaneous}} {{Save:= Will negates (harmless, object)

(DC: [[@{selected|spelldc0} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless, object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Mending repairs small breaks or tears in objects.

See full description for more details.

PHB p.253}}

 

Message

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Message](http://www.dandwiki.com/wiki/SRD:Message) }} {{School:=Trans [Lang-Dep]}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Target:= @{selected|casterlevel} creatures }} {{Dur:= [[10*@{selected|casterlevel}]] minutes}} {{Save:= None }} {{SR:= No }} {{notes= You can whisper messages and receive whispered replies with little chance of being overheard. You point your finger at each creature you want to receive the message. When you whisper, the whispered message is audible to all targeted creatures within range. Magical silence, 1 foot of stone, 1 inch of common metal (or a thin sheet of lead), or 3 feet of wood or dirt blocks the spell. The message does not have to travel in a straight line. It can circumvent a barrier if there is an open path between you and the subject, and the path's entire length lies within the spell's range. The creatures that receive the message can whisper a reply that you hear. The spell transmits sound, not meaning. It doesn't transcend language barriers.

See full description for more details.

PHB p.253}}

 

Open/Close

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Open/Close](http://www.dandwiki.com/wiki/SRD:Open/Close) }} {{School:=Trans}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= Object weighing up to 30 lb. or portal that can be opened or closed }} {{Dur:= Instantaneous}} {{Save:= Will negates (object)

(DC: [[@{selected|spelldc0} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= You can open or close (your choice) a door, chest, box, window, bag, pouch, bottle, barrel, or other container. If anything resists this activity (such as a bar on a door or a lock on a chest), the spell fails. In addition, the spell can only open and close things weighing 30 pounds or less. Thus, doors, chests, and similar objects sized for enormous creatures may be beyond this spell's ability to affect.

PHB p.258}}

 

Prestidigitation

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Prestidigitation](http://www.dandwiki.com/wiki/SRD:Prestidigitation) }} {{School:=Univ}} {{Level:= Brd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 10 ft }} {{Target, Effect, or Area:= See text }} {{Dur:= 1 hour}} {{Save:= See text }} {{SR:= No }} {{notes= Prestidigitations are minor tricks that novice spellcasters use for practice. Once cast, a prestidigitation spell enables you to perform simple magical effects for 1 hour. The effects are minor and have severe limitations.

See full description for more details.

PHB p.264}}

 

Ray of Frost

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Ray of Frost](http://www.dandwiki.com/wiki/SRD:Ray_of_Frost) }} {{School:=Evoc [Cold]}} {{Level:= Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Ray }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|rangedattackbonus}]] for [[1d3]] point(s) of cold damage.}} {{notes= PHB p.269}}

 

Read Magic

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Read Magic](http://www.dandwiki.com/wiki/SRD:Read_Magic) }} {{School:=Div}} {{Level:= Brd 0, Clr 0, Drd 0, Pal 1, Rgr 1, Sor/Wiz 0}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[10*@{selected|casterlevel}]] minutes}} {{Save:= None }} {{SR:= No }} {{notes= You can decipher magical inscriptions that would otherwise be unintelligible. This does not normally invoke the magic contained in the writing, although it may do so in the case of a cursed scroll. You can read at the rate of one page (250 words) per minute. Identify a glyph of warding with a DC 13 Spellcraft check, a greater glyph of warding with a DC 16 Spellcraft check, or any symbol spell with a Spellcraft check (DC 10 + spell level).

See full description for more details.

PHB p.269}}

 

Resistance

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Resistance](http://www.dandwiki.com/wiki/SRD:Resistance) on @{target|token_name} }} {{School:=Abj}} {{Level:= Brd 0, Clr 0, Drd 0, Pal 1, Sor/Wiz 0}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= 1 minute}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc0} + @{selected|sf-abjuration}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= @{target|token_name} gains a +1 resistance bonus on saves.

See full description for more details.

PHB p.272}}

 

Touch of Fatigue

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Touch of Fatigue](http://www.dandwiki.com/wiki/SRD:Touch_of_Fatigue) }} {{School:=Necro}} {{Level:= Sor/Wiz 0}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] round(s)}} {{Save:= Fortitude negates

(DC: [[@{selected|spelldc0} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|meleeattackbonus}]]. Negative energy fatigues target unless save succeeds.}} {{notes= See full description for more details.

PHB p.294}}

## Sorcerer/Wizard Spells - Level: 1 ver 20150806

==============================================

 

Alarm

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Alarm](http://www.dandwiki.com/wiki/SRD:Alarm) }} {{School:=Abj}} {{Level:= Brd 1, Rgr 1, Sor/Wiz 1}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Area:= 20-ft-radius emanation centered on a point in space }} {{Dur:= [[2*@{selected|casterlevel}]] hours (D)}} {{Save:= None }} {{SR:= No }} {{notes= Alarm sounds a mental or audible alarm each time a creature of Tiny or larger size enters the warded area or touches it. A creature that speaks the password (determined by you at the time of casting) does not set off the alarm. You decide at the time of casting whether the alarm will be mental or audible.

See full description for more details.

PHB p.197}}

 

Animate Rope

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Animate Rope](http://www.dandwiki.com/wiki/SRD:Animate_Rope) }} {{School:=Trans}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Target:= One ropelike object, up to [[50 + 5*@{selected|casterlevel}]] ft long; see text }} {{Dur:= [[@{selected|casterlevel}]] round(s)}} {{Save:= None }} {{SR:= No }} {{notes= You can animate a nonliving ropelike object, such as string, yarn, cord, line, rope, or even a cable.

See full description for more details.

PHB p.199}}

 

Burning Hands

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Burning Hands](http://www.dandwiki.com/wiki/SRD:Burning_Hands) }} {{School:=Evoc [Fire]}} {{Level:= Fire 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 15 ft }} {{Area:= Cone-shaped burst }} {{Dur:= Instantaneous}} {{Save:= Reflex half

(DC: [[@{selected|spelldc1} + @{selected|sf-evocation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= A cone of searing flame shoots from your fingertips. Any creature in the area of the flames takes [[ [[{5, @{selected|casterlevel} }dh1]]d4]] points of fire damage. Flammable materials such as cloth, paper, parchment, and thin wood burn if the flames touch them. A character can extinguish burning items as a full-round action.

PHB p.207}}

 

Cause Fear

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Cause Fear](http://www.dandwiki.com/wiki/SRD:Cause_Fear)   }} {{School:=Necro [Fear, Mind-Aff]}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One living creature with 5 or fewer HD }} {{Dur:= [[1d4]] rounds or 1 round; see text}} {{Save:= Will partial

(DC: [[@{selected|spelldc1} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Affected creature becomes frightened for the full duration. If the subject succeeds on a Will save, it is just shaken for 1 round. Creatures with 6 or more Hit Dice are immune to this effect.

See full description for more details.

PHB p.208}}

 

Charm Person

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Charm Person](http://www.dandwiki.com/wiki/SRD:Charm_Person) }} {{School:=Ench (Charm) [Mind-Aff]}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One humanoid creature }} {{Dur:= [[@{selected|casterlevel}]] hour(s)}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} attempts to charm target. ((notes= See full description for more details.

PHB p.209}}

 

Chill Touch

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Chill Touch](http://www.dandwiki.com/wiki/SRD:Chill_Touch) }} {{School:=Necro}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Up to @{selected|casterlevel} creature(s) touched }} {{Dur:= Instantaneous; see text}} {{Save:= Fortitude partial or Will negates; see text

(DC: [[@{selected|spelldc1} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= A touch from your hand, which glows with blue energy, disrupts the life force of living creatures. Each touch channels negative energy that deals 1d6 points of damage. The touched creature also takes 1 point of Strength damage unless it makes a successful Fortitude saving throw. You can use this melee touch attack up to one time per level.

 

An undead creature you touch takes no damage of either sort, but it must make a successful Will saving throw or flee as if panicked for [[1d4 + @{selected|casterlevel}]] rounds.

PHB p.209}}

 

Color Spray

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Color Spray](http://www.dandwiki.com/wiki/SRD:Color_Spray) }} {{School:=Ill (Pattern) [Mind-Aff]}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= 15 ft }} {{Area:= Cone-shaped burst }} {{Dur:= Instantaneous; see text}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-illusion}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= A vivid cone of clashing colors springs from @{selected|token_name}'s hand. }} {{notes= 2 HD or less: Unconscious, blinded, and stunned for 2d4 rounds, then blinded and stunned for 1d4 rounds, and then stunned for 1 round. (Only living creatures are knocked unconscious.)

3 or 4 HD: Blinded and stunned for 1d4 rounds, then stunned for 1 round.

5+ HD: The creature is stunned for 1 round. Sightless creatures are not affected by color spray.

PHB p.210}}

 

Comprehend Languages

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Comprehend Languages](http://www.dandwiki.com/wiki/SRD:Comprehend_Languages) {{School:=Div}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[10*@{selected|casterlevel}]] minutes}} {{Save:= None }} {{SR:= No }} {{notes= You can understand the spoken words of creatures or read otherwise incomprehensible written messages. In either case, you must touch the creature or the writing. The ability to read does not necessarily impart insight into the material, merely its literal meaning. The spell enables you to understand or read an unknown language, not speak or write it.

 

Written material can be read at the rate of one page (250 words) per minute. Magical writing cannot be read, though the spell reveals that it is magical, but comprehend languages is often useful when deciphering treasure maps. This spell can be foiled by certain warding magic (such as the secret page and illusory script spells). It does not decipher codes or reveal messages concealed in otherwise normal text.

See full description for more details.

PHB p.212}}

 

Detect Secret Doors

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Secret Doors](http://www.dandwiki.com/wiki/SRD:Detect_Secret_Doors) }} {{School:=Div}} {{Level:= Brd 1, Knowledge 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of secret doors.

 

2nd Round: Number of secret doors and the location of each. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each Additional Round: The mechanism or trigger for one particular secret portal closely examined by you.

 

Each round, you can turn to detect secret doors in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.220}}

 

Detect Undead

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Undead](http://www.dandwiki.com/wiki/SRD:Detect_Undead) }} {{School:=Div}} {{Level:= Clr 1, Pal 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of undead auras.

 

2nd Round: Number of undead auras in the area and the strength of the strongest undead aura present. If you are of good alignment, and the strongest undead aura's strength is overwhelming (see full text), and the creature has HD of at least twice your character level, you are stunned for 1 round and the spell ends.

 

3rd Round: The strength and location of each undead aura. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each round, you can turn to detect undead in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.220}}

 

Disguise Self

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Disguise Self](http://www.dandwiki.com/wiki/SRD:Disguise_Self) }} {{School:=Ill (Glamer)}} {{Level:= Brd 1, Sor/Wiz 1, Trickery 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= You make yourself -- including clothing, armor, weapons, and equipment -- look different. You can seem 1 foot shorter or taller, thin, fat, or in between. You cannot change your body type. For example, a human caster could look human, humanoid, or like any other human-shaped bipedal creature. Otherwise, the extent of the apparent change is up to you. You could add or obscure a minor feature, such as a mole or a beard, or look like an entirely different person.

See full description for more details.

PHB p.221}}

 

Endure Elements

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Endure Elements](http://www.dandwiki.com/wiki/SRD:Endure_Elements) on @{target|token_name} }} {{School:=Abj}} {{Level:= Clr 1, Drd 1, Pal 1, Rgr 1, Sor/Wiz 1, Sun 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= 24 hours}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= @{target|token_name} can exist comfortably in conditions between –50 and 140 degrees Fahrenheit. Equipment is also protected.

 

Endure elements doesn't provide any protection from fire or cold damage, nor does it protect against other environmental hazards such as smoke, lack of air, and so forth.

PHB p.226}}

 

Enlarge Person

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Enlarge Person](http://www.dandwiki.com/wiki/SRD:Enlarge_Person) on @{target|token_name} }} {{School:=Trans}} {{Level:= Sor/Wiz 1, Strength 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One humanoid creature }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Fortitude negates

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= This spell causes instant growth of a humanoid creature, doubling its height and multiplying its weight by 8. This increase changes the creature's size category to the next larger one. The target gains a +2 size bonus to Strength, a –2 size penalty to Dexterity (to a minimum of 1), and a –1 penalty on attack rolls and AC due to its increased size.

 

A humanoid creature whose size increases to Large has a space of 10 feet and a natural reach of 10 feet. This spell does not change the target's speed.

See full description for more details.

PHB p.226}}

 

Erase

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Erase](http://www.dandwiki.com/wiki/SRD:Erase) }} {{School:=Trans}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One scroll or two pages }} {{Dur:= Instantaneous}} {{Save:= See text }} {{SR:= No }} {{notes= Erase removes writings of either magical or mundane nature from a scroll or from one or two pages of paper, parchment, or similar surfaces. With this spell, you can remove explosive runes, a glyph of warding, a sepia snake sigil, or an arcane mark, but not illusory script or a symbol spell. Nonmagical writing is automatically erased if you touch it and no one else is holding it. Otherwise, the chance of erasing nonmagical writing is 90%.

 

Magic writing must be touched to be erased, and you also must succeed on a caster level check (1d20 + @{selected|casterlevel}) against DC 15. (A natural 1 or 2 is always a failure on this check.) If you fail to erase explosive runes, a glyph of warding, or a sepia snake sigil, you accidentally activate that writing instead.

PHB p.227}}

 

Expeditious Retreat

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Expeditious Retreat](http://www.dandwiki.com/wiki/SRD:Expeditious_Retreat) }} {{School:=Trans}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= Your base land speed increases by 30 feet. (This adjustment is treated as an enhancement bonus.) There is no effect on other modes of movement, such as burrow, climb, fly, or swim, but this spell does affect your jumping distance (see the Jump skill, PHB p.77).

PHB p.228}}

 

Feather Fall

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Feather Fall](http://www.dandwiki.com/wiki/SRD:Feather_Fall) }} {{School:=Trans}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V}} {{Cast Time:= 1 free action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= Up to @{selected|casterlevel} Medium or smaller free-falling objects or creatures, no two of which more than 20 ft apart }} {{Dur:= Until landing or [[@{selected|casterlevel}]] round(s)}} {{Save:= Will negates (harmless) or Will negates (object)

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= See full description for more details.

PHB p.229}}

 

Floating Disk

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Floating Disk](http://www.dandwiki.com/wiki/SRD:Floating_Disk) }} {{School:=Evoc [Force]}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= 3-ft-diameter disk of force }} {{Dur:= [[@{selected|casterlevel}]] hour(s)}} {{Save:= None }} {{SR:= No }} {{notes= Creates 3-ft-diameter horizontal disk that holds [[100*@{selected|casterlevel}]]lbs. The disk floats approximately 3 feet above the ground at all times and remains level. It floats along horizontally within spell range and will accompany you at a rate of no more than your normal speed each round. If not otherwise directed, it maintains a constant interval of 5 feet between itself and you.

See full description for more details.

PHB p.294}}

 

Grease

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Grease](http://www.dandwiki.com/wiki/SRD:Grease) }} {{School:=Conj (Creat)}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target or Area:= One object or a 10-ft square }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= See text }} {{SR:= No }} {{notes= A grease spell covers a solid surface with a layer of slippery grease. Any creature in the area when the spell is cast must make a successful Reflex save or fall. This save is repeated on your turn each round that the creature remains within the area. A creature can walk within or through the area of grease at half normal speed with a DC 10 Balance check. Failure means it can't move that round (and must then make a Reflex save or fall), while failure by 5 or more means it falls (see the Balance skill for details).

See full description for more details.

PHB p.237}}

 

Hold Portal

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Hold Portal](http://www.dandwiki.com/wiki/SRD:Hold_Portal) }} {{School:=Abj}} {{Level:= Sor/Wiz 1}} {{Comp:=V}} {{Cast Time:= 1 std action}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Target:= One portal, up to [[20*@{selected|casterlevel} sq ft }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell magically holds shut a door, gate, window, or shutter of wood, metal, or stone. The magic affects the portal just as if it were securely closed and normally locked. A knock spell or a successful dispel magic spell can negate a hold portal spell. For a portal affected by this spell, add 5 to the normal DC for forcing open the portal.

PHB p.241}}

 

Hypnotism

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Hypnotism](http://www.dandwiki.com/wiki/SRD:Hypnotism) }} {{School:=Ench (Comp) [Mind-Aff]}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Area:= Several living creatures, no two of which may be more than 30 ft apart }} {{Dur:= [[2d4]] rounds (D)}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= You fascinate [[2d4]] HD worth of nearby creatures, causing them to stop and stare blankly at you. You can use their rapt attention to make your suggestions and requests seem more plausible. Creatures with fewer HD are affected before creatures with more HD. Only creatures that can see or hear you are affected, but they do not need to understand you to be fascinated.

 

If you use this spell in combat, each target gains a +2 bonus on its saving throw. If the spell affects only a single creature not in combat at the time, the saving throw has a penalty of –2.

See full description for more details.

PHB p.242}}

 

Identify

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Identify](http://www.dandwiki.com/wiki/SRD:Identify) }} {{School:=Div}} {{Level:= Brd 1, Magic 2, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 hour}} {{Range:= Touch }} {{Target:= One touched object }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= No }} {{notes= The spell determines all magic properties of a single magic item, including how to activate those functions (if appropriate), and how many charges are left (if any). Identify does not work on artifacts.

 

Arcane Material Component: A pearl of at least 100 gp value, crushed and stirred into wine with an owl feather; the infusion must be drunk prior to spellcasting.

PHB p.243}}

 

Jump // Thanks to Brian for the Enhancement determination math!

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Jump](http://www.dandwiki.com/wiki/SRD:Jump) on @{target|token_name} }} {{School:=Trans}} {{Level:= Drd 1, Rgr 1, Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{target|token_name} gets a +[[10 + {floor(@{selected|casterlevel} / 5), 1}kl1 * 10 + {floor(@{selected|casterlevel} / 9), 1}kl1 * 10]] enhancement bonus on Jump checks. }} {{notes= PHB p.246}}

 

Mage Armor

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Mage Armor](http://www.dandwiki.com/wiki/SRD:Mage_Armor) on @{target|token_name} }} {{School:=Conj (Creat) [Force]}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] hour(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-conjuration}]]) }} {{SR:= No }} {{notes= An invisible but tangible field of force grants @{target|token_name} a +4 armor bonus to AC.

See full description for more details.

PHB p.249}}

 

Magic Aura

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Magic Aura](http://www.dandwiki.com/wiki/SRD:Magic_Aura) }} {{School:=Ill (Glamer)}} {{Level:= Brd 1, Magic 1, Sor/Wiz 1}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= One touched object weighing up to [[5*@{selected|casterlevel}]]lbs }} {{Dur:= @{selected|casterlevel} days (D)}} {{Save:= None; see text

(DC: [[@{selected|spelldc1} + @{selected|sf-illusion}]]) }} {{SR:= No }} {{check= }} {{checkroll= }} {{notes= You alter an item's aura so that it registers to detect spells as though it were nonmagical, or a magic item of a kind you specify, or the subject of a spell you specify. You could make an ordinary sword register as a +2 vorpal sword as far as magical detection is concerned or make a +2 vorpal sword register as if it were a +1 sword or even a non-magical sword.

See full description for more details.

PHB p.257}}

 

Magic Missile

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Magic Missile](http://www.dandwiki.com/wiki/SRD:Magic_Missile) }} {{School:=Evoc [Force]}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Target:= Up to five creatures, no two of which can be more than 15 ft apart }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{check= [[{5, [[ceil(@{selected|casterlevel}/2)]] }dh1]] missile(s) fly from @{selected|token_name}'s fingers,}} {{checkroll=hitting for [[1d4+1]]|[[1d4+1]]|[[1d4+1]]|[[1d4+1]]|[[1d4+1]] force damage.}} {{notes= See full description for more details.

PHB p.251}}

 

Magic Weapon

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Magic Weapon](http://www.dandwiki.com/wiki/SRD:Magic_Weapon) }} {{School:=Trans}} {{Level:= Clr 1, Pal 1, Sor/Wiz 1, War 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Weapon touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= Will negates (harmless, object)

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless, object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magic weapon gives a weapon a +1 enhancement bonus on attack and damage rolls. (An enhancement bonus does not stack with a masterwork weapon's +1 bonus on attack rolls.)

 

You can't cast this spell on a natural weapon, such as an unarmed strike (instead, see magic fang). A monk's unarmed strike is considered a weapon, and thus it can be enhanced by this spell.

PHB p.251}}

 

Mount

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Mount](http://www.dandwiki.com/wiki/SRD:Mount) }} {{School:=Conj (Summ)}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One mount }} {{Dur:= [[2*@{selected|casterlevel}]] hours (D)}} {{Save:= None }} {{SR:= No }} {{notes= You summon a light horse or a pony (your choice) to serve you as a mount. The steed serves willingly and well. The mount comes with a bit and bridle and a riding saddle.

PHB p.256}}

 

Obscuring Mist

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Obscuring Mist](http://www.dandwiki.com/wiki/SRD:Obscuring_Mist) }} {{School:=Conj (Creat)}} {{Level:= Air 1, Clr 1, Drd 1, Sor/Wiz 1, Water 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 20 ft }} {{Effect:= Cloud spreads in 20-ft radius from you, 20 ft high }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= None }} {{SR:= No }} {{notes= A misty vapor arises around you. It is stationary once created. The vapor obscures all sight, including darkvision, beyond 5 feet. A creature 5 feet away has concealment (attacks have a 20% miss chance). Creatures farther away have total concealment (50% miss chance, and the attacker cannot use sight to locate the target).

See full description for more details.

PHB p.258}}

 

Protection from Chaos

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Chaos](http://www.dandwiki.com/wiki/SRD:Protection_from_Chaos) on @{target|token_name} }} {{School:=Abj [Lawful]}} {{Level:= Clr 1, Law 1, Pal 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by chaotic creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Protection from Evil

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Evil](http://www.dandwiki.com/wiki/SRD:Protection_from_Evil) on @{target|token_name} }} {{School:=Abj [Good]}} {{Level:= Clr 1, Good 1, Pal 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by evil creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Protection from Good

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Good](http://www.dandwiki.com/wiki/SRD:Protection_from_Good) on @{target|token_name} }} {{School:=Abj [Evil]}} {{Level:= Clr 1, Evil 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by good creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Protection from Law

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Law](http://www.dandwiki.com/wiki/SRD:Protection_from_Law) on @{target|token_name} }} {{School:=Abj [Chaotic]}} {{Level:= Chaos 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by lawful creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Ray of Enfeeblement

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Ray of Enfeeblement](http://www.dandwiki.com/wiki/SRD:Ray_of_Enfeeblement) at @{target|token_name} }} {{School:=Necro}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Ray }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= None }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|rangedattackbonus}]] for [[1d6 + {5, [[floor(@{selected|casterlevel}/2)]] }dh1]] point(s) of Strength damage to @{target|token_name}.}} {{notes= The subject's Strength score cannot drop below 1.

PHB p.269}}

 

Reduce Person

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Reduce Person](http://www.dandwiki.com/wiki/SRD:Reduce_Person) on @{target|token_name} }} {{School:=Trans}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One humanoid creature }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Fortitude negates

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= This spell causes instant diminution of a humanoid creature, halving its height, length, and width and dividing its weight by 8. This decrease changes the creature's size category to the next smaller one. The target gains a +2 size bonus to Dexterity, a –2 size penalty to Strength (to a minimum of 1), and a +1 bonus on attack rolls and AC due to its reduced size.

 

A Small humanoid creature whose size decreases to Tiny has a space of 2-1/2 feet and a natural reach of 0 feet (meaning that it must enter an opponent's square to attack). A Large humanoid creature whose size decreases to Medium has a space of 5 feet and a natural reach of 5 feet. This spell doesn't change the target's speed.

See full description for more details.

PHB p.269}}

 

Shield

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Shield](http://www.dandwiki.com/wiki/SRD:Shield) }} {{School:=Abj [Force]}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= Shield creates an invisible, tower shield-sized mobile disk of force that hovers in front of you. It negates magic missile attacks directed at you. The disk also provides a +4 shield bonus to AC. This bonus applies against incorporeal touch attacks, since it is a force effect. The shield has no armor check penalty or arcane spell failure chance. Unlike with a normal tower shield, you can't use the shield spell for cover.

PHB p.278}}

 

Shocking Grasp

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Shocking Grasp]([http://www.dandwiki.com/wiki/SRD:Shocking_Grasp](http://www.dandwiki.com/wiki/SRD:Shocking_Grasp)) }} {{School:=Evoc [Elec]}} {{Level:= Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature or object touched }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|meleeattackbonus}]] for [[ [[{5, @{selected|casterlevel} }dh1]]d6]] point(s) of electricity damage to target.}} {{notes= When delivering the jolt, you gain a +3 bonus on attack rolls if the opponent is wearing metal armor (or made out of metal, carrying a lot of metal, or the like).

PHB p.279}}

 

Silent Image

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Silent Image](http://www.dandwiki.com/wiki/SRD:Silent_Image) }} {{School:=Ill (Figment)}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Long ([[400+40*@{selected|casterlevel}]]ft) }} {{Effect:= Visual figment up to [[4 + @{selected|casterlevel}]] 10-ft cubes (S) }} {{Dur:= Concentration}} {{Save:= Will disbelief (if interacted with)

(DC: [[@{selected|spelldc1} + @{selected|sf-illusion}]]) }} {{SR:= No }} {{notes= Creates the visual illusion of an object, creature, or force, as visualized by you. The illusion does not create sound, smell, texture, or temperature. You can move the image within the limits of the size of the effect.

PHB p.279}}

 

Sleep

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Sleep](http://www.dandwiki.com/wiki/SRD:Sleep) }} {{School:=Ench (Comp) [Mind-Aff]}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 round}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Area:= One or more living creatures within a 10-ft-radius burst }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Causes a magical slumber to come upon 4 Hit Dice of creatures. Creatures with the fewest HD are affected first. Among creatures with equal HD, those who are closest to the spell's point of origin are affected first. Hit Dice that are not sufficient to affect a creature are wasted.

 

Sleeping creatures are helpless. Slapping or wounding awakens an affected creature, but normal noise does not. Awakening a creature is a standard action (an application of the aid another action).

 

Sleep does not target unconscious creatures, constructs, or undead creatures.

PHB p.280}}

 

Summon Monster I

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) }} {{School:=Conj (Summ) [see text]}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One summoned creature }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell summons an extraplanar creature (typically an outsider, elemental, or magical beast native to another plane). It appears where you designate and acts immediately, on your turn. It attacks your opponents to the best of its ability. If you can communicate with the creature, you can direct it not to attack, to attack particular enemies, or to perform other actions. See full description for more detail.

See full description for more details.

PHB p.285}}

 

True Strike

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [True Strike](http://www.dandwiki.com/wiki/SRD:True_Strike) }} {{School:=Div}} {{Level:= Sor/Wiz 1}} {{Comp:=V, F}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= See text}} {{Save:= None }} {{SR:= No }} {{notes= Your next single attack roll (if it is made before the end of the next round) gains a +20 insight bonus. Additionally, you are not affected by the miss chance that applies to attackers trying to strike a concealed target.

PHB p.296}}

 

Unseen Servant

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Unseen Servant](http://www.dandwiki.com/wiki/SRD:Unseen_Servant) }} {{School:=Conj (Creat)}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One invisible, mindless, shapeless servant }} {{Dur:= [[@{selected|casterlevel}]] hour(s)}} {{Save:= None }} {{SR:= No }} {{notes= An unseen servant is an invisible, mindless, shapeless force that performs simple tasks at your command. It has an effective Strength score of 2 (so it can lift 20 pounds or drag 100 pounds). It can trigger traps and such, but it can exert only 20 pounds of force, which is not enough to activate certain pressure plates and other devices. It can't perform any task that requires a skill check with a DC higher than 10 or that requires a check using a skill that can't be used untrained. Its speed is 15 feet.

 

The servant cannot attack in any way; it is never allowed an attack roll. It cannot be killed, but it dissipates if it takes 6 points of damage from area attacks. (It gets no saves against attacks.)

See full description for more details.

PHB p.297}}

 

Ventriloquism

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Ventriloquism](http://www.dandwiki.com/wiki/SRD:Ventriloquism) }} {{School:=Ill (Figment)}} {{Level:= Brd 1, Sor/Wiz 1}} {{Comp:=V, F}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Intelligible sound, usually speech }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will disbelief (if interacted with)

(DC: [[@{selected|spelldc1} + @{selected|sf-illusion}]]) }} {{SR:= No }} {{notes= You can make your voice (or any sound that you can normally make vocally) seem to issue from someplace else, such as from another creature, a statue, from behind a door, down a passage, etc. You can speak in any language you know. With respect to such voices and sounds, anyone who hears the sound and rolls a successful save recognizes it as illusory (but still hears it).

PHB p.298}}

And now some Cleric macros.

Cleric Level 0:[ http://pastebin.com/xgWpsuuq](http://pastebin.com/xgWpsuuq)

Cleric Level 1:[ http://pastebin.com/JBkF4mtT](http://pastebin.com/JBkF4mtT)

## Cleric Spells - Level: 0 ver 20150810

=====================================

 

Create Water

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Create Water](http://www.dandwiki.com/wiki/SRD:Create_Water) }} {{School:=Conj (Creat) [Water]}} {{Level:= Clr 0, Drd 0, Pal 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= Up to [[2*@{selected|casterlevel}]] gallons of water }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= No }} {{check= }} {{checkroll= }} {{notes= Water can be created in an area as small as will actually contain the liquid, or in an area three times as large -- possibly creating a downpour or filling many small receptacles.

 

Note: Water weighs about 8 pounds per gallon. One cubic foot of water contains roughly 8 gallons and weighs about 60 pounds.

PHB p.215}}

 

Cure Minor Wounds

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Cure Minor Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Minor_Wounds) on @{target|token_name} }} {{School:=Conj (Heal)}} {{Level:= Clr 0, Drd 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= Instantaneous}} {{Save:= Will half (harmless); see text

(DC: [[@{selected|spelldc0} + @{selected|sf-conjuration}]]) }} {{SR:= Yes (harmless); see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} heals @{target|token_name} for [[1]] point. }} {{notes= PHB p.216}}

 

Detect Magic

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Magic](http://www.dandwiki.com/wiki/SRD:Detect_Magic) }} {{School:=Div}} {{Level:= Brd 0, Clr 0, Drd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of magical auras.

 

2nd Round: Number of different magical auras and the power of the most potent aura.

 

3rd Round: The strength and location of each aura. If the items or creatures bearing the auras are in line of sight, you can make Spellcraft skill checks to determine the school of magic involved in each. (Make one check per aura; DC 15 + spell level, or 15 + half caster level for a nonspell effect.)

 

Each round, you can turn to detect magic in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.219}}

 

Detect Poison

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Poison](http://www.dandwiki.com/wiki/SRD:Detect_Poison) }} {{School:=Div}} {{Level:= Clr 0, Drd 0, Pal 1, Rgr 1, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target or Area:= One creature, one object, or a 5-ft cube }} {{Dur:= Instantaneous}} {{Save:= None }} {{SR:= No }} {{notes= Tell if a creature, object, or area has been poisoned or is poisonous. You can determine the exact type of poison with a DC 20 Craft (alchemy) check or a DC 20 Wisdom check.

 

The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

PHB p.219}}

 

Guidance

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Guidance](http://www.dandwiki.com/wiki/SRD:Guidance) on @{target|token_name} }} {{School:=Div}} {{Level:= Clr 0, Drd 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= 1 minute or until discharged}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc0} + @{selected|sf-divination}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll=  @{target|token_name} gets a +1 competence bonus on a single attack roll, saving throw, or skill check. @{target|token_name} must choose to use the bonus before making the roll to which it applies.}} {{notes= PHB p.238}}

 

Inflict Minor Wounds

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Inflict Minor Wounds](http://www.dandwiki.com/wiki/SRD:Inflict_Minor_Wounds) }} {{School:=Necro}} {{Level:= Clr 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= Instantaneous}} {{Save:= Will negates

(DC: [[@{selected|spelldc0} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|meleeattackbonus}]] and inflicts [[1]] point of damage.}} {{notes= PHB p.244}}

 

Light

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Light](http://www.dandwiki.com/wiki/SRD:Light) }} {{School:=Evoc [Light]}} {{Level:= Brd 0, Clr 0, Drd 0, Sor/Wiz 0}} {{Comp:=V, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Object touched }} {{Dur:= [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell causes an object to glow like a torch, shedding bright light in a 20-foot-radius (and dim light for an additional 20 feet) from the point you touch.

See full description for more details.

PHB p.248}}

 

Mending

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Mending](http://www.dandwiki.com/wiki/SRD:Mending) }} {{School:=Trans}} {{Level:= Brd 0, Clr 0, Drd 0, Sor/Wiz 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 10 ft }} {{Target:= One object of up to 1 lb }} {{Dur:= Instantaneous}} {{Save:= Will negates (harmless, object)

(DC: [[@{selected|spelldc0} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless, object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Mending repairs small breaks or tears in objects.

See full description for more details.

PHB p.253}}

 

Purify Food and Drink

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Purify Food and Drink](http://www.dandwiki.com/wiki/SRD:Purify_Food_and_Drink) }} {{School:=Trans}} {{Level:= Clr 0, Drd 0}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 10 ft }} {{Target:= [[@{selected|casterlevel}]] cu. ft of contaminated food and water }} {{Dur:= Instantaneous}} {{Save:= Will negates (object)

(DC: [[@{selected|spelldc0} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{check= }} {{checkroll= }} {{notes= This spell makes spoiled, rotten, poisonous, or otherwise contaminated food and water pure and suitable for eating and drinking. Unholy water and similar food and drink of significance is spoiled by purify food and drink, but the spell has no effect on creatures of any type nor upon magic potions.

 

Note: Water weighs about 8 pounds per gallon. One cubic foot of water contains roughly 8 gallons and weighs about 60 pounds.

PHB p.267}}

 

Read Magic

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Read Magic](http://www.dandwiki.com/wiki/SRD:Read_Magic) }} {{School:=Div}} {{Level:= Brd 0, Clr 0, Drd 0, Pal 1, Rgr 1, Sor/Wiz 0}} {{Comp:=V, S, F}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[10*@{selected|casterlevel}]] minutes}} {{Save:= None }} {{SR:= No }} {{notes= You can decipher magical inscriptions that would otherwise be unintelligible. This does not normally invoke the magic contained in the writing, although it may do so in the case of a cursed scroll. You can read at the rate of one page (250 words) per minute. Identify a glyph of warding with a DC 13 Spellcraft check, a greater glyph of warding with a DC 16 Spellcraft check, or any symbol spell with a Spellcraft check (DC 10 + spell level).

See full description for more details.

PHB p.269}}

 

Resistance

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Resistance](http://www.dandwiki.com/wiki/SRD:Resistance) on @{target|token_name} }} {{School:=Abj}} {{Level:= Brd 0, Clr 0, Drd 0, Pal 1, Sor/Wiz 0}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= 1 minute}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc0} + @{selected|sf-abjuration}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= @{target|token_name} gains a +1 resistance bonus on saves.

See full description for more details.

PHB p.272}}

 

Virtue

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Virtue](http://www.dandwiki.com/wiki/SRD:Virtue) on @{target|token_name} }} {{School:=Trans}} {{Level:= Clr 0, Drd 0, Pal 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= 1 minute}} {{Save:= Fortitude negates (harmless)

(DC: [[@{selected|spelldc0} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= @{target|token_name} gains 1 temporary hit point.

PHB p.298}}

## Cleric Spells - Level: 1 ver 20150810

=====================================

 

Bane

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Bane](http://www.dandwiki.com/wiki/SRD:Bane) }} {{School:=Ench (Comp) [Fear, Mind-Aff]}} {{Level:= Clr 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= 50 ft }} {{Area:= All enemies within 50 ft }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Each affected creature takes a –1 penalty on attack rolls and a –1 penalty on saving throws against fear effects.

See full description for more details.

PHB p.203}}

 

Bless

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Bless](http://www.dandwiki.com/wiki/SRD:Bless) }} {{School:=Ench (Comp) [Mind-Aff]}} {{Level:= Clr 1, Pal 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= 50 ft }} {{Area:= The caster and all allies within a 50-ft burst, centered on the caster }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= None }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Each ally gains a +1 morale bonus on attack rolls and on saving throws against fear effects.

See full description for more details.

PHB p.205}}

 

Bless Water

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Bless Water](http://www.dandwiki.com/wiki/SRD:Bless_Water) {{School:=Trans [Good]}} {{Level:= Clr 1, Pal 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 minute}} {{Range:= Touch }} {{Target:= Flask of water touched }} {{Dur:= Instantaneous}} {{Save:= Will negates (object)

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Imbues a flask (1 pint) of water with positive energy, turning it into holy water (see PHB p.128).

 

Material Component: 5 pounds of powdered silver (worth 25 gp).

PHB p.205}}

 

Cause Fear

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Cause Fear](http://www.dandwiki.com/wiki/SRD:Cause_Fear) }} {{School:=Necro [Fear, Mind-Aff]}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One living creature with 5 or fewer HD }} {{Dur:= [[1d4]] rounds or 1 round; see text}} {{Save:= Will partial

(DC: [[@{selected|spelldc1} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Affected creature becomes frightened for the full duration. If the subject succeeds on a Will save, it is just shaken for 1 round. Creatures with 6 or more Hit Dice are immune to this effect.

See full description for more details.

PHB p.208}}

 

Command

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Command](http://www.dandwiki.com/wiki/SRD:Command) }} {{School:=Ench (Comp) [Lang-Dep, Mind-Aff]}} {{Level:= Clr 1}} {{Comp:=V}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= One living creature }} {{Dur:= 1 round}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-enchantment}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= You give the subject a single command, which it obeys to the best of its ability at its earliest opportunity. You may select from the following options.

 

Approach: On its turn, the subject moves toward you as quickly and directly as possible for 1 round. The creature may do nothing but move during its turn, and it provokes attacks of opportunity for this movement as normal.

 

Drop: On its turn, the subject drops whatever it is holding. It can't pick up any dropped item until its next turn.

 

Fall: On its turn, the subject falls to the ground and remains prone for 1 round. It may act normally while prone but takes any appropriate penalties.

 

Flee: On its turn, the subject moves away from you as quickly as possible for 1 round. It may do nothing but move during its turn, and it provokes attacks of opportunity for this movement as normal.

 

Halt: The subject stands in place for 1 round. It may not take any actions but is not considered helpless.

 

If the subject can't carry out your command on its next turn, the spell automatically fails.

PHB p.211}}

 

Comprehend Languages

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Comprehend Languages](http://www.dandwiki.com/wiki/SRD:Comprehend_Languages) {{School:=Div}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[10*@{selected|casterlevel}]] minutes}} {{Save:= None }} {{SR:= No }} {{notes= You can understand the spoken words of creatures or read otherwise incomprehensible written messages. In either case, you must touch the creature or the writing. The ability to read does not necessarily impart insight into the material, merely its literal meaning. The spell enables you to understand or read an unknown language, not speak or write it.

 

Written material can be read at the rate of one page (250 words) per minute. Magical writing cannot be read, though the spell reveals that it is magical, but comprehend languages is often useful when deciphering treasure maps. This spell can be foiled by certain warding magic (such as the secret page and illusory script spells). It does not decipher codes or reveal messages concealed in otherwise normal text.

See full description for more details.

PHB p.212}}

 

Cure Light Wounds

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Cure Light Wounds](http://www.dandwiki.com/wiki/SRD:Cure_Light_Wounds) on @{target|token_name} }} {{School:=Conj (Heal)}} {{Level:= Brd 1, Clr 1, Drd 1, Healing 1, Pal 1, Rgr 2}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= Instantaneous}} {{Save:= Will half (harmless); see text

(DC: [[@{selected|spelldc1} + @{selected|sf-conjuration}]]) }} {{SR:= Yes (harmless); see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} heals @{target|token_name} for [[1d8+{@{selected|casterlevel}, 5}dh1}]] points. }} {{notes= PHB p.215}}

 

Curse Water

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Curse Water](http://www.dandwiki.com/wiki/SRD:Curse_Water) }} {{School:=Necro [Evil]}} {{Level:= Clr 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 minute}} {{Range:= Touch }} {{Target:= Flask of water touched }} {{Dur:= Instantaneous}} {{Save:= Will negates (object)

(DC: [[@{selected|spelldc1} + @{selected|sf-necromancy}]]) }} {{SR:= Yes (object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Imbues a flask (1 pint) of water with negative energy, turning it into unholy water. Unholy water damages good outsiders the way holy water damages undead and evil outsiders (see PHB p.128).

 

Material Component: 5 pounds of powdered silver (worth 25 gp).

PHB p.216}}

 

Deathwatch

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Deathwatch](http://www.dandwiki.com/wiki/SRD:Deathwatch) }} {{School:=Necro [Evil]}} {{Level:= Clr 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 30 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= [[10*@{selected|casterlevel}]] minutes}} {{Save:= None }} {{SR:= No }} {{notes= You instantly know whether each creature within the area is dead, fragile (alive and wounded, with 3 or fewer hit points left), fighting off death (alive with 4 or more hit points), undead, or neither alive nor dead (such as a construct). Deathwatch sees through any spell or ability that allows creatures to feign death.

PHB p.217}}

 

Detect Chaos

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Chaos](http://www.dandwiki.com/wiki/SRD:Detect_Chaos) }} {{School:=Div}} {{Level:= Clr 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of chaos.

 

2nd Round: Number of chaotic auras (creatures, objects, or spells) in the area and the power of the most potent chaotic aura present. If you are of lawful alignment, and the strongest chaotic aura's power is overwhelming (see full text), and the HD or level of the aura's source is at least twice your character level, you are stunned for 1 round and the spell ends.

 

3rd Round: The power and location of each aura. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each round, you can turn to detect chaos in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.218}}

 

Detect Evil

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Evil](http://www.dandwiki.com/wiki/SRD:Detect_Evil) }} {{School:=Div}} {{Level:= Clr 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of evil.

 

2nd Round: Number of evil auras (creatures, objects, or spells) in the area and the power of the most potent evil aura present. If you are of good alignment, and the strongest evil aura's power is overwhelming (see full text), and the HD or level of the aura's source is at least twice your character level, you are stunned for 1 round and the spell ends.

 

3rd Round: The power and location of each aura. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each round, you can turn to detect evil in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.218}}

 

Detect Good

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Good](http://www.dandwiki.com/wiki/SRD:Detect_Good) }} {{School:=Div}} {{Level:= Clr 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of good.

 

2nd Round: Number of good auras (creatures, objects, or spells) in the area and the power of the most potent good aura present. If you are of evil alignment, and the strongest good aura's power is overwhelming (see full text), and the HD or level of the aura's source is at least twice your character level, you are stunned for 1 round and the spell ends.

 

3rd Round: The power and location of each aura. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each round, you can turn to detect good in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.219}}

 

Detect Law

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Law](http://www.dandwiki.com/wiki/SRD:Detect_Law) }} {{School:=Div}} {{Level:= Clr 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of law.

 

2nd Round: Number of lawful auras (creatures, objects, or spells) in the area and the power of the most potent lawful aura present. If you are of chaotic alignment, and the strongest lawful aura's power is overwhelming (see full text), and the HD or level of the aura's source is at least twice your character level, you are stunned for 1 round and the spell ends.

 

3rd Round: The power and location of each aura. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each round, you can turn to detect law in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.219}}

 

Detect Undead

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Detect Undead](http://www.dandwiki.com/wiki/SRD:Detect_Undead) }} {{School:=Div}} {{Level:= Clr 1, Pal 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= 60 ft }} {{Area:= Cone-shaped emanation }} {{Dur:= Concentration, up to [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= 1st Round: Presence or absence of undead auras.

 

2nd Round: Number of undead auras in the area and the strength of the strongest undead aura present. If you are of good alignment, and the strongest undead aura's strength is overwhelming (see full text), and the creature has HD of at least twice your character level, you are stunned for 1 round and the spell ends.

 

3rd Round: The strength and location of each undead aura. If an aura is outside your line of sight, then you discern its direction but not its exact location.

 

Each round, you can turn to detect undead in a new area. The spell can penetrate barriers, but 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt blocks it.

See full description for more details.

PHB p.220}}

 

Divine Favor

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Divine Favor](http://www.dandwiki.com/wiki/SRD:Divine_Favor) }} {{School:=Evoc}} {{Level:= Clr 1, Pal 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= 1 minute}} {{Save:= None }} {{SR:= No }} {{checkroll= @{selected|token_name} gains a +[[{ floor(@{selected|casterlevel}/3), 3}dh1]] luck bonus on attack and weapon damage rolls for 1 minute. }} {{notes= The bonus doesn't apply to spell damage.

PHB p.224}}

 

Doom

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Doom](http://www.dandwiki.com/wiki/SRD:Doom) }} {{School:=Necro [Fear, Mind-Aff]}} {{Level:= Clr 1 }} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Med ([[100+10*@{selected|casterlevel}]]ft) }} {{Target:= One living creature }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= This spell fills a single subject with a feeling of horrible dread that causes it to become shaken.

PHB p.225}}

 

Endure Elements

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Endure Elements](http://www.dandwiki.com/wiki/SRD:Endure_Elements) on @{target|token_name} }} {{School:=Abj}} {{Level:= Clr 1, Drd 1, Pal 1, Rgr 1, Sor/Wiz 1, Sun 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= 24 hours}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= @{target|token_name} can exist comfortably in conditions between –50 and 140 degrees Fahrenheit. Equipment is also protected.

 

Endure elements doesn't provide any protection from fire or cold damage, nor does it protect against other environmental hazards such as smoke, lack of air, and so forth.

PHB p.226}}

 

Entropic Shield

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Entropic Shield](http://www.dandwiki.com/wiki/SRD:Entropic_Shield) }} {{School:=Abj}} {{Level:= Clr 1, Luck 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Personal }} {{Target:= You }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= Glowing magical field deflects incoming arrows, rays, and other ranged attacks. Each ranged attack directed at you for which the attacker must make an attack roll has a 20% miss chance.

PHB p.227}}

 

Hide from Undead

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Hide from Undead](http://www.dandwiki.com/wiki/SRD:Hide_from_Undead) }} {{School:=Abj}} {{Level:= Clr 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Up to @{selected|casterlevel} touched creature(s) }} {{Dur:= [[10*@{selected|casterlevel}]] minutes (D)}} {{Save:= Will negates (harmless); see text

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Undead cannot see, hear, or smell the warded creatures. Even extraordinary or supernatural sensory capabilities, such as blindsense, blindsight, scent, and tremorsense, cannot detect or locate warded creatures. Nonintelligent undead creatures are automatically affected and act as though the warded creatures are not there. An intelligent undead creature gets a single Will saving throw. If it fails, the subject can't see any of the warded creatures. However, if it has reason to believe unseen opponents are present, it can attempt to find or strike them.

 

If a warded creature attempts to turn or command undead, touches an undead creature, or attacks any creature (even with a spell), the spell ends for all recipients.

PHB p.241}}

 

Inflict Light Wounds

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Inflict Light Wounds](http://www.dandwiki.com/wiki/SRD:Inflict_Light_Wounds) }} {{School:=Necro}} {{Level:= Clr 1, Destruction 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= Instantaneous}} {{Save:= Will half

(DC: [[@{selected|spelldc1} + @{selected|sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{checkroll= @{selected|token_name} hits Touch AC [[1d20 + @{selected|meleeattackbonus}]] and inflicts [[1d8+{@{selected|casterlevel}, 5}dh1}]] points of negative energy damage.}} {{notes= PHB p.244}}

 

Magic Stone

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Magic Stone](http://www.dandwiki.com/wiki/SRD:Magic_Stone) }} {{School:=Trans}} {{Level:= Clr 1, Drd 1, Earth 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Up to three pebbles touched }} {{Dur:= 30 minutes or until discharged}} {{Save:= Will negates (harmless, object)

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless, object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= You transmute as many as three pebbles. If hurled, they have a range increment of 20 feet. If slung, treat them as sling bullets (range increment 50 feet). The spell gives them a +1 enhancement bonus on attack and damage rolls.

 

The user of the stones makes a normal ranged attack. Each stone that hits deals 1d6+1 points of damage (including the spell's enhancement bonus), or 2d6+2 points against undead.

PHB p.251}}

 

Magic Weapon

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Magic Weapon](http://www.dandwiki.com/wiki/SRD:Magic_Weapon) }} {{School:=Trans}} {{Level:= Clr 1, Pal 1, Sor/Wiz 1, War 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Weapon touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= Will negates (harmless, object)

(DC: [[@{selected|spelldc1} + @{selected|sf-transmutation}]]) }} {{SR:= Yes (harmless, object) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magic weapon gives a weapon a +1 enhancement bonus on attack and damage rolls. (An enhancement bonus does not stack with a masterwork weapon's +1 bonus on attack rolls.)

 

You can't cast this spell on a natural weapon, such as an unarmed strike (instead, see magic fang). A monk's unarmed strike is considered a weapon, and thus it can be enhanced by this spell.

PHB p.251}}

 

Obscuring Mist

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Obscuring Mist](http://www.dandwiki.com/wiki/SRD:Obscuring_Mist) }} {{School:=Conj (Creat)}} {{Level:= Air 1, Clr 1, Drd 1, Sor/Wiz 1, Water 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= 20 ft }} {{Effect:= Cloud spreads in 20-ft radius from you, 20 ft high }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= None }} {{SR:= No }} {{notes= A misty vapor arises around you. It is stationary once created. The vapor obscures all sight, including darkvision, beyond 5 feet. A creature 5 feet away has concealment (attacks have a 20% miss chance). Creatures farther away have total concealment (50% miss chance, and the attacker cannot use sight to locate the target).

See full description for more details.

PHB p.258}}

 

Protection from Chaos

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Chaos](http://www.dandwiki.com/wiki/SRD:Protection_from_Chaos) on @{target|token_name} }} {{School:=Abj [Lawful]}} {{Level:= Clr 1, Law 1, Pal 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by chaotic creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Protection from Evil

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Evil](http://www.dandwiki.com/wiki/SRD:Protection_from_Evil) on @{target|token_name} }} {{School:=Abj [Good]}} {{Level:= Clr 1, Good 1, Pal 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by evil creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Protection from Good

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Good](http://www.dandwiki.com/wiki/SRD:Protection_from_Good) on @{target|token_name} }} {{School:=Abj [Evil]}} {{Level:= Clr 1, Evil 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by good creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Protection from Law

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Protection from Law](http://www.dandwiki.com/wiki/SRD:Protection_from_Law) on @{target|token_name} }} {{School:=Abj [Chaotic]}} {{Level:= Chaos 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S, M/DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s) (D)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No; see text ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical barrier around the subject at a distance of 1 foot moves with the subject and has three major effects.

 

First, the subject gains a +2 deflection bonus to AC and a +2 resistance bonus on saves. Both these bonuses apply against attacks made or effects created by lawful creatures.

 

Second, the barrier blocks any attempt to possess or control the warded creature.

 

Third, the spell prevents bodily contact (including natural weapons) by summoned creatures. Spell resistance can allow a creature to overcome this protection and touch the warded creature.

See full description for more details.

PHB p.266}}

 

Remove Fear

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Remove Fear](http://www.dandwiki.com/wiki/SRD:Remove_Fear) }} {{School:=Abj}} {{Level:= Brd 1, Clr 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Target:= [[1 + floor(@{selected|casterlevel}/4)]] creatures, no two of which can be more than 30 ft apart }} {{Dur:= 10 minutes; see text}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Subjects gain a +4 morale bonus against fear effects for 10 minutes. If a subject is under the influence of a fear effect when receiving the spell, that effect is suppressed for the duration of the spell.

See full description for more details.

PHB p.271}}

 

Sanctuary

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Sanctuary](http://www.dandwiki.com/wiki/SRD:Sanctuary) on @{target|token_name} }} {{School:=Abj}} {{Level:= Clr 1, Protection 1}} {{Comp:=V, S, DF}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] round(s)}} {{Save:= Will negates

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= No }} {{notes= Any opponent attempting to strike or otherwise directly attack the warded creature must attempt a Will save. If the save succeeds, the opponent can attack normally and is unaffected by that casting of the spell. If the save fails, the opponent can't follow through with the attack, that part of its action is lost, and it can't directly attack the warded creature for the duration of the spell. Those not attempting to attack the subject remain unaffected. This spell does not prevent the warded creature from being attacked or affected by area or effect spells. The subject cannot attack without breaking the spell but may use nonattack spells or otherwise act. This allows a warded cleric to heal wounds, for example, or to cast a bless spell, perform an augury, summon creatures, and so on.

PHB p.274}}

 

Shield of Faith

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Shield of Faith](http://www.dandwiki.com/wiki/SRD:Shield_of_Faith) on @{target|token_name} }} {{School:=Abj}} {{Level:= Clr 1}} {{Comp:=V, S, M}} {{Cast Time:= 1 std action}} {{Range:= Touch }} {{Target:= Creature touched }} {{Dur:= [[@{selected|casterlevel}]] minute(s)}} {{Save:= Will negates (harmless)

(DC: [[@{selected|spelldc1} + @{selected|sf-abjuration}]]) }} {{SR:= Yes (harmless) ([[1d20+@{selected|casterlevel}+@{selected|spellpen}]] vs SR) }} {{notes= Magical field grants @{target|token_name} a +[[{ floor(2 + @{selected|casterlevel}/6), 5}dh1]] deflection bonus to AC.

PHB p.278}}

 

Summon Monster I

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{selected|token_name} }} {{subtags=casts [Summon Monster I](http://www.dandwiki.com/wiki/SRD:Summon_Monster_I) }} {{School:=Conj (Summ) [see text]}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S, F/DF}} {{Cast Time:= 1 round}} {{Range:= Close ([[25+5*floor(@{selected|casterlevel}/2)]]ft) }} {{Effect:= One summoned creature }} {{Dur:= [[@{selected|casterlevel}]] round(s) (D)}} {{Save:= None }} {{SR:= No }} {{notes= This spell summons an extraplanar creature (typically an outsider, elemental, or magical beast native to another plane). It appears where you designate and acts immediately, on your turn. It attacks your opponents to the best of its ability. If you can communicate with the creature, you can direct it not to attack, to attack particular enemies, or to perform other actions.

See full description for more details.

PHB p.285}}

------------------------------------

# Robert D’s Cause Fear Macro:

Cause Fear

&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} casts [Cause Fear]([http://www.dandwiki.com/wiki/SRD:Cause_Fear](http://www.dandwiki.com/wiki/SRD:Cause_Fear)) }}{{Source:=PHB 208}}{{School:=Nec [Fear, Mind Aff]}} {{Level:= Brd 1, Clr 1, Sor/Wiz 1}} {{Comp:=V, S}} {{Cast Time:= 1 std action}} {{Range:= Close ([[25+5*floor(@{casterlevel}/2)]]ft) }}{{Target:= One living creature with 5 or fewer HD }} {{Dur:= [[1d4]] rounds or 1 round, see text}} {{Save:= Will partial(DC: [[@{spelldc1} + @{sf-necromancy}]]) }} {{SR:= Yes ([[1d20+@{casterlevel}+@{spellpen}]] vs SR) }} {{notes=The affected creature becomes frightened. If the subject succeeds on a Will save, it is shaken for 1 round. Creatures with 6 or more Hit Dice are immune to this effect.

*Cause fear *counters and dispels *remove fear*.}}

-----------------------------------

# Devil’s 3e/3.5e hybrid spells:

[https://app.roll20.net/forum/post/4369397/3e-3-dot-5e-dnd-spell-macros-for-3-dot-5e-char-sheet-by-diana-p-dot/?pageforid=4369397#post-4369397](https://app.roll20.net/forum/post/4369397/3e-3-dot-5e-dnd-spell-macros-for-3-dot-5e-char-sheet-by-diana-p-dot/?pageforid=4369397#post-4369397) 

Link to Devil’s Google Docs for his spell list:  [https://docs.google.com/document/d/15l89Rjy9uoal-a9NyDmKFGA7HLH6XSG7DMN3fJPo5WQ/edit](https://docs.google.com/document/d/15l89Rjy9uoal-a9NyDmKFGA7HLH6XSG7DMN3fJPo5WQ/edit) 

-----------------------------------

# Moonpile’s spell macros from the XML SRD:

[https://drive.google.com/drive/folders/1bmN-mECopU-gtdjj3iYNcxKomXIqrP8h](https://drive.google.com/drive/folders/1bmN-mECopU-gtdjj3iYNcxKomXIqrP8h)

From: [https://app.roll20.net/forum/post/6264239/d-and-d-3-dot-5-all-spell-macros](https://app.roll20.net/forum/post/6264239/d-and-d-3-dot-5-all-spell-macros)

-----------------------------------

# Danielle G’s Complete list of Druid Macros:

From: [https://app.roll20.net/forum/post/7170513/3-dot-5e-druid-spell-macros-complete-list](https://app.roll20.net/forum/post/7170513/3-dot-5e-druid-spell-macros-complete-list) 

[https://pastebin.com/d90jb5HD](https://pastebin.com/d90jb5HD) 

-------------------------------------

# MusicManiac’s Spreadsheet of Macros:

[https://docs.google.com/spreadsheets/d/1XXyihH6eviQ7JsVEnBoZrDHVwi6R5mt6nftsR1Mkc58/edit#gid=543880460](https://docs.google.com/spreadsheets/d/1XXyihH6eviQ7JsVEnBoZrDHVwi6R5mt6nftsR1Mkc58/edit#gid=543880460)

From:  [https://app.roll20.net/forum/post/7332011/huge-3-dot-5-char-sheet-macro-list-spells-skills-and-more](https://app.roll20.net/forum/post/7332011/huge-3-dot-5-char-sheet-macro-list-spells-skills-and-more) 

-----------------------------------

# Attack Macro and Calculation variants:

## Andrew’s Attack with Charge and Power Attack:

&{template:DnD35Attack} {{name=@{character_name}}} {{subtags=stabs with the lance from horseback at the @{target|token_name} }} {{pcflag=true}} {{attack1=Attack 1:[[ @{weapon1attackcalc} ]] }} {{critconfirm1=Crit!:[[ @{weapon1attackcalc} ]] }} {{damage1=Damage 1:[[ @{weapon1damage}+@{weapon1damage}+?{Charge}*@{weapon1damage}[Spirited Charge] ]] }} {{critdmg1=+[[ @{weapon1crit}+@{weapon1crit}+?{Charge}*@{weapon1crit}[Spirited Charge] ]] }}

Attack Calc

1d20cs>@{weapon1critmin} +@{bab}[BAB] +@{epicattackbonus}[Epic AB] + @{weapon1stat}[Ability] +@{size}[size] +@{weapon1enh}[Weapon Enh] +@{weapon1focus}[Weapon Focus]+?{Charge|No,0|Yes,1}*2[Charge] + ?{Flank|No,0|Yes,1}*2[Flank] +?{Power Attack (use negative for chosen penalty)|0}[Pwr Attk] +?{Additional Attack Bonus?|0}[Ad'l Atk Bon]

Damage Calc

1d8 + @{weapon1damagestat}[Weapon Dmg Ability] +@{weapon1enh}[Weapon Enh] +@{weapon1specialize}[Weapon Spec] +?{Power Attack (use negative for chosen penalty)}*(-1)[Pwr Attk] +?{Additional Damage Bonus?|0}[Ad'l Dmg Bon]

Crit Calc

[[ (@{weapon1critmult}-1) ]]d6 + [[ (@{weapon1critmult}-1) ]] *( @{weapon1damagestat}[Weapon Dmg Ability] +@{weapon1enh}[Weapon Enh] +@{weapon1specialize}[Weapon Spec] +?{Power Attack (use negative for chosen penalty)}*(-1)[Pwr Attk] +?{Additional Damage Bonus?|0}[Ad'l Dmg Bon])

## Andrew’s Flurry of Blows for Monk: 

From: [https://app.roll20.net/forum/post/4583045/full-attack-macro-for-flurry-of-blows-3-dot-5/?pageforid=4599243#post-4599243](https://app.roll20.net/forum/post/4583045/full-attack-macro-for-flurry-of-blows-3-dot-5/?pageforid=4599243#post-4599243) 

The plan is this...

1) Flurry of Blows functions as its own weapon.  You can use it to call the Unarmed Strike Damage if you want you just change the number in the @{weapon*k*attack}, etc entries.

2) All the Flurry extras all run off the first attack. So load them up in the first attack as extra details.

3) Add the 'usual' extra attacks of the Full Attack at the end as normal. 

*Attack Calc*

1d20cs>@{weapon1critmin} +[[ { [[ [[{0,@{selected|level} }>9]]*[[@{selected|bab}]] ]],[[ [[{9,@{selected|level} }<8)]]*[[@{selected|level}-3]] ]] }kh1 ]][BAB] +@{epicattackbonus}[Epic AB] + @{weapon1stat}[Ability] +@{size}[Size] +@{weapon1enh}[Weapon Enh] +@{weapon1focus}[Weapon Focus] + ?{Flank|No,0|Yes,1}*2[Flank] +?{Power Attack? (put in penalty with negative sign eg -3)|0}[Pwr Attk]+?{Charge|No,0|Yes,2}[Charge] +?{Additional Attack Bonus?|0}[Ad'l Atk Bon]

*Damage Calc*

1d4 + @{weapon1damagestat}[Weapon Dmg Ability] +@{weapon1enh}[Weapon Enh] +@{weapon1specialize}[Weapon Spec] +?{Power Attack? (put in penalty with negative sign eg -3)|0}[Pwr Attk] +?{Additional Damage Bonus?|0}[Ad'l Dmg Bon]

*Full Attack Macro*

&{template:DnD35Attack} {{pcflag=true}} {{name=@{character_name}}} {{subtags=attacks with a @{weapon1name} }} {{attack1=A1: [[@{weapon1attackcalc}]] A2: [[ [[ @{weapon1attackcalc} ]]*({0,@{level} }>8) ]] A3: [[ [[@{weapon1attackcalc}]]*({0,@{level} }>11) ]] A4: [[ [[@{weapon1attackcalc}]]*({0,@{level} }>15) ]] }} {{critconfirm1=Crit?: C1: [[@{weapon1attackcalc}]] C2: [[ [[ @{weapon1attackcalc} ]]*({0,@{level} }>8) ]] C3: [[ ({0,@{level} }>11)*[[@{weapon1attackcalc}]] ]] C4: [[ ({0,@{level} }>15)*[[@{weapon1attackcalc}]] ]] }} {{fumbleroll=Fumble: [[ d20 ]] }} {{damage1= D1: [[ @{weapon1damage} ]] D2: [[ [[ @{weapon1damage} ]]*({0,@{level} }>8) ]] D3: [[ [[@{weapon1damage}]]*({0,@{level} }>11) ]] D4: [[ [[@{weapon1damage}]]*({0,@{level} }>15) ]] }} {{critdmg1= CD1: [[ @{weapon1crit} ]] CD2: [[ [[ @{weapon1crit} ]]*({0,@{level} }>8) ]] CD3: [[ [[@{weapon1crit}]]*({0,@{level} }>11) ]] CD4: [[ [[@{weapon1crit}]]*({0,@{level} }>15) ]] }} {{fullattackflag= [[ ?{Full Attack?|No, 0d1|Yes, d1} ]] }} {{attack2=A5: [[ @{weapon1attackcalc}-5 ]] }} {{critconfirm2=Crit!: C5: [[ @{weapon1attackcalc}-5 ]] }} {{damage2=D5: [[ @{weapon1damage} ]] }} {{critdmg2= CD5: [[ @{weapon1crit} ]] }} {{attack3=A6: [[ @{weapon1attackcalc}-10 ]] }} {{critconfirm3=Crit! C6: [[ @{weapon1attackcalc}-10 ]] }} {{damage3=D6: [[ @{weapon1damage} ]] }} {{critdmg3= CD6: [[ @{weapon1crit} ]] }}

-----------------------------------

# Christopher B’s Maneuver Macro:

From: [https://app.roll20.net/forum/post/7024828/maneuver-macro#post-7032989](https://app.roll20.net/forum/post/7024828/maneuver-macro#post-7032989)

&{template:DnD35StdRoll}{{name=@{selected|character_name} }} {{pcflag=true}} ?{Which maneuver?

|Bull Rush ,{{subtags=tries to bullrush @{target|token_name} &#125;&#125;

{{Bull Rush: [[ 1d20 + @{selected|str-mod} [Ability] + ?{Improved Bull Rush? (1=yes)&#124;0&#125;*4 [Imp. Bull Rush] + ?{Charging? (1=yes)&#124;0&#125;*2 [Charge] ]] &#125;&#125;

{{notes=To beat Bull Rush: [[ 1d20 + @{target|str-mod} [Ability] + ?{Is opponent a dwarf or have more than two legs? (1=yes)&#124;0&#125;*4 [Stability] ]] &#125;&#125;

|Disarm ,{{subtags=tries to disarm @{target|token_name} &#125;&#125;

{{Disarm: [[ 1d20 + @{selected|bab} [BAB] + @{selected|str-mod} [Ability] + @{selected|size} [Size] - ?{Light Weapon? (1=yes)&#124;0&#125;*4 [Light Weapon] + ?{Two-handed Weapon? (1=yes)&#124;0&#125;*4 [Two-handed Weapon] + ?{Improved Disarm? (1=yes)&#124;0&#125;*4 [Imp. Disarm] ]] &#125;&#125;

{{notes=To beat Disarm [[ 1d20 + @{target|bab} [BAB] + @{selected|str-mod} [Ability] + @{selected|size} [Size] - ?{Opponent Light Weapon? (1=yes)&#124;0&#125;*4 [Light Weapon] + ?{Opponent Two-handed Weapon? (1=yes)&#124;0&#125;*4 [Two-handed Weapon] ]] &#125;&#125;

|Feint ,{{subtags=tries to feint @{target|token_name} &#125;&#125;

{{Bluff Check: [[ 1d20 + @{selected|bluff} [Bluff] - ?{Nonhumanoid? (1=yes)&#124;0&#125;*4 [Type] ]] &#125;&#125;

{{notes=To beat Sense Motive: [[ 1d20 + @{target|sensemotive} [Sense Motive] ]] &#125;&#125;

|Grapple ,{{subtags=grapples with @{target|token_name} &#125;&#125;

{{Grapple check: [[ 1d20 + @{selected|bab} [BAB] + @{selected|strmod} [Str Mod] + @{selected|size} [Size] + @{selected|grapplemiscmod} [Misc Mod] + @{selected|npcgrapple} [NPC Grapple Mod] ]] &#125;&#125;

{{notes=To beat Grapple check [[ 1d20 + @{target|bab} [BAB] + @{target|strmod} [Str Mod] + @{target|Size} [Size] + @{target|grapplemiscmod} [Misc Mod] + @{target|npcgrapple} [NPC Grapple Mod] ]] &#125;&#125;

|Sunder ,{{subtags=tries to Sunder @{target|token_name}'s weapon &#125;&#125;

{{Sunder: [[ 1d20 + @{selected|bab} [BAB] + @{selected|str-mod} [Ability] + @{selected|size} [Size] - ?{Light Weapon? (1=yes)&#124;0&#125;*4 [Light Weapon] + ?{Two-handed Weapon? (1=yes)&#124;0&#125;*4 [Two-handed Weapon] + ?{Improved Sunder? (1=yes)&#124;0&#125;*4 [Imp. Sunder] ]] &#125;&#125;

{{notes=To beat Sunder [[ 1d20 + @{target|bab} [BAB] + @{selected|str-mod} [Ability] + @{selected|size} [Size] - ?{Opponent Light Weapon? (1=yes)&#124;0&#125;*4 [Light Weapon] + ?{Opponent Two-handed Weapon? (1=yes)&#124;0&#125;*4 [Two-handed Weapon] ]] &#125;&#125;

|Trip ,{{subtags=tries to trip @{target|token_name} &#125;&#125;

{{Touch attack [[ 1d20 + @{selected|bab} [BAB] + @{selected|str-mod} [Str Mod] + @{selected|size} [Size Mod] + @{selected|npcstr-mod} [NPC Grapple Mod] ]] &#125;&#125;

{{Strength check: [[ 1d20 + @{selected|str-mod} [Ability] + ?{Improved Trip? (1=yes)&#124;0&#125;*4 ]] &#125;&#125;

{{notes=To beat Strength check [[ 1d20 + @{target|str-mod} [Ability] ]] &#125;&#125;

}

-------------------------------------

# Other Things:

## DtotheP’s Macro Maker:

[http://www.theparkside.net/mmm/index.php](http://www.theparkside.net/mmm/index.php) 

## ørjan s.’ Spell Macro Maker: 

(from: [Roll20 Forum Post](https://app.roll20.net/forum/post/2630375/sharing-a-spell-macro-maker-for-d-and-d-3-dot-5-character-sheet/?pageforid=2630375#post-2630375) )

[https://www.dropbox.com/s/5wooj6g5wsoouo2/Makro%20Lager%20v2.xls?dl=0](https://www.dropbox.com/s/5wooj6g5wsoouo2/Makro%20Lager%20v2.xls?dl=0) 

## DMokun’s PCGen Spell Macro Generator:

[https://app.roll20.net/forum/post/3656037/3-dot-5e-generating-spell-roll-macros-with-pcgen](https://app.roll20.net/forum/post/3656037/3-dot-5e-generating-spell-roll-macros-with-pcgen) 

## Adnan’s Spell Macro Generator:

[https://app.roll20.net/forum/post/5185431/3-dot-5-i-made-a-roll20-spell-macro-generator](https://app.roll20.net/forum/post/5185431/3-dot-5-i-made-a-roll20-spell-macro-generator)

## Ziechael’s Powercard Generator (with SRD Spells setup):

[https://docs.google.com/spreadsheets/d/1sE0AoSwsNopcOkCsPJA5go2mJgl3bT3v522S3QRdHH4/edit#gid=808637055](https://docs.google.com/spreadsheets/d/1sE0AoSwsNopcOkCsPJA5go2mJgl3bT3v522S3QRdHH4/edit#gid=808637055) 

Note that Powercards requires the Powercards API and a Pro Subscription.  

(from: [https://app.roll20.net/forum/post/6325444/who-uses-macros-and-abilities/?pageforid=6327985#post-6327985](https://app.roll20.net/forum/post/6325444/who-uses-macros-and-abilities/?pageforid=6327985#post-6327985) )

-------------------------------------------------

Created and Collected by Diana P.  (last updated March 2019)

