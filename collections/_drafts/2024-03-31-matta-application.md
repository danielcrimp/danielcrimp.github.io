---
layout: post
title: Returning to my roots in hardware
date: 2025-03-31
summary: Creating a truly full-stack CV
---

Recently, after two years working in enterprise tech consulting, I decided to try something new and make a move into a product company.

Here's the story of how I applied to a really cool company.

<div style="display: flex; justify-content: center; height: 350px; margin-bottom: 2rem;">
  <img src="/images/matta-application/office.jpeg" alt="The Office!" style="max-width: 100%; border-radius: 15px;">
</div>

Those that know me know I'm a hardware person. I muck around with cars and motorcycles, build cameras and go out of my way to fix things that break, often at more expense than necessary. I'm 3 for 3 on nutribullet repairs.

I wound up writing code for a living because I wanted to make stuff and fix stuff, and you'd do alright if you fixed digital stuff. At least that's what my mate's dad said once. When I was in back home, I was technically making stuff, but something didn't feel right. I wasn't particularly connected to the results of my work.

When I relocated to the UK, I decided to also make a move from corporate number-crunching into proper software development. This was a great decision - I felt so much more at home doing more technical work and talking with technical people. However, eventually I realised this still wasn't scratching the itch. I thought that maybe if I got a "proper" tech job, this might be fixed.

## Finding the right role

I spent a few months in discussions with various tech companies, and was quite unsuccessful. I wasn't interviewing well, and I didn't find suitable openings in companies that excited me. After some unfulfilling searching, I eventually stumbled across Matta. They had a lot of really digestible published research which they'd packaged as a slick product - indefatigable cameras that get deployed on site and keep a watchful eye on manufacturing processes, picking up minute errors. Their opening sounded like one of the vanishingly few roles that would value hardware, software, ML knowledge and creative skills. On the listing, they said applicants were encouraged to find creative ways to apply.

## Challenge accepted

I knew Matta were involved in manufacturing, had a very technical founding team and a good sense of humour. I thought I'd come up with an application that showcased my abilities as a creative and multidisplinary engineer in such a way that aligned with their company's branding and DNA.

So I designed this envelope that housed my CV and covering letter.

<div style="display: flex; justify-content: center; margin-bottom: 2rem;">
    <model-viewer 
    src="/assets/files/env.glb" 
    alt="A 3D model" 
    camera-controls 
    exposure = "0.8"
    style="width: 75%; height: 300px;border-radius: 15px; overflow: hidden;">
    </model-viewer>
</div>

The envelope was printed from PLA plastic. I designed each half using a band that acted as the sides, with internal tabs for fasteners. I have a weird preference for avoiding requirement for supports and out-of-plane detail, and this design reduced that. Covers for each half could be printed face-down (so as to pick up a beautiful finish from the print bed) and screwed down onto the bands with some countersunk screws. This gave the box a nice industrial look and feel.

I'd used this trick in a build at uni where you'd inject viscous acrylic paint into milled surfaces. The paint would adhere to the walls of each cut but sink in the middle, which would create a very nice radius once it set. I bought some paint syringes online and spent an evening injecting acrylic paint into the cuts in the print face.

<div style="display: flex; justify-content: center; height: 350px; margin-bottom: 2rem;">
  <img src="/images/matta-application/paint.png" alt="10:51:69pm" style="max-width: 100%; border-radius: 15px;">
</div>

For the text, I pulled the company logo from the website and vectorised it in GIMP. I also dropped the raster into a font finder and selected a similar typeface to use for the rest of the text. I had to do some clever shit for some characters - using the dots from the I's as colons, and copying the 'a' entirely. Once I had it arranged attractively, I imported the vectors into Fusion and extruded them from the envelope face.

I wanted a clever link to my website, because the hyperlinks in my CV probably wouldn't work after I printed it out. At first I was going to go for a QR code, but that would take too long to paint. So, I sourced some NFC tags online and got them delivered. They're just basically 1mm thick discs of 25mm diameter. I left a cutout in the back of one of the plates and glued the tag in behind it. You can program the tags using a simple phone utility.

<div style="display: flex; justify-content: center; height: 350px; margin-bottom: 2rem;">
  <img src="/images/matta-application/nfc.gif" alt="Scanning..." style="max-width: 100%; border-radius: 15px;">
</div>

Finally, I generated a gif from my CAD software which showed the box design being drawn up.

<img src="/images/envelope.gif" style="width: 400px; height: 400px; border-radius: 1em; display: block; margin: 0 auto;">

## Conclusion
At the time of writing this, I'm sitting on the couch in the Matta office, having come in a bit early to finish off this post. I got the job!

In hindsight, I think I really made the application for me. I liked it. I was *good* at it. I stayed up 'til midnight every day for a week - designing, painting and polishing, agonising over details. This was more effort than I'd put into anything I'd done at work since I was a recent graduate, and I think I know why.

Something changed since I was a kid, dreaming about a technical career. The type of problems our best minds once solved were practical. Nowadays, our skills are put to designing solutions for increasingly nebulous and abstract problems. Your average technical mind is more likely to be found creating the next fintech unicorn than repairing a pump for the well.

Making this application reminded me there is still value to be found in creating things that serve humanity in real life. That I can work on these problems for a living is rewarding, and the transition to this work has had a hugely positive effect on my wellbeing.

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
