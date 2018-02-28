# HIBP
Have I Been Pwned (HIBP)
Gathering HIBP breach data is relatively straightforward.  First, you'll get the complete list of breaches along with all the related data.  Next, you'll make an API call for each breach to get the location (URL) of the file containing the list of email accounts involved in the breach (aka the "hash file").  Finally, you'll use the location to download the hash file.
Description of breach may be edited. 
curl https://haveibeenpwned.com/api/v2/breaches
