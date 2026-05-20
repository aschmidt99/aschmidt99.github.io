

<img width="1000" alt="LTDM_Workshop_hero_1000pixel" src="https://github.com/user-attachments/assets/3ec645ff-ad00-4c98-9bfe-4c336df01fa7" />

# Workshop Description

**When:** Tuesday 23 June 2026, 2pm-6pm

**Where:** Fab Lab @ Loughborough University London

[Click Here to sign-up](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=B3WJK4zudUWDC0-CZ8PTB9QuUbj7BKhDgUWiQeRTMqlUMkZTQzlJSjFWWDI4NEw1UUpNOVZYTTVaNC4u)

This half-day workshop focuses on creating and playing feedback-actuated string instruments using Lorentz force actuation. Rather than using electromagnetic coils found in most actuated instruments, Lorentz force actuation involves running electric current through conductive instrument strings in close proximity to strong permanent magnets to induce vibrations in the string. Now the entire length of the string is eligible to become part of the transducer that is formed between the string and the magnet, granting players access to string harmonics and complex behaviors that vary with magnet placement and mechanism design. Participants will first be introduced to the Lorentz Time Division Multiplexing (LTDM) kit – a hardware device that can infinitely-sustain vibrations of conductive instrument strings without the need for external vibration sensors/actuators by simply connecting leads to the ends of a conductive string or a series of strings in close proximity to a strong permanent magnet. Next, depending on a participant’s skills and interests, they will be free to develop new feedback algorithms, develop control and interaction schemes, implement LTDM on their own supplied instrument, and/or build musical mechanisms with the supplied materials.

# Call for Participation
**Intended Audience:** The workshop is aimed towards instrument designers, musicians, and/or engineers who would like to create feedback actuated electroacoustic instruments. The focus of the workshop will be on developing/tweaking/hacking the audio software algorithms within the feedback path and prototyping physical mechanisms that couple strings and magnets. To get the most out of the workshop, participants will ideally have experience with any of the following:
- Programming in the Arduino/Teensy environment
- DSP Concepts
- Building/modifying Max/MSP patches
- Rapid prototyping with simple materials and hand tools

Note: An understanding of hardware or circuit concepts is not required nor is it the focus of this workshop. Individuals may pair/team up if they find that they have complementary skillsets.

Please sign up here to attend the workshop: [Sign-up Link](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=B3WJK4zudUWDC0-CZ8PTB9QuUbj7BKhDgUWiQeRTMqlUMkZTQzlJSjFWWDI4NEw1UUpNOVZYTTVaNC4u)

# Motivation
This workshop is a follow-up to the NIME 2012 Actuated Acoustic Instruments Workshop organized by McPherson, Berdahl,
Snyder, & Britt at a time when the community was seeing new actuated instruments year after year. Since then, NIME has seen interest in this space grow with many additional new actuated and feedback instruments, reflections on feedback and feedback-actuated instruments in general, and the alternate method of string actuation known as Lorentz force actuation become better understood.

The newly-developed LTDM kit works by first sensing the string’s velocity, which is proportional to the electromotive
force (EMF) voltage induced in the string as it moves in a magnetic field. Next, applying an electric current to the
string to induces a Lorentz force that can physically move the string. This is the same basic principle as a microphone
coil or speaker coil, but one can imagine the coil has been unwound, stretched out, and put under tension. Just as in a
guitar pickup, microphone, or speaker, the key to transduction between electrical and mechanical domains is a magnetic
field near to the wire. In our case, this is provided by a strong permanent neodymium magnet. The hardware then rapidly
alternates between sensing and actuating modes (at 20kHz), a scheme characteristic of Time Division Multiplexing (TDM). We are then granted ability to feed the sensed signal back into the actuation hardware nearly simultaneously but without electrical crosstalk because the sensing and actuating events are isolated in time rather than space (see below figure). The result is the indefinitely sustaining vibrations in a string similar to an eBow Sustainer, Sustainiac, Fernandes Sustainer, or Moog Guitar.

<img width="3128" alt="LTDM" src="https://github.com/user-attachments/assets/fe207f84-cd10-476c-bd8e-86fb8e33b239" />

The LTDM kit makes the deployment of feedback-actuated instruments simpler than ever with the minimum requirements to build a feedback system being just two electrical leads, a conductive resonant string, and a permanent magnet. No computers, calibrations, or theoretical understanding of the system are required to deploy a new feedback system, making the kit ideal for a short workshop with the barrier to making a new feedback string instrument being lower than ever. All of the hardware requirements for this feedback-actuation scheme have been designed into the portable kit so that electronic luthiers can focus on coaxing out new timbres, interactions, and behaviors out of the same strings that have been found on instruments for centuries. We have developed a handful of LTDM-based instrument configurations already, but there are seemingly endless possibilities for how to deploy and enjoy this hardware technology. New timbres have been explored thus far by altering the code within the feedback scheme, experimenting with magnet positions and arrangements,and by creating resonant mechanisms with emergent behavior(s). We wish to engage the creativity of the NIME community to explore additional playing techniques, software algorithms, and instrument morphologies. Some example project ideas that could be investigated during the workshop include (but are not limited to):
- A physical synthesis step sequencer (similar to Korg Phase8)
- A Lorentz force feedback-actuated ukulele or lap steel
- A no-input-mixing setup where a string is part of the feedback path (via the send & return jacks on the kits)
- A room-length actuated string, inspired by Lucier’s Music on a long, thin wire

