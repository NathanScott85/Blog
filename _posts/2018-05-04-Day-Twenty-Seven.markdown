---
layout: post
title: Day Twenty Seven
date: 2018-05-30 23:32:00 +0100
description: 100DaysOfCode Day 27
img: 27.jpeg
tags: [Software, Blog, 100DaysOfCode]
---
# 100 Days Of Code - Log

## Day 27: May 31, 2018

**Today's Progress**: Today I began working on the Burger Builder project as part of the Udemy Course by Maximilian and slowly implementing each section as it was explained to me, I had some issues when working through one particular section where I had not used the correct opening and closing tags  => {} on the Controls section.

**Thoughts:** 
Aside from the issues that I have mentioned above, I worked through each section fine although I find that some parts I did not understand fully: -

<!--- let transformedIngredients = Object.keys( props.ingredients )
  .map( igKey => {
      return [...Array( props.ingredients[igKey] )].map( ( _, i ) => {
          return <BurgerIngredient key={igKey + i} type={igKey} />;
      } );
  } )
  .reduce((arr, el) => {
      return arr.concat(el)
  }, []);

  if (transformedIngredients.length === 0) {
    transformedIngredients = <p>Please Add Ingredients</p>;
  } -->

**Links to work:**

[Burger Builder](https://github.com/NathanScott85/burger-builder/commits/master)