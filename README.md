# faq
A repository of common questions and answers to reduce repetition on the r/cybersecurity community.

## Contribution Guide

1. File an [issue](https://github.com/r-cybersecurity/faq/issues) stating a question you believe should be answered on the FAQ. A project administrator will make sure that this question is relevant and that nobody is working on a similar question. They may also suggest rewording or a similar question. Once a question has been finalized, the moderator will approve you to work on answering the question. An example issue is [here](https://github.com/r-cybersecurity/faq/issues/1).
2. Once approved, you need a copy of this repository. In the upper right of the repository's [page on GitHub](https://github.com/r-cybersecurity/faq), there is a button called "fork." Select fork, and create a copy in your account. A copy will be available at `https://github.com/<your_account>/faq` or whatever name you chose for this.
3. Navigate to your copy. You can either work locally or directly on GitHub.
  * If you are working locally, and you are unfamiliar with git, please look at [this guide](https://rogerdudler.github.io/git-guide/). Start at "checkout a repository". However, this guide assumes you are going to use GitHub's web UI for this.
  * If you are working directly on GitHub, please click "Add file" and then "Create new file"
4. Set the filename! If your questions is "What laptop should I get for cybersecurity?", please name your file "What laptop should I get for cybersecurity.md" - so leave off the question mark, and add `.md` at the end. Just place all of these in the current directory.
5. Write your content! This needs to be written in [Markdown](https://www.markdownguide.org/basic-syntax/), which is a human-readable formatting language (Discord, Reddit, etc. use this - so you are probably already familiar), and is very easy to get started with. You can save the changes whenever you want (by clicking 'commit changes'), then click on the file again later, and click "edit" to continue. Content should follow this format, which makes a H2-size header with the question being asked (ex. What laptop should I get for cybersecurity?) and then your answer can be written afterwards. Example content is [here](https://raw.githubusercontent.com/r-cybersecurity/faq/main/What%20laptop%20or%20desktop%20should%20I%20buy%20for%20cybersecurity.md).
```
## What question is being asked?

1-3 paragraphs of content.
Enough to answer the question, but don't worry about covering EVERY possible case.
```
6. Review your content! You can do this in GitHub by clicking "Preview" in the upper left of the editor, and will show the output from parsing your Markdown. Please be sure to check for spelling and grammar errors, make sure that all links are correct, and that there are no formatting goofs.
7. Add a little signature after your answer if you like! You don't have to, but would be a nice way to get credit for the answer. This should be short and contain no personal information. For example:
```
Answered by u/tweedge ([blog](https://chris.partridge.tech/), [Twitter](https://twitter.com/_tweedge))
```
8. Don't forget to commit your changes! Green button at the bottom. "Working locally" folks - use the aforementioned guide to add and push your changes.
9. Once your content is ready, you should then create a new pull request. This will take a couple steps to do:
  * On your copy, click the "pull requests" tab. Then, click the green button on the right "New pull request"
  * GitHub will suggest the last branch to receive commits to the repository you forked it from. Therefore - merging `<your_account>/faq:main` to `r-cybersecurity/faq:main`. In human words: it is suggesting to add your file to the main repository. Perfect! Click "create pull request."
  * In the body, write "Closes issue #<your issue number>" - you can find this on the [Issues](https://github.com/r-cybersecurity/faq/issues) page by clicking your issue and looking at the URL or title (the number is slightly faded next to the title). This automatically links your issue and your pull request.
  * Finally, click "Create pull request" again.
10. Moderators will review your contribution and may comment on your pull request to request edits. This will email you, but please check back every day in case you miss the email. If edits are requested, just update the file in your repository normally - the pull request will be updated with the new changes you made automatically. An example pull request is [here](https://github.com/r-cybersecurity/faq/pull/2).

Once we're satisfied, we'll confirm with you that your content is OK to be licensed under CC BY-NC-SA 4.0. If you approve, we will merge the pull request, and this will close your Issue automatically. If you weren't familiar with Git before, now you're a little more familiar with how some things happen - get a bit more experience and before you put Git on your resume though!

## License

All contributed works are licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), which is a Creative Commons license stipulating (among many things):

* People may adapt and remix this work.
* People must provide appropriate attribution to the creators of this work.
* People may not use this work for commercial purposes.
* People must share any derived works under the same license.

We feel this preserves the freedom of great resources generated by this community and minimizes certain misuse cases. The above is an incomplete set of human-readable talking points, and not a substitute for the license, which is available on the web [here](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) or in this repository as [LICENSE](https://github.com/r-cybersecurity/faq/blob/main/LICENSE).

## Edge Cases

We currently don't have a well-defined mechanism for community-provided edits. We are focusing on the most goof in the shortest amount of time first, though if edits are *necessary*, an editor may edit an existing file on a fork, add a signature indicating their are an editor if the edits are significant (**do not** remove or alter the author's signature), and then submit the changes for consideration.

Moderators will handle spelling or grammatical errors caught after the pull request completed without adding their own credit.

Additionally, failure to successfully produce an accepted article within a week - for any reason - will result in you forfeiting your ability to answer the question exclusively. Others may answer the question themselves and then submit their own PR. We'll be flexible if you need a couple more days but please remember we're trying to move fast here, and that answers should be pretty to-the-point. If this happens, we will close your PR without accepting the changes, and mark your Issue as up-for-grabs. Thank you for understanding.
