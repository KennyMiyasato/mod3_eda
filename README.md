# Does median income affect encarceration rates or violent crime?

In this project we wanted to assess the following questions:

  * Is there a relationship between median income and violent crime?
  
  * Is there a relationship between mediam income and prison population?
 
Do do so we gathered the following data:

   - Prison Population By State For Years (1978-2016)
        - The Bureau of Justice Statistics - csv file
        
   - Index Crimes by County and Agency (1990 - 2016)
        - data.ny.gov - csv file
        
   - American Community Survey 1-Year Data (2011-2018)
        - US Census API 
        
# Hypotheses 
1. $H_0$ = Prison Population and Median Income are not correlated 

   $H_a$ = Prison Population and Median Income are not correlated 

   ![Prison Population and Median Income are not correlated](prison_pop_vs_med_inc_by_state.jpg)
 
2. $H_0$ = Violent Crime and Median Income are not correlated 

   $H_a$ = Violent Crime and Median Income are not correlated 

   ![Violent Crime and Median Income are not correlated](violence_total_vs_med_inc_by_county.jpg)

3. $H_0$ = There is no statistical significance difference in percent change between prison population percentage and median income percentage from 2010 to 2016
   
   $H_a$ = There is a statistical significance difference in percent change between prison population percentage and median income percentage from 2010 to 2016

   ![There is a statistical significance difference in percent change between prison population percentage and median income percentage from 2010 to 2016](student_t_test.jpg)
   
# Methodology
We used the Pearson's correlation coefficient to evaluate the relationship between two variables.
For both cases we found that there was significant correlation and were able to reject the null hypothesises.

We also used Student's T-Test to find if there was any statistical significance difference to reject our third null hypothesis.
