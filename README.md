## Simple Settings Example

A simple settings example which demonstrates how to store contextual data regarding a specific content add-in.

Each control added to the page will be able to store it's own text. Simply change the text in the text box to change the saved content.

Exported on: Friday, December 21st 2018, 12:13:47 am

Built with [Script Lab](https://github.com/OfficeDev/script-lab)

* * *

### To re-import the snippet into Script Lab:
Copy the metadata (*.yaml) file into the "import" screen in Script Lab. See <https://github.com/OfficeDev/script-lab/blob/master/README.md#import> for detailed instructions.

### To run the snippet *outside* of Script Lab (like a "mini" exported Add-in):

1. Publish the html file to a website. Note that because settings/cookies/etc are stored per domain name (not per page URL, but the entire domain name), it is best to put the snippet in its own website (with its own unique domain name) if you make use of these.

2. Search for `https://<INSERT-URL-HERE>` within manifest file (should be 2 occurrences), and replace both with the URL that the html page is published to. If you've renamed the html file, adjust the path as well.

3. Sideload the manifest using the instructions found at <https://aka.ms/sideload-addins>.
