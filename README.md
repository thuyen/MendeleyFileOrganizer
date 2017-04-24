### Mendeley File Organizer
The script will help you rename your pdfs into the format: LastName_Year_Journal_Title.pdf and move the file into a category folder. 

This is how I organize/sync my mendeley database using this script:

Mendeley sqlite database is moved to ~/Papers/Mendeley, which is linked back to orginial location. This way all papers and sqlite database are synchorized across all machines through Dropbox by creating a symbolic link for ~/Papers on Dropbox. I turned off the cloud sync in my Mendeley.

I create a shell script mdl.sh at ~/Papers/Mendeley and run it at startup. This will organize all pdfs into categories within ~/Papers

Be careful, backup your data before trying this.
