# FAQ

## Who started this project?

This project was the original creation of David Eldersveld, and has become a community effort since then. 

## I want to ask a question, where can I ask it?

You can [create a new issue] in this repository to get a response from someone in our community of contributors.

## How do you find theme properties?

It's possible to explore a Power BI Desktop file on your local computer to see the properties that are set, even if they aren't documented by Microsoft yet.
Check out [this great article](https://nolock.medium.com/how-to-discover-undocumented-theme-settings-in-power-bi-desktop-dcbe264351c8) for a guide on how to extract these properties.

## I want to help add to this project, how do I get started?

Contribution guidelines will be added shortly. In the meantime, fork this repo, make some changes, and create a pull request. One of our maintainers will review it and help you get it merged into the main project.

## Why was this project restarted instead of forked?

Github does not have an easy way to steer users to the latest active fork. Several experiments have been done that show users get confused with the 'forked from username/repositoryname' link at the top of a forked repository, and often create issues or PRs against the original, inactive repository. Splitting this repository was done intentionally to keep the collaboration in an active repository.

## What are the known issues with Power BI Theme Templates?

These are the items that cannot be controlled through a JSON template:
* Slicer
  * 'Search' can never be toggled on or off by default, the related parameter is selfFilterEnabled (see issue #64)

[create a new issue]: https://github.com/MattRudy/PowerBI-ThemeTemplates/issues/new
