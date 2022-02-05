# Preface
The software was developed with the support of the Barnaul bus station in 2022 in the form of a course project by 2nd-year students of the Faculty of Information Technology of the PI-03 group.

In Russian: https://github.com/Rol225/Dispatcher-s-Terminal/blob/main/README_RU.md

# Dispatcher-s-Terminal
Nowadays it is difficult to imagine a modern air-, auto-, railway- station without public address systems for various purposes. These are passenger information systems and alerts inside or from the outside of train stations.

Now in almost every city, at any train station, you can see electronic LED displays and digital panel monitors that provide passengers with the necessary information. The main advantage of such systems is the rapid change of information at any time of the day. On the LED display boards, reference information is offered, in the form of a table - about the schedule of planes, trains, indicating flight numbers, arrival and departure times, etc. In waiting rooms, the LED scoreboard is usually large and displays not only the transport schedule, but also the nearest arrival or departure, as well as the direction and exit to the terminal or to the corresponding platform.

All electronic displays and handsfree devices are included in one system, which is controlled via a computer, using a server and special programs. The information is entered by the operators-cashiers and the station dispatcher. Transport infrastructure facilities serve a large number of passengers every day, a significant part of which is concentrated on relatively small areas. To properly inform such a large number of people, a convenient, flexible and fault-tolerant system is needed.
# Software of the passenger notification system of transport infrastructure facilities using visual, audio and individual communication channels.
![](https://sun9-87.userapi.com/impg/DmRVv9Kw85QYx_gYwY4PiKOQiMvYZ0xSWuI3wQ/efMf5Fa2eOo.jpg?size=1920x996&quality=96&sign=9185dd003480cf7ac11a7aa9ed7a2d24&type=album)
This repository is a software dispatcher terminal, which is a desktop application installed on a Windows PC, and is a client application, implementing the following functions:
<ul>
  <li>A software microphone console that allows you to selectively transmit voice messages to one or more notification zones pre-configured on the server.</li>
  <li>A software visual console that allows you to selectively transmit visual information to one or more alert zones pre-configured on the server.</li>
  <li>A software telephone console that allows you to selectively transmit voice and text messages to any type of phones.</li>
  <li>A software Email console that allows you to selectively transmit audio, video, and text messages.</li>
  <li>Convenient management of audio-video information, with the ability to create publication plans for certain devices with subsequent editing of the plan.</li>
  <li>Automatic and manual verification of incoming information.</li>
</ul>

It is necessary to take into account that the user will work with the dispatcher terminal for a long time without interruptions, therefore it is necessary to reduce the visual load – to make the interface understandable, not overloaded, with a soft color scheme, where there is an emphasis on important interface details.

Since it is impossible to create a single user-friendly interface for all users, it was decided to provide end users with the ability to edit application styles. This allows you to create the most comfortable working environment for the end user and increase the profitability of the system.

To implement the client part in the WebStorm development environment, a stack of web technologies was selected, namely:
<ul>
  <li>Html 5</li>
  <li>CSS 3</li>
  <li>JavaScript (ECMAScript 6)</li>
  <li>TypeScript</li>
  <li>Node JS</li>
  <li>Chromium</li>
  <li>Electron</li>
  <li>React js</li>
</ul>

A local Chromium local storage cache was used to save user settings.

# Layout
The interface layout was developed in the Company, link: https://www.figma.com/file/GajbrYCreXQVPObTAROUnH/%D0%A2%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D0%B0%D0%BB-%D0%B4%D0%B8%D1%81%D0%BF%D0%B5%D1%82%D1%87%D0%B5%D1%80%D0%B0?node-id=0%3A1

Application layout in code, link: https://github.com/Rol225/Dispatcher-Terminal-layout
