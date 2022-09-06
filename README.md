# 2008 Flight Data Exploration
## by (Mukhtar Abimbola)


# Dataset

> The flight data set consist of information regarding flights and airline operations in the USA for year 2008 from January - April. It consist of 2,389,217 entries and 29 column flight opertional variables. Notable among these variables are arrival and departure times, arrival and departure delays, flight cancellations and diversions. These are the variables of interest used for the data exploration.
> Consequently, plane data was also downloaded and merged with the original flight data set. The plane data consist of 5,029 entries of all aircraft information including the aircraft types, engine types and their manufacturers.
 


# Summary of Findings
## **Univariate Exploration**
>- ### **Cancellations**
>>- 2.7% of the flights were cancelled.
>>- American Airline(AA), American Eagle Airline Inc(MQ) and Skywest Airline Inc(OO) are the most cancelled airlines.

>- ### **Diversions**
>>- 0.2% of the flights were diverted.
>>- Flights were mostly diverted on Tuesdays and least diverted on Thursdays.

>- ### **Delays**
>>- 25% of the flights were delayed on arrival.
>>- 21% of the flights were delayed on departure.
>>- American Airline(AA) had the highest arrival delays followed by South Western airline(WN).
>>- Aloha airline(AQ), Hawaiian Airline(HA) and Frontier Airline(F9) had the least delays on arrival.
>>- WN had the highest departure delays while HA, AQ and F9 had the lowest delays.
>>- Arrival and departure flights had average delay of 1 hour with 2 days delay as the maximum delay for arrival.
>>- Delays due to Late aircraft was the highest, about 22 minutes.
>>- Security reason had the least average delay time.


## **Bivariate Exploration**
>>- Corrleation between arrival and departure delay times are highly positively.
>>- There is no corrleation between Flight distance and mean arrival delays.
>>- Most aircraft manufacturers used Turbo-fan,Turbo-jet, Turbo-prop and reciprocating engines.
>>- Turbo-fan and Turbo-Jet had the highest counts of usage and was also found most common aong the carriers.
>>- Fixed wingsingle-engine and fixed wing-multi-engine aircraft are the most common aircraft types.
>>- Turbo-Shaft engines contributed most to carrier delays followed by Turbo-prop and 4-Cycle engines.
>>- Turbo-Prop engines contributed most to weather delays followed by reciprocating engines while Turbo-shaft which is least contributor.
>>-Most cancellations involved Fixed wing multi-engine aircrafts with Turbo-fan,Turbo-jet and Turbo-prop engine types.
>>- carriers with rotorcraft and ballon aircraft had no cancellations.
>>- Fixed wing single-engine aircraft contributed most to late aircraft delays while Fixed wing multi-engine contributed least.
>>- Turbo-prop engines contributed most to late aircraft delays just like it did for carrier and weather delays as well as high cancellations when used in fixed wing multi-engine aircraft


## **Multivariate Exploration**
>>-  Number of flights movement affects average arrival delay times in the most busy airports. 
>>-  Weather and late aircraft reasons contributed most to overall delays



# Key Insights for Presentation
>> - The presentation will focus on  flight cancellations and delays.
>> - Reasons for each variabless will be presented in relation to their contributions in the number of cancellations and delay times.
>> - Aircraft engine type will also be considered as a factor that influences flight cncellations and delays.
>> - Appropriate visualizations will be used  to  convey all important information with the right clear titles and axes labels.


```python

```


```python

```
