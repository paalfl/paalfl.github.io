# Using an MCP server

## What an MCP server is, and why I trust the mst0441 server

An MCP server is like a universal translator for AI. It is a small program that connects AI tools (like Claude or ChatGPT) to your actual data, files, and apps.

I trust the mst0441 server because i highly trust my professor who made the server.


## The new version of workshop 2

My agent wrote these problems with the mst0441 MCP server on 9 November 2026. They cover sessions 8 to 11, like workshop 2. Every problem passed mst0441_check_problem.

**Problem 1 (15%)** Fjordlys Regnskap is an accounting firm. Every client file it handles needs four tasks: bookkeeping entries, payroll runs, tax reports and client meetings. One worker-hour produces one task-unit of any task and costs w = 500 kroner. The firm can instead rent AI services. One AI-service unit costs r = 1500 kroner and produces A_i task-units in task i:

| Task | AI productivity A_i | Baseline cost share χ_i |
|---|---|---|
| Bookkeeping entries | 5 | 1/4 |
| Payroll runs | 3 | 3/10 |
| Tax reports | 2 | 1/4 |
| Client meetings | 1/2 | 1/5 |

The cost shares refer to the cost of a fixed bundle of client files when every task is done by workers. Quality is the same with either method, and there are no setup costs. When the two methods cost the same, the task stays with labor.

(a) Write the cost of one task-unit with each method. Derive the cutoff for A_i above which a task goes to AI, in general notation first, and find the set of automated tasks at r = 1500.

(b) Compute the saving π_i on each task and the fixed-weight saving index G = Σ χ_i π_i. The bundle of client files costs 250 000 kroner when every task is done by workers. How many kroner does the firm save on that bundle?

(c) The rental rate falls to r = 1000, with w, A_i and χ_i unchanged. Find the new automated set, the new savings, G and the saving in kroner on the same bundle. Split the change in G between the task that was already automated and the task that is newly automated.

(d) A union representative says: "AI can already do payroll runs, so the wages of our payroll staff will fall." Explain what the calculation in (a) to (c) can and cannot tell us about these workers, using a maximum of 4 sentences.

**Problem 2 (12%)** Home and Foreign make two goods, sailboats (x) and cheese (y), with labor alone. Labor moves freely between the two industries in a country, but not between countries. The hours of labor needed per unit and the labor forces are:

| | sailboats | cheese | labor force |
|---|---|---|---|
| Home | a_x = 3 | a_y = 3 | E = 36 |
| Foreign | a_x* = 2 | a_y* = 1 | E* = 20 |

Consumers in both countries have the utility function u = x^(1/2) y^(1/2), so each country spends half its income on each good. Cheese is the numeraire, p_y = 1, and p = p_x/p_y is the relative price of sailboats.

(a) Draw each country's production possibility frontier with sailboats on the horizontal axis. Give the intercepts and the slope.

(b) Find the autarky relative price of sailboats in each country, derived from the condition that wages are equal across industries. Who has the absolute advantage and who has the comparative advantage in each good?

(c) The countries open to free trade. State which good each country produces, and find the world price p that clears the market for sailboats. Show that p lies between the two autarky prices.

(d) Find the wage in each country, measured in cheese. Show with unit costs that each country is the cheaper producer of exactly one good. Explain why Home exports sailboats although Foreign needs fewer hours to make every good, using a maximum of 3 sentences.

**Problem 3 (8%)** An economy makes aluminium (good y) and furniture (good x) with capital K and labor E. Both industries are competitive, so price equals unit cost and profits are zero. One unit of aluminium needs 2 units of capital and 1 unit of labor. One unit of furniture needs 1 unit of capital and 3 units of labor. The economy is small and takes world prices as given. Write r for the rental rate of capital and w for the wage.

(a) Rank the two industries by factor intensity. Write the zero-profit conditions and find r and w at p_y = 10 and p_x = 10.

(b) The price of furniture rises to p_x = 12, while p_y stays at 10. Find the new r and w. Compute the four percentage changes, arrange them in one chain and name the theorem.

(c) Do workers gain or lose in real terms? Do capital owners? Explain why your answer does not depend on whether a person spends most of their income on aluminium or on furniture. Maximum 3 sentences.

**Problem 4 (5%)** Lavland and Høyland are identical countries. In each of them one differentiated industry, craft beer, operates under monopolistic competition: many breweries, each with its own variety, a fixed cost and a constant marginal cost, free entry and exit, and consumers who love variety. No calculation is needed in this problem. Answer in words, within the sentence limits.

(a) (3 points) Lavland and Høyland open to trade with each other. The elasticity of demand is constant. Explain what happens to the price of a craft beer, to the output of each brewery, to the number of breweries in Høyland, and to the number of varieties a consumer in Høyland can buy. Where does the gain from trade come from? Maximum 5 sentences.

