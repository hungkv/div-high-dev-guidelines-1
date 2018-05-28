## Code Review
  ### Benefit of code reviews
    - Reduce bugs: Bugs maybe grow during developers implement new features. Code reviews will reduce the amount of those bugs
    - Code quality: Codes that are reviewed by reviewer will more readable, easy to maintain, good performance.
    - Share knowledge: Member of our team can learn from each other while review(or are reviewed) other's PR
  ### Workflow
  ![review_workflow](https://user-images.githubusercontent.com/2276767/40638200-024f6a5e-6334-11e8-9454-751efeaee27c.jpg)
   #### Step 1: Create pull request and request review
     - After implementing a feature, developer creates new pull request
     - Make sure the pull request has enough document that make reviewers easy to understand what do you want to do.
     - Include automation test in your changes to make sure your code works
     - Make sure pull request pass CI checking(if using CI)
     - Inform reviews via Chatwork or slack with link of pull request
     - Update the checklist (When start project, we should create checklist file and use it for all reviews).
   #### Step 2: Review code and feedback
     - Review pull request follow checklist.
     - Reviewers submit small comments for issues that they recognized.

   #### Step 3: Fix discovered issues and finalize the review
     - After fixing discovered issues, commit and push updates the pull request.
     - Make sure pull request pass CI checking(if using CI) again
   #### Step 4: Approve pull request and merge it!
     - When all work is done, reviewers will approve the pull request
     - Pull request is only merged by person in charge when have at least 2 approvals from reviewers.
     - Depending on each project, pull request sender may have right to merge the pull instead of team leader or similar role
     
