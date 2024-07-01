# Custom Definitions

Custom characters that I've created for my games. Icons for these characters can be found in the `icons` directory.

## Townsfolk

### Detective

"Each night, choose a player (not yourself): learn their character type. If they are a Townsfolk, you are drunk until dawn. If you have selected players from three different character types, lose this ability."

The Detective can identify people with something to hide, but is paranoid about people who don't.

- If the (sober and healthy) Detective selects an Outsider, Minion, or Demon, they correctly learn that player's character type.
- If they choose a Townsfolk, they are made drunk, so (probably) learn something other than Townsfolk.
- Once the Detective has selected players from three different types, they no longer wake up to use their ability.

#### Examples

> On the first night, the **Detective** chooses Oli, the **Mezepheles**, and learns that he is a Minion.
> The next night, they choose Ewan, the **Shugenja**, and learns (incorrectly) that he is a Demon.
> The next night, they choose Mimi, the **No Dashii**, and learns that she is a Demon.
> The **Detective** does not wake up on any further nights, as they have selected a Minion, a Townsfolk, and a Demon.

> It is the fourth night. So far, the Detective has learnt Outsider, Demon, Minion.
> The Detective still wakes up, because they have chosen three Townsfolk.

## Outsiders

### Blabbermouth

"Each night, choose a living player (not yourself): until dusk, any true info they learn is false, and any false info they learn is true."

The Blabbermouth flips true info and false info.

- If the Blabbermouth chooses someone who should learn true info, they instead learn something false.
- If they choose someone who should learn false info, they instead learn something true.
- If they choose someone drunk or poisoned, the Storyteller can decide (as usual).

#### Examples

> On the first night, the **Blabbermouth** selects Robin, the **Empath**.
> Robin is sat next to two evil players, but his information is now false, so he learns a 1.

> There is a **Vortox** in play, so all Townsfolk information is false.
> The **Barista**'s ability targets the **Undertaker**, so tonight they will instead learn true info.
> However, the **Blabbermouth** then selects the **Undertaker** player, so they will now learn false info.

## Minions

### Chatterbox

"Each night, choose a player: tomorrow, if they're mad that something false is true, they might die in the night."

The Chatterbox kills players who lie.

- A Chatterbox death, like a Harpy death, occurs during the night, so is not an execution.
- A player chosen by the Chatterbox does not learn that they have been chosen.

#### Examples

> On the first, second, and third night, the **Chatterbox** selects Corry, the **Chef**, who learns that there is one pair of evil players.
> During the first day, Corry does not claim any characters and does not share any information. They have not lied, so do not die that night.
> During the second day, they say they are either the **Chambermaid**, the **Chef**, or the **Noble**. This is true (they are the Chef), so they do not die that night.
> During the third day, they hard-claim the **Noble**. This is false, so tonight they might die.

## Fabled

### Editor

"When a player leaves the game, the Storyteller gains their ability until they die."

Use the Editor in a Teensyville game where some players have to travel, but doing so would be too powerful for the good team.

- The Storyteller "gaining the ability" works similarly to the **Plague Doctor** in that they don't
  become the alignment of the player who left, they don't become a player who can be targeted by abilities,
  and they cannot vote or nominate.
- The player who left does not die.
- If the player who left dies, the Storyteller loses their ability.
- In order to execute the player who left, the other players nominate _them_, not the Storyteller.

#### Examples

> On the first day of a five-player game, Jeremy (the **Cerenovus**) has to leave. Each night afterwards,
> the Storyteller chooses someone to be mad using the **Cerenovus**' ability.

> The **Virgin** (who is yet to be nominated) leaves. The next day, a Townsfolk nominates
> the **Virgin** and dies.

> The **Vortox** leaves. Each night afterwards, the Storyteller chooses a player to die, and gives
> false info to all Townsfolk. On the final day, the **Vortox** is executed. Good wins.

#### Explanation

A five-player game with a Traveller is too powerful for the good team, since that Traveller is
basically guaranteed to be good, and the number of players who can be the Demon is now four instead of five.

With an Editor in play, every player can have a normal character's ability (including being the Demon!)
without worring if leaving will guarantee a loss or the use of the **Fiddler**.
