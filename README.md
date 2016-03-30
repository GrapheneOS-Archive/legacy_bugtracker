## Welcome to CopperheadOS

This is the bug tracker for both [CopperheadOS](https://copperhead.co/android/) and the
https://copperhead.co/ website. The source code for the operating system is kept under the
[CopperheadOS organization](https://github.com/copperheados).

## Guidelines
Any issue opened that does not follow these guidelines
will be closed. Redundant and out-of-scope issues drain our resources
which would be better allocated towards CopperheadOS.

# Building

Follow the steps detailed [here](https://copperhead.co/android/docs/building)

# Contribution

Thank you for your interest in helping support the CopperheadOS project. Our goal with this project is to secure everyday communications utilizing the Android OS and we thrive to be in sync with our community. We're
always looking to receive valid and descriptive bug reports to continue to secure Android. More importantly, we're eager to get people on our team to help us continue our vision: [Apply!](mailto:team@copperhead.co)

## Feature Requests

As the CopperheadOS project continues to grow, we find more and more users are requesting features as part of our solution. While helpful, if you're looking to request a feature please ensure
that the [feature hasn't already been planned](https://github.com/copperhead/bugtracker/labels/enhancement). Redundant feature requests only slow things down! Most importantly if you're capable of implementing
this feature in our OS [please let us know!](mailto:team@copperhead.co)

##<a name="Porting">Porting To Other Devices/Operating Systems</a>

CopperheadOS is tuned to **work on Nexus devices only** and
there are no plans to expand device support beyond the Nexus line.
If someone is interested in porting CopperheadOS to a device, they are free to do so however
it will not have official Copperhead support. We do not have the resources to cover multiple source trees.

## Reporting issues

To keep our bug tracker progressing in the right direction, utilize the following steps before reporting a bug:

* Has the [bug been reported already](https://github.com/copperhead/bugtracker/search?utf8=%E2%9C%93&q=relevant+bug&type=Code)?
* Keep each issue to **one** bug report.
* Is your issue an [Android issue](https://code.google.com/p/android/issues/list)?
* Is this a bug relevant with the project?
* Do you have the [required information](#Debugging) to help us process the bug?
* Are you able to help squash this bug? If so, please inform us!
* Are you running the [current version of CopperheadOS](https://copperhead.co/android/downloads)?

##<a name="Debugging">Debugging</a>

To get an idea of what caused the bug, please ensure you report to us the following information while issuing a bug:
* Steps To Reproduce The Bug
* CopperheadOS version (Settings -> About Phone)
* Device Model
* [ADB Logcat dumps](https://f-droid.org/wiki/page/Getting_logcat_messages_after_crash)
