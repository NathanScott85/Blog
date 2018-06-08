---
layout: post
title: Day Thirty-Two
date: 2018-06-06 23:32:00 +0100
description: 100DaysOfCode Day 31
img: 32.png
tags: [Software, Blog, 100DaysOfCode]
---

# 100 Days Of Code - Log

## Day 32: June 06, 2018

**Today's Progress**: I worked through tutorials for some of today and I ended up traveling into the city where I met up with a Free Code Camp Member and ended up showing him some react that I had been learning.

Example code from the project I worked on offline.

      import React, { Component } from "react";
      import './Recipe.css';
      import propTypes from 'prop-types';
      export default class Recipe extends Component {
        
        static propTypes = {
          title: propTypes.string.isRequired,
          ingredients: propTypes.arrayOf(propTypes.string).isRequired,
          instructions: propTypes.string.isRequired,
          img: propTypes.string.isRequired,
        }

        render() {
          const { title, img, instructions, other} = this.props;
          const ingredients = this.props.ingredients.map((ing, index) => (
            <li key={index}>{ing}</li>
          ));
          return (
            <div className="recipe-card">
              <div className="recipe-card-img">
                <img src={img} alt={title} />
              </div>

              <div className="recipe-card-content">
                <h3 className="recipe-title"> {title}</h3>
                <h4>Ingredients:</h4>
                  <ul>
                  {ingredients}
                  </ul>
                  <h4>Instructions:</h4>
                  <p> {instructions}</p>
                <p>{other}</p>
              </div>
            </div>
          );
        }
      }


**Thoughts:**  I honestly enjoyed today as it gave me a break from the constant overload of information that I have been getting everyday for the past few days.


**Links to work:** 