# Intended audience
The workshop is aimed towards instrument designers, musicians, and/or engineers who would like to create feedback actuated electroacoustic instruments. The focus of the workshop will be on developing/tweaking/hacking the audio software algorithms within the feedback path, prototyping physical mechanisms that couple strings and magnets. To get the most out of the workshop, participants will ideally have experience with any of the following: Programming in the Arduino/Teensy environment, DSP, modifying Max/MSP patches, or rapid prototyping with simple materials and hand tools. An understanding of hardware or circuit concepts is not required nor is it the focus of this workshop. Individuals may pair or team up if they find that they have complementary skillsets.

# Workshop Schedule
The first 30 minutes of the workshop will cover the basics of Lorentz force actuation, demonstrate how to use the LTDM kit's presets and end with an interactive demonstration of some current systems and prototypes that use the LTDM kit. The next 30 minutes will be hands-on yet open-ended. LTDM kits will be distributed, and participants will be welcome and encouraged to explore the supplied instruments and materials with the LTDM kit presets to inspire ideas for new interactions and/or mechanisms. Individuals may take this time to try LTDM on their own instruments should they have brought one.

We will then regroup to hear ideas and thoughts from participants on their intended next steps and allow time for further questions regarding LTDM theory or the kits themselves. Individuals with complementary ideas and/or skills may decide to work together for the remainder of the workshop. Next, we will go over how to program the LTDM kit in both the firmware code or with Max/MSP. Following this, the sessions will have a short break.

As individuals return, we return to hands-on work time. During this time, the organizers will act as technical support for the participants, offering programming help or assistance building instrument prototypes and mechanisms. At the end of the session, participants will share the systems they have built and the sounds they generate.

| Workshop Schedule, beginning at 4pm | |
|---|---|
| Organizer and participant introductions | 10 minutes |
| LTDM background and theory of operation | 10 minutes |
| Demonstrations + Q&A | 10 minutes |
| Hands-on work time | 30 minutes |
| Regroup & share initial ideas | 10 minutes |
| Practical material and programming considerations | 10 minutes |
| Break | 10 minutes |
| Hands-on work time | 2 hours |
| Present instruments and/or algorithms | 30 minutes |

# LTDM Kit
Participants will be given the following during the workshop:
- **LTDM Kit** for driving 2 string channels (note that this does not mean the kits are limited to actuating just 2 strings). A paper on the kit’s technical design, a music installation in the installation track, and an alt.nime submission featuring instruments that use the kit are all featured this NIME 2026.
- **Conductive strings** of various gauges and lengths.
- **Permanent magnets** of various geometries and strengths.
- **Instrument Parts** to build monochords or other simple instruments (i.e., wood, tuning pegs, bridges, etc.)
- **A few premade instrument prototypes** such as zithers and monochords will be available for those that are most
interested in diving into software development rather than physical prototyping.

<img width="2371" alt="LTDMKit" src="https://github.com/user-attachments/assets/768db1e7-9057-493a-8a6f-dce901dca183" />

The focus of the workshop is primarily on evoking interesting feedback-actuation behavior through mechanical design,
programming (in C or Max/MSP), or some interesting interaction between mechanism and software. Given the flexible
nature of the workshop, participants are recommended to bring a laptop with either the Arduino IDE or Max/MSP to
program the LTDM kit. However, there are several alternative ways to engage in the workshop.
- Work in Arduino IDE to program the LTDM Kit’s UI and signal processing
- Use our supplied starter Max/MSP patch to control the kit
- explore various resonant mechanisms with LTDM presets
- build a new instrument with the LTDM presets
- any combination of the above

<img width="4041" alt="LTDM_RevB" src="https://github.com/user-attachments/assets/57c93732-60ce-4b99-9fe1-67b1f6420c7a" />

# Organizers
**Adam Schmidt** is a PhD Student at Imperial College London's Dyson School of Design Engineering working on designing electromagnetically actuated instruments under the direction of Professor Andrew McPherson in the Augmented Instruments Lab. He received his bachelor's in Sound Engineering and Electrical Engineering and master's in Performing Arts Technology from the University of Michigan. His research investigates how vibrations within instruments can be augmented via electronic feedback and alternative transduction methods. Lately he has been focusing on Lorentz force actuation in instruments such as the Lorentz Lap Brass  with Michael Gurevich, the Sparksichord with Jeff Snyder and Andrew McPherson, and the Weather Harp with Molly Jones and Michael Gurevich.

**Andrew McPherson** is a computing researcher, composer, electronic engineer, and musical instrument designer. He is Professor of Design Engineering and Music in the Dyson School of Design Engineering, Imperial College London, where he leads the Augmented Instruments Laboratory. Andrew holds undergraduate degrees in both engineering and music from MIT, an MEng in electrical engineering from MIT, and a PhD in music composition from the University of Pennsylvania. Prior to joining Imperial in 2023, he has been a professor in the Centre for Digital Music at Queen Mary University of London. He is the creator of the magnetic resonator piano, an electromagnetically-augmented acoustic piano that has been used in dozens of pieces across several genres. He was a co-organiser of the NIME 2012 actuated instruments workshop.

**Jeff Snyder** is a composer, improviser and instrument-designer living in Skillman, New Jersey, and active in the New York City area. He is the Director of Electronic Music at Princeton University, and the Director of PLOrk, the Princeton Laptop Orchestra. Jeff received a doctorate in music composition from Columbia University. He regularly performs on instruments he designed and built, including the Electrosteel, the Electrobass, the Vocodec, and the Manta. He also leads a band as his electro-country alter ego Owen Lake, and co-runs the experimental music label Carrier Records. He was also a co-organiser of the NIME 2012 actuated instruments workshop.

---

This site will be updated as the workshop approaches. Registered participants will be updated via email. If you have questions in the meantime, please don't hesitate to reach out to a (dot) schmidt24 (at) imperial (dot) ac (dot) uk
