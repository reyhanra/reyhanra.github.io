---
layout: posts
title: "The Sound of Life: Acoustics Around Us"
date: 2018-03-26
---

For the past two months, I've had the honor of attending [Prof. Jeong-Guon Ih](https://www.researchgate.net/profile/Jeong_Guon_Ih)'s lecture in the field of acoustics. Acoustics is an interesting, if a bit underrated, field in engineering and building physics, so I thought it would be interesting to share several aspects of acoustics. In this post, I'll describe three things: the (human) hearing mechanism, acoustic materials, and transmission loss and soundproofing.

# Our Hearing

*Or: the beginning of everything acoustics.*

As with almost every technical fields out there, nature remains the best engineer. Our hearing mechanism is very fascinating indeed. It's capable of amplifying, discerning, and ultimately decoding the myriads of information coming to our ears, all in a span of a couple of milliseconds! So, before we dive into other aspects of acoustics engineering, let's look into the engineering marvel that lies (literally) within ourselves:

![The human ear]({{ "/assets/ear-anatomy.png" | absolute_url }})

Our seemingly complicated ears can be divided into three components: the "horn", the "microphone", and the "analyzer". A sound wave's journey into our minds start with the (3) **auricle** (or *pinna*, a word that sounds like a [pasta](https://en.wikipedia.org/wiki/Penne) that actually means "wing"). The auricle's job is to redirect as much sound wave into our ear as possible, while amplifying it around 2-3 times (a modest gain, as we will see). From there, the sound wave enters the (2) auditory canal, which connects to the (4) **eardrum** (or the "tympanic membrane"). Just like it's namesake, the eardrum is a flexible membrane and serves to transfer vibrations to the (6-8) **ossicles**, a series of hearing bones with possibly the coolest name in the body, the *malleus*, *stapes*, and *incus*. These three bones together provides ~45 times amplification to the sound wave before entering the (10) **cochlea**. It is in the cochlea the hard work of decoding the different frequencies in the sound wave happens.

The cochlea is a structure consisting of three chambers (the upper *scala vestibuli*, middle *scala media*, and lower *scala tympani*, joined at the *helicotrema*), Reissner's membrane, basilar membrane, and the organ of Corti. Inside the organ of Corti are the hair cells which fires electrical impulses in response to sound waves, thus sending hearing information to the nerves and, ultimately, the brain.

When hearings fail, there are technologies that can help. This ranges from the simple hearing trumpet (which basically helps the auricle) to electrical amplifiers, like the **BTE** (behind-the-ear), **CIC** (completely-in-the-canal), **ITC** (in-the-canal), and **ITE** (in-the-ear). All electrical amplifiers behave as an ear-slash-mouth, picking up sound waves, amplifying them, and then delivering them to the ear.

These simple hearing aids help your ear the way an eyeglasses help your eyes---by modifying the incoming signal so your sensory system can pick it up. There are more advanced hearing aids that can help when your ear doesn't work at all (a condition called *nerve deafness*). These hearing aids are called **cochlear implant**. Just as its name implies, the cochlear implant takes over the cochlea's function, converting sound waves into electrical impulses and feeding it directly to your nerve.

# Acoustic Materials

*Or: bending sound waves to your will*

Now, while your ear is a very capable sensory system, it remains dependent on whatever sound wave enters the ear. No amount of hearing aid will help if the sound wave in a room, for example, is dispersed poorly. Thankfully, there are several ways to improve sound distribution in an area.

One of them is through the use of **acoustic materials**. These materials absorbs or reflects incoming sound wave, changing the distribution of sound inside a room. In this post, I'll only be describing absorber materials. There are several types of absorber materials, including:

