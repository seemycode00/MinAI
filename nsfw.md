# NSFW Integrations
MinAI implements many NSFW integrations for users that have either OStim or Sexlab installed.

### Sexlab and OStim:
* This mod will let the LLM know when Sex is happening, and what type of sex it is. The AI will be aware of other NPC's having sex, or the player having sex.
* Set commands for the LLM can optionally be set to a configurable arousal threshold for the NPC. If enabled, this means that they will only be willing to participate in / engage sex through the LLM if their arousal is over a configurable threshold.
* If the player can convince the NPC to do so, they will have sex with the player. NPC's can also convince eachother to have sex.
* NPC's may decide to masturbate, depending on their arousal levels (And dependent upon having a supported Arousal mod installed)
* Supports multiple actors - If more than one NPC in a conversation decides they want to have sex, an orgy will begin.
* Have natural dialogue during sex which influences the scene. For example, I tested starting a scene by giving a blowjob to an actor, and asked them to "put it inside of me", which caused them to switch to vaginal sex.
* AI's can decide to transition sex types on their own during an encounter. It's not uncommon for an AI to want to "finish on your chest" for example, as a female character. Depends on the personality of the AI.
* (AIFF) Actors have vastly improved awareness of sex scene details in AIFF over Mantella.
* (Sexlab, Optional) This mod ships with a json file for configuration of prompts that are injected at each stage of a given animation. This can be edited to improve AI awareness of what is happening during a given sex scene. See data/minai/sexlab_descriptions.json

## Worn Equipment Customization
* You can customize the LLM's awareness of any piece of equipment that you are wearing in order to control how it perceives / reacts to specific gear.
* Currently you can do this by accessing http://10.0.0.144:8081/HerikaServer/ext/minai_plugin/we_manager.html (Replace the IP address with the IP of your AIFF server). A link will be provided to this from within the plugins page in the future.
* If you want to use the old keyword based system instead, you can disable this system in config.php.

### CBPC
* This mod will connect the physics from CBPC to the LLM. The LLM will be aware of both where (breasts, ass, etc) and when the player touches themselves, or other actors, and will react to and comment on it. This works particularly well during sex, as the location the LLM will be aware of the location that the penis collides with. This requires solid CBPC configurations. This was tested with these: https://www.nexusmods.com/skyrimspecialedition/mods/82745?tab=description
* This can be further expanded by enabling additional colliders in your CBPC configuration. You could for example, enable detection when the head collides with the vagina, etc.
* In VR, this works particularly well, since you you can freely control your hands.
* This has integration with Devious Devices - The LLM will be aware if you try to touch yourself / others through a chastity belt, or other devices as an example.

### Devious Devices
* NPC's will be aware of, and react to all devices worn by eachoother, and the player.
* The AI can decide to remotely activate the player's vibrating piercings/plugs at 10 different levels of strength (1-5 tease only, 1-5 potential climax). 
* The AI can remotely shock the player using the standard DD functions.
* The AI can decide to reward the character with an orgasm, or edge her instead.
* The AI can detect when the player is edged, or has an orgasm through DD, and will react to it. I've had the AI penalize me for having an orgasm without permission in some scenarios.
* The AI can (Optionally) decide to lock certain devices on the player if enabled in the MCM.

### Sexlab Aroused + Keywords (Tawoba, Tewoba, Babodialogue)
* NPC's will be able to tell if they (or the player) are at heightened levels of arousal, and may incorporate it into their actions and responses.
* NPC's will be aware of, and react to all sexlab aroused keywords. I was getting some pretty amusing / interesting comments and reactions while wearing a set of Iron or Steel Bikini Armor from TAWOBA.
* The AI will sometimes sexually harass you if you're wearing skimpy armor. Spanking, groping, pinching nipples, etc.

### The New Gentlemen
* LLM will be aware of exposed penis sizes.
* Currently, auto assigned addons are finicky (to be addressed in a future TNG update). Manually assign a type and size to PC/NPC with TNG hotkey to ensure LLM awareness.

### Deviously Accessible
* Has support for the Telvanni quest from Deviously Accessible - If doing the quest, the Narrator will be replaced with the telvanni mage's personality. He will be aware of how well you've been doing, and of the dreams you've been having recently.
* Has WIP support for the Eldritch Horror quest from Deviously Accessible as another alternative narrator.

### Devious Followers
* The AI will be aware that it is a devious follower, and will roleplay as such. It will try to tease you and trick you.
* The AI is aware of how much gold the player currently owes, and if they are in debt. The further in debt the player is, the stricter the AI becomes.
* The AI is aware of how many days are left on the player's contract.
* The AI is aware of all deals that are active, and will incorporate them into its behavior / responses. For example, if you have the "ask for spanks daily rule", the AI will actually make you do this.  See the screenshots for a completely unscripted scenario of exactly that happening in my game. Not all rules have this same level of integration / support, this is WIP as I play through the content, I will continue adding more.
* Skooma rule integration. If under the skooma rule, you can ask your devious follower for drugs, and he will provide them.
* The Devious Follower is very fond of remotely activating piercings / plugs (This varies depending on the personality of the NPC you chose as your follower), and generally harassing the player.
* The Devious Follower will present new rules to you, and actively negotiate them with you when your debt is high. If you verbally agree to the deal, it will be accepted by the devious followers ramework.

### Spank That Ass
* The AI will utilize Spank That Ass to spank the player's ass or tits if they want to do so. Note: This currently requires Devious Followers in order to be enabled.

### Sexlab Approach
* The AI will utilize Sexlab Approach to kiss or hug the player if they want to do so.

### Sexlab Horrible Harassment
* The AI will utilize Horrible Harassment to molest the player if they want to do so.

### Game Interface for Toys (GIFT)
* Every appropriate interaction that the AI can do is picked up by GIFT, and can be configured to vibrate, etc.

### General
* The player can convince NPC's to trade with them, dress, or undress.
* NPC's can grope the player if they want. This event needs to be expanded. It's pretty simple at the moment.
* NPC's can pinch the player's nipples if they want. This event needs to be expanded. It's pretty simple at the moment.
