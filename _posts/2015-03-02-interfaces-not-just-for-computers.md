---
layout: post
title: Interfaces -- Not Just for Computers
---

The embedded track of the Electrical Engineering program at the utexas school system is fundamentally flawed. This is evident from my own observations and my interactions with the course administrators and other students in all levels of the coursework.

The underlying problem stems from the outdated (as in, still recommending you save to your floppy disks), unclear, inspecific lab manuals designed to walk students through the labs from start to finish.

A real lab manual would behave like the contracts we study every day in our classes: it would explicitly define inputs and tolerable outputs; the rest is an exercise for the reader. This is how standards are defined, this is how libraries are implemented, this is how interfaces are implemented, this is how contracts are upheld in the real world.

Our lab manuals have no clear goals. The long worded paragraphs incompletely reference nonexistent code blocks, the abuse of pronouns merits a support group (or at least a re-enrollment in EE 333T) and inconsistencies in the naming conventions of given stubs leave students wondering if they are looking at artifacts of an out-of-date lab document or if two functions are expected come checkout.

Students are recommended to use the provided lab starter code. Any student coming to TAs or administrators with issues regarding code outside the supplied starter code is given the standard "I can only help you if you use the known context we gave you." What does this teach the pupil?

Valvano's starter code is non-portable, un-reuseable, magic-number ridden, incompletely documented, non-original kludge. Is this even preparing us for industry work? Am I going to spend 2 hours of company time reading a manual to determine which bits to flip when TI has provided me with LaTeX, html and in-line comments to a beautiful multi-peripheral driver library? Context (micro-controller) specific code, code reusability, shorter development time, and a confinement to the manufacturer's known working context are a few of the advantages using TI's driverlib brings Hershic's codebase.

Identifying problems without accompanying solutions is complaining. A quick re-alignment is simple: "so what are you going to do about it?"

Team Hershic has decided the only way to stop this maddening cycle of spending hours "interpreting" a lab doc and implementing the lab only to be told our progress is tangential and inconsequential is to have weekly meetings with the TAs regarding the objectives of next weeks' lab.

Yes, this is adding extra work and reducing disposable free time for both Team Hershic and the course TAs. Yes, this is supposed to be exactly what the lab documents are for. But the lab documents are not working. Here is a fix implementable on my end -- please please please consider a fix on yours.
