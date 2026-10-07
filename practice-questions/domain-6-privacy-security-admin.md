# Practice Questions - Domain 6 (Privacy, Security, and Administration)

### Question 1
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: Authentication  
**Difficulty**: Beginner  

Which authentication method is commonly used for Git operations without a password?

A. OAuth token  
B. SSH key  
C. SSO session  
D. GitHub Actions token  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** SSH keys are used for Git operations without passwords.

**Reference:** https://docs.github.com/en/authentication/connecting-to-github-with-ssh
</details>

### Question 2
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: PAT Types  
**Difficulty**: Beginner  

Which PAT type allows repo-specific, permission-specific scope?

A. Classic PAT  
B. Fine-grained PAT  
C. OAuth token  
D. SSH key  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Fine-grained PATs allow granular scopes per repo.

**Reference:** https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
</details>

### Question 3
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: Secret Scanning  
**Difficulty**: Beginner  

What does push protection do?

A. Scans code only after merge  
B. Blocks pushes that contain secrets  
C. Requires code owner approval  
D. Encrypts the repository  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Push protection blocks commits containing detected secrets.

**Reference:** https://docs.github.com/en/code-security/secret-scanning
</details>

### Question 4
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: Dependabot  
**Difficulty**: Beginner  

Which Dependabot feature opens PRs to update vulnerable dependencies?

A. Alerts  
B. Security updates  
C. Version updates  
D. Code scanning  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Security updates generate PRs that remediate vulnerabilities.

**Reference:** https://docs.github.com/en/code-security/dependabot/dependabot-security-updates
</details>

### Question 5
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: Security Policy  
**Difficulty**: Beginner  

What file describes how to report a vulnerability?

A. `CODEOWNERS`  
B. `SECURITY.md`  
C. `LICENSE`  
D. `README.md`  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** `SECURITY.md` defines reporting and disclosure guidelines.

**Reference:** https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository
</details>

### Question 6
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: PAT Types  
**Difficulty**: Beginner  

Which PAT type allows permissions to be restricted to specific repositories?

A. Classic PAT  
B. Fine-grained PAT  
C. OAuth app token  
D. SSH key  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Fine-grained PATs are scoped to specific repos and permissions.

**Reference:** https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
</details>

### Question 7
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: Secret Scanning  
**Difficulty**: Beginner  

What happens when push protection detects a secret?

A. The push is blocked with a bypass option  
B. The repo is deleted  
C. The user is removed from the org  
D. A release is created  

<details>
<summary>Answer</summary>

**Correct Answer:** A

**Explanation:** Push protection blocks the push and may allow a bypass with justification.

**Reference:** https://docs.github.com/en/code-security/secret-scanning/working-with-secret-scanning-and-push-protection
</details>

### Question 8
**Domain**: Domain 6 - Privacy, Security, and Administration
**Topic**: Dependabot
**Difficulty**: Beginner

Which file configures version update schedules for Dependabot?

A. `.github/dependabot.yml`  
B. `.github/actions.yml`  
C. `SECURITY.md`  
D. `.github/workflows/dependabot.yml`  

<details>
<summary>Answer</summary>

**Correct Answer:** A

**Explanation:** Dependabot version updates are configured in `dependabot.yml`.

**Reference:** https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuring-dependabot-version-updates
</details>

### Question 9
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: Code Scanning  
**Difficulty**: Beginner  

What is CodeQL in GitHub?

A. A package manager  
B. A static analysis engine for code scanning  
C. A branching strategy  
D. A workflow trigger  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** CodeQL is the analysis engine used for code scanning.

**Reference:** https://docs.github.com/en/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning
</details>

### Question 10
**Domain**: Domain 6 - Privacy, Security, and Administration  
**Topic**: 2FA Enforcement  
**Difficulty**: Beginner  

Where do organization owners enforce 2FA?

A. Repo settings  
B. Organization security settings  
C. GitHub Actions settings  
D. Issues settings  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** 2FA enforcement is managed at the organization level.

**Reference:** https://docs.github.com/en/organizations/keeping-your-organization-secure/requiring-two-factor-authentication-in-your-organization
</details>
