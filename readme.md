## MyNotes:
### (1) $Group : this aggregate stage that use for grouped the documents and allow to do more work with the same selected document and it always return unique fields.

### (2) $unwind : It is used to transform a single document containing an array into multiple documents and each document contaning an individual values from an array.

### (3) $addField : Adds new fields to documents. $addFields outputs documents that contain all existing fields from the input documents and newly added fields.                                                                                                           The $addFields stage is equivalent to a $project stage that explicitly specifies all existing fields in the input documents and adds the new fields.

### (4) $match: Filters the documents to pass only the documents that match the specified condition to the next pipeline stage.

### (5) $count: It returns the number of documents at this stage of the aggregation pipeline.


[Data_Link](https://gist.github.com/hiteshchoudhary)

## Aggregation Pipeline Query :

### 1- How many users are active?
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/1-match.json)

### 2- What is the average age of all users?
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/1-match.json)

### 3- List the top 5 most common favorite fruits among users
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/2-group-avg.json)

### 4- Find the total numbers of gender like males and females

[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/3-totalNumberGenders.json)

### 5- highest registered users in which country:
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/4-highestRegisteredUsersInWhichCountry.json)


### 6- List all the unique eyes colors present in the collection:
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/5-uniqueEyeColorPresentInCollection.json)

### 7- What is the average number of tags per user?
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/6-avgNumTagsPerUser.json)

### 8- how many users have 'enim' as one of their tags?
[pipeline query](https://github.com/AzeemKhan27/master_mongodb_aggregation/blob/main/7-filterUserByGivenValueInTags.json)