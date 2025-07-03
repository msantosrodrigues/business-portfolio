## SELECTED CASES AND WORKS
- Bolt business case
- Criteo business case
- Teachable/Hotmart business case
- Tiendanube/Nuvemshop business case


### [Bolt business case](https://github.com/msantosrodrigues/business-portfolio/tree/main/company_a)

Bolt is a company in ride-sharing and hailing business in Europe. 
They own operations spanning from car sharing to scooters in Central and Eastern Europe. The goal here was to study and predict pricing variables and improve the upfront pricing prediction mechanisms, making it closer to the final price of the ride. 

The main difficulty here was to define a base fare equation to accommodate the distance and time variables there. After that, I picked up, from the most to the least important, variables involved in the price generation, as phone model (e.g., Uber is known to charge more from iOS than Android devices) and others. All of that wrapped in the usual procedures, as normalization, exploratory, and descriptive analysis.

### [Criteo business case](https://github.com/msantosrodrigues/business-portfolio/tree/main/company_b)

Criteo is an advertising company with global operations. As their business scope is very broad, I had room to bring some different conclusions, but it also brought me lots of difficulties to see what really matters here.
The dataset isn't really complex, with lots of variables, so I brought in many things from actual business scenarios, as well as World Bank and statistics bureaus’ numbers. I think it's very important not to detach the business and data from the real world, always looking beyond the company walls.

The second (and most interesting) part was using the numbers to forecast the sales for upcoming years. Due to the small sample of data, I had to balance the accuracy with the choice of the right technique, being aware of the limitations of each one: exponential smoothing or weighted moving average? Look for seasonality or focus on small timeframe trends? Each choice came with its ups and downs, but at the end, things went well. 

### [Teachable/Hotmart business case](https://github.com/msantosrodrigues/business-portfolio/tree/main/teachable_hotmart)

Hotmart is the largest online courses platform in Brazil. From a few years to now, they M&A'd with Teachable, an American whitelabel platform for all kinds of classes.
My job here was to analyse the scope of businesses regarding Teachable, from countries to most common payment ways (one-time, recurring, installments, etc.). \

The main challenge here was the database size: 1.8mi rows and 450MB .csv file. This kind of configuration took me, first, to Python to prepare the data (normalize/denormalize columns) and do the exploration using the notebook.
To create a dashboard here, I couldn't use the whole database, but create a star schema for data marting the tables, connect and create dataviz using them. It was quite challenging to ensure what's the most important data, select to each fact/dimension table and generate each one separated.

### [Tiendanube/Nuvemshop business case](https://github.com/msantosrodrigues/business-portfolio/tree/main/tiendanube_nuvemshop)

Tienanube/Nuvemshop is a B2B e-commerce platform provider very large in Latin America.
My challenge here was to evaluate the performance of each channel, their KPIs, and suggest changes or improvements. Although it was pretty straightforward, the challenge came from the growth-focused approach that I chose instead of focusing on the % of each channel. 
