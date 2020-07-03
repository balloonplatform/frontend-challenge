#  Balloon Frontend Challenge

> 🎈 🙇‍♀️🙇‍♂️

## 📝 Instructions

**Develop this pricing page:** 👇 

![balloon marketing page pricing design](./design.png)

- The tech and tools are completely up to you. You can choose the frameworks, libs, tools and tech stack you want.

- Does not need to be pixel perfect, but should look like **the design above**.

- The sections marked `A`, `B`, and `C` in the design **should be dynamic**. Everything else is static content. Links can go to made up URLs, and the email `<input>` doesn't need to do anything.

- Our pricing model is based on the number of **Authors** on a team. The price for each author depends on the number of **Participants** they are able to add/invite to a **Flight** (their "participant limit"). (Authors are the users that can create a **Flight**.) There are 3 available prices/plans, which correspond to a specific participant limit. When you create your **Balloon** account, you can set up one or multiple authors, each at one of the 3 participant limits. For example, as shown in the design, the visiting user has selected "up to 50" and then has 3 additional authors at the *20 limit*, 4 additional authors at the *50 limit*, and 4 additional authors at the *300 limit*. The total for these 12 users is $262.50/mo, billed annually ($262.50 x 12 = $3150).

- Your job is to put the pieces together. Create the UI to **allow customers choose the limit** they want (A), and **allow them to set *additional* authors** for each of the levels (B). Base on those selections, it should **calculate the final price** (C)

- If the user selects "300+" for their limit, the calculated price should just say "Contact us!"

- You can make your own assumptions: if something is not clear, ambiguous or could be done in different ways, just make your choice. We are sure you will opt for the best alternative 🙂

> ⏱ Do not spend more than ~8 hours on this. If you think you can't complete this in that time, just pick a specific part of the project and focus on having something solid and functional.

> 📦 When you are done, just send an email to [noah@getballon.com](noah@getballon.com) and [nacho@getballon.com](nacho@getballon.com) with a zip folder containing your code, or include a link to a zip or a private git repo.


## 💾 Data

In this repo, you will find `data.json` file which contains an `Array` of objects. Each element in the array represents a pricing plan. You can just use that file in your code. **There does not need to be aby API or HTTP interaction.**

When you implement the pricing plans in your application, you should only consider the plans with the property `active === true` *and* the property `interval === year`. The plans that don't match both conditions, should be skipped/filtered out.

Other properties you will find relevant in each plan:
- `metadata.limit`: Indicates the participant limit for the plan
- `amount`: Indicates the plan's price (the unit is cents)

## 🌉 Assets

Inside the `assets` directory, you will find some useful images for design and markup.
