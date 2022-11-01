# habit

api written in Go and Gin 

TODO: 
* Create MySQL DB
* Create Routes
    * Users
        * Create
        * Delete
        * Update
    * Habits
        * Create
        * Delete
            * We dont actually want to delete any habits or goals so that we don't loose trend data
        * Update 
    * Goals 
        * Create
        * Delete
            * We dont actually want to delete any habits or goals so that we don't loose trend data
        * Update 
* OAuth
    * Inactivity results in logout
    * Look into Google Auth 