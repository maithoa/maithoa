# From Two Big Releases a Year to 2.4 Deployments a Week

By Thoa Nguyen

When I joined the team in 2021, we were putting out urgent fixes every few days.

If you wanted a small improvement to the same software, there were two dates on the calendar for the whole year. Miss one, and you could spend months doing the same work the hard way.

![A developer waits beside a calendar with two dates circled. In the next scene, a developer shows a small change to a colleague.](assets/smaller-releases.webp)

Most of those fixes landed with two senior developers. Aaron was one of them. When he picked up a fix, his work on the next big release had to wait.

I asked the business leads and the developers why new features had to wait. Both groups said that was just how it worked. The business leads would have been happy to get something useful sooner. Could we get one small change to them before the next big release?

## We started with a spreadsheet

The business team used Excel to answer two questions about each prospect. Did he or she already have a membership? Had we sent him/her an invitation to try it?

I picked that workflow for our first small release. The spreadsheet showed us what the first version needed to track, and the business team could keep it as a fallback.

Three weeks later, we had a demo of the new feature. It solved the problem better as it integrated with our data about the person, and by having that we did not only remove the excel work but also time to manage and cross references data between different systems. The people doing the work in Excel wanted to use it.

Our testers were already booked, and the version they were testing included other changes planned for the big release. To release the feature on its own, we needed to test it against the software people were already using.

I worked with Li and another tester to decide which of their other tasks could wait. We set up a separate place to test the feature. People from the business tried it before launch.

The feature went live two weeks after the demo, ahead of the big release. We started hearing what people thought straight away. That’s how our DevOps journey started.

## Could we do that again?

Of course we could. But first we had to make room for it.

I asked all the developers to take turns handling urgent fixes and agree on which problems needed immediate attention. That gave Aaron and the other senior developer more time for planned work.

We also took one wait out of testing. Testers used to wait for a developer to deploy each new version to a test environment. We automated that step. When developers merged a change into the shared code, it went straight to the right test environment. There was less back-and-forth, less waiting, and less stress for both testers and developers.

In 2025 and early 2026, we averaged **2.4 deployments a week** to the live system, including urgent fixes and deployments done by hand. By then, we needed far fewer urgent fixes, and the share of proposed code changes reviewed by another developer had risen from **70% to 98%**.

## What was worth the team’s time?

There was always another nice-to-have we could build. Agreeing on which problem mattered most to the business helped us choose what to work on first and what belonged in the first version. Making it easier to test and release that version meant people could start using it sooner.

Next time, I’ll go back to the interruptions that kept pulling Aaron away from his work. **What actually counts as urgent?**

*Names have been changed.*
