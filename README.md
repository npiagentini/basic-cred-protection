# basic-cred-protection
Builds a new default URL filtering profile with basic credential protection enabled

PANOS supports the ability for URL filtering profiles to alert if usernames matching the current User-ID value of a session are entered into websites of a specific category.  Unlike the fuller featured, and more complex credential protection offered by using dedicated read only Domain Controllers, this function only requires User ID to be active. This skillet edits the default URL filtering profile to add in credential protection settings. This profile can then be used as a starting point to create other profiles.

