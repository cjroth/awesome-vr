# Awesome VR [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Virtual Reality (VR) things.

*Inspired by the [awesome list](https://github.com/sindresorhus/awesome) thing.*

**Check out my [blog](https://cjroth.com) :monkey: or say *hi* on [Twitter](https://twitter.com/chrisrxth).**

## Headsets

> There are currently 3 main types of VR Headsets. Desktop VR, Mobile VR and Standalone VR. Desktop Headsets require a desktop computer and are the most powerful of the three. Mobile headsets act as a peripheral and require a smartphone to run the application. Mobile is generally the weakest of the 3 and typically only supports 3-DOF instead of 6-DOF. Standalone headsets do not require an external device since everything needed is built into the headset itself. Standalone is the newest of the 3 and acts either as a lower powered version of Desktop VR or as Mobile VR without the need for a phone.

<table>
	<tr>
		<th>Headset</th>
		<th>Type</th>
		<th>Price (Lowest)</th>
		<th>Resources</th>
	</tr>
	<tr>
		<td>Google Cardboard</td>
		<td>Mobile</td>
		<td>$15</td>
		<td>
			<a href="https://vr.google.com/cardboard/index.html">Google</a>
			<a href="https://en.wikipedia.org/wiki/Google_Cardboard">Wikipedia</a>
		</td>
	</tr>
	<tr>
		<td>Samsung Gear VR</td>
		<td>Mobile</td>
		<td>$100</td>
		<td>
			<a href="http://www.samsung.com/global/galaxy/wearables/gear-vr/">Samsung</a>
			<a href="https://www.oculus.com/en-us/gear-vr/">Oculus</a>
			<a href="https://en.wikipedia.org/wiki/Samsung_Gear_VR">Wikipedia</a>
		</td>
	</tr>
	<tr>
		<td>Sony Playstation VR</td>
		<td>Desktop (PS4)</td>
		<td>$400</td>
		<td>
			<a href="http://blog.us.playstation.com/2016/03/15/playstation-vr-launching-october-for-399/">Sony</a>
			<a href="https://en.wikipedia.org/wiki/PlayStation_VR">Wikipedia</a>
		</td>
	</tr>
	<tr>
		<td>Oculus Rift</td>
		<td>Desktop</td>
		<td>$400</td>
		<td>
			<a href="https://www.oculus.com/en-us/rift/">Rift</a>
			<a href="https://en.wikipedia.org/wiki/Oculus_Rift">Wikipedia</a>
		</td>
	</tr>
	<tr>
		<td>Oculus Quest</td>
		<td>Standalone (Desktop)</td>
		<td>$400</td>
		<td>
			<a href="https://www.oculus.com/quest/">Quest</a>
		</td>
	</tr>
	<tr>
		<td>Oculus Go</td>
		<td>Standalone (Mobile)</td>
		<td>$200</td>
		<td>
			<a href="https://www.oculus.com/go/">Go</a>
		</td>
	</tr>
	<tr>
		<td>Htc Vive</td>
		<td>Desktop</td>
		<td>$500</td>
		<td>
			<a href="https://www.htcvive.com/us/">Htc Vive</a>
			<a href="https://en.wikipedia.org/wiki/HTC_Vive">Wikipedia</a>
		</td>
	</tr>
	<tr>
		<td>Htc Vive Pro</td>
		<td>Desktop</td>
		<td>$800</td>
		<td>
			<a href="https://www.vive.com/us/product/vive-pro/">Vive Pro</a>
		</td>
	</tr>
	<tr>
		<td>Htc Vive Focus</td>
		<td>Standalone (Desktop)</td>
		<td>TBA</td>
		<td>
			<a href="https://www.vive.com/cn/product/vive-focus-en/">Vive Focus</a>
		</td>
	</tr>
	<tr>
		<td>Sensics</td>
		<td>Desktop</td>
		<td>Nonconsumer</td>
		<td>
			<a href="http://sensics.com/">Sensics</a>
			<a href="https://en.wikipedia.org/wiki/Sensics">Wikipedia</a>
		</td>
	</tr>
	<tr>
		<td>HP WMR</td>
		<td>Desktop</td>
		<td>$259</td>
		<td></td>
	</tr>
	<tr>
		<td>Lenovo Explorer</td>
		<td>Desktop</td>
		<td>$199</td>
		<td></td>
	</tr>
	<tr>
		<td>Samsung Odyssey</td>
		<td>Desktop</td>
		<td>$499</td>
		<td></td>
	</tr>
	<tr>
		<td>ASUS HC102</td>
		<td>Desktop</td>
		<td>$423</td>
		<td></td>
	</tr>
	<tr>
		<td>Acer WMR</td>
		<td>Desktop</td>
		<td>$246</td>
		<td></td>
	</tr>
	<tr>
		<td>Dell Visor</td>
		<td>Desktop</td>
		<td>$289</td>
		<td></td>
	</tr>
</table>

## Complete VR Systems
- Leap Motion Orion [ [Leap Motion](https://www.leapmotion.com/product/vr) ] - Uses Oculus Rift CV1 or HTC Vive and Unity.
- Steam VR [  [Steam](http://store.steampowered.com/steamvr) ] - Uses HTC Vive, Oculus Rift and WMR headsets

## Software

- [Unity](https://unity3d.com/learn/tutorials/topics/virtual-reality)
    - C#, Javascript
    - [Google VR SDK](https://developers.google.com/vr/unity/) available
    - [SteamVR plugin](https://assetstore.unity.com/packages/tools/integration/steamvr-plugin-32647) available
    - [Windows Mixed Reality](https://unity3d.com/partners/microsoft/mixed-reality) built-in support
- [Unreal Engine](https://www.unrealengine.com/vr-page)
	- C++, Blueprint
- [Godot](https://godotengine.org/article/godot-3-vr-and-ar-support)
	- GDScript, C#, C++, VisualScript
	- 3rd party plugins for Python, Nim and D
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
- [OpenXR](https://www.khronos.org/openxr)
	- Khronos VR Initiative for standardized VR and AR
- [Adobe Creative](https://www.adobe.com/creativecloud/video/360-vr-video-tools.html)
	- Used for editing VR video and photos
- [CityEngine](https://www.esri.com/en-us/arcgis/products/esri-cityengine/overview)
	- Used for creating 3D models from map data that can be viewed in VR
	- Viewed in VR using the [ArcGIS 360 VR App](https://www.arcgis.com/home/item.html?id=58094e8cf92644d28d5cb4a4fda3602e)
		- Requires Samsung Gear VR

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
- Avoid creating sudden cuts to another scene if producing cinematics
- Using spatial audio for attracting user attention is highly effective
- Placing objects in scene closer than a perceived 6 inches from user's face will make them uncomfortable
- Average human has a binocular field of view of ~114 degrees (about 1/3 of a circle)

## Applications

- Architecture/Real Estate/Urban Planning
- Collaboration - Screen share, meetings, using 3D renders for pinpointing issues.
- Education - Interact with molecules in chemistry, view the Z-axis naturally in math, etc.
- Films/Live Events
- Gaming
- Medical - Treatment for depression, anxiety, PTSD, phobias, etc.
- Psychology/meditation
- Social - Joining a 3D chat room, virtual living room, etc.
- Tourism - Demonstrating a destination in 3D. Exploring museums, landmarks, and more.
- Training - Paramedics, flight simulation, surgeons, welding, etc.

## People

- Sanem Avcil [ [Twitter](https://twitter.com/Sanemavcil) ] - VR influencer.
- Clay Bavor - VP of VR @ Google.
- David Coz [ [Twitter](https://twitter.com/dav_cz) ] - Co-inventor of Google Cardboard.
- Rob Crisco [ [Twitter](https://www.linkedin.com/in/robcrasco) ] - VR influencer; CyberAdept.
- Bob O’Donnel [ [Twitter](https://twitter.com/bobodtech) ] - Tech researcher covering IoT, VR, AR, AI.
- Nate Ralph [ [CNET](http://www.cnet.com/profiles/nateralph/#articles) ] - Covers VR for CNET.
- Palmer Luckey [ [Wikipedia](https://en.wikipedia.org/wiki/Palmer_Luckey) ] - Inventor of Oculus Rift.
- Jaron Lanier [ [Wikipedia](https://en.wikipedia.org/wiki/Jaron_Lanier) ] - Father of Virtual Reality.

## Major Players

- HTC
- Google
- Unity
- Sony
- Oculus (acquired by Facebook for $2B in cash in 2014)
- Samsung
- Mozilla
- Sensics [ [Official](http://sensics.com/) | [Wikipedia](https://en.wikipedia.org/wiki/Sensics) ] - Create professional-grade headsets.
- Microsoft

## Media

- CNET
- [ [RoadToVR](https://www.roadtovr.com/) ]
- [ [UploadVR](https://uploadvr.com/) ]

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

## e-Learning

- [Udacity](https://www.udacity.com/courses/all) - has $400 per term nanodegree, but also a free option for some courses
- [Udemy](https://www.udemy.com/courses/search/?q=virtual%20reality) - has many cheap courses, generally $10 - 15 when on sale
- [EdX](https://www.edx.org/professional-certificate/virtual-reality-vr-app-development) - has 3 course VR app development program that is free to take, $267 for certificate option
- [Coursera](https://www.coursera.org/specializations/virtual-reality#courses) - has 5 course VR track, free to take, but need a monthly subscription for the certificate

## Startups

- [StoryUP](http://www.story-up.com/) - Uses VR along with EEG for mindfulness
- [Neurable](http://neurable.com/) - Designs interfaces for using the brain as an input for VR

## Conferences

- [Mixed Reality Developer Conference](http://www.xrdconf.com/)
- [Virtual Reality Developer Conference](http://www.gdconf.com/vrdc/)
- [SIGGRAPH](https://www.siggraph.org/)
- [Oculus Connect](https://www.oculusconnect.com/)


## Movies / Series

- 1982 Tron
- 1992 Lawnmower Man
- 1996 Lawnmower Man 2
- 1999 The Matrix
- 2003 The Matrix Reloaded
- 2003 The Matrix Revolutions
- 2003 Spy Kids 3-D: Game Over
- 2010 Tron Legacy
- 2012 Sword Art Online
- 2013 Log Horizon
- 2018 Ready Player One

## Other Awesome VR Lists

- [Awesome VR](https://github.com/thejourneydude/awesome_vr)
- [Awesome WebVR](https://github.com/wizztjh/awesome-WebVR)
- [Awesome VR UX](https://github.com/mauricesvay/awesome-vr-ux)
- [VR Awesome](https://github.com/Vytek/VR-Awesome)
