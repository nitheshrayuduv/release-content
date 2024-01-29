- Summary: This pull request addresses [briefly describe the purpose or issue being addressed].

**Version information**
- [ ] Tested against target systems and versions: _FILL IN TARGET SYSTEMS AND TARGET SYSTEM VERSIONS HERE_
- [ ] Tested with Digital.AI Release version: _FILL IN DIGITAL.AI RELEASE VERSION AND PLUGIN VERSIONS HERE_

**Review**

- [ ] Check for proper folder structure and versioning settings if a new subfolder is added under workflows.
- [ ] Ensure `autoImport` is set to `true` for the workflows folder versioning settings.
- [ ] If adding a new workflow, update the `Releasefile.yaml` for proper Digital.ai Release import.
- [ ] Avoid using community plugins.
- [ ] Do not use global or folder variables.
- [ ] Confirm that variables follow the correct naming convention (camel case or snake case) and have appropriate labels and descriptions.
- [ ] Workflows should have accurate titles and descriptions.
- [ ] Verify that all phases and tasks have correct titles and descriptions.
- [ ] Ensure the change fulfills and explains the business requirements properly.
- [ ] Place the workflow in the correct folder based on its category, and ensure that proper documentation accompanies it.

**QE**

- [ ] Confirm that the changes can be successfully imported into Digital.ai Release without any breaking issues.
- [ ] Generate a workflow execution from the newly added or updated workflow and verify that there are no failures.

**PR Merge Activity**

- [ ] Squash and merge the PR.
- [ ] After the PR is merged, make sure to push the appropriate tags on the main branch to reflect the changes in customer installations.