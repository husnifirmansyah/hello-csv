## Hello CSV

The backlog is as folows:

0. Read the file (sample.csv).
1. Parse the loaded csv.
2. For each line do transfomation for `first_name` and `last_name` into `full_name`, then put that into the data (hence we have `full_name` for each line).
3. Send the transformed line via SMS. (see helper.js) 
4. Log the SMS sending status result to S3. (see helper.js)

### Discussion

- What do you think about the `naive()` function (please see the parse-callback.js)?
- Please take a peek at the parse-async.js, parse-stream.js and parse-promise.js, then give your best gift to us! (Yes, sending us a proper PR https://help.github.com/articles/creating-a-pull-request/)

**Constraint**: Please use async API only e.g. `fs.readFile` **NOT** `fs.readFileSync` for reading files.

**Note**: The `sendSms` and `logToS3` have surprises, please deal with that.

Ah, yes, one last thing, please use http://jscs.info/ to make your code consistent.

Have fun!
