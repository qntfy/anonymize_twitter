This is a repository generated to de identify Twitter data to support mental health research (specifically
the computational linguistics and clinical psychology [CLPsych] 2015 Shared Task).
For more information, see http://clpsych.org

Authors and Contributors:
Glen Coppersmith
Meg Mitchell
Craig Harman
Mark Dredze
Ryan Leary


Tweet Object fields
  https://dev.twitter.com/overview/api/tweets

  Anonymized:
    - entities    
    - id
    - id_str
    - in_reply_to_screen_name
    - in_reply_to_status_id',
    - in_reply_to_status_id_str
    - in_reply_to_user_id
    - in_reply_to_user_id_str
    - retweeted_status
    - text
    - user

  Kept:
    - created_at
    - favorite_count
    - lang
    - possibly_sensitive
    - retweet_count
    - scopes
    - truncated
    - source

  Removed:
    - annotations
    - contributors
    - coordinates
    - current_user_retweet
    - filter_level
    - geo
    - place
    - withheld_copyright
    - withheld_in_countries
    - withheld_scope


User Object fields
  https://dev.twitter.com/overview/api/users

  Anonymized:
    - id
    - id_str

  Kept: 
    - created_at
    - favourites_count
    - followers_count
    - friends_count
    - geo_enabled
    - lang
    - listed_count
    - statuses_count
    - time_zone
    - utc_offset
    - verified

  Removed:
    - contributors_enabled
    - default_profile
    - default_profile_image
    - description
    - entities
    - follow_request_sent
    - following
    - is_translator
    - location
    - name
    - notifications
    - profile_background_color
    - profile_background_image_url
    - profile_background_image_url_https
    - profile_background_tile
    - profile_banner_url
    - profile_image_url
    - profile_image_url_https
    - profile_link_color
    - profile_sidebar_border_color
    - profile_sidebar_fill_color
    - profile_text_color
    - profile_use_background_image
    - protected
    - screen_name
    - show_all_inline_media
    - status
    - url
    - withheld_in_countries
    - withheld_scope


Entity Object fields
  https://dev.twitter.com/overview/api/entities

  Anonymized:
  - media
  - urls
  - user_mentions

  Kept:
  - hashtags


Entity Media Object fields
  https://dev.twitter.com/overview/api/entities#obj-media

  Anonymized:
  - display_url
  - expanded_url
  - id
  - id_str
  - media_url
  - media_url_https
  - source_status_id
  - source_status_id_str
  - url

  Kept:
  - indices
  - sizes
  - type

