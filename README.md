A very rudimentary script to send HTMl formatted emails. A (limited) precursor to Postman With a Broken Leg. 

## Usage:
1. Set up the Gmail-API, as per the [Python Quickstart](https://developers.google.com/workspace/gmail/api/quickstart/python).
2. Download the above file and replace the contents of  `quickstart.py` with the above code.
3. Edit the string fed into `internal_email` (line 19) with the div of your email template (obtained via using inspect element on an email in your inbox).
4. Edit the `from` and `subject` variables (lines 22 and 23 respectively).
5. Edit the tuple containing the list of emails you would like to send to (line 50).
6. Run the file.
