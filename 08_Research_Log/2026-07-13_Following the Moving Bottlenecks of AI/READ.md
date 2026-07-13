# Following the Moving Bottlenecks of AI

When people discuss AI today, most conversations revolve around models.

Which LLM performs better.

Which GPU is faster.

Which company released the newest model.

For a long time, I looked at AI in much the same way.

I followed model releases, benchmark results, GPU announcements, and the rapid growth of data centers. I understood AI primarily through the visible layer of the industry: models, software, and computing performance.

However, spending the past several months working at a Broadcom-related FC-BGA substrate manufacturing site has gradually changed my perspective.

The more I observed the manufacturing environment, the more I realized that AI is not constrained by a single bottleneck.

Instead, the bottleneck keeps moving.

Several years ago, GPUs were widely viewed as the primary limitation.

The basic argument was simple.

AI development required more computing power, and the supply of advanced GPUs could not keep pace with demand.

As GPU production increased, however, attention began shifting to the layers required to integrate and operate those chips.

Advanced packaging became more important.

A GPU cannot function as an isolated chip. It must be connected to memory, power delivery systems, substrates, cooling systems, and other components. This increased attention on technologies such as FC-BGA substrates and other forms of advanced packaging.

Working inside an FC-BGA manufacturing environment made this shift much more concrete for me.

Before entering the factory, I had understood FC-BGA only as one component within the semiconductor supply chain.

Inside the factory, I began to see how many physical processes, tools, control systems, and infrastructure layers were required before a substrate could support an advanced processor.

The bottleneck was no longer only the GPU.

It had moved into the manufacturing systems required to support the GPU.

More recently, discussions have expanded further.

Glass core substrates are being considered as one possible response to the limitations of conventional substrate materials.

High-speed optical interconnects and co-packaged optics are receiving increasing attention because electrical connections face limitations as data volumes and transmission speeds rise.

Each of these developments addresses one constraint.

At the same time, each solution creates new dependencies on materials, production equipment, manufacturing precision, testing, and supply-chain capacity.

Outside semiconductor manufacturing, another bottleneck became increasingly visible.

Electricity.

Building larger AI models requires enormous computing power, and computing power requires electricity.

A data center cannot operate simply because enough GPUs are available.

It also requires stable power generation, grid connections, substations, cooling systems, and long-term access to energy.

Soon after I began thinking more seriously about electricity, another issue appeared.

Transformers.

Even when a country has enough generation capacity, electricity cannot reach factories or data centers without sufficient transmission and distribution infrastructure.

Transformers are essential to that process.

This changed my understanding again.

The AI bottleneck could move from semiconductor production to the electrical grid.

A shortage in one industrial component far outside the software industry could delay the expansion of AI infrastructure.

Then I began noticing something much closer to my daily work.

Factory control systems.

For several months, I had been observing the installation, wiring, setup, and power-on testing of conveyor systems.

At first, I viewed each conveyor simply as a machine.

I also regarded the large control panels next to the equipment as boxes containing breakers, cables, and electrical components.

One question continued to bother me.

Why did each machine require its own large control panel?

Why could the entire factory not be operated through one central control panel?

Through discussions with engineers, I gradually understood that each piece of equipment operates as an independent control system.

Inside the control panel are PLCs, I/O modules, power supply units, and communication devices.

Sensors send information to the PLC.

The PLC sends instructions to motors and actuators.

I/O modules connect the controller with the physical devices in the field.

Network cables connect separate machines and link them to higher-level factory systems.

The blue LAN cable at the bottom of one control panel became particularly important to me.

Until then, I had seen it only as a communication cable.

After understanding the control structure, I began to see it as part of the factory's nervous system.

Motors move individual machines.

Information coordinates the movement of the factory as a whole.

This was a very small observation, but it changed my view of AI manufacturing.

Even if every advanced production tool is physically present, the factory cannot operate without control systems that coordinate equipment, sensors, transportation, and information.

The bottleneck could therefore move again.

It could move from semiconductors and electricity into factory automation, system integration, maintenance, or control engineering.

Another observation came during my weekend runs around Singapore's Pasir Ris Wafer Fab Park.

