Title: ‎Gemini - direct access to Google AI

URL Source: https://gemini.google.com/share/04ebf1fd59d0

Markdown Content:
‎Gemini - direct access to Google AI
===============

[Sign in](https://accounts.google.com/ServiceLogin?passive=1209600&continue=https://gemini.google.com/share/04ebf1fd59d0&followup=https://gemini.google.com/share/04ebf1fd59d0&ec=GAZAkgU)

[Gemini](https://gemini.google.com/app)

[About Gemini Opens in a new window](https://gemini.google/about/?utm_source=gemini&utm_medium=web&utm_campaign=gemini_zero_state_link_to_marketing_microsite)[Gemini App Opens in a new window](https://gemini.google.com/app/download)[Subscriptions Opens in a new window](https://one.google.com/ai)[For Business Opens in a new window](https://workspace.google.com/solutions/ai/?utm_source=geminiforbusiness&utm_medium=et&utm_campaign=gemini-page-crosslink&utm_term=-&utm_content=forbusiness-2025Q3)

**Semiconductor Fundamentals Curriculum Design**
================================================

[https://gemini.google.com/share/04ebf1fd59d0](https://gemini.google.com/share/04ebf1fd59d0)

 Created with **Thinking** January 25, 2026 at 08:33 AM Published January 30, 2026 at 05:53 PM

I’m interested in learning about semiconductors kind of from the ground up. I’m somewhat familiar with basics: transistors, diodes, mosfets. What other applications do they have? What is the back story here and how did we get to semiconductors? How did we turn them into different useful components?

Please design a curriculum to learn this in the SolveIt platform.

I’d like a lot of practical exercises where relevant - direct experiences with the learning subject where possible, but indirect/analogous/simulated are also fine.

Start out by asking any clarifying questions and then I’ll ask you to generate the curriculum.

It’s great to see you diving into the "physics-to-function" side of electronics! Moving from "I know what a MOSFET does" to "I understand how the lattice structure makes it happen" is a rewarding jump.

Since you're looking for a "SolveIt" style curriculum—which emphasizes deep understanding through problem-solving—I want to make sure the "practical" side aligns with the gear you have or the environment you prefer.

Before I draft the syllabus, I have a few clarifying questions:

*   **Breadboard vs. Simulation:** You’ve done some great work with real components (like your boost converter and Darlington pair). For this curriculum, do you want to stick strictly to **physical components** (diodes, BJTs, MOSFETs) where possible, or are you interested in using **simulators** (like Falstad or LTspice) to visualize things like electron flow and depletion regions that you can't "see" on a bench?

*   **Math Comfort Level:** How deep do you want to go into the "physics" math? We can keep it at a high-level conceptual level (holes, electrons, and doping) or dive into things like the Fermi level and the Shockley diode equation.

*   **The "Why":** Beyond just understanding the components, is there a specific "end-game" application you’re curious about? (e.g., How a CPU logic gate is formed from scratch, or perhaps how specialized sensors like photodiodes or LEDs work at the atomic level?)

*   **Historical Context:** Are you interested in the "Great Man/Lab" history (Shockley, Bardeen, Brattain at Bell Labs) or more of the "Evolution of Material Science" (from vacuum tubes to silicon)?

Once I have a better feel for your preferred balance of "physics vs. workbench," I’ll generate a comprehensive curriculum for you!

Breadboard vs. Simulation: -> bias toward physical, real experiments and demonstrations but use simulations where it’s obviously better or more reasonable. For physical things it’s okay to need to buy objects or consumables.

Math Comfort Level -> not deep into physics but it’s okay to dip in and see how we do

The "Why" -> enough both historical as well as practical and theoretical understanding to digest information about contemporary semiconductor use and have an informed understanding of what’s going on with computers.

I’m also interested in hearing about a wide array of uses of semiconductors, without the need to go too deep into them.

Biasing toward the “Evolution of Material Science” version of the story.

This is a fantastic path to take. Moving from "the component is a black box" to "the component is a piece of engineered material" changes how you look at every piece of silicon on your workbench.

Based on your preference for physical experiments and the "Material Science" evolution of the story, here is a curriculum designed for the SolveIt platform. It is structured to move from raw materials to complex logic.

* * *

Curriculum: The Silicon Alchemy
-------------------------------

**Goal:** To understand how we engineered matter to control electricity, leading from vacuum tubes to the modern CPU.

### Phase 1: The Pre-Semiconductor Era (The "Space" Problem)

*   **The Concept:** Before silicon, we had the vacuum. How do you control electricity without moving parts?

*   **The History:** The Edison Effect and the birth of the Vacuum Tube.

*   **Practical Exercise:** * **The Lightbulb Experiment:** Using a clear incandescent bulb (if you can find one) or a high-wattage resistor, observe how heat changes resistance.

    *   **Simulation:** Use Falstad to "build" a vacuum tube triode. Visualize how a grid of wire in a vacuum can "pinch" a stream of electrons.

*   **SolveIt Challenge:** "Why did we need to get rid of the vacuum?" (Focus on heat, scale, and reliability).

### Phase 2: The Magic of Doping (Building the Lattice)

*   **The Concept:** What makes a "semi"-conductor? It’s all about the crystal structure of Silicon and Germanium.

*   **The Science:** Introduction to P-type and N-type materials. How adding a "impurity" (Boron or Phosphorus) creates "holes" or "extra electrons."

*   **Practical Exercise:**

    *   **The Pencil Lead Rheostat:** Use graphite (a semi-metal/semiconductor) to create a variable resistor. Explore how mechanical pressure or heat changes its conductivity.

    *   **Analogy Build:** Create a physical model of a Silicon lattice using marbles or LEDs to represent "holes" vs. "electrons" to visualize "drift" vs. "diffusion."

### Phase 3: The PN Junction (The One-Way Valve)

*   **The Concept:** When you smash P and N together, magic happens at the border: The Depletion Region.

*   **The History:** Cat's-whisker detectors in early crystal radios.

*   **Practical Exercise:**

    *   **The Diode "Turn-on" Mystery:** Use your multimeter to measure the forward voltage drop of a Silicon diode vs. a Schottky diode vs. an LED. Why are they different?

    *   **The Temperature Sensor:** Use a diode as a thermometer. Watch the voltage drop change as you touch it with your finger or a soldering iron (carefully!).

*   **SolveIt Challenge:** "Predict the IV curve of a diode using only a battery, a pot, and your multimeter."

[![Image 1: Image of ](https://encrypted-tbn3.gstatic.com/licensed-image?q=tbn:ANd9GcTttY9lZaVUXNrqRd9eOrSc7XizHWH6FnxVqw_0NYjw7b-yD9jhZ_TfHgT2vss9C0xeD4eIW5w6loALRPK-P_BC5MsFI_cDUMzYhMO-IVS1O52PfZM) Opens in a new window](https://encrypted-tbn3.gstatic.com/licensed-image?q=tbn:ANd9GcTttY9lZaVUXNrqRd9eOrSc7XizHWH6FnxVqw_0NYjw7b-yD9jhZ_TfHgT2vss9C0xeD4eIW5w6loALRPK-P_BC5MsFI_cDUMzYhMO-IVS1O52PfZM)

Shutterstock

 Explore 

### Phase 4: The Transistor Revolution (BJT vs. MOSFET)

*   **The Concept:** Using a small current (BJT) or a small voltage (MOSFET) to control a large current.

*   **The Science:** Minority carriers and the "Field Effect."

*   **Practical Exercise:**

    *   **The Human Resistor:** Build a high-gain Darlington pair (which you've done!) but use your own body's resistance as the "base" trigger to turn on an LED.

    *   **MOSFET Gate Capacitance:** Charge the gate of a MOSFET with a battery, then disconnect it. Observe how the LED stays on because the "gate" acts like a tiny capacitor holding the "field" open.

*   **SolveIt Challenge:** "Design a circuit where a BJT acts as a switch, then modify it to act as a linear amplifier. What is the physical difference in how the electrons are moving?"

### Phase 5: The "Wide Array" of Semiconductor Flavors

*   **The Concept:** Beyond switches. How do we make semiconductors move, glow, or sense?

*   **The Survey:**

    *   **Optoelectronics:** LEDs (converting electrons to photons) and Photodiodes (the reverse).

    *   **Power Electronics:** IGBTs (the heavy lifters in EV inverters).

    *   **Sensors:** Hall Effect (magnetic), Piezoelectric (pressure), and MEMS (accelerometers).

*   **Practical Exercise:** * **The Solar Cell as a Sensor:** Use a small solar cell or an LED as a light sensor. Measure the micro-voltage generated when light hits the PN junction.

### Phase 6: The Integrated Circuit (The Modern Miracle)

*   **The Concept:** How do we put 10 billion of these on a fingernail? Photolithography and the "planar process."

*   **The Theory:** Logic Gates (NAND, NOR) built from MOSFETs.

*   **Practical Exercise:**

    *   **The Discrete Logic Gate:** Build a 2-input NAND gate using only individual N-channel MOSFETs.

    *   **Simulation:** Use a logic simulator to see how thousands of these gates form an ALU (Arithmetic Logic Unit).

*   **Final SolveIt Project:** "Tracing a Bit." Follow a single signal from a physical switch press, through a debouncing semiconductor circuit, into a logic gate.

* * *

### A Wide Array of Semiconductor Uses

To give you a taste of the diversity you'll encounter:

1.   **Thermoelectric Coolers (TEC):** Semiconductors that move heat from one side to the other when current flows (The Peltier Effect).

2.   **Varactors:** Diodes that act as voltage-controlled capacitors, used to tune your SDR radio.

3.   **Zener Diodes:** Diodes engineered to "break" at a very specific voltage, used for voltage regulation.

4.   **Laser Diodes:** Highly engineered junctions that bounce photons back and forth to create coherent light for fiber optics.

* * *

**Would you like me to expand on the "Phase 1" reading material and experiments to get you started, or would you like to tweak the order of these topics?**

Let's set up a list of components that I need to understand and explain as well.

To build a truly "ground up" understanding, you need a kit that represents the evolutionary milestones of material science. Instead of just buying a generic "1000-piece resistor kit," we should focus on components that demonstrate specific physical phenomena.

Here is the essential "Semiconductor Genealogy" list. These are the parts you'll want on your bench to transition from "I know what this is" to "I know why this works."

* * *

### 1. The Foundation: PN Junctions

These components demonstrate how we first learned to control the direction of charge.

Component What it teaches Why it's in the curriculum
**1N4148 (Signal Diode)**The Depletion Region The classic high-speed silicon switch. Great for seeing the 0.7V "barrier."
**1N5817 (Schottky Diode)**Metal-Semiconductor Junction Lower voltage drop and faster switching. It’s a different "flavor" of physics.
**1N47xx Series (Zener Diode)**Reverse Breakdown Learn how we "engineered" a part to fail safely at a specific voltage to create regulation.
**Red & Blue LEDs**Bandgap Energy Why do different colors require different voltages? It's literally the "gap" electrons jump across.

Export to Sheets

### 2. The Amplifiers: Bipolar Junction Transistors (BJT)

These represent the first "Solid State" revolution—using current to control current.

*   **2N3904 (NPN) & 2N3906 (PNP):** The "Hello World" of transistors. You'll use these to understand **Minority Carrier Injection** (how a tiny base current floods the middle layer with charge).

*   **TIP120 (Darlington Pair):** A "transistor inside a transistor." It demonstrates how we can chain semiconductor structures to multiply gain.

### 3. The Field Effects: MOSFETs

This is the technology that makes modern computing possible. It's about using an electric **field** to open a channel without drawing any current into the "gate."

*   **2N7000 (Small Signal N-Channel):** Perfect for breadboarding logic gates.

*   **IRFZ44N (Power MOSFET):** A beefy component to understand **R_ds(on)**—the internal resistance of the silicon channel—and how heat dissipation works at the material level.

*   **AO3401 (P-Channel):** Understanding the "inverse" logic of holes vs. electrons.

### 4. The Functional Blocks: Integrated Circuits (ICs)

Once you understand the discrete parts, you see how we shrunk them and crammed them into "black boxes."

*   **LM358 (Op-Amp):** The "Analog Computer." It uses dozens of internal transistors to perform math on voltages.

*   **74HC00 (NAND Gates):** This is the bridge to computers. You’ll see how four MOSFETs arranged specifically create the "Universal Gate" that can build any computer in the world.

*   **TL431 (Shunt Regulator):** A "programmable Zener." It’s a fascinating look at how a tiny IC can act like a single, perfect component.

### 5. The "Weird" Physics (Specialized)

*   **CdS Photoresistor / Photodiode:** How light (photons) physically knocks electrons loose in a semiconductor lattice.

*   **Hall Effect Sensor (e.g., AH3503):** How a magnetic field pushes electrons to one side of a conductor (the Hall Effect), creating a measurable voltage.

* * *

### The "Explain This" Challenge

As you move through the curriculum, your goal is to be able to explain each of these using only three concepts:

1.   **The Lattice:** Where the atoms are.

2.   **The Charge Carriers:** Where the electrons (and holes) are.

3.   **The Barrier:** What is stopping them from moving, and how are we "tricking" the material into letting them through?

**Would you like me to create a "Shopping List" with specific quantities and a breakdown of the first experiment involving the Signal Diode vs. the Schottky Diode?**

Yes

To build a laboratory that traces the **evolution of material science**, you will need a set of components that each represent a specific breakthrough in how we control the "invisible" world of charge carriers.

### The Semiconductor Shopping List

For the most effective learning, focus on these specific parts. They are common, inexpensive, and each demonstrates a unique physical principle.

The [Adafruit 1N4148 Signal Diode 10 Pack](https://google.com/search?q=Adafruit+1N4148+Signal+Diode+10+Pack&prds=catalogid%3A13754041179079405185%2Cgpcid%3A756351348573263236%2CheadlineOfferDocid%3A11436203225891731055%2Cmid%3A576462852185670638%2Cproductid%3A12826592940849650020%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) is the industry standard for **small signal rectification**. It will help you visualize the **0.7V turn-on barrier** and is fast enough to show why early computers could finally ditch vacuum tubes.

[![Image 2: Adafruit 1N4148 Signal Diode 10 Pack](https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcQteXB0TsBGAiZYIBtHahiFXPaoNNtKnYz_UDl2QgNJp680-g5nQkaNk8PgbRM)![Image 3: Adafruit 1N4148 Signal Diode 10 Pack](https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcRk17yW5lqaRUWCgy83IzSFxz1KsHOSG16m3Dd56xxdblH58cfSAbglrNivxg)![Image 4: Adafruit 1N4148 Signal Diode 10 Pack](https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcQqVjht-Wanbke7T26grCkegNV1d7CDWladzDz0DiS1KaAIeaYkUQVT3zcYicA) Adafruit 1N4148 Signal Diode 10 Pack $1.50 Adafruit 5 (2) Opens in a new window](https://google.com/search?q=Adafruit+1N4148+Signal+Diode+10+Pack&prds=catalogid%3A13754041179079405185%2Cgpcid%3A756351348573263236%2CheadlineOfferDocid%3A11436203225891731055%2Cmid%3A576462852185670638%2Cproductid%3A12826592940849650020%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1)

The [Bojack 1N5817 Schottky Diode](https://google.com/search?q=Bojack+1N5817+Schottky+Diode+1+A+20+V+DO-41+Axial+5817&prds=catalogid%3A5570536117430191302%2Cgpcid%3A6037545950596382000%2CheadlineOfferDocid%3A12361786144494650486%2Cmid%3A576462375557385127%2Cproductid%3A3439429434433566922%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) uses a **metal-semiconductor junction** rather than a standard PN junction. This results in a significantly **lower forward voltage drop**, demonstrating how changing material interfaces alters efficiency.

[![Image 5: Bojack 1N5817 Schottky Diode 1 A 20 V DO-41 Axial 5817](https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcRWeSCeMVRBvWOZ2NmD2tjZoVg9Z1H7Ux0OIhnJm3-ej80S3yzhBUI2tXj9Rlo)![Image 6: Bojack 1N5817 Schottky Diode 1 A 20 V DO-41 Axial 5817](https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcRgIfboiLpjBNtJi_yH4D7iolOpRV7p2Y4rk7ui9t1Ytd5RmTn1ebB8ZMJ5hfWlHusAQFEm4kHM)![Image 7: Bojack 1N5817 Schottky Diode 1 A 20 V DO-41 Axial 5817](https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcQwX6i0nyeJ92AZUF_E9X0dq_Md3HdvpcFOe8evkYkKEWu7jhEHMlob2tFhfdLzmByvQNiq1Ek) Bojack 1N5817 Schottky Diode 1 A 20 V DO-41 Axial 5817 $9.65 Opens in a new window](https://google.com/search?q=Bojack+1N5817+Schottky+Diode+1+A+20+V+DO-41+Axial+5817&prds=catalogid%3A5570536117430191302%2Cgpcid%3A6037545950596382000%2CheadlineOfferDocid%3A12361786144494650486%2Cmid%3A576462375557385127%2Cproductid%3A3439429434433566922%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1)

For understanding **voltage regulation**, the [Addicore 1N4733A Zener Diode](https://google.com/search?q=Zener+Diode+5.1V+1W&prds=catalogid%3A18414676246053338340%2Cgpcid%3A10933975241792391517%2CheadlineOfferDocid%3A1238135443002587174%2Cproductid%3A16721448373298589400%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) is essential. It is designed to "break" at exactly **5.1V** in reverse, showing how engineers turned a material failure (breakdown) into a useful feature.

[![Image 8: Zener Diode 5.1V 1W](https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcQDA9McC2WfEHNLjn_wVZOgbrNfqtgzPJyQbu25obzTmZADfNDKURLqtwUcHlMOxPP7LenZNr4K) Zener Diode 5.1V 1W $0.20 Tinkersphere 5 (24) Opens in a new window](https://google.com/search?q=Zener+Diode+5.1V+1W&prds=catalogid%3A18414676246053338340%2Cgpcid%3A10933975241792391517%2CheadlineOfferDocid%3A1238135443002587174%2Cproductid%3A16721448373298589400%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1)

To explore **active switching**, the [eElectronicParts 2N3906 + 2N3904 pairs](https://google.com/search?q=100Pcs+50+x+2N3906+PNP+%2B+50+x+2N3904+NPN+pairs+TO-92+general+purpose+transistors&prds=headlineOfferDocid%3A8301898972714192684%2Cproductid%3A8301898972714192684%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) provide both NPN and PNP types. These allow you to experiment with **Minority Carrier Injection**, the fundamental physics behind the first solid-state amplifiers.

[![Image 9: 100Pcs 50 x 2N3906 PNP + 50 x 2N3904 NPN pairs TO-92 general purpose transistors](https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcTyrYVubX4OwsqbHoF9Kmgc3hAD85akammiDlbrdvRM1pPYd8IGgEWXvj3i7A0aiXb8Crv2_Lei)![Image 10: 100Pcs 50 x 2N3906 PNP + 50 x 2N3904 NPN pairs TO-92 general purpose transistors](https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcRKhqW-_iIs8IpfH5HqG6KYgV4vzFHKq4TBs_RHGDhvI6elFMmEc54P3glXBoX4X23PyMu4aiA) 100Pcs 50 x 2N3906 PNP + 50 x 2N3904 NPN pairs TO-92 general purpose transistors $8.98 Opens in a new window](https://google.com/search?q=100Pcs+50+x+2N3906+PNP+%2B+50+x+2N3904+NPN+pairs+TO-92+general+purpose+transistors&prds=headlineOfferDocid%3A8301898972714192684%2Cproductid%3A8301898972714192684%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1)

The [Addicore 2N7000 N-Channel MOSFET](https://google.com/search?q=Addicore+2N7000+N-Channel+MOSFET+(TO-92+package)&prds=headlineOfferDocid%3A5931602055230778327%2Cproductid%3A5931602055230778327%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) is a **Field-Effect Transistor** that uses an electric field to open a channel. It’s the closest discrete relative to the billions of transistors inside your computer's CPU.

[![Image 11: Addicore 2N7000 N-Channel MOSFET (TO-92 package)](https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcSEKR0eLWIUpE3PWT3Qz13XT9t4ZLJouF1xE9iNUb-hlJnB1HTutE7wGTQE_k7wZQ2m8lOE3es)![Image 12: Addicore 2N7000 N-Channel MOSFET (TO-92 package)](https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcTm0tnYBMUBXFgnM-bbUdu6kxmf5K3dl0NngeMvVudyr0P8IWWVnZRSG18zafrf-ibxJyXKQ_js) Addicore 2N7000 N-Channel MOSFET (TO-92 package) $0.15 ON Semiconductor 4.6 (11) Opens in a new window](https://google.com/search?q=Addicore+2N7000+N-Channel+MOSFET+(TO-92+package)&prds=headlineOfferDocid%3A5931602055230778327%2Cproductid%3A5931602055230778327%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1)

Finally, the [Jameco 74HC00 NAND Gate](https://google.com/search?q=Ic+74HC00+Quad+2-Input+Nand+Gate&prds=headlineOfferDocid%3A14139829816286882667%2Cproductid%3A14139829816286882667%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) represents the first level of **integration**. It packs multiple MOSFETs into one chip to perform logic, proving that you can build any complex system from simple NAND blocks.

[![Image 13: Ic 74HC00 Quad 2-Input Nand Gate](https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcTvTe5l4KFVybsGtpIPpwxnaZj8v7pw-VGXac-T9zflGG5_DD5oevH_ugRZ8W5yNsA2DAQ-0GGe) Ic 74HC00 Quad 2-Input Nand Gate $0.59 Major Brands Opens in a new window](https://google.com/search?q=Ic+74HC00+Quad+2-Input+Nand+Gate&prds=headlineOfferDocid%3A14139829816286882667%2Cproductid%3A14139829816286882667%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1)

* * *

### Phase 1 Experiment: The Diode "Turn-On" Mystery

This first experiment demonstrates the **Depletion Region**—the invisible wall that prevents current from flowing until a specific energy threshold is met.

**Equipment Needed:**

*   **Diodes:**[1N4148](https://google.com/search?q=Adafruit+1N4148+Signal+Diode+10+Pack&prds=catalogid%3A13754041179079405185%2Cgpcid%3A756351348573263236%2CheadlineOfferDocid%3A11436203225891731055%2Cmid%3A576462852185670638%2Cproductid%3A12826592940849650020%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) (Silicon) and [1N5817](https://google.com/search?q=Bojack+1N5817+Schottky+Diode+1+A+20+V+DO-41+Axial+5817&prds=catalogid%3A5570536117430191302%2Cgpcid%3A6037545950596382000%2CheadlineOfferDocid%3A12361786144494650486%2Cmid%3A576462375557385127%2Cproductid%3A3439429434433566922%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) (Schottky).

*   **Control:** A **10kΩ potentiometer** and a **1kΩ resistor**.

*   **Power:** Your breadboard power supply (set to 5V).

*   **Measurement:** A digital multimeter.

**The Procedure:**

1.   **Build the Sweep:** Connect the potentiometer's outer legs to 5V and Ground. Connect the middle "wiper" to a 1kΩ resistor in series with your diode.

2.   **Measure Voltage (Vd):** Place your multimeter probes directly across the diode.

3.   **Measure Current (Id):** If your meter has a mA setting, put it in series. Otherwise, measure the voltage across the **1kΩ resistor** and use Ohm’s law (I=V/R).

4.   **The Comparison:** Slowly turn the pot. Note the exact voltage when the diode begins to conduct significant current (>1 m A).

**The Material Science "Why":**

*   The [1N4148](https://google.com/search?q=Adafruit+1N4148+Signal+Diode+10+Pack&prds=catalogid%3A13754041179079405185%2Cgpcid%3A756351348573263236%2CheadlineOfferDocid%3A11436203225891731055%2Cmid%3A576462852185670638%2Cproductid%3A12826592940849650020%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) should "wake up" around **0.6V–0.7V**. This is the energy required to push electrons across the silicon PN gap.

*   The [1N5817](https://google.com/search?q=Bojack+1N5817+Schottky+Diode+1+A+20+V+DO-41+Axial+5817&prds=catalogid%3A5570536117430191302%2Cgpcid%3A6037545950596382000%2CheadlineOfferDocid%3A12361786144494650486%2Cmid%3A576462375557385127%2Cproductid%3A3439429434433566922%2Cpvo%3A38%2Cpvt%3Ahg&ibp=oshop&pvo=38&opi=103135050&gl=us&hl=en&noiga=1) should wake up much earlier, around **0.2V–0.3V**. By replacing one side of the junction with **metal**, we lowered the energy barrier.

[How to plot a Diode IV Curve](https://www.youtube.com/watch?v=m-osT1k8M-Q) This video provides a visual walkthrough of setting up a breadboard experiment to capture the current-voltage relationship of a diode, which is the exact first step in your curriculum.

Would you like me to provide the specific wiring diagram for the Zener Diode "Voltage Clamp" experiment next?

[![Image 14](https://www.gstatic.com/images/branding/productlogos/youtube/v9/192px.svg) Demonstration of I-V Characteristic of Diode - YouTube Electronics with Dr. Wary · 10K views](https://www.youtube.com/watch?v=m-osT1k8M-Q)

![Image 15](https://i.ytimg.com/vi/m-osT1k8M-Q/sddefault.jpg)

![Image 16](https://www.gstatic.com/images/branding/productlogos/youtube/v9/192px.svg)

[Google Privacy Policy Opens in a new window](https://policies.google.com/privacy)[Google Terms of Service Opens in a new window](https://policies.google.com/terms)[Your privacy & Gemini Apps Opens in a new window](https://support.google.com/gemini?p=privacy_notice)
Gemini may display inaccurate info, including about people, so double-check its responses.

 Sign in 

Copy public link

Report
