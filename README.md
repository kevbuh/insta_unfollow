# insta_unfollow

Little jupyter notebook to see who doesn't follow you

Main function to look for
- Near the bottom of the notebook

```python
def get_non_followers(follower_json, following_json):
  """
  Input the your own JSON object into follower_json and following_json.
  Then run the cell to see result of who doesn't follow you back!
  """
````

## How to download your instagram data
Go to you instagram account -> settings -> privacy and security -> download account info
Instagram will then proceed to send you an email with your account's data.

## See who doesn't follow you back
1. Unzip, and then go to ./login_and_account_creation/followers_and_following.
2. Then, go into followers.json and following.json and get the JSON objects from there. 
3. Finally, put your objects into the notebook and run every cell to see who doesn't follow you back.
