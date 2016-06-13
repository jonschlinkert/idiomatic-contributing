# idiomatic-contributing

Welcome! If you've never contributed to a GitHub project before, we hope this guide gives you the confidence to get started. If you're an experienced contributor, hopefully this guide will help you become a more effective contributor, or give you ideas for your own contributing guides. 

**Contributing to this project**

All contributions are welcome:

- If you're an experienced contributor, please consider sharing your wisdom in this guide. 
- If you're new to GitHub and/or open source development, your perspective is equally valuable (perhaps moreso). What questions do you have? What would make it easier for you to contribute? Let us know what's on your mind. 

## Table of contents

The following sections are planned. Any contributions or shared wisdom would be appreciated!

- [ ] Getting familiarized with a project
- [The 4 Details of Highly Effective Bug Reports](#the-4-details-of-highly-effective-bug-reports)
- [ ] Effective feature requests
- [ ] Contributing code
- [ ] Contributing documentation
- [ ] Other ways to contribute

## TODO

- [ ] add `.github` folder with `contributing.md` and `issue_template.md`

## The 4 Details of Highly Effective Bug Reports

### tldr

Always include the following essential details in every bug report:

1. [version](#version): what version of X were you using when you experienced the bug?
1. [description](#description): clear description of the bug, and minimum steps to reproduce it.
1. [error messages](#error-messages): paste any error messages into the issue or a [github gist](https://gist.github.com/)
1. [code](#code): paste any code necessary for reproducing the bug into the issue or a [github gist](https://gist.github.com/)

Always wrap error message and code in [gfm code blocks][gfm].

### Reasoning

Like you, maintainers have to make decisions about where to spend their time. Not only within a given project, but oftentimes across multiple projects. 

If you've experienced a bug and you want to make a report, keep in mind that a maintainer is more likely to act quickly to resolve an issue when it is clearly described and organized. Throughout the course of solving an issue, it's typical for a maintainer to ask for more information. But no one wants to have to ask for details that could have easily been shared up front. 


It's important to provide the minimum details necessary for core team members to evaluate the issue

For your issue to be resolved quickly, . 

This section explains why these details are important.

#### version 

**tldr**: Important! Always, always, always provide this detail in bug reports.

No matter how long you've been contributing to a project, or how familiar you are with the code and core team, every time a bug is reported, the first thing a core team member wants to know is: "What version were you using when you experienced the bug?". Core team members even ask one another for this detail when debugging. The bug you're experience may have alreay been fixed in a patch.

Providing this detail up front will make everyone happy. If you don't provide this detail, maintainers will have to ask you for it, which can be annoying for experienced maintainers who have had to ask for this crucial detail many times. 

#### description

Decribe the bug with all of the details necessary for others to understand the , along with:

- [ ] Expected behavior and actual behavior.
- [ ] Steps to reproduce the problem.

[description]

#### error message

```sh
# paste any error messages here
```

See GitHub's guide to [Creating and highlighting code blocks][gfm] for more details.


#### code

```js
// paste your code into a GFM code block like this. Be sure to use the 
// appropriate language label after the first code "fence"
```

See GitHub's guide to [Creating and highlighting code blocks][gfm] for more details.

[gfm]: https://help.github.com/articles/creating-and-highlighting-code-blocks/