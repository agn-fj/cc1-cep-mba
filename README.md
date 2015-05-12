# cc1-cep-mba
Service concepts for tracking course completions

AGN=>Moodle: Get Course Completions By Date Range
 - moodle.getCoursesByDateRange(DateBegin, DateEnd)
 - return: list of completed courses
 - notes: would be called by CC1 nightly batch process
 
AGN=>Moodle: Get Course Completions By User
 - moodle.getCoursesByUser(UserId)
 - return: list of completed courses
 - notes: would be called by CC1/CEP users, possibly in a "Get Latest" scenario between batch runs

![](assets/cep_mba_v1.png?raw=true)
