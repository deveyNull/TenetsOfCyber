# Tenets of the Cyber Domain:
Last Updated: 08Mar2021

These are the unsolicited opinions of someone who has never conducted cyber operations with no knowledge of controlled information. 

I have never been read in to anything and have no real world knowledge of the subject. Take that as you will. 

Feedback appreciated @deveynull or d.m.devey@gmail.com. 

1. Attribution
    1. Attribution is split into two distinct entities, Capital "A" and lower-case "a" attribution
        1. Capital "A" Attribution is defined as the ability to identify an action or series of actions as the result of a specific individual or organization that is grounded upon enough evidence to launch a Tomahawk at them and start a war. 
        2. Lower-case "a" attribution is very useful for just about any other use case, **especially in the private sector**
            * Can also be used by governments for response lower than going to war, especially sanctions.
            * Lower-case "a" has plenty of nuance and intelligent things written about it by the CTI people. They are generally correct and have good intentions, but are financially incentivized to view lower-case "a" as an important part of defense when it isn't. 
            * I am not particularly interested in attribution and will focus on Attribution
    2. **You cannot perfectly Attribute any attack using exclusively digital artifacts.**
        1. Not Attributable:
            1. Tools
            2. Techniques
            3. Procedures
            4. Command and Control 
                1. The location of computers and "ownership" of computers means nothing
                2. The location of the first hop off of a hacked box means less than nothing
                3. Even if you think you have tracked all the hops back to the originating server, that server might not be controlled by the owner
         2. You will only have attribution if your attacker is a) bad at their job b) wants you to/doesn't care or c) you have significant intelligence capabilities and got lucky
         3. Meaningful attribution requires an OPSEC failure, SIGINT, HUMINT, or a combination of the three. Anything else is guesswork.
            1. If an organization has meaningful Attribution from HUMINT, it might not be shared because sources and methods are more important than somebodys' computers getting popped. Also, nobody who does HUMINT will trust computer nerds to be discrete about things like this. 
            2. Just because there is an opsec failure doesn't mean you have attribution
                1. Framing someone else is pretty easy.
                2. Anonymity is bolstered by universal access to offensive TTPs
                    1. I strongly believe that uncontrolled distribution of Offensive TTPs is the single greatest enabler of malicious actors, the vast majority of which are non-technical.
                    2. For more on this, read [@anthomsec's blog on this.](https://medium.com/@anthomsec/misconceptions-unrestricted-release-of-offensive-security-tools-789299c72afe) I am in full agreement. 
    3. You will not get Attribution, let alone attribution, ever for the vast majority of attacks, and the ones that you get attribution for will take longer than you have for your window of response
        1. **If your doctrine assumes that you have Attribution for an attack, it will not be applicable for 99.99% of cases.**
            * I can write more on this and point to examples, or you can just agknowledge this as a universal truth
    4. In the event of a cyber attack that kills people or causes serious harm, unless you can prove nation state foreknowledge, place hands on keyboard to a specific actor, and intent to cause the harm that occurred, you do not have Attribution that is worth starting a war over
        1. Even if an attack can be traced back to a state sponsored actor in a specific country that doesn't provide enough evidence to place blame for attack on country
        2. Intent is necessary because something that could have been meant to be initial access might knock critical systems offline or have other unintended negative side effects
        3. Indiscriminate worms are irresponsible, but that doesn't mean they are an act of war

2. Deterrence
    1. ***Nuclear style deterrence does not work because Attribution does not work. Full stop.***
    2. "Holding at Risk"
        1.  If the people who you are intending to hold at risk can attack you with confidence the attack will not be able to be attributed, you cannot hold them at risk
        2.  Technically, holding at risk requires you to a) have zero day or b) have access and maintain access up until the time that you need to act.
            1. In both of these scenarios the person you are holding at risk does not know how you are holding them at risk or if you are at any given time, removing the point of it
            2. Ability to hold at risk can be instantly erased with a patch or antivirus rule
            3. If you are &quot;holding at risk&quot; by putting implants in foreign countries critical infrastructure, you are setting very bad precedents that do not favor America

     3. _Only meaningful deterrence is via cost imposition_
          1. Resilience
              1. Defense in depth makes it take more time/energy/resources
          2. Cost of exploits/tooling
              1. Make it so first use of exploit the only time it is zero day
              2. Time to patch speed needs to be fast
              3. Open source tooling/dumping exploits on Twitter makes this very difficult to effect
          3. Passing real world sanctions
              1. You probably won&#39;t be able to arrest individual actors, but if they are not state sponsored or like to go on vacation it is possible
                  1. Indicting them sets a weird precedent and accomplishes nothing... signaling? To who?
                  2. It also makes it hard for my friends and I to go surfing in SE Asia
              2. Economic sanctions on their country is pretty sweet

