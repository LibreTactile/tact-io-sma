[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](/docs/code_of_conduct.md)

# tact-io SMA

**Open-source hardware** design of a simple tactile actuator mechanism driven by a Shape Memory Alloy (SMA) wire, tact-io for short.

![tact-io-sma activation close up](/docs/img/tact-io-sma-activation-pin.webp)

> Tact-io _softly_ pokes your skin for multimodal user experiences.

**Design considerations:**

1. _Easy to use_ by researchers, technicians, hobbists and makers.
2. _Easy to build_ with basic electronic skills, tools and components.
3. _Easy to modify_, in case you need a stronger sensation, smaller footprint, or larger linear actuation.
4. _Modular_, simple and lightweight design allows for different configurations (single pin, line or matrix of multiple pins, or separate stimulation points like in the [example below](/docs/README.md#how-you-can-use-tact-io)) for building more complex tactile human-computer interfaces.
5. _Low cost_, allowing you to use several in your tactile gadgets without rendering them unaffordable.
6. _Open source_, which means anyone in the world can build, support, improve and sell the hardware so it can mature over time.

## Why tact-io?

We (my PhD research team and our partners) are developing [assistive technology for visually impaired people](https://societeinclusive.ca/en/projets/dispositif-assistance-navigation/), and we noticed that there aren't many options for tactile actuators, not even simple ones, and certainly not many inexpensive ones. So we decided to **create our own** and open source it to _enable more people to **develop tactile interfaces**_, to be implemented in assistive technologies, or any other field (gaming, XR, VR neurorehab, etc).

_NOTE_: To allow as many people as possible to build and use the tactile actuator, our design favors **simplicity** over performance, size, or aesthetics. We encourage anyone that would like to improve the design or create their own design.

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

### tactile VR glove

For example, we built (and plan to open source) a 'tactile VR glove'. You can see in the picture below my hand wearing it while being tracked by the leap motion (laptop screen displays the leapmotion VR viewer).
![working principle illustration](/docs/img/use-case-1.png)

Then we created a VR scene for Google Cardboard in the Unity3D game engine, with hand tracking. In this scene, your fingers are tracked by the Leap motion, and you are in the middle of an asteroid field, if any of your virtual fingers collides with a passing asteroid, the tactile vr glove will poke the corresponding physical fingers.
![Google Cardboard](/docs/img/use-case-1-1.png)

### Assistive technology

We are currently developing an [assitive technology device to support screen reader interent navigation](https://societeinclusive.ca/en/projets/dispositif-assistance-navigation/) for visually impaired users.

> Learn more about how to adapt tact-io to your project in our [user manual](/docs/user-manual.md).

## How to build it:

> You can learn how to build and modify tact-io in the [build guide](/docs/build-guide.md).

Here is a summary of the build steps:

1. Gather the materials (muscle wire, music wire, resistor, preperforated circuit board, wood stick, paper clip and compression spring) and tools (solder iron, hot glue gun, hand drill, pliers).
1. Mark layout in board and wood stick, cut to size and drill the holes.
1. Assemble the pieces together by tying, gluing or soldering in place.
1. Add a resistor (or PWM circuit) and connect to 5V.
1. (_Optional_) Build a case to contain the mechanism and expose only the tip of the pin.

## Get in touch

If you need help building the tact-io, implementing it on your own gadget or would like to get more involved in the project, you can get check out the [FAQ](/docs/faq.md), and the [discussion tab](https://github.com/JRNIF/tact-io-sma/discussions), or send an email to [libretactile@gmail.com](mailto:libretactile@gmail.com).

## Help out

If you have an idea of how to improve the project, are curious of where the development is heading or if you would like to encourage the team, you can join in the [discussion](https://github.com/JRNIF/tact-io-sma/discussions).
Dont forget to read the [code of conduct](/docs/code_of_conduct.md) to understand the kind of open and welcoming environment we try to promote.

If you would like to contribute to the project, follow the [contribuiting guideliness](/docs/contribuiting.md).
We are a small team, made up mostly of academic researchers, so any artist, writer, translator, tester, accessibility expert, researcher, mainteiner or anyone who can (and wishes) to help is very much apprecited.

You can also show support for the project, through a financial contribution by using our github sponsor button.

<!-- TODO:  add sponsor button, or something like that ...-->

## Project organization

> [/LICENSE](/LICENSE): details about the licensing of tact-io SMA.  
>  [/docs/](/docs/): you can find the project documentation here.
>
> > [/docs/source/](/docs/source/): you can find the source files for the hardware design here.  
> > [/docs/hw-license/](/docs/hw-license/): you can find the text of the hardware license and guide on how to use it.  
> > [/docs/img/](/docs/img/): image assets for the documentation are stored here.  
> > [/docs/README](/docs/README.md): location of this README file.  
> > [/docs/faq](/docs/faq.md): list of frequently asked questions.  
> > [/docs/user-manual](/docs/user-manual.md): description of how to use the project.  
> > [/docs/build-guide](/docs/build-guide.md): detailed step-by-step guide for building and modifying the tact-io.  
> > [/docs/r-and-d](/docs/r-and-d.md): description of the R&D approach and a log of some of the critical design decisions.  
> > [/docs/changes](/docs/changes.md): a brief log of the design changes in the project.  
> > [/docs/code_of_conduct](/docs/code_of_conduct.md): a description of the expected behavior for the people involved in the project, aimed at creating an open and inclusive environment.  
> > [/docs/contribuiting](/docs/contribuiting.md): a guide of how to contribuite to the project.

## Research team

Juan Nino MA - PhD student at Laval University in Quebec.  
[Jocelyne Kiss PhD](https://www.design.ulaval.ca/personnel/professeurs/jocelyne-kiss) - Associate Professor of Arts and Technologies.  
[Geoffrey Edwards](https://www.scg.ulaval.ca/geoffrey-edwards) - Professeur titulaire Faculté de foresterie, géographie et géomatique, Département des sciences géomatiques / Université Laval  
[Ernesto Morales PhD](https://www.cirris.ulaval.ca/en/researchers/ernesto-morales/) - Associate professor, Faculté de Médecine, Département de réadaptation / Université Laval  
[Walter Wittich PhD FAAO CLVT](https://www.opto.umontreal.ca/wittichlab/en/index.html) - Associate Professor, School of Optometry  
[Frédérique Poncet ERG PhD](https://crir.ca/en/member/frederique-poncet-erg-ph-d/) Institutional Researcher, Lethbridge-Layton-Mackay Rehabilitation Centre (LLMRC)

## Partners

This project is made possible thanks to the collaboration of our partner organizations.

[![Laval University logo](/docs/img/logo-ulaval.png "Laval University")](https://www.ulaval.ca/en)

[![CIRRIS logo](/docs/img/logo-cirris.png "CIRRIS")](https://www.cirris.ulaval.ca/)

[![Inclusive society logo](/docs/img/logo_is.png "Inclusive society")](https://societeinclusive.ca/en/socinc/vers-une-societe-quebecoise-plus-inclusive/)

[![CRIR logo](/docs/img/logo-crir.png "CRIR")](https://crir.ca/en/)

[![Lethbridge-Layton-Mackay logo](/docs/img/logo_crllm.png "CLethbridge-Layton-Mackay")](https://www.llmrc.ca/)

[![INLB logo](/docs/img/logo-inlb.png "INLB")](https://www.santemonteregie.qc.ca/en/node/2134)

[![RAAMM logo](/docs/img/logo-raamm.png "RAAMM")](https://raamm.org/)

### Acknowledgement

Special thanks to the general open source community, which have taken poured years of effort to create resources and tools to facilitate the creation, licensing, distribution and support of open source software and hardware.

- The content and structure of this repository is heavily informed on the guides and resources of the The [Open Source Hardware Association](https://www.oshwa.org/) (OSHWA).
- Our hardware license was crafted by the [European Organization for Nuclear Research](https://home.cern/) (CERN).
- Our code of conduct was adapted from the [Contributor Covenant](https://www.contributor-covenant.org/)'s code of conduct.

---

## License

The software and documentation of this project are released under [MIT license](/LICENSE) (permissive). The hardware design files are released under the [CERN-OHL-P v2 license](/docs/hw-license/cern-ohl-p-v2.md) (permissive).
You can learn more about the choice of license and the project in general reading the [FAQ](/docs/faq.md).
