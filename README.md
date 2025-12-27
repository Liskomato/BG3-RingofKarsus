No Illithids or Orb Required for Ending - A Baldur's Gate 3 mod by Liskomato
=======
Inspired by the **No Mindflayers Needed To Defeat the Absolute** mod from Nexus, maintained by *FirmDesigns* and *SetFiresUP*.


# Features:
### SPOILERS FOR ACT 3 AND THE END OF THE GAME!

<br><br><br><br><br><br><br><br><br><br><br><br>

This mod allows you to skip the mind flayer requirement for the endgame, allowing you to proceed past the Astral Prism after the events at the Morphic Pool without anyone undergoing ceremorphosis, provided you have the required buff and/or item with you along with the Orphic Hammer. 

There are **two** ways to get the **Unbreakable Will** passive needed to cast Karsus' Compulsion without ceremorphosis:

1. Destroy the Astral-Touched Tadpole while not having **any** illithid powers at all.
    - *(Make sure you have the Astral Tadpole still available to use when loading this mod in a save for the first time.)*
2. Obtain the Ring of Karsus from Karsus' vault in Sorcerous Sundries. It is located in the invisible chest that contains the Foebreaker weapon.
    - *(You need to install the mod before you enter Lower City for the first time for this to work.)*  

Once you have the passive, when you liberate Orpheus, a Supreme Tadpole is temporarily added to your inventory during your conversation with the Prince of the Comet. Agree to bear the burden of transforming yourself, and you should be able to proceed without anyone transforming to a mind flayer, even if some cutscenes treat you as having done so. After Orpheus departs in the aftermath of destroying the Netherbrain, the game proceeds as normal in an ending where you didn't become a mind flayer.



## FAQ

### Wait what? Why create this mod?

It has been a long-time complaint among Baldur's Gate 3 fans that you can't truly earn a happy or a "golden" (meaning best-case scenario) ending where none of the major characters dies or succumbs to ceremorphosis. The components are there, but someone has always had to bite the figurative bullet in order to truly control the Netherstones and dominate the elder brain.

Sure, there are hoops where you can get to the High Hall itself by being gifted the "Supreme Tadpole" from the Emperor, but then immediately betraying him and using the Orphic Hammer to free Orpheus afterwards, but even in the best-case scenario there, you'd need Gale to blow himself and the Netherbrain up with his orb to truly get a mind flayerless ending. You survived, but at what cost to your dear wizard of Waterdeep?

Hence why this mod's name is "No Illithids **or Orb** Required for Ending".

### What is the Supreme Tadpole? Why have I never heard of it before?

The Supreme Tadpole is actually a vanilla item, believe it or not! It is how the Emperor can transform you into a mind flayer for the final battle, if you tell him that you want to transform so you can control the Netherstones yourself. He will offer it to you right before he moves to assimilate Orpheus, and you can tell him that you will use it later. If you attack him immediately afterwards or side with Lae'zel on her Orpheus path in her interrupting dialogue, you will actually keep the tadpole for yourself even though the Emperor leaves you, and can decide whether to liberate Orpheus (with the Orphic Hammer) or to consume him yourself (the only option to proceed if you don't have the hammer).

If you liberate Orpheus with the tadpole in your inventory, you can delay transformation all the way up to reaching the Crown itself atop the Netherbrain by telling Orpheus that you will become the mind flayer. He will know that you have the means to do it, sees you as a mind flayer for a second (either because of a visual bug or because he hallucinates), and then opens the portal for you.

If you instead decide Karlach or Orpheus should be the mind flayer instead, you will see an unique animation where you hand over the tadpole to them immediately, or get told off by Orpheus if you happened to drop it for any reason.

In case of how this mod interacts with this item, if you liberate Orpheus with the Unbreakable Will passive earned but not having grabbed the tadpole from the Emperor, this mod will spawn it in your inventory temporarily to let Orpheus proceed in his dialogue as if you had it that way. Once the portal to the High Hall is open, this temporary tadpole is then removed from your inventory for good, allowing you to proceed as normal.

### Any edge-cases I should be aware of? What if I still wanted to be a mind flayer while freeing Orpheus?

There is in fact one scenario where you will still automatically transform even with the supreme tadpole in your inventory. If you initially refuse to become a mind flayer and you have Karlach in your party, she will offer herself to be the mind flayer instead. If you decide there to be the mind flayer instead of Karlach, Orpheus' dialogue path assumes without question that you have no special tadpole, and he lowers his defenses to do the transformation the Netherbrain way (which is how it normally should go in this scenario).

If this isn't what you want, tell Karlach "neither of us will become mind flayers, not now", then Orpheus will go on the dialogue path where he offers himself, which is where you should intervene and then offer to become mind flayer instead. This will then set the dialogue path where it normally goes if you offer yourself as the mind flayer immediately, which is where the supreme tadpole-specific dialogue path enters the picture, truncating what would normally be the ceremorphosis scene for you into the shorter, delayed version.

This same scenario happens even in a vanilla game where you took the supreme tadpole from the Emperor and liberated Orpheus afterwards, so keep this in mind if you wanted to try that path yourself. I haven't altered any dialogue files of the game directly with this mod, most of the work has been done in the Flag and Story editors of the official Baldur's Gate 3 toolkit.

### When is the best time for me to install this mod?

Ideally, any time before you reach Act 3. If you have already used the Astral Tadpole or destroyed it before you installed the mod, it has no way of knowing about it, and thus it can't grant you the Unbreakable Will buff afterwards.

Likewise, if you've already been to Lower City as you installed this mod, the loot tables for that area will already have been generated, and thus the Ring of Karsus will not be available as this mod is the one to add it to the Karsus Vault loot table in the first place.

### How does this mod work under the hood?
This mod is primarily an Osiris script mod. No dialogue files found within the game have been altered, but four new flags have been added which alter some behaviour around certain dialog scenes. The mod also adds one new item template to an existing loot table, which sets one of the newly added flags if you add it to your inventory.


### If you have any questions or have bugs to report, please tell me about them as soon as you can!

I will do my best to fix any bugs you or I might come across with this mod. I haven't had the chance to test this mod in every possible scenario (including multiplayer)
# Releases
* [mod.io](https://mod.io/g/baldursgate3/m/no-illithids-or-orb-required-for-ending) 
* ~~Nexus (TBD)~~

# Attribution
- [Baldur's Gate 3](https://store.steampowered.com/app/1086940/Baldurs_Gate_3/), a game by [Larian Studios](http://larian.com/)
- [No Mindflayers Needed to Defeat the Absolute](https://www.nexusmods.com/baldursgate3/mods/3118), the original mod by FirmDesigns that inspired this current mod in the first place.
- Your Friend the Dragon, a good friend of mine whose playthrough of BG3 with me helped inspire the creation of this mod.
- BG3 Modding / Moonglasses discord for helping out in figuring out some bits with this mod.