3. Rules, Routines, Norms and International Law
    1. **All the countries can agree on whatever they want but they can and will launch attacks from non-attributable sources whenever they want**
        1.  See Attribution.

4. The &quot;State Sponsored&quot; Continuum
    1. State Sponsored actors exist but there is a huge range in their attributability to their &quot;sponsor&quot; country
        1.  Ranges from uniformed military/intelligence, non uniformed intelligence, contractors, freelancers, or merely sympathetic parties
        2.  Any step can be outsourced, from TTP development to initial access to actions of target to post attack analysis, eliminating nation state liability**
            1. Differentiating between the actions of sympathetic parties and uniformed military is impossible without Intelligence
    2. American Private Sector Involvement
        1. Leads to an unfavorable status quo as the US has little to gain from normalization of non-state actors **in any domain**
        2. Militia/ Letters of Marque/Privateering
            1. Anyone who wants this is a fool and should be ignored
        3. Every other country in the world would benefit from this status quo

5. Threat Actors
    1. The only reason specific threat groups exist is because they are lazy (read:resource constrained) and don&#39;t change TTPs.
        1.  Just because identical TTPs are used doesn&#39;t mean it is the same threat group.
            1. It probably is, but in no way is that good enough for attribution
        2.  Offensive TTPs are approaching the point where they will be universal
            * Cobalt Strike is actually ***that*** good.
     2. Knowing what threat group is going after you should barely change your posture
        0. Security is a static baseline you slowly raise in response to additional investment in your security team
        1. "The Russians were always after your shit, you just know it now."
            * Should be used to allow you to research their TTPs and perform a targeted hunt process
            * Can be useful for selling to uninformed higher ups you need more funds

