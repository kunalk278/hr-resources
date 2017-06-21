# hr-resources
## Additional Human Resources Documents for reuse

This is a series of documents we're using at the The OpenGov Foundation, created by ourselves with our laywers. Creating a strong human resources policy is an expensive, difficult task for most small organizations.

All of these documents are being released with open licenses, meaning they're **absolutely free to use**.  This will allow any person or organization - **for profit or not for profit** - to copy, edit, rewrite, and distribute them at no cost!  They are [Creative Commons CC0 Licensed](https://creativecommons.org/publicdomain/zero/1.0/), dedicating them to the public domain.

There are a variety of documents here which may or may not be relevant to your organization, so feel free to use whichever of these are useful and ignore the rest.

Included are:

* [Employee Review Form](./markdown/employee-review.md) - A simple form for employee reviews, focusing on goal-setting for the employee.
* [Status Messages](./markdown/status-messages.md) - How to write effective daily stand-up or status emails or messages.  We have every employee send a message to the team every morning.  We've found these very useful for small, decentralized teams to keep everyone in the loop.
* [Timesheets](./markdown/timesheets.md) Guide - How to enter time into your timesheet application.  This is general enough to adapt this for any software tool you might use to track time - this is process-oriented, not software-oriented.

Please suggest any changes that you think we should make, or contribute your own to the repo!

**There are other useful documents to use in our [HR Policy Repository](https://github.com/opengovfoundation/hr-manual), including our actual Human Resources Policy Manual.**

## Disclaimer
This was created based on United States law, and if you're not in the US the policies here might not be legal wherever you are.

We are not lawyers, and cannot give you legal advice or tell you what is best for your organization.  You should have an actual lawyer review these documents before you use them in the first place.  If you have any questions, ask a lawyer.

We cannot be held responsible for any legal trouble that these documents get you into.  You're using them of your own accord.  We're providing them as-is with no warranty.  Seriously, please don't sue us.

## Available Files

The following files are available in a variety of formats - use the links below to download them directly.

Document | Description | | | |
--- | --- | --- | --- | --- |
Status Messages | [Markdown](https://rawgit.com/opengovfoundation/hr-manual/master/markdown/status-messages.md) | [HTML](https://rawgit.com/opengovfoundation/hr-manual/master/html/status-messages.html) | [PDF](https://rawgit.com/opengovfoundation/hr-manual/master/pdf/status-messages.pdf) | [Microsoft Word](https://rawgit.com/opengovfoundation/hr-manual/master/docx/status-messages.docx)
Timesheets | [Markdown](https://rawgit.com/opengovfoundation/hr-manual/master/markdown/timesheets.md) | [HTML](https://rawgit.com/opengovfoundation/hr-manual/master/html/timesheets.html) | [PDF](https://rawgit.com/opengovfoundation/hr-manual/master/pdf/timesheets.pdf) | [Microsoft Word](https://rawgit.com/opengovfoundation/hr-manual/master/docx/timesheets.docx)
Employee Review Form | [Markdown](https://rawgit.com/opengovfoundation/hr-manual/master/markdown/employee-review.md) | [HTML](https://rawgit.com/opengovfoundation/hr-manual/master/html/employee-review.html) | [PDF](https://rawgit.com/opengovfoundation/hr-manual/master/pdf/employee-review.pdf) | [Microsoft Word](https://rawgit.com/opengovfoundation/hr-manual/master/docx/employee-review.docx)

## Contributing

We welcome suggested edits to these documents!

We use Markdown as the primary format for these files, so you'll need to know a little before you begin. Don't worry - it's easy!  [Here's a quick guide.](https://guides.github.com/features/mastering-markdown/) If you've used a wiki, reddit, etc. it should be easy to pick up.  *Note that we _cannot_ accept changes directly made to other formats, only Markdown.*

If you don't want to learn Markdown and still want to contribute, feel free to [open an issue on this repo](./issues), or just [send us an email](mailto:sayhello@opengovfoundation.org).

### The Easy Way ###
You can edit the files directly using the links below, no account or GitHub experience needed!

*Coming Soon!*

### The Advanced Way ###
If you are familiar with GitHub, please fork the repo and send a pull request.

We use [pandoc](http://pandoc.org/) to generate the many formats we display.  If you don't have pandoc installed, that's ok!  Just send us a pull request with the updated markdown files.

If you have pandoc installed with pdfLaTeX, you can run the following command from the repository root to generate these files:

    for myfile in $( ls ./markdown ); do echo Converting $myfile; for fmt in html docx pdf; do filetrim=${myfile%???}; pandoc -o "./"$fmt"/"$filetrim"."$fmt -f markdown "./markdown/"$myfile; done ; done


