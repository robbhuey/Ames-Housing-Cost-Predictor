# Project 2 - Ames Housing Data and Kaggle Challenge

**Problem Statement:**

Hello, my name is Robert Huey and I am a previous divorce lawyer hired at a realestate firm to help couples find homes in Ames, Iowa. Given the that the housing market has gotten more expensive with inflation, it does make sense that we are seeing an uptick of joint homeowners in the market. By using my previous knowledge in the space and the data provided to me from the firm, I have come up with some graphs and models that will help prospective couple homebuyers have an easy and enjoyable experience to pick something that will be meant to last. 

## Summary

Before we go into the presentation of the data let us explain the contents of this workbook. In total we have 5 total notebooks going in order of how they should be digested.These notebooks will be contained in the "code" folder. The first one will go over the cleaning of the data provided by deleting any columns that were missing too many values and combining others that could be used for future inference like, square footage. The second notebook will go over some exploratory data graphs to find different types of correlation in the dataset to be able to further my research and create my models. This then leads to the pre-processing and modeling notebook which focuses a lot more on taking the data we scrounged from the previous notebooks to start to do modeling predictions. In this notebook we can see the different columns chosen and the different effects each one had on price from the coefficients provided. This also allowed us to infer about the effectiveness of the models tested by looking at various train test splits and R2 scores. Leaving the last portions of the workbook to be focused on the final model that I chose from the pre-processing notebook, and a Kaggle submission to see where I stacked among the other realtors in the area. 

The other two folders for datasets and images will contain the following. Datasets will contain the columns and rows used for the data of the project to come to its conclusions. The images folder will hold the graphs used for my presentations that were exported from the notebooks. 

## Conclusion

From everything we saw in the workbook it became easy to surmise that kitchens play a huge part in the costs in Ames. This can be from either buying a home or selling one the kitchen quality made a huge difference in the cost of a home. Other portions like quality and condition factored into the home buying process as well but not as much as I would think in the general scheme of things. The best way for couples to aim for buying a home here will be to follow 3 simple steps. Pick the neighborhood, house type, and then see how much wiggle room is left in the budget to focus on what add-ons they tell me to be important. Once we have those simple things it becomes a lot easier to send them homes that will become a forever decision or a good investment. 

## Submission

Materials must be submitted by **10 AM Pacific, Friday, July 21**.

The last day for the Kaggle competition will be **5 PM Pacific, Thursday, July 20**.

Your technical report will be hosted on Github Enterprise. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis and models (renamed to describe your project)
- At least one successful prediction submission on [DSIR-626 Regression Challenge](ttps://www.kaggle.com/competitions/626-ames-competition) --  you should see your name in the "[Leaderboard](https://www.kaggle.com/competitions/626-ames-competition/leaderboard)" tab.
- Data files
- Presentation slides
- Any other necessary files (images, etc.)

**Check with your instructors for how they would like you to submit your repo.**

---

## Presentation Structure

- **Must be within time limit of 8 minutes.**
- Use Google Slides or some other visual aid (Keynote, Powerpoint, etc).
- Consider the audience.
- Start with the **data science problem**.
- Use visuals that are appropriately scaled and interpretable.
- Talk about your procedure/methodology (high level).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow logically from your analyses and narrative and answer your data science problem.

Be sure to rehearse and time your presentation before class.

---

## Rubric

Your local instructor will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

**Scores will be out of 27 points based on the 9 items in the rubric.** 
*3 points per section*

| Score | Interpretation |
| --- | --- |
| **0** | *Project fails to meet the minimum requirements for this item.* |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.* |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.* |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |

### The Data Science Process

**Problem Statement**
- Is it clear what the student plans to do?
- What type of model will be developed?
- How will success be evaluated?
- Is the scope of the project appropriate?
- Is it clear who cares about this or why this is important to investigate?
- Does the student consider the audience and the primary and secondary stakeholders?

**Data Cleaning and EDA**
- Are missing values imputed appropriately?
- Are distributions examined and described?
- Are outliers identified and addressed?
- Are appropriate summary statistics provided?
- Are steps taken during data cleaning and EDA framed appropriately?
- Does the student address whether or not they are likely to be able to answer their problem statement with the provided data given what they've discovered during EDA?

**Preprocessing and Modeling**
- Are categorical variables one-hot encoded?
- Does the student investigate or manufacture features with linear relationships to the target?
- Have the data been scaled appropriately?
- Does the student properly split and/or sample the data for validation/training purposes?
- Does the student utilize feature selection to remove noisy or multi-collinear features?
- Does the student test and evaluate a variety of models to identify a production algorithm (**AT MINIMUM:** linear regression, lasso, and ridge)?
- Does the student defend their choice of production model relevant to the data at hand and the problem?
- Does the student explain how the model works and evaluate its performance successes/downfalls?

**Evaluation and Conceptual Understanding**
- Does the student accurately identify and explain the baseline score?
- Does the student select and use metrics relevant to the problem objective?
- Is more than one metric utilized in order to better assess performance?
- Does the student interpret the results of their model for purposes of inference?
- Is domain knowledge demonstrated when interpreting results?
- Does the student provide appropriate interpretation with regards to descriptive and inferential statistics?

**Conclusion and Recommendations**
- Does the student provide appropriate context to connect individual steps back to the overall project?
- Is it clear how the final recommendations were reached?
- Are the conclusions/recommendations clearly stated?
- Does the conclusion answer the original problem statement?
- Does the student address how findings of this research can be applied for the benefit of stakeholders?
- Are future steps to move the project forward identified?

### Organization and Professionalism

**Project Organization**
- Are modules imported correctly (using appropriate aliases)?
- Are data imported/saved using relative paths?
- Does the README provide a good executive summary of the project?
- Is markdown formatting used appropriately to structure notebooks?
- Are there an appropriate amount of comments to support the code?
- Are files & directories organized correctly?
- Are there unnecessary files included?
- Do files and directories have well-structured, appropriate, consistent names?

**Visualizations**
- Are sufficient visualizations provided?
- Do plots accurately demonstrate valid relationships?
- Are plots labeled properly?
- Are plots interpreted appropriately?
- Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?

**Python Syntax and Control Flow**
- Is care taken to write human readable code?
- Is the code syntactically correct (no runtime errors)?
- Does the code generate desired results (logically correct)?
- Does the code follows general best practices and style guidelines?
- Are Pandas functions used appropriately?
- Are `sklearn` methods used appropriately?

**Presentation**
- Is the problem statement clearly presented?
- Does a strong narrative run through the presentation building toward a final conclusion?
- Are the conclusions/recommendations clearly stated?
- Is the level of technicality appropriate for the intended audience?
- Is the student substantially over or under time?
- Does the student appropriately pace their presentation?
- Does the student deliver their message with clarity and volume?
- Are appropriate visualizations generated for the intended audience?
- Are visualizations necessary and useful for supporting conclusions/explaining findings?

In order to pass the project, students must earn a minimum score of 1 for each category.
- Earning below a 1 in one or more of the above categories would result in a failing project.
- While a minimum of 1 in each category is the required threshold for graduation, students should aim to earn at least an average of 1.5 across each category. An average score below 1.5, while it may be passing, means students may want to solicit specific feedback in order to significantly improve the project before showcasing it as part of a portfolio or the job search.

### REMEMBER:

This is a learning environment and you are encouraged to try new things, even if they don't work out as well as you planned! While this rubric outlines what we look for in a _good_ project, it is up to you to go above and beyond to create a _great_ project. **Learn from your failures and you'll be prepared to succeed in the workforce**.
