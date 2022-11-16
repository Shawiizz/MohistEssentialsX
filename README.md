# About the PSA written by EssentialsX

Why EssentialsX's PSA about Mohist shouldn't be trusted.

Before reading:
- I don't natively speak English, so this article may contain spelling errors, I'm sorry for that.
- A few months ago, the EssentialsX plugin was [properly fixed](https://github.com/MohistMC/Mohist/commit/fa50a83b2ec107e78f000a130200b663cf234fe4#diff-0d24b179f56b3af28027a28dba50d851448d3ed889a6ca8b6d1a06c2e8576d35) into Mohist and the modified plugin isn't needed anymore.
- EssentialsX original page: https://essentialsx.net/do-not-use-mohist.html
- Mohist's organization: https://github.com/MohistMC
- "we" and "us" = The Mohist project or Mohist team.
- I'm writing this as a Mohist admin.
- Grammar assistance by [Soapy7261](https://github.com/Soapy7261)

## Context
Mohist is a Forge + Bukkit/Spigot/Paper hybrid which allows you to run mods and plugins at the same time. This software is currently in beta and may contain bugs.
This README has been written to correct errors and misinformation disseminated in that PSA. Everything that is said in this README is proven and can be verified by yourself if you wish.

Know that you're free to not use or not support Mohist. This README just explains the errors made on the EssentialsX page.

## Explanations
### Let's start
![image](https://user-images.githubusercontent.com/55449195/126685207-078a4223-b8b1-461f-a67a-3050e280ebb4.png)

Yes, Mohist can replace **with your permission** the EssentialsX plugin with a modified one made by us to **temporarily** fix an incompatibility between EssentialsX and Mohist **until** we find a proper way to fix it on our side.
This modified plugin allows users to use EssentialsX on Mohist without incompatibilities. Also, this modified plugin source code is available [on Github](https://github.com/KR33PY/Essentials) <ins>**and it has always been the case**</ins>. Plus, **you're free to check its source code** and what has been modified in the code, by looking at the [commits](https://github.com/KR33PY/Essentials/commits/2.x). Note: The repository has been marked as archived, but it still contains the modified code so that you can check it if needed.

### Bukkit and Forge compatibility
![image](https://user-images.githubusercontent.com/55449195/126694413-da51f826-108f-4ee9-9296-0b11aa9755ef.png)
Yes, Bukkit and Forge aren't made to be compatible, but the aim of Mohist is to resolve this incompatibility with as few bugs as possible. Of course, it's **not possible** to make a Forge + Bukkit software without any bugs, and it's very hard to create hybrid server software as there is no way to properly implement the Bukkit API on top of Forge without modifying it. Also, know that we do our best to make Mohist a stable, bug-free, and cleanly coded software.

### Mohist potential issues
![image](https://user-images.githubusercontent.com/55449195/126695195-0348d93f-a243-48cf-88f9-2bc14187c2ca.png)
The first issue _(Injecting block/item types added by Forge into the Bukkit Material enum twice)_ doesn't exist anymore and has been fixed since the creation of Mohist 1.16.5.

The second issue exists, and <ins>**it's how Forge works**</ins>. Forge re-creates the player instance when a player dies and it's hard to change that without breaking Forge mods compatibility. But again, we are doing our best to think about a way to patch this problem without breaking mod compatibility. Of course, this issue can break some plugin compatibility, but keep in mind that Mohist is **based on Forge** and not Bukkit.

### Plugin checker
The Mohist's plugin checker has been made to **temporarily** fix a plugin which doesn't work well with Mohist until we find a proper way to fix it.
Of course, it **always asks for your permission <ins>(and this has always been the case since its creation)</ins>** before downloading a modified plugin.

![image](https://user-images.githubusercontent.com/55449195/126695944-f175c64f-b455-459b-a0b4-dac5c5f9704f.png)
![image](https://user-images.githubusercontent.com/55449195/126696216-e03e5e1f-ed7a-4b69-9081-172de451a3c5.png)

We now know it, this text was not clear and we are sorry for that, it was not our intention. As you may know, our team does not contain any native English speakers, so it is **difficult** for us to write clear messages, even though we make every effort to make it as clear as possible to everyone. Fortunately, our community has been able to help us correct this problem.

Actually, this text doesn't mean the bug comes from EssentialsX. It means the plugin cannot work due to an incompatibility **on Mohist's side** and **ask the user** if he allows the Mohist software to download a modified version of this plugin (temporarily) to make it work fine with Mohist, <ins>and I insist on the fact that it requires the user's agreement and that it has always been the case</ins>. **Also EssentialsX is properly fixed in Mohist and doesn't need the modified plugin anymore for a long time**.

Secondly, Mohist **never** run any untrusted code as the code of modified plugins is always published on GitHub and **shows** what has been modified in the plugin's code. That message actually misses some information, like the repository URL, what has been changed and fixed, etc., and it has been [fixed there](https://github.com/MohistMC/Mohist/commit/04270a57b30f5de902409b524ad682c790c70657). This is explained in our Discord server, but not everyone can go to our Discord server and we solved this problem by adding more details to that message, and we hope it is now clearer for everyone.

Plus, know that **we never and will never use this plugin checker to download anything malicious**. You are **free to check what is downloaded** with the plugin checker as [**Mohist is free and open source on GitHub**](https://github.com/MohistMC/Mohist/), fixed plugins source code is always published in GitHub and you can also **decide** if you want to download the modified plugin or not. And to finish, <ins>**you can even disable the plugin checker**</ins> by setting `disable_plugins_blacklist` to `true` in mohist-config/mohist.yml.

### More explanations
![image](https://user-images.githubusercontent.com/55449195/126698711-2f595546-3d1b-4f9c-9102-944b0144b5df.png)

To conclude this README, making Forge and Bukkit API work together is really difficult and today no one achieved to do it without any bugs. The EssentialsX team doesn't know how hard is it to code a hybrid software, and we understand it.

But we also have a few things to say about EssentialsX and its team. They're often saying that we did things wrong and did not make any effort, but on their side, they did not make any effort either. Instead of coming to discuss with the Mohist team **as any other team would have done** as civilized people, they decided to try to destroy the reputation of our software, which is totally **shameful** and shows a deep lack of communication on their part. Not only does their PSA spread false ideas and information, but it is also a lie to their community, which poses a trust issue with their team.
Moreover, their reasons for hating hybrids are not very well thought out. Yes, Forge and Bukkit are not made to work properly, but if we don't try to solve this problem, who will?
We also know there are good people on their team, but unfortunately, the behaviour of some of them was not as we would have liked.

Again, we are really sorry if the plugin checker's message couldn't be understood correctly, and we hope this README will make everything clearer for everyone. Furthermore, even after these events, we have never and will never prevent users from using EssentialsX, as it is not our intention to do so. To finish with this article, know that <ins>**we always care about the security of our users**</ins> and that it's an important thing for us and <ins>**above all our priority.**</ins>
