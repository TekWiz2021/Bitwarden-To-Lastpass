# Bitwarden-To-Lastpass
Export Bitwarden Passwords to LastPass  3 simple changes to Titles... Step By Step... See Readme File


Overview:
Easily Convert Bitwarden passwords to LastPass
Under settings in Bitwarden choose Export Vault and choose .cvs format and save to a location.
Using A Text Editor make the 3 changes below.
Then go to LastPass and go to Account Options\Advanced\Import
Select Generic CSV and import all your passwords and settings will be updated.

Specifics:
When you use a text editor on a Bitwarden Vault Exported .csv file... The Titles look like this.

folder,favorite,type,name,notes,fields,reprompt,login_uri,login_username,login_password,login_totp

Make The Changes Below And That's It. Changes are on the second line.
folder,favorite,type,name,notes,fields,reprompt,login_uri,login_username,login_password,login_totp
folder,favorite,type,name,notes,fields,reprompt,url,username,password,login_totp

Now you can import the Bitwarden Vault Exported.csv to LastPass using the Generic CSV selection.
That's all there is to it.
