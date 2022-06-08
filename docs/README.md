# Tact-io SMA (DRAFT)

**Open-source hardware** design of a simple tactile actuator mechanism driven by a Shape Memory Alloy (SMA) wire, tact-io for short.

> Tact-io _softly_ pokes your skin for multimodal user experiences.

![tact-io-sma activation close up](/docs/img/tact-io-sma-activation-pin.webp)

## Why tact-io?

[We](https://github.com/LibreTactile/.github/blob/main/profile/README.md#partners) are developing [assistive technology](https://societeinclusive.ca/en/projets/dispositif-assistance-navigation/) for visually impaired people.
In the process, we decided to **create our own** modular tactile stimulation hardware
(to allow multiple configurations such as single pin, line or matrix of multiple pins, or separate stimulation points like in the [example below](/docs/README.md#how-you-can-use-tact-io))
and open source it to _enable more people to **develop tactile interfaces**_.

## Who is tact-io for?

Anyone interested in computer controlled tactile stimulation, which includes gamers, VR/XR enthusiasts, makers, electronics hobbists, and user experience researchers.

Also, organizations that do reaserch and development in related fields might benefit from supporting this open source project.

Finally, both visually impaired users and rehabilitation technology researchers can benefit from easier development of assistive technology.

## How tact-io works:

![working principle illustration](/docs/img/working-principle.png)  
The actuation device is a _pin that presses against the skin when activated_. A the contraction of a SMA "muscle" wire is used to move a lever that activates the pin, and a spring is used to return the lever to its inactive position.
![tact-io-sma activation naked](/docs/img/tact-io-sma-activation-multiple-pin.webp)

## How you can use tact-io:

Tactile interfaces can enhace user experience by providing multimodal feedback. You can create different gadgets that make use of tactile technology.

### Tactile VR glove

For example, we built (and plan to open source) a 'tactile VR glove'. You can see in the picture below my hand wearing it while being tracked by the leap motion (laptop screen displays the leapmotion VR viewer).
![working principle illustration](/docs/img/use-case-1.png)

Then we created a VR scene for Google Cardboard in the Unity3D game engine, with hand tracking. In this scene, your fingers are tracked by the Leap motion, and you are in the middle of an asteroid field, if any of your virtual fingers collides with a passing asteroid, the tactile vr glove will poke the corresponding physical fingers.
![Google Cardboard](/docs/img/use-case-1-1.png)

> Learn more about how to adapt tact-io to your project in our [user manual](/docs/user-manual.md).

## How to build it:

Our development process prioritizes openness, modularity, affordability, ease of use, construction, and modification over performance, aesthetics, or size. Learn more about our design considerations at [LibreTactile](https://github.com/LibreTactile#r--d).

> You can learn how to build and modify tact-io in the [build guide](/docs/build-guide.md). We encourage everyone to optimize the design for their needs.

Here is a summary of the build steps:

1. Gather the materials (muscle wire, music wire, resistor, preperforated circuit board, wood stick, paper clip and compression spring) and tools (solder iron, hot glue gun, hand drill, pliers).
2. Mark layout in board and wood stick, cut to size and drill the holes.
3. Assemble the pieces together by tying, gluing or soldering in place.
4. Add a resistor (or PWM circuit) and connect to 5V.
5. (_Optional_) Build a case to contain the mechanism and expose only the tip of the pin.

## Get in touch

If you need help building the tact-io, implementing it on your own gadget or would like to get more involved in the project, you can join the [discussion](https://github.com/orgs/LibreTactile/discussions) or send an email to [libretactile@gmail.com](mailto:libretactile@gmail.com).

> Find out more about getting involved in the project at [LibreTactile](https://github.com/orgs/LibreTactile/discussions).

## Project organization

> [/LICENSE](/LICENSE): details about the licensing of tact-io SMA.  
>  [/docs/](/docs/): you can find the project documentation here.
>
> > [/docs/source/](/docs/source/): you can find the source files for the hardware design here.  
> > [/docs/hw-license/](/docs/hw-license/): you can find the text of the hardware license and guide on how to use it.  
> > [/docs/img/](/docs/img/): image assets for the documentation are stored here.  
> > [/docs/README](/docs/README.md): location of this README file.  
> > [/docs/user-manual](/docs/user-manual.md): description of how to use the project (_pending_).  
> > [/docs/build-guide](/docs/build-guide.md): detailed step-by-step guide for building and modifying the tact-io (_draft_).  
> > [/docs/r-and-d](/docs/r-and-d.md): description of the R&D approach and a log of some of the critical design decisions (_pending_).  
> > [/docs/changes](/docs/changes.md): a brief log of the design changes in the project.

## Collaborators

This project is made possible thanks to the collaboration of our [research team](https://github.com/LibreTactile/.github/tree/main/profile#research-team), our [partners](https://github.com/LibreTactile/.github/tree/main/profile#partners) and the resources provided by the [open source community](https://github.com/LibreTactile/.github/tree/main/profile#partners).

---

## License

The software and documentation of this project are released under [MIT license](/LICENSE) (permissive). The hardware design files are released under the [CERN-OHL-P v2 license](/docs/hw-license/cern-ohl-p-v2.md) (permissive).
You can learn more about the choice of license and the project in general reading the [FAQ](/docs/faq.md).

---

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](/docs/code_of_conduct.md)
