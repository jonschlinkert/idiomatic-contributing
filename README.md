# Guide to Idiomatic Contributing

Welcome! The fact that you're here means you want to start contributing to open source projects, or you want learn how to be a better contributor. We applaud you for that, and hope you get the most out of this guide. But if you read no further than this section, here are the most important things to take away:

- Idiomatic contributing has more to do with relationships and communication than it does with code
- Conventions are often used in projects to make them easier to maintain. The more popular the project, the more difficult it is to "please everyone". You don't need to like a project's conventions, but it's important to respect them anyway. 

In other words: _Be considerate of a projects conventions, and kind to its humans, and you will go much further in your career as a developer_.

## Table of contents

The following sections are planned. Any contributions or shared wisdom would be appreciated!

- [What to expect from this guide](#what-to-expect-from-this-guide)
- [Contributing 101](#contributing-101)
  * [What is contributing](#what-is-contributing)
  * [Why should I contribute?](#why-should-i-contribute)
  * [Getting familiarized with a project](#getting-familiarized-with-a-project)
- [Effective Bug Reports](#effective-bug-reports)
- [Effective feature requests](#effective-feature-requests)
- [Effective pull requests](#effective-pull-requests)
- [Effective Contributing](#effective-contributing)
  * [Contributing code](#contributing-code)
  * [Contributing documentation](#contributing-documentation)
  * [Other ways to contribute](#other-ways-to-contribute)
- [Code of conduct and beyond](#code-of-conduct-and-beyond)
- [About](#about)

<br>
<br>
<br>

![separator](https://cloud.githubusercontent.com/assets/383994/16028940/48225e8e-31b2-11e6-8170-6eea6574a7a6.png)

<br>
<br>
<br>

## What to expect from this guide

This guide won't teach you how to use git, or GitHub, or any specific frameworks or tools. There are many other resources available for those things. This guide isn't a replacement for a project's `contributing.md` file either. If you find this guide to be useful, we encourage you to link to it from your project's readme and `contributing.md` files.

If successful, this guide should achieve the following, depending on your level of experience:

- **new to open source**: As the saying goes, "competence breeds confidence". If you've never contributed to an open source project before, this guide will give you the information you need to get started. Confidence will arrive with experience.
- **experienced**: If you're an experienced contributor, hopefully this guide will help you become a more effective contributor, or at very least give you ideas to use in your own contributing guides. 

<br>
<br>
<br>

![separator](https://cloud.githubusercontent.com/assets/383994/16028940/48225e8e-31b2-11e6-8170-6eea6574a7a6.png)

<br>
<br>
<br>

## Contributing 101

### What is contributing? 

There are many ways to contribute to an open source project, including:

- Updating or correcting documentation
- Feature requests
- Submitting bug reports

But you aren't limited to these things. Use your imagination! If you like a project, and you see something that can or should be improved, then you have an opportunity (but not an obligation) to contribute. 

### Why should I contribute?

Regardless of the details, being an effective contributor means that you're _adding value_ to a project.

Here are just a few of the advantages of adding value to a project:

- you gain the appreciation and respect of the project's maintainers and community
- you gain valuable experience, and learn valuable collaboration skills
- you get noticed by job recruiters
- you become more attractive as a candidate to potential employers
- increase "street cred" with peers
- you might even make some new friends along the way

### Getting familiarized with a project

Before you attempt to contribute to a project, take a moment to get familiarized with it. In most cases you can learn all you need to know within a couple of minutes. 

#### Required

The following items are a pre-requisite for contributing to any project. Avoid creating issues or doing pull requests until you've done all of these things:

- **Review the readme**: Oftentimes a project readme has links to documentation, advice on creating issues or bug reports, and so on.
- **Read contributing guidelines**: look for a `contributing.md` file and, if one exists, read it in its entirety before creating issues or doing a pull request. Typically this is in the root of the project, but it might be in `.github/contributing.md`
- **Search issues**: Before creating bug reports, feature requests, or submitting issues of any kind, you should always search for existing issues (closed or open) that address the same thing.
- **Search google (or whatever search engine you prefer)**: Oftentimes a quick google search will turn up information that won't show up in a GitHub search. This reminds me of something I personally experienced recently. I was about to create an issue on a project I use to ask a question about a feature. It seemed unlikely that other users were using this project for the same thing as me, so I almost didn't do a search for existing issues first. I went ahead and searched googla anyway, and as it turned out, not only did other users wonder about the same thing, but there were several complete blog posts dedicated to answering the question I had.

#### Recommended

- **Review unit tests**: one of the best ways to get familiarized with a project is through its unit tests. Of course, this depends on the type of project, complexity, test coverage, and so on. But when applicable, test are often a good source of insight.
- **Get familiarized with the code**: If the codebase is small, and you're familiar with the language, take a moment to review the code to see if you find anything that can be improved. If the codebase is large, this provides even more opportunity to add value. You might be able to provide domain expertise or fixes for specific areas. If you want to add value to a big project, don't shy away from contributing because you aren't sure where to start with the code. Instead, if the project's contributing guide doesn't cover this already, create an issue and ask the maintainers to point you in the right direction. 
- **Ask questions**: Depending the project type and size, it might be good to start by searching google to find anwers to your questions. Then, check to see if the project uses [gitter](https://gitter.im) or has a [slack](https://slack.com/) channel, or something similar. Also visit [stackoverflow](https://stackoverflow.com) and do a search to see if others have already asked the same question. As a last resort, create an issue on the project's GitHub repository.

<br>
<br>
<br>

![separator](https://cloud.githubusercontent.com/assets/383994/16028940/48225e8e-31b2-11e6-8170-6eea6574a7a6.png)

<br>
<br>
<br>

## Effective Bug Reports

### Prerequisites

The most important detail to consider when creating a bug report is whether or not you should create one at all. 

**Do research first**

Did you research existing issues, closed and open, to see if other users have experienced (and potentially already solved) the same issue you're having?

Also make sure you search Google and [StackOverflow](https://stackoverflow.com) to see if users outside of the GitHub community have discussed the issue.

**Describe the problem, don't jump to conclusions**

Another maintainer and I were discussing this topic recently. We wondered how many issues we've handled that were created with the word "bug" in the title, or something along those lines that ended up being user error or were definitely not a bug. This is a guesstimate, but I think it's conservative to say that only 1 out of 10 reports with "bug" in the title has actually ended up being a bug. 

Even if you determine that what you're experiencing is absolutely a bug, it's always better to use a title and wording that describes the actual problem you're having, instead of describing it as a bug. Labeling an issue as a bug is better left to the project's maintainers. 

_However, the exception to the rule_ is when a project requires labels to be added to issue titles, and the only suitable label is "bug". In these situations, it's better to follow the rules.

### 4 Important Details

When a bug report is warranted, the vast majority of bug reports should include the following four bits of information: 

1. `version`
2. `description`
3. `error messages`
4. `code`

**Rationale**

The easier you make it for a maintainter or members of the community to react, the more likely it is for them to react quickly. 

Like you, maintainers have to make decisions about where to spend their time. Not only within a given project, but oftentimes across multiple projects. If you're experiencing a bug and you want to make a report, bug reports that are clearly described and organized are much more likely to get addressed by the maintainers or member of the community.

Providing these details up front will make everyone happy. If you don't provide these details, maintainers will have to ask you for them, which can be annoying for experienced maintainers who have had to ask for these crucial details many times. 

**The details**

Always include the following essential details in every bug report:

1. [version](#1-version): what version of X were you using when you experienced the bug?
2. [description](#2-description): clear description of the bug, and minimum steps to reproduce it.
3. [error messages](#3-error-messages): paste any error messages into the issue or a [github gist](https://gist.github.com/), and be sure to wrap the error messages in [gfm code blocks][gfm].
4. [code](#3-code): paste any code necessary for reproducing the bug into the issue or a [github gist](https://gist.github.com/), and be sure to wrap the code in [gfm code blocks][gfm].

Let's review the details in more... detail.

#### 1. version 

Always, always, always provide the version you're using in bug reports. This can't be overstated.

_(No matter how long you've been contributing to a project, or how familiar you are with the code and core team, every time a bug is reported, the first thing a core team member wants to know is: "What version were you using when you experienced the bug?". Core team members even ask one another for this detail when debugging. The bug you're experience may have alreay been fixed in a patch.)_

#### 2. description

Decribe the bug with all of the details necessary for others to understand what's happening, including:

- [ ] Expected behavior and actual behavior.
- [ ] Steps to reproduce the problem.

[description]

#### 3. error message

```sh
# paste any error messages here
```

See GitHub's guide to [Creating and highlighting code blocks][gfm] for more details.

#### 4. code

```js
// paste your code into a GFM code block like this. Be sure to use the 
// appropriate language label after the first code "fence"
```

See GitHub's guide to [Creating and highlighting code blocks][gfm] for more details.

[gfm]: https://help.github.com/articles/creating-and-highlighting-code-blocks/


### Effective feature requests

Before submitting a feature request, try to get familiarized with the project. Find out if the project has certain goals, or guidelines that describe how feature requests should be made. 

### Effective pull requests

WIP

It's not unusual for the maintainers of a project to ask you to make changes to your pull request. Here are some common reasons:

- Code formatting doesn't following the project's stated or established standards 
- Code isn't commented according to the project's stated or established standards
- Grammatical mistakes or typos
- Missing unit tests

Whatever the reason, it's up to you to decide whether or not to make the changes, and it's up to the maintainers to decide whether or not to merge your pull request. 

If you do decide to make any changes requested by the maintainers, you might find this [guide to ammending commits][ammending-commits] useful.

## Effective contributing

### Contributing code

TODO

### Contributing documentation

TODO

### Other ways to contribute

**Adding value takes time**

Depending on your personal goals, keep in mind that it might take longer and require more time committment to add value to a larger project than it would for a small project. 

If you want to become a respected and valuable member of a popular project, consider time investment made by the current maintainers and the project's creator. It's reasonable to expect that it will take some time to become familiar with the project's codebase. Review the project's unit tests. Read the docs. Try to understand the project's goals and direction, and try to get to know the current maintainers and community. 

**Show your support**

Sometimes we find a project we like but just don't have time to contribute. That's okay, there are other ways to show support:  

- Star the project
- Tweet about it
- Tell your friends
- Do a talk about the project at local meetups

**Show your appreciation**

Maintainers are people too. You can make someone's day, and even inspire and motivate them to keep doing a great job, by letting them know you appreciate their work. If you use a library in one of your own projects, let the author know you care:

- Add a "shout out" with a link to the project on your project's readme
- Say "thanks" on twitter

<br>
<br>
<br>

![separator](https://cloud.githubusercontent.com/assets/383994/16028940/48225e8e-31b2-11e6-8170-6eea6574a7a6.png)

<br>
<br>
<br>

## Code of conduct and beyond

### Do

- Politely and respectfully ask for clarification if you don't understand or agree with a maintainer's answers or feedback. 
- Remember that humor is very difficult to convey in written form (I seem to fail on this one a lot)
- Ask for feedback and code reviews from peers. Collaboration leads to faster solutions, shows humility, and results in mutual respect.
- Try to build lasting relationships

### Don't

- Ask if a project is still being maintained. To a maintainer, this is amongst the most insulting questions you can ask. Especially in light of the fact that a written library or well-maintained project will require far less activity. A lot of activity is not always a sign of health. 
- Ask "Why hasn't this been fixed?" on a project's GitHub issues. Questions like this are extremely insulting to a project's maintainers. Remember that FOSS (free and open source software) is, in fact, free and open source. Sometimes contributors do so on their own spare time, other times companies subsidize time spent on FOSS. But in both cases the software is free to you, and you are not entitled to an answer to this question. 
- Tell other users they are "bikeshedding" (or other similar tactics) to force an end to conversations on pull requests or issues. Telling another user that they are bikeshedding is equivalent to telling them: "What you're saying is not important to me", which is contentious at best, offensive at worst. Instead, whether you are a user or a maintainer, if you feel like you're "finished" with a conversation that users seem interested in continuing, it's better to avoid commenting at all. Or, if you feel it's necessary to comment, try to bring the discussion back on topic by restating goals or reminding users what's important about the issue at hand. 
- Email maintainers directly with questions about a project, requests for help, or suggestions for a project. Once you've established a relationship with the maintainers this might be okay, but it's frowned upon otherwise. Even once you establish a relationship, it's often better to have these discussions in the open, so that other community members can benefit from the dialog.


***

TODO:

- dealing with rejection (Sometimes we try to contribute to a project and it doesn’t work out)
- attribution and respecting copyrights

<br>
<br>
<br>

![separator](https://cloud.githubusercontent.com/assets/383994/16028940/48225e8e-31b2-11e6-8170-6eea6574a7a6.png)

<br>
<br>
<br>

## Resources

**Resources mentioned in this guide:**

- [Guide to Ammending Commits][ammending-commits]

**Related information:**

- [Awesome contributing guides](https://github.com/jonschlinkert/awesome-contributing): Curated list of awesome `contributing.md` guides

<br>
<br>
<br>

![separator](https://cloud.githubusercontent.com/assets/383994/16028940/48225e8e-31b2-11e6-8170-6eea6574a7a6.png)

<br>
<br>
<br>

## About

### Contributors

If you contribute to this project, thank you! Please add your name to the following list:

**Blake Embrey**

* [github/blakeembrey](https://github.com/blakeembrey)
* [twitter/blakeembrey](http://twitter.com/blakeembrey)

[your name here!]

### Contributing to this project

Please visit the [contributing guide](.github/contributing.md) to learn more about contributing to this project.

### Authors

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

**Brian Woodward**

* [github/doowb](https://github.com/doowb)
* [twitter/doowb](http://twitter.com/doowb)

## License

Released under [Creative Commons](LICENSE).
Copyright © 2016, [Jon Schlinkert](https://twitter.com/jonschlinkert).

[issue-templates]: https://github.com/blog/2111-issue-and-pull-request-templates
[ammending-commits]: https://github.com/RichardLitt/docs/blob/master/amending-a-commit-guide.md
