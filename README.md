# FMYI (Mostly a note for myself)
1. Steps to publish (TL;DR: Work on blog-staging, copy locally built site elsewhere, push built to master)
Because of the Jekyll plug-ins, I'm opting on building the jekyll site locally and pushing the built html statics to master to be served by GitHub to my site.
2. Blog tags
3. Formats

# Steps to publish (TL;DR: Work on blog-staging, copy locally built site elsewhere, push built to master)
1. Checkout blog-staging on git to write the blog post.
2. Commit and push blog-staging branch to origin.
3. (Doesn't have to be in this order) bundle exec jekyll serve to build the site.
4. Copy the built site and .DS_Store to a folder.
5. Checkout master.
6. Write over with the copied info from step 4.
7. Commit and push master branch to origin.

# Blog Tags to Consider
1. How-to
2. Readings
3. Thoughts

## Sub-categories:
1. Communication
  - Conflict resolution
  - Change management
  - Meeting management
2. Motivation
  - Employee engagement
  - Employee empowerment
  - Stress management & mental health
  - Leading innovation
  - Team performance and wellbeing
3. Planning
  - Time management
  - Execution management
  - Delegation
  - Productivity
  - Manage v. Lead
5. Relationships
  - Building trust
  - Effective coaching and feedback
  - Goal setting
  - Collaboration on problem solving

# Formats to Consider
- How-to
  - Listicles
  - How To's
  - "Flips": snappy learnings on each flip
  - "Table of contents": series of blogs that are stitched together in view. Lengthier than Flips
- Manager-toolkit
  - Infographics
  - Quizzes
  - Checklists
  - Case studies
- Further-learning
  - Resources review & analysis: books, videos, podcast episodes, articles
- My-view
  - Q&A
  - Stories
  - "Tiny thought"