6. Advanced Persistent Threats
     1. Everyone is an APT if they want to put the time and money in
        1.  Cost of entry to the space is minimal due to universal access to offensive TTPs
        2.  Read [Grugq's Build an APT Post.](https://medium.com/@thegrugq/cyber-ignore-the-penetration-testers-900e76a49500)
     2. Sophistication will vary inside of the same threat group based on operational requirements
        1. **Whatever the minimum level of sophistication is that is required, that is what an attacker will use**
        2.  There is no reason for a group to use a million dollar 0day and their custom toolkit when an old exploit and an open source implant will do the job.
            1. There is no reason to use an exploit when phishing will do the job
                1. There is no need to exploit anything if your databases are public facing
7. Authorities in Cyberspace
    1. United States/FVEY/a few other folks
        1. Concept only acknowledged by the United States/allies, hamstrings us
            2.  Title 10/50 Authority is what we have, in comparison to Title #yolo which is what everyone else uses
     2. Everyone else
        1. Military/Intelligence community do whatever they want
        2. Non-attributable actors do whatever they want (And who are those guys?)
        3. Criminals are allowed to do whatever they want as long as it doesn&#39;t hurt host country
           * Criminals can also do whatever they want as long as they don't think they'll get caught by host country

8. Signalling and Escalation in Cyberspace
    1. Intelligence Gathering
        1. Everything is intelligence gathering until proven otherwise
        2. Everyone does it
        3. No it is not an escalation
    2. Implants in Critical Infrastructure
        1. See 8.1. 
        2. We do it too, we just yell when we find stuff in our networks
        3. No benefit to anyone acting shocked, shocked I tell you when we find stuff
    3. Signaling
        1. Ambiguous, attacks have no clear objective until actions are taken
        2. Almost all attacks look the same and can be repurposed at any time
        3. Nobody can tell who did what, unless you cryptographically do so. Noone has ever done that.
        4. You can also announce your intentions aheed of time, which is what the US has been doing, but that opens up a whole new can of worms. Honestly think this might be the best way to do it, though it opens the door for someone front-running your signaling and making you look like you turned off a hospital. Still, probably the best move. 
    4. Speed of decision making
         1.  Decisions need to be made faster than the information needed to make the decisions will come in. The options are don&#39;t make decisions or have red lines that make your decision making process easier
    5. Red Lines
        1. Useless without attribution
        2. Useless if your enemies know what they are
            1. Will be crossed by non-attrib actors and you won&#39;t be able to do anything about it
    6. Escalation
        1.  Don&#39;t be the person who starts a shooting war over some malware in your power plants


1. Types of Action in Cyberspace (In progress, hard)

1. Offense is hard
      1. Tactical Level
            1. Providing on-demand access to specific assets is very difficult because zero days are hard to come by and maintaining long term access is harder
            2. Providing on-demand, non-targeted access to random boxes for short periods of time is inexpensive
            3. 0-days
                  1. Hard to get, requires talent or paying talent. COST OF DEVELOPMENT IS HIGH
                  2. Value of developed 0day is HIGHER than cost of development
                  3. Cost of Use is ZERO but risks eliminating value of exploit
                       1. Sitting on a cache of 0days is the only way to guarantee access to a target, making a stash of 0days for cyberwar purposes the best way to go about things

                          1. If you lose your 0days and everyone in the world gets hacked, you messed up and should apologize and explain why you need a stash, at least to Congress
                          2. Cough
                  4. Upon detection/leak, becomes an N-day.
                      1. Cost of re-use is ZERO
                      2. Value of exploit approaches ZERO
                      3. Applicability of exploit approaches zero with patching and blocking (but never comes close to zero)
                      4. Cyber proliferation makes responsible use difficult
            3. Maintaining a campaign is hard
                1. Targeting at scale with discrimination is hard
                2. Difficult to do battle damage assessments
                3. Maintaining access is the hard problem
            6. Maintaining Access
                1. Significantly more complicated than the initial access problem
                2. This can be broken up into two time periods, Undetected and Post-Detection:
                3. To remain Undetected, once attackers are on the network, they need to be correct 100% of the time, while defenders need to only get lucky once
                4. Only real answer is pivot early, pivot often, grab creds, and maintain access in multiple ways. Each additional action increases chance of detection and lowers chances of remaining in an Undetected mode. 
    2. Strategic Level
        1. Desired effect is to hold enemy at risk
              1. See Deterrence.
        2. Targeting/employment
             1. Counter Value
             2. Counter Target

2. Defense is hard
    1. Aggressor chooses time, place, and method
        1. Attacker Only Needs to Be Right Once (to get in)
            1.  Defenders have to be perfect 100% of the time, attacker only needs to get lucky once/you don't patch. Or have an 0day.
            1. If an attacker is good, they will get in to anywhere
                1. See "Mossad gonna mossad on you"
            2. If an attacker is lowercase "p" persistent, they will get in to most places eventually
        2.  Once attackers are on the network, they need to be correct 100% of the time to remain Undetected, while defenders need to only get lucky once
            1. Set up your defenses so that you can get lucky early
            2. Set up your logging so that one alert allows full Incident response
                1. Set up alerting on high fidelity indicators so that one alert results in detection
                2. You should be using honeypots
        3. In incident response the paradigm is flipped once again. Responders need to be perfect, attackers just need to survive. 
    3. Anonymity of attacker
        1.  See Attribution.
    4. 0day Detection
        1.  0days can only be detected if defenders architect and log in a way to capture payloads. If it isn&#39;t caught, its still an 0day
    5. Patching
        1. Even if you are perfectly patched, 0days and n-days can and will happen.
           * If an n-day for one of your external systems gets dropped on Twitter and you're on the "Req. Access" list, time to start your IR. 
        2. Patch releases take a while, or may never come if EOL'd or neglected
           * Not every system can be patched
        3.  When a patch is released, the boys will be reverse-engineering it. If they get the exploit before you install your patches, and you're on the "Req. Access" list. 
     6. Inventory management is most of defense
        1.  Know your attack surface
              1. Where is your data stored
              2. What systems do you own
              3. What systems do you not own
              4. What applications do you use
         2.  If you fail here you can&#39;t do access control/hardening/logging
         3.  If you don't know these things, you also don't know what n-days matter to you
    7. "Security One Percent"
        * Popularized by [this blog by TaoSecurity.](https://taosecurity.blogspot.com/2020/10/security-and-one-percent-thought.html)
        * To sum up the post: "The actions of the security 1% (and especially the .1%) have done more harm than good for 99.9999 percent of Americans."
        * Read the post and know it to be true.

1. Digital Sovereignty
    1. National Sovereignty
        1.  Physical and cyber sovereignty are meaningless to our enemies
            1. Also meaningless technologically
            2. Enemies use friendly, neutral, and adversary territory against us
        2. Handcuffs US forces
            1. Hack back can cause all sorts of problems
    2. Shared infrastructure
        1. &quot;multistakeholder&quot;
        2.  Everyone is on the same playing field
    3. Requires collaboration between international, public, and private organizations
        1. This doesn&#39;t work at the speed required to defend.
    4. Neutral and civilian infrastructure used for offensive purposes will require internationally accepted treaties that allow actions against

1. &quot;Oh my god things are changing so fast this is all so new how do we respond&quot;
    1. Read &quot;Cuckoo&#39;s Egg&quot;
    2. Nothing has changed in the last 50 years.
         1. New combinations of ideas, rise in prevalence, but that is really it
    3. Anyone who says that things move too fast to learn or keep up is wrong. The news is constant and is mostly noise, but the principles remain the same.
        1. _Probably should write more about this in a different paper._
    4. Thank you to everyone who has been in this domain for the last 50 years and managed not to create any meaningful international agreements about it

1. Stupid Topics
    1. Dark Web/TOR
        1. Nothing happens here that doesn&#39;t happen on the regular internet
        2.  It&#39;s not even very anonymous
    2. Anonymous
         1. Not a thing worth mentioning, ever. Low sophistication, low motivation, poorly organized (if any organization exists)
            1. Plenty of state sponsored &quot;hacktivists&quot;
    3. ISIS cyber
        1. Shut up.
    4. Tallinn Manual
        1. Absolute joke because it uses an incorrect model of cyber war. See everything above.
    5. Stuxnet
        1. If you use this as your example it is the name of the only piece of malware you know, your audience is the general public, or are discussing sophisticated malware which only makes sense to be created/used by a nation state
            1. Only the 3rd is acceptable if you want to be taken seriously
    6. &quot;\_\_insert noun\_\_ is vulnerable&quot;, &quot;the sky is falling&quot;, or any other FUD
        1.  Spreading Fear, Uncertainty, and Doubt contributes nothing but awareness. Awareness doesn&#39;t count for much, but it counts for something
        2. Also everything is vulnerable. Nobody cares.
            1. Not even about the grid.
    7. Offensive Artificial Intelligence
        1.  This makes no sense in whatever offensive context you are thinking about
    8. Number of attacks a day/unique malware samples
            1. Don&#39;t use numbers that cost the attacker nothing. Untargeted attacks (or worse, scans) are meaningless.
            2.  If you count external scans as attacks you should be as far away from writing doctrine as possible
            3.  Look for the organizations that say "We dealt with 4 attackers this month". They know what they are doing.
    9. Breaches
        1. They don&#39;t cause companies to go out of business and they barely affect bottom line
           * Unless the companies business is data, then it hurts
        2. Or they get ransomwared/wiped and can&#39;t recover
            1. Then ouch
        3. I buy calls every time, do you?
    10. STEM/Cyber Talent Shortage
        1.  Doesn&#39;t exist. 
    11. Gerasimov Doctrine
        1. Also not a thing
    12. Cyber Letters of Marque/Privateering
        1. This person wants to make money and doesn't care if people die in the process.
        2. Or they just want to hack shit and don't care if people die in the process.
        3. Similar to the HUMINT discussion earlier, there are too many children (nerds) at the table when it comes to cyber war. The real world does not care about rules or your precious computers when human lives are on the line.
        
Things worth reading:

Anything by
  - TheGrugq
  - Dave Aitel
  - Bruce Schneier
  - Marasawr
  - Athomsec
  - Rob Joyce
  - Chris Inglis

Videos: 
- Decent Argument that the Rob Joyce talk videos are better than any paper
    - https://www.youtube.com/watch?v=gmgV4r25XxA
    - https://www.youtube.com/watch?v=bDJb8WOJYdA

  
  Books: 
    - [https://www.amazon.com/Network-Attacks-Exploitation-Matthew-Monte/dp/1118987128](https://www.amazon.com/Network-Attacks-Exploitation-Matthew-Monte/dp/1118987128)
    - [https://www.amazon.com/Cyber-Towards-Operational-Art-Conflict/dp/0692911561](https://www.amazon.com/Cyber-Towards-Operational-Art-Conflict/dp/0692911561)
    - Sandworm
    - Countdown to Zero Day: Stuxnet and the Launch of the World’s First Digital Weapon
    - [https://www.amazon.com/Cuckoos-Egg-Tracking-Computer-Espionage](https://www.amazon.com/Cuckoos-Egg-Tracking-Computer-Espionage/dp/1416507787/ref=pd_sim_14_10?_encoding=UTF8&amp;pd_rd_i=1416507787&amp;pd_rd_r=868b8a07-8d03-11e8-a455-9f459e9048be&amp;pd_rd_w=2bGBV&amp;pd_rd_wg=mMDnT&amp;pf_rd_i=desktop-dp-sims&amp;pf_rd_m=ATVPDKIKX0DER&amp;pf_rd_p=2610440344683357453&amp;pf_rd_r=FGN4CHC6HEHAR4YJVD27&amp;pf_rd_s=desktop-dp-sims&amp;pf_rd_t=40701&amp;psc=1&amp;refRID=FGN4CHC6HEHAR4YJVD27)
    - [A Fierce Domain- Jason Healey](https://www.amazon.com/Fierce-Domain-Conflict-Cyberspace-1986/dp/098932740X)
    - [On Cyber -Greg Conti](https://www.amazon.com/Cyber-Towards-Operational-Art-Conflict/dp/0692911561)
    - 

Papers:

- https://www.hoover.org/research/us-cyber-commands-first-decade
- https://www.cybercom.mil/Portals/56/Documents/USCYBERCOM%20Vision%20April%202018.pdf
- https://www.cybercom.mil/Portals/56/Documents/2020%20Tech%20Challenge%20Problems%20UNCLASS%20CAO-PAO%20FINAL.pdf?ver=2020-08-18-160721-850

- Abelson, Hal et al., Keys Under Doormats: Mandating Insecurity by Requiring Government Access to All Data and Communications, Jul 2015.
- Barlow, John Perry, &quot;A Declaration of the Independence of Cyberspace&quot;, February 8, 1996, https://projects.eff.org/~barlow/Declaration-Final.html
- Mandiant, APT1: Exposing One of China&#39;s Cyber Espionage Units, (2013) http://intelreport.mandiant.com/Mandiant\_APT1\_Report.pdf
- Steven G. Bradbury, _The Developing Legal Framework for Defensive and Offensive Cyber Operations_
- Andru E. Wall, Demystifying the Title 10-Title 50 Debate: Distinguishing Military Operations, Intelligence Activities, &amp; Covert Action (pp 85-122 only)
- Introduction to Jus Ad Bellum/Jus In Bello and Sovereignty; Use of Force and Armed Attacks; Attribution; Necessity and Proportionality 
- Council of Europe Convention on Cybercrime (articles 2-8, 11, 13, 15, 22-26, 35)
- Josephine Wolf, NATO&#39;s Empty Cybersecurity Gesture
- Matthew Waxman, Self Defense Force Against Cyber Attacks
- Siobhan Gorman, Cyber Combat: Act of War
- Michael Schmitt, International Law and Cyber Attacks
