# E& IoT Development 
```
Dear Team, 
Welcome to E& IoT Development repository! 🎉

As we collaborate on projects, it is essential to adhere to the principles and guidelines
outlined in this document. These guidelines are designed to ensure consistency, efficiency,
and high-quality results across all our work. 

Please make it a habit to follow these practices, and feel free to provide suggestions for
improving our workflows and principles whenever necessary. Your contributions and commitment
to these standards will significantly enhance our productivity and collaboration.

Thank you for being an integral part of this team!

- Siv <ssugaman@eand.com>
```
<br/>

**❗Urgent changes**
> Currently, there are a large number of repositories in the organization, with a minimum of three per project. To improve maintainability and reduce complexity, we must transition to a mono-repo structure. A refactoring initiative should be undertaken to consolidate multiple repositories into mono-repos where feasible.

## Repository Guidelines

###  Mono-repo Structure:

- Use a mono-repo for each team or major project.
- Each repository should be self-contained with clear folder structures.

### Naming Conventions:
Start repository names with a standard prefix, e.g., `XXX-` to identify your team's repos.

Example:
- XXX-project-name
- XXX-toolkit

#### Repository Structure:
```
/root
|-- src/            # Source code
|-- tests/          # Unit tests
|-- docs/           # Documentation
|-- scripts/        # Utility scripts
|-- .github/        # GitHub actions and workflows
|-- README.md       # Overview of the repository
```
### Development Workflow

#### Branching Strategy:
1. Use main as the default branch for production-ready code.
2. Use feature branches for new developments: feature/feature-name.
3. Use hotfix branches for bug fixes: hotfix/fix-name.

#### Pull Request (PR) Workflow:
- Create PRs for all code changes.
- Use templates for PRs to ensure quality and consistency.

#### PRs must include:

- Clear description of changes.
- References to relevant issues (if any).
- Evidence of tests passing (e.g., screenshots, logs).
- Require at least one reviewer to approve PRs.


### Documentation

#### Code Documentation:
- Use **comments** to explain complex logic.
- Follow JSDoc or similar standards for documenting functions and modules.

#### Project Documentation:
- Maintain a `docs/` folder with project-specific documentation.
- Use markdown files for ease of use.

#### Onboarding:
Include an `ONBOARDING.md` in every repo to help new contributors get started.

#### Continuous Integration/Continuous Deployment (CI/CD):
Set up GitHub Actions for automated _builds_, _testing_, and _deployment_.

Example GitHub Action Workflow:

- **Build**: Ensure the code compiles.
- **Test**: Run all unit tests.
- **Lint**: Ensure code adheres to style guidelines.
- **Deploy**: Trigger automated deployment upon merging into main.


