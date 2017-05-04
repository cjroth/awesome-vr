# Awesome VR [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Virtual Reality (VR) things.

*Inspired by the [awesome list](https://github.com/sindresorhus/awesome) thing.*

**Check out my [blog](https://cjroth.com) :monkey: or say *hi* on [Twitter](https://twitter.com/chrisrxth).**

## Headsets

- Google Cardboard [ [Google](https://vr.google.com/cardboard/index.html) | [Wikipedia](https://en.wikipedia.org/wiki/Google_Cardboard) ] \($15+) - Allows you to turn your phone into a VR device.
- Samsung Gear VR [ [Samsung](http://www.samsung.com/global/galaxy/wearables/gear-vr/) | [Oculus](https://www.oculus.com/en-us/gear-vr/) | [Wikipedia](https://en.wikipedia.org/wiki/Samsung_Gear_VR) ] \($100) - Powered by Oculus's technology; allows you to use a Samsung phone as VR device.
- Sony Playstation VR [ [Sony (Blog)](http://blog.us.playstation.com/2016/03/15/playstation-vr-launching-october-for-399/) | [Wikipedia](https://en.wikipedia.org/wiki/PlayStation_VR) ] \($400) - Requires PlayStation 4; not quite as good graphics as Rift/Vive; launching October 13, 2016.
- Oculus Rift [ [Oculus](https://www.oculus.com/en-us/rift/) | [Wikipedia](https://en.wikipedia.org/wiki/Oculus_Rift) ] \($600) - Requires gaming PC.
- HTC Vive [ [HTC Vive](https://www.htcvive.com/us/) | [Wikipedia](https://en.wikipedia.org/wiki/HTC_Vive) ] \($800) - Requires gaming PC.
- Sensics [ [Official](http://sensics.com/) | [Wikipedia](https://en.wikipedia.org/wiki/Sensics) ] - Many different professional (not consumer) grade products.

## Complete VR Systems
- Leap Motion Orion [ [Leap Motion](https://www.leapmotion.com/product/vr) ] - Uses Ocuclus Rift CV1 or HTC Vive and Unity.
- Steam VR [  [Steam](http://store.steampowered.com/steamvr) ] - Uses HTC Vive as headset.

## Software

- [Unity](https://unity3d.com/learn/tutorials/topics/virtual-reality)
    - C#, Javascript
    - [Google VR SDK](https://developers.google.com/vr/unity/) available
- [Unreal Engine](https://www.unrealengine.com/vr-page)
- [WebVR](https://webvr.info/)

    - Experimental Javascript API that provides access to VR devices in the browser
    - Available in experimental builds of Chrome and nightly builds of Firefox
    - Polyfill available: https://github.com/borismus/webvr-polyfill by https://github.com/borismus
    - [Mozilla VR](https://mozvr.com/)
    - [Aframe](https://aframe.io/), MozVR’s open source framework for creating WebVR worlds with markup (https://aframe.io/)
- [Google Daydream](https://vr.google.com/daydream/)
	- Coming October 13, 2016.
	- Competitor to Unity?
	- Daydream-ready phones - equipped with sufficient sensors, displays, and processors for VR.
	- Android-N - version of android with VR mode.
	- Google is developing a VR viewer to work with Android phones and a controller.
	- YouTube might support VR experiences in the future.
	- Google Street View could support VR.
- [OpenVR](https://github.com/ValveSoftware/openvr)
   - SDK by Steam. Not actually open-source.
- [Open Source Virtual Reality (OSVR)](https://en.wikipedia.org/wiki/Open_Source_Virtual_Reality)
   - A project to enable cross-compatibility of headsets and software.
   - Sponsored by Razer and [Sensics](https://en.wikipedia.org/wiki/Sensics).

## Design Considerations
- Don’t begin until the user indicates readiness
- Mismatch between bodily cues and visual cues cause simulator sickness
- User should tap button with VR icon to enter a scene
- Do not use dialogues; they do not work with binocular vision
- Indicate that an app includes VR by mentioning VR in the title and including screenshots of binocular vision
- Use full screen mode, not lights out mode
- Users can target/select objects in their field of vision; when doing so, display a reticle (plus sign with circle around it) to show the user what they are “selecting"
- Don’t use text instructions; use audio
- Using haptic (sense of touch) information for feedback is good
- Put UI controls directly in user’s field of vision
- Use “fuse buttons” to let the user select things but also allow the user to click the button on their goggles so they don’t have to wait for the button to activate. A fuse button is a button that the user can “click” by targeting their glasses at a point and holding it for a few seconds to activate it.
- Show a countdown to activation for fuse buttons
- Don’t put fuse buttons too close together
- Avoid sudden transitions between dark and light brightness
- Use fixed objects to ground a user - eg putting them in a cockpit, virtual chair, etc. If they are sitting IRL then show them sitting in the VR.
- Users should be active controllers in the app, not passengers
- Try to always keep head tracking on in the app; if needed, show splash screens or 2D images in 3D space

## Applications

- Gaming
- Films/Live Events
- Architecture/Real Estate/Urban Planning
- Medicine
- Training - Paramedics, flight simulation, surgeons, etc.
- Tourism - Demonstrating a destination in 3D.
- Psychology/meditation
- Social - Joining a 3D chat room, meeting, etc.

## People

- Sanem Avcil [ [Twitter](https://twitter.com/Sanemavcil) ] - VR influencer.
- Clay Bavor - VP of VR @ Google.
- David Coz [ [Twitter](https://twitter.com/dav_cz) ] - Co-inventor of Google Cardboard.
- Rob Crisco [ [Twitter](https://www.linkedin.com/in/robcrasco) ] - VR influencer; CyberAdept.
- Bob O’Donnel [ [Twitter](https://twitter.com/bobodtech) ] - Tech researcher covering IoT, VR, AR, AI.
- Nate Ralph [ [CNET](http://www.cnet.com/profiles/nateralph/#articles) ] - Covers VR for CNET.

## Major Players

- HTC
- Google
- Unity
- Sony
- Oculus (acquired by Facebook for $2B in cash in 2014)
- Samsung
- Mozilla
- Sensics [ [Official](http://sensics.com/) | [Wikipedia](https://en.wikipedia.org/wiki/Sensics) ] - Create professional-grade headsets.

## Media

- CNET

## Timeline

- **2016**: “The Year Of VR"
- **Fall 2016**: Google Daydream Launches

## Articles

- 5/15 - [SteamVR: Everything You Need To Know](http://www.pcgamer.com/steamvr-everything-you-need-to-know/) - PC Gamer
- 5/16 - [Virtual Reality 2016: Top 100 Influencers and Brands](http://www.onalytica.com/blog/posts/virtual-reality-2016-top-100-influencers-and-brands/
) - Onalytica
- 5/16 - [A Glimpse Inside Google’s VR Daydream](http://www.cnet.com/special-reports/a-glimpse-inside-googles-vr-daydream/
) - CNET

## Resources
- [Yobi3D - Free 3D model search engine](https://www.yobi3d.com/)
- [Statistics and facts about Virtual Reality (VR)](http://www.statista.com/topics/2532/virtual-reality-vr/) - Statistica
- [Virtual Reality 101](http://www.cnet.com/special-reports/vr101/) - CNET
- [`google-vr` on Stack Overflow](http://stackoverflow.com/questions/tagged/google-vr)
- [`vr` on Stack Overflow](http://stackoverflow.com/questions/tagged/vr)
- [`aframe` on Stack Overflow](http://stackoverflow.com/questions/tagged/aframe)
- [Google Community for “Cardboard and VR Developers”](https://plus.google.com/communities/111524380182206513071)
- [Google VR on Google Developers](https://developers.google.com/vr/)
- [Unity Documentation for VR](http://docs.unity3d.com/Manual/VirtualReality.html)
- [Introduction to VR for Unity](https://unity3d.com/learn/tutorials/topics/virtual-reality)
- [Google VR on GitHub](https://github.com/googlevr/)
- [WebVR API Spec (W3C)](https://w3c.github.io/webvr/)
- [WebVR API Documentation (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebVR_API)
- [Aframe](https://aframe.io/) - MozVR’s open source framework for creating WebVR worlds with markup.
- [VR Slack Channel](https://vrslack.typeform.com/to/mKpqkA) - Created by Eva Hoerth.
- [VR Best Practices by Oculus](https://developer.oculus.com/documentation/intro-vr/latest/concepts/bp_intro/)
- [Playstation VR on Reddit](https://www.reddit.com/r/playstationvr/)

## Other Awesome VR Lists:

- [Awesome VR](https://github.com/thejourneydude/awesome_vr)
- [Awesome WebVR](https://github.com/wizztjh/awesome-WebVR)
- [Awesome VR UX](https://github.com/mauricesvay/awesome-vr-ux)

## Groups

## Startups

## Conferences
