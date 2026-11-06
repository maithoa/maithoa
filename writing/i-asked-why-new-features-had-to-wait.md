# I Asked Why New Features Had to Wait

By Thoa Nguyen

I asked our business leads why new features had to wait for one of two release dates each year. They told me they had assumed that was how software development worked. They would have been happy to get useful changes sooner.

The developers had a different worry. Urgent fixes were going live every few days, and the same two developers handled most of them. The team worried that squeezing in more changes would leave them with even less time for the big release they were already working on.

I started out as a developer, and I still like to see how the work actually gets done. I wanted to understand what users were waiting for and what made it hard for the team to get a change into their hands.

## We started with a spreadsheet

I picked one workflow the business was already doing in Excel. We agreed on what a small first version needed to do and built a demo in three weeks. The business wanted to use it. The team explained what was in the way. The testers were already booked, and the test environments contained changes for the big release.

I agreed with two testers on what work could wait. We set up separate environments to test the feature against the version people were already using, and business representatives tried it before launch. Once it went live, users gave us feedback straight away.

## The next release had to be easier

I asked the team to take turns handling urgent fixes and agree on which problems needed immediate attention. We also automated the handoff that kept testers waiting. Once code was merged, testers could start their checks in the right environment without waiting for a developer to deploy it by hand.

In 2025 and early 2026, we averaged **2.4 production deployments a week**, including urgent fixes and manual deployments. By then, we needed far fewer urgent fixes. The share of pull requests that received a code review rose from **70% to 98%**.

The engineers told me that knowing who needed a change and why helped them think through the design. That's a conversation I want engineers to be part of from the start. They're the ones who have to turn what they hear into something people can use.