(b) (2 points) Lavland and Høyland trade craft beer in both directions. Why would a model in which trade comes only from differences in technology or in factor endowments predict no trade between them? Maximum 2 sentences.

**Problem 5 (10%)** Ten multiple-choice questions on key concepts, one point each. Exactly one answer is correct. Write the question number and the letter.

1. The elasticity of substitution between AI and labor is σ = 1/2. AI becomes cheaper relative to labor. Labor's share of the firm's costs
   (a) rises (b) falls (c) stays the same, since the firm uses both inputs (d) cannot be signed without the firm's output
2. In the task model with a given wage, AI productivity rises in a task that is already automated. Then
   (a) the automated set grows by one task (b) the automated set is unchanged, and the saving on that task rises (c) the wage of the workers in that task falls (d) the saving index G is unchanged
3. In the Ricardian model, a country that needs fewer hours than its trading partner to make every good
   (a) exports both goods (b) exports the good in which its advantage is largest, and has the higher wage (c) gains nothing from trade (d) imports both goods
4. In the Ricardian model with good y the numeraire, Home specializes in good x at world price p. Home's wage in units of y is
   (a) 1/a_y (b) p/a_x (c) p · a_x (d) a_x/a_y
5. In the Heckscher-Ohlin model, the economy's labor force rises while goods prices stay fixed. Then
   (a) the wage falls (b) both outputs rise in proportion (c) the output of the labor-intensive good rises by more than in proportion, and the output of the capital-intensive good falls (d) the rental rate of capital rises
6. Bowen, Leamer and Sveikauskas test the sign of the Heckscher-Ohlin-Vanek prediction factor by factor. The sign is right in about half of the cases. This means that
   (a) Heckscher-Ohlin-Vanek with identical technologies does no better than a coin flip (b) Heckscher-Ohlin is confirmed for half the countries (c) the data on factor endowments are wrong (d) Leontief's paradox is resolved
7. Gravity with unit elasticities, ln X_ij = k + ln Y_i + ln Y_j − ln d_ij. The exporter's GDP doubles, the importer's GDP quadruples, and the distance between them doubles. Predicted trade changes by a factor of
   (a) 16 (b) 8 (c) 4 (d) 2
8. A border between a small country and a large country carries the same true trade friction for both. The border effect measured without multilateral resistance is
   (a) the same for both countries (b) larger for the small country, since the border cuts it off from a larger share of its potential partners (c) larger for the large country, since it trades more (d) zero for the large country
9. In estimated gravity equations, the coefficient on distance is typically close to
   (a) 0 (b) between −1 and −1.4 (c) +1 (d) −5
10. Two identical countries trade cars in both directions. The model that accounts for this two-way trade relies on
    (a) differences in labor productivity (b) differences in capital per worker (c) increasing returns and differentiated varieties (d) differences in tastes between the countries

## My solution, written before the check

### Problem 1

**(a)**
- Cost of one task-unit with labor: c_L = w = 500 kr.
- Cost of one task-unit with AI: c_A,i = r/A_i.
- A task goes to AI when r/A_i < w, which means A_i > r/w. Ties stay with labor.
- At r = 1500 the cutoff is A* = 1500/500 = 3.
- Automated set: **{Bookkeeping}**, since A = 5 > 3. Payroll has A = 3, which is a tie, so it stays with labor. Tax reports (2) and client meetings (1/2) are below the cutoff.

**(b)**
- The saving is π_i = 1 − r/(w·A_i) if the task is automated, and 0 otherwise.
- Bookkeeping: π = 1 − 1500/2500 = **0.4**. Payroll, tax reports and client meetings: π = 0.
- G = (1/4)(0.4) = **0.10**.
- Saving on the bundle: 0.10 × 250 000 = **25 000 kr**.

**(c)**
- At r = 1000 the cutoff is A* = 2. Automated set: **{Bookkeeping, Payroll}**. Tax reports have A = 2, which is a tie, so they stay with labor.
- Bookkeeping: π = 1 − 1000/2500 = **0.6**. Payroll: π = 1 − 1000/1500 = **1/3**. Tax reports and client meetings: 0.
- G = (1/4)(0.6) + (3/10)(1/3) = 0.15 + 0.10 = **0.25**.
- Saving on the bundle: 0.25 × 250 000 = **62 500 kr**.
- Splitting ΔG = 0.15:
  - Bookkeeping, already automated (intensive margin): (1/4)(0.6 − 0.4) = **0.05**, one third of the change.
  - Payroll, newly automated (extensive margin): (3/10)(1/3) = **0.10**, two thirds of the change.

**(d)** The calculation takes the wage w = 500 as given. It only shows which tasks it is cheaper for the firm to give to AI and how much the firm saves: payroll moves to AI only once r falls below 1500, and at r = 1500 it is a tie and stays with labor. It cannot tell us what happens to payroll workers' wages, because wages are set in the labor market and not inside this cost comparison. That outcome depends on whether displaced workers can move to other tasks or firms, and on the productivity effect: lower costs can raise demand for client files and so for the tasks that stay with labor.

