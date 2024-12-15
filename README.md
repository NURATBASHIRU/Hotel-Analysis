# Hotel-Analysis
![Hotel_analysis_animation](https://github.com/user-attachments/assets/a33ab9b1-0f44-4e9f-9bf0-e107b63f9579)

## Introduction

Just like every other businesses, it’s very important of an hotelier to continuously assess it business and customers in order to continuously tailor it products and services in a way that will improve it flow of work, customer satisfaction and retention in the long run.

This, however is the essence of the business and customer overview project which is to compare two hotels (resort and city hotel) on the basis of its customers and business performance for further business objectives.

In this project, I performed quantitative analysis that creates deep insights on the customers’ segment and business operations on each hotel type. As a result, I created a twin dashboard that visually demonstrates the results of the analysis.


## Data Overview 
### Data source;
[Kaggle](https://www.kaggle.com/datasets/thedevastator/hotel-bookings-analysis)

### Data Preparation Process
The data set originally obtained from Kaggle contained lots of of encoded information. For example; the country and meal services columns;
<img width="960" alt="dirty_data2" src="https://github.com/user-attachments/assets/6900e048-848e-4eca-be6a-bbf474f906cc" />


### Steps taken;
<img width="960" alt="clean_data" src="https://github.com/user-attachments/assets/6c3708d3-1cd8-4bbd-8899-740e27475a7c" />

<img width="959" alt="pq_hotel_analysis" src="https://github.com/user-attachments/assets/d8223bfe-41c8-49dc-bf4a-ef07aa621072" />



My data cleaning process was executed in Excel power query. And it’s important to note that some of the information encoded in the original dataset are familiar to me due to my academic background in Tourism, Hospitality and Events Management.

And as much as I understood this, it could be a huge barrier for people from other works of life so I had to do further research for transparency and to ensure that the direct meaning are still universally recognized.

So, while cleaning this dataset, I also wanted to ensure that my analysis is readable and easy comprehensible. So, I 
1. Downloaded the Alpha 2 and Alpha 3 country code for all countries and merged each record with its corresponding country name in power query.
2. Decoded BB, FB, SC and HB in the meal column to Bed and Breakfast, Full Board, Self Catering and Half Board respectively.
3. Formatted the date columns into a consistent date format
4. Generated a unique identifier for each record
5. Manipulated the columns for further analysis 
6. Treated empty columns and null values
7. Formatted columns for consistent results 

### Results

### Insights and Recommendations
### City Hotel;
<img width="792" alt="city_hotel" src="https://github.com/user-attachments/assets/8a899cea-5cdb-4d91-b245-6d51b2d923dc" />

The hotel charges an average daily rate of $105 dollars, has received a total of 78,057 guests in the space of 2 years and has a repeat guest of 2,030 - less than 4% of it total guests.

1. The hotel has experienced a up-downward movement of guests arrival with a close upward projection - which means although the business may suffer some down times in terms of gussets arrival but it definitely will bounce back with time.
   ### The hotel should develop means of stabilising the upward tragectory by improving its booking process, ambience and guests' experience.
2. Majority of it guests are “transient” - short time guests; which means they may as well be travelers or tourists; ideally, people who most likely have a short period of stay.
   ### The hotel should devise strategic customer satisfaction motives that would increase its customer retention rate.
4. Some of these transient guests also have babies and toddlers which may also be a reason why they stay a short period of time.
   ### If the guests feel safe enough to visit a hotel with their kids, the hotelier should provide kids-inclusive facilities that would improve customer stay.
5. Majority of it customers come from the North American region.
6. Short-term guests also tend to use a huge capacity of the hotel parking space and as guests increase.
   ### The hotel my run out of parking space.

### Resort Hotel
<img width="804" alt="resort_hotel" src="https://github.com/user-attachments/assets/1454f119-9fd2-45b6-933c-3175841243f3" />

The hotel charges an average daily rate of $95 dollars, has received a total of 39,151 guests in the space of 2 years and has a repeat guest of 1,768 - less than 5% of it total guests.

1. The hotel has experienced a up-and-down movement of guests arrival with a linear projection - although with a lesser down-time compared to the City Hotel.
   ### The hotel needs a marketing strategy that would give it a second wave of guests visitation.
2. Majority of it guests are “transient” and two days lodger; which means they may as well be travelers or tourists; ideally, people who most likely have a short period of stay and albeit short-term guests also tend to use a huge capacity of the hotel parking space but guests who use the parking space are barely up to 2,000 in number which may be an indicator that guests avoid the parking space due to levy - If 2-days occupants contibute to majority of the hotel's guests, then what are the parking space alternative they have been using?
   ### To answer this question, there is a need for deeper analysis. A customer experience questionnaire would help.
3. Some of these transient guests also have babies and toddlers and more requests for special orders.
   ### In order to improve guests stay, there is a need for a tailored guest experience. 
4. Majority of it customers come from the asian region with a weaker threshold.
   ### There is a need to increase it customers' threshold and increase it overall business tragectory.


   Thank you for reading till the end 🙏🏾
   Please, feel free to add your feedback in comments of my LinkedIn post 🤗
