<!-- markdownlint-disable MD025 -->
# Threat Modeling

Balancing security, privacy, and usability is one of the first and most difficult tasks you'll face on your privacy journey. Everything is a trade-off: The more secure something is, the more restricting or inconvenient it generally is, etc. Often, people find that the problem with the tools they see recommended is that they're just too hard to start using!

If you wanted to use the  **most**  secure tools available, you'd have to sacrifice  *a lot*  of usability. And, even then,  nothing is ever fully secure.  There's  **high**  security, but never  **full**  security. That's why threat models are important.

**So, what are these threat models, anyway?**

A threat model is a list of the most probable threats to your security and privacy endeavors.  Since it's impossible to protect yourself against  **every**  attack(er), you should focus on the  **most probable**  threats. In computer security, a threat is an event that could undermine your efforts to stay private and secure.

Focusing on the threats that matter to you narrows down your thinking about the protection you need, so you can choose the tools that are right for the job.

## Creating Your Threat Model

To identify what could happen to the things you value and determine from whom you need to protect them, you should answer these five questions:

1. What do I want to protect?
2. Who do I want to protect it from?
3. How likely is it that I will need to protect it?
4. How bad are the consequences if I fail?
5. How much trouble am I willing to go through to try to prevent potential consequences?

### What do I want to protect?

An “asset” is something you value and want to protect. In the context of digital security,  an asset is usually some kind of information.  For example, your emails, contact lists, instant messages, location, and files are all possible assets. Your devices themselves may also be assets.

*Make a list of your assets: data that you keep, where it's kept, who has access to it, and what stops others from accessing it.*

### Who do I want to protect it from?

To answer this question, it's important to identify who might want to target you or your information.  A person or entity that poses a threat to your assets is an “adversary”.  Examples of potential adversaries are your boss, your former partner, your business competition, your government, or a hacker on a public network.

*Make a list of your adversaries or those who might want to get ahold of your assets. Your list may include individuals, a government agency, or corporations.*

Depending on who your adversaries are, under some circumstances, this list might be something you want to destroy after you're done security planning.

### How likely is it that I will need to protect it?

Risk is the likelihood that a particular threat against a particular asset will actually occur.  It goes hand-in-hand with capability. While your mobile phone provider has the capability to access all of your data, the risk of them posting your private data online to harm your reputation is low.

It is important to distinguish between what might happen and the probability it may happen. For instance, there is a threat that your building might collapse, but the risk of this happening is far greater in San Francisco (where earthquakes are common) than in Stockholm (where they are not).

Assessing risks is both a personal and subjective process. Many people find certain threats unacceptable, no matter the likelihood they will occur, because the mere presence of the threat is not worth the cost. In other cases, people disregard high risks because they don't view the threat as a problem.

*Write down which threats you are going to take seriously, and which may be too rare or too harmless (or too difficult to combat) to worry about.*

### How bad are the consequences if I fail?

There are many ways that an adversary could gain access to your data. For example, an adversary can read your private communications as they pass through the network, or they can delete or corrupt your data.

The motives of adversaries differ widely, as do their tactics.  A government trying to prevent the spread of a video showing police violence may be content to simply delete or reduce the availability of that video. In contrast, a political opponent may wish to gain access to secret content and publish that content without you knowing.

Security planning involves understanding how bad the consequences could be if an adversary successfully gains access to one of your assets. To determine this, you should consider the capability of your adversary. For example, your mobile phone provider has access to all of your phone records. A hacker on an open Wi-Fi network can access your unencrypted communications. Your government might have stronger capabilities.

*Write down what your adversary might want to do with your private data.*

### How much trouble am I willing to go through to try to prevent potential consequences?

There is no perfect option for security.  Not everyone has the same priorities, concerns, or access to resources. Your risk assessment will allow you to plan the right strategy for you, balancing convenience, cost, and privacy.

For example, an attorney representing a client in a national security case may be willing to go to greater lengths to protect communications about that case, such as using encrypted email, than a mother who regularly emails her daughter funny cat videos.

*Write down what options you have available to you to help mitigate your unique threats. Note if you have any financial constraints, technical constraints, or social constraints.*

### Try it yourself: Protecting Your Belongings

These questions can apply to a wide variety of situations, online and offline. As a generic demonstration of how these questions work, let's build a plan to keep your house and possessions safe.

**What do you want to protect? (Or,  *what do you have that is worth protecting?*)**

Your assets might include jewelry, electronics, important documents, or photos.

**Who do you want to protect it from?**

Your adversaries might include burglars, roommates, or guests.

**How likely is it that you will need to protect it?**

Does your neighborhood have a history of burglaries? How trustworthy are your roommates or guests? What are the capabilities of your adversaries? What are the risks you should consider?

**How bad are the consequences if you fail?**

Do you have anything in your house that you cannot replace? Do you have the time or money to replace those things? Do you have insurance that covers goods stolen from your home?

**How much trouble are you willing to go through to prevent these consequences?**

Are you willing to buy a safe for sensitive documents? Can you afford to buy a high-quality lock? Do you have time to open a security box at your local bank and keep your valuables there?

Only once you have asked yourself these questions will you be in a position to assess what measures to take. If your possessions are valuable, but the probability of a break-in is low, then you may not want to invest too much money in a lock. But, if the probability of a break-in is high, you'll want to get the best lock on the market and consider adding a security system.

Making a security plan will help you to understand the threats that are unique to you and to evaluate your assets, your adversaries, and your adversaries' capabilities, along with the likelihood of risks you face.

## Further Reading

For people looking to increase their privacy and security online, we've compiled a list of common threats our visitors face or goals our visitors have, to give you some inspiration and demonstrate the basis of our recommendations.

