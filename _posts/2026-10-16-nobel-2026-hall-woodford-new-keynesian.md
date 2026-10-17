---
title: "Hall and Woodford, Nobel 2026: How Expectations Rebuilt Stabilization Policy"
description: The 2026 economics prize went to Robert Hall and Michael Woodford.
  What their papers showed, how the New Keynesian model works, where it falls
  short, and what I take from it.
categories:
  - Nobel Prize in Economics
  - "2026"
tags:
  - nobel prize
  - robert hall
  - michael woodford
  - new keynesian
  - monetary policy
  - stabilization policy
image:
  path: /assets/img/posts/Nobleprizeineconomics2026.webp
pin: false
toc: true
math: true
---
**Key points**

- Robert E. Hall (Stanford) and Michael Woodford (Columbia) won the 2026 prize "for microeconomic foundations of macroeconomic stabilisation" (Royal Swedish Academy of Sciences, 2026a).
- Hall showed how to test whether households plan spending around the future. Woodford built that behavior, sticky prices and an interest-rate rule into one model that central banks now use.
- The framework has known weak spots: it handles average households better than unequal ones, and promises about distant interest rates look too powerful in it.
- My own reading: the prize is about expectations, which is also the weak joint in the current AI investment boom.

## 1. The prize and the question

On 12 October 2026 the Royal Swedish Academy of Sciences announced that Robert E. Hall and Michael Woodford had won the Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel. Both are American, and both earned their PhDs at MIT (Royal Swedish Academy of Sciences, 2026b). The prize carries 12 million Swedish kronor (Time, 2026).

The committee's chair, John Hassler, said the work leaves us "better equipped to deal with shocks in the economy" (Royal Swedish Academy of Sciences, 2026a), such as energy crises or sudden shifts in household spending.

The question behind the prize is old. Governments can try to smooth unemployment and inflation over the business cycle, but how much should they do, and with which tools? The answer changed twice in the last century, and this prize rewards the second change.

## 2. The problem they inherited

Keynes's argument, written during the Great Depression, was that total demand does not automatically match what an economy can produce, so governments should lower interest rates and run deficits in downturns and do the opposite in booms. Postwar models turned this into arithmetic. They relied on stable statistical links between inflation, unemployment, consumption and output, and the Academy's popular background says those links were assumed to be roughly linear (Royal Swedish Academy of Sciences, 2026c).

The 1970s broke them. Inflation and unemployment rose together, which the old relationships said would not happen. Lucas (1976) gave the diagnosis: the equations summarized how people behaved under past policy, so they could not predict behavior under new policy. The demand that followed was clear and hard to meet. Build models from the decisions of households and firms, and make them simple enough to use.

## 3. Hall: spending that looks ahead

Hall's 1978 paper started from a simple prediction. If households plan their spending around expected lifetime income, they should change that spending only when they learn something new. News cannot be forecast, so the change in consumption from one period to the next should not be forecastable from information already known (Hall, 1978). Hall tested this on US data and found it largely held.

This mattered because expectations cannot be observed directly. Hall's insight was that spending reveals them. If a household acts on everything it knows, today's spending already summarizes what it expects.

The second step was about who does not fit. Hall and Mishkin (1982) used household-level data and found that most consumption behaved as the theory predicts, but a sizeable minority of households behaved as if they simply spent whatever income arrived. That split matters for policy. A tax rebate sent to a household with savings is mostly saved. The same rebate sent to a household without any is mostly spent.

Hall also worked on the labor market, where he proposed a way for search models to produce the large swings in unemployment seen in the data (Hall, 2005; Hall & Milgrom, 2008), after Shimer (2005) had shown that standard versions could not. That work sits beside the prize rather than at its center, and I mention it to show how broad his program is.

## 4. Woodford: one model for central banks

Woodford took Hall's forward-looking household and added two things. The first is firms that set prices but cannot change them all the time. The second is a central bank that sets an interest rate by a rule. Rotemberg and Woodford (1997) laid out an optimization-based framework for evaluating monetary policy, and Woodford's 2003 book *Interest and Prices* gave the complete treatment. The Academy's popular background describes the result as a full New Keynesian model built on microfoundations and calls its three-equation form the prototype for later models (Royal Swedish Academy of Sciences, 2026c).

