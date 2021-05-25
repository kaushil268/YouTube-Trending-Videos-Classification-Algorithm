# YouTube-Trending-Videos-Classification-Algorithm

YouTube maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.

This dataset was collected using the YouTube API. This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included regions USA, Great Britain, Germany, Canada, and France, Russia, Mexico, South Korea, Japan and India respectively with up to 200 listed trending videos per day.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the five regions in the dataset.

To classify and identify a video as trending multiple factors are taken into account like its category, number of views, likes, dislikes, average video viewing time, comment count etc.

This project aims at identifying and classifying videos as trending according to their category and depicting trending videos in each category taking into consideration the above mentioned parameters and same is done with channels of each category.

Basically this projects creates the Trending list you always see on your app...
