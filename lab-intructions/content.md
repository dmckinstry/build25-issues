# Issued & Projects lab - Build 2025

**Abstract: _Learn how GitHub Issues and project planning capabilities balance structure and flexibility for complex software development. Get hands-on with the redesigned GitHub Issues experience and other enhancements and discover practical techniques for leveraging markdown-based issue templates and custom sections that adapt to your team's unique workflows. Perfect for developers and DevOps practitioners seeking to streamline collaboration without sacrificing visibility or accountability._**

## Lab Setup
1. TBD
   - Ensure VM and GitHub account access
   - Copy/Fork source repo
   - Run appropriate automation to setup whatever is needed
   - Open a browser and navigate to [your GitHub lab repo](https://github.com/dmckinstry/build25-issues).

## Working with GitHub Issues
_In this section you'll learn the basics of GitHub issues, including issue creation, issue templates, working with labels and milestones, assignment, querying issues, issue hierarchies, issue types, and cross-repo collaboration._

2. Getting started with GitHub Issues
   - [ ] Create your first issue, based on the "Build Lab-Issue Basics template" issue template using the default settings.
         <details><summary>Step details</summary>
          <nl>
            <li>Click the <b>Issues</b> tab in the top navigation bar of your GitHub repo in the browser (Possible image).</li>
            <li>Click the green New Issue button on the right side of the bwoser screen (possible image).</li>
            <li>Review markdown used in the <b> Description</b> to format content. If you aren't already familiar with markdown you can refer to the <a href="https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github">GitHub docs</a> for more information.</li>
            <li>Click the green <b>Create</b> button near the bottom of the window.  The template you selected already had everything filled out so you dont' need to make any changes.</li> 
          </nl>
        </details>

   - [ ] Assign the new issue to yourself.
   - [ ] Apply the "feature request" label to your new issue.
   - [ ] Apply the "tbd" milestone to your new issue.
   - [ ] Query issues to find and filter this issue and others in your repo.
   - [ ] Verify automation triggered by issues
2. Structuring GitHub Issues
   _Most development teams need more than simple issues to manage development procedures. We've prepopulated a few more issues in your repo so that you can apply issue types and parent/child relationships._
[[PREPOPULATE A "Investigate linking issues to code" and add the batch as a parent]]
   - [ ] Create a new issue titled "Apply structure to GitHub Issues" using the blank issue template.
   - [ ] Apply the "Task" type to the new issue.
   - [ ] From the list of all issues, open the "Investigate Issue Basics" issue and apply the "Task" type.
   - [ ] Add the "Batch to track learning GitHub Issues" issue as the Parent relationship of the "Investigate Issue Basics" issue
   - [ ] Navigate to the "Batch to track learning GitHub Issues" from the open task.
   - [ ] Add the existing "Apply structure to GitHub Issues" task to the open batch.
   - [ ] Add a new child task "Verify Issue Hierarchy" to the existing Batch. [[<-- prepopulate?]]
   - [ ] Add the "TBD" parent issue to the batch.  Note that this Epic can be found in the TBD/TBD repo.
3. Linking Issues to Code
   - [ ] Create a something PR (maybe already have the branch and code change?) with the "closes" ref.
   - [ ] Close and merge the PR.
   - [ ] Review the TBD issue
3. Lab Verification
   _At this point you should have a batch similar to the following:_
   [SCREEN SHOT TBD]
   - [ ] Verification complete!
   - [ ] Close the "Batch to track learning GitHub Issues" batch and all child tasks.

## Managing work with GitHub Projects

4. [ ] Project Fundamentals
    - Create a new project
      - Purpose=TBD, template=TBD
    - Add existing Task issues (only tasks at this point - will show more with views)
    - tbd - States and Fields??
5. [ ] Working with Project Views
   - TBD
6. [ ] Intro to Project Automation
   - Add automation for "new item in your repo" and exercise it with a new item
   - Add automation for "Closed means complete"
   - Add a new issue and verify the automation
   - Close the issue and verify the automation
   - ?? (Bonus) Possible advanced automation with existing

7. Insights on your Projects
   - TBD
