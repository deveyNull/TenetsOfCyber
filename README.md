# Tenets of the Cyber Domain:

These are the unsolicited opinions of someone who has never conducted cyber operations with no knowledge of controlled information. 
Take that as you will. Feedback appreciated @deevnull. 

1. Attribution
    1. Attribution, in this very limited dialog, is defined as the ability to identify an action or series of actions as the result of a specific individual or organization that is grounded upon enough evidence to launch a Tomahawk at them. 
        1. A confidence level for attribution is useful for just about any other use case, especially in the private sector. 
    1. **You cannot attribute any attack using exclusively digital artifacts.**
        1.  Tools are not attributable.
        2. Techniques are not attributable.
        3.  Procedures are not attributable.
        4.  Command and control servers are not perfectly attributable.
            1. The location of computers and &quot;ownership&quot; of computers means nothing
            1. The location of the first hop off of a hacked box means less than nothing
      2. Even if you think you have tracked all the hops back to the originating server, that server might not be controlled by the owner
      3. You will only have attribution if your attacker is a) bad b) wants you to or c) you have significant intelligence capabilities and got lucky
            1. Meaningful attribution requires an OPSEC failure, SIGINT, HUMINT, or a combination of the three. Anything else is guesswork.
            1. If an organization has meaningful attribution from capital I Intelligence, it will not be shared because sources and methods need to be protected
            2. Just because there is an opsec failure doesn&#39;t mean you have attribution
                1. Framing someone else is pretty easy.
                2. Anonymity is bolstered by universal access to offensive TTPs
    2. You will not get attribution ever for the vast majority of attacks, and the ones that you get attribution for will take longer than you have for your window of response
        1. If your doctrine assumes that you have attribution for an attack, it will not be applicable for 99.99% of cases.
    3. Unless you can prove nation state knowledge, attribute hands on keyboard to a specific actor, and intent to cause the harm that occurred, you do not have _attribution_ that is worth killing anyone over
        1. Even if an attack can be traced back to a state sponsored actor in a specific country that doesn&#39;t provide enough evidence to place blame for attack on country
        2. Intent is necessary because something that could have been meant to be a crimeware worm might knock critical systems offline or have other unintended negative side effects

2. Deterrence
    1. Nuclear style deterrence does not work because attribution does not work. Full stop.
    2. &quot;Holding at Risk&quot;
        1.  If the people who you are intending to hold at risk can attack you with confidence the attack will not be able to be attributed, you cannot hold them at risk
        2.  Technically, holding at risk requires you to a) have zero day or b) have access and maintain access up until the time that you need to act.
            1. In both of these scenarios the person you are holding at risk does not know how you are holding them at risk or if you are at any given time, removing the point of it
            2. Ability to hold at risk can be instantly erased with a patch or antivirus rule
            3. If you are &quot;holding at risk&quot; by putting implants in foreign countries critical infrastructure, you are setting very bad precedents that do not favor America

      1. _Only meaningful deterrence is via cost imposition_
          1. Resilience
              1. Defense in depth makes it take more time/energy/resources
          2. Cost of exploits/tooling
              1. Make it so first use of exploit the only time it is zero day
              2. Time to patch speed needs to be fast
              3. Open source tooling/dumping exploits on Twitter makes this very difficult to effect
          3. Passing real world sanctions
              1. You probably won&#39;t be able to arrest individual actors, but if they are not state sponsored or like to go on vacation it is possible
                  1. Indicting them sets a weird precedent and accomplishes nothing... signaling?
              2. Economic sanctions on their country is pretty sweet

1. Rules, Routines, Norms and International Law
    1. **All the countries can agree on whatever they want but they can and will launch attacks from non-attributable sources whenever they want**
        1.  See Attribution.

1. The &quot;State Sponsored&quot; Continuum
    1. State Sponsored actors exist but there is a huge range in their attributability to their &quot;sponsor&quot; country
        1.  Ranges from uniformed military/intelligence, non uniformed intelligence, contractors, freelancers, or merely sympathetic parties
        2.  Any step can be outsourced, from TTP development to initial access to actions of target to post attack analysis, eliminating nation state liability**
            1. Differentiating between the actions of sympathetic parties and uniformed military is impossible without Intelligence
    2. American Private Sector Involvement
        1. Leads to an unfavorable status quo as the US has little to gain from normalization of non-state actors **in any domain**
        2. Militia/ Letters of Marque/Privateering
            1. Anyone who wants this is a fool and should be ignored
        3. Every other country in the world would benefit from this status quo

1. Threat Actors
    1. The only reason specific threat groups exist is because they are lazy and don&#39;t change TTPs.
        1.  Just because identical TTPs are used doesn&#39;t mean it is the same threat group.
            1. It probably is, but in no way is that good enough for attribution
        2.  Offensive TTPs are approaching the point where they will be universal
     2. Knowing what threat group is going after you shouldn&#39;t change your posture
        1. Should be used to allow you to research their TTPs and perform a targeted hunt process
        2. Can be useful for selling to uninformed higher ups you need more funds

