# Dual-Licensing Template for ABI Research Software

An exemplary template for researchers and students to start software projects with a dual-licensing framework and academic attribution metadata.

This repository includes a pre-configured `LICENSE` file template and a machine-readable `CITATION.cff` file.

---

## Starting a New GitHub Repository

If you are launching a new software project, we highly recommend using this repository as a baseline template. 

1. Click the **Use this template** button in the top-right corner of this page:

<img width="682" height="123" alt="Use this template button" src="https://github.com/user-attachments/assets/f794fff1-5765-409a-a6a6-f81e433b86bf" />

2. Select **Create a new repository**. GitHub will redirect you to the configuration page:

<img width="904" height="739" alt="Create new repository configuration" src="https://github.com/user-attachments/assets/943bd3c9-d22c-45c3-8a50-a1099aac81c6" />

3. Configure your new repository settings:
   * Keep **Start with a template** set to `ABI-Software/dual-licensing-example`.
   * Keep **Include all branches** turned **off**.
   * Select the appropriate **Owner** (your personal account or your organisation) and enter your **Repository name**.
   * Add a project description (you can update this later).
   * Set the visibility to **Public** or **Private** based on your project's current confidentiality requirements.
4. Click **Create repository**.

You now have a clean repository populated with the correct dual-licensing text and a citation template. You are ready to begin developing your code!

---

## Rectifying an Existing Repository

Transitioning an active, existing codebase to a dual-licensing model requires careful legal and technical compliance:

1. **Verify IP Ownership:** Ensure you have the legal right to license the code. Review the *Intellectual Property Policy from the Unviersitry*. Remember that external contributions or viral dependencies may impact your licensing options.
2. **Obtain Contributor Consent:** You **must** get explicit, written agreement from 100% of the past authors/contributors who wrote code currently in the repository before changing the license terms.
3. **Apply the New Licence:** Copy the `LICENSE` file from this template into your root directory. Update your documentation to state that the dual-licensing model applies to all versions from this commit forward. *Note: Do not delete historical open-source licences if that legacy code remains in your version history.*
4. **Add Academic Attribution:** Copy and update the `CITATION.cff` file to ensure your team receives proper academic citation when your software is used by other researchers.
