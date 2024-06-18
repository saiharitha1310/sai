# Self-Learning Document on Git Project Dashboard, Agile, Scrum Calls, and Jira Management

## Git Version Control System
Git is a powerful and widely used version control system that plays a crucial role in software development and other collaborative projects. It allows developers to track changes in their code, collaborate efficiently, and revert to previous versions if necessary. Git's core functionality revolves around the concept of a repository, which is a central location where all the project files and their history are stored.

![Git Version Control System](https://miro.medium.com/max/1400/1*JdNb1hTRbzL2qvXxt1nKFg.png)
*GitHub Project Dashboard*

## Branching in Git
Branching in Git is a powerful feature that allows developers to work on different versions of a project simultaneously. Think of it like creating a copy of your project to experiment with new features, fix bugs, or try out different ideas without affecting the main branch of your code. Each branch is essentially a pointer to a specific snapshot of your codebase. When you create a new branch, you're essentially creating a new pointer that points to the same starting point as the main branch.

![Branching in Git](https://wac-cdn.atlassian.com/dam/jcr:213b39c8-2f43-4f42-bf0c-47e84d715aa0/03%20(2).svg?cdnVersion=576)
*Branching and Merging in Git*

## Merging in Git
Merging is the process of combining changes from different branches into a single branch. Git uses a three-way merge algorithm to determine how to combine changes. The algorithm compares the common ancestor of the two branches, the target branch, and the source branch to identify the changes that need to be merged.

There are two main ways to merge branches in Git:
1. **Fast-Forward Merges**: This happens when the target branch is a direct descendant of the source branch. In this case, Git simply moves the target branch pointer to the latest commit in the source branch.
2. **Non-Fast-Forward Merges**: This happens when the target branch has diverged from the source branch. In this case, Git creates a new merge commit that combines the changes from both branches.

![Merging in Git](https://wac-cdn.atlassian.com/dam/jcr:e166fcff-8a5e-4ec2-b97f-e18555a12478/07%20(1).svg?cdnVersion=576)
*Merging in Git*

## Resolving Conflicts in Git
Conflicts arise when multiple developers modify the same part of the codebase simultaneously. Git flags these areas as conflicts and prevents automatic merging, requiring manual resolution.

1. Use a merge tool like Git Merge tool or Visual Studio Code for easier visualization and conflict resolution.
2. Review the conflicting sections carefully, understand the intent of each change, and choose the best solution for your project.
3. After resolving the conflicts, you must stage the changes and commit them, indicating that you have resolved the conflict and are ready to merge the branches.
4. Once conflicts are resolved, the merge can be completed, and the changes from both branches will be integrated into the target branch.

![Resolving Conflicts](https://scrumorg-website-prod.s3.amazonaws.com/drupal/inline-images/2018-04/ScrumFramework_web.png)
*Resolving Conflicts in Git*

## Git Project Management Tools
Git project management tools, often referred to as Git hosting services, provide a central platform for managing your Git repositories and collaborating with others on code projects. These tools offer a range of features that streamline development workflows, enhance collaboration, and facilitate code management. Popular options include GitLab, GitHub, and Bitbucket.

### Features of Git Project Management Tools
1. **Repository Hosting**: Storing and managing your Git repositories in the cloud.
2. **Issue Tracking**: Tracking bugs, feature requests, and other tasks associated with your project.
3. **Code Review**: Facilitating code review and feedback processes between team members.
4. **Continuous Integration and Continuous Delivery (CI/CD)**: Automating building, testing, and deploying your code.
5. **Collaboration Tools**: Features like wikis, discussion forums, and team messaging to enhance communication and collaboration within teams.

![GitHub Issues](https://miro.medium.com/max/2400/1*skDRukcVsX6BiI1wn2KNhQ.png)
*GitHub Issues Interface*

### Basic Git Commands
- `git init`: Initializes a new Git repository in a directory.
- `git clone`: Creates a local copy of a remote repository.
- `git add`: Stages changes in files for inclusion in the next commit.
- `git commit`: Creates a snapshot of the staged changes with a commit message.
- `git status`: Shows the current state of the repository and any untracked changes.
- `git merge`: Combines changes from one branch into another.
- `git push`: Uploads local commits to a remote repository.
- `git pull`: Downloads commits from a remote repository and integrates them into the local branch.

![Basic Git Commands](https://www.visual-paradigm.com/servlet/editor-content/scrum-framework-overview.png)
*Basic Git Commands*

## Agile Methodology
Agile methodology is a way of approaching software development that emphasizes flexibility, collaboration, and customer feedback. Instead of planning out everything upfront, agile teams work in short bursts called sprints. They focus on delivering small, incremental improvements quickly and adjusting their plans based on feedback. This method allows teams to respond to changes more effectively and deliver software that better meets the needs of users.

![Agile Manifesto](https://upload.wikimedia.org/wikipedia/commons/0/0d/Agile_values_and_principles.png)
*Agile Manifesto*

### Benefits of Agile Methodology
- **Flexibility**: Agile allows teams to adapt quickly to changes in requirements or priorities.
- **Customer Satisfaction**: Regular feedback loops ensure that the product meets customer needs and expectations.
- **Faster Delivery**: Incremental releases mean features can be delivered sooner, providing value earlier.
- **Collaboration**: Team members work closely together and with stakeholders, fostering better communication and shared understanding.
- **Quality**: Continuous testing and integration help maintain high standards throughout the development process.

### Key Princip