1. Advanced Persistent Threats
     1. Everyone is an APT if they want to put the time in
        1.  Cost of entry to the space is minimal due to universal access to offensive TTPs
     2. Sophistication will vary inside of the same threat group based on needs
        1. **Whatever the minimum level of sophistication is that is required, that is what an attacker will use**
        2.  There is no reason for a group to use a million dollar 0day and their custom toolkit when an old exploit and an open source implant will do the job.
            1. There is no reason to use an exploit when phishing will do the job
                1. There is no need to exploit anything if your databases are public facing
2. Authorities in Cyberspace
    1. United States
        1. Concept only acknowledged by the United States/allies, hamstrings us
            2.  Title 10/50 Authority is the closest we have to Title #yolo which is what everyone else uses
     2. Everyone else
        1. Military/Intelligence community do whatever they want
        2. Non-attributable actors do whatever they want
        3. Criminals are allowed to do whatever they want as long as it doesn&#39;t hurt host country

1. Signalling and Escalation in Cyberspace
    1. Implants in Critical Infrastructure
        1. We do it to, we just yell when we find stuff in our networks
        2. No benefit to anyone acting shocked, shocked I tell you when we get owned
    2. Signaling
        1.  Ambiguous, attacks have no clear objective until actions are taken
        2.  Almost all attacks look the same and can be repurposed at any time
        3. Nobody can tell who did what, unless you cryptographically do so. Noone has ever done that.
    3. Speed of decision making
         1.  Decisions need to be made faster than the information needed to make the decisions will come in. The options are don&#39;t make decisions or have red lines that make your decision making process easier
     4. Red Lines
        1. Useful for making decisions easily
        2. Useless if your enemies know what they are
        3.  Will be crossed by non-attrib actors and you won&#39;t be able to do anything about it
    5. Escalation
        1.  Don&#39;t be the person who starts a shooting war over some malware in your grid

1. Types of Action in Cyberspace (In progress, hard)

1. Offense is hard
      1. Tactical Level
            1. Providing on demand access to specific assets is very difficult because zero days are hard to come by and maintaining long term access is hard
            2.  0days
                  1. Hard to get, requires talent or paying talent. COST OF DEVELOPMENT IS HIGH
                  2. Value of developed 0day is HIGHER than cost of development
                  3. Cost of Use is ZERO but risks eliminating value of exploit
                       1. Sitting on a cache of 0days is the only way to guarantee access to a target, making a stash of 0days for cyberwar purposes the best way to go about things

                          1. If you lose your 0days and everyone in the world gets hacked, you messed up and should apologize and explain why you need a stash, at least to Congress
                          2. Cough
                  4. Upon detection/leak, becomes an N-day.
                      1. Cost of re-use is ZERO
                      2. Value of exploit becomes ZERO
                      3. Applicability of exploit approaches zero with patching and blocking
                      4. Cyber proliferation makes responsible use difficult
            3. Maintaining a campaign is hard
            4. Targeting at scale with discrimination is hard
            5. Difficult to do battle damage assessments
            6.  Once attackers are on the network, they need to be correct 100% of the time, while defenders need to only get lucky once
                  1. Maintain access in multiple ways 
    2. Strategic Level
        1. Desired effect is to hold enemy at risk
              1. See Deterrence.
        2. Targeting/employment
             1. Counter Value
            2. Counter Target

1. Defense is hard
    1. Aggressor chooses time, place, and method
    2. Attacker Only Needs to Be Right Once (to get in)
        1.  Defenders have to be perfect 100% of the time, attacker only needs to get lucky once. Or have an 0day.
        1. If an attacker is good, they will get in to anywhere
            1. See "Mossad gonna mossad on you"
        2. If an attacker is persistent, they will get in to most places eventually
    2.  Once attackers are on the network, they need to be correct 100% of the time, while defenders need to only get lucky once
        1. Set up your defenses so that you can get lucky early
        2. Set up your logging so that one alert allows full Incident response
            1. Set up alerting on high fidelity indicators so that one alert results in detection
        3.  In incident response the paradigm is flipped again. Responders need to be perfect, attackers just need to survive.
    3. Anonymity of attacker
        1.  See Attribution.
    4. 0day Detection
        1.  0days can only be detected if defenders architect and log in a way to capture payloads. If it isn&#39;t caught, its still an 0day
    5. Patching
        1. Even if you are perfectly patched, 0days and Ndays can and will happen.
        2. Patch releases take a while, or may never come if EOLd or neglected
        3.  Not every system can be patched
     6. Inventory management is most of defense
        1.  Know your attack surface
              1. Where is your data stored
              2. What systems do you own
              3. What systems do you not own
              4. What applications do you use
         2.  If you fail here you can&#39;t do access control/hardening/logging

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
    3. Isis cyber
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
            1. Don&#39;t use numbers that cost the attacker nothing
            2.  If you count external scans as attacks you should be as far away from writing doctrine as possible
    9. Breaches
        1. They don&#39;t cause companies to go out of business and they barely affect bottom line
        1. Unless the companies business is data, then it hurts
        2. Or they get ransomwared/wiped and can&#39;t recover
            1. Then ouch
    10. STEM/Cyber Talent Shortage
        1.  Doesn&#39;t exist.
    11. Gerasimov Doctrine
        1. Also not a thing
    12. Cyber Letters of Marque/Privateering
        1. This person wants to make money and doesn't care if people die in the process.
        2. Or they just want to hack shit and don't care if people die in the process.
        