1. **Porous materials** are materials that have cavities mostly filled with air. These cavities "trap" the sound wave and convert them into heat, effectively absorbing the wave. Porous materials works best at high frequencies.
2. **Panel absorbers** are thin sheets installed a distance away from a rigid wall, forming an air space between them. This sheet vibrates due to the incoming sound wave and absorbs the wave's energy. Panel absorbers work best at low frequencies.
3. **Cavity absorbers** or Helmholtz absorbers are air pockets, bound by rigid boundaries, that are connected to the room through an opening. It absorbs sound wave through resonance and thus works best around those resonance frequencies.

An easy way to improve the acoustic property of a room you can't otherwise control is to add acoustic materials (absorbers included). A lecture auditorium, for example, requires speech intelligibility. This can be improved by taking into account direct sound path between the speaker and the listeners and the sound reflections from the walls. While direct sound is difficult to improve without altering the design of the room (by using inclined floor, for example), reflections can be improved through the addition of acoustic materials. Panel absorbers could be installed on the rear ceiling and rear wall (far from the speaker) to reduce reverberation time. Porous materials could be installed on the side walls to avoid distracting echoes. The front wall and front ceiling will need reflective materials to maximize reflection to the audience.

# Transmission Loss

*Or: what happens in the room stays in the room*

Equally important to improving sound quality inside the building is improving sound isolation so that people outside the room are not disturbed. If you're ever disturbed by your neighbor's loud music, you know what I'm talking about. A material's ability to keep sound in and neighbors happy is related to its **transmission loss**, which is how much a sound lose its power as it travels through a material.

Before discussing transmission loss, let's look into an interesting phenomenon called the *coincidence effect*. Coincidence effect is a phenomenon where a stiff material passes through a certain frequency range exceptionally well. This happens because of bending wave that forms in the material transfers sound far more efficiently than normal.

The coincidence effect, along with the general mass and stiffness of the material, relates to the transmission loss characteristics of a material. There are four regions of transmission loss in a material:

![Transmission loss diagram]({{ "/assets/transmission-loss.gif" | absolute_url }})

1. The **stiffness-controlled** region, where mass and damping have little effect. This region usually affects very low frequencies, and thus are of little importance.
2. The **resonance-controlled** region, which occurs around the natural frequency of the material (which also depends on the dimension of the material). In this region, the material vibrates more easily due to resonance and thus have less transmission loss.
3. The **mass-controlled** region, which occurs beyond the resonance region, is the most important region. In this region, the material more-or-less follows the mass law, which states that if you double the density of the material, the transmission loss increases by about 6 dB.
4. The **coincidence-controlled** region occurs beyond a certain critical frequenct. In this region, the coincidence effect severely reduces a material's ability to block sound waves. This usually matters more in wooden materials (metals have a very high critical frequency).

How a material behaves, along with the activities done inside the room, is critical to designing a soundproof room. A classroom, for example, need to contain speeches and conversations. These activities mostly lie within the mid-frequency range where the transmission loss is mass-controlled. It is fairly easy to design the walls to limit sound transmission outside the room (a reasonably thick brick wall will do). In contrast, a music room needs to contain sounds in the low frequency range. This may lie in the resonance-controlled region, thus greater care is needed in selecting the material. The walls may need to be thicker to accomodate the low frequency sounds.

# Sources

1. L. E. Kinsler, A. R. Frey, A. B. Coppens, and J. V. Sanders, *Fundamentals of Acoustics*, 4th Ed. NY: John Wiley & Sons, 2000.
2. C. Woodford, 'Hearing aids', 2018. Available: http://www.explainthatstuff.com/hearingaids.html.
3. 'Cochlear Implants'. Available: http://www.hearingloss.org/content/cochlear-implants.
4. J. P. Parkinson, "Acoustic Absorber Design", M.S. Thesis, Dept. of Mech. Eng., Univ. of Canterbury, Christchurch, 1999.
5. M. Remes, "Acoustical Design." Aalto University, 2015.
6. Juha, 'Basic of soundproofing'. Available: http://personal.inet.fi/koti/juhladude/soundproofing.html.
7. 'Sound: Transmission'. Available: http://wiki.naturalfrequency.com/wiki/Sound_Transmission.
