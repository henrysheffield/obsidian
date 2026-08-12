Here are 10 practice problems focused on radioactive decay and half-life, progressing from easy to difficult. As you requested earlier, the solutions below all utilise the natural logarithm ($\ln$) approach to solve them in single algebraic steps.

### **Part 1: The Questions**

**Easy (Direct Application)**

1. A $100\text{ g}$ sample of Technetium-99m has a half-life of $6.0\text{ hours}$. Calculate the mass remaining after $18\text{ hours}$.

    
2. Iodine-131 has a half-life of $8.0\text{ days}$. If you start with $50.0\text{ g}$, exactly how much remains after $20\text{ days}$?
    
3. An unknown isotope has a half-life of $5.0\text{ years}$. How long will it take for a sample to decay to exactly $25\%$ of its original amount?
    

**Medium (Finding half-life and working with activity)**

4. A $40.0\text{ mg}$ sample of a radioactive isotope decays to $5.0\text{ mg}$ in $15\text{ days}$. Calculate the half-life of the isotope.

5. A fossil bone is analysed and found to contain only $15\%$ of its original Carbon-14 concentration. Given the half-life of Carbon-14 is $5730\text{ years}$, calculate the approximate age of the fossil.

6. The activity (decay rate) of a radioactive sample drops from $8000\text{ decays/minute}$ to $1000\text{ decays/minute}$ in $45\text{ hours}$. What is the half-life of the sample?

7. A specific medical tracer requires at least $2.0\text{ mg}$ of an isotope to be active in the body to be detected by a scan. If the initial dose given to a patient is $10.0\text{ mg}$ and the isotope's half-life is $12.0\text{ hours}$, how long is the tracer effective?

**Difficult (Multi-step and complex ratios)**

8. A laboratory mixture contains $10.0\text{ g}$ of Isotope A (half-life = $3.0\text{ days}$) and $10.0\text{ g}$ of Isotope B (half-life = $9.0\text{ days}$). After how many days will the mass of Isotope B be exactly four times the mass of Isotope A?

9. You have a $20.0\text{ g}$ sample of a radioactive element. After $14\text{ days}$, you measure it and find $4.5\text{ g}$ remaining. Suddenly, you realise you need exactly $1.0\text{ g}$ of the substance for a critical experiment. How many _additional_ days from the $14$-day mark must you wait for it to decay to this amount?

10. Uranium-235 (half-life = $7.04 \times 10^8\text{ years}$) decays eventually into stable Lead-207. A geological rock sample is analysed and found to contain a U-235 to Pb-207 mass ratio of $1:3$. Assuming all the Lead-207 in the rock came strictly from the decay of Uranium-235, calculate the age of the rock.

### **Part 2: The Solutions**

_Note: All solutions utilise the base-e decay formula $N(t) = N_0 e^{-\lambda t}$ and its rearranged forms, where $\lambda = \frac{\ln 2}{t_{1/2}}$._

**1.**

$$N(t) = 100 \cdot e^{-\left(\frac{\ln 2}{6.0}\right) \times 18}$$

$$N(t) = 100 \cdot e^{-3\ln 2} = 100 \cdot 0.125 = \mathbf{12.5\text{ g}}$$

**2.**

$$N(t) = 50.0 \cdot e^{-\left(\frac{\ln 2}{8.0}\right) \times 20}$$

$$N(t) = 50.0 \cdot e^{-1.7328} \approx 50.0 \cdot 0.1767 = \mathbf{8.84\text{ g}}$$

**3.**

Using $t = -\frac{\ln(N/N_0) \cdot t_{1/2}}{\ln 2}$:

$$t = -\frac{\ln(0.25) \cdot 5.0}{\ln 2}$$

$$t = -\frac{(-1.386) \cdot 5.0}{0.693} = \mathbf{10\text{ years}}$$

**4.**

Rearranging for $t_{1/2}$: $t_{1/2} = -\frac{\ln 2 \cdot t}{\ln(N/N_0)}$

$$t_{1/2} = -\frac{\ln 2 \cdot 15}{\ln(5.0/40.0)} = -\frac{\ln 2 \cdot 15}{\ln(0.125)}$$

$$t_{1/2} = -\frac{0.693 \cdot 15}{-2.079} = \mathbf{5.0\text{ days}}$$

**5.**

$$t = -\frac{\ln(0.15) \cdot 5730}{\ln 2}$$

$$t = -\frac{(-1.897) \cdot 5730}{0.693} \approx \mathbf{15,684\text{ years}}$$

**6.**

Activity follows the exact same decay equation as mass.

$$t_{1/2} = -\frac{\ln 2 \cdot 45}{\ln(1000/8000)} = -\frac{\ln 2 \cdot 45}{\ln(0.125)}$$

$$t_{1/2} = -\frac{0.693 \cdot 45}{-2.079} = \mathbf{15\text{ hours}}$$

**7.**

$$t = -\frac{\ln(2.0/10.0) \cdot 12.0}{\ln 2}$$

$$t = -\frac{\ln(0.2) \cdot 12.0}{\ln 2} = -\frac{(-1.609) \cdot 12.0}{0.693} \approx \mathbf{27.86\text{ hours}}$$

**8.**

Set up the equations for both isotopes and set $N_B(t) = 4 \cdot N_A(t)$:

$$10 e^{-\left(\frac{\ln 2}{9}\right)t} = 4 \cdot \left( 10 e^{-\left(\frac{\ln 2}{3}\right)t} \right)$$

Divide both sides by $10$ and combine the $e$ terms by dividing:

$$\frac{e^{-\left(\frac{\ln 2}{9}\right)t}}{e^{-\left(\frac{\ln 2}{3}\right)t}} = 4 \implies e^{\left(\frac{\ln 2}{3} - \frac{\ln 2}{9}\right)t} = 4$$

Take the natural log of both sides:

$$\left(\frac{3\ln 2}{9} - \frac{\ln 2}{9}\right)t = \ln 4$$

$$\left(\frac{2\ln 2}{9}\right)t = 2\ln 2$$

Divide both sides by $2\ln 2$:

$$\frac{t}{9} = 1 \implies \mathbf{t = 9\text{ days}}$$

**9.**

**Step 1:** Find the decay constant ($\lambda$) or half-life.

$$\lambda = -\frac{\ln(4.5/20.0)}{14} = -\frac{\ln(0.225)}{14} \approx 0.1065\text{ day}^{-1}$$

**Step 2:** Calculate the time to go from the current $4.5\text{ g}$ down to $1.0\text{ g}$.

$$t_{\text{additional}} = -\frac{\ln(1.0/4.5)}{\lambda}$$

$$t_{\text{additional}} = -\frac{\ln(0.222)}{0.1065} = -\frac{-1.504}{0.1065} \approx \mathbf{14.1\text{ days}}$$

**10.**

If the ratio of U-235 to Pb-207 is $1:3$, it means out of every $4$ original atoms, $1$ remains as U-235 and $3$ have decayed into Lead. Therefore, the fraction of Uranium remaining ($N/N_0$) is exactly $\frac{1}{4}$ or $0.25$.

$$t = -\frac{\ln(0.25) \cdot (7.04 \times 10^8)}{\ln 2}$$

$$t = -\frac{(-1.386) \cdot 7.04 \times 10^8}{0.693} = 2 \cdot (7.04 \times 10^8) = \mathbf{1.408 \times 10^9\text{ years}}$$

_(Which equates to exactly 2 half-lives)._