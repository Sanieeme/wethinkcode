# wethinkcode
my first wethinkcode repo
pre academic plan
I was able to create an account on GitLab successfully. Since I’m already familiar with GitHub, navigating GitLab wasn’t too difficult. 
However, I made sure to read through all the provided information to deepen my understanding. 
While GitLab and GitHub share similarities, they are not the same, and it's important not to assume that prior knowledge of one automatically means mastery of the other.

I reminded myself to approach this with a learner’s mindset—not to assume I know everything just because I understand the basics. That mindset proved helpful, as I discovered several new concepts and tools unique to GitLab.

In addition to the Git commands I was already familiar with—such as git clone, git add, git commit, git push, git pull, git merge, git branch, git status, and git fetch—I’ve now learned about many more Git commands and their capabilities. 
It’s exciting to expand my toolkit and gain a deeper understanding of what Git can do. 
This has been a valuable learning experience, and I look forward to applying this knowledge in real-world projects.


**THESE ARE THE THINGS THAT I HAVE LEARNT:**


GITLAB FLOW:
gitlab flow helps in turning idea to real solution. there are steps to follow which inlude:
step 1: create an issue -> step2: create a merge -> step3: commit changes->step4: CI pipeline runs->step5: Review Apps->step6: Peer Review and discussion->step7: Approve changes->step8: Merge; Issued closed; CD Pipeline runs-> step9: Monitor

CODE REVIEW- Typical Workflow

The change is reviewed using the following:
New merge Request -> Assign and review -> final Assignment -> final Review -> Merge Approved
additional tools for code review and collaborations are: snippets, wikis and web IDE


SETTING UP your organization in GitLab

Key things to remember

>GitLab Projects are housed within **Groups**

>Groups can have any number of **Subgroups**

>Permissions are inherited down from the top-level groups, so add users with the least permission and give them higher permissions at the Subgroup or Project level

>Labels and Milestones created at the top-group level and are available to all Subgroups and Projects so add shared labels at the highest level possible

**group -> subgroup -> project -> issue -> comment; participants; assignment**

GitLab and Group Visibility
**Private; Internal and Public**

**GitLab EPIC**
is a way to group related tasks or issues tother in gitlab
you can also group other epics inside an epic for even bigger planning

Group Epic
Key things to remember

Epics are defined at the Group level.
Epics can contain both issues and epics as children.
Epics can be used as a filter in issue lists and issue boards.
Epics provide visibility on child epics, issue statuses, and the roadmap timeline.
Epics do not have an Assignee.
Epics cannot be created in Projects.

Parent Epic

you can make epics private so that people with access can see them and they aka confidential epics
they are useful when you want to keep security isseues secret and hide infomation from the public+

GITLAB ISSUES
isssues is a way to write down and track a task, idea, or problem.
use issues to plan new features  or anything that needs to be done
it helps teams work together and stay organized
issues are used tolink it to epics, merge requests or milestones and it add labels, dates or show it on a roadmap or board.

You can also use issues for:
Discussing the implementation of a new idea
Managing an incident
Asking questions
Reporting bugs

key things to remember

Issues are defined in the scope of a Project, not a Group.

KEY THINGS TO REMEMBER
Issues only exist in projects. While Groups have boards that manage issues and lists of issues, the issues always are stored in a project that is subordinate to the group.
GitLab Groups do not have issues. Groups have Epics.
An issue can only be the child of a single epic.
Limitations: An issue cannot be added to more than one Milestone.

here are many detailed parts of an issue, such as: 

Time tracking 
Weight 
Participants and notifications 
Mentions 
Related issues 
Related Merge Requests 
Comments 

Quick Actions are effectively commands that make it easy and efficient to change an issue such as:

/assign followed by a user ID, will assign the issue to a person
/close will close an issue
/duplicate followed by an issue number will close the current issue as a duplicate and link to the given (open) issue

LABELS IN GITLAB
labels are like tags you add to epics, issues or merge requests to help orginize and find them easily
labels are used to show things like priority, status, type and help search and filter items quickly, group similar tasks and keep track of your work

Scoped Labels are used to:

* Assign status
* Support workflows
* Segment items into "either / or" situations

Key things to remember

There are two types of labels in GitLab:

* Project labels can be assigned to Issues and Merge Requests in that project only.
* Group labels can be assigned to Epics, Issues and Merge Requests in any project in the selected Group or its Subgroups.
* Create Labels at the lowest possible level.
* Group-level Labels should only be used for tracking at the Group level, across multiple projects and/or subgroups.

assign and unassign labels with quick actions:
* assign labels with /label
*remove labels with /unlabel
* remove all labels and assign new ones qith /relabel

