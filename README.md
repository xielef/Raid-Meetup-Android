<p align="center">
  <img src="https://raw.githubusercontent.com/Flinesoft/Raid-Meetup-Android/stable/Logo.png"
      width=256 height=256 alt="Raid Meetup">
</p>

<p align="center">
    <a href="https://www.bitrise.io/app/49ceeb364feb9f18">
        <img src="https://www.bitrise.io/app/49ceeb364feb9f18.svg?token=tCgvVSh9D5kD1CUgQCeNAw&branch=stable" alt="Build Status">
    </a>
    <a href="https://codebeat.co/projects/github-com-flinesoft-raid-meetup-android-stable">
        <img src="https://codebeat.co/badges/06071caa-b3da-4ad4-89f1-665a1ad0880d" alt="Codebeat Badge">
    </a>
    <img src="https://img.shields.io/badge/Kotlin-1.1-FFAC45.svg" alt="Kotlin: 1.1">
    <img src="https://img.shields.io/badge/Android_Studio-2.3-4598FF.svg" alt="Android Studio: 2.3">
    <img src="https://img.shields.io/badge/Platforms-Android-FF69B4.svg" alt="Platforms: Android">
    <a href="https://github.com/Flinesoft/Raid-Meetup-Android/blob/stable/LICENSE.md">
				<img src="https://img.shields.io/badge/License-GPL--3.0-lightgrey.svg" alt="License: GPL-3.0">
    </a>
</p>

<p align="center">
    <a href="#mission">Mission</a>
  • <a href="#server">Server</a>
  • <a href="#app-store">App Store</a>
  • <a href="https://community.flinesoft.com/c/raid-meetup">Community Forum</a>
  • <a href="#donate">Donate</a>
  • <a href="#contributing">Contributing</a>
  • <a href="#license">License</a>
</p>


# Raid Meetup

An Android app for meeting up to fight raids together for Pokémon GO players. See [here](https://github.com/Flinesoft/Raid-Meetup-for-Pokemon-GO) for the iOS counterpart.


## Mission

Our goal is to provide a way to meet up for raids in Pokémon GO in a way that is **safe** and **transparent**. Also this projects is **open source** and currently is and always will stay **ad-free** ([donations](#donate) are welcome).

### Safety

We think one of the reasons Niantic has not included such a feature like this app provides right within the Pokémon GO app is due to the potential of safety problems for players. This is why we are taking safety seriously. Here's how we plan to tackle the safety problem:

- We do **not** provide **an open chat**, instead players can only communicate with **pre-defined actions**. Possible actions:
  - Providing Data: "There's a raid of level 2 at this location beginning at 3:21 PM."
  - Joining a Raid: "I would join this raid if there were at least 3 other people"
- We are going to collect and provide **reliability information** about users and raids. Possible actions:
  - Reporting Users: "This user did show up" / "This user did not show up"
  - Reporting Raids: "I can confirm this raid" / "There is no such raid"

- We plan to require Sign In via Google sometime in the future (see [forum entry](https://community.flinesoft.com/t/require-log-in-via-google-account/40/1))
- We plan to investigate if we can directly use the Pokémon GO APIs to validate users by fetching their in-game profile
  - there's [this](https://github.com/lsapan/pgoapi-swift) and [that](https://github.com/AgentFeeble/pgoapi) API library written in Swift which might help us to do this


For more information, checkout our [FAQ section](https://community.flinesoft.com/c/raid-meetup/questions) on our Community Forum.


## Server

To provide this service, we need to have a **server** as a backend which saves all the data provided by our users, including the positions and times of Raid Fights and the players who plan to attend them. The server part of this project has a **documented and open API** mainly to allow volunteer developers to write a similar app for Android as well. Of course the server part is open source, too. It is written in Ruby on Rails, an open-source, modern and secure backend framework with a big community.

You can find the server part of this project here:
[https://github.com/Flinesoft/Raid-Meetup-Server](https://github.com/Flinesoft/Raid-Meetup-Server)


## App Store

Here you can find the app on the Google Play Store:

TODO: Add link once app is uploaded to Play Store


## Donate

Hello, my name is Cihat Gündüz and I'm the maintainer and main developer of this project. I'm doing all the hard work in **my free time**, and I'm not earning any money from this software, as it is a **free download** on the App Store and **doesn't contain ads**. I'd like to keep it that way cause I don't like ads (who does?). I'm even losing money since I have to **pay the servers** required to get this app working across multiple users.

So, if you like this app and want to **motivate me to maintain and improve it** over time, even a small donation will definitely help me out! I'm thankful for your help.

<a href="https://www.paypal.me/Dschee">
    <img src="https://img.shields.io/badge/Donate-PayPal-green.svg" alt="Donate via PayPal">
</a>


## Contributing

Contributions are welcome. We do have a [**Community Forum**](https://community.flinesoft.com/c/raid-meetup) where you can discuss and exchange ideas about this project. Feel free to post your ideas there or implement an idea yourself and post a pull request – there's a [voted list](https://community.flinesoft.com/c/prayer-app/ideas) of feature requests, and there's also a [list of bugs](https://community.flinesoft.com/c/raid-meetup/bugs) for you to get started.

If you want to contribute code, please try to follow the same syntax and semantic in your **commit messages** (see rationale [here](http://chris.beams.io/posts/git-commit/)).

## License

This project is released under the [GNU General Public License, version 3 (GPL-3.0)](http://opensource.org/licenses/GPL-3.0).
