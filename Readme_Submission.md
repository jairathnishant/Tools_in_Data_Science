<!-- Start here -->
# Steps Comparison App
![Markdown logo](https://markdown-here.com/img/iconf256.png)

<p><strong>Finally</strong>, here is the app to track the steps <em>you</em> walk each day and compare it against your competitors for leaderboard creation </p>
---
## Own steps calculation
> Download the **Stepper** app on your android or iOS mobile and follow below steps -
1. Sign-up on the app and add your details 
1. Toggle **Step Counter** button for recording your steps
2. Choose the *start date* and *end date* for comparison
3. Here is the link to app for quick access
[Stepper](https://github.com/jairathnishant/Tools_in_Data_Science "Stepper App")

---
## Competitor steps calculation
> To compare the steps with your fellow competitors please follow the below steps:

<!-- Unordered List -->
* Go to homepage of the app
* Click on import contacts list
* Click ok and give it a few mins
* Click on the *Contacts* button
  * Select the people from the list
  * Invite anyone who is coming as ~~strikethrough~~
  * Click on **Compare** at the bottom
 
---
## Comparison output

Find the mean of steps taken during the duration selected between start and end date.

```r
x <- c(1, 2, 3)
mean(x)
```

You will ultimately get a leaderboard table like below -

<!-- Table -->

| Name    | Duration | Total Steps | Average Steps | Rank |
|---------|----------|-------------|---------------|------|
| Nishant | 4 weeks  | 10000       | 2500          | 2    |
| Anand   | 7 weeks  | 15000       | 2700          | 1    |
| Anshul  | 2 weeks  | 1000        | 500           | 3    |

## Next steps

Congratulations on getting started. Please follow through the rest of steps (unmarked) to reach the finals!

* [x] Download the App and Sign-up
* [x] Start recording your steps and add competitors
* [ ] Record for at least 8 weeks to go to next round
* [ ] Submit your average step count to keep advancing