# Frequently Asked Questions

## What is open source hardware?
The Open Source Hardware Association ([OSHWA](https://www.oshwa.org/)) defines Open Source Hardware ([OSHW](https://www.oshwa.org/definition/)) as: 
>"... hardware whose design is made publicly available so that anyone can study, modify, distribute, make, and sell the design or hardware based on that design."  

If you wish to learn more about open source hardware, its licensing and certification, check out [their FAQ](https://www.oshwa.org/faq/).  In fact, the resources provided by the OSHWA have been really helpful during the development of this project.

## What about hardware licenses?
Copyright does not apply to hardware the same way as it does to software, making licesing hardware [more complicated](https://opensource.com/law/15/2/intro-open-hardware-licensing). It is [not recommended](https://ohwr.org/project/cernohl/wikis/faq#q-why-not-use-existing-licences-such-as-gpl-and-any-in-the-family-of-creative-commons-licences) to use a software license (like [MIT](/docs/README.md#license)) for hardware designs. However, the CERN has written an open source hardware license ([OHL](https://ohwr.org/cernohl)) that is analogous to open source software licenses, and complies with the [OSHWA definition](https://www.oshwa.org/definition/) of open hardware (and its also applicable to software).

The CERN OHL v2 has [three variants](https://cern-ohl.web.cern.ch/), strong reciprocal `S`, weak reciprocal `W`, and permissive `P`.  Our project is licensed under the [CERN-OHL-P v2](/docs/hw-license/cern-ohl-p-v2.md).
>"CERN-OHL-P is a permissive licence. It allows people to take your code, relicense it and use it without any obligation to distribute the sources when they ship a product". - [CERN OHL FAQ](https://ohwr.org/project/cernohl/wikis/faq#q-what-are-all-these-suffixes).

## Why choose a permissive license?
We would like everyone (be it hobbist, researcher or company) to interact with as much freedom as possible with the project. We believe that by removing any frictions imposed by reciprocal licenses we could facilitate its adoption, acceleate its development and distribute the effort required to support it.   

After all, this project was originally conceived for the propose of facilitating the [development of assistive technology](/docs/README.md#why-tact-io) for visually impaired people, which often faces low rates of adoption, slow implementation of new technologies, lack of documentation, support and training. Often times the designs of new assistive devices simply never reach the market (and hence the people they try to help).  

## What are the implications of the license?
Here are some of the most important implications of the CERN-OHL-`P`:

1. You can make and distribute the hardware described in the design files (see notices to include in #5).  
1. You can take the design, relicense it and use it without any obligation to distribute the sources. If you relicense the project, you should include a copy of  the license [text](/docs/hw-license/cern-ohl-p-v2.md) (see notices to include in #5).  
1. You can copy, distribute, or modify the design files. When sharing the hardware design source files, the license [text](/docs/hw-license/cern-ohl-p-v2.md), license [use guide](/docs/hw-license/hw-license-howto.pdf) and the [change log](/docs/changes.md) should be included (see notices to include in #5).  
1. If you make modifications to the design, these should be described in the [change log](/docs/changes.md).  
1. The copyright and trademark notices, references to the CERN-OHL-P v2 and disclaimer of warranties:
   1. Should be kept intact if you don't make any changes to the design.
   2. Should be updated as applicable if you do make any changes to the design.  
<!--   3. Must be included with hardware you make and distribuite from the source files in the project. -->
1. The design files or hardware are provided 'as is' without any warranty and the licensor(s) have no liability for damages in relation to the project. 

1. Anyone litigating for patent infringement would lose the rights granted by the license. 

1. If it comes to our attention that you have infringed the terms of the license, we might notify you. You will have a grace period of 30 days after receiving the notification to come into compliance, which is specially helpful in case you infringed the terms of the licence inadvertently.

>_Disclaimer_: Although we make a constant effort to be well informed, and to share appropiate information; we cannot provide legal advice. If you notice something wrong or inconsistent, please [get in touch](/docs/README.md#get-in-touch).

## How to contribuite?
You could [lend a hand](/docs/README.md#help-out) in any area of your interest, like writing, translating, testing, improving the design, spreading the word or maintaining the repository.  
<!--TODO: List of tasks to prioritize-->
Here is a list of of tasks we are prioritizing, but as I am currently the only developer in a team made up of only academic researchers, **any help** is _VERY MUCH APPRECIATED_!

You can also support the project financially via the Github sponsor button. 
<!--TODO: Setup sponsor button-->

## More questions?
If you have more questions or would you like to share your feeback please do so in the [discussion tab](https://github.com/JRNIF/tact-io-sma/discussions) of this repository, so everyone can benefit from the conversation. If you would like to share something privately, you could send us an email to [libretactile@gmail.com](mailto:libretactile@gmail.com)

