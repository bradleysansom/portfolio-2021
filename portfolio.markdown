---
layout: default
title: Portfolio | 
---

 <style>
        @import url('https://fonts.googleapis.com/css2?family=Oxygen:wght@300;400;700&display=swap');
        body {
            background-color: #111111;
            font-family: 'Oxygen';
            background-image: url('monogram.png');
            font-size: 1.2em;
            background-size: 40px;
            background-repeat: round;
        }
        
        main div {
            padding: 10px;
            background-color: #000000;
            border-radius: 10px;
            margin: 10px;
            color: white;
        }
        
        main {
            width: 80vw;
            margin: auto;
            background-color: initial;
        }
        
        
        .seperator {
            text-align: center;
            color: white;
            background: rgb(44, 103, 159);
            background: linear-gradient(90deg, rgba(44, 103, 159, 1) 0%, rgba(121, 210, 184, 1) 100%);
        }
        
        
        
        .seperator img {
            height: 10vw;
            max-width: 70vw;
        }
        
        .welcome {
            border: 2px solid rgba(121, 210, 184, 1);
            background-image: url('concrete.jpg');
            padding: 150px;
            font-size: 1.5rem;
        }
        
        img.greeting {
            height: 8vw;
            max-width: 50vw;
            padding-bottom: 10px;
        }
        
        img.thanks {
            padding-top: 10px;
            height: 5vw;
            max-width: 50vw;
        }
        
        .blurb {
            padding-left: 150px;
            padding-right: 150px;
        }
        
        .blurb a {
            color: white;
        }
        
        .gallery {
            background-color: #cccccc;
            text-align: center;
        }
        
        .gallery img {
            width: 65vw;
        }
        
        .button {
            text-align: center;
            width: fit-content;
            background: rgb(44, 103, 159);
            background: linear-gradient(90deg, rgba(44, 103, 159, 1) 0%, rgba(121, 210, 184, 1) 100%);
            transition: 0.5s;
            padding: 10px 30px;
            margin: auto;
            margin-top: 10px;
            margin-bottom: 10px;
            cursor: pointer;
        }
        
        .button a {
            display: block;
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: 0.5s;
        }
        
        .button:hover a {
            color: rgb(44, 103, 159);
            transition: 0.5s;
        }
        
        .button:hover {
            background: white;
            transition: 0.5s;
        }
        
        .gallery video {
            width: 70vw;
        }
        
        .navigation {
            text-align: center;
        }
        
        span#jumpto {
            margin: auto;
            padding: 10px 10px;
            margin-bottom: 10px;
        }
        
        .navigation ul {
            margin: 0;
            padding: 0;
            padding-top: 10px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        
        .navigation li {
            border-radius: 10px;
            transition: 0.5s;
            display: inline-block;
            list-style-type: none;
            padding: 10px 30px;
        }
        
        .navigation li img {
            height: 4vw;
        }
        
        .navigation li:hover {
            background-color: #ffffff33;
            transition: 0.5s;
        }
        
        @media only screen and (max-width: 600px) {
            body {
                font-size: 1em;
            }
            .blurb,
            .welcome {
                padding-left: 10px;
                padding-right: 10px;
            }
            .all {
                width: 90vw;
            }
            img.greeting,
            img.thanks {
                height: 12vw;
                max-width: 50vw;
            }
        }
    </style>
    
<div class="welcome">
    <img class="greeting" id="greetingText" src="/portfolio/goodday.png" alt="Good day"> <br> Welcome to my portfolio. Below, please find a selection of the works I have created over the last couple of years. <br><img class="thanks" src="/portfolio/thanks.png" alt="Thanks">
</div>
<script>
                var today = new Date();
                var hour = today.getHours();
                console.log(hour);
                if (hour <= 5) {
                    var greeting = "goodnight.png";
                } else if (hour <= 11) {
                    var greeting = "goodmorning.png";
                } else if (hour <= 17) {
                    var greeting = "goodafternoon.png";
                } else if (hour <= 22) {
                    var greeting = "goodevening.png";
                } else {
                    var greeting = "goodnight.png";
                }
                document.getElementById('greetingText').src = greeting;
</script>
<div class="navigation">
    <span class="jumpto">Jump to:</span>
    <ul>
        <li>
            <a href="#infographics"><img src="/portfolio/infographics.png" alt="Infographics"></a>
        </li>
        <li>
            <a href="#branding"><img src="/portfolio/branding.png" alt="Branding"></a>
        </li>
        <li>
            <a href="#wayfinding"><img src="/portfolio/wayfinding.png" alt="Wayfinding"></a>
        </li>
        <li>
            <a href="#broadcasting"><img src="/portfolio/broadcast.png" alt="Broadcast design"></a>
        </li>
    </ul>
</div>
<div class="seperator" id="infographics">
    <img src="/portfolio/infographics.png" alt="Infographics">
</div>
<div class="blurb">
    As part of a project looking at the ways that infographics are used to present information in a graphical manner, I produced a poster which aims to explain how general elections work to first-time voters.
</div>
<div class="gallery">
    <video poster="thumnailinfographics.png" controls>
        <source src="/portfolio/infographic_development.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I developed my ideas with sketches, and settled on a basic design centred on a river motif. The impression of a flowing 'river' would lead from the Thames outside Big Ben, taking on the forms of ballot papers, an electoral roll, and finally a racecourse
    (extending the <a href="https://en.wikipedia.org/wiki/First-past-the-post_voting">'First Past the Post'</a> metaphor). With each sketch, I added annotations so that the next version of the infographic would be informed
    by the weaknesses of the last one.
</div>
<div class="gallery">
    <img src="/portfolio/progression.png" alt="The development of my infographic">
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/infog_develop.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I then moved on to the computer, using Illustrator to develop a final version of my infographic.
</div>
<div class="gallery">
    <img src="/portfolio/infographic.png" alt="How a British General Election works">
    <div class="button">
        <a href="https://drive.google.com/file/d/12h0AHF3GpHjj_Bh9ZzMPn8WEupSc8SS1/view?usp=sharing">View PDF</a>
    </div>
</div>
<div class="seperator" id="branding">
    <img src="/portfolio/branding.png" alt="Branding">
</div>
<div class="blurb">
    I undertook research and looked at case studies around branding, exploring the ways that designers can help to change the way that an organisation is viewed.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/branding_intro_research.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    As part of a project in college, I responded to a live branding brief for a local skincare company known as Skin Kitchen Co.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/brief.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I analysed the details about the company given in the branding brief, to look at what imagery, colour scheme, and themes my branding should incorporate.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/branding_development.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I utilised natural imagery, scanned in from foliage picked from my garden, as part of the brand for the skincare company. This made my brand more linked to the natural world, emphasising the desire of the company's owner for her products to be seen as
    ecological and pure. I created different versions of the logo, before deciding on which struck the right balance between easily reproducible and visually recognisable. I then created some physical mockups to explore the ways that the brand
    could be applied to packaging.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/cols.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I continued to develop my brand, creating patterns and alternative logos, and choosing a colour scheme and font which communicates the values set out in the brief.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/mockups.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I applied my branding system to a range of applications, including to packaging, signage, and social media.
</div>
<div class="gallery">
    <img src="/portfolio/styleboard.jpg" alt="Branding style board">
    <div class="button">
        <a href="https://drive.google.com/file/d/16pbn3bSRLUQgmqM4eh0tffkdLBx3n7ZS/view?usp=sharing">View PDF</a>
    </div>
</div>
<div class="blurb">
    I created a Branding Style Board to showcase my designs to the client, demonstrating the flexibility of my branding system.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/eval.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I evaluated my branding project, assessing what went right and how I could improve.
</div>
<div class="gallery">
    <img src="/portfolio/feedback.png" alt="feedback">
</div>
<div class="blurb">
    I enjoyed the chance to work on a live brief, a limitation which also helped me get used to working on tight deadlines and forced me to consider to a greater extent the desires of the client. The live brief was a design competition, in which I came second
    and received positive feedback from the client.
</div>
<div class="seperator" id="wayfinding">
    <img src="/portfolio/wayfinding.png" alt="Wayfinding design">
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/idea.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    Faced with a number of briefs to pick from as part of a mock exam paper, I chose to theme my project around the 'Haven' option. I wanted to create a number of interventions in public space around my hometown of Bradford in order to shift the balance of
    the built environment in favour of pedestrians for once. I researched the huge problem of car dependency within Bradford, in order to inform my designs.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/haven-sketches.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I applied some of my ideas about what I could design for wayfinding signage to some specific sites in Bradford. I looked at one specific route in Bradford, one commonly taken by tourists visiting the Media Museum via rail or bus. This is a route that
    either involves a poorly-signed on-street route, or using a system of underpasses and subways which are dingy and unappealing. I looked at the sorts of signage that could be included there to brighten the area up and to improve navigation.
    I also made some paper and digital sketches of isometric representations of Bradford buildings. These would then be incorporated into the graphics I eventually made.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/gifs.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I created animated .gif icons for many notable buildings in Bradford, in a monochrome isometric style. These were to be used on animated signage projects or on websites or apps as part of an integrated brand promoting walking in Bradford. I assembled
    these into a basic website to showcase how animated signs could be created.
    <div class="button">
        <a href="https://bradleysansom.github.io/signage/">View as webpage</a>
    </div>
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/rail.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I also created simple animations for an arrow, to be used on directional signage, and the logos of National Rail and Metro (West Yorkshire's transport authority).
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/princes.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    Using the sort of signage used by the <a href="https://en.wikipedia.org/wiki/Legible_London">Legible London project</a> as inspiration, I produced an example of what an animated piece of signage could look like in the centre of Bradford,
    allowing pedestrians to navigate between landmarks with ease.
</div>
<div class="gallery">
    <img src="/portfolio/jacobswell.png" alt="Jacobs Well">
    <div class="button">
        <a href="https://bradleysansom.github.io/sphere/jacobs-well/">View in 360??</a>
    </div>
</div>
<div class="blurb">
    I then applied some of the icons and graphical elements I had created to a number of scenes. The first is in the subway beneath the busy Jacobs Well roundabout in Bradford city centre.
</div>
<div class="gallery">
    <img src="/portfolio/kirkgate.png" alt="Kirkgate">
    <div class="button">
        <a href="https://bradleysansom.github.io/sphere/darley-street/">View in 360??</a>
    </div>
</div>
<div class="blurb">
    The second location was centred around one main 'hoop' design, an installation which would promote connectivity between Bradford's historic 'Top of Town' and the newer, more commercialised areas down the hill.
</div>
<div class="gallery">
    <img src="/portfolio/interchange.png" alt="Interchange Nelson St">
    <div class="button">
        <a href="https://bradleysansom.github.io/sphere/interchange/">View in 360??</a>
    </div>
</div>
<div class="blurb">
    The third location is close to the rear entrance to Bradford Interchange, the main bus and rail station in the city. I added signage to improve wayfinding and to brighten the walk from the shops to the station.
</div>
<div class="blurb">
    Please note that the above pieces of work used imagery from Google Street View. Ideally, I'd have been able to use primary photographs to edit. However, this was not possible due to the coronavirus lockdown.
</div>
<div class="seperator" id="broadcasting">
    <img src="/portfolio/broadcast.png" alt="Broadcast design">
</div>
<div class="blurb">
    My most recent project involves creating the branding for a local TV channel. As part of the preparation for the project, I wrote a Statement of Intent summarising my aims in the project. </div>
<div class="button">
    <a href="https://drive.google.com/file/d/1FN9b_sBRnPeQ1ixlt-91vXNHRgDCeg3x/view?usp=sharing">View statement of intent</a>
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/experi.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    After conducting a photoshoot in my local area of various pieces of equipment used for picking up broadcast signals, I proceeded to manipulate these images to highlight the invisible messages being transmitted through the air continually.<br>                I then moved on towards exploring the branding used as part of broadcasting, and specifically started a project to develop a brand for a TV station local to West Yorkshire.
</div>

<div class="gallery">
    <video controls>
        <source src="/portfolio/logodev.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I decided that the channel should be known as Channel 8. The existing network of local TV channels available in many areas operates on Freeview channel 8, and I envisage that my brand would continue this. I developed a logo based around segments of a
    circle, which create the general impression of a numeral 8. Using paper, I sketched out some ways that the logo could be animated and incorporated into graphics on screen. I made sure to produce variants of the logo for different backgrounds,
    so that it remains legible in all applications.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/patterns.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    After researching the technical patterns that have been used for the decades to test the performance of TV screens, I created a range of patterns based on the test cards familiar to viewers.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/sourcesofpatt.mp4" type="video/mp4">
    </video>
</div>
<div class="blurb">
    I documented the sources of inspiration for the various patterns I made for the brand. It is my hope that the viewers subconsciously associate these patterns with television, both on screen and off screen.
</div>
<div class="gallery">
    <img src="/portfolio/endboard.png" alt="Trailer endboards">

</div>
<div class="blurb">
    One of my first experiments in the project was creating the graphic shown at the end of a programme trailer. I sketched some ideas on paper, which incorporated the patterns alongside the curved elements from the logo.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/endboard.mp4" type="video/mp4">
    </video>
    <div class="button">
        <a href="https://bradleysansom.github.io/o/c/h/o/endboard/index.html">Try out the graphic generator</a>
    </div>
</div>
<div class="blurb">
    I have produced a web app which allows unique, randomised graphics to be created for the channel. It uses the patterns I have created, and takes inputs from the user about what programme the graphic will be promoting. The idea is that every graphic generated
    for the channel will be seen just once; I have calculated that there are over 300 million combinations of the patterns making up an endboard. The graphic could be tailored to fit the mood of the programme it was promoting; for instance
    more sombre programmes could use just the greyscale patterns. <br>The generator, by deselecting the 'Show programme information' option, and selecting the 'Autogenerate' option, can produce a sequence of graphics which,
    when shown consecutively, would form part of the channel ident. I enjoyed the opportunity to create generative graphics during this project, an area which I would like to explore further in future.


</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/alert.mp4" type="video/mp4">
    </video>
    <div class="button">
        <a href="https://bradleysansom.github.io/o/c/h/o/alert/index.html">Try out the alert generator</a>
    </div>
</div>
<div class="blurb">
    I undertook research into the different ways that TV channels generate graphics for their channels. I came across the <a href="https://twitter.com/BBCDesignScot/status/1296020576096616448?s=20">RowZed</a> tool, used by the BBC to show
    sports graphics, which are generated through HTML. I designed and built a similar solution for my channel, which takes inputs and allows an animated graphic to be generated on the fly. This gives flexibility to my designs.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/further.mp4" type="video/mp4">
    </video>
    <div class="button">
        <a href="https://bradleysansom.github.io/o/c/h/o/ipp/index.html">Try out the 'Now and Next' graphic generator</a>
    </div>
    <div class="button">
        <a href="https://bradleysansom.github.io/o/c/h/o/access/index.html">Try out the Accessibility graphic generator</a>
    </div>
</div>
<div class="blurb">
    I created further graphic generators, which allow the graphics for the channel to be created generatively. This gave me an opportunity to take into consideration the needs of the wide range of audience members that would be watching; I therefore created
    a graphic that would show at the beginning of a programme, flagging if the show was subtitled, audio described, and signed. I also produced a graphic which would be shown at the end of a programme, signalling what was to follow.
</div>
<div class="gallery">
    <img src="/portfolio/emley.png" alt="Poster">

</div>
<div class="blurb">
    I produced a range of posters to promote the TV channel. They combine phrases associated with Yorkshire, with terms to do with TV. In the example above, the 'anthem of Yorkshire', <i>On Ilkla Moor Baht 'At</i>, has been combined with the
    name of the landmark local TV transmitter Emley Moor, to create a uniquely Yorkshire feeling slogan for the channel. The use of the coloured bars is carried over from the patterns on screen, creating a link between the various applications
    of the brand.
</div>
<div class="gallery">
    <img src="/portfolio/goodnight.gif" alt="Advertisements">

</div>
<div class="blurb">
    In another series of animated posters, I combined classic catchphrases from TV with the names of places in West Yorkshire. For instance, in the example above, the well-known catchphrase of <i>The Two Ronnies</i> is alluded to, but with
    a distinct grounding in Yorkshire, symbolising the arrival of a new channel in the county. I created further such posters, which when seen as part of a series would help to raise brand awareness of the channel.
</div>
<div class="gallery">
    <img src="/portfolio/accessibility.png" alt="Accessibility poster">

</div>
<div class="blurb">
    I produced a set of posters featuring the accessibility icons I had created. I compiled them into a 3D scene, and made versions in each of the brand's signature colours. These posters help to promote the inclusive, public service values of a channel that
    strives to cater to all through the provision of subtitles, audio description, and sign language.
</div>
<div class="gallery">
    <video controls>
        <source src="/portfolio/social.mp4" type="video/mp4">
    </video>

</div>
<div class="blurb">
    I produced an animated graphic for promoting the channel's launch on social media. I then created a mockup of how this would look on a social media feed.
</div>
<div class="gallery">
    <img src="/portfolio/brandboard1.png" alt="Branding style board">

</div>
<div class="blurb">
    I produced a branding style board to summarise the work I had done on the brand. I included the colours and fonts I had used as a reference, and then added mockups of how the graphics I had produced would look on screen and elsewhere.
</div>
<div class="gallery">
    <img src="/portfolio/brandboard2.png" alt="Branding style board">
    <div class="button">
        <a href="https://drive.google.com/file/d/1YMqkPOgPq_pHLvl0HGTm6WWpXhmTqkIi/view?usp=sharing">View high-resolution PDF branding board</a>
    </div>
</div>
<div class="blurb">
    I printed out my branding style board and mounted it.
</div>
