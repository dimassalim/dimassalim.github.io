+++
date = '2024-12-22T17:41:41+07:00'
draft = true
title = 'The increasing need for a more accurate global positioning system'
+++

## Introduction

From surveying to robotics, RTK has been a major player in precise GNSS positioning. For many years, GPS has been giving us up to two meters precision, precise enough to locate our general location, but when it comes to professional job, meters precision just doesn't cut it.

That's when RTK comes in, RTK allow us to get up to millimeters precision, just enough for most jobs that requires precise global positioning coordinate. But, how is it able to give us that much precision when the best GPS can do was 2 meters? That's what we're going to discuss here.

When sending information through space, lights scatters around atmosphere, bounces off objects and sometimes get obstructed before it finally get into our devices increasing the time needed for us to receive the information.

If you're familiar with how EDM works, you should understand that even a microsecond difference in which the lights was received would lead to around 300.000 meters deviation when not counting on the possibility for these errors. We haven't talked about clock errors, receiver noises, and many other issues that makes precise positioning through the satellite challenging, but this should give you a perspectives on how difficult it is to get RTK precisions in our day to day 

## What is RTK?
RTK was a _technique_ to get up to millimeters precisions, the techniques includes reducing most of these source of error, including:
1. Atmospheric errors 
2. Clock errors
3. 