# My Notes — [OLUHARAOTU ALEXANDER O]

> **How to use this file:**
> 1. **Download** this file to your computer — click the **Raw** button on GitHub, then right-click and *Save As*, OR click the download icon at the top-right of the file view
> 2. **Rename** the downloaded file — replace `yourname` with your actual first and last name in lowercase, separated by hyphens, e.g. `microsoft-entra-oyimafu-emmanuel.md`
> 3. **Open** the renamed file in any text editor (Notepad, VS Code, TextEdit) and fill in your notes below
> 4. **Upload** your file to GitHub — go into this session folder on your forked repo, click **Add file → Upload files**, drag in your completed file, then click **Commit changes**
> 5. **Open a Pull Request** back to the main repo — the facilitator will review your notes before merging

---

## Key Concepts I Learned

<!-- Write the main ideas covered in today's session -->

- The AI secrets problems and risk model
- Key Vault object types (secrets,keys and certificates
- RBAC verses access policies
- Managed Identities secret access flow 
- Network controls,soft delete and purge protection
- Defender for Key vault
- Lab ; Deploy and secure Azure Key Vault.

---

## Lab / Hands-On Work

<!-- Describe what you did in the lab. Include steps, commands, or screenshots descriptions -->

### What I did

Deploy an Azure Key Vault 
Assign role-based access to the application's managed identity and a test user account
Store an API key and a cryptographic key in the vault
Confirm that a limited Reader role does not grant access to secret values
Retrieve the secret using the App Service managed identity via the managed identity token endpoint
Restrict vault network access to an authorized virtual network
Enable the Defender for Key Vault protection plan and configure audit log forwarding


### What happened / Result


### Challenges I faced


---

## My Takeaways

<!-- What was most valuable to you personally from this session? -->

- Identity is everything. It all starts and Ends with Identity
- Entra I D portal is different from the Azure Portal
- Control Plane were one creates,deletes and assign policy
- Data Plane (core content)read and write secrets,key and certificates are authorized
-Managed Identity secret retrieval.
- 
---

## Questions I Still Have

<!-- Anything you want to follow up on or ask the mentor -->

-
-

---

## Resources I Found Useful

<!-- Any links, docs, or Microsoft Learn modules you found helpful -->

-

---

*Submitted by: [oluharaotu alexander] · [little saint]*
