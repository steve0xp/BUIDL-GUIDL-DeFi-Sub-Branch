# BUIDL-GUIDL-DeFi-Sub-Branch
A template repo for the DeFi sub-branch (likely to migrate this to a scaffold-eth fork once writing SRE yearn strategy tutorial)). This README just lays out my current thinking of how everything will look and open-ended thoughts I currently have. I invite anyone to add thoughts to these ideas by opening an issue!

# Current Concept

### Summary:

Over the last month I’ve gotten a lot of work done for the MVP for level 3000 type tutorials for a DeFi sub-branch, specifically for writing Yearn strategies. 

I propose the following:

- Finish the strategy,
- I’ll distill it down to a generic strategy/tutorial, in conjunction with yearn,
- then we release it to the world

The idea is that the below can be used as a template process of sorts for other niches (so **imagine me or someone else in BUIDL GUIDL doing this monthly for different projects:** for building pools with Balancer, Curve, or other protocols that decide to **************partner************** with us 

- Basically dev rel as a service.

### Details of the Student’s UX

All in all, this is still in the exploratory phase, but I've got a lot of work done for the MVP. My thinking is that a level 3000 student would go through the following for different DeFi niches. Making these are the TODOs for me to make for the yearn strategy for example.

1. **Read the tweetstorms to better understand the breakdown (I'm working on a thread series walking through the process of creating a yearn strategy)**

_*Draft threads made but need to get the OK from yearn about their details._

1. concept & initialization
2. troubleshooting & discussions
3. testing
4. deployment and post-deployment

2. **Watch and read recommended resources (outlined in thread #1)**
    1. *There's a repo (which I'm gonna write a commit for (in progress)) && a video that is good for onboarding people to v2 yearn vaults && strategies.*
        1. REPO LINK - https://github.com/umphams/yearn_mellow-gearbox-strategy
3. **Go through the more open-ended challenge of creating a strategy and submit it to get auto-graded using a foundry local hardfork mainnet test suite.**
    1. Go through a repo with a challenge outlined, and tests made.
    2. Here's the repo I've been working on the last month to really get the ins and outs of creating a yearn strategy. My thinking is I'll glean what I think is important for autograding a yearn strategy, and then create that test file and a solutions file. We won't give the solutions to people to start.

<aside>
💡 *A big portion of the experience so far is peer reviewing. It would be cool to have students who are at this level peer review each other. It really depends on the scope.*

- If we are training them to get "informal badges" that show they know yearn strategies, then I assume yearn wants them to eventually create strategies that are peer reviewed by theixr strategists / coder community.
- **My proposal is to train them to just about ready to code stuff to get peer reviewed by strategists/protocol-native coder community.**
</aside>