# Summary about usability testing and mobile UX

## Used resources
Articles:

- Mobile User Experience: Limitations and Strengths ([https://www.nngroup.com/articles/mobile-ux/](https://www.nngroup.com/articles/mobile-ux/))
- Feature Fake: Exploring and Testing Connected Mobile Prototypes ([http://uxpamagazine.org/feature-fake](http://uxpamagazine.org/feature-fake/))
- Usability Testing for Mobile is Easy ([https://www.nngroup.com/articles/mobile-usability-testing/](https://www.nngroup.com/articles/mobile-usability-testing/))
- When to Use Which User-Experience Research Method ([https://www.nngroup.com/articles/which-ux-research-methods/](https://www.nngroup.com/articles/which-ux-research-methods/))
- Mouse vs Fingers ([https://www.nngroup.com/articles/mouse-vs-fingers-input-device/](https://www.nngroup.com/articles/mouse-vs-fingers-input-device/))
- User Interface for Mobile Content ([http://ieeexplore.ieee.org.ieeexploredigitallibrary.han.technikum-wien.at/stamp/stamp.jsp?tp=&arnumber=1621006](http://ieeexplore.ieee.org.ieeexploredigitallibrary.han.technikum-wien.at/stamp/stamp.jsp?tp=&arnumber=1621006))
- Side information: https://www.nngroup.com/articles/interaction-cost-definition/

---

Papers:

- User Experience in Mobile Application Development: Developer and End-user Perceptions ([http://tampub.uta.fi/bitstream/handle/10024/82680/gradu05184.pdf;sequence=1](http://tampub.uta.fi/bitstream/handle/10024/82680/gradu05184.pdf;sequence=1))

## Usability testing methods: when to use which one of them
*Attitudinal- and behavioral* (what people say/what people do) dimension:

- behavioral- and attitudinal dimension:
- **attitudinal** (self reported) methods bring **insight of users' mental model** of an information space
	- **card sorting** to get best information architecture
	- **surveys** to measure an categorize attitudes and to discover issues
	- **focus groups** to get a top-of-mind view of what peope think about a concept
- **behavioral** methods focus on **"what people do"** with a product
	- **A/B testing** to see effects of different designs
	- **eyetracking** to understand users' interaction with an interface
- field- and usability studies are in between (mixture of self-reported data and behavioral observations)

*Qualitative- and quantitative* dimension:

- **qualitative studies** to generate data about behaviors or attitudes **based on observations (directly)**
- qualitative studies to answer questions about **"why" and "how to fix"**
- qualitative studies are **interviews and field studies**
- **quantitative studies** to generate data about behaviors or attitudes **based on measurements (indirectly)**
- quantitative studies to answer questions about **"how many" and "how much"**
- quantitative studies are **clickstream analysis and surveys**

*Context of product use* dimension:

- **natural** use --> ethnographic field studies, data mining
- **scripted** use --> benchmarking study
- **not using** --> to examine issues that are broader than usability, such as study of the brand
- **hybrid** use --> participatory design

*Time dimension*:

- at the beginning (**to explore and choose new directions**) use **qualitative and quantitative** studies (field studies, data mining and analytics)
- during the design phase use mainly **(formative) qualitative studies** (field statues, paper prototypes) to decide upon go/no-go situations
- to improve the product over time (measure performance) use **(summative) quantitative studies** (A/B testing, online assemssment)

## Mobile UX: properties and their impact on mobile UX
- *Screen size*: screen size is limited on a mobile device --> **content and feature prioritization**!
- *Portable*: portable devices are often used in a context where interruption can happen --> attention on mobile is fragmented and sessions on mobile devices are short (72 seconds on mobile vs. 150 seconds on desktop) --> **design for interruptions**! meaning the following
	- save context to make resuming an interrupted task easier
	- allow users to share information via different channels (email, social media)
	- simplify tasks and interactions (no walls of details)
- *Single window*: users see only a single window --> tasks should be easy to complete in **a single app/website**! therefore: keep the app/website self-sufficient to reduce complexity and make it less error prone
- *Touchscreen*: use available input technologies:
	- **gestures**: can make interaction more efficient and save screen space, but suffer from discoverability
	- **typing**:
		- users need to pay attention to what they are typing and the content that they were typing
		- touch keypads have small keys and are crowded (compared to a physical keybaord)
		- accidental touches can leave the user disoriented and unsure
- *Variable connectivity*: mind the waiting time --> **connectivity and network coverage can vary**! design pages that are light and minimize the number of steps/page loads
- *Sensors and features*: mobile devices come with a vary of sensors and features (compared to a desktop) --> **make use of them**! e.g.:
	- GPS for geographical information
	- Camera and voice for recording
	- Fingerprint sensors for authentification
	- NFC for communication

Conclusion: Mobile devices come with limitations and strengths that both need to be considered during the design phase of an application/website.

## Feature faking to test connected mobile prototypes
Mobile devices come with connected technologies like sensors, NFC and beacons --> **prototypes need to represent the intended user experience as realistically as possible**!

Kowing the **user journey** and creating a **authentic prototype** are both equally important. Delivering a fully functional product at an early stage is not possible, but the **core functions** of a product need to be represented. Prototyping is **not about the quality of how a digital product's technical features** would work, **but about the user experience**!

Examples of 'feature fakes':

- *Sensors*: prototyping tools cannot acces onboard sensors
	- Camera: use an animated gif or video
	- Bluetooth: imitate connection by using "talk-aloud" technique and an other device (e.g. HTML5 prototype)
- *Touchscreen*: use a smartphone instead
- *Smartwatches*: imitate vibration notifications with a second wrist device

Conclusion: In comparison to desktop PCs, mobile devices offer a variety of **sensors that cannot be easily accessed for prototyping**. Instead, **use "workarounds"** to imitate the desired behaviour to enhance the user experience during testing.

## Setup of an mobile usability testing session (vs. desktop)
- Recording with an **external camera** (document camera or webcam) over a screen-recording solution on mobile.
- Project the **recordings from the mobile device to an external desktop PC** to follow the participant's actions and to record them.
- Decrease glare (from light sources) to a minimum to not influence the quality of the recording.
- Good cellular signal and high-speed wireless network should be available (test mobile apps on both, because cellular connectivity usually is slower than WiFi).

Conclusion: Mobile UX testing requires an extended setup of an environment, meaning the recording, light sources and network connectivity. Selecting the right users and evaluating the test sessions is similar to desktop testing. Check if context is needed to decide whether lab- or field-testing is appropriate!

## Mouse vs. fingers: input devices in comparison
- *Precision*: fingers have low precision --> **bigger buttons** on mobile- than in desktop applications!
- *Number of controls and signal states*: a **mouse provides more controls** (left, middle, right mouse button) **and signal states** (hover, down, up) than fingers can do for mobile (multi touch, finger down and -up) --> keep the **control actions simple**!
- *Pointer/Cursor*: is visible on desktop --> **analyse pointer movement**
- *Learning and engagement*: no learning time and high engagement with screen on mobile

Conclusion: There is **no single winner**! **Emphasize the strengths** of the available inputs when designing a user interface.

## User Interfaces for Mobile Content
Mobility contraints:

- technology-related
	- communications-related (higher noise, relatively lower bandwiths)
	- device-related (smaller display size, smaller-sized buttons)
- user-related (limited attention spans, changing locations)

User interface design must address two distinct purposes: **content production and -consumption**.
Content production tools to process resources from **integrated sensors** (camera, voice).
Content consumption on multiple levels (level of detail, presentation quality and -style).
**Certain actions** (query for content, request content, provide feedback, setting user preferences) should be **"key-stroke optimized"**!
Treat **mobile phones as personal devices** --> make as much as possible **customizable**!

Conclusion: Users expect **consistency**, **ease of discovery**, **seamless processing** and **transfer of content**!

## Side information: interaction cost as an indicator for UX
Interaction cost is the **sum of efforts** that users must deploy in interacting with an application **to reach their goal**. Usable sites **minimize the interaction cost** to a minimum! Actions that increase interaction cost are reading, scrolling, looking around in order to find information, clicking/touching/typing, page loads, memory load and attention switches. Relative **importance depends on the user** (dyslexia or motor impairments). The usability heuristics target to keep the interaction cost low!

## User Experience in Mobile Application Development (what is not mentioned above already)
- **field testing vs. lab testing**
	- "field testing is only justifiable to understand the user's contextual behaviour"
	- "lab testing is useless because of missing context"
	- Nielsen: "field testing to discover **problems that lab testing can not surface**"
- UX of native applications is much bettern than their web based counterparts, because they are **tailored to a specific platform**
- follow general- and platform **guidelines to provide a constistent design**
- Apple suggests to start with paper sketches and -prototyping
- Xcode provides a drag-and-drop UI editor; developers can learn how certain controls behave and what they look like
- first do **design research (personas), then conceptual design (sketches and stories) and prototyping (consistency)**
- use mock-up tools and web templates to kick off with a prototype faster
- do an **expert review** to remove major UX problems, then run **user testing** to find contextual problems
- consider **integration of social networks and cellular network infrastructure/connectivity** when designing/testing

Conclusion: **Field- and lab-testing should both be performed** (lab-testing is a minimum). Consider developing a **platform native application over a mobile website** and to work based on the **platform guidelines** to provide consistent design/flow. Design **research and conceptual design before implementation** tasks; prototyping to discover the users' experience.