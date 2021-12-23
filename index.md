# COVID19_ProportionalDeaths

During the COVID-19 surge of late 2021 fueled by the Omicron variant, I was glued to the news. Specifically, the [New York Times interactive graphs](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjIiKmf0_f0AhVnq3IEHcO7A34QFnoECAkQAQ&url=https://www.nytimes.com/interactive/2021/us/covid-cases.html&usg=AOvVaw3H4cBYqcOslX5JuboWPJFD).

I noticed that I the news seemed to be reporting on rising case loads along with rising hospitalizations and deaths. There was one metric, however, that I could not seem to find. I wanted to know the proportion of new cases that resulted in death. My hypothesis was that this proportion would decrease as more people were getting vaccinated.

To solve this problem, I turned to the [New York Times COVID data repository](https://github.com/nytimes/covid-19-data).  I then created a Jupyter Notebook to pull the data from the NYT and added a new column representing proportions of deaths to cases.


 Figure 1: Rolling Average of new cases and deaths
 
 ![Figure 1: AVG Deaths and New Cases - 7 Day Average](https://github.com/mattlampl/COVID19_ProportionalDeaths/raw/main/output1.png)

Figure 2: Proportion of new cases resulting in death

![Figure 2: Proportion of New Cases Resulting in Deaths](https://github.com/mattlampl/COVID19_ProportionalDeaths/raw/main/output2.png)