### Problem 2

**(a)**
- Home: sailboat intercept 36/3 = **12**, cheese intercept 36/3 = **12**, slope −a_x/a_y = **−1**.
- Foreign: sailboat intercept 20/2 = **10**, cheese intercept 20/1 = **20**, slope **−2**.
- Both frontiers are straight lines.

**(b)**
- Equal wages across industries means p_x/a_x = p_y/a_y, so p = a_x/a_y.
- Home: **p = 1**. Foreign: **p\* = 2**.
- Absolute advantage: **Foreign in both goods** (2 < 3 hours for sailboats, 1 < 3 hours for cheese).
- Comparative advantage: **Home in sailboats** (opportunity cost 1 < 2). **Foreign in cheese** (opportunity cost 1/2 < 1).

**(c)**
- Home specializes in sailboats (x = 12). Foreign specializes in cheese (y = 20).
- The sailboat market clears when world spending on sailboats equals supply: (12p + 20)/(2p) = 12. This gives 24p = 12p + 20, so **p = 5/3**.
- 1 < 5/3 < 2, so p lies between the two autarky prices.

**(d)**
- Wages in cheese: Home w = p/a_x = (5/3)/3 = **5/9**. Foreign w\* = 1/a_y\* = **1**.
- Unit cost of sailboats: Home 3·(5/9) = 5/3, which equals p. Foreign 2·1 = 2, which is more than 5/3. Home is cheaper.
- Unit cost of cheese: Home 3·(5/9) = 5/3, which is more than 1. Foreign 1·1 = 1. Foreign is cheaper.
- Why Home exports sailboats: Foreign's productivity advantage is 3× in cheese but only 1.5× in sailboats. Its wage is 1/(5/9) = 1.8 times Home's, which lies between 1.5 and 3. That high wage more than cancels Foreign's small advantage in sailboats, so Home is the cheaper sailboat producer. Comparative advantage decides trade, not absolute advantage.

### Problem 3

**(a)**
- Aluminium (K/E = 2) is **capital-intensive**. Furniture (K/E = 1/3) is **labor-intensive**.
- Zero-profit conditions: 2r + w = p_y and r + 3w = p_x.
- At p_y = p_x = 10: **w = 2, r = 4**.

**(b)**
- With p_x = 12: 2r + w = 10 and r + 3w = 12. This gives **w = 2.8, r = 3.6**.
- Percentage changes: ŵ = +40%, p̂_x = +20%, p̂_y = 0%, r̂ = −10%.
- Chain: **ŵ (40%) > p̂_x (20%) > p̂_y (0%) > r̂ (−10%)**.
- This is the **Stolper–Samuelson theorem** (the magnification effect).

**(c)** Workers gain in real terms and capital owners lose. The wage rises by more than either goods price, and the rental rate falls while neither price falls. Any consumption bundle has a price index that rises by between 0% and 20%, so the result holds whatever mix of aluminium and furniture a person buys.

### Problem 4

**(a)** With constant elasticity the markup is constant, so the price of a craft beer does not change. Output per brewery also stays the same. The number of breweries in Høyland stays the same, because its labor force and the zero-profit scale per brewery are unchanged. Consumers in Høyland can now buy Lavland's varieties too, so the number of varieties available to them doubles. The whole gain from trade comes from this greater variety.

**(b)** Identical technology and identical factor endowments give identical autarky prices, so neither country has a comparative advantage. These models therefore predict no reason to trade, and certainly no two-way trade in the same good.

### Problem 5

1. a
2. b
3. b
4. b
5. c
6. a
7. c
8. b
9. b
10. c

## What the check said

My agent checked my solution on 9 November 2026. It recomputed the numbers in problems 2 and 3 with mst0441_verify and marked the rest against the rubrics for sessions 8 to 11.

**Right**
- Problem 2: all numbers OK with mst0441_verify. Intercepts, autarky prices, world price 5/3 and wages 5/9 and 1 match.
- Problem 3: all numbers OK with mst0441_verify. w = 2 and r = 4 at the first prices, w = 2.8 and r = 3.6 at the second.
- Problem 1: the numbers are correct by the agent's hand check. The tool cannot check the session 8 task model, so no machine has checked them.
- Problem 4: both answers are within the sentence limits and match the rubric. No machine has checked text answers.
- Problem 5: 10 of 10 correct. Only question 7 is a calculation.

**Wrong or missing**
- 2(a): the frontiers are described in text but not drawn. The task says "Draw".
- 2(d): the explanation has 4 sentences. The limit is 3.
- 1(d): the answer does not say in words that exposure is not adoption. The tie at r = 1500 shows it, but the answer never states it.

## What I changed

TO BE WRITTEN BY ME.
