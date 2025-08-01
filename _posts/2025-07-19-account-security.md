---
title: 'Thoughts of Account Security'
date: 2025-07-19
collection: posts
permalink: /posts/2025-07-19-account-security/
---

The first question you must answer is: who are you trying to defend against? In other words, who is the last person you would want to access your accounts? Your security strategy and the steps you should take depend entirely on this answer.

If your goal is to protect your accounts from friends, relatives, or unknown actors such as hackers, you should prioritize using two-factor authentication (2FA). Rely on "what you have"—such as passkeys, security keys, or authenticator apps—instead of "what you know" like passwords or security questions, which are easier to compromise.

However, if your concern is with institutional access—for example, if you're trying to prevent access by official organizations in your region—you should consider choosing a platform that stores your data outside of your home country. One way to achieve this is by setting your account region (such as for your Apple ID) to a different country. This may help store your data in a jurisdiction with different legal or privacy protections.

You can also combine multiple security technologies for enhanced protection. In my case, I prioritize the following methods (in order of preference): hardware security keys, passkeys, authenticator app codes, and email verification codes. I avoid using passwords whenever possible. I also refrain from using SMS verification, except when it's the only available method to access an account.

**Hardware security keys** offer an extremely high level of protection, as they are nearly impossible to clone or hack remotely. **However, if you're using security keys as your 2FA method, you must disable all other forms of 2FA** to ensure that weaker alternatives don’t become a vulnerability. Always keep at least two keys—one primary and one backup—but never carry them together. The drawbacks are their limited platform support and relatively high cost.

**Passkeys** function like virtual security keys linked to a trusted ecosystem (e.g., Apple or Google). They are free and user-friendly, but their security depends on the safety of the devices that store them. If any device with a stored passkey is compromised, so are the credentials. Passkey support is also still limited across platforms.

**Authenticator app codes** act like offline passkeys and are supported more broadly. Offline apps store codes locally, which enhances privacy but creates risk: if you lose or damage the device, access to your accounts can be permanently lost. Online authenticator apps offer backup and syncing, but they introduce a trust dependency on the provider and often require a master account login with its own risks.

**Email verification codes** are only as secure as your email account. Losing access to your email puts all associated services at risk. In countries with extensive surveillance policies, popular email providers may cooperate with authorities, meaning your verification codes—and possibly your entire account—can be monitored or accessed without your knowledge. To reduce this risk, consider using an email service hosted outside your home country.

**SMS verification codes** are among the least secure options. They are almost always monitored by local telecom providers, which are often regulated or controlled by government authorities. SMS codes can be intercepted through silent SMS or SIM swap attacks, making them highly vulnerable. In high-surveillance environments, SMS-based 2FA provides little to no real privacy or protection.

Regardless of your login methods, here are several additional tips to enhance account security:

1. **Never reuse passwords across accounts.** Use a password manager (such as 1Password, Bitwarden, or Proton Pass) to generate and store unique, strong passwords. Regularly update them.

2. **Avoid logging into your accounts on public or shared devices.** These systems may be infected with malware capable of stealing your credentials.

3. **For highly sensitive accounts**—such as those involving cryptocurrency—use a dedicated device for access, and ensure that no information related to those accounts is ever transferred outside that device.

4. **Never share account information through online communication tools**, especially on social media or chat apps. These channels are often insecure.

For users in high-surveillance environments, consider the following additional precautions:

1. **Avoid typing passwords when possible.** Input method editors (IMEs) may log your keystrokes. Use biometric or hardware-based authentication instead.

2. **Limit participation in online discussions**, especially on forums, live chat platforms, or group chats. These interactions may be monitored.

3. **Use email and SMS services provided by companies outside your country**, preferably in jurisdictions with strong privacy protections.

4. **Use a trusted VPN service** to encrypt your internet traffic. If possible, operate through a custom DNS server to reduce exposure to local surveillance infrastructure.
