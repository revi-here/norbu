# Norbu Stress Control
<b> by Revathy Thiyagarajan  
  
Norbu Stress Control is an anti-stress app that teaches to manage stress and emotions on the physical level.  
Anxiety relief games, breathing exercises and guided meditations help to develop stress-control habits.  
“5-days unlock Premium for free” feature makes these premium exercises available for those who really need them for no cost.
Norbu app has guided meditations and antistress trainings. The exercises are very simple and safe.You can meditate and breathe with a guide or in silence.
Our project is to work on various factors impacting Conversion Rate for the 'Norbu' app and come up with solution.

Problem Statement : Low CR in payment.
What is the best mechanism for switching from the free version to paid one to make it convenient for the user, and at the same time increase the payment or increase the duration of use of free version?  
  
*** 

## Resources
1.Data Source   
2.Data analysis : Pandas , Numpy  
3.Database : PostgreSQL  
4.Matplotlib,Pyplot,Seaborn
  
***
## Exploratory Data Analysis.  
 
 Considering the size of the data , March 4,2022 to Apr 4,2022 data used mostly for our analysis.  
  
<b>1,3,7 days IOS Retention  
![IOS Retention](images/android.png '1,3,7 days IOS Retention')  
<b>1,3,7 days Android Retention  
![Android Retention](images/ios.png '1,3,7 days Android Retention')  
***Conclusion***  
Average Day 1 ,Day 3 and Day 7 retention of IOS users are comparitively lower than android retention rates.  
We do see some really high retention rates(IOS) as maximum -- 42% for 1 day ,20% for day 3 and 13% for day 7 retention but with a very rare occurence..
<b>Event funnel  
![Event funnel](images/user_funnel.png 'Event funnel')   
Of the total users only 5% ends up in paid subscription  and around 11% opts for free trial..  
Of the users in free trial , only 1 user less than 1% go for paid subscription..
<b>DAU (Daily Active Users)
![DAU](images/dau.png 'DAU')  
The average session length is around 7-8minutes consistently for almost all the sessions..
Daily Active User and total number of sessions shows similar pattern of spike and dips..  
Most of the user have 1 session per day with average session duration of 7-8 minutes..  
 
<b>Free users<br>
![Free users](images/free.png 'Free users')  
<br>
<b>Paid users<br>
![Paid users](images/paid.png 'Paid users')  
 <br> 
 Of the total users , only 5% buy paid subscription. 
 ‘norbu_annual’ ,’app.norbu.premium’,’norbu_mounth’, ‘norbu_month_ios’,’app.norbu.premium_sale’,’norbu_mounth_sale’ are the products bought by paid subscription.
 Though in pricy side ,’app.norbu.premium’ is used by more users (30$) as well as on sale for 15-20$.   
 
# Final Conclusion.   
From all the above points we see that we need to get some changes with IOS as IOS retention is lesser compared  
to Android and also conversion rate from free to paid user is way less..Users are not in free trial for required time period..  
So we need to either change the plan for free trial or add some interesting features to attract user to stay for the full time  
and proceed with paid subscription..'app.norbu.premium' can be given with some extra features in the range (15-20$)for Android  
users as more users prefer this price range...These changes will improve the retention rate and conversion rate ..

 # Presentation.  
 [Presentation](https://docs.google.com/presentation/d/1kP_OW7dlzC85_vj1VnEM1rtyPvFN04u-/edit?usp=sharing&ouid=113662054605653502082&rtpof=true&sd=true)
  
  
  
  

