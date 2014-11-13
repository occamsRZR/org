<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. <span class="todo TODO">TODO</span> Abstract out the industry page functionality&#xa0;&#xa0;&#xa0;<span class="tag"><span class="corporate">corporate</span></span></a>
<ul>
<li><a href="#sec-1-1">1.1. <span class="done DONE">DONE</span> Write path helpers so we aren't using media industry path&#xa0;&#xa0;&#xa0;<span class="tag"><span class="corporate">corporate</span></span></a></li>
<li><a href="#sec-1-2">1.2. <span class="done DONE">DONE</span> See which controller methods can be reused cand which have to be specific&#xa0;&#xa0;&#xa0;<span class="tag"><span class="corporate">corporate</span></span></a></li>
<li><a href="#sec-1-3">1.3. <span class="todo TODO">TODO</span> Look at the landing pages for Press and Commerce&#xa0;&#xa0;&#xa0;<span class="tag"><span class="corporate">corporate</span></span></a></li>
</ul>
</li>
<li><a href="#sec-2">2. <span class="todo TODO">TODO</span> Photo Galleries&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span>&#xa0;<span class="corporate">corporate</span></span></a>
<ul>
<li><a href="#sec-2-1">2.1. <span class="todo TODO">TODO</span> Photo Gallery for Corporate Sites&#xa0;&#xa0;&#xa0;<span class="tag"><span class="corporate">corporate</span></span></a></li>
<li><a href="#sec-2-2">2.2. <span class="todo TODO">TODO</span> Photo Gallery for Premium Profiles&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span></span></a>
<ul>
<li><a href="#sec-2-2-1">2.2.1. <span class="todo TODO">TODO</span> includes videos&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span></span></a></li>
<li><a href="#sec-2-2-2">2.2.2. <span class="todo TODO">TODO</span> includes multiple photos instead of one</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#sec-3">3. <span class="todo TODO">TODO</span> Remedy server issues&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span></span></a>
<ul>
<li><a href="#sec-3-1">3.1. <span class="todo TODO">TODO</span> Setup alerts on AWS for hard drive space</a></li>
<li><a href="#sec-3-2">3.2. <span class="todo TODO">TODO</span> Provide estimate for how much work it would take to move to s3</a></li>
</ul>
</li>
<li><a href="#sec-4">4. <span class="todo TODO">TODO</span> Sponsored Listings&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span></span></a></li>
<li><a href="#sec-5">5. <span class="todo TODO">TODO</span> Premium Profiles&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span></span></a></li>
<li><a href="#sec-6">6. <span class="todo TODO">TODO</span> Banner Ads&#xa0;&#xa0;&#xa0;<span class="tag"><span class="core">core</span></span></a></li>
<li><a href="#sec-7">7. <span class="todo TODO">TODO</span> Group Travel&#xa0;&#xa0;&#xa0;<span class="tag"><span class="corporate">corporate</span></span></a></li>
</ul>
</div>
</div>


# TODO Abstract out the industry page functionality     :corporate:

## DONE Write path helpers so we aren't using media industry path     :corporate:

## DONE See which controller methods can be reused cand which have to be specific     :corporate:

## TODO Look at the landing pages for Press and Commerce     :corporate:

-   These need styling tweaks
-   The backend for these subsections should work

# TODO Photo Galleries     :core:corporate:

## TODO Photo Gallery for Corporate Sites     :corporate:

-   Waiting on a few things from BL
    1.  Mocks
        1.  Mocks for search results
        2.  Mocks for photo gallery
        3.  Dimentions for photo gallery thumbnails and medium views
    2.  If we need to refactor the photo gallery
    3.  Them to classify all of the images into photo galleries

## TODO Photo Gallery for Premium Profiles     :core:


### TODO includes videos     :core:

-   client was thinking youtube videos for premium profiles would be best
-   don't worry about users uploading videos and converting them

### TODO includes multiple photos instead of one

-   Might want to use the Attachment data model

# TODO Remedy server issues     :core:


## TODO Setup alerts on AWS for hard drive space

## TODO Provide estimate for how much work it would take to move to s3

# TODO Sponsored Listings     :core:

-   Have the backend part set up for this
-   Need to start displaying three of them at a time with certain conditions
    1.  If there are three in the interest group, display them
    2.  If there are less than three, get those in the interest group and then pull the rest from the general category
    3.  Need to ask: check if there are city-specific ads and where they need to be pulled in
-   Implement the city-specific ads

# TODO Premium Profiles     :core:

# TODO Banner Ads     :core:

-   This will need to be interest and general category specific ads pulled from dfp

# TODO Group Travel     :corporate:

-   This still needs work and we are waiting to hear by from Michael for the approval process
-   Need to get a deadline for this
