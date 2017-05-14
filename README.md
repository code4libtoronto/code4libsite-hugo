# Introduction

This repository is the Hugo Build for [code4libtoronto.github.io](http://code4libtoronto.github.io).

## Usage

If you want to build the site, run the deploy.sh script. From the instructions on the hugo site for using github pages:

```
./deploy.sh "Your optional commit message" to send changes to <username>.github.io (careful, you may also want to commit changes on the <your-project>-hugo repo).

```

Changes should be pushed to the [code4libtoronto.github.io repository](https://github.com/code4libtoronto/code4libtoronto.github.io)

## Content Editing Workflow

hugo new post/2017-11-01.md
cd content/post/2017-11-01.md
Make changes, edit metadata
hugo -t=after-dark
hugo server --buildDrafts
copy over to code4libtoronto.github.io repository
