
# Project 2 (Ames Housing Data)

### Problem Statement
We are a property consultancy firm that aims to help residential home owners estimate the selling price of their homes. We thus aim to identify the features that are most important to predict sales price. This would allow us to provide our clients with an easy tool that gives quick estimates of how much their homes are worth, and help them identify aspects of their properties they can improve on to increase their selling price.

### Contents
- [Problem Statement](#Problem-Statement)
- [Data Dictionary](#Data-Dictionary)
- [Conclusions   and Recommendations](#Conclusions-and-Recommendations)
- [Rubrics](#Rubrics)

### Data Dictionary
|Feature|Description|
|---|---|
|**sale_price**|The price at which the house was sold.|
|**property_size**|The size of the house in square feet.|
|**overall_qual**|The quality of the material and finish of the house.|
|**overall_cond**|The condition of the house at the time it was sold.|
|**property_age**|The number of years since the house was first built at the time it was sold.|
|**num_floors**|The number of floors in the house.|
|**num_bedrooms**|The number of bedrooms in the house, not including basement bedrooms.|
|**num_full_baths**|The number of full bathrooms in the house, including those in the basement. Full bathrooms are bathrooms that contain a sink, a toilet, a shower, and a bathtub.|
|**num_half_baths**|The number of half bathrooms in the house, including those in the basement. Half bathrooms are bathrooms that contain a sink and toilet, but no bathing facilities.|
|**num_kitchens**|The number of kitchens in the house.|
|**num_fireplaces**|The number of fireplaces in the house.|
|**has_remodeled**|Binary variable representing whether the house has ever been remodeled.|
|**has_bsmt**|Binary variable representing whether the house has a finished basement.|
|**has_unf_bsmt**|Binary variable representing whether the house has an unfinished basement.|
|**has_garage**|Binary variable representing whether the house has a finished garage.|
|**has_unf_garage**|Binary variable representing whether the house has an unfinished garage.|
|**has_porch**|Binary variable representing whether the house has a porch or deck.|
|**has_fence**|Binary variable representing whether the house has a fence.|
|**has_pool**|Binary variable representing whether the house has a pool.|
|**near_road**|Binary variable representing whether the house is adjacent to or within 200' of an arterial or feeder road|
|**near_rail**|Binary variable representing whether the house is adjacent to or within 200' of a railway station.|
|**near_pos**|Binary variable representing whether the house is near a positive feature such as a park or greenbelt.|
|**area_(name)**|Dummy variables representing the neighborhood in which the house is located in.|

### Conclusions and Recommendations
## Conclusions & Recommendations
---
The goal of this project was to identify the features that are most important to predict sales price, so as to provide clients with an easy tool that gives a quick estimate of how much their home is worth, and help them identify aspects of their properties they can improve on to increase their selling price. Based on the results of model 3, our recommendations are:

1. **The overall quality of building material and finish is the strongest indicator of selling price:** 
Clients should pay attention to material and finish when purchasing homes to maximize resale value. Clients may also consider refurbishing homes with better material and finishing to increase resale value.

2. **Older houses sell for much less than newer houses:** 
Clients should sell their houses when they are still new, and take care to purchase newer houses to maximize resale value.

3. **Overall condition of the house is a strong indicator of selling price.** 
Clients should take care to maintain the condition of the house to maximize resale value. If the condition of a house has deteriorated over time, the client should attempt to restore the condition of the house as much as possible before selling it.

4. **Larger houses sell for more.** 
Clients should purchase houses that come with larger plots of land. Extending the house if there are large areas of unused land will increase resale value.

5. **The number of bathrooms, bedrooms, and fireplaces are important.** 
Clients should take note of the number of bathrooms and bedrooms when purchasing a house. Building additional bathrooms and bedrooms if there is space can also increase resale value. Building another full bathroom is likely to result in the biggest increase in resale value, followed by building another bedroom, building another fireplace, and then building another half bathroom.

6. **Having a porch or a garage increases resale value, but an unfinished garage decreases resale value.**
Clients should try to buy a home with a porch and/or a garage, finished or unfinished. If the client's home has an unfinished garage, they should finish the garage before selling it to maximize resale value. If the home doesn't have a porch, the client can consider building a porch if there is unused land around the house.

7. **Being near a railway station or major road decreases resale value, but being near a park or greenbelt increases resale value.**
Clients should try to buy homes near greenery that are away from major roads and railway stations. It's possible that being near to major roads and railway stations results in noise pollution, which lowers the value of the property. An alternative explanation is that buyers in Ames City tend to prefer homes that are more secluded.

8. **Having a basement, a pool, or more than one kitchen is not guaranteed to increase resale value. Having more than one kitchen MAY in fact decrease resale value.**
In purchasing a house, clients who seek to maximize resale value should not pay too much attention to whether the house has a basement, pool, or more than one kitchen. If they have already purchased a house with extra kitchens, they may consider converting extra kitchens into bedrooms or bathrooms.

9. **Remodeling a house in itself is not guaranteed to increase resale value.**
If a client is seeking to increase the resale value of their home, they should try to purchase a house that has the previously-mentioned qualities. If they have already bought a home that has a suboptimal resale value, they should remodel strategically according to the previous recommendations.

10. **Location strongly affects the resale value of a house.**
Clients should purchase house in better neighborhoods. The best neighborhoods to own a house are Northridge Heights, Crawford, and Northridge. The worst neighborhoods to own a house are Briardale, Meadow Village, and Edwards.

### Rubrics
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