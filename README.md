# ua-jira-releases
 Adapter can create, update, read and query the Releases(Versions) of Jira within a Project.

1) It has been tested with 10 fields.
2) Attached the tested field mapping in the images section.
3) Attached the api observation and jolt transformations in the docs section.

Working Condition:
- It cannot query the records which is last modified as it doesn't have date-time field.
- It can query all the records with descending sequence.
- It can read, create and update the records.
