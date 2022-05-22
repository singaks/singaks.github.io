# Understanding Growth

# **Growth**

Growth models and understanding of the growth curve holds a pivotal role in the research and investigations related to various domains of pursuit. An epidemiologist for instance is interested in the prevalence, decay and growth of bacteria or viruses in the affected population. An ecologist is interested in the population growth of one or many of the species. An economist must be interested in the aggregate growth of economic health indicators.  A business owner is interested in understanding the growth of sales and revenue metrics. What is common in all of these studies is

1. [**Measure-eta**] Metric(s) chosen to proxy the *target of study* and *levers* that control the mechanics of change in the measure. E.g. Affected population, GDP , etc.
2. [**Model-zeta**] A model to understand the nature of association between the levers that control the increase/decrease of *target-metric*

$$
\eta_t = \eta_{t-1}(1+\gamma(\Theta)) = \zeta(r)\eta_{t-1}
$$

# **FinTech Services**

In this article, we try to understand the growth model from financial service business perspectives and economics that are used to sustain the growth.

## **Conceptual Framework**

Financial service providers solve the financial needs and wealth aspirations of the customer. Theoretically,  the client-size of a financial service market is thus as big as the number of people on this planet. (say  $\Gamma$)

However, these needs and aspirations come in various shapes and sizes; serviced through various productised supplies like asset-products, liability-products, loans, insurance, etc. Financial service companies grow when

1. They increase the services they provide so as to reach the needs and aspirations of larger groups.
2. They make their current offerings affordable and available to larger groups.

Both of the above, stems from solving for the information gap (future money uncertainty) and friction between intermediaries. To top it, the size of the business-house that ventures into the financial service arena faces capital, technology and reachability constraints as their endowment and trust of users, the largest hurdle to the growth of their client-base.

For example, the currently digitised and intelligent financial services industry players growth potential is definitely stochastically dominated

1.  By the penetration of the smartphone ($\gamma_s$)
2. Financial awareness/literacy and viability ($\gamma_I\gamma_s$) . E.g. If you are a digital player in a broking service, what you really get to see is a proxy for Is is growth in demat accounts.
3. The value-proposition (customer-product) quotient of the service-provider ( $\gamma_P\gamma_I\gamma_s$ ). For example, the growth model of a specific digital player is manifested as growth in their client base

$\gamma_s$ is aka the market share in the competition space

## **Factors affecting System Dynamics of Growth**

| Gamma | Growth-Causal(s) | Company specific actions to capture more market share |
| --- | --- | --- |
| Gamma-Tech (S) | - Technological penetration | Affordable Solutions launched as add-on to their core products (E.g. POS machines) |
| Gamma-Industry (I) | • Financial Literacy
• Awareness Campaigns
• Influencers/Activism | Design Campaigns, Workshops, Free-Try(s),  and try Influencer Marketing to 
[Increase market participants and be the sole-beneficiary] |
| Gamma-Company (S) | • Broadcast value proposition
• Play with marketing-mix
• SEOs
• Viral content(s) etc. | Make efforts to capture sale-ready market |

