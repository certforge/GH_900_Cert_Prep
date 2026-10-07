# Practice Questions - Domain 4 (Modern Development)

### Question 1
**Domain**: Domain 4 - Modern Development  
**Topic**: Workflow Structure  
**Difficulty**: Beginner  

Where are GitHub Actions workflows stored?

A. `.github/actions/`  
B. `.github/workflows/`  
C. `.github/scripts/`  
D. `.git/workflows/`  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Workflows are YAML files in `.github/workflows/`.

**Reference:** https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions
</details>

### Question 2
**Domain**: Domain 4 - Modern Development  
**Topic**: Action Types  
**Difficulty**: Beginner  

Which action type runs using `using: 'composite'` in `action.yml`?

A. JavaScript action  
B. Docker action  
C. Composite action  
D. Reusable workflow  

<details>
<summary>Answer</summary>

**Correct Answer:** C

**Explanation:** Composite actions combine multiple steps in one reusable action.

**Reference:** https://docs.github.com/en/actions/creating-actions/creating-a-composite-action
</details>

### Question 3
**Domain**: Domain 4 - Modern Development  
**Topic**: Artifacts  
**Difficulty**: Beginner  

Which action is used to upload build output for later download?

A. `actions/cache`  
B. `actions/download-artifact`  
C. `actions/upload-artifact`  
D. `actions/checkout`  

<details>
<summary>Answer</summary>

**Correct Answer:** C

**Explanation:** Artifacts are uploaded with `actions/upload-artifact`.

**Reference:** https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts
</details>

### Question 4
**Domain**: Domain 4 - Modern Development  
**Topic**: Triggers  
**Difficulty**: Beginner  

Which event trigger allows manual runs with inputs?

A. `schedule`  
B. `workflow_dispatch`  
C. `workflow_call`  
D. `release`  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** `workflow_dispatch` provides manual runs and inputs.

**Reference:** https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows
</details>

### Question 5
**Domain**: Domain 4 - Modern Development  
**Topic**: Tokens  
**Difficulty**: Beginner  

What is `GITHUB_TOKEN`?

A. A personal access token stored in secrets  
B. A token generated for each workflow run  
C. A permanent token for org admins only  
D. A token for GitHub Packages only  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** `GITHUB_TOKEN` is auto-generated for each workflow run.

**Reference:** https://docs.github.com/en/actions/security-guides/automatic-token-authentication
</details>

### Question 6
**Domain**: Domain 4 - Modern Development  
**Topic**: Marketplace  
**Difficulty**: Beginner  

What does the Verified Creator badge indicate in GitHub Marketplace?

A. The action is owned by GitHub only  
B. The publisher identity has been verified by GitHub  
C. The action is open-source only  
D. The action has no dependencies  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Verified Creator indicates the publisher identity is verified.

**Reference:** https://docs.github.com/en/actions/learn-github-actions/finding-and-customizing-actions
</details>

### Question 7
**Domain**: Domain 4 - Modern Development  
**Topic**: Caching  
**Difficulty**: Beginner  

Which action is used to cache dependencies?

A. `actions/cache`  
B. `actions/checkout`  
C. `actions/setup-node`  
D. `actions/upload-artifact`  

<details>
<summary>Answer</summary>

**Correct Answer:** A

**Explanation:** `actions/cache` stores and restores dependency caches.

**Reference:** https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows
</details>

### Question 8
**Domain**: Domain 4 - Modern Development  
**Topic**: Workflow Dispatch  
**Difficulty**: Beginner  

Which file location is required for Actions workflows?

A. `.github/workflows/*.yml`  
B. `.github/actions/*.yml`  
C. `.github/ci/*.yml`  
D. `.ci/workflows/*.yml`  

<details>
<summary>Answer</summary>

**Correct Answer:** A

**Explanation:** Workflows must live under `.github/workflows`.

**Reference:** https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions
</details>

### Question 9
**Domain**: Domain 4 - Modern Development  
**Topic**: Reusable Workflows  
**Difficulty**: Beginner  

Which trigger enables a workflow to be called by another workflow?

A. `workflow_run`  
B. `workflow_call`  
C. `workflow_dispatch`  
D. `schedule`  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** `workflow_call` enables reusable workflows.

**Reference:** https://docs.github.com/en/actions/using-workflows/reusing-workflows
</details>

### Question 10
**Domain**: Domain 4 - Modern Development  
**Topic**: Permissions  
**Difficulty**: Beginner  

Where are default workflow permissions configured for a repository?

A. Actions tab run logs  
B. Repository settings under Actions  
C. Issues settings  
D. Pull request templates  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** Workflow permissions are configured in repo Actions settings.

**Reference:** https://docs.github.com/en/actions/security-guides/automatic-token-authentication#permissions-for-the-github_token
</details>

### Question 11
**Domain**: Domain 4 - Modern Development  
**Topic**: Codespaces  
**Difficulty**: Beginner  

What file defines the dev container configuration for Codespaces?

A. `docker-compose.yml`  
B. `devcontainer.json`  
C. `.github/workflows/ci.yml`  
D. `package.json`  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** `devcontainer.json` defines the Codespaces dev container configuration.
**Reference:** https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration
</details>

### Question 12
**Domain**: Domain 4 - Modern Development  
**Topic**: Runners  
**Difficulty**: Beginner  

Which runner type is managed and maintained by GitHub?

A. Self-hosted runners  
B. GitHub-hosted runners  
C. Ephemeral runners only  
D. Private runners only  

<details>
<summary>Answer</summary>

**Correct Answer:** B

**Explanation:** GitHub-hosted runners are provided and maintained by GitHub.
**Reference:** https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners
</details>
