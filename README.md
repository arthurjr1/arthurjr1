# Arthur Tartee
## Graduate Student, American University: SIS

People first person looking to solve solve society intractable problems with others who are seeking change to the status quo.

### Skills

- Programming
  - `R/RStudio` especially `tidyverse` like `ggplot(data=x, aes(y=var1)))`
  - git
 
- Statistics and econometrics 
  - Descriptive analysis
  - Inference
  - Regression
  
- Data 
Statiscal Skills

### An example of my skills

Here's some code I wrote in `R`:
```
# "tidy" the data by lengthening
mx %>%
  pivot_longer(
    cols = 5:15, # try different specs to see what can go wrong
    names_to = 'Year', # new var recording col names
    names_transform = list(Year = as.integer),
    values_to = 'CO2emit'  # new var recording the data
  ) %>%
  ggplot(aes(x = Year, y = CO2emit)) +
  geom_line() + geom_point()
```

### Hi there 👋

<!--
**arthurjr1/arthurjr1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
