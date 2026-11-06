# From Two Big Releases a Year to 2.4 Deployments a Week

By Thoa Nguyen

I get asked about this fairly often, so I decided to type it out. 😀

Back in 2021, I met my new team. They were a smart bunch, and a little stressed. DevOps had been a word for years. We had two big release dates on the calendar.

Every few days, we shipped an urgent fix. The next big release was still months away.

![A developer waits beside a calendar with two dates circled. In the next scene, a developer shows a small change to a colleague.](assets/smaller-releases.webp)

I asked our business leads why new features had to wait. They thought that was just how software development worked. They would have been happy to get something useful sooner.

I asked the developers the same question. They gave me pretty much the same answer. That was how it worked.

Meanwhile, the same two experienced developers handled most of the urgent fixes, and the team was trying to get the next big release out the door. I’d started out as a developer, and I knew what it felt like to work that way. I wanted the team to experience what DevOps could do for us. Could we get one useful change into people’s hands and hear what they thought while the work was still fresh?

## A small change meets a big release

Early on, I spent a lot of time with our business leaders trying to understand what was getting in their way. One problem caught my attention. The business team was already working around it in Excel.

That made it a good first pick. We could see how people did the work, agree on a small first version, and leave them with a familiar fallback if they needed it. Three weeks later, we had a demo. The people doing the work in Excel wanted to use it.

To the business, it looked like we were almost there. If you’ve worked on a waterfall project, you can probably guess what came next. :)

- Features were piling up in the development branches for the big release.
- Production was thousands of commits behind those branches.
- The testers were booked, and the test environments already contained changes for the big release.

We could have put the feature on the same release date as everything else. But we already had people who wanted to try it. What would it take to get it to them sooner?

I worked with two testers to decide what could wait. We set up separate environments so we could test the feature against the version users already had. Business representatives tried it before launch. Once it went live, feedback started coming in straight away.

That’s how our DevOps journey started.

## Could we do that again?

First, we needed to make room for planned work. I asked the developers to take turns handling urgent fixes and agree on which problems actually needed immediate attention. That gave the two people who had been handling most of the fixes more time for other work.

We also took one small wait out of the workflow. Testers used to wait for a developer to deploy the code by hand. Once we automated that step, merging the code put it in the right test environment.

In 2025 and early 2026, we averaged **2.4 production deployments a week**, including urgent fixes and manual deployments. By then, we needed far fewer urgent fixes, and the share of pull requests that received a code review had risen from **70% to 98%**.

That first release was how we got started. Getting to 2.4 deployments a week took a few years, and we kept coming back to three questions.

Who is affected by this problem, and how much does it get in their way?

What’s the smallest version that would actually help them?

Which parts of testing and releasing could we automate so the next change would be easier to ship?

And remember the two developers who handled most of the urgent fixes? Taking turns helped spread the work. We still had to agree on when a problem was worth asking someone to drop what they were doing.

**What actually counts as urgent?** That’s where I’ll pick up next time.
