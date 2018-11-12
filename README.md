# Sentiment and Predictive Analyses of 2016 Election based on Social Media

***

[Link to Data Source](https://www.kaggle.com/kinguistics/election-day-tweets/kernels)

[Link to CSV File](https://drive.google.com/drive/folders/167CxGqwEPn2q9OevOQqy2rXenQ-L_sZF)

|            Variable           | Description                                                                                                                   |
|:-----------------------------:|-------------------------------------------------------------------------------------------------------------------------------|
|              text             | text of the tweet                                                                                                             |
|           created_at          | date and time of the tweet (format yyyy-mm--dd hh:mm:ss)                                                                      |
|              geo              | a JSON object containing coordinates [latitude, longitude] and a "type"                                                       |
|              lang             | Twitter's guess as to the language of the tweet                                                                               |
|             place             | a Place object from the Twitter API                                                                                           |
|          coordinates          | a JSON object containing coordinates [longitude, latitude] and a `type'; note that coordinates are reversed from the geofield |
|     user.favourites.count     | number of tweets the user has favorited                                                                                       |
|      user.statuses_count      | number of statuses the user has posted                                                                                        |
|        user.description       | the text of the user's profile description                                                                                    |
|         user.location         | text of the user's profile location                                                                                           |
|            user.id            | unique id for the user                                                                                                        |
|        user.created_at        | when the user created their account                                                                                           |
|         user.verified         | bool; is user verified?                                                                                                       |
|         user.following        | bool; am I (Ed King - the data creator) following this user?                                                                  |
|            user.url           | the URL that the user listed in their profile (not necessarily a link to their Twitter profile)                               |
|       user.listed_count       | number of lists this user is on (?)                                                                                           |
|      user.followers_count     | number of accounts that follow this user                                                                                      |
|   user.default_profile_image  | bool; does the user use the default profile pic?                                                                              |
|        user.utc_offset        | positive or negative distance from UTC, in seconds                                                                            |
|       user.friends_count      | number of accounts this user follows                                                                                          |
|      user.default_profile     | bool; does the user use the default profile?                                                                                  |
|           user.name           | user's profile name                                                                                                           |
|           user.lang           | user's default language                                                                                                       |
|        user.screen_name       | user's account name                                                                                                           |
|        user.geo_enabled       | bool; does user have geo enabled?                                                                                             |
| user.profile_background_color | user's profile background color, as hex in format "RRGGBB" (no '#')                                                           |
|     user.profile_image_url    | a link to the user's profile pic                                                                                              |
|         user.time_zone        | full name of the user's time zone                                                                                             |
|               id              | unique tweet ID                                                                                                               |
|         favorite_count        | number of times the tweet has been favorited                                                                                  |
|           retweeted           | bool; is this a retweet?                                                                                                      |
|             source            | if a link, where is it from (e.g., "Instagram")                                                                               |
|           favorited           | have I (Ed King - data creator) favorited this tweet?                                                                         |
|         retweet_count         | number of times this tweet has been retweeted         |
