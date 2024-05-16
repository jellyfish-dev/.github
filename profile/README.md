Hi Everyone! 

We are thrilled to announce that **Jellyfish Server** has been rebranded as **Fishjam Server**, effective from **May 16th, 2024**! 

You can find the new GitHub organization [here](https://github.com/fishjam-dev).

The main impetus behind our rebranding has been to eliminate any confusion between us and other products operating in the same space. A fresh start is needed, particularly as we plan to roll out new updates in the Fishjam space, specifically concerning the launch of a SaaS platform. This platform will allow customers to easily set up our multimedia server, leverage our SDKs to build a WebRTC-based product without the hassle of managing and owning the underlying multimedia infrastructure.

To help our community navigate this transition period, we've prepared a brief **FAQ** (see below) . If anything remains unclear, please don't hesitate to reach out!


**FAQ**

**Q1: What is the exact timeline of this change and what steps are you going to take?**

On May 16th, during the AM hours CEST, we will rename the Jellyfish-dev organization which will render the old links unusable. On the same day, we will rename the repositories affected by the rebranding; however, thanks to GitHub handling the redirects, old links should still work. We will also update the package managers where we publish our packages. In the following weeks, we plan to update our codebase to remove the old Jellyfish references. We will keep you posted on the progress.

**Q2: I have forked/cloned a Jellyfish repository. How does this change affect me?**

No action is required on your part. GitHub will automatically handle everything.

**Q3: I am using Jellyfish Elixir/Python/JS SDK. How does this change affect me?**

There are two possible scenarios here: a) If you downloaded a package from the respective package manager (HEX, PyPi, NPM), the only impact is the change of the package name, i.e., jellyfish-server-sdk becomes fishjam-server-sdk. b) If you are directly referencing the SDK repository in your code,  it will be for the best to update the repository URL.

**Q4: I am using the Jellyfish client SDK (iOS, Android, React, React Native). How does this change affect me?**

The only change here is the namespace on the respective package manager, i.e., instead of @jellyfish-dev, it will be @fishjam-dev.

**Q5: I am using Jellyfish docker image. How does this change affect me?**

Old github container registry links will stop working. Instead of pulling from `ghcr.io/jellyfish-dev` , pull from `ghcr.io/fishjam-dev`. <br /> 
For example: `docker pull ghcr.io/jellyfish-dev/jellyfish:0.5.0` -> `docker pull ghcr.io/fishjam-dev/jellyfish:0.5.0`. <br />
Version 0.5.0 is the last version named `jellyfish`. Starting from version 0.6.0, docker image will be named `fishjam`.
