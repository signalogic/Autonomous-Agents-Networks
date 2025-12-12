<!-- Slide number: 1 -->
# Autonomous Agents Networks
Akraino Physical AI Blueprint Family, v0.1

![](Picture13.jpg)

![](Picture14.jpg)

![](Picture15.jpg)

<!-- Slide number: 2 -->
# Contents
Overview – Agents, Machines, and Interaction
Motivation
autonomous agents are the next industrial revolution
prioritize communication, collaboration, and human safety
Agent-Agent Interaction
use cases
cloud independent
Human-Agent Interaction
use cases
safety is a primary concern
Key Technologies
P2P communication over cellular and satellite networks
small multimodal models
human interaction - audio and visual
environmental recognition – hazards and dangerous conditions
small form-factors pose performance challenges
Hardware Examples
Software Components
Kaldi or Whisper ASR
OpenCV
Mediashark
small multimodal models – Llama-4, Gemma 3, Qwen2, MiniPCM

![](Picture8.jpg)

![](Picture9.jpg)

![](Picture11.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
2

<!-- Slide number: 3 -->
# Overview – Agents, Machines, and Interaction
“Agents” vs “Machines”
agents imply autonomy, goal-orientation, andability to learn and adapt
AAN is about physical agents
as agents become more flexible, like humansthey will be separate from machines, for examplea car might have a humanoid driver (even if thecar has its own automation)
there is some risk of confusion in using the term“agents”, as “machines” will inevitably becomea popular term
specific use cases may refer to “machines”
“Interaction” includes …
bi-directional communication, feedback
fundamentals of collaboration – situational awareness, reaction, teamwork

![](Picture6.jpg)
Car with humanoid driver, Univ of Tokyo, Kento Kawaharazuka

![](Picture13.jpg)

![](Picture15.jpg)

![](Picture16.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
3

### Notes:

<!-- Slide number: 4 -->
# Motivation
In the next industrial revolution millions of agents must …
collaborate with each other and with humans
operate fully autonomously, with intermittent cloud connectivity when available
expectations of always-available cloud connectivity are unrealistic, expensive, not secure, energy hungry – and most importantly – unsafe
maximize energy efficiency, resilience, flexibility, and adaptability
the correct approach to distributed intelligence, as demonstrated by evolution
Agent teamwork and human safety are top priorities
human safety is the most difficult challenge
open source software, small form-factor hardware, new DNN1 training methods, and 3GPP and IEEE P2P communication standards are emerging areas of innovation
BigAI business models and “incompatible moats” are problematic
they will make less money when intelligence is decentralized
not their top priority
difficult to recruit BigAI contributors to telecom and edge-centricblueprints

![](Picture6.jpg)
4th Industrial Revolution is the 2nd Information Revolution[Surajudeen Abiola Abdulrahman, MD, MHPM, PhD, National Health Service, UK]

![](Picture8.jpg)
1 Deep Neural Network

![](Picture13.jpg)

![](Picture16.jpg)
4th Industrial Revolution includes human interaction with digital devices[Neos Networks, https://neosnetworks.com/resources/blog/what-is-fourth-industrial-revolution-4ir]

![](Picture19.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
4

<!-- Slide number: 5 -->
# Autonomous Agents Networks Blueprint
AAN is a member of the Akraino Physical AI blueprint family
agents are robots, drones, automated vehicles, factory fixed and mobile, environmental sensors
agent-agent and human-agent interaction
cloud independence and human safety are primary objectives
two (2) key underlying technologies are AI and telecom
Initial use cases
Industrial Collaboration
Flood Detection, Prediction, and Rescue
First Responder Machine Assistants

![](Picture8.jpg)

![](Picture9.jpg)

![](Picture11.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
5

<!-- Slide number: 6 -->
# Agent-Agent Interaction

![](Picture2.jpg)

![](Picture7.jpg)
LoRa / HaLow
LoRa / HaLow

![](Picture2.jpg)
Industrial use cases
manufacturing
mobile delivery and roadside (cleaning, driver assistance)
construction
agriculture
P2P (peer-to-peer) communication
between agents
relay via cell and satcom networks
multicast to other agents in close proximity
3GPP C-V2X (+ PC5 sidelink and relay), HaLow802.11ah, LoRa+LoRaWAN, IEEE 802.11x DSRC1
high MHz to mid GHz bands, sometimes known as “mobile WiFi”
short, low-power, codified messages
optional text, and low bitrate audio and video, depending onagent compute capacity

PC5 Relay

![](Picture9.jpg)
PC5 Sidelink

![](Picture5.jpg)

![](Picture4.jpg)
PC5 Relay
1 Dedicated Short Range Communications

![](Picture19.jpg)

![](Picture20.jpg)

![](Picture21.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
6

<!-- Slide number: 7 -->
# Human-Agent Interaction

![](Picture9.jpg)
Use cases
flood prediction, detection, and rescue
first responder machine assistants
proximate machine safety
Audio and visual interaction
small multimodal models
apps supported but not required, we assumeunreliable or unavailable cloud connection
very small form-factor devices (e.g. pico ITX)
background noise, urgent or stressed voiceinput, and background talkers
machine noise from servo motor and othermechanical sources

![](Picture5.jpg)

![](Picture8.jpg)

![](Picture7.jpg)

![](Picture11.jpg)

![](Picture18.jpg)
Drawing excerpt from Amazon delivery drone patent (see Supplemental slides for more information)

![](Picture19.jpg)

![](Picture20.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
7

<!-- Slide number: 8 -->
# Key Technologies

![](Picture6.jpg)
Telecom
P2P communications between agents, relayover cell and satellite networks
short, energy-efficient, machine-readablemessages prioritized by human safety,commercial need, machine failure, etc
AI
small multimodal models, recognizing …
speech
behavior, and gestures
hazards and dangerous conditions

![](Picture9.jpg)

![](Picture11.jpg)

![](Picture13.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
8

<!-- Slide number: 9 -->
# Technology – Architecture Diagram

![](Picture7.jpg)

![](Picture9.jpg)

![](Picture11.jpg)

![](Picture13.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
9

<!-- Slide number: 10 -->
# Technology – Data Flow Diagram

![](Picture6.jpg)

![](Picture9.jpg)

![](Picture11.jpg)

![](Picture13.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
10

<!-- Slide number: 11 -->
# Technology – Messaging
Format and Prioritization
machine readable
optional text, audio, and video
w
Standards
SAE xxx
XXX
yyy
1 Size, weight, and power consumption

![](Picture11.jpg)

![](Picture13.jpg)

![](Picture15.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
11

<!-- Slide number: 12 -->
# Technology Challenges
Severe SWaP 1 constraints
small size, especially in drone and consumer applications
low power consumption, posing a technical challenge for communication and small multimodal models
weight is limited and may have less obvious consequences, for example GPU use may be limited due to heatsink of liquid cooling requirements
Model performance and accuracy
limited number of CPU cores
Data storage
dedicated storage nodes may be required
1 Size, weight, and power consumption

![](Picture11.jpg)

![](Picture13.jpg)

![](Picture15.jpg)
Autonomous Agents Networks blueprint - Not Under NDA
Sep-Dec 2025
12
