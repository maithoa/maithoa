# I Asked Why New Features Had to Wait

By Thoa Nguyen

Every few days, we shipped an urgent fix.

New features had two dates on the calendar. Two for the entire year.

![A developer waits beside a calendar with two dates circled. In the next scene, a developer shows a small change to a colleague.](assets/smaller-releases.webp)

I asked our business leads why new features had to wait. They thought that was just how software development worked. They would have been happy to get useful changes sooner.

The developers were looking at a different calendar. The same two people handled most of the urgent fixes, and the team was already trying to get the next big release out the door. Where exactly was another release supposed to go?

I started out as a developer. I wanted to follow one small change all the way to a user and see where it got stuck.

## A small change meets a big release

The business was already doing one of its workflows in Excel. I picked that one. We agreed on what the first version needed to do, and three weeks later we had a demo. The people who had been doing the work in Excel wanted to use it.

It felt like we were nearly there.

Then we tried to find somewhere to test it.

The testers were booked, and the test environments were already full of changes for the big release. We had a small feature ready to test and nowhere to try it against the version users actually had.

I worked with two testers to decide what could wait. We set up separate test environments for the feature, and business representatives tried it before launch. Once it went live, feedback started coming in straight away.

## Could we do that again?

I asked the team to take turns handling urgent fixes and agree on which problems really needed immediate attention. We also took one small wait out of the workflow. A tester used to have to wait for a developer to deploy the code by hand. Once we automated that step, merging the code got it into the right test environment.

In 2025 and early 2026, we averaged **2.4 production deployments a week**, including urgent fixes and manual deployments. We needed far fewer urgent fixes by then, and the share of pull requests that received a code review rose from **70% to 98%**.

The engineers told me something that stuck with me. Knowing who needed a change and why helped them think through the design. Now, when I ask an engineer to build something around a spreadsheet, I want them to hear from the person who uses it.
