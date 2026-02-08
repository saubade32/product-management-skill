# Hooked: Building Habit-Forming Products

Based on Nir Eyal's "Hooked" framework. Use this when designing features, onboarding flows, engagement loops, gamification, notifications, or any product decision where user retention and repeat engagement matter.

## Core Principle

The best product doesn't win. The product that captures the **monopoly of the mind** wins — the thing users turn to first with little or no conscious thought.

Engagement is as important, if not MORE important, than growth. If you can't retain users and keep them coming back, you've got nothing.

## The Hook Model (4 Steps)

Every habit-forming product embeds a **hook** — a 4-step cycle that runs repeatedly:

```
Trigger → Action → Variable Reward → Investment
   ↑                                      |
   └──────────────────────────────────────┘
```

### 1. TRIGGER — "What prompts the user?"

Two types:

**External Triggers** — things in the environment telling the user what to do next:
- Push notifications, emails, CTAs, buttons ("Click here", "Buy now", "Play this")
- Product teams already understand these well

**Internal Triggers** — the critical piece most teams miss:
- Stored as a memory/association inside the user's head
- Most frequently these are **negative emotions**: boredom, loneliness, uncertainty, dissatisfaction, fatigue, fear of missing out
- Users turn to products to **modulate their mood** — to feel something different
- Examples:
  - Lonely → Facebook/social media
  - Uncertain → Google
  - Bored → YouTube, Reddit, news, feeds

**Key question to answer:** What is your product's internal trigger? What is the frequently occurring itch your product addresses? If your team can't answer this, you have a problem.

**Frequency rule:** The habit you want to create MUST occur within **a week's time or less**. More frequent = better. Products like Facebook, Slack, Instagram are used multiple times daily (people check home screens ~150 times/day). If the behavior doesn't occur at least weekly, it's almost impossible to form a habit.

### 2. ACTION — "What's the simplest behavior?"

The action is the **simplest behavior done in anticipation of a reward** — the easiest thing the user can do to scratch that itch.

- Scrolling a feed on Pinterest
- Typing a search on Google
- Pushing play on YouTube

**BJ Fogg's Behavior Model:** For any behavior to occur, you need 3 things simultaneously:
1. **Motivation** — energy for action, how much they want to do it
2. **Ability** — capacity to do the behavior, how easy it is
3. **Trigger** — must be present

**Critical insight:** 90% of the time, teams focus on increasing motivation (videos, testimonials, persuasion). This is usually the WRONG approach. The better ROI is to **increase ability** — make the behavior easier.

**6 Factors of Ability** (reduce any of these to make behavior more likely):
1. **Time** — how long it takes
2. **Money** — how much it costs
3. **Physical effort** — how much work is required
4. **Brain cycles** — how hard it is to understand (critical for tech products)
5. **Social deviance** — people are more likely to do things others like them do
6. **Non-routine** — we're more likely to do things we've done before (practice effect — habits have a repeater effect: more you do it → easier it becomes → more likely to do it again)

### 3. VARIABLE REWARD — "Scratch the itch, but leave them wanting more"

It's NOT enough to just give people what they want. You must give them what they want AND **leave them wanting more**. This is done through **variable rewards**.

Based on BF Skinner's operant conditioning: pigeons pecked at a disc more when rewards came on a variable (unpredictable) schedule vs. fixed schedule. Variability spikes the reward system in the brain and creates a wanting/desirous response.

**Three types of variable rewards:**

**a) Rewards of the Tribe** — feel good, come from other people, have uncertainty:
- Cooperation, competition, romance, empathetic joy
- Social media feeds: never sure what you'll see, how many likes, what comments say
- Apply to: social features, community, collaboration, sharing

**b) Rewards of the Hunt** — primal search for resources/information:
- Slot machines (uncertainty of what you might win)
- **The Feed** — scrolling through content, one story isn't interesting but the next might be, so you keep scrolling. Same psychology as pulling a slot machine.
- Searching for the next interesting piece of information
- Apply to: content feeds, search results, discovery features, recommendations

**c) Rewards of the Self** — intrinsically pleasurable, not from others or material:
- Search for mastery, competency, consistency, control
- Gameplay: getting to the next level, completing accomplishments
- Email: clearing unread messages, finishing to-do lists, clearing notifications
- Apply to: gamification, progress tracking, skill building, completion mechanics

### 4. INVESTMENT — "What work increases the next pass?"

The most overlooked step. The user puts something into the product **in anticipation of a future benefit** (not immediate gratification).

**Purpose:** Increase the likelihood of the next pass through the hook.

**Two mechanisms:**

**a) Loading the next trigger:**
- Send a message on WhatsApp → no immediate reward, but when they reply you get an external trigger (notification) → cycle restarts
- Create content → others engage → notification brings you back

**b) Storing value:**
- Physical goods depreciate with use. Habit-forming products **appreciate** with use — they get better the more you engage.
- Types of stored value:
  - **Data** — preferences, history, settings
  - **Content** — uploads, posts, articles created
  - **Followers/connections** — social graph
  - **Reputation** — ratings, karma, status, levels
- Stored value makes the product better, customizes it for the user, and **makes it harder to leave**
- When users invest, it doesn't matter if a better product comes along

## The 5 Fundamental Questions

When building any feature requiring unprompted engagement, answer:

1. **What's the internal trigger?** What itch does your product address? Does it occur frequently enough (weekly minimum)?
2. **What's the external trigger?** What prompts the user to action?
3. **What's the simplest action?** What's the easiest behavior done in anticipation of reward?
4. **Is the reward fulfilling yet variable?** Does it scratch the itch but leave the user wanting more?
5. **What's the investment?** What bit of work increases the likelihood of the next pass through the hook?

## Applying to Harbor

When designing Harbor features, evaluate against the hook model:

| Hook Step | Harbor Application |
|---|---|
| **Internal Trigger** | Uncertainty about content strategy, fear of falling behind competitors, pressure to publish consistently |
| **External Trigger** | Lifecycle emails, dashboard notifications, weekly recap emails, getting started tasks |
| **Action** | One-click discovery, generate article, scroll idea feed — keep these as simple as possible |
| **Variable Reward** | Discovery results (hunt — what topics will surface?), article quality (self — mastery of content), community/social proof (tribe) |
| **Investment** | Sites added, presets configured, articles generated, discovery history — all make Harbor more valuable over time and harder to leave |

### Feature Design Checklist

Before shipping any engagement feature, ask:
- [ ] Does this reduce friction (ability) rather than just adding motivation?
- [ ] Is there a variable reward component, or is the outcome always predictable?
- [ ] Does this create stored value that makes the product stickier?
- [ ] Does this load the next trigger to bring the user back?
- [ ] Does this address a real internal trigger (negative emotion) the user experiences frequently?
- [ ] Will this behavior occur at least weekly?
