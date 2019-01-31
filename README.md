# Notion Export to ICS

This is a simple Python script to export a Notion database with a 'Date' attribute to an ICS file. All the heavy lifting is done by the 
[`notion-py`](https://github.com/jamalex/notion-py) library. You'll need to provide a `settings.json` file with the following keys:

  - `token`: the `token_v2` you can get from your browsers cookies
  - `block`: the Notion URL of your database

Also make sure that the `make_title` function in the `make_ics` script fits your Database.

If you run this script in a cron job, and publish it on some publicly reachable URL, you can import it into Google Calendar :).

