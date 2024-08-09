---
title: "[New] In 2024, A Beginner's Tutorial on Using LUTs in AR"
date: 2024-08-08T02:13:59.728Z
updated: 2024-08-09T02:13:59.728Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes [New] In 2024, A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes [New] In 2024, A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://thmb.techidaily.com/78f06b81f7c57e1e88ac6a7fa4601f5ae07cf7d31be3889aa12b125cc68b1e89.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-decoding-technical-difficulties-in-facebook-live-videos/"><u>[New] 2024 Approved  Decoding Technical Difficulties in Facebook Live Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-beginners-blueprint-progressive-sound-intensity-rise/"><u>[New] Beginner’s Blueprint  Progressive Sound Intensity Rise</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-find-anything-you-want-to-know-about-instagram-video-limit-for-2024/"><u>[New] Find Anything You Want to Know About Instagram Video Limit for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-intuitive-steps-setting-up-snapchat-macos-style/"><u>[New] In 2024, Intuitive Steps  Setting up Snapchat macOS-Style</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-leading-av-creators-digital-edition-list/"><u>[New] Leading AV Creators  Digital Edition List</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-top-tier-funny-editing-tool/"><u>[New] Top-Tier Funny Editing Tool</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transform-sound-with-cloud-tools-top-5-online-text-to-speech-services-reviewed/"><u>[New] Transform Sound with Cloud Tools  Top 5 Online Text-to-Speech Services Reviewed</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-visual-snips-tool/"><u>[Updated] 2024 Approved  Visual Snips Tool</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-a-beginners-guide-to-personal-brand-craftsmanship-for-2024/"><u>[Updated] A Beginner's Guide to Personal Brand Craftsmanship for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-cost-free-webinar-software-for-recording-sessions/"><u>[Updated] Cost-Free Webinar Software for Recording Sessions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unleash-your-brands-potential-on-igtv-with-these-top-10-tactics/"><u>[Updated] Unleash Your Brand’s Potential on IGTV with These Top 10 Tactics</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-a-review-10-best-free-luts-with-download-links/"><u>2024 Approved  A Review  10 Best Free LUTs with Download Links</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-benq-bl2711u-a-journey-through-professional-4k-display-tech/"><u>2024 Approved  BenQ BL2711U - A Journey Through Professional 4K Display Tech</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-best-writing-ever-seen-across-film-genres/"><u>2024 Approved  Best Writing Ever Seen Across Film Genres</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-beyond-inshot-top-pc-editing-solutions/"><u>2024 Approved  Beyond Inshot  Top PC Editing Solutions</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-calming-chronicles-on-screen-evaluating-bedtime-story-videos/"><u>2024 Approved  Calming Chronicles on Screen  Evaluating Bedtime Story Videos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-crafting-conceptions-unveiling-the-worlds-best-schools-for-stories-top-8/"><u>2024 Approved  Crafting Conceptions  Unveiling the World's Best Schools for Stories (Top 8)</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-elevate-your-android-vids-top-10-players/"><u>2024 Approved  Elevate Your Android Vids  Top 10 Players</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-entering-a-new-era-with-htcs-immersive-vr-gaming/"><u>2024 Approved  Entering a New Era with HTC's Immersive VR Gaming</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-freeze-frame-like-a-pro-easy-steps-to-amazing-slow-mo-videos-on-android/"><u>2024 Approved  Freeze Frame Like a Pro  Easy Steps to Amazing Slow Mo Videos on Android</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-from-timeless-tales-in-tone-on-tone-to-dynamic-digital-narratives/"><u>2024 Approved  From Timeless Tales in Tone-On-Tone to Dynamic Digital Narratives</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-gamers-selection-top-livestraning-tech-picks/"><u>2024 Approved  Gamer's Selection  Top Livestraning Tech Picks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-generating-income-with-every-swipe-up/"><u>2024 Approved  Generating Income with Every Swipe Up</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-harness-power-of-persuasion-with-these-tips-for-reddit/"><u>2024 Approved  Harness Power of Persuasion with These Tips for Reddit</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-hero5-vs-yi-4k-updated-battle-for-best-action-cam/"><u>2024 Approved  Hero5 Vs. Yi 4K  Updated Battle for Best Action Cam</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-how-to-choose-vr-headset-mobile-vr-or-tethered-vr/"><u>2024 Approved  How to Choose VR Headset? Mobile VR or Tethered VR?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-iconic-stock-photographs-meme-lives-and-histories/"><u>2024 Approved  Iconic Stock Photographs  Meme Lives and Histories</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-inside-the-secrets-of-quantum-hdr-photography/"><u>2024 Approved  Inside the Secrets of Quantum HDR Photography</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-photography-on-instagram-adding-images-made-simple/"><u>2024 Approved  Photography on Instagram  Adding Images Made Simple</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-pioneering-seven-water-resilient-camera-brands/"><u>2024 Approved  Pioneering Seven Water-Resilient Camera Brands</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-prime-picks-best-windows-phone-video-players-list/"><u>2024 Approved  Prime Picks  Best Windows Phone Video Players List</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-ranking-relaxing-front-row-activities-that-arent-sports/"><u>2024 Approved  Ranking Relaxing Front Row Activities That Aren't Sports</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-step-by-step-to-supercharge-videos-on-snapchat/"><u>2024 Approved  Step by Step to Supercharge Videos on Snapchat</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-streampulse-app-testimonials/"><u>2024 Approved  StreamPulse App Testimonials</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-toonbox-complete-insight-for-24-year/"><u>2024 Approved  ToonBox Complete Insight for '24 Year</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-top-tactics-in-producing-convincing-customer-testimonial-videos/"><u>2024 Approved  Top Tactics in Producing Convincing Customer Testimonial Videos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-transitioning-video-content-into-stills-with-windows-11/"><u>2024 Approved  Transitioning Video Content Into Stills with Windows 11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-ultimate-choice-15-superior-action-recorders/"><u>2024 Approved  Ultimate Choice  15 Superior Action Recorders</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-visual-riches-at-no-cost-the-top-10-finds/"><u>2024 Approved  Visual Riches at No Cost – The Top 10 Finds</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-voice-customization-leaders-beyond-echo-magic/"><u>2024 Approved  Voice Customization Leaders  Beyond Echo Magic</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-honor-magic5-ultimate-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/6-methods-for-switching-from-apple-iphone-8-to-samsung-drfone-by-drfone-transfer-from-ios/"><u>6 Methods for Switching from Apple iPhone 8 to Samsung | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/best-ways-to-record-live-sports-streaming-for-2024/"><u>Best Ways to Record Live Sports Streaming for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-honor-play-40c-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-honor-play-40c-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Honor Play 40C Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-crafting-compelling-podcast-names-a-detailed-guide-with-idea-examples/"><u>In 2024, Crafting Compelling Podcast Names  A Detailed Guide with Idea Examples</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-vivo-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Vivo Pattern Lock Screen</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-windows-movie-maker-for-efficient-video-projects-in-windows-8/"><u>In 2024, Navigating Windows Movie Maker for Efficient Video Projects in Windows 8</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-8-digital-collage-crafting-software/"><u>In 2024, TOP 8 Digital Collage Crafting Software</u></a></li>
<li><a href="https://some-skills.techidaily.com/tag-friends-listen-to-this-podcast-story-for-2024/"><u>Tag Friends  Listen to This Podcast Story for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/troubleshooting-stuttering-video-on-photo-booth-app/"><u>Troubleshooting Stuttering Video on Photo Booth App</u></a></li>
</ul></div>