Things worth reading:

- [https://www.amazon.com/Cyber-Towards-Operational-Art-Conflict/dp/0692911561](https://www.amazon.com/Cyber-Towards-Operational-Art-Conflict/dp/0692911561)
- [https://www.amazon.com/Network-Attacks-Exploitation-Matthew-Monte/dp/1118987128](https://www.amazon.com/Network-Attacks-Exploitation-Matthew-Monte/dp/1118987128)
- [https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1980901759/ref=pd\_lpo\_sbs\_14\_t\_0?\_encoding=UTF8&amp;psc=1&amp;refRID=FGN4CHC6HEHAR4YJVD27](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1980901759/ref=pd_lpo_sbs_14_t_0?_encoding=UTF8&amp;psc=1&amp;refRID=FGN4CHC6HEHAR4YJVD27)
- [https://www.amazon.com/Cuckoos-Egg-Tracking-Computer-Espionage](https://www.amazon.com/Cuckoos-Egg-Tracking-Computer-Espionage/dp/1416507787/ref=pd_sim_14_10?_encoding=UTF8&amp;pd_rd_i=1416507787&amp;pd_rd_r=868b8a07-8d03-11e8-a455-9f459e9048be&amp;pd_rd_w=2bGBV&amp;pd_rd_wg=mMDnT&amp;pf_rd_i=desktop-dp-sims&amp;pf_rd_m=ATVPDKIKX0DER&amp;pf_rd_p=2610440344683357453&amp;pf_rd_r=FGN4CHC6HEHAR4YJVD27&amp;pf_rd_s=desktop-dp-sims&amp;pf_rd_t=40701&amp;psc=1&amp;refRID=FGN4CHC6HEHAR4YJVD27)
- [https://www.amazon.com/Incident-Response-Computer-Forensics-Third](https://www.amazon.com/Incident-Response-Computer-Forensics-Third)
- [https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/)
- [https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/](https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441/ref=pd_sim_14_7?_encoding=UTF8&amp;pd_rd_i=1593271441&amp;pd_rd_r=868b8a07-8d03-11e8-a455-9f459e9048be&amp;pd_rd_w=2bGBV&amp;pd_rd_wg=mMDnT&amp;pf_rd_i=desktop-dp-sims&amp;pf_rd_m=ATVPDKIKX0DER&amp;pf_rd_p=2610440344683357453&amp;pf_rd_r=FGN4CHC6HEHAR4YJVD27&amp;pf_rd_s=desktop-dp-sims&amp;pf_rd_t=40701&amp;psc=1&amp;refRID=FGN4CHC6HEHAR4YJVD27)
- [https://www.amazon.com/dp/B07GD4MFW2/ref=dp-kindle-redirect?\_encoding=UTF8&amp;btkr=1](https://www.amazon.com/dp/B07GD4MFW2/ref=dp-kindle-redirect?_encoding=UTF8&amp;btkr=1)
- Abelson, Hal et al., Keys Under Doormats: Mandating Insecurity by Requiring Government Access to All Data and Communications, Jul 2015.
- Barlow, John Perry, &quot;A Declaration of the Independence of Cyberspace&quot;, February 8, 1996, https://projects.eff.org/~barlow/Declaration-Final.html
- Libicki, Martin C., Cyberdeterrence and Cyberwar, RAND Report, Santa Monica: Rand Corp., 2009, http://www.rand.org/pubs/monographs/2009/RAND\_MG877.pdf
- Mandiant, APT1: Exposing One of China&#39;s Cyber Espionage Units, (2013) http://intelreport.mandiant.com/Mandiant\_APT1\_Report.pdf
- Anything by
  - TheGrugq
  - Dave Aitel
  - Bruce Schneier
  - Marasawr
- Steven G. Bradbury, _The Developing Legal Framework for Defensive and Offensive Cyber Operations_
- Andru E. Wall, Demystifying the Title 10-Title 50 Debate: Distinguishing Military Operations, Intelligence Activities, &amp; Covert Action (pp 85-122 only)

- Introduction to Jus Ad Bellum/Jus In Bello and Sovereignty; Use of Force and Armed Attacks; Attribution; Necessity and Proportionality 

- Council of Europe Convention on Cybercrime (articles 2-8, 11, 13, 15, 22-26, 35)

- Josephine Wolf, NATO&#39;s Empty Cybersecurity Gesture

- Matthew Waxman, Self Defense Force Against Cyber Attacks
- Siobhan Gorman, Cyber Combat: Act of War

- Michael Schmitt, International Law and Cyber Attacks
