# Introduction to Measures of Disease frequency
- Measure the occurrence of health outcomes to **monitor changes** and **plan interventions**.
## Health outcome occurrences: Measures of frequency
For more details, look at the attached handouts.
1. **Prevalance**: malaria affects 10% of the world's population.
2. **Risk**: there's 50,000 newly infected cases of HIV a year, divided by the # of individuals at risk in the US
3. **Rate**: the overall death rate from cardiovascular disease was 236.1 per 100,000 person-years in 2009 in the U.S.
4. **Odds**: out of 100 births, the probability of having a boy is 51% and having a girl is 49%. Therefore, the odds of having a boy is 51 to 49 = 1.04
## Prevalent vs Indident cases
|                          Incident cases                          |                           Prevalent cases                          |
|:----------------------------------------------------------------:|:------------------------------------------------------------------:|
|                      *new* cases of disease                      |                       *all* cases of disease                       |
| individuals who change in status over a specified period of time | individuals with outcome of interest, regardless of when diagnosed |
|                      calculate rates, risks                      |                        calculate prevalence                        |

**Eg**: Imagine you have a repo of c++ files. Each c++ file in the repo is a prevalent case. When you add new c++ files to the repo, these are still *prevalent cases*, but since they are new, they are also called *incident cases*. Each c++ file removed from the repo represents a death/recovery.
## Prevalence
* Formula: Existing cases/total population
* Proportion of a *defined* population that has the health outcome
	* When can't we define a population for certain health outcome?
* Uses existing cases of the health outcome
	* Cases whose health outcome developed or was diagnosed **before** they were identified for the study
* Quantifies the burn on a population
* Useful for planning health services.
* Note that population is health outcome specific. You wouldn't want to include the whole population of the US in the denominator if you're trying to calculate the prevalence of abortion of women between the age of 12 to 19.
* A time period is crucial here, without this the result wouldn't be called prevalence. So also called as a *cross-sectional* measure because it measures the health outcome at once slice in time

**Eg**: 11% of the us population of age over 65 has alzheimer's disease.
### Analogy
Let's use the above example of my c++ repo. Suppose the repo's on disk X. The *prevalence* is the space the repo has on the disk to the total available space on the disk at a specific point in time, like now.
### Two types of prevalence measurements
#### Point prevalence
- Prevalence at one point in time.

**Eg**: "do you *currently* have asthma?"
#### Period prevalence 
- Prevalence over a specific period of time, divided by the number of the population in that period of time.

**Eg**: "have you had asthma in the last **3 years**?"
### Example
* 500 men with lung cancer
* asked about smoking habits
* 451 men smoked more than a pack of cigarettes a day

=> prevalence: 461/500 = .922. so the prevalence of smoking among 500 men with lung cancer is 92.2%
## Risks
### Elements of calculation
* Numerator: incident cases (i.e. new cases identified during study follow-up)
* Denominator: study population at risk at the beginning of follow-up
### Use
- Measures the number of **new** cases of the health outcome that develop among people in the population at risk, over a specified time period.
- Refers to the probability that a health outcome will occur.
### Assumptions
- closed study population: no new participants
- a specified time period
- people do not enter or leave the study
### How to calculate
1. Define population at risk
2. Determine # of *incident* cases
3. Specifying the time period
### Example
* 4,000 students at a college were followed over 4 years, or until the dropout. 70 cases were identified over the 4 year study period.
* What's the **risk** of developing the outcome of interst: dropout?
Risk = 70/4000 = .0175 = 17.5 students per 1000 over 4 years.
## Rates
* Measures the **occurrence** of new cases of a disease or health outcome in a population.
* Not a proportion because the denominator is not fixed.
* Effective for the situation when a population is changing over time (people can enter and leave the study).
## How to calculate
1. Define population at risk
2. Determine # of new cases
3. Determine denominator (person time at risk)
## What is person-time
* The sum of times that each person remains at risk for the health outcome **and under study observation**.
* Person-year, person-month, etc.
### Person-time can stop when
- death
- people leaving the study
- health outcome develops
- researchers can't do follow-up
## Odds
- Probability that an event will occur to the probability that it will not: 
```latex 
odds = p/(1-p)
```
### Example
* If the probability of heart diseases in a patient is 4.7%, then the odds of hearth diseases are: 4.7/(100-4.7) = .049 = 1:20

