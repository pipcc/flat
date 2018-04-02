# What is flat?
flat is a web based docker management solution targeting Single Board Computer (SBC) platforms such as Raspberry Pi and Tinker Board. It has originally forked from the popular Portainer UI. (thanks for great work, Portainer team)

# flat vs. Others: What can flat do more?
Although docker has been ported for many different CPUs including ARM, Portainer and similar tools have been focused on serving docker on mainstream server platform such as x86/x64/amd, which almost always never allow/expose/exist H/W capabilities SBC fundamentally provides such as GPIO access, so their lack of support for, for example, host-to-container device-linking and linux CAP allocation is not conincedence.

flat, on the other hand, has designed and is evolving to better serve popular SBC platform. It provides all the essential features described above, and on top of that, currently available 50+ templates are built for SBC only. Why? Because SBC is more capable than those boring servers better be remained untinkered, living in packed groups..

# Our Mission
flat's mission is inspiring and encouraging creative people to more focus on their ultimate goals than wasting time in search of, let's say, an optimal LAMP stack for collecting sensor data repeating install&configure 100+ times throughout their lives.
flat believes, by applying the powerful and proven container technology docker has built upon, we can help SBC community to achieve more than ever.

# Where to Start
Follow the instruction at https://github.com/pipcc/getflat.

![flat](http://host.wednus.com/flat/flat.png#1)
