# Gatsby Challenge

This challenge is designed to test your ability to use [Gatsby](https://www.gatsbyjs.org/) and [Netlify CMS](https://www.netlifycms.org/). Starting with the [gatsby-starter-netlify-cms](https://github.com/netlify-templates/gatsby-starter-netlify-cms) project, you should make some additions and changes:

* Create a new page type: History
* Modify the fields of an existing page type: Blog
* Allow an admin user to add a custom script tag to a Blog page

## Rules

* **Do not fork this repo**
  * Create a new repo in your account and note the git url
  * Clone this repo
  * Set your new repo as the origin `git remote set-url origin ${your repo url}`
  * Push
* Deploy your repo to [Netlify](https://netlify.com)
* Set up Identity service. Leave your site registration open to let any user sign in with email
* Create a page with new collection, "History", and add two articles to it using content from `history1.md` and `history2.md`
* Add a new field, named "Script", to the "Blog" collection
* An editor of the site should be able to add a JavaScript tag to the page using this new "Script" field
* Be sure that this works properly and the tag is added to the page and executes for visitors
* For example, an editor should be able to paste the following into the field and see the alert when visiting that page:

`<script>
    window.alert('The most dangerous drinking game is seeing how long I can go without coffee')
</script>`

* Once you have completed the challenge, send your hiring contact the link to your Github repo and your deployed Netlify site
