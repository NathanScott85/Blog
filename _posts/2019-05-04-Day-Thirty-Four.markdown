---
layout: post
title: Day Thirty-Three
date: 2018-06-08 23:32:00 +0100
description: 100DaysOfCode Day 34
img: 34.png
tags: [Software, Blog, 100DaysOfCode]
---

# 100 Days Of Code - Log

## Day 34: June 08, 2018

**Today's Progress**: Today started with me adding a global font to the site wrapper, I added styling to the background image, I added in the use of RGBA and learned about how to use alpha channels on the navbar to make it transparent, I spent a small amount of time working on free code camp which gave a decent change of pace.

    import React, { Component } from 'react';
    import {BackgroundImage, H1, Button} from '../Pages/PageStyles/HomeStyles';
    import Navigation from '../Navigation/Navigation';
    import {Wrapper} from '../../Containers/Wrapper';
    class Home extends Component {
        render () {
            return (
                <div className="Home">
                    <BackgroundImage>
                    <Wrapper>
                        <Navigation/>
                            <H1>Get Stuck In</H1>
                        <Button>Explore</Button>
                    </Wrapper>
                    </BackgroundImage>
                </div>
            );
        }
    }

    export default Home;
The results are shown below: -

![Maps and Sets]({{site.baseurl}}/assets/img/comparison.jpg)

**Thoughts:** I did not have much difficulty today and most of the FCC work was on css, i think one or 2 problems they gave me got me thinking but it is nice to be seeing results of the past 30 or so days.

**Links to work:**
[National Parks](https://github.com/NathanScott85/national-parks/commits/master)