In the standard textbook version, the three equations are these.

$$x_t = E_t x_{t+1} - \sigma\left(i_t - E_t \pi_{t+1} - r^n_t\right)$$

$$\pi_t = \beta E_t \pi_{t+1} + \kappa x_t + u_t$$

$$i_t = r^n_t + \phi_\pi \pi_t + \phi_x x_t$$

Here $x_t$ is the output gap, $\pi_t$ is inflation, $i_t$ is the policy interest rate, $r^n_t$ is the natural rate of interest, $u_t$ is a cost shock, and $E_t$ means expectations formed today. The first equation says households spend more when they expect higher future output or when the real interest rate is low. The second says that firms set prices with an eye on expected inflation and current demand. The third is a Taylor-type rule for the central bank, with $\phi_\pi > 1$ so that the bank raises the nominal rate by more than the rise in inflation.

![Schematic of the New Keynesian loop between households, firms and the central bank, with expectations feeding both private sectors](/assets/img/posts/nobel-2026-nk-loop.png){: w="760" }
*Figure 1. The standard three-equation model. Expectations sit in the middle because both households and firms decide today with the future in mind. Author's schematic.*

Two consequences matter in practice. First, the interest rate, not the money supply, becomes the policy instrument. Woodford argued as early as 1998 that a central bank can steer inflation even in an economy where people hold very little cash (Woodford, 1998). Second, what a central bank says becomes a tool. If households and firms look ahead, a credible statement about future rates changes spending and pricing today. Woodford argued that clear communication improves a central bank's ability to stabilize the economy (Woodford, 2005).

## 5. What changed in practice

According to the Academy's popular background, New Keynesian models are now used by central banks and finance ministries around the world, and the Swedish central bank has its own version adapted to Swedish conditions (Royal Swedish Academy of Sciences, 2026c). The NPR account of the announcement ties the work to the pandemic and the supply shocks that followed (NPR, 2026).

I would be careful with the causal story. It is plausible that better models helped policymakers respond to recent shocks, and the Academy says so. It is much harder to show that this explains why the recent inflation episode was shorter than the one in the 1970s, since the shocks, the institutions and the central banks' independence all differ.

## 6. Where the framework falls short

These are my reading of the literature, not claims from the prize announcement.

- **Heterogeneity.** Hall and Mishkin's own result says households differ, yet the textbook model uses one representative household. Kaplan, Moll and Violante (2018) show that models with unequal households change how monetary policy works, so the field has been moving in that direction.
- **The forward guidance puzzle.** In the simple model, promises about rates far in the future have very large effects today. Del Negro, Giannoni and Patterson (2023) document the puzzle, and McKay, Nakamura and Steinsson (2016) show that it weakens once households face borrowing limits. This should make us cautious about leaning on promises alone.
- **Financial crises.** The model is built to manage shocks that arrive in an otherwise functioning economy. A banking crisis needs other tools.

## 7. My perspective

*This section is the author's own view.*

The word I keep coming back to is expectations. Hall's household and Woodford's firm both decide today based on what they believe about tomorrow, and the central bank's main job becomes managing those beliefs. That is a useful way to read the AI investment boom I wrote about in my [post on the IMF's October outlook](/posts/ai-investment-imf-weo-october-2026/). Investment in AI holds up demand before any productivity gain shows in the data, so its durability rests on expectations. If expectations shift, the same logic that makes forward guidance powerful also makes a reversal fast.

The second thing I notice is the distance between the model's households and real ones. The framework assumes people form rational expectations. Woodford himself has spent years on the limits of that assumption, and he teaches a course on cognitive mechanisms and economic behavior at Columbia (Columbia University, 2026). Hall and Mishkin's minority of rule-of-thumb households is the first piece of evidence that the representative household is too simple. I think the most interesting work now sits where behavioral economics meets stabilization policy: how people actually form beliefs about inflation and rates, and what that means for how a central bank should speak.

The third is a hypothesis, not a finding. The model needs sticky prices to give demand any power over output. Digital markets may be weakening that assumption, because algorithmic pricing lets firms update prices cheaply and often. If that is true, price stickiness should be lower in sectors with heavy algorithmic pricing, and the output effect of a monetary shock should shrink there. I would like to see this tested with price-level data.

