> The trouble is that thought and culture are not the sort of thing that can have distinct units. 
> They do not have a granular structure for the same reason that ocean currents do not have one — namely, because they are not stuffs, but patterns.
>
> — **Mary Midgley**, _Myths We Live By_

> Data dominates. If you've chosen the right data structures and organized things well, the algorithms will almost always be self-evident. Data structures, not algorithms, are central to programming.
>
> — **Rob Pike** (one of the creators of Go)

#### 🍓📊 Hi! Welcome!
### My name is Gwyneth, but everybody calls me Winnie
##### (people only call me Gwen when I'm in trouble)
###### or 'Aunt Gen' if you're my niece 🥹

💽🌿 I love building stuff with (and for) data and AI.

A hyper-responsive data platform → super tidy and well-documented data models for agents and humans → clear narrative analyses with just the right level of snappy interactivity and gorgeous artifacts — this stack does something to my brain that makes me very happy.

🌌🐴 As my fascination with data ranges all over — and I'm just as interested in building dev tools for the work as the work itself — I've never been able to stay cramped in a rigid box. Which one am I: an Analyst or Data Engineer (or Software Developer, Developer Experience Advocate, Teacher, Consultant, Manager...)? The answer is 'yes'.

Hence: **Data Cowgirl**. Ride around my trusty stallion Bracket and make sure all the data is[^1] thriving. Nurture it, help it grow strong. When the leaves turn, go shear it, then spend the long winter weaving it into tapestries. That kind of thing.

To be less..._poetic_[^2] about it — the way this manifests changes all the time, making labels a bit difficult. I've spent professional stretches:

