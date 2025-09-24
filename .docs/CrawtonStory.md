# Notes for the Crawton plot

## Option A: The Marbrands

### 258 AC - Setting the Scene

Eyron Crawton (Crawton001) is baron of Crawton Castle (b_goldburn). He is sworn to Lord Joffrey (Pendrick_54) of Pendric Hills (c_pendric_hills).

Lord Alyn (Marbrand_50) of Ashemark (d_ashemark) is a neighboring ruler. His daughter, Jeyne (Marbrand_51), was the mother of Tywin Lannister. She died while giving birth to her fifth child, Gerion Lannister.

The children of Lord Bermond Bettley (Bettley_1) and the late Sharra Pendric (Pendric_52), Othell (Bettley_2) and Jon (Bettley_3) have claims to the county.

Lord Alyn wants to install one of the Bettley children as Lord, but waits for the right opportunity.

Both Alyn and his son, Denys (Marbrand_52) died in 255 (wiki) or 260 (mod = 8260.1.18) when trying to arrest Walderan Tarbeck (Tarbeck_27). Ashemark is inherited by Denys' son, Damon (Marbrand_1), who is 18 years old at the time. He has a younger brother, Addison, who becomes an adventurer in the mod. He will also have a son, Addam (Marbrand_4), who is also a canon character and heavily featured in the books.

### 261 AC - The Revolt

Eyron and Lord Joffrey support his liege Lord Roger Reyne in the rebellion. When the rebels are executed and their lands taken, Pendric Hills is given to 7-year-old Jon (Bettley_3), who swears fealty to Lord Damon. Eyron's son Armand flees to the Vale. Crawton Castle is ruined.

The other lords:
* Castamere is taken by the Lannisters.
* The Lowells stay in power.
* The Lenders of Borrowmore become vassals of the Lannisters.
* The Sarsfields stay in power.

### 273 AC - The Kidnapping

House Marband or some agents associated with them kidnap Armond Crawton's (Crawton002) children, Seamus (Crawton003) and Torrhen (Crawton004). They are returned after their father pays a heavy ransom.

Maybe it was Addison? He is 23 years old at the time and an adventurer. His brigade is known as "Knights of Marbrand" (d_laamp_Marbrand_66).

### 277 AC - The Defiance of Duskendale

Cerelle dies.

### 282 AC - Robert's Rebellion

The brothers fight alongside Jon Arryn in the siege of Gulltown.

### 290 AC - Tourney at Runestone

There was some sort of a scandal involving the Crawton brothers. Maybe it had something to do with their Rival, Addison Marbrand?

## Option B: The Baneforts
as
This is less intrusive because the mod already grants Pendric Hills to the Baneforts in 261.

Characters:
* Lord Sebaston (Banefort_34), dies in 260
* Ser Baldick (Banefort_105), his brother, dies in 286 --> could be pulling the strings for the kidnapping?
* Lord Symond (Banefort_3), Sebaston's only child, dies in 276
* Lord Quenten (Banefort_1), born in 264

## Technical notes

House feud is handled by the "agot_house_feuds" on_action, which triggers the "agot_events_generic.0003" hidden event, which in turn uses the "house_feud_start_effect".

To be checked:
* "house_feud_story_modifier"
* "story_cycle_house_feud"
* "house_feud_reason"
* "house_feud_memory_effect"
* "ongoing_house_feud_events"