My original purpose was simply to look at the area surrounding Applied Materials after reading about its expansion.

During the run, however, I saw UMC, Soitec, SSMC, Micron, Jabil, surrounding utility infrastructure, and facilities associated with water management.

What initially appeared to be a collection of individual companies gradually revealed itself as a much larger industrial ecosystem.

There were foundries.

There were engineered wafer suppliers.

There were advanced packaging operations.

There were equipment manufacturers.

There were roads, water systems, electricity infrastructure, industrial land, and government planning.

Each organization appeared to address a different constraint.

The foundry addressed chip production.

The wafer supplier addressed specialized material requirements.

The equipment manufacturer supported production capacity.

Water infrastructure supported manufacturing processes.

Industrial planning made large-scale clustering possible.

Together, these layers formed an ecosystem capable of supporting semiconductor production and, indirectly, AI.

This helped me understand why a bottleneck should not be examined as an isolated shortage.

A bottleneck is produced by the relationship between multiple layers.

When one layer expands faster than another, the slower layer becomes the new constraint.

When GPU supply increases, advanced packaging may become the bottleneck.

When packaging capacity expands, power supply may become the bottleneck.

When electricity becomes available, transformers and grid connections may become the bottleneck.

When factory construction is completed, control systems, skilled engineers, materials, water, or maintenance capacity may become the bottleneck.

The order is not fixed.

It changes as investment, technology, policy, and demand move through the system.

This realization changed how I think about AI.

Previously, I saw AI as software running on GPUs.

Today, I see AI as an industrial system supported by countless physical layers.

Those layers include semiconductor materials, front-end fabrication, advanced packaging, electrical infrastructure, transformers, cooling, water, logistics, factory automation, and control networks.

Each time one bottleneck is resolved, another becomes visible further upstream or downstream.

In other words, AI does not advance by eliminating bottlenecks permanently.

It advances by moving them.

This also changes how I interpret news.

A new GPU announcement may appear to be the center of AI progress.

However, the actual limiting factor may already have moved somewhere else.

It may be the substrate beneath the processor.

It may be the optical connection between computing systems.

It may be the transformer outside the data center.

It may be the water infrastructure surrounding a semiconductor fab.

It may be the PLC and network that allow a production line to operate continuously.

The most visible technology is not always the most important constraint.

For me, this has become one of the most important lessons from observing AI manufacturing on site.

Only a few months ago, I thought GPUs were the center of AI.

Then I entered an FC-BGA factory and began to understand the manufacturing layers supporting those GPUs.

I studied the control panel beside a conveyor and learned how PLCs, I/O modules, and communication networks coordinate industrial equipment.

I ran through Singapore's Wafer Fab Park and saw how semiconductor companies, materials suppliers, utilities, and government planning formed a single industrial ecosystem.

I also began to understand why electricity, transformers, cooling, water, optical communication, and next-generation substrate materials were appearing repeatedly in discussions about AI infrastructure.

These observations did not lead me to identify one permanent bottleneck.

They led me to a different conclusion.

The bottleneck itself is mobile.

I no longer ask,

**"What is today's AI bottleneck?"**

Instead, I ask,

**"Where will the next bottleneck move?"**

---

## Learning Notes

* AI bottlenecks are dynamic rather than fixed.
* A bottleneck emerges when one layer of the system expands faster than the layers connected to it.
* The primary constraint can move from GPU availability to advanced packaging, substrate materials, electrical infrastructure, transformers, cooling, optical communication, water, factory automation, or skilled labor.
* Solving one constraint often exposes another at a different point in the value chain.
* The most visible AI technology is not always the layer that currently limits growth.
* A semiconductor factory is not simply a collection of production tools. It is a network of independent control systems coordinated through sensors, PLCs, I/O modules, and communication networks.
* Industrial clusters such as Singapore's Wafer Fab Parks demonstrate that AI infrastructure depends on the coordination of companies, materials, utilities, land, logistics, and public planning.
* Understanding AI therefore requires observing not only models and chips, but also the physical systems that make their production and operation possible.
* Manufacturing sites provide a practical perspective that complements software-centered discussions of AI.
* The more useful question is not which bottleneck exists today, but where the next bottleneck is likely to appear.
