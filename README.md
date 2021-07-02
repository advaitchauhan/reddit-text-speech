# RedditTTS: Auto-generated interrnet trash

There are a number of very successful youtube channels entirely comprosed of robotic narrators reading funny reddit content out loud. W/ some background music and video frames where the content can also be read... Some channel examples:
* https://www.youtube.com/channel/UCRVewEWU9NEWeKh3cCAif0w (250k subs)
* https://www.youtube.com/channel/UCSd-3R1xJ0hRT8rQkuIiDew (150k subs)

We wondered, why not just generate such content automatically and generate a profitable youtube channel while putting in 0 effort creating content?

We thus wrote up some code where you can just paste a reddit link, and a video of this style is generated automatically. The script scrapes the reddit content and finds the the most upvoted comments, generates a text-to-speeech narration, generates a sequence of video frames, and stitches it all together into a final video (w/ some tastefully added music to boot)

Here's some generated output:
* https://www.youtube.com/watch?v=XycswRYDPCQ
* https://www.youtube.com/watch?v=GiKkZXeJanQ


## Self serve

To use the code, you can simply create a config file (see the configs folder) with the URL you want to scrape. Then just run the script:

`python run_reddit_man.py`

Which will generate a video output file. 
