# YouTube JSON API
Getting YouTube Data Feed as JSON Format

## Usage

### For used function in this script
getFeedBySpecificVideoID( "09R8_2nJtjg", "feed_by_specific_video_id" );
Set first parameter as video id and second parameter as element id

getFeedByKeyword( "Tailor Swift", "feed_by_keyword" );
Set first parameter as searching keyword and second parameter as element id

### For Developing more
If you want to extend the functions then just use the gdata url as your needed.

http://gdata.youtube.com/feeds/api/videos/?v=[put-videoid-here]2&alt=jsonc

https://gdata.youtube.com/feeds/api/videos?q=[put-keyword-here]&v=2&alt=jsonc

##Demo [http://sohelamin.github.io/youtube-json-api/]
