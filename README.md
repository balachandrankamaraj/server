# server
1. List query has limit for 40 size, If do the pagination in frontend, we can achieve below 10ms each request. if not using limit and  offset in query it will take more than a secounds
2. I did optionzation the select query and add the index in user and friend table based on neccessary of our business logic

3. I have add the max connection and pagesize in front end, we can check the limitation based on selection.
4. I add the two combination constrains for select query optimization.
5. added the name index query to user table
6. Here I framed the dynamic query due to given option from frontend. when we want to go for bulk data with more limitation.

   Note: if you want me cover any more logic, Please let me know for further changes.

   
