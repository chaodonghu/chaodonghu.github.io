---
layout: post
title: "Instagram Mass Follow, Unfollow, Like Scripts"
date: 2022-04-11
description: 3 separate Google Chrome scripts that allows (1) user to mass follow instagram users on another's profile, (2) user to mass unfollow instagram users on another's profile and (3) user to mass like posts on a certain hashtag/search query.
author: Dong Hu
tags:
  - Portfolio
---
I had always wondered how businesses or influencers are able to gain hundreds of thousands of followers overnight. Many accounts go instantly viral after a certain tweet or post but I was curious if there was more to it. There are some accounts that have hundreds of thousands of followers but only one or two posts. I realized that there was this concept of "buying" instagram followers or likes, a pay for followers businesses that several companies offer by attracting real instagram users to your account instead of spam or bot accounts. Simply put, wouldn't that just mean liking and following/unfollowing accounts that are similar to yours? This inspired me to make 3 scripts that were relatively easy to use and required zero setup and configuration to mimic this pay for followers/likes model.

<hr />

#### Mass follow

I started off thinking about how one could gain followers. There is a notion of following back users that have followed you, so what if you followed users of a certain page/account to garner similar interest. For example, following all the followers of a ontario hiking page would prompt the followed accounts to click on my account after I follow theirs. This simple engagement tactic would not guarantee a new follower but possibly a page hit or post like on your most recent posts.

I wanted to make the process as easy as possible with no overhead of running or hosting an app. I looked into a simple vanilla javascript script that clicks on the relevant elements in the DOM which could be copy and pasted into the google chrome console. A simple timeout that is configurable would help to throttle the number of follows/clicks on the page to bypass instagram's bot detection.

<script src="https://gist.github.com/chaodonghu/c25c7ee3e3eb85c0a0de051892e596a4.js"></script>
