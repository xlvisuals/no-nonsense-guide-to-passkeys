## The no-nonsense guide to Passkeys
(Without losing control or getting locked into a single ecosystem)

### Why Passkeys?
Passkeys were designed to solve the two biggest flaws of the internet: **phishing** and **server leaks**. 
While a password is a secret you *share* with a website (giving them something to lose), a passkey is a secret that *never leaves your device*.

But for many, especially security conscious users, the "convenience" of passkeys feels like a trap: trading independence for a system that locks keys inside a specific phone or a "Big Tech" cloud. 

Fortunately you don't have to choose between high-end security and personal autonomy. By using a **third-party manager**, you get the mathematical "un-hackability" of a passkey with the cross-platform freedom of a password. You own the keys; the manager just carries them for you.

---

### How to use Passkeys without getting locked in or locked out
You can enjoy the elite asymmetric security (public/private key pairs) of passkeys while maintaining your independence by using a **Password Manager** (1Password, Proton Pass, Bitwarden, NordPass, Dashlane, Keeper, etc.) instead of the built - in tools from Apple, Google, or Microsoft. This keeps your keys **portable** across all your devices.

* **Everyday login:** Use the Passkey stored in your manager. It is mathematically impossible to phish and protects your login data even if the website itself is hacked. The website has your public key, only you have your private key.
* **The sovereignty check:** **Don't let the OS hijack the process.** When creating a passkey, ensure your Password Manager is the one handling the request. If you see a system pop - up from Windows, iOS, or Android instead of your manager, stop. Choose **"Other Options"** or **"Use another device"** to ensure that key lives in your portable vault, not stuck inside that specific device.
* **The fail-safe:** When you create a passkey, the website will often give you **Recovery/Backup Codes. Treat these like gold.**
* **The digital vault backup:*** Since you can't write a passkey on paper, periodically export your encrypted vault file (e.g. .cxp, .1pux or .json) to a secure USB drive. This ensures you have copied of your passwords and keys even if the Password Manager suddenly stops working. The **Credential Exchange Protocol (CXP)** is the new standard file format for this.
* **The digital vault backup:** You can't write Passkeys on paper. Periodically export your Password Manager vault to a USB drive (e.g., **.cxp**, **.1pux**, or **.json**). To keep this file safe from thieves, keep the USB drive otherwise disconnected and store the file inside an encrypted container using [**VeraCrypt**](https://veracrypt.io/) or [**Cryptomator**](https://cryptomator.org/).
  * **The one exception to password re-use**: Set the password for your backup vault to be the same as the master password for your Password Manager. They protect the same data, and reusing the password here ensures you won't be locked out of your backup because you forgot a secondary password you rarely use.
* **Beware of "recovery code phishing":** Phishers are smart — they will stop trying to phish your login and start trying to phish your recovery. If you get a phone call or an email from "Support" asking you to read back a recovery code to "verify your identity," **it is a scam.**
* **Update your offline backup:** Periodically export your Password Manager database to a secure file and make sure it includes your Passkeys. This ensures you aren't reliant on the continued access to your Password Manager database.

---

### If things go wrong, you have three layers of safety:

1.  **Vault access:** Because the Password Manager keeps a **local encrypted copy** on your device, you can still access your passkeys even if the servers go down or you are offline. **Verify this now:** Turn on Airplane Mode (or disconnect your PC/Mac) and ensure you can still open your vault and see your entries.
2.  **Email recovery:** Many sites still let you use "Forgot Password" or email links as a fallback, though they may add a "security delay" to protect you.
3.  **The nuclear option:** The **Recovery Codes** stored on paper or an encrypted file will bypass the passkey entirely and get you back into the account instantly.

---

### The Bottom Line

You don't have to trust "the cloud" or "Big Tech." By storing passkeys in a third-party manager and keeping paper recovery codes, you get the best security in the world (Passkeys) with the same reliability as your old system, and without being tied to a single device.
