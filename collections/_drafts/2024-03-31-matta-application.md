---
layout: post
title: Returning to my roots in hardware
date: 2025-03-31
summary: Creating a truly full-stack CV
---

Recently, after two years working in enterprise tech consulting, I decided to try something new and make a move into a product company.

Here's the story of how I initially struggled to sell myself as a technologist, eventually stumbled across a role that couldn't have been a better fit, and put my absolute best efforts into making my application.

<div style="display: flex; justify-content: center; height: 350px; margin-bottom: 2rem;">
  <img src="/images/matta-application/office.jpeg" alt="The Office!" style="max-width: 100%; border-radius: 15px;">
</div>

Those that know me know I'm a hardware person. I muck around with cars and motorcycles, build cameras and go out of my way to fix things that break, often at more expense than necessary. I'm 3 for 3 on nutribullet repairs.

You can imagine my innocent frustration when, upon finishing uni, the search for "robotics engineer" roles in central NZ yielded zero results. I ended up working at engineering-*sounding* businesses, but I felt I was never solving any "real" engineering problems. My technical skills did not improve fast. All the while, I'm reading online about the amazing work people were doing overseas at tech companies.

When I relocated to the UK, I decided to also make a move from corporate number-crunching into proper software development. This was a great decision - I felt so much more at home doing more technical work and talking with technical people. However, I eventually grew to be dissatisfied in how connected I was with the results of my work. I thought that maybe if I got a "proper" tech job, this might be fixed.

## Solution to the job hunt: get very lucky

I spent a few months in discussions with various tech companies, and was quite unsuccessful. After some unfulfilling searching, I eventually stumbled across Matta. They had a lot of really digestible published research which they'd packaged as a slick product. Their opening sounded like one of the vanishingly few roles that would value hardware, software and creative skills. On the listing, they said applicants were encouraged to find creative ways to apply.

## Applying Creatively

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

The envelope was printed from PLA plastic. I designed each half using a band that acted as the sides, with internal tabs for fasteners. Then, covers for each half could be printed face-down (so as to pick up a beautiful finish from the print bed) and screwed down onto the bands with some countersunk screws. This gave the box a nice industrial look and feel.

For the text on the box, I pulled the company logo from the website and vectorised it in GIMP. I also dropped the font into a font finder and selected a similar typeface to use for the rest of the text. I had to copy the 'a's as the font I found was dissimilar. I had to get creative and use the dots from the 'i's in the colons. Once I had it arranged attractively, I imported the vectors into Fusion and extruded them from the envelope face, taking care that they would be legible with the print resolution.

I'd used a technique in a build at uni where you'd inject viscous acrylic paint into milled surfaces. The paint would adhere to the walls of each cut but sink in the middle, which would create a very nice radius once it set. I bought some paint syringes online and spent an evening injecting acrylic paint into the cuts in the print face.


<div style="display: flex; justify-content: center; height: 350px; margin-bottom: 2rem;">
  <img src="/images/matta-application/paint.png" alt="10:51:69pm" style="max-width: 100%; border-radius: 15px;">
</div>

I wanted a clever link to my website, because the hyperlinks in my CV probably wouldn't work after I printed it out. At first I was going to go for a QR code, but that would take too long to paint. So, I sourced some NFC tags online and got them delivered. They're just basically 1mm thick discs of 25mm diameter. I left a cutout in the back of one of the plates and glued the tag in behind it. You can program the tags using a simple phone utility.

<div style="display: flex; justify-content: center; height: 350px; margin-bottom: 2rem;">
  <img src="/images/matta-application/nfc.gif" alt="Scanning..." style="max-width: 100%; border-radius: 15px;">
</div>

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
