# setu-product-demo
This Repo contains product demo for setu.in
The script is written in python as an ipython notebook.
Pandas used for data analysis
Sample data created with reference from : https://www.who.int/selection_medicines/country_lists/India_NLME_2011.pdf

# Problem statement:
## Personalized Pill Pack Recommendation

Details - We have a scientifically designed sense test where we ask around 15-20 questions depending on the goal user selects and after considering user inputs, we recommend the best products (2-3 products for each goal) to help achieve your goals.

Sense Test - [https://www.setu.in/hra/](https://www.setu.in/hra/)

Instead of recommending multiple products, we want to recommend a pill pack that will consist of one pill from each product. So instead of sending 3 product bottles for 1 month,  there will be 30 pill packs and each pack will have 2-3 tablets depending on the recommendation.

We have to build this logic on the fly after the user takes the sense test. Few points to be noted

1. These pill packs will be dispatched from a different warehouse
2. It will depend on the availability of the pill packs, if not available then we’ll recommend the individual products only, else recommend the pill pack.
3. We might need to make the design changes on the result page.
4. How the order creation will happen differently and how you will push this information to the warehouse.
