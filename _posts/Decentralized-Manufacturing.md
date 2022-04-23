---
layout: post
title:  "The Future of Decentralized Manufacturing"
---
Ten years ago, manufacturing was forecasted to trend towards decentralization. 

Additive manufacturing (3D printing, mainly) implied the capital cost and barrier of entry to manufacturing would asymptotically approach values that would make difficulty in starting up the requisite machinery to manufacture negligible. Makerspaces and low volume machine shops would begin to eat away at the manufacturing sector. Those seasoned in on demand manufacturing were rolling their eyes.

# The Promise of Decentralization

In the early aughts, CAD was becoming ubiquitous. AutoCAD was now more common than a drafting table. CAD was a semi-requisite to decentralized manufacturing as it meant you could skip a vital and difficult part of the manufacturing process that decades ago required trained professionals - 2D part drawings.

Additive manufacturing meant easily making parts digitally with little to no waste. The cost of digital fabrication equipment (CNC Routers, desktop CNC machines, etc.) would continue to decrease in cost and become more accessible to anyone with a power outlet and some indoor space to operate the machinery in.

Garages everywhere would have alongside their standard toolbox and project car a Shopbot CNC Router now at a cost that a standard middle class home owner could afford. This could shift manufacturing from centralized facilities towards a decentralized model, pushing manufacturing to the edge.

# What Eventually Happened
So what did happen? Prototyping became cheaper.

We can now 3D print non-structural parts in hours. The idea that a manufacturing laymen (often times, an engineer) can turn an undimensioned CAD model into an actual part should still shock anyone. This has changed the way engineers think about part cost forever. As an example: when designing a mechatronic system, limit switches and sensors are critical where axes of motion interact with each other, or with themselves (say, a hard-stop for example). Fine tuning the kinematics of the system and the placement of sensors could take hours or days. Today, I can pay some amount of attention to it, and know that when I get it wrong, I can easily crank out a new bracket on a 3D printer by the end of the day. This makes prototyping faster.

In the case for sensor mounting on prototypes, additive manufacturing works well. However, there are major limitations to additive manufacturing. Structural parts, for example, are an immediate culling of your most cost effective additive manufacturing options. Markforged has made decent strides in affordable structural parts, but not in a meaningful way. For example, their carbon fiber reinforced FDM printing does provide stronger parts, but not in a quantifiable way as they cannot provide yield or ultimate tensile stresses with which to analyze against. Fundamentally, if I cannot analyze a part for structural strength, it cannot be a structural (useful) part. [See their design guide for reference](https://static.markforged.com/downloads/CompositesDesignGuide.pdf){:target="_blank"}{:rel=noopener noreferrer"}


Even if Markforged could provide required mechanical property values, only a small percentage of engineers understand analyzing anisotropic materials, or would find it worth the time as opposed to cutting a part from metal and moving on with their day.

# Will Manufacturing go to the Cloud?

No. The cost of moving a bit across the country is and always will be significantly cheaper than moving one gram of aluminum. This can't scale.

Instead, the companies and their user interfaces will appear cloud like, but they will disperse their manufacturing facilities around the country to accommodate faster shipping. [See Walmart's distribution system as an example.](https://www.mbaknol.com/management-case-studies/case-study-of-walmart-logistics-management/){:target="_blank"}{:rel=noopener noreferrer"}



# The Reality

Surprise - capex was only one variable in the equation. Depending on the machine, opex can be a monumental cost. Anyone with an FDM 3D printer knows this to be true. You spend as much time tuning and repairing the printer as you do running it in the worst cases. The solution to this is to run many of the same machine and employ technicians specifically trained to operate and repair them, letting economy of scale make the opex of the machines lower.

Instead of decentralized manufacturing, we will see something similar to the online retail order fulfillment model unfold for manufacturing. There will be large manufacturing centers dispersed throughout the country, within one day shipping range of 90% of the population. It's likely this will seem like the cloud, but in practice the only part that feels cloud like will be the online interface. At first, companies will focus on a specialty (see, SendCutSend and sheet metal cutting and forming, or Protolabs and CNC machining).

Large companies (automotive manufacturers, for example) will not feel the change for some time, but they will eventually as dispersed manufacturing companies eat away at the bottom of the market (prototypes and low run manufacturing). Eventually, these on demand manufacturing services will be so good that they will fit into the just in time manufacturing model perfectly and offer de-risking of small to medium size manufacturers (and potentially offer optional capacity to the largest manufacturers).

Eventually, these companies will adopt as many manufacturing techniques as possible. The most efficient and fastest will consume the market until there are a small number of competitors vying for market share in a race to the bottom of opex cost.


Robotics will play a key role in this, not just mechatronic solutions. By definition this does not make sense, but it is because we are thinking about the two incorrectly when considering robotics as a subset of mechatronics. Robots are generalizable whereas a machine built for a process is built specifically for that process and can only perform work in that one process. I will try to elaborate on this later.

