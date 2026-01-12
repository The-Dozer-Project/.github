# The Dozer Project

The Dozer Project is an open, systems-first effort focused on building auditable, deterministic, and failure-honest infrastructure for adversarial and high-stakes environments.

This is not a product company in the traditional sense.
It is a design-driven systems project built around the idea that intent should be a first-class citizen in software.

No dashboards that lie.
No probabilistic vibes trafficked as certainty.
No hidden automation.

## What We're Building

The Dozer Project currently consists of several tightly related systems:

### Ben

A telemetry, policy, and routing system designed for zero-trust environments.

Ben emphasizes:

* Deterministic behavior
* Explicit failure modes
* Replayability
* Strong compile-time guarantees
* Clear provenance and audit trails

Ben is not a "detect everything" system.
It is a system that makes why something happened legible.

### Lucius

A declarative, compile-time language for expressing intent, evidence, and escalation boundaries.

Lucius is:

* A high throughput sanitizer.
* Highly extensible engine with determinism.
* Multi-stage and multi-faceted system to get analytical information on potential malicious data.
* Not a system that guarantees everything will be caught.
* A system to outsource operator thinking.

It exists to describe what is data is as determined by operator intent in the conext of the host system.
Luxamen is the deeper inspection system associated with Lucius. Luxamen is a VM orchestration and detonation 
engine, and malware analytics system.

### Benson

A simulation and laboratory environment used to:

* Test Ben intent
* Explore adversarial scenarios
* Validate design assumptions
* Develop policies safely and efficiently

Benson exists so real systems don't have to be abused to learn from them.

### Ed

An AI training engine to created models with bounded autonomy to:

* Customize detectors for host systems
* Provide an intuitive interface for training
* Provides clear provenance and history of training configuations

### Future systems

In the future the Dozer Project will also aim to create a threat intelligence correlation platoform called Dorian
and a rich-media extraction system called Oscar. Basic shapes of each system exists but out of scope with initial
organizational offerings. 

## Design Ethos

This project is guided by a few non-negotiable principles:

* Intent before implementation
* Compile-time enforcement over runtime guesswork
* Determinism over cleverness
* Explicit failure over silent degradation
* Operators are accountable and respected
* Complexity must remain legible

We prefer boring, understandable systems that work to clever systems that can't be reasoned about.

## What This Is Not

The Dozer Project is not:

* A SaaS platform
* A hype-driven security product
* An AI-first system
* A replacement for human judgment
* A magic box that guarantees safety

If you're looking for certainty theater, this is not the right place.

## Status

The project is early, active, and design-heavy.

A significant amount of time is spent on:

* Architecture
* DSL design
* Macro systems
* Failure modeling
* Long-term maintainability

Code exists, but design correctness comes first.

## Who This Is For

You may find this project interesting if you:

* Care about systems that can be audited years later
* Are uncomfortable with black-box security tooling
* Value correctness over velocity
* Prefer honest limitations to exaggerated claims
* Enjoy reading design docs as much as code

## Engagement

This project is intentionally quiet.

There is no marketing funnel.
There is no Discord hype loop.
There is no pressure to engage.

If you're reading the docs, cloning the repos, or thinking through the ideas that's already meaningful participation.

No collaboration is being sought right now, however feedback is appreciated.

## License

Most of the project is licensed under AGPL.

This is intentional.

If these systems are valuable they should be open and improvements should remain visible and shared. 
Not wrapped and buried for economic gain.

The only system slated to be closed source is Luxamen for reasons that it would bolster adversaries
against it ultimately making development much harder and destroy potential efficacy. 

## Final Note

The Dozer Project is built by someone who believes that:

Good systems are boring, predictable and easy to understand.
Honest systems admit what they don't know.
And the most important: the user is the design focal point.

If that resonates, you're in the right place.
