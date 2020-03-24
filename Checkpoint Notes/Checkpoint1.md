
# CP-1 Questions

## Main Questions
1. *the data capturing process*: Has the group found adequate and sufficient data sources for their application?
    - Relevant information is available and in the public domain. City and State information has been isolated from the US Census Bureau. The Committee and Candidate tables are generated based off of information published by the FEC. Event data will be obtained from the website Ballotpedia, which publishes their information under an acceptable license.
2. *the minimum number of 250,000 tuples*: Can the group exceed this threshold?
    - The data set of presidential campaign contributions is quite large. We currently intend on adding 3 candidates, and expect this to more than meet the tuple requirement. This can be easily modified to include more candidates if needed. The group anticipates no issues meeting this requirement.
3. *the database*: Has the database schema be created? Has the database been filled with real world data? What has still to be done?
    - We have loaded some of the FEC data set into the database to ensure it would import without issues. We have created CSV files to facilitate importing our City, State, and Campaign tables. The data behind the Event table needs to be extracted from the source.
4. *the user interface*: Has the user interface been implemented to
  some extent? What has still to be done?
    - Work on the UI of our application is not yet started, though we anticipate beginning work on it this week.
5. *the connection between the database and the user interface*: Has the group managed to establish the connection between both components so that they can send data from the user interface to the database and retrieve data from the database and display them on the user interface?
    - A connection between PHP and our database has been successfully tested and is functional.
6. *possible social problems within a group*
 Does the group regularly? Is the group facing some social problems? Can the group members work together? Does each group member contribute to the group's activities? Are there group members who let the other group members work for them?
    - Our group meets regularly via Zoom and communicates regularly using a Slack instance. Github is being utilized to facilitate group development of the application.

## Further questions:

- *the used system environment*:
   - Currently the public_html hosting of the CISE terminal servers are being utilized to test the platform.
- *the programming language used for the web-based part*:
  - Initial development is being completed in PHP. We do not anticipate this changing.
- *how data are captured, processed, and put into the database*:
  - Data is being uploaded as a CSV file to the terminal server and imported to the database using SQL*plus.