- [Common Goals and Threats](https://www.privacyguides.org/basics/common-threats/)

## Sources

- [EFF Surveillance Self Defense: Your Security Plan](https://ssd.eff.org/en/module/your-security-plan)

---

# Common Threats

Broadly speaking, we categorize our recommendations into the  [threats](https://www.privacyguides.org/basics/threat-modeling/)  or goals that apply to most people.  You may be concerned with none, one, a few, or all of these possibilities, and the tools and services you use depend on what your goals are. You may have specific threats outside of these categories as well, which is perfectly fine! The important part is developing an understanding of the benefits and shortcomings of the tools you choose to use, because virtually none of them will protect you from every threat.

- Anonymity  - Shielding your online activity from your real identity, protecting you from people who are trying to uncover  *your*  identity specifically.
- Targeted Attacks  - Being protected from hackers or other malicious actors who are trying to gain access to  *your*  data or devices specifically.
- Passive Attacks  - Being protected from things like malware, data breaches, and other attacks that are made against many people at once.
- Service Providers  - Protecting your data from service providers (e.g. with  E2EE, which renders your data unreadable to the server).
- Mass Surveillance  - Protection from government agencies, organizations, websites, and services which work together to track your activities.
- Surveillance Capitalism  - Protecting yourself from big advertising networks, like Google and Facebook, as well as a myriad of other third-party data collectors.
- Public Exposure  - Limiting the information about you that is accessible online—to search engines or the general public.
- Censorship  - Avoiding censored access to information or being censored yourself when speaking online.

Some of these threats may be more important to you than others, depending on your specific concerns. For example, a software developer with access to valuable or critical data may be primarily concerned with  Targeted Attacks, but they probably still want to protect their personal data from being swept up in  Mass Surveillance  programs. Similarly, many people may be primarily concerned with  Public Exposure  of their personal data, but they should still be wary of security-focused issues, such as  Passive Attacks—like malware affecting their devices.

## Anonymity vs. Privacy

Anonymity

Anonymity is often confused with privacy, but they're distinct concepts. While privacy is a set of choices you make about how your data is used and shared, anonymity is the complete disassociation of your online activities from your real identity.

Whistleblowers and journalists, for example, can have a much more extreme threat model which requires total anonymity. That's not only hiding what they do, what data they have, and not getting hacked by malicious actors or governments, but also hiding who they are entirely. They will often sacrifice any kind of convenience if it means protecting their anonymity, privacy, or security, because their lives could depend on it. Most people don't need to go so far.

## Security and Privacy

Passive Attacks

Security and privacy are also often confused, because you need security to obtain any semblance of privacy: Using tools—even if they're private by design—is futile if they could be easily exploited by attackers who later release your data. However, the inverse isn't necessarily true: The most secure service in the world  *isn't necessarily*  private. The best example of this is trusting data to Google who, given their scale, have had few security incidents by employing industry-leading security experts to secure their infrastructure. Even though Google provides very secure services, very few people would consider their data private in Google's free consumer products (Gmail, YouTube, etc.)

When it comes to application security, we generally don't (and sometimes can't) know if the software we use is malicious, or might one day become malicious. Even with the most trustworthy developers, there's generally no guarantee that their software doesn't have a serious vulnerability that could later be exploited.

To minimize the damage that a malicious piece of software  *could*  do, you should employ security by compartmentalization. For example, this could come in the form of using different computers for different jobs, using virtual machines to separate different groups of related applications, or using a secure operating system with a strong focus on application sandboxing and mandatory access control.

Tip

Mobile operating systems generally have better application sandboxing than desktop operating systems: Apps can't obtain root access, and require permission for access to system resources.

Desktop operating systems generally lag behind on proper sandboxing. ChromeOS has similar sandboxing capabilities to Android, and macOS has full system permission control (and developers can opt-in to sandboxing for applications). However, these operating systems do transmit identifying information to their respective  OEMs. Linux tends to not submit information to system vendors, but it has poor protection against exploits and malicious apps. This can be mitigated somewhat with specialized distributions which make significant use of virtual machines or containers, such as  [Qubes  OS](https://www.privacyguides.org/desktop/#qubes-os).

Targeted Attacks

Targeted attacks against a specific person are more problematic to deal with. Common attacks include sending malicious documents via email, exploiting vulnerabilities (e.g. in browsers and operating systems), and physical attacks. If this is a concern for you, you should employ more advanced threat mitigation strategies.

Tip

By design,  **web browsers**,  **email clients**, and  **office applications**  typically run untrusted code, sent to you from third parties. Running multiple virtual machines—to separate applications like these from your host system, as well as each other—is one technique you can use to mitigate the chance of an exploit in these applications compromising the rest of your system. For example, technologies like Qubes  OS  or Microsoft Defender Application Guard on Windows provide convenient methods to do this.

If you are concerned about  **physical attacks**  you should use an operating system with a secure verified boot implementation, such as Android, iOS, macOS, or  [Windows (with  TPM)](https://docs.microsoft.com/en-us/windows/security/information-protection/secure-the-windows-10-boot-process). You should also make sure that your drive is encrypted, and that the operating system uses a  TPM  or Secure  [Enclave](https://support.apple.com/guide/security/secure-enclave-sec59b0b31ff/1/web/1)  or  [Element](https://developers.google.com/android/security/android-ready-se)  to rate limit attempts to enter the encryption passphrase. You should avoid sharing your computer with people you don't trust, because most desktop operating systems don't encrypt data separately per-user.

## Privacy From Service Providers

Service Providers

We live in a world where almost everything is connected to the internet. Our "private" messages, emails, and social interactions are typically stored on a server, somewhere. Generally, when you send someone a message it's stored on a server, and when your friend wants to read the message the server will show it to them.

The obvious problem with this is that the service provider (or a hacker who has compromised the server) can access your conversations whenever and however they want, without you ever knowing. This applies to many common services, like  SMS  messaging, Telegram, and Discord.

Thankfully,  E2EE  can alleviate this issue by encrypting communications between you and your desired recipients before they are even sent to the server. The confidentiality of your messages is guaranteed, assuming the service provider doesn't have access to the private keys of either party.

Note on Web-based Encryption

In practice, the effectiveness of different  E2EE  implementations varies. Applications, such as  [Signal](https://www.privacyguides.org/real-time-communication/#signal), run natively on your device, and every copy of the application is the same across different installations. If the service provider were to introduce a  [backdoor](https://en.wikipedia.org/wiki/Backdoor_(computing))  in their application—in an attempt to steal your private keys—it could later be detected with  [reverse engineering](https://en.wikipedia.org/wiki/Reverse_engineering).

On the other hand, web-based  E2EE  implementations, such as Proton Mail's webmail or Bitwarden's  *Web Vault*, rely on the server dynamically serving JavaScript code to the browser to handle cryptography. A malicious server can target you and send you malicious JavaScript code to steal your encryption key (and it would be extremely hard to notice). Because the server can choose to serve different web clients to different people—even if you noticed the attack—it would be incredibly hard to prove the provider's guilt.

Therefore, you should use native applications over web clients whenever possible.

Even with  E2EE, service providers can still profile you based on  **metadata**, which typically isn't protected. While the service provider can't read your messages, they can still observe important things, such as who you're talking to, how often you message them, and when you're typically active. Protection of metadata is fairly uncommon, and—if it's within your  [threat model](https://www.privacyguides.org/basics/threat-modeling/)—you should pay close attention to the technical documentation of the software you're using to see if there's any metadata minimization or protection at all.

## Mass Surveillance Programs

Mass Surveillance

Mass surveillance is the intricate effort to monitor the "behavior, many activities, or information" of an entire (or substantial fraction of a) population.[1](https://www.privacyguides.org/basics/common-threats/#fn:1)  It often refers to government programs, such as the ones  [disclosed by Edward Snowden in 2013](https://en.wikipedia.org/wiki/Global_surveillance_disclosures_(2013%E2%80%93present)). However, it can also be carried out by corporations, either on behalf of government agencies or by their own initiative.

Atlas of Surveillance

If you want to learn more about surveillance methods and how they're implemented in your city you can also take a look at the  [Atlas of Surveillance](https://atlasofsurveillance.org/)  by the  [Electronic Frontier Foundation](https://www.eff.org/).

Governments often justify mass surveillance programs as necessary means to combat terrorism and prevent crime. However, breaching human rights, it's most often used to disproportionately target minority groups and political dissidents, among others.

ACLU:  [*The Privacy Lesson of 9/11: Mass Surveillance is Not the Way Forward*](https://www.aclu.org/news/national-security/the-privacy-lesson-of-9-11-mass-surveillance-is-not-the-way-forward)

In the face of [Edward Snowden's disclosures of government programs such as  [PRISM](https://en.wikipedia.org/wiki/PRISM)  and  [Upstream](https://en.wikipedia.org/wiki/Upstream_collection)], intelligence officials also admitted that the NSA had for years been secretly collecting records about virtually every American’s phone calls — who’s calling whom, when those calls are made, and how long they last. This kind of information, when amassed by the NSA day after day, can reveal incredibly sensitive details about people’s lives and associations, such as whether they have called a pastor, an abortion provider, an addiction counselor, or a suicide hotline.

Despite growing mass surveillance in the United States, the government has found that mass surveillance programs like Section 215 have had "little unique value" with respect to stopping actual crimes or terrorist plots, with efforts largely duplicating the FBI's own targeted surveillance programs.[2](https://www.privacyguides.org/basics/common-threats/#fn:2)

Online, you can be tracked via a variety of methods:

- Your  IP  address
- Browser cookies
- The data you submit to websites
- Your browser or device fingerprint
- Payment method correlation

[This list isn't exhaustive].

If you're concerned about mass surveillance programs, you can use strategues like compartmentalizing your online identities, blending in with other users, or, whenever possible, simply avoiding giving out identifying information.

Surveillance Capitalism

> Surveillance capitalism is an economic system centered around the capture and commodification of personal data for the core purpose of profit-making.[3](https://www.privacyguides.org/basics/common-threats/#fn:3)

For many people, tracking and surveillance by private corporations is a growing concern. Pervasive ad networks, such as those operated by Google and Facebook, span the internet far beyond just the sites they control, tracking your actions along the way. Using tools like content blockers to limit network requests to their servers, and reading the privacy policies of the services you use can help you avoid many basic adversaries (although it can't completely prevent tracking).[4](https://www.privacyguides.org/basics/common-threats/#fn:4)

Additionally, even companies outside of the  *AdTech*  or tracking industry can share your information with  [data brokers](https://en.wikipedia.org/wiki/Information_broker)  (such as Cambridge Analytica, Experian, or Datalogix) or other parties. You can't automatically assume your data is safe just because the service you're using doesn't fall within the typical AdTech or tracking business model. The strongest protection against corporate data collection is to encrypt or obfuscate your data whenever possible, making it difficult for different providers to correlate data with each other and build a profile on you.

## Limiting Public Information

Public Exposure

The best way to keep your data private is simply not making it public in the first place. Deleting unwanted information you find about yourself online is one of the best first steps you can take to regain your privacy.

- [View our guide on account deletion](https://www.privacyguides.org/basics/account-deletion/)

On sites where you do share information, checking the privacy settings of your account to limit how widely that data is spread is very important. For example, enable "private mode" on your accounts if given the option: This ensures that your account isn't being indexed by search engines, and that it can't be viewed without your permission.

If you've already submitted your real information to sites which shouldn't have it, consider using disinformation tactics, like submitting fictitious information related to that online identity. This makes your real information indistinguishable from the false information.

## Avoiding Censorship

Censorship

Censorship online can be carried out (to varying degrees) by actors including totalitarian governments, network administrators, and service providers. These efforts to control communication and restrict access to information will always be incompatible with the human right to Freedom of Expression.[5](https://www.privacyguides.org/basics/common-threats/#fn:5)

Censorship on corporate platforms is increasingly common, as platforms like Twitter and Facebook give in to public demand, market pressures, and pressures from government agencies. Government pressures can be covert requests to businesses, such as the White House  [requesting the takedown](https://www.nytimes.com/2012/09/17/technology/on-the-web-a-fine-line-on-free-speech-across-globe.html)  of a provocative YouTube video, or overt, such as the Chinese government requiring companies to adhere to a strict regime of censorship.

People concerned with the threat of censorship can use technologies like  [Tor](https://www.privacyguides.org/advanced/tor-overview/)  to circumvent it, and support censorship-resistant communication platforms like  [Matrix](https://www.privacyguides.org/real-time-communication/#element), which doesn't have a centralized account authority that can close accounts arbitrarily.

Important

While evading censorship itself can be easy, hiding the fact that you are doing it can be very problematic.

You should consider which aspects of the network your adversary can observe, and whether you have plausible deniability for your actions. For example, using  [encrypted  DNS](https://www.privacyguides.org/advanced/dns-overview/#what-is-encrypted-dns)  can help you bypass rudimentary,  DNS-based censorship systems, but it can't truly hide what you are visiting from your  ISP. A  VPN  or Tor can help hide what you are visiting from network administrators, but can't hide that you're using those networks in the first place. Pluggable transports (such as Obfs4proxy, Meek, or Shadowsocks) can help you evade firewalls that block common  VPN  protocols or Tor, but your circumvention attempts can still be detected by methods like probing or  [deep packet inspection](https://en.wikipedia.org/wiki/Deep_packet_inspection).

You must always consider the risks of trying to bypass censorship, the potential consequences, and how sophisticated your adversary may be. You should be cautious with your software selection, and have a backup plan in case you are caught.

---

# Common Misconceptions

## "Open-source software is always secure" or "Proprietary software is more secure"

These myths stem from a number of prejudices, but whether the source code is available and how software is licensed does not inherently affect its security in any way.  Open-source software has the  *potential*  to be more secure than proprietary software, but there is absolutely no guarantee this is the case.  When you evaluate software, you should look at the reputation and security of each tool on an individual basis.

Open-source software  *can*  be audited by third-parties, and is often more transparent about potential vulnerabilities than proprietary counterparts. It also allows you to review the code and disable any suspicious functionality you find yourself. However,  *unless you do so*, there is no guarantee that code has ever been evaluated, especially with smaller software projects. The open development process has also sometimes been exploited to introduce new vulnerabilities into even large projects.[1](https://www.privacyguides.org/basics/common-misconceptions/#fn:1)

On the flip side, proprietary software is less transparent, but that doesn't imply that it's not secure. Major proprietary software projects can be audited internally and by third-party agencies, and independent security researchers can still find vulnerabilities with techniques like reverse engineering.

To avoid biased decisions, it's  *vital*  that you evaluate the privacy and security standards of the software you use.

## "Shifting trust can increase privacy"

We talk about "shifting trust" a lot when discussing solutions like VPNs (which shift the trust you place in your  ISP  to the  VPN  provider). While this protects your browsing data from your  ISP  *specifically*, the  VPN  provider you choose still has access to your browsing data: Your data isn't completely secured from all parties. This means that:

1. You must exercise caution when choosing a provider to shift trust to.
2. You should still use other techniques, like  E2EE, to protect your data completely. Merely distrusting one provider to trust another is not securing your data.

## "Privacy-focused solutions are inherently trustworthy"

Focusing solely on the privacy policies and marketing of a tool or provider can blind you to its weaknesses. When you're looking for a more private solution, you should determine what the underlying problem is and find technical solutions to that problem. For example, you may want to avoid Google Drive, which gives Google access to all of your data. The underlying problem in this case is lack of  E2EE, so you should make sure that the provider you switch to actually implements  E2EE, or use a tool (like  [Cryptomator](https://www.privacyguides.org/encryption/#cryptomator-cloud)) which provides  E2EE  on any cloud provider. Switching to a "privacy-focused" provider (that doesn't implement  E2EE) doesn't solve your problem: it just shifts trust from Google to that provider.

The privacy policies and business practices of providers you choose are very important, but should be considered secondary to technical guarantees of your privacy: You shouldn't shift trust to another provider when trusting a provider isn't a requirement at all.

## "Complicated is better"

We often see people describing privacy threat models that are overly complex. Often, these solutions include problems like many different email accounts or complicated setups with lots of moving parts and conditions. The replies are usually answers to "What is the best way to do  *X*?"

Finding the "best" solution for yourself doesn't necessarily mean you are after an infallible solution with dozens of conditions—these solutions are often difficult to work with realistically. As we discussed previously, security often comes at the cost of convenience. Below, we provide some tips:

1. Actions need to serve a particular purpose:  think about how to do what you want with the fewest actions.
2. Remove human failure points:  We fail, get tired, and forget things. To maintain security, avoid relying on manual conditions and processes that you have to remember.
3. Use the right level of protection for what you intend.  We often see recommendations of so-called law-enforcement or subpoena-proof solutions. These often require specialist knowledge and generally aren't what people want. There's no point in building an intricate threat model for anonymity if you can be easily de-anonymized by a simple oversight.

So, how might this look?

One of the clearest threat models is one where people  *know who you are*  and one where they do not. There will always be situations where you must declare your legal name and there are others where you don't need to.

1. **Known identity**  - A known identity is used for things where you must declare your name. There are many legal documents and contracts where a legal identity is required. This could range from opening a bank account, signing a property lease, obtaining a passport, customs declarations when importing items, or otherwise dealing with your government. These things will usually lead to credentials such as credit cards, credit rating checks, account numbers, and possibly physical addresses.

    We don't suggest using a  VPN  or Tor for any of these things, as your identity is already known through other means.

    Tip

    When shopping online, the use of a  [parcel locker](https://en.wikipedia.org/wiki/Parcel_locker)  can help keep your physical address private.

2. **Unknown identity**  - An unknown identity could be a stable pseudonym that you regularly use. It is not anonymous because it doesn't change. If you're part of an online community, you may wish to retain a persona that others know. This pseudonym isn't anonymous because—if monitored for long enough—details about the owner can reveal further information, such as the way they write, their general knowledge about topics of interest, etc.

    You may wish to use a  VPN  for this, to mask your  IP  address. Financial transactions are more difficult to mask: You could consider using anonymous cryptocurrencies, such as  [Monero](https://www.getmonero.org/). Employing altcoin shifting may also help to disguise where your currency originated. Typically, exchanges require KYC (know your customer) to be completed before they'll allow you to exchange fiat currency into any kind of cryptocurrency. Local meet-up options may also be a solution; however, those are often more expensive and sometimes also require KYC.

3. **Anonymous identity**  - Even with experience, anonymous identities are difficult to maintain over long periods of time. They should be short-term and short-lived identities which are rotated regularly.

    Using Tor can help with this. It is also worth noting that greater anonymity is possible through asynchronous communication: Real-time communication is vulnerable to analysis of typing patterns (i.e. more than a paragraph of text, distributed on a forum, via email, etc.)

---

# Account Creation

Often people sign up for services without thinking. Maybe it's a streaming service so you can watch that new show everyone's talking about, or an account that gives you a discount for your favorite fast food place. Whatever the case may be, you should consider the implications for your data now and later on down the line.

There are risks associated with every new service that you use. Data breaches; disclosure of customer information to third parties; rogue employees accessing data; all are possibilities that must be considered when giving your information out. You need to be confident that you can trust the service, which is why we don't recommend storing valuable data on anything but the most mature and battle-tested products. That usually means services which provide  E2EE  and have undergone a cryptographic audit. An audit increases assurance that the product was designed without glaring security issues caused by an inexperienced developer.

It can also be difficult to delete the accounts on some services. Sometimes  [overwriting data](https://www.privacyguides.org/basics/account-deletion/#overwriting-account-information)  associated with an account can be possible, but in other cases the service will keep an entire history of changes to the account.

## Terms of Service & Privacy Policy

The  ToS  are the rules that you agree to follow when using the service. With larger services these rules are often enforced by automated systems. Sometimes these automated systems can make mistakes. For example, you may be banned or locked out of your account on some services for using a  VPN  or VOIP number. Appealing such bans is often difficult, and involves an automated process too, which isn't always successful. This would be one of the reasons why we wouldn't suggest using Gmail for email as an example. Email is crucial for access to other services you might have signed up for.

The Privacy Policy is how the service says they will use your data and it is worth reading so that you understand how your data will be used. A company or organization might not be legally obligated to follow everything contained in the policy (it depends on the jurisdiction). We would recommend having some idea what your local laws are and what they permit a provider to collect.

We recommend looking for particular terms such as "data collection", "data analysis", "cookies", "ads" or "3rd-party" services. Sometimes you will be able to opt-out from data collection or from sharing your data, but it is best to choose a service that respects your privacy from the start.

Keep in mind you're also placing your trust in the company or organization and that they will comply with their own privacy policy.

## Authentication methods

There are usually multiple ways to sign up for an account, each with their own benefits and drawbacks.

### Email and password

The most common way to create a new account is by an email address and password. When using this method, you should use a password manager and follow  [best practices](https://www.privacyguides.org/basics/passwords-overview/)  regarding passwords.

Tip

You can use your password manager to organize other authentication methods too! Just add the new entry and fill the appropriate fields, you can add notes for things like security questions or a backup key.

You will be responsible for managing your login credentials. For added security, you can set up  [MFA](https://www.privacyguides.org/basics/multi-factor-authentication/)  on your accounts.

[Recommended password managers](https://www.privacyguides.org/passwords/)

#### Email aliases

If you don't want to give your real email address to a service, you have the option to use an alias. We described them in more detail on our email services recommendation page. Essentially, alias services allow you to generate new email addresses that forward all emails to your main address. This can help prevent tracking across services and help you manage the marketing emails that sometimes come with the sign up process. Those can be filtered automatically based on the alias they are sent to.

Should a service get hacked, you might start receiving phishing or spam emails to the address you used to sign up. Using unique aliases for each service can assist in identifying exactly what service was hacked.

[Recommended email aliasing services](https://www.privacyguides.org/email/#email-aliasing-services)

### Single sign-on

Note

We are discussing Single sign-on for personal use, not enterprise users.

Single sign-on (SSO) is an authentication method that allows you to register for a service without sharing much information, if any. Whenever you see something along the lines of "Sign-in with  *provider name*" on a registration form it's  SSO.

When you choose single sign-on in a website, it will prompt your  SSO  provider login page and after that your account will be connected. Your password won't be shared but some basic information will (you can review it during the login request). This process is needed every time you want to log in to the same account.

The main advantages are:

- **Security**: no risk of being involved in a  [data breach](https://en.wikipedia.org/wiki/Data_breach)  because the website does not store your credentials.
- **Ease of use**: multiple accounts are managed by a single login.

But there are disadvantages:

- **Privacy**: a  SSO  provider will know the services you use.
- **Centralization**: if your  SSO  account gets compromised or you aren't able to login to it, all other accounts connected to it are affected.

SSO  can be especially useful in those situations where you could benefit from deeper integration between services. For example, one of those services may offer  SSO  for the others. Our recommendation is to limit  SSO  to only where you need it and protect the main account with  [MFA](https://www.privacyguides.org/basics/multi-factor-authentication/).

All services that use  SSO  will be as secure as your  SSO  account. For example, if you want to secure an account with a hardware key but that service doesn't support hardware keys, you can secure your  SSO  account with a hardware key and now you essentially have hardware  MFA  on all your accounts. It is worth noting though that weak authentication on your  SSO  account means that any account tied to that login will also be weak.

### Phone number

We recommend avoiding services that require a phone number for sign up. A phone number can identity you across multiple services and depending on data sharing agreements this will make your usage easier to track, particularly if one of those services is breached as the phone number is often  **not**  encrypted.

You should avoid giving out your real phone number if you can. Some services will allow the use of VOIP numbers, however these often trigger fraud detection systems, causing an account to be locked down, so we don't recommend that for important accounts.

In many cases you will need to provide a number that you can receive  SMS  or calls from, particularly when shopping internationally, in case there is a problem with your order at border screening. It's common for services to use your number as a verification method; don't let yourself get locked out of an important account because you wanted to be clever and give a fake number!

### Username and password

Some services allow you to register without using an email address and only require you to set a username and password. These services may provide increased anonymity when combined with a  VPN  or Tor. Keep in mind that for these accounts there will most likely be  **no way to recover your account**  in the event you forget your username or password.

---

# Account Deletion

Over time, it can be easy to accumulate a number of online accounts, many of which you may no longer use. Deleting these unused accounts is an important step in reclaiming your privacy, as dormant accounts are vulnerable to data breaches. A data breach is when a service's security is compromised and protected information is viewed, transmitted, or stolen by unauthorized actors. Data breaches are unfortunately all  [too common](https://haveibeenpwned.com/PwnedWebsites)  these days, and so practicing good digital hygiene is the best way to minimize the impact they have on your life. The goal of this guide then is to help navigate you through the irksome process of account deletion, often made difficult by  [deceptive design](https://www.deceptive.design/), for the betterment of your online presence.

## Finding Old Accounts

### Password Manager

If you have a password manager that you've used for your entire digital life, this part will be very easy. Oftentimes, they include built-in functionality for detecting if your credentials were exposed in a data breach—such as Bitwarden's  [Data Breach Report](https://bitwarden.com/blog/have-you-been-pwned/).

![Bitwarden's Data Breach Report feature](https://www.privacyguides.org/assets/img/account-deletion/exposed_passwords.png)

Even if you haven't explicitly used a password manager before, there's a chance you've used the one in your browser or your phone without even realizing it. For example:  [Firefox Password Manager](https://support.mozilla.org/kb/password-manager-remember-delete-edit-logins),  [Google Password Manager](https://passwords.google.com/intro)  and  [Edge Password Manager](https://support.microsoft.com/en-us/microsoft-edge/save-or-forget-passwords-in-microsoft-edge-b4beecb0-f2a8-1ca0-f26f-9ec247a3f336).

Desktop platforms also often have a password manager which may help you recover passwords you've forgotten about:

- Windows  [Credential Manager](https://support.microsoft.com/en-us/windows/accessing-credential-manager-1b5c916a-6a16-889f-8581-fc16e8165ac0)
- macOS  [Passwords](https://support.apple.com/en-us/HT211145)
- iOS  [Passwords](https://support.apple.com/en-us/HT211146)
- Linux, Gnome Keyring, which can be accessed through  [Seahorse](https://help.gnome.org/users/seahorse/stable/passwords-view.html.en)  or  [KDE Wallet Manager](https://userbase.kde.org/KDE_Wallet_Manager)

### Email

If you didn't use a password manager in the past or you think you have accounts that were never added to your password manager, another option is to search the email account(s) that you believe you signed up on. On your email client, search for keywords such as "verify" or "welcome." Almost every time you make an online account, the service will send a verification link or an introductory message to your email. This can be a good way to find old, forgotten accounts.

## Deleting Old Accounts

### Log In

In order to delete your old accounts, you'll need to first make sure you can log in to them. Again, if the account was in your password manager, this step is easy. If not, you can try to guess your password. Failing that, there are typically options to regain access to your account, commonly available through a "forgot password" link on the login page. It may also be possible that accounts you've abandoned have already been deleted—sometimes services prune all old accounts.

When attempting to regain access, if the site returns an error message saying that email is not associated with an account, or you never receive a reset link after multiple attempts, then you do not have an account under that email address and should try a different one. If you can't figure out which email address you used, or you no longer have access to that email, you can try contacting the service's customer support. Unfortunately, there is no guarantee that you will be able to reclaim access your account.

### GDPR  (EEA  residents only)

Residents of the  EEA  have additional rights regarding data erasure specified in  [Article 17](https://www.gdpr.org/regulation/article-17.html)  of the  GDPR. If it's applicable to you, read the privacy policy for any given service to find information on how to exercise your right to erasure. Reading the privacy policy can prove important, as some services have a "Delete Account" option that only disables your account and for real deletion you have to take additional action. Sometimes actual deletion may involve filling out surveys, emailing the data protection officer of the service or even proving your residence in the  EEA. If you plan to go this way, do  **not**  overwrite account information—your identity as an  EEA  resident may be required. Note that the location of the service does not matter;  GDPR  applies to anyone serving European users. If the service does not respect your right to erasure, you can contact your national  [Data Protection Authority](https://ec.europa.eu/info/law/law-topic/data-protection/reform/rights-citizens/redress/what-should-i-do-if-i-think-my-personal-data-protection-rights-havent-been-respected_en)  and you may be entitled to monetary compensation.

### Overwriting Account information

In some situations where you plan to abandon an account, it may make sense to overwrite the account information with fake data. Once you've made sure you can log in, change all the information in your account to falsified information. The reason for this is that many sites will retain information you previously had even after account deletion. The hope is that they will overwrite the previous information with the newest data you entered. However, there is no guarantee that there won't be backups with the prior information.

For the account email, either create a new alternate email account via your provider of choice or create an alias using an  [email aliasing service](https://www.privacyguides.org/email/#email-aliasing-services). You can then delete your alternate email address once you are done. We recommend against using temporary email providers, as oftentimes it is possible to reactivate temporary emails.

### Delete

You can check  [JustDeleteMe](https://justdeleteme.xyz/)  for instructions on deleting the account for a specific service. Some sites will graciously have a "Delete Account" option, while others will go as far as to force you to speak with a support agent. The deletion process can vary from site to site, with account deletion being impossible on some.

For services that don't allow account deletion, the best thing to do is falsify all your information as previously mentioned and strengthen account security. To do so, enable  [MFA](https://www.privacyguides.org/basics/multi-factor-authentication/)  and any extra security features offered. As well, change the password to a randomly-generated one that is the maximum allowed size (a  [password manager](https://www.privacyguides.org/passwords/)  can be useful for this).

If you're satisfied that all information you care about is removed, you can safely forget about this account. If not, it might be a good idea to keep the credentials stored with your other passwords and occasionally re-login to reset the password.

Even when you are able to delete an account, there is no guarantee that all your information will be removed. In fact, some companies are required by law to keep certain information, particularly when related to financial transactions. It's mostly out of your control what happens to your data when it comes to websites and cloud services.

## Avoid New Accounts

As the old saying goes, "an ounce of prevention is worth a pound of cure." Whenever you feel tempted to sign up for a new account, ask yourself, "Do I really need this? Can I accomplish what I need to without an account?" It can often be much harder to delete an account than to create one. And even after deleting or changing the info on your account, there might be a cached version from a third-party—like the  [Internet Archive](https://archive.org/). Avoid the temptation when you're able to—your future self will thank you!

---

# Introduction to Passwords

Passwords are an essential part of our everyday digital lives. We use them to protect our accounts, our devices and our secrets. Despite often being the only thing between us and an adversary who's after our private information, not a lot of thought is put into them, which often leads to people using passwords that can be easily guessed or brute-forced.

## Best Practices

### Use unique passwords for every service

Imagine this; you sign up for an account with the same e-mail and password on multiple online services. If one of those service providers is malicious, or their service has a data breach that exposes your password in an unencrypted format, all a bad actor would have to do is try that e-mail and password combination across multiple popular services until they get a hit. It doesn't matter how strong that one password is, because they already have it.

This is called  [credential stuffing](https://en.wikipedia.org/wiki/Credential_stuffing), and it is one of the most common ways that your accounts can be compromised by bad actors. To avoid this, make sure that you never re-use your passwords.

### Use randomly generated passwords

You should  **never**  rely on yourself to come up with a good password.  We recommend using  [randomly generated passwords](https://www.privacyguides.org/basics/passwords-overview/#passwords)  or  [diceware passphrases](https://www.privacyguides.org/basics/passwords-overview/#diceware-passphrases)  with sufficient  entropy  to protect your accounts and devices.

All of our  [recommended password managers](https://www.privacyguides.org/passwords/)  include a built-in password generator that you can use.

### Rotating Passwords

You should avoid changing passwords that you have to remember (such as your password manager's master password) too often unless you have reason to believe it has been compromised, as changing it too often exposes you to the risk of forgetting it.

When it comes to passwords that you don't have to remember (such as passwords stored inside your password manager), if your  [threat model](https://www.privacyguides.org/basics/threat-modeling/)  calls for it, we recommend going through important accounts (especially accounts that don't use multi-factor authentication) and changing their password every couple of months, in case they have been compromised in a data breach that hasn't become public yet. Most password managers allow you to set an expiry date for your password to make this easier to manage.

Checking for data breaches

If your password manager lets you check for compromised passwords, make sure to do so and promptly change any password that may have been exposed in a data breach. Alternatively, you could follow  [Have I Been Pwned's Latest Breaches feed](https://feeds.feedburner.com/HaveIBeenPwnedLatestBreaches)  with the help of a  [news aggregator](https://www.privacyguides.org/news-aggregators/).

## Creating strong passwords

### Passwords

A lot of services impose certain criteria when it comes to passwords, including a minimum or maximum length, as well as which special characters, if any, can be used. You should use your password manager's built-in password generator to create passwords that are as long and complex as the service will allow by including capitalized and lowercase letters, numbers and special characters.

If you need a password you can memorize, we recommend a  [diceware passphrase](https://www.privacyguides.org/basics/passwords-overview/#diceware-passphrases).

### Diceware Passphrases

Diceware is a method for creating passphrases which are easy to remember, but hard to guess.

Diceware passphrases are a great option when you need to memorize or manually input your credentials, such as for your password manager's master password or your device's encryption password.

An example of a diceware passphrase is  `viewable fastness reluctant squishy seventeen shown pencil`.

To generate a diceware passphrase using real dice, follow these steps:

Note

These instructions assume that you are using  [EFF's large wordlist](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt)  to generate the passphrase, which requires five dice rolls per word. Other wordlists may require more or less rolls per word, and may require a different amount of words to achieve the same  entropy.

1. Roll a six-sided die five times, noting down the number after each roll.

2. As an example, let's say you rolled  `2-5-2-6-6`. Look through the  [EFF's large wordlist](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt)  for the word that corresponds to  `25266`.

3. You will find the word  `encrypt`. Write that word down.

4. Repeat this process until your passphrase has as many words as you need, which you should separate with a space.

Important

You should  **not**  re-roll words until you get a combination of words that appeal to you. The process should be completely random.

If you don't have access to or would prefer to not use real dice, you can use your password manager's built-in password generator, as most of them have the option to generate diceware passphrases in addition to regular passwords.

We recommend using  [EFF's large wordlist](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt)  to generate your diceware passphrases, as it offers the exact same security as the original list, while containing words that are easier to memorize. There are also other wordlists in different languages, if you do not want your passphrase to be in English.

Explanation of  entropy  and strength of diceware passphrases

To sum it up, diceware passphrases are your best option when you need something that is both easy to remember  *and*  exceptionally strong.

## Storing Passwords

### Password Managers

The best way to store your passwords is by using a password manager. They allow you to store your passwords in a file or in the cloud and protect them with a single master password. That way, you will only have to remember one strong password, which lets you access the rest of them.

There are many good options to choose from, both cloud-based and local. Choose one of our recommended password managers and use it to establish strong passwords across all of your accounts. We recommend securing your password manager with a  [diceware passphrase](https://www.privacyguides.org/basics/passwords-overview/#diceware-passphrases)  comprised of at least seven words.

[List of recommended password managers](https://www.privacyguides.org/passwords/)

Don't place your passwords and  TOTP  tokens inside the same password manager

When using  TOTP  codes as  [multi-factor authentication](https://www.privacyguides.org/multi-factor-authentication/), the best security practice is to keep your  TOTP  codes in a  [separate app](https://www.privacyguides.org/multi-factor-authentication/#authenticator-apps).

Storing your  TOTP  tokens in the same place as your passwords, while convenient, reduces the accounts to a single factor in the event that an adversary gains access to your password manager.

Furthermore, we do not recommend storing single-use recovery codes in your password manager. Those should be stored separately such as in an encrypted container on an offline storage device.

### Backups

You should store an  [encrypted](https://www.privacyguides.org/encryption/)  backup of your passwords on multiple storage devices or a cloud storage provider. This can help you access your passwords if something happens to your primary device or the service you are using.

---

# Multi-Factor Authentication

**Multi-Factor Authentication**  (**MFA**) is a security mechanism that requires additional steps beyond entering your username (or email) and password. The most common method is time limited codes you might receive from  SMS  or an app.

Normally, if a hacker (or adversary) is able to figure out your password then they’d gain access to the account that password belongs to. An account with  MFA  forces the hacker to have both the password (something you  *know*) and a device that you own (something you  *have*), like your phone.

MFA  methods vary in security, but are based on the premise that the more difficult it is for an attacker to gain access to your  MFA  method, the better. Examples of  MFA  methods (from weakest to strongest) include  SMS, Email codes, app push notifications,  TOTP, Yubico  OTP  and  FIDO.

## MFA  Method Comparison

### SMS  or Email  MFA

Receiving  OTP  codes via  SMS  or email are one of the weaker ways to secure your accounts with  MFA. Obtaining a code by email or  SMS  takes away from the "something you  *have*" idea, because there are a variety of ways a hacker could  [take over your phone number](https://en.wikipedia.org/wiki/SIM_swap_scam)  or gain access to your email without having physical access to any of your devices at all. If an unauthorized person gained access to your email, they would be able to use that access to both reset your password and receive the authentication code, giving them full access to your account.

### Push Notifications

Push notification  MFA  takes the form of a message being sent to an app on your phone asking you to confirm new account logins. This method is a lot better than  SMS  or email, since an attacker typically wouldn't be able to get these push notifications without having an already logged-in device, which means they would need to compromise one of your other devices first.

We all make mistakes, and there is the risk that you might accept the login attempt by accident. Push notification login authorizations are typically sent to  *all*  your devices at once, widening the availability of the  MFA  code if you have many devices.

The security of push notification  MFA  is dependent on both the quality of the app, the server component and the trust of the developer who produces it. Installing an app may also require you to accept invasive privileges that grant access to other data on your device. An individual app also requires that you have a specific app for each service which may not require a password to open, unlike a good  TOTP  generator app.

### Time-based One-time Password (TOTP)

TOTP  is one of the most common forms of  MFA  available. When you set up  TOTP, you are generally required to scan a  [QR Code](https://en.wikipedia.org/wiki/QR_code)  which establishes a "[shared secret](https://en.wikipedia.org/wiki/Shared_secret)" with the service that you intend to use. The shared secret is secured inside of the authenticator app's data, and is sometimes protected by a password.

The time-limited code is then derived from the shared secret and the current time. As the code is only valid for a short time, without access to the shared secret, an adversary cannot generate new codes.

If you have a hardware security key with  TOTP  support (such as a YubiKey with  [Yubico Authenticator](https://www.yubico.com/products/yubico-authenticator/)), we recommend that you store your "shared secrets" on the hardware. Hardware such as the YubiKey was developed with the intention of making the "shared secret" difficult to extract and copy. A YubiKey is also not connected to the Internet, unlike a phone with a  TOTP  app.

Unlike  [WebAuthn](https://www.privacyguides.org/basics/multi-factor-authentication/#fido-fast-identity-online),  TOTP  offers no protection against  [phishing](https://en.wikipedia.org/wiki/Phishing)  or reuse attacks. If an adversary obtains a valid code from you, they may use it as many times as they like until it expires (generally 60 seconds).

An adversary could set up a website to imitate an official service in an attempt to trick you into giving out your username, password and current  TOTP  code. If the adversary then uses those recorded credentials they may be able to log into the real service and hijack the account.

Although not perfect,  TOTP  is secure enough for most people, and when  [hardware security keys](https://www.privacyguides.org/multi-factor-authentication/#hardware-security-keys)  are not supported  [authenticator apps](https://www.privacyguides.org/multi-factor-authentication/#authenticator-apps)  are still a good option.

### Hardware security keys

The YubiKey stores data on a tamper-resistant solid-state chip which is  [impossible to access](https://security.stackexchange.com/a/245772)  non-destructively without an expensive process and a forensics laboratory.

These keys are generally multi-function and provide a number of methods to authenticate. Below are the most common ones.

#### Yubico  OTP

Yubico  OTP  is an authentication protocol typically implemented in hardware security keys. When you decide to use Yubico  OTP, the key will generate a public ID, private ID, and a Secret Key which is then uploaded to the Yubico  OTP  server.

When logging into a website, all you need to do is to physically touch the security key. The security key will emulate a keyboard and print out a one-time password into the password field.

The service will then forward the one-time password to the Yubico  OTP  server for validation. A counter is incremented both on the key and Yubico's validation server. The  OTP  can only be used once, and when a successful authentication occurs, the counter is increased which prevents reuse of the  OTP. Yubico provides a  [detailed document](https://developers.yubico.com/OTP/OTPs_Explained.html)  about the process.

![Yubico OTP](https://www.privacyguides.org/assets/img/multi-factor-authentication/yubico-otp.png)

There are some benefits and disadvantages to using Yubico  OTP  when compared to  TOTP.

The Yubico validation server is a cloud based service, and you're placing trust in Yubico that they are storing data securely and not profiling you. The public ID associated with Yubico  OTP  is reused on every website and could be another avenue for third-parties to profile you. Like  TOTP, Yubico  OTP  does not provide phishing resistance.

If your threat model requires you to have different identities on different websites,  **do not**  use Yubico  OTP  with the same hardware security key across those websites as public ID is unique to each security key.

#### FIDO  (Fast IDentity Online)

[FIDO](https://en.wikipedia.org/wiki/FIDO_Alliance)  includes a number of standards, first there was  U2F  and then later  [FIDO2](https://en.wikipedia.org/wiki/FIDO2_Project)  which includes the web standard  [WebAuthn](https://en.wikipedia.org/wiki/WebAuthn).

U2F  and FIDO2 refer to the  [Client to Authenticator Protocol](https://en.wikipedia.org/wiki/Client_to_Authenticator_Protocol), which is the protocol between the security key and the computer, such as a laptop or phone. It complements WebAuthn which is the component used to authenticate with the website (the "Relying Party") you're trying to log in on.

WebAuthn is the most secure and private form of second factor authentication. While the authentication experience is similar to Yubico  OTP, the key does not print out a one-time password and validate with a third-party server. Instead, it uses  [public key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)  for authentication.

![FIDO](https://www.privacyguides.org/assets/img/multi-factor-authentication/fido.png)

When you create an account, the public key is sent to the service, then when you log in, the service will require you to "sign" some data with your private key. The benefit of this is that no password data is ever stored by the service, so there is nothing for an adversary to steal.

This presentation discusses the history of password authentication, the pitfalls (such as password reuse), and discussion of FIDO2 and  [WebAuthn](https://webauthn.guide/)  standards.

FIDO2 and WebAuthn have superior security and privacy properties when compared to any  MFA  methods.

Typically for web services it is used with WebAuthn which is a part of the  [W3C  recommendations](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium#W3C_recommendation_(REC)). It uses public key authentication and is more secure than shared secrets used in Yubico  OTP  and  TOTP  methods, as it includes the origin name (usually, the domain name) during authentication. Attestation is provided to protect you from phishing attacks, as it helps you to determine that you are using the authentic service and not a fake copy.

Unlike Yubico  OTP, WebAuthn does not use any public ID, so the key is  **not**  identifiable across different websites. It also does not use any third-party cloud server for authentication. All communication is completed between the key and the website you are logging into.  FIDO  also uses a counter which is incremented upon use in order to prevent session reuse and cloned keys.

If a website or service supports WebAuthn for the authentication, it is highly recommended that you use it over any other form of  MFA.

## General Recommendations

We have these general recommendations:

### Which Method Should I Use?

When configuring your  MFA  method, keep in mind that it is only as secure as your weakest authentication method you use. This means it is important that you only use the best  MFA  method available. For instance, if you are already using  TOTP, you should disable email and  SMS  MFA. If you are already using FIDO2/WebAuthn, you should not be using Yubico  OTP  or  TOTP  on your account.

### Backups

You should always have backups for your  MFA  method. Hardware security keys can get lost, stolen or simply stop working over time. It is recommended that you have a pair of hardware security keys with the same access to your accounts instead of just one.

When using  TOTP  with an authenticator app, be sure to back up your recovery keys or the app itself, or copy the "shared secrets" to another instance of the app on a different phone or to an encrypted container (e.g.  [VeraCrypt](https://www.privacyguides.org/encryption/#veracrypt)).

### Initial Set Up

When buying a security key, it is important that you change the default credentials, set up password protection for the key, and enable touch confirmation if your key supports it. Products such as the YubiKey have multiple interfaces with separate credentials for each one of them, so you should go over each interface and set up protection as well.

### Email and  SMS

If you have to use email for  MFA, make sure that the email account itself is secured with a proper  MFA  method.

If you use  SMS  MFA, use a carrier who will not switch your phone number to a new  SIM  card without account access, or use a dedicated  VoIP  number from a provider with similar security to avoid a  [SIM  swap attack](https://en.wikipedia.org/wiki/SIM_swap_scam).

[MFA  tools we recommend](https://www.privacyguides.org/multi-factor-authentication/)

## More Places to Set Up  MFA

Beyond just securing your website logins, multi-factor authentication can be used to secure your local logins,  SSH  keys or even password databases as well.

### Windows

Yubico has a dedicated  [Credential Provider](https://docs.microsoft.com/en-us/windows/win32/secauthn/credential-providers-in-windows)  that adds Challenge-Response authentication for the username + password login flow for local Windows accounts. If you have a YubiKey with Challenge-Response authentication support, take a look at the  [Yubico Login for Windows Configuration Guide](https://support.yubico.com/hc/en-us/articles/360013708460-Yubico-Login-for-Windows-Configuration-Guide), which will allow you to set up  MFA  on your Windows computer.

### macOS

macOS has  [native support](https://support.apple.com/guide/deployment/intro-to-smart-card-integration-depd0b888248/web)  for authentication with smart cards (PIV). If you have a smartcard or a hardware security key that supports the PIV interface such as the YubiKey, we recommend that you follow your smartcard/hardware security vendor's documentation and set up second factor authentication for your macOS computer.

Yubico have a guide  [Using Your YubiKey as a Smart Card in macOS](https://support.yubico.com/hc/en-us/articles/360016649059)  which can help you set up your YubiKey on macOS.

After your smartcard/security key is set up, we recommend running this command in the Terminal:

`sudo defaults write /Library/Preferences/com.apple.loginwindow DisableFDEAutoLogin -bool YES`

The command will prevent an adversary from bypassing  MFA  when the computer boots.

### Linux

Warning

If the hostname of your system changes (such as due to DHCP), you would be unable to login. It is vital that you set up a proper hostname for your computer before following this guide.

The  `pam_u2f`  module on Linux can provide two-factor authentication for logging in on most popular Linux distributions. If you have a hardware security key that supports  U2F, you can set up  MFA  authentication for your login. Yubico has a guide  [Ubuntu Linux Login Guide -  U2F](https://support.yubico.com/hc/en-us/articles/360016649099-Ubuntu-Linux-Login-Guide-U2F)  which should work on any distribution. The package manager commands—such as  `apt-get`—and package names may however differ. This guide does  **not**  apply to Qubes  OS.

### Qubes  OS

Qubes  OS  has support for Challenge-Response authentication with YubiKeys. If you have a YubiKey with Challenge-Response authentication support, take a look at the Qubes  OS  [YubiKey documentation](https://www.qubes-os.org/doc/yubikey/)  if you want to set up  MFA  on Qubes  OS.

### SSH

#### Hardware Security Keys

SSH  MFA  could be set up using multiple different authentication methods that are popular with hardware security keys. We recommend that you check out Yubico's  [documentation](https://developers.yubico.com/SSH/)  on how to set this up.

#### Time-based One-time Password (TOTP)

SSH  MFA  can also be set up using  TOTP. DigitalOcean has provided a tutorial  [How To Set Up Multi-Factor Authentication for  SSH  on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-multi-factor-authentication-for-ssh-on-ubuntu-20-04). Most things should be the same regardless of distribution, however the package manager commands—such as  `apt-get`—and package names may differ.

### KeePass (and KeePassXC)

KeePass and KeePassXC databases can be secured using Challenge-Response or  HOTP  as a second-factor authentication. Yubico has provided a document for KeePass  [Using Your YubiKey with KeePass](https://support.yubico.com/hc/en-us/articles/360013779759-Using-Your-YubiKey-with-KeePass)  and there is also one on the  [KeePassXC](https://keepassxc.org/docs/#faq-yubikey-2fa)  website.

---

# Email Security

Email is an insecure form of communication by default. You can improve your email security with tools such as  OpenPGP, which add End-to-End Encryption to your messages, but  OpenPGP  still has a number of drawbacks compared to encryption in other messaging applications, and some email data can never be encrypted inherently due to how email is designed.

As a result, email is best used for receiving transactional emails (like notifications, verification emails, password resets, etc.) from the services you sign up for online, not for communicating with others.

## Email Encryption Overview

The standard way to add  E2EE  to emails between different email providers is by using  OpenPGP. There are different implementations of the  OpenPGP  standard, the most common being  [GnuPG](https://en.wikipedia.org/wiki/GNU_Privacy_Guard)  and  [OpenPGP.js](https://openpgpjs.org/).

There is another standard which is popular with business called  [S/MIME](https://en.wikipedia.org/wiki/S/MIME), however, it requires a certificate issued from a  [Certificate Authority](https://en.wikipedia.org/wiki/Certificate_authority)  (not all of them issue S/MIME certificates). It has support in  [Google Workplace](https://support.google.com/a/topic/9061730?hl=en&ref_topic=9061731)  and  [Outlook for Web or Exchange Server 2016, 2019](https://support.office.com/en-us/article/encrypt-messages-by-using-s-mime-in-outlook-on-the-web-878c79fc-7088-4b39-966f-14512658f480).

Even if you use  OpenPGP, it does not support  [forward secrecy](https://en.wikipedia.org/wiki/Forward_secrecy), which means if either your or the recipient's private key is ever stolen, all previous messages encrypted with it will be exposed. This is why we recommend  [instant messengers](https://www.privacyguides.org/real-time-communication/)  which implement forward secrecy over email for person-to-person communications whenever possible.

### What Email Clients Support  E2EE?

Email providers which allow you to use standard access protocols like  IMAP  and  SMTP  can be used with any of the  [email clients we recommend](https://www.privacyguides.org/email-clients/). Depending on the authentication method, this may lead to the decrease security if either the provider or the email client does not support OATH or a bridge application as  [multi-factor authentication](https://www.privacyguides.org/basics/multi-factor-authentication/)  is not possible with plain password authentication.

### How Do I Protect My Private Keys?

A smartcard (such as a  [Yubikey](https://support.yubico.com/hc/en-us/articles/360013790259-Using-Your-YubiKey-with-OpenPGP)  or  [Nitrokey](https://www.nitrokey.com/)) works by receiving an encrypted email message from a device (phone, tablet, computer, etc) running an email/webmail client. The message is then decrypted by the smartcard and the decrypted content is sent back to the device.

It is advantageous for the decryption to occur on the smartcard so as to avoid possibly exposing your private key to a compromised device.

## Email Metadata Overview

Email metadata is stored in the  [message header](https://en.wikipedia.org/wiki/Email#Message_header)  of the email message and includes some visible headers that you may have seen such as:  `To`,  `From`,  `Cc`,  `Date`,  `Subject`. There are also a number of hidden headers included by many email clients and providers that can reveal information about your account.

Client software may use email metadata to show who a message is from and what time it was received. Servers may use it to determine where an email message must be sent, among  [other purposes](https://en.wikipedia.org/wiki/Email#Message_header)  which are not always transparent.

### Who Can View Email Metadata?

Email metadata is protected from outside observers with  [Opportunistic  TLS](https://en.wikipedia.org/wiki/Opportunistic_TLS)  protecting it from outside observers, but it is still able to be seen by your email client software (or webmail) and any servers relaying the message from you to any recipients including your email provider. Sometimes email servers will also use third-party services to protect against spam, which generally also have access to your messages.

### Why Can't Metadata be  E2EE?

Email metadata is crucial to the most basic functionality of email (where it came from, and where it has to go).  E2EE  was not built into the email protocols originally, instead requiring add-on software like  OpenPGP. Because  OpenPGP  messages still have to work with traditional email providers, it cannot encrypt email metadata, only the message body itself. That means that even when using  OpenPGP, outside observers can see lots of information about your messages, such as who you're emailing, the subject lines, when you're emailing, etc.

---

# VPN Overview

Virtual Private Networks are a way of extending the end of your network to exit somewhere else in the world. An  ISP  can see the flow of internet traffic entering and exiting your network termination device (i.e. modem).

Encryption protocols such as  HTTPS  are commonly used on the internet, so they may not be able to see exactly what you're posting or reading but they can get an idea of the  [domains you request](https://www.privacyguides.org/advanced/dns-overview/#why-shouldnt-i-use-encrypted-dns).

A  VPN  can help as it can shift trust to a server somewhere else in the world. As a result, the  ISP  then only sees that you are connected to a  VPN  and nothing about the activity that you're passing into it.

## Should I use a  VPN?

**Yes**, unless you are already using Tor. A  VPN  does two things: shifting the risks from your Internet Service Provider to itself and hiding your  IP  from a third-party service.

VPNs cannot encrypt data outside of the connection between your device and the  VPN  server.  VPN  providers can see and modify your traffic the same way your  ISP  could. And there is no way to verify a  VPN  provider's "no logging" policies in any way.

However, they do hide your actual  IP  from a third-party service, provided that there are no  IP  leaks. They help you blend in with others and mitigate  IP  based tracking.

## When shouldn't I use a  VPN?

Using a  VPN  in cases where you're using your  [known identity](https://www.privacyguides.org/basics/common-threats/#common-misconceptions)  is unlikely be useful.

Doing so may trigger spam and fraud detection systems, such as if you were to log into your bank's website.

## What about encryption?

Encryption offered by  VPN  providers are between your devices and their servers. It guarantees that this specific link is secure. This is a step up from using unencrypted proxies where an adversary on the network can intercept the communications between your devices and said proxies and modify them. However, encryption between your apps or browsers with the service providers are not handled by this encryption.

In order to keep what you actually do on the websites you visit private and secure, you must use  HTTPS. This will keep your passwords, session tokens, and queries safe from the  VPN  provider. Consider enabling "HTTPS  everywhere" in your browser to mitigate downgrade attacks like  [SSL Strip](https://www.blackhat.com/presentations/bh-dc-09/Marlinspike/BlackHat-DC-09-Marlinspike-Defeating-SSL.pdf).

## Should I use encrypted  DNS  with a  VPN?

Unless your  VPN  provider hosts the encrypted  DNS  servers,  **no**. Using DOH/DOT (or any other form of encrypted  DNS) with third-party servers will simply add more entities to trust and does  **absolutely nothing**  to improve your privacy/security. Your  VPN  provider can still see which websites you visit based on the  IP  addresses and other methods. Instead of just trusting your  VPN  provider, you are now trusting both the  VPN  provider and the  DNS  provider.

A common reason to recommend encrypted  DNS  is that it helps against  DNS  spoofing. However, your browser should already be checking for  [TLS  certificates](https://en.wikipedia.org/wiki/Transport_Layer_Security#Digital_certificates)  with  **HTTPS**  and warn you about it. If you are not using  **HTTPS**, then an adversary can still just modify anything other than your  DNS  queries and the end result will be little different.

Needless to say,  **you shouldn't use encrypted  DNS  with Tor**. This would direct all of your  DNS  requests through a single circuit and would allow the encrypted  DNS  provider to deanonymize you.

## Should I use Tor  *and*  a  VPN?

By using a  VPN  with Tor, you're creating essentially a permanent entry node, often with a money trail attached. This provides zero additional benefits to you, while increasing the  attack surface  of your connection dramatically. If you wish to hide your Tor usage from your  ISP  or your government, Tor has a built-in solution for that: Tor bridges.  [Read more about Tor bridges and why using a  VPN  is not necessary](https://www.privacyguides.org/advanced/tor-overview/).

## What if I need anonymity?

VPNs cannot provide anonymity. Your  VPN  provider will still see your real  IP  address, and often has a money trail that can be linked directly back to you. You cannot rely on "no logging" policies to protect your data. Use  [Tor](https://www.torproject.org/)  instead.

## What about  VPN  providers that provide Tor nodes?

Do not use that feature. The point of using Tor is that you do not trust your  VPN  provider. Currently Tor only supports the  [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)  protocol.  [UDP](https://en.wikipedia.org/wiki/User_Datagram_Protocol)  (used in  [WebRTC](https://en.wikipedia.org/wiki/WebRTC)  for voice and video sharing, the new  [HTTP3/QUIC](https://en.wikipedia.org/wiki/HTTP/3)  protocol, etc),  [ICMP](https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol)  and other packets will be dropped. To compensate for this,  VPN  providers typically will route all non-TCP  packets through their  VPN  server (your first hop). This is the case with  [ProtonVPN](https://protonvpn.com/support/tor-vpn/). Additionally, when using this Tor over  VPN  setup, you do not have control over other important Tor features such as  [Isolated Destination Address](https://www.whonix.org/wiki/Stream_Isolation)  (using a different Tor circuit for every domain you visit).

The feature should be viewed as a convenient way to access the Tor Network, not to stay anonymous. For proper anonymity, use the Tor Browser, TorSocks, or a Tor gateway.

## When are VPNs useful?

A  VPN  may still be useful to you in a variety of scenarios, such as:

1. Hiding your traffic from  **only**  your Internet Service Provider.
2. Hiding your downloads (such as torrents) from your  ISP  and anti-piracy organizations.
3. Hiding your  IP  from third-party websites and services, preventing  IP  based tracking.

For use cases like these, or if you have another compelling reason, the  VPN  providers we listed above are who we think are the most trustworthy. However, using a  VPN  provider still means you're  *trusting*  the provider. In pretty much any other scenario you should be using a secure**-by-design**  tool such as Tor.

## Sources and Further Reading

1. [VPN  - a Very Precarious Narrative](https://schub.io/blog/2019/04/08/very-precarious-narrative.html)  by Dennis Schubert
2. [Tor Network Overview](https://www.privacyguides.org/advanced/tor-overview/)
3. [IVPN Privacy Guides](https://www.ivpn.net/privacy-guides)
4. ["Do I need a  VPN?"](https://www.doineedavpn.com/), a tool developed by IVPN to challenge aggressive  VPN  marketing by helping individuals decide if a  VPN  is right for them.

## Related  VPN  Information

- [The Trouble with  VPN  and Privacy Review Sites](https://blog.privacyguides.org/2019/11/20/the-trouble-with-vpn-and-privacy-review-sites/)
- [Free  VPN  App Investigation](https://www.top10vpn.com/free-vpn-app-investigation/)
- [Hidden  VPN  owners unveiled: 101  VPN  products run by just 23 companies](https://vpnpro.com/blog/hidden-vpn-owners-unveiled-97-vpns-23-companies/)
- [This Chinese company is secretly behind 24 popular apps seeking dangerous permissions](https://vpnpro.com/blog/chinese-company-secretly-behind-popular-apps-seeking-dangerous-permissions/)
