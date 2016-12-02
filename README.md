# Design documentation starter site

This is a simple [Jekyll](http://jekyllrb.com) design documentation site based on [Hyde](http://hyde.getpoole.com/)/[Poole](http://getpoole.com). I've started the site out with some key pages and tag grouping (research).


## Setup

This project uses GitHub pages and is set up so that you can edit files locally, sync the changed files with GitHub.com, and allow GitHub pages to render the Jekyll, so that you do not need to run Jekyll locally. These instructions assume you’re using the GitHub desktop client and have a GitHub.com account.

- Install [GitHub Desktop client](https://desktop.github.com/) if you don’t already have it.
- Fork [this repo](https://github.com/18F/test-docsite) to your account or team.
- Clone the repo by clicking the green button, choosing _Open in Desktop_ from the menu. (I have created a _Sites_ directory inside my Mac user directory, along side Documents, Downloads, etc. where I keep my local repos.)
- On the _Settings_ tab, change the _Repository name_ to the name of your choice.
- On the _Settings_ tab, in the _GitHub Pages_ section, change the _Source_ to “master branch”.
- The site should now be visible at https:_username_.github.io/_reponame_ (replacing the italicized text with your username/team name and repo name). Note: the links will point to the original repo, so we’ll change that now.)
- In a text editor such as [Atom](https://atom.io/), locate your local copy of the repo and open the `_config.yml` file.
- in the _Setup_ section, replace the title, tagline, description, url, and baseurl. The url and baseurl values need to be changed to point to your new site’s location which should follow the _username_.github.io/_reponame_ convention. Further down you can also change the _repo_ value to point to your github.com repo’s URL. Save these changes.
- Open GitHub for Mac client. You should be able to select your local copy of the repo from the menu on the left. Select the repo. Select “master” from the branch selection menu near the top left.
- You should see an uncommitted change. Add a brief commit summary and click “Commit to master”. Then, at the upper right, click the “Sync” button to push the changes up to github.com. You links should not be correct and your site working.

## Usage

**Posts** are written in [markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/) and found in the `_posts` directory. You’ll see there are a number of dummy posts already there. Notice the file naming convention defines the posts’ publish date. Remove of edit the posts as you’d like.

The post named `_posts/2012-02-07-example-content.md` shows a variety of text formatting options.

If you open a post in your text editor, you’ll see some information near the top that’s sectioned off. This is the **YAML front matter. This is metadata about your post. You define the post’s title there.

Some posts include **tags** in the YAML front matter. In this example, a few posts have “research” as a tag, which allows those posts to be included on the Research page (see research.md).

There are a few **pages** included in the root directory. These are just static pages and not chronological in nature, as posts are. They are also written in markdown. These pages can be edited or removed. They have been linked to from the sidebar ( found in `/_includes/sidebar.html` ).

The _Research_ page has been set up as a page for listing all posts that are tagged “research’. You can use this as an example for making other tag category pages.
