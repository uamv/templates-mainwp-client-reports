# MainWP Client Report Templates
This collection of email templates is for use with the MainWP Client Reports extension.

## Usage

### Preparing Your Network
+ Ensure [MainWP Client Reports](https://twhl.xyz/mwp-cr/) is installed on child sites
+ Ensure **@records** are being retained for more than the necessary number of days. The [Code Snippets](https://twhl.xyz/mwp-cs/) extension can be used to [check](https://github.com/uamv/snippets-mainwp-code-snippets/blob/master/child-report-period-get.php) and [set](https://github.com/uamv/snippets-mainwp-code-snippets/blob/master/child-report-period-set.php) this value.
+ Ensure the necessary **@tokens** and **@tokens-custom** are set for each child site in your MainWP dashboard.
+ Ensure all extensions shown in **@requires** are active in your MainWP dashboard.

### Preparing Your Report
+ Using a text editor, find and replace all **@replace** placeholders in the template.
+ Personalize any of the other message text.
+ In your MainWP dashboard, create a new client report.
+ Define *Report Settings* and *Select Sites*.
+ Paste client report code into the *Report Body > Text Editor*.
+ Click ***Save Report***.
+ Click ***Send Test Email***.
