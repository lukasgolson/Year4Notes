Objectives

-   estimate the probability and risk of damage to populations and
    infrastructure
-   understand impacts of weather and land change impacts on extreme
    events

 

Reason

flooding is the most destructive disaster worldwide. Most common.
Incredibly costly.

 

Definitions

probability density function (pdf): a function that roughly models a
distribution.

return period: the time it takes on average for Q to happen

 

Q: discharge  P: probability Tr: return period

 

Equations

-   p = 1/tr
-   Tr = 1/p

Nuances

area under the probability density curve is always 1

normal distribution only has 2 variables (mean and variance).

some distributions, such as Gumbel, have a third parameter (skewness).

 

 

Assumptions of flood frequency analysis

1.  Time series of floods is a set of independent observations.. This
    assures that a hydrologic event such as a single large storm does
    not enter the data set more than once. A single storm system may
    produce two or more runoff peaks, only the largest should enter the
    data set.
2.  The time series of floods is homogeneous. This assures that all the
    flood observations are from the same population, for instance:
    1.  Stream gauge has not been relocated
    2.  Land use change has not occured
    3.  No structures have been placed on the stream or its tributaries
    4.  There are no major natural lakes upstream of the stream gauge
    5.  Climate has not changed or changes are accounted for

Two methods for frequency analysis

-   Graphical method:
    -   Using data records to estimate Tr and P within the observed
        data.
        -   Rank magnitude from largest to smallest. Largest = 1;
            smallest = n
        -   Calculate exceedance probability \[p = m / (n + 1)\]  or
            return period \[(Tr) = (n + 1) / m\]
-   Analytical method
    -   Using a theoretical pdf to extrapolate beyond the observed
        record
    -   Assigning probabilities to events, where every event has a
        probability of occurrence
    -   Every location has a specific probability density function
        (pdf), but we don't know it
        -   Fitting and testing pdf: we assume the overall shape of the
            pdf but use the data to obtain the parameters
        -   Different distributions may give equally good fit to the
            sample sample of observed floods but may have different
            extrapolation capabilities leading to significantly
            different estimates of extreme foods such as 100-year event.
    -   Selection of appropriate pdf:
        -   Larger the dataset, the more parameters that can be
            included.
        -   One approach is to test various pdf, and select the one with
            the best fit.
-   Some considerations:
    -   Frequency analysis is only valid when conditions are stable.
    -   Changes in mean and variance caused by variability in climate
        and land use can have a significant impact on extreme events.
    -   Graphic method works best in the middle range of the dataset;
        uncertainties grow in the extremes.
    -   Sample size and pdf selection are critical.
    -   What is the link between the number of parameters of a pdf and
        the sample size.

Applications, examples, and uses

Risk (R): Probability of exceeding an event at least once in the next n
successive years.

 

Probability of non-exceedance (q):

q = 1 - p

Probability of non-exceedance in n successive years:

q\^n = (1 - P)\^n

Risk (R):

1 - (1 - p)\^n = 1 - (1-(1/Tr))\^n

 

Example: the lifetime of a stream crossing is 25 years; the stream
crossing was originally designed based on the 100-yr design flood. What
is the risk of failure of the stream crossing in its lifetime?

R = 1-(1-(1/Tr))\^n = 1-(1-(1/100))\^25 = 0.222 = 22.2%

 

 

Risk-based design

-   Projects involve risks to environment, property, and life
-   When danger to human life is absent, the design will focus on
    minimizing total expected cost.

 

Frequency-based design

-   Selection of a frequency or return period for the design of a
    structure is most often based on potential damage to the
    environment, property, danger to life, and economic loss
-   Forest practices code requires all stream crossings under forest
    roads to be designed to convey the 100-year design flood

 

Chronological Pairing (vs. frequency pairing)

Two reasonably similar watersheds are selected for comparison: one to
serve as a control, the other to undergo a treatment such as logging. At
certain time intervals (e.g. the year 1993) or at certain dates (e.g.
April 7th, 1993), some aspect of each watershed - such as peak flow - is
measured. The fact that these measurements are made and compared at the
same time is the distinguishing characteristic of chronological pairing,
and is what allows you to construct the graphs where the peak flow of
one watershed is on the X axis while the peak flow of another watershed
is on the Y axis: each point on that graph represents a moment in time. 

This approach seems fairly intuitive and logical on the face of it
because it appears to control for certain environmental factors: the
assumption is that if one year has an especially snowy winter and the
paired watersheds are close together, then you would expect to see that
reflected in both the control watershed and the treatment watershed. 

Younes, however, claims that the underlying assumption that paired
watersheds will be in similar states at similar times is incorrect
because there's a high degree of stochasticity in natural phenomena:
just because the one watershed has a big snowpack in a given year
doesn't mean that the other will. Because of this stochasticity
chronologically pairing is an "uncontrolled experiment": no one's
checked that every potential confounding variable - such as antecedent
soil moisture -- is being controlled; therefore, you can't say whether
or not a hydrological response is due to a treatment or some other
reason. 

Frequency pairing fixes this problem by doing away with the time
element. Rather than asking "how big were the floods in watershed A
versus the floods in watershed B in years C, D, and E after it was
logged?", the question becomes "since we logged watershed A, how have
its biggest floods compared to watershed B, and how often have those
occurred?" The idea is that, for stochastic reasons, watershed A might
be more prone to having big floods in 1993 while watershed B might be
more prone to having big floods in 1994, so you compare the floods that
these years produce, rather than comparing watershed A in 1993 with
watershed B in 1993.

Another way to think about it: If you look at the graphs associated with
CP, the peak flows of two watersheds are paired as a function of time
(i.e. time is on the X-axis); so the question is "how big was the peak
flow of each watershed at time T?". When you look at the graphs for
frequency pairing, return interval is on the X-axis, so the question is
"how big is teh 100-year peak flow of watershed A versus watershed B?".
CP assumes that time controls for all pertinent variables; with FP, you
know that all stochastic variables are being controlled for by comparing
between years.
