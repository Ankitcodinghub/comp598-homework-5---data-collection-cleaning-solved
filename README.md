# comp598-homework-5---data-collection-cleaning-solved
**TO GET THIS SOLUTION VISIT:** [COMP598 Homework 5 – Data Collection & Cleaning Solved](https://www.ankitcodinghub.com/product/comp-598-homework-5-data-collection-cleaning-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118612&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP598 Homework 5 – Data Collection \u0026amp; Cleaning Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Non-standard (i.e., built-in) python libraries you can use:

– pandas

– requests

Cleaning data (10 pts)

You are cleaning files containing user posts in JSON data. The JSON objects are all valid, but they have field consistency issues that you need to fix. Your script, clean.py, should accept an input file and produce a cleaned output file. The script is run:

python3 clean.py -i &lt;input_file&gt; -o &lt;output_file&gt;

The input file will contain one JSON dictionary per line (see the file example.json included with the assignment which you can use as an example… though you shouldn’t treat it as a complete test. Your script will need to handle arbitrary JSON dictionaries). Each dictionary is a post. The output file should also have one JSON dictionary (i.e., post) per line. Your script should do the following:

o Remove all the posts that don’t have a title or title_text field.

o Posts that haven’t been flagged for removal should be written to the output file in the order they appear in the input file.

o Any lines that contain invalid JSON dictionaries should be ignored.

Tips:

– Python provides a very powerful datetime package called… datetime – When working with JSON data, the json package is your friend.

Data Collection &amp; Bias (20 pts)

You’ve been given the task of assessing the average length of a Reddit post title. But since we can’t collect ALL Reddit posts, we’re going to try two different ways of sampling posts to assess their length:

– Sample 1: Collect the 1000 newest posts from the 10 most popular subreddits by subscribers: funny, AskReddit, gaming, aww, pics, Music, science, worldnews, videos, todayilearned.

– Sample 2: Collect the 1000 newest posts from the 10 most popular subreddits by # of posts by day: AskReddit, memes, politics, nfl, nba, wallstreetbets, teenagers, PublicFreakout, leagueoflegends, unpopularopinion

Compute average post title length (measured as # of characters/post text) for each scenario. This task should be split into two scripts: collect.py and compute_title_lengths.py

collect.py does the work of collecting the data for BOTH of the sampling approaches. It should store the data (as received from Reddit) in files data/sample1.json and data/sample2.json (respectively). It can work however you like – we will not grade it directly.

Tips:

– If the post title doesn’t contain any text, it still counts as a post … just with text length of zero.

– Note that you are collecting POSTS, not comments (which are the responses to posts).

– To collect the posts you’ll want to use the /new API endpoint.

– make sure to set the User-Agent in your get requests … see API guidelines here: https://github.com/reddit-archive/reddit/wiki/API.

https://github.com/reddit-archive/reddit/wiki/OAuth2 – The packages requests + json will be your friends.

Submission Instructions

Your MyCourses submission must be a single zip file entiled HW5_&lt;studentid&gt;.zip. It should contain the following items:

– scripts/ o clean.py – the script for Task 1 o collect.py – the script for Task 2

o compute_title_lengths.py – the script for Task 2

– src/ o hw5/ – this directory will be included in the PYTHONPATH when clean.py and compute_title_lengths.py are run

 &lt;whatever you want here&gt;…

– data/ o sample1.json – the 1000 posts you collected from the first set of subreddits o sample2.json – the 1000 posts you collected from the second set of subreddits