- building industry-leading enterprise SaaS platforms, and lovingly crafted OSS CLIs
- constructing bomb-proof streaming data platforms for cutting-edge factories, and tiny data warehouses pro bono for education non-profits (carefully designed to never tick over BigQuery's generous free tier)
- weaving diverse data sources into a cohesive world, and passionate human beings into cohesive communities 
- designing beautiful web apps, and resilient patterns for data work
- managing analytics for teams (a lot of Marketing, Finance, DevOps, Sales), and managing teams of my own
- writing in-depth docs on Python SDKs, and explorations of what truth means in data
- and of course, making the best memes in the data space 😌

🎷🐄 You get the idea — data cowgirl.

No matter the particulars, the mission is always: 

1. 🌱🍄‍🟫 Nurture data ecosystems with technical rigor and deep empathy
2. ✨🕸️ Get people excited about _their_ ability to do amazing things within it
3. 🗺️🌊 Work together to understand this world a little better every day 🫶

Giddyup!
<img width="20" alt="cowboy-shy" src="https://github.com/user-attachments/assets/f8255fea-debb-49a2-a856-45756e559011" />

<details>
  <summary><h4>❤️‍🔥🪭 If you'd like to learn a bit about my taste and takes, there's more in here!</h4></summary>

### Things I love

👩🏻‍🌾🐚 Terminals, shells, command lines, Neovim, and spending waaay too much time gardening my dotfiles. You can [check them out here](https://github.com/gwenwindflower/dotfiles) (I recently migrated to [chezmoi](https://www.chezmoi.io/), if you're a dotfiles nerd, I recommend it). I'm really stoked about the terminal renaissance we're seeing from Claude Code! Seeing more people reach for the precision, speed, and control of the command line is so welcome after a decade of trying to wrap everything in a GUI.

🍦🦕 Writing cute and useful CLIs and TUIs in Go with the [Charm](https://github.com/charmbracelet) libraries is a favorite of mine — although recently I've been using Deno a lot as well, and sometimes build multi-threaded Python tools with Typer when scale or portability is not a concern. I'm planning to spend more time building in Rust this year though, as it's clearly become the gold standard for modern command line tools. I've been starting to release some random tools from my freelance work via the [g15r GitHub org](https://github.com/g15r), the ones I'm most excited about are still baking, but there are some nice utils in my [Homebrew tap](https://github.com/g15r/homebrew-tap) for now.

#### 💌📈 Tools and trends I dig

  - [DuckDB](https://duckdb.org/docs/stable/)
    - Cool stuff in the ecosystem as well, like the [Airport](https://airport.query.farm/) extension
    - [DuckLake](https://ducklake.select/),in my opinion a superior data lake standard over Iceberg
  - [Daft](https://www.daft.ai/) and [DataFusion](https://datafusion.apache.org/) running on platforms with fantastic developer experiences like [Modal](https://modal.com/) as the new way to handle massive datasets
  - The convergence on Parquet + Arrow lakes with flexible compute and query engines accessing them is just generally a huge improvement (speaking as somebody who has migrated a _lot_ of data between BigQuery ⇄ Snowflake ⇄ Redshift ⇄ Databricks) 
  - [Marimo](https://marimo.app/), whose cloud platform runs on Modal
  - [Hex](https://hex.tech/), hands-down best BI tool in the world (maybe ever? probably ever.)
    - Open standards emerging around metrics definitions in these kinds of tools (as opposed to the LookML days)
  - [MotherDuck](https://motherduck.com), the best warehouse for 90% of businesses not operating at massive scale
  - Most importantly, I think what we understand broadly as analytics engineering, the analytics engineering skillset, is what's driving the best AI data systems — context engineering for analytics agents is just a new category of analytics engineering

If you like my recommendations and want more: my collecting/scrapbooking/journaling/organizing/labeling instinct is powerful, so I am a dedicated GitHub Stargazer — you're welcome to explore [my lists](https://github.com/gwenwindflower?tab=stars)!

### 🌶️🤷🏻‍♀️ A handful of heresies

If you're still here, I guess it's safe to get a little spicy. I'll leave you with some of my more heterodox beliefs:

1. Data visualization is really overrated! Don't get me wrong, I _love_ great data visuals, and there are tons of analyses where they help communicate in a way words can't (I'm a girl with the complete works of Tufte on my shelf who gets very excited when a new issue of The Pudding drops) — but in 95% of BI work, visualization has historically been treated as the obvious standard output. In spite of half a decade lamenting the deficiencies of dashboards, they remain _the_ final destination of all this engineering and modeling effort in most people's minds. We're past due to realize that a summary of interesting shifts in this week's revenue metrics might work better as a short paragraph. Blessedly, AI is finally getting us to the post-dashboard promised land.

2. You're looking at too much data. The reality is, your brain _cannot_ track a dashboard of 50 metrics hour-by-hour, day-by-day in a way that is actually useful and effective. It's the data equivalent of operating as if you had no object permanence. A child figures out how a bouncy ball moves, then can track when it disappears behind the couch — we need to get there with our metrics. All the brain power you expend keeping tabs would be better spent building that intuition for the physics of your business. While it _is_ cool to pounce on your CEO's pop quiz at the board meeting with a ratatat of punchy metrics that would make Aaron Sorkin proud — I absoluetly get that — it's theater, not impact. Save chart watching for the chaotic crises.

</details>

🃏🧚🏼 In parting, my favorite card from Brian Eno's famous Oblique Strategies deck...

<img src="https://d2w9rnfcy7mm78.cloudfront.net/22056133/original_0d5668acc4b1d30ab5b462553f91f31b.png?1685494625?bc=0" width=500 />

##### Thanks for stopping by! ˚ʚ♡ɞ˚

```text
  　　　∧＿∧
　 ｒy´・ω・｀ヽっ
　　`!　　　　　i
　　 ゝc＿c_,.ノ
　　　 （
　　　　）
　.∧＿∧.(
(´・ω・ ∩
o　　 ,ノ
Ｏ＿ .ノ
　.(ノ
```

[^1]: If you're frustrated that I don't treat "data" as a plural, sorry—language is a living, evolving thing!
[^2]: Annoying
