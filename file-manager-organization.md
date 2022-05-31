# Hazel 

## Getting help

Folder Watching Best Practices
Regardless of what method you use for folder watching, follow these best practices to
produce an efficient and reliable workflow:
Wait for items to finish writing to disk before processing them.
Move processed items to an output folder so the same items aren't detected and
processed a second time.
Handle errors gracefully, such as by moving problematic items to an error folder so
other processing can proceed.
• Bring dialogs and alerts to the front so they're visible and can be addressed.

About Folders & Rules
Hazel lets you automate the management and organization of your files and folders. You can ask Hazel to watch any
number of folders, and for each one, you create one or more rules that detail what should happen to the folder's contents
and under what circumstances.
Hazel can be used to organize almost any folder, but the best candidates are ones that tend to collect files, such as where
your browser downloads files, where Mail puts attachments, or a shared Dropbox folder. Hazel can also use Smart Folders
(with minor limitations).
What Rules Can Do
Rules in Hazel, much like rules in Apple Mail, specify two things:
• What to look for in the selected folder (conditions)
• What to do when the conditions are met (actions)
You can have Hazel watch any number of folders; and for each folder. you can create any number of rules. Each rule, in
turn. nave one or more conditions that, when met, trigger one or more actions.
Conditions
A Hazel rule can match a vast range of conditions for both files and folders practically anything you can think of. To give
just a few examples, a condition can examine attributes such as:
• The name size of file or folder-for example, "Filename contains cherry" or 'Size is greater than 100 MB"
The creation or modification date of file or folder-for example, "Date Created is in the last week" or "Date Last
Modified occurs after 3:00 PM on a weekend in January or March"
The text contents of a file-for example, *Contents do not contain virtual machine" or "Contents contain match any
word followed by a three-digit number"
• Metadata such as Finder tags and comments-for example, "Tags contain Work" or "Comment is not blank"
• The number of items (files or folders) in a subfolderfor example, "Sub-file/folder Count is less than 5"
Normally hidden Spotlight metadata for photos, music, and other media files-for example, "Resolution width is
than 300 DPI)" or "Composer contains Bach"
And, multiple conditions be combined in any way you like a rule de can be set to match any, all, or none of the conditions
you specify; and you can even nest conditions to create complex logical tests.
Actions
When your rule matches the condition(s) you specify, it then takes one or more actions. Again the range of options iS
immense, but here few examples:
• Move or copy the matched item to another location, or upload it to a server
• Sort the matched item into a subfolder
• Rename the matched item
• Zip or unzip the matched item
* Change metadata such as Finder tags and comments
. Import the item into Photos or Music
* Display a notification
• Run an AppleScript, JavaScript, Automator workflow, or shell script

Example Rules
Putting conditions and actions together, here are a few examples of complete rules you can create in Hazel:
• When a family member puts a photo in a shared Dropbox folder, import it into Photos, delete the original, and
display a notification.
When a PDF file appears on my Desktop, move it into my Documents folder and then open it in Preview.
When my Downloads folder contains a dm file that's larger than 100 MB and older than one week, move it to the
Trash.
• When I put a Word file in my Research folder that contains the text "earnings report," apply the Finder tag
"Finances."

When a scanned document appears in my Images folder, run an AppleScript that opens it in PDFpenPro and
performs OCR (optical character recognition) on it.
In cases where a folder has numerous rules, or the conditions and actions are complex, it can take some planning and
experimentation to achieve exactly your desired results. For a detailed explanation of Hazel's logic when processing rules,
read Understand the Logic of Rules.

Anatomy of a Simple Rule
To illustrate how Hazel rules are constructed, let's look at a simple example. This happens to be one of the sample rules you
can install by choosing Help Load Sample Rules.
This example shows the "Pictures" rule (which is meant to be attached to the Downloads folder, not shown):
Name: Pictures B

all * of the following conditions are met
Kind is Image
Do the following to the matched file or folder:
Move € to folder: Pictures Options
Revert Save

This rule looks for files in the Downloads folder with a kind of "Image" and, for each one moves it to the Pictures
folder (that is. Macintosh HD Users > your-username • Pictures).
Here's what each element does:
. be Name D: The rule's name can be anything you like. This one is simply Called "Pictures."

Note 2: If you want to make notes or comments about the rule-perhaps explaining what it does or why you
constructed it a certain way. click the Note E) icon, enter the note, and then click the X & icon (or just click
anywhere outside the note bubble). When a rule includes a note, the Note E icon turns blue.

Conditions (3): The conditions area, outlined in green in the image above, specifies what has to be true in order for
the rule to be triggered (and thus for the action(s) to run). This rule has only one condition, created by choosing
options from a series of pop-up menus: "Kind is Image." (We could add more conditions by clicking the plus +
button in the Conditions section.) That is, if the rule encounters a file in the Downloads folder with a kind of "Image,"
the condition is true and the action C applies to that file.

Actions 4: The actions area, outlined in blue above, specifies what happens to each file or folder for which the
condition(s) above have been met. This rule has only one action (again, constructed by choosing options from a
series of pop-up menus): "Move to folder Pictures." (We could add more actions by clicking the plus + button in
the Actions section.)

Notice the Options 1 icon next to the action. Some actions offer additional parameters; click this icon to adjust
them. (For the "Move" action, options let you specify what happens if a file with the same name already exists at
the destination, whether to throw the file away if it's a duplicate, and O whether or how to copy the folder structure
when moving a folder.)

Some conditions and actions have more or fewer pop-up menus, require you to fill in blanks, or let you build patterns of
various kinds. But they all follow this basic structure, and every condition and action starts with a choice from the leftmost
pop-up menu in its row.
