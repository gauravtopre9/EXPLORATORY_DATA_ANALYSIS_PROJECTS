# DMart Products Analysis 

<p>
<img src="https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter">
<img src="https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge&logo=Python">
</p>

<a href="https://www.kaggle.com/code/gauravtopre/dmart-products-analysis/data">
<img src="https://img.shields.io/badge/Data%20From-Kaggle-blue">
</a>

## Introduction 

DMart as we know is the most popular supermarket chain across the nation and the most attractive fact about DMart is the high discount offered on various kind of products and this project is dedicated to the analysis of products present at Dmart.

## About the Dataset 

The dataset contains the products listed on the website of online grocery store Big Basket.

Avenue Supermarts Limited, d/b/a DMart, is an Indian retail corporation that operates a chain of hypermarkets in India. It was founded by Radhakishan Damani in 2002, with its first branch in Powai's Hiranandani Gardens.

**Description of Columns:**
1. Name : Name of Product
2. Brand : Brand of Product 
3. Price : Original Listed Price / MRP
4. DiscountedPrice: Price after Discount 
5. Category : Category to which the product belongs
6. SubCategory : subsection of the category to which the product belongs
7. Quantity : Quantity in which the product is being sold (can be weight or no.of items or any such combination) [We haven't used this]
8. Description : Description of the product
9. Breadcrumbs : Category Breadcrumbs [We haven't used this]

**Derived Columns:**
1. DiscountPercent : Percent of discount offered on perticular product


## Few Important Insights of this analysis:

1. **Mean Price,DiscountedPrice and DiscountPercent** are as follows

    * Price : Rs.344
    * DicountedPrice : Rs.237 
    * DiscountPercent : 26%
    
 2. DMart Sells **NAGIN INDIAN HOT SAUCE** for Rs.1 which saves Rs.49 from customers wallet😍.
 
 3. **Wordcloud** on the basis of Description
 
 ![image](https://user-images.githubusercontent.com/80534916/187941206-aa905d44-10e5-42ad-af1a-e068ab4837f1.png)
 
 
  **From here only we can directly conclude that max products will be having Skin in their description so maximum number of products will be from personal care category.**
 
 4. The dataset was having few flaus as **Wonderchef, Syska,pigeon,Zebronic,Geep,Joyo Plastic and Butterfly** were mentioned as categories whereas they are the names of brands, so we have corrected them.
    
    * Zebronic is a Mobile Appliances manifacturing Company so category for these columns will be Appliances and Subcategory will be appliances only.

    * Syska manifactures electrical equipments which we use in home so we will allot it to Home & Kitchen Subcategory will be Home Appliances.

    * Geep will be in Appliances Category,subcategory is also appliances.

    * Butterfly will be alloted to Home & Kitchen and subcategory will be Kitchen Appliances.

    * Pigeon will be alloted to Home & Kitchen and subcategory will be Kitchen Appliances.

    * Joyo Pastics will be alloted to Home & Kitchen and subcategory will be Kitchen Appliances.

    * Wonderchef will be alloted to Home & Kitchen and subcategory will be Kitchen Appliances.
 
 5. **Number of Products(unique) available per category**
 
 ![image](https://user-images.githubusercontent.com/80534916/187942193-3fe090a0-b96e-45c7-91fb-4fb1fb38d976.png)

6. **Analysis on Avg. Discount per category**

    * DMART is offereing high percent of discounts on those categories in which we usually purchase.
    * Though Smartwatches,Backpacks and Computer Accessories are at top 3 positions in list but the number of product or the variety in them is quite less. So the main categories which are attracting the cutomers by discounts offer in them are

        1. Colthes and Accessories 
        2. Beauty and Cosmetics
        3. Personal Care 
        4. Packaged Food 
        all above listed categories are having avg.Discount above 25%
        
    * In Dmart Baby & Kids Products are offered with least Avg.Discount as well as the variety is not that much (Here DMART can play big Game and by working on this Category they can be a competitor of stores like FirstCry.com,etc).

    * Dmart Groceries which comes under the production and packaging of DMART is having more discount as compared to the other Grocery products.

7. We found out two types of Groceries in Categories column of our dataset and those were **DMart Groceries** and **Other Groceries** below is the comparison of their prices

    * DMart Rice avg Price 437
    * Other Rice avg Price 348
    * DMart Rice avg Discount 24
    * Other Rice avg Discount 22
    
8. We analysed **clothings👕** and found put following numbers

![image](https://user-images.githubusercontent.com/80534916/187946659-1378809f-1720-4310-8ac3-64de02447711.png)


### These were few of the insights which I have drafted from the notebook for more so visit my Kaggle Profile

<p align ="center">
<img src="http://ForTheBadge.com/images/badges/built-with-love.svg">
</p>
    
