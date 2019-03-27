# Gun Violence Participants
Quick data wrangling project for the Cline Center - processing and reformatting data about participants in gun violence. CSV from https://github.com/jamesqo/gun-violence-data

Original Goal: take the participant columns from the original gun violence data and reformat them so that each participant per incident has their own row.
- 'participantsraw.csv' contains the relevant columns from the original csv (which is too large to be uploaded to the repo, and can be found at https://github.com/jamesqo/gun-violence-data)
- 'participants.csv' contains the transformed data, with rowID being the uniqueID (in the format of incidentID-participantID)
