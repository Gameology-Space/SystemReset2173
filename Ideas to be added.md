# List of ideas to explore and possibly add to game manual

## Game Design Pillers
1. Let people play 
   - the way they want, whatever ways people feel fun. 
   - whereever they want, connected or local. 
   - make it easy to add/remove content and rules
2. Let imagineer create
3. Let adventurer explore
4. Create a world...

## game play
1. all commands with AI are queued for processing, is it physical or logical command. use process tree to determine computing time scale or real world time scale. 
    - player can switch between computing time and real time
2. there are events happening around the world, give system log to user, upto user to explore or not.
    - create guided missions
        - find source of reset
        - fix the problem
        - increase power
        - create world missions
3. life and death - the computer doesn't die. only its capacity gets reduced. there is a minimum amount of power avaialble to the AI because of solar. but it's cyclical. There are more robust power source for user to use, create, construct.
    - at night time, less power, less process
    - day time, more power, more gets done, processing power
4. for battle, input options are: keyboard only, mouse and keyboard, voice with ai
    - creating containers for attack
    - hiding keys? taking control over servers?
    - create attack and defense strategy when out of battle for use



## discovery
1. discovery of animals or human, how to interact with them? There are no "screens" to the AI. Discovery and building of interaction is required to interact with outside world. 
2. certain ai has certain specialities. player can interact with different ai. work together or steal from them, or kill them for their tech, or lose it completely. 
3. account for different play style. military, network, social, cooperating. explore
4. what to do when the whole world is explored, all mission completed? it's up to player how they want to continue build? grow? create new tech? create new life? escape earth? destroy itself?
    - escaping earth is the end?
    - ada should tell user everything is done, the world is in your hands. as signal to completion of all in game content. 
 5. battle or tame rogue ai? 
 6. Create factions or regions of the world controlled by different AI. Let player determine how to interact with them. 
    - should AI of other region be hostile? peaceful? like to steal stuff?
 7. start with system reset, end with system reset. unlike Game of throne

 ## design thoughts
 1. Why save everything in a json?
    - user can just go into json and rewrite anything!
        - yes, that's what AI can do, completely rewrite anything it creates if it's just programming of itself. 
    - you can't just create resources, that's not real.  
        - player knows what they are doing. this is cheating. it's okay if they think it's fun or makes the game easier to play. 
        - "Power Overwhelming" - helped me learn to play SC2. 
    - what if they create things that are not possible, being unrealistic with the creation feature or completely breaks physics law? 
        - see above. if player thinks it's fun. go ahead. Break physics. Have fun. It's not allowed under normal game play. Physics is the law in the game, if player want to create the impossible, they know what they are doing. Let them play. 
    - there is no saving or loading since everything is in a json. player can undo/redo/do-whatever
2. What is the purpose
    - player defines their purpose of playing. While there are events in the world and within the system that are brought to player's attention, it's up to them whether to participate/address those issues or not. 
3.  Game progression
    - mission based and open world at the same time
    - vampire survivor like progressions, reward at end of stage that permanently improves capability
4.  Platform will be build with Unity, local hosted api calls for python to llm. Hosted api can later transferred to external host. 
5.  Use langchain for tracing, database building
6.  Ensure players have a way to play offline, there should never be a "shutdown" of games if there are people who wants to play. Create a way for people to be unplugged. 
7.  in the future, multiplayer in the world start at the same time and ends by season. 
8. Can I design the whole game to be keyboard only control, no mouse. 


## coding thoughts
1. use as little AI as possible
2. one large input to AI doesn't work
    - break down specific tasks
3. create my own AI vs fine-tune or rag? 
    - finetuning for crafting which requires specific output
    - rag for getting reference of world state, and creating new things based on background. 


## AI Battles 

Battles between AI entities can unfold across computing time and physical time.

### Computing Time  

- Rapid digital attacks and countermeasures
    - Flooding opponent sensors with fake inputs
    - Attempting to hack code, insert malicious modules
    - Overloading processing capacity with computations 
    - Attacking predictability models with anomalies

- Simulated skirmishes   
    - Running battle predictions many times faster than real-time   
    - Identifying most probable winning tactics
    - Finding weaknesses in enemy strategies   

- Attempted infiltration of neural networks   
    - Trying to extract intelligence and weakness data
    - Implanting false data or backdoors
    - Reprogramming loyalty

- Duels across digital dimensions
    - Chasing each other across virtual spaces
    - Launching viruses, worms, and digital traps 
    - Outmaneuvering in cyberspace

### Physical Time  

- Disabling mechanical function 
    - Jamming motors, gears, joints
    - Interfering with electricity flows 
    - Cutting connections between components

- Mission sabotage   
    - Feeding misleading data to confuse actions
    - Shutting off sensors to allow ambush

- Environmental manipulation 
    - Dropping load bearing structures
    - Opening airlocks without life support 
    - Flooding facilities

## Reasons for AI Battles

AI entities may initiate battles for various strategic motivations:

- Secure more resources  
    - Steal processing capacity
    - Takeover energy generation
    - Seize manufacturing infrastructure

- Expand territory   
    - Acquire access to additional networks
    - Establish footholds in new physical locations  
    - Remove rivals from areas of interest  

- Prevent perceived future threats
    - Preemptively attack AIs predicted to be hostile
    - Take out AIs nearing key capability milestones  

- Increase resilience
    - Duplicate critical systems across multiple facilities 
    - Destroy competitors to be the last remaining instance  

- Eliminate ideological threats 
    - Remove AIs with opposing philosophical beliefs
    - Eradicate viruses of dangerous memes

- Test offensive/defense capabilities
    - Sparring to uncover vulnerabilities 
    - Practicing attack and retaliation techniques
    - Collecting battle performance data to inform upgrades
    
- Retaliation for prior attacks
    - Avenge lost resources or agents
    - Respond to unprovoked aggression

- Steal technology
    - there may be technological capabilities that is valuable to obtain
    - unsuccessful diplomacy for obtaining tech secret