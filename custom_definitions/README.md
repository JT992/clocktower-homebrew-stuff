# Custom Definitions

Custom characters that I've created for my games. Icons for these characters can be found in the `icons` directory.

## Townsfolk

### Detective

"Each night, choose two living players (not yourself or Travellers): learn one of their character types. If both are Townsfolk, you are drunk until dawn. If you have selected players from all in-play character types, lose this ability."

The Detective can identify people with something to hide, but is paranoid about people who don't.

- The Detective learns the character type of one of the people they investigate.
- If both of the people they select are Townsfolk, they are made drunk, so (probably) learn something other than Townsfolk.
- Once the Detective has selected players from all different types, they no longer wake up to use their ability.

#### Examples

> On the first night, the **Detective** chooses Oli, the [**Mezepheles**](https://wiki.bloodontheclocktower.com/Mezepheles),
> and Ewan, the [**Shugenja**](https://wiki.bloodontheclocktower.com/Shugenja). They learn that one is a Minion.
> The next night, they choose Mimi, the [**No Dashii**](https://wiki.bloodontheclocktower.com/No_Dashii),
> and El, the [**Moonchild**](https://wiki.bloodontheclocktower.com/Moonchild). They learn that one is a Outsider.
> The **Detective** does not wake up on any further nights, as they have selected a Townsfolk, Outsider, Minion and Demon.

> The Detective selects the [**Ravenkeeper**](https://wiki.bloodontheclocktower.com/Ravenkeeper) and
> [**Undertaker**](https://wiki.bloodontheclocktower.com/Undertaker). Both are Townsfolk, so the **Detective** is drunk
> and learns (incorrectly) that one is a Demon.

> It is the fourth night. So far, the Detective has learnt Outsider, Demon, Minion.
> The Detective still wakes up, because they have chosen three Townsfolk.

### Augur

"Each night, choose two non-Demon characters: learn if at least one is in play."

The Augur can determine the existence of characters in the game.

- The Augur learns if either or both of the characters they choose are in play.
- The Augur is not allowed to choose Demon characters.

#### Examples

> On the first night, the **Augur** chooses the [**Shugenja**](https://wiki.bloodontheclocktower.com/Shugenja)
> and the [**Moonchild**](https://wiki.bloodontheclocktower.com/Moonchild).
> They learn Yes, because there is a **Moonchild**.

> On the third night, the **Augur** chooses the [**Vigormortis**](https://wiki.bloodontheclocktower.com/Vigormortis)
> as one of their picks. The Storyteller shakes their head to prompt them to choose someone else,
> because the **Augur** cannot choose Demon characters.

### Haruspex

**THIS CHARACTER HAS NOT BEEN TESTED!** The Haruspex's ability needs some serious balancing before it's ready to work.

"Each night, if at least a third of the players are dead, choose a dead player: perform that character's night action (without affecting the board). If they are evil, you are poisoned until dawn."

The Haruspex receives visions of the dead players they investigate.

- If at least a third (rounded UP) of players are dead, the Haruspex chooses a dead player.
- The Haruspex doesn't "gain the ability", they simply learn information about what that player would have done/learnt.
- If the player they choose is evil, they are poisoned, so the action they perform is arbitrary.

#### Examples

> On the first night, the [**Investigator**](https://wiki.bloodontheclocktower.com/Investigator)
> correctly learns that either Oli or Ewan is the [**Cerenovus**](https://wiki.bloodontheclocktower.com/Cerenovus).
> Later in the game, the **Haruspex** chooses the (now dead) **Investigator** player. The Haruspex learns
> "Amy, Elle, [**Organ Grinder**](https://wiki.bloodontheclocktower.com/Organ_Grinder)".
> Neither Amy nor Elle are the **Organ Grinder** (who is not-in-play):
> the Haruspex has just learnt "plausible" information for the role they chose.

> The **Haruspex** chooses the dead [**Mezepheles**](https://wiki.bloodontheclocktower.com/Mezepheles) and so is poisoned.
> The Mezepheles was bluffing [**Dreamer**](https://wiki.bloodontheclocktower.com/Dreamer),
> so the Storyteller decides to prompt the Haruspex to choose a player and then tells them a good and evil role.

### Necromancer

"Once per game, at night, if at least a quarter of the players are dead, choose a dead player: if they are good, you die and they become a living (and possibly evil) Necromancer."

The Necromancer can revive good players, at the cost of their own life... and (possibly) the chosen player's conscience.

- If at least a quarter (rounded UP) of players are dead, the Necromancer can choose a dead player.
- If the player they choose is good, the old Necromancer dies and the chosen player becomes a living Necromancer.
- If this happens, the selected player's alignment may also switch to evil.

#### Examples

> The **Necromancer** uses their ability on the first night they can.
> They choose Corry, the dead [**Artist**](https://wiki.bloodontheclocktower.com/Artist).
> The original Necromancer dies, because Corry is good. Corry becomes a living evil Necromancer.
> The night after, Corry chooses Robin, the [**Clockmaker**](https://wiki.bloodontheclocktower.com/Clockmaker).
> Corry dies, and Robin becomes a living good Necromancer.

> The **Necromancer** chooses the [**Poisoner**](https://wiki.bloodontheclocktower.com/Poisoner) player.
> This player is evil, so nothing happens. The Necromancer loses their ability.

## Outsiders

### Blabbermouth

"Each night, choose a living player (not yourself): until dusk, any true info they learn is false, and any false info they learn is true."

The Blabbermouth flips true info and false info.

- If the Blabbermouth chooses someone who should learn true info, they instead learn something false.
- If they choose someone who should learn false info, they instead learn something true.
- Like the [**Vortox**](https://wiki.bloodontheclocktower.com/Vortox), drunk or poisoned players chosen by the Blabbermouth must still learn false info.

#### Examples

> On the first night, the **Blabbermouth** selects Robin, the [**Empath**](https://wiki.bloodontheclocktower.com/Empath).
> Robin is sat next to two evil players, but his information is now false, so he learns a 1.

> There is a [**Vortox**](https://wiki.bloodontheclocktower.com/Vortox) in play, so all Townsfolk information is false.
> The [**Barista**](https://wiki.bloodontheclocktower.com/Barista)'s ability targets the [**Undertaker**](https://wiki.bloodontheclocktower.com/Undertaker), so tonight they will instead learn true info.
> However, the **Blabbermouth** then selects the **Undertaker** player, so they will now learn false info.

## Minions

### Chatterbox

"Each night, choose a player: tomorrow, if they're mad that something false is true, they might die in the night."

The Chatterbox kills players who lie.

- A Chatterbox death, like a [Harpy](https://wiki.bloodontheclocktower.com/Harpy) death, occurs during the night, so is not an execution.
- A player chosen by the Chatterbox does not learn that they have been chosen.

#### Examples

> On the first, second, and third night, the **Chatterbox** selects Corry, the [**Chef**](https://wiki.bloodontheclocktower.com/Chef), who learns that there is one pair of evil players.
> During the first day, Corry does not claim any characters and does not share any information. They have not lied, so do not die that night.
> During the second day, they say they are either the [**Chambermaid**](https://wiki.bloodontheclocktower.com/Chambermaid), the **Chef**, or the [**Noble**](https://wiki.bloodontheclocktower.com/Noble). This is true (they are the **Chef**), so they do not die that night.
> During the third day, they hard-claim the **Noble**. This is false, so tonight they might die.

> The **Chatterbox** selects the [**Town Crier**](https://wiki.bloodontheclocktower.com/Town_Crier) player, who is drunk.
> The **Town Crier** learns Yes, even though no Minions nominated today.
> During the day, the **Town Crier** says they learnt Yes. This is true, so they don't die tonight.
> If the **Town Crier** said that a Minion nominated last night, they would be lying, so they might have died in the night.

## Demons

### Sleeper

"You think you are a good character who chooses someone each night, but you are not. Each night\*, one player you choose (not yourself) dies. All Minions know you are the Sleeper."

The Sleeper doesn't know that they are the Demon.

- The Sleeper draws a Townsfolk or Outsider that chooses players or characters in the night, but they are actually the Sleeper.
- After the first night, one of the players the Sleeper selects each night using the good ability they think they have dies.
- The Sleeper cannot die to their own ability.
- All Minions learn who the Sleeper is, and that they are the Sleeper.
- The Sleeper does not wake to learn the Minions or bluffs.
- The good ability the Sleeper thinks they have does not work, much like the Drunk or Marionette.
- The Sleeper registers as evil and as the Sleeper.

#### Optional rules

- One Minion can receive the Demon bluffs instead of the Sleeper.

#### Examples

> Oli is the **Sleeper** who drew the [**Chambermaid**](https://wiki.bloodontheclocktower.com/Chambermaid) token.
> On the first night, he chooses two players, and learns information that may or may not be correct.
> On each subsequent night, the same happens, but one of the players he chooses dies.

> The **Sleeper** draws the [**Gambler**](https://wiki.bloodontheclocktower.com/Gambler) token.
> On the second night, they "gamble" Fin as the [**Cannibal**](https://wiki.bloodontheclocktower.com/Cannibal),
> so either Fin or the **Cannibal** player dies tonight.

> The **Sleeper** draws the [**Snake Charmer**](https://wiki.bloodontheclocktower.com/Snake_Charmer) token.
> On the fourth night, they decide to "snake charm" themselves.
> No-one dies, because the Sleeper cannot attack themselves in this way.

## Fabled

### Editor

"When a player leaves the game, the Storyteller gains their ability until they die."

Use the Editor in a Teensyville game where some players have to travel, but doing so would be too powerful for the good team.

- The Storyteller "gaining the ability" works similarly to the [Plague Doctor](https://wiki.bloodontheclocktower.com/Plague_Doctor)
  in that they don't become the alignment of the player who left, they don't become a player who can be
  targeted by abilities, and they cannot vote or nominate.
- The player who left does not die.
- If the player who left dies, the Storyteller loses their ability.
- In order to execute the player who left, the other players nominate _them_, not the Storyteller.

#### Examples

> On the first day of a five-player game, Jeremy (the [**Cerenovus**](https://wiki.bloodontheclocktower.com/Cerenovus)) has to leave. Each night afterwards,
> the Storyteller chooses someone to be mad using the **Cerenovus**' ability.

> The [**Virgin**](https://wiki.bloodontheclocktower.com/Virgin) (who is yet to be nominated) leaves. The next day, a Townsfolk nominates
> the **Virgin** and dies.

> The [**Vortox**](https://wiki.bloodontheclocktower.com/Vortox) leaves. Each night afterwards, the Storyteller chooses a player to die, and gives
> false info to all Townsfolk. On the final day, the **Vortox** is executed. Good wins.

#### Explanation

A five-player game with a Traveller is too powerful for the good team, since that Traveller is
basically guaranteed to be good, and the number of players who can be the Demon is now four instead of five.

With an Editor in play, every player can have a normal character's ability (including being the Demon!)
without worring if leaving will guarantee a loss or the use of the [Fiddler](https://wiki.bloodontheclocktower.com/Fiddler).
