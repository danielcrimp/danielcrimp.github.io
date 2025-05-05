---
layout: post
title: Returning to my roots in hardware
date: 2025-03-31
summary: Creating a truly full-stack CV
---

Recently, after two years working in enterprise tech consulting, I decided to try something new and make a move into a product company.

I initially struggled to present as a typical tech hire. Then I found an atypical company - and made a very atypical application.

<img src="/images/matta-application/office.jpeg" alt="The Office!" class="responsive-img">


Those that know me know I'm a hardware person. I muck around with cars and motorcycles, build cameras and go out of my way to fix things that break, often at more expense than necessary. I'm 3 for 3 on nutribullet repairs.

I wound up writing code for a living because I wanted to make stuff and fix stuff, and you'd do alright if you fixed digital stuff. At least that's what my mate's dad said once. When I was working in NZ, I had a pretty cool job writing code - but something didn't feel right. I didn't feel connected to the results of my work.

When I relocated to the UK, I decided to also make a move from corporate number-crunching into proper software development. This was a great decision - I felt so much more at home doing technical work with technical people. I soon realised this still wasn't scratching the itch. I thought that maybe if I got a "proper" tech job, this might be fixed.

## Finding the right role

I spent a few months researching and applying at established tech companies and startups. This didn't go great. I wasn't interviewing well, and I wasn't excited by a lot of the work that was out there. After some unfulfilling searching, I stumbled across Matta. They had a lot of really digestible published research which they'd packaged as a slick product - industrial cameras connected to an inference pipeline that finds defects in most manufacturing processes with barely a day's finetuning. Their opening sounded like one of the vanishingly few roles that would value hardware, software, ML knowledge and creative skills. On the listing, they said applicants were encouraged to find creative ways to apply.

## Challenge accepted

I knew Matta were involved in manufacturing, had a very technical founding team and a good sense of humour. I thought I'd come up with an application that showcased my abilities as a creative and multidisciplinary engineer in such a way that aligned with their company's character. I'd also read about their enthusiasm for Lego building breaks and coffee.

So I designed this envelope that housed my CV and covering letter, some Wellingtonian coffee-infused chocolate and a Dan Minifig.

<div class="responsive-container">
  <model-viewer 
    src="/assets/files/env.glb" 
    alt="A 3D model" 
    camera-controls 
    exposure="0.8">
  </model-viewer>
</div>


The envelope was printed from PLA plastic. Each half has a band that acts as the walls, with internal tabs for fasteners. This design minimises support structure and out-of-plane detail. Covers for each half could be printed face-down to pick up a nice finish from the print bed. Countersunk screws hold it all together and sit flush. I was stoked with the industrial feel of the thing. 

Rather than design a clasp mechanism - which takes a lot of trial and error - I embedded neodymium magnets in the print which hold the cap on. The whole thing closes quite firmly with a nice thunk.

<img src="/images/matta-application/parts.jpeg" alt="Parts laid out" class="responsive-img">

My mate Ryan showed me this trick in a uni project where you'd inject viscous acrylic paint into milled surfaces. The paint would adhere to the walls of each cut but sink in the middle, which would create a very nice radius once it set. I bought some paint syringes online and spent an evening injecting acrylic paint into the cuts in the print face. For the text itself, I found a similar font and combined that with some vectors I scraped from their site assets.

<img src="/images/matta-application/paint.png" alt="Paint fill detail" class="responsive-img">

I wanted a clever link to my website, because the hyperlinks in my CV probably wouldn't work after I printed it out. At first I was going to go for a QR code, but that would take too long to paint. So, I sourced some NFC tags online and got them delivered. They're just basically 1mm thick discs of 25mm diameter. I left a cutout in the back of one of the plates and glued the tag in behind it. You can program the tags using a simple phone utility.

<img src="/images/matta-application/nfc.gif" alt="Scanning..." class="responsive-img">

Finally, I generated a gif from my CAD software which showed the box design being drawn up. I displayed that on a hidden page on my website which provided a download for the CV and covering letter. The NFC tag linked to this page.

<img src="/images/envelope.gif" alt="Envelope animation" class="responsive-img">


## Conclusion
At the time of writing this, I'm sitting on the couch in the Matta office, having come in a bit early to finish off this post. I got the job!

In hindsight, I think I really made the application for me. [I liked it. I was *good* at it.](https://www.youtube.com/watch?v=FQlAfI91cZ8) I stayed up 'til midnight every day for a week - designing, painting and polishing, agonising over details. Why did I put so much effort into this? In writing this post, I think I've figured out the answer to that.

The type of problems our technical minds once solved were practical. Nowadays, our skills are directed toward designing solutions for increasingly nebulous and abstract problems.

Making this application reminded me there is still value to be found in creating things that serve humanity in the real world. That I can work on these problems for a living is rewarding, and the transition to this work has had a hugely positive effect on my wellbeing.

> 
"The place to improve the world is first in one's own heart and head and hands, and then work outward from there. Other people can talk about how to expand the destiny of mankind. I just want to talk about how to fix a motorcycle."

Robert Pirsig, *Zen and The Art of Motorcycle Maintenance*

Ka kite anō,

Dan xx


<!-- To detail about the build
- Design 
    - build plate constraints meant I couldn't make an actual envelope design
    - getting the plate finish on exposed faces by using a band rather than tub
    - cloning the font using a font tool
    - acrylic paint via syringes to get the attractive radius
    - 8x neodymium magnets to get the lid to adhere nicely
    - clearancing
- Legoman
    - fighting off kids in lego leicester square
- chocolate
    - NZ man
- Covering letter
    - shabooskie
- NFC tag
    - hidden application URL
    
 -->