## 8. Conclusion

Hall showed how to test the idea that households plan around the future and found that many, though not all, do. Woodford turned that behavior, sticky prices and a rule for the interest rate into a model that central banks can use, and he made communication part of policy. The prize recognizes a framework that now sits in the daily work of central banks. It also leaves open questions about unequal households, distant promises and financial crises, and those are the places where I expect the next decade of research to work.

## References

Columbia University. (2026, October 12). *Columbia's Michael Woodford wins 2026 Nobel Memorial Prize in Economics*. [https://news.columbia.edu/news/columbias-michael-woodford-wins-2026-nobel-memorial-prize-economics](https://news.columbia.edu/news/columbias-michael-woodford-wins-2026-nobel-memorial-prize-economics)

Del Negro, M., Giannoni, M., & Patterson, C. (2023). The forward guidance puzzle. *Journal of Political Economy Macroeconomics, 1*(1), 43-79.

Hall, R. E. (1978). Stochastic implications of the life cycle-permanent income hypothesis: Theory and evidence. *Journal of Political Economy, 86*(6), 971-987.

Hall, R. E. (2005). Employment fluctuations with equilibrium wage stickiness. *American Economic Review, 95*(1), 50-65.

Hall, R. E., & Milgrom, P. R. (2008). The limited influence of unemployment on the wage bargain. *American Economic Review, 98*(4), 1653-1674.

Hall, R. E., & Mishkin, F. S. (1982). The sensitivity of consumption to transitory income: Estimates from panel data on households. *Econometrica, 50*(2), 461-481.

Kaplan, G., Moll, B., & Violante, G. L. (2018). Monetary policy according to HANK. *American Economic Review, 108*(3), 697-743.

Lucas, R. E. (1976). Econometric policy evaluation: A critique. *Carnegie-Rochester Conference Series on Public Policy, 1*, 19-46.

McKay, A., Nakamura, E., & Steinsson, J. (2016). The power of forward guidance revisited. *American Economic Review, 106*(10), 3133-3158.

NPR. (2026, October 12). *2 Americans win Nobel Prize in economics for work on boom-bust cycles*. [https://www.npr.org/2026/10/09/nx-s1-5996634/nobel-prize-in-economics](https://www.npr.org/2026/10/09/nx-s1-5996634/nobel-prize-in-economics)

Rotemberg, J. J., & Woodford, M. (1997). An optimization-based econometric framework for the evaluation of monetary policy. *NBER Macroeconomics Annual, 12*, 297-346.

Royal Swedish Academy of Sciences. (2026a, October 12). *The Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel 2026* [Press release]. [https://www.nobelprize.org/prizes/economic-sciences/2026/press-release/](https://www.nobelprize.org/prizes/economic-sciences/2026/press-release/)

Royal Swedish Academy of Sciences. (2026b). *Announcement of the Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel 2026*. [https://www.nobelprize.org/prizes/economic-sciences/2026/prize-announcement/](https://www.nobelprize.org/prizes/economic-sciences/2026/prize-announcement/)

Royal Swedish Academy of Sciences. (2026c). *Popular science background: Microfoundations deliver macro insights*. [https://www.nobelprize.org/prizes/economic-sciences/2026/popular-information/](https://www.nobelprize.org/prizes/economic-sciences/2026/popular-information/)

Shimer, R. (2005). The cyclical behavior of equilibrium unemployment and vacancies. *American Economic Review, 95*(1), 25-49.

Time. (2026, October 12). *Meet the 2026 Nobel Prize winners*. [https://time.com/article/2026/10/05/nobel-prize-2026-winners/](https://time.com/article/2026/10/05/nobel-prize-2026-winners/)

Woodford, M. (1998). Doing without money: Controlling inflation in a post-monetary world. *Review of Economic Dynamics, 1*(1), 173-219.

Woodford, M. (2003). *Interest and prices: Foundations of a theory of monetary policy*. Princeton University Press.

Woodford, M. (2005). Central bank communication and policy effectiveness. *NBER Working Paper No. 11898*.
