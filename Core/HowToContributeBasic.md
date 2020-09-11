# General Contribution Guidelines
## An overview
We welcome your contributions to our repository.  You may contribute original work or links to publically available works you have found useful.

To add a contribution, create a pull request on the GitHub repo [cloudcomputingCurriculum](https://github.com/cloudcomputingcurricula/Cloud-Computing-Curricula):
Copy `Module.md` to a new file with a name describing your contribution and add it to the `Content` folder.
Update `Contributions.md` to include a link to your new module file.

## Guidance for your copy of `Module.md`

In the file `Module.md`, update the sections as follows:
* Title: Replace the Title line with the Title of your contribution
* Summary: A summary of your contribution 
* Author or Contributor (Optional): As much of your contact information as you would like to include.  Your basic information will be available through the GitHub history even if this section is omitted.  If you're willing to have others contact you, please include your prefered method of contact.
* Content Link: the link or links to your contribution
* Knowledge Area(s): Select the Knowledge Areas that are applicable
* Material Theme(s): Select the appropriate themes for your material based on [these definitions](/Core/Themes.md).
* Tags: words or short phrases to help others find your material
  * Level of study (Optional)
  * Cloud Vendor(s): If your contribution is specific to one or more vendors, list them here
  * General tags: Any other tags that would be useful
* Prerequisites (Optional): Any prerequisites to using your contribution
* Learning objectives (Optional)
* License (Optional)

See [this file](Sample.md) for an example of an edited `Module.md`.

## Guidance for changes to `Contributions.md`
Add information that will help others decide if they'd like to explore your contribution further to the `Contributions.md` file.  Put it under the appropriate header (adding a header if necessary).

Your entry should consist of:
```
[Title of contribution](link to your .md file) (KA1, KA2, …): Summary (tags)
```
KA1, KA2 should be replaced by the abbreviations of the Knowledge Areas covered by your contribution.  The summary may be the summary from your `.md` file or may be a shorter version.  The tag should be the list of tags provided in your tags.  
An example of an entry to match [the sample file](Sample.md) is below:
```
[Sample Contribution](Sample.md) (FCC, SDCA, CPMF): Here's a sample contribution of wonderful materials to the repo. (Intermediate, WWW, backend, security, programming)
```

For details on the mechanics on how to update the GitHub repo, see the following:
* How to contribute (using GitHub Desktop)
* [How to contribute (via the browser)](HowtoContributeBrowser.md)
* [How to contribute (via the command line)](HowToContributeCMD.md)
