# Introduction to Epidemiological Terms

## Epidemic Parameters

**Attack rate/ratio:** Refers to the \(number of new cases of disease\)/\(population at risk\) during a specified time interval. Generally, the time interval here is defined as “the duration of the outbreak.” \([CDC](https://www.cdc.gov/csels/dsepd/ss1978/glossary.html)\)

**R0 \(basic reproduction number or “R naught”\):** Refers to the estimated contagiousness of an infectious agent and is affected by its biological features as well as human behaviors. Generally, it refers to the average number of people an infectious person is expected to infect in an entirely susceptible population \(i.e., no immunity or vaccination\). For this reason, R0 is by definition unaffected by vaccination but it can change over time and place and is not a constant of the disease \(i.e., an outbreak of a disease can have a different R0 the second time there is an outbreak in the same place if population density is higher\). R0 can also be mathematically defined as follows:

$$
R_{0} = \beta *  \kappa * D
$$

in which **β** is the risk of transmission per contact, **κ** is the contact rate, and **D** __is the duration of infectiousness. \([CDC](https://wwwnc.cdc.gov/eid/article/25/1/17-1901_article)\)

**Re \(effective reproduction number\):** The same as R0 without the assumption that everyone is susceptible. As a formula,

$$
R_e = R_o * X
$$

where X is the proportion of the population susceptible. Therefore, vaccination would decrease X and correspondingly the Re value. Additionally, as more people are infected with a virus, more individuals become immune to reinfection from the virus, and X decreases. When Re &lt; 1, the total number of infected persons declines, and the outbreak dies out. Re = 1 would keep numbers stable, and Re &gt; 1 would lead to continued growth in the numbers of infected persons. Re gives an idea of transmission over time and is useful for monitoring during an outbreak, as compared to R0, which is most useful in forecasting potential severity and spread at the start of an outbreak. \([CDC](https://wwwnc.cdc.gov/eid/article/25/1/17-1901_article), [Giesecke 2002](https://books.google.com/books/about/Modern_Infectious_Disease_Epidemiology_S.html?id=lHSBQgAACAAJ)\)

**Doubling time:** The period of time required for the number of infected individuals in a population to double. \([Vynnycky and White, 2010](http://anintroductiontoinfectiousdiseasemodelling.com/)\)

**Epidemic curve:**  ****A graph of cases vs. time. Most graphs being used in articles are examples of this type of curve. Epidemic curves are most often presented as the number of new \(incident\) cases over time, though may also be presented as the cumulative number of cases. It can be used to make predictions about how well interventions are working and compare across different communities. Like any graph or curve, it is only as reliable as the data it is based on. \([CDC](https://www.cdc.gov/training/quicklearns/createepi/index.html)\)

**Community transmission:** Refers to transmission occurring between people within the same community. This phenomenon is separate from people acquiring the infection while traveling or due to close contact with someone who visited an area with the infection as it implies that there are unknown cases spreading the infection locally. \([CDC](https://www.cdc.gov/coronavirus/2019-ncov/downloads/community-mitigation-strategy.pdf)\)

**Case-fatality rate \(CFR\):** The percentage of patients with the disease \(cases\) who die from the condition. This is sometimes referred to as the case-fatality ratio as it is strictly speaking a proportion, not a rate. This measure is often used as a proxy for the severity of a disease. Mathematically it can be defined as:

_Number of cause-specific deaths among incident cases   
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
                   Total number of incident cases_

Note that incomplete data can skew the CFR. For example, if severe cases are more likely to be diagnosed than milder cases, then the denominator would be artificially lowered relative to the numerator and CFR would be inflated. Conversely, if many people were dying of the cause without being diagnosed \(e.g. at home without interfacing with the medical system\), the CFR could be artificially lowered. \([CDC](https://www.cdc.gov/csels/dsepd/ss1978/lesson3/section3.html)\)

**Mortality rate:** The number of people who died in a defined population for a given time interval. For this reason, it is often expressed as x deaths per 100,000 people. The denominator is the entire population at risk per time studied, and is generally multiplied by 10,000 or 100,000 to make the number comparable to other populations or diseases. Unlike case-fatality rate, this measure is not a proxy for severity, as it does not look only at infected persons, but rather estimates mortality attributable to the disease across the population. \([CDC](https://www.cdc.gov/csels/dsepd/ss1978/lesson3/section3.html)\) ****

## Case Descriptors

**Incubation period:** The period of time between exposure to a pathogen and onset of first _symptoms_. \([CDC](https://www.cdc.gov/training/QuickLearns/exposure/2.html)\)

**Latent period:** The period of time between exposure to a pathogen and onset of _infectiousness_. Note that the latent period can be shorter than the incubation period, leaving a window of pre-symptomatic infectiousness. In addition, virus transmission can happen even with a person that ultimately does not develop symptoms, known as asymptomatic infectiousness.

**Serial interval:** The period of time between symptom onsets in an infector-infectee pair. This period is often used as a proxy for **generation interval**, which is the period of time between infection of an infector-infectee pair. The serial interval helps determine the speed with which an outbreak spreads, and along with Re is a key parameter for how “steep” or “flat” an epidemic curve will appear.

![Adapted from Giesecke, J. Modern Infectious Disease Epidemiology. 2002.](https://lh6.googleusercontent.com/JuXtFn-a7Bq8rz5QTO0taFwFNFbHKmHSDGwUm4ZWQu5OBytoraQTTQ_BwHOEp9x7lA5ePxJl5FwD7tY0TmHg3vCoozyQ7qj7eZkBmmMmYBuoDaSNIEwT9HsU3fsodKfUIaCLp3Wr)

\*\*\*\*

## Non-Pharmaceutical Interventions

### Containment and Suppression

**Contact tracing:** An intervention in which close contacts of known cases are traced, notified of their potential exposure, and encouraged to self-quarantine. Relies on speedy testing and significant effort for each case.

**Quarantine:** An intervention that separates and restricts the movement of people who were exposed to a contagious disease to see if they become sick. Individuals can also choose to self-quarantine. \([CDC](https://www.cdc.gov/quarantine/index.html)\) 

**Isolation:** Separation of sick people with a contagious disease from those who are not sick. Individuals can also choose to self-isolate. \([CDC](https://www.cdc.gov/quarantine/index.html)\)

### Mitigation

**Social distancing:** A [public health practice](https://hub.jhu.edu/2020/03/13/what-is-social-distancing/) that aims to prevent sick people from coming in close physical contact with healthy people in order to reduce opportunities for disease transmission. It can include large-scale measures like canceling group events or closing public spaces, as well as [individual decisions](https://medium.com/@ariadnelabs/social-distancing-this-is-not-a-snow-day-ac21d7fa78b4), such as avoiding crowds. The goal of these interventions is to avoid infecting high-risk populations and “flatten the curve.”

**Peak:** The largest value reached on anthe epidemic curve of incident cases. This value generally refers to the maximal number of patients infected in a single short time period \(e.g. day, week\) in the course of an epidemic. Many mitigation strategies are aimed at reducing this peak in order to minimize the number of cases at any given time and reduce the strain on the healthcare system at any given time. \([CDC](https://www.cdc.gov/csels/dsepd/ss1978/lesson1/section11.html)\)

**Medical surge capacity:** The ability of a medical system to provide medical care for an increased volume of patients or an increased medical demand of patients beyond the normal operating capacity. Therefore, when discussing trying to minimize the surge of the pandemic, we are referring to reducing the demand on the health care system. \([PHE.gov](https://www.phe.gov/Preparedness/planning/mscc/handbook/chapter1/Pages/whatismedicalsurge.aspx)\)

**Flattening the curve:** The concept is based on the reality that the healthcare system can only handle a limited number of sick patients at one time. Measures to “flatten the curve” attempt to slow the spread so that there are fewer cases at any one time \(however, cases are spread out over a longer period of time\) and the healthcare system is capable of providing appropriate care without being overwhelmed. Failing to do so increases the spread of the infection and the case fatality rate as the healthcare system is unable to provide appropriate care to every patient. Should improvements in treatment occur, a larger proportion of the infected population will have access to appropriate treatment. Should a vaccine be developed, more people will gain immunity that way rather than by getting sick.

_Note: flattening the curve does not necessarily mean that fewer people will become infected and require medical care in total - the area under the curve is not necessarily reduced \(even though many graphs on the Internet might suggest otherwise\)_

![](https://lh5.googleusercontent.com/p6vpfE1XTzmhdaALgyghn0X6vFAqaPcCn2wcOOwC6JADJD-YmUWXRXNbJF-zGtMcTV4_1Boe8wn-82gFNueIZi-65woTT4uvG2sZ6VnhzrpPwosaH9_7gMpdasKHnilo8Tb4fMUr)