[Smartphone penetration growth forecast: Ref: [[Link](https://www.statista.com/statistics/467163/forecast-of-smartphone-users-in-india/#:~:text=Smartphone%20users%20in%20India%202010%2D2040&text=The%20number%20of%20smartphone%20users,1.5%20billion%20users%20in%202040.&text=The%20number%20of%20smartphone%20users%20worldwide%20is%20projected%20to,nearly%202.7%20billion%20by%202019.)] Statistia.com](https://lh5.googleusercontent.com/NsuN_ddkiLmu9pw5o4voGqYzqeqKBEbhP1Cw_xzULzsHTUlsCphKVrpSG_yHvjHnoYU93EyttlsMB4NzlyhT3knUesBmvjRReX2xmjYIFA_ec_ipMaIiWFyqK63I7VUjkZRC0VeKLOxixW4fJw)

Smartphone penetration growth forecast: Ref: [[Link](https://www.statista.com/statistics/467163/forecast-of-smartphone-users-in-india/#:~:text=Smartphone%20users%20in%20India%202010%2D2040&text=The%20number%20of%20smartphone%20users,1.5%20billion%20users%20in%202040.&text=The%20number%20of%20smartphone%20users%20worldwide%20is%20projected%20to,nearly%202.7%20billion%20by%202019.)] Statistia.com

[User Count growth when zoomed out and studied.](https://lh4.googleusercontent.com/wzDhiY0bxNcAuO0Hia2g3ganf-iYin-S8BjvW9kYDWG_fKMnmMhgDknXGDzV7DBMFASNtZ_m6Yj3rVGSbk41hM9unel-EjfofIZS41N-KcxS93vnD4bYcSR_alQDQWTM46C9vgKFhuGiDvtaMQ)

User Count growth when zoomed out and studied.

## **System Dynamics of Growth**

To capture the sectoral/industrial growth we need to solve for two-key unknowns

1. **Growth-curve model(s)**] Model for the pattern of growth: The pattern can be studied at various granularities, viz. Global aggregation, Spatial aggregation, Product level aggregation and all such aggregations at which a company can create strategies for capturing the demand. Underlying figure is an illustration of the dynamics of the growth constituents.
2. **Intervention Model(s)** - These models are fundamentally a what-if/econometric model that tries to capture the association/causation between the strategies adopted and the outcomes expected. Historically, academicians have been framing and studying various Structural Equation Models (SEMs) to understand the growth-hacks for various development metrics of interest.

[Figure reference from [1]](https://lh4.googleusercontent.com/XdsCQtekVWRSopYyJS9-ir65oE0s2sG6RgCrUQhAAWJq-RVXHL1H-wzywja84C1DtR0TDociUj2aLCJNZwK0FD0en4dOSCcPjqvYWBbmtA1Ja-ADeIvMtaYXaGeTWpV8MNKHcfWrEYtQkqccgA)

Figure reference from [1]

## **Quantitative Efforts in Growth**

### **Decision Theoretic**

This approach is largely hinged on [Decisions] **strategies**, [current standing of users] **states**, [transitions with/without interventions] **probability of states** and **payoffs**.

- The substrates on which the decisions are based is Standard Dynamics, Domain Experts know-how. Let us assume that these are quantified as a vector of variable ($S_k$). This vector can include but not limited to budget across channels of efforts.
- Secondly, the states are observed based on the customer journey in the platform and is understood as ($O_j$) with their state transition probability given as ($p_{ij}(S_k)$) for $O_i \to O_j$ transition using strategy $S_k$
- The payoff per users in a state $(O_j)$ on customer journey is generally calculated by the revenue model for monetising the engagements of the users. ($P_j$)
- Goal is to maximize/increase payoff in every iteration with minimum cost where cost is the cost of strategies. Besides, the strategies have externalities and disrupt the process in the next cycle. Hence these are generally multi-stage decisions. The objectives can thus be compresses as

$$
\text{max } \sum_{O_j} \sum_{k} P_j\times p_{ij}(S_k)\times \#(O_i\to O_j |S_k)
$$

$$
\text{s.t} \sum_{k} f(S_k)<C
$$

The work done to establish the decision theoretic efforts has three pillars.

1. Understanding Customer/Prospect journey and the levers adopted to influence the throughput of customers/prospect through various channels and ultimately through product pipelines. The product of each milestone growth accounts for total growth.
2. Optimisation of payoffs across a collection of levers (a state in the user journey) to influence a particular aspect of the journey of prospect/user

[https://lh4.googleusercontent.com/8NI9Ij_c9rJjz2ew270v0wxsZmrpqJXzhRXMkyDWQVW7nMXpizrOVMKAZXfmODc4gZwZWttTbAzP5IURuPvbWanxWyOmjy5I1gNkqgDzDUd_JCmhVqIKoEZEymhVA1KcuneyIMhU2ZJnqo-9_Q](https://lh4.googleusercontent.com/8NI9Ij_c9rJjz2ew270v0wxsZmrpqJXzhRXMkyDWQVW7nMXpizrOVMKAZXfmODc4gZwZWttTbAzP5IURuPvbWanxWyOmjy5I1gNkqgDzDUd_JCmhVqIKoEZEymhVA1KcuneyIMhU2ZJnqo-9_Q)

[https://lh6.googleusercontent.com/7J4unBS4RO-QemXlGBePVxeNlJxm4IurcjZu15t7ngAU6A14daGDrKjsRaBHmq1ogVjNcIlommsBPJXTv1mJ9-eW294FQVpBVpodFAtt4m2e1PndjaHgcINH0WYB7KQZN3TcEn6C8CKLSvmN6Q](https://lh6.googleusercontent.com/7J4unBS4RO-QemXlGBePVxeNlJxm4IurcjZu15t7ngAU6A14daGDrKjsRaBHmq1ogVjNcIlommsBPJXTv1mJ9-eW294FQVpBVpodFAtt4m2e1PndjaHgcINH0WYB7KQZN3TcEn6C8CKLSvmN6Q)

1. Optimisation across all levers to influence the full journey of a prospect/user - This is the same strategy as (2) but optimises for the payoffs from the entire journey.

### **Empirical, Statistical and Machine Learnings**

The empirical effort includes and is not limited to

1. **Validating Hypothesis** - Even before we create a System Dynamics of the process and decipher the inferential probability of transitions we might have to either study historical data or conduct experiments to lay down a process flow to optimise for.
2. **Hypothesis generation** - The insights or causal exploration that is done on the data to hypothesise the nature of growth or the influencers of the growth is also driven by empirical study of the survey data or the generated data.

Example : There seems to be 5 distinct user-states in the path to revenue growth of the platform. Can you validate if indeed it is five distinct classes? It seems that distribution of an always on discount coupon transitions the revenue state of the users, can you validate?

The outcome of these empirical pursuits, aids system dynamics, decisions, and even qualitative processes.

### *Learning Problems*

Most of the learning problems that one engages with here are largely targeted to solve for problem statements stem from the missing/unknown information in Decision Process and System Dynamics.

Example : Model the probability of transitions, create a representation of the states in the user journey, etc.

# **Conclusion**

Developing an understanding of the growth and its dynamics is fundamental to developing quantitative growth-hackers.

We at angel-one are scripting and solving the path to solution for growth in the financial service industry. We are looking for enthusiastic and analytical minded people to engage with rich-data and help solve these fundamental problems. Please come and join us!

# **References**

[1] Nasridinov, Aziz & Marakhimov, Azizbek & Park, Young-Ho. (2015). A Study on Diffusion Dynamics of Intelligence-Driven Cloud Solutions in Law Enforcement Authorities. Lecture Notes in Electrical Engineering. 330. 1049-1054. 10.1007/978-3-662-45402-2_149.

[2] Smartphone growth rate as proposed at [https://www.statista.com/statistics/467163/forecast-of-smartphone-users-in-india/](https://www.statista.com/statistics/467163/forecast-of-smartphone-users-in-india/)

[3] Duggan, J. (2016). System Dynamics Modeling with R. Germany: Springer International Publishing.

[4] Growth Curve Models and Applications: Indian Statistical Institute, Giridih, India, March 28-29, 2016. (2017). Germany: Springer International Publishing.

[5] Peterson, M. (2017). An Introduction to Decision Theory. India: Cambridge University Press.

[6] Blog: [https://thesystemsthinker.com/](https://thesystemsthinker.com/)

[7] Murphy, K. P. (2012). Machine Learning: A Probabilistic Perspective. United Kingdom: MIT Press.

[8] Huyen, C. (2022). Designing Machine Learning Systems: An Iterative Process for Production-Ready Applications. United States: O'Reilly Media, Incorporated.

[9] Wasserman, L. (2013). All of Statistics: A Concise Course in Statistical Inference. Ukraine: Springer New York.

[10] Meadows, D., Meadows, D., Randers, J. (2004). Limits to Growth: The 30-Year Update. United States: Chelsea Green Publishing.