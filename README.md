## Blog Publishing FYI (Mostly a note for myself)

Because of the Jekyll plug-ins, I'm opting on building the jekyll site locally and pushing the built html statics to master to be served by GitHub to my site.

## Steps

1. Checkout blog-staging on git to write the blog post.
2. Commit and push blog-staging branch to origin.
3. (Doesn't have to be in this order) `bundle exec jekyll serve` to build the site.
4. Copy the built site and .DS_Store to a folder.
5. Checkout master. 
6. Write over with the copied info from step 4.
7. Commit and push master branch to origin.
