# Engineering Weekly cw #17
## April 19 2018, [8:00 AM MDT](https://www.worldtimebuddy.com/?qm=1&lid=7&h=7&date=2018-4-26&sln=8-9)
### [Agenda](https://github.com/MARKETProtocol/community/issues/2)
### [Recording](https://www.youtube.com/watch?v=QuW6ez_uoP8)
### Attendees
@pelsasser @pchuck @perfectmak @eswarasai @42piratas Collins Brown and Robert Jordan.
## To-do
- Move the info from [docs.originprotocol.com/#contributing](http://docs.originprotocol.com/#contributing) to [docs.marketprotocol.io](https://docs.marketprotocol.io/). Responsible: @pelsasser
- Create a list of examples of calls/functions for the API layer. Responsible: @pelsasser
- Try to identify process improvement opportunities with Perfect, Eswara, and new collaborators. Responsible: @42piratas

## Notes
- Newcomers: Robert Jordan and @42piratas.
- Info: dApp progress as shared by Eswara:
  - Increased the code coverage by adding the test cases.
  - Added validation for Base Token Address before Deploying Contract.
  - Added link to transaction upon successful test query submit.
  - Added recommended GasPrice instead of hardcoding the value for transactions.
  - Deployed the dev version of the app to AWS and also setup the auto-deployment on Travis CI.
- Unfo: static website progress as shared by Phil:
  - There are a few issues to be resolved, but they are being tackled at the moment.
  - The goal is to have the website live within one or two days (i.e. by April 30th).
- Discussion brought by Phil: should we move the info from [docs.originprotocol.com/#contributing](http://docs.originprotocol.com/#contributing) to [docs.marketprotocol.io](https://docs.marketprotocol.io/) to centralize such info in a clean way?
  - Patrick agrees it is a good idea.
- Info: next outstanding milestones as shared by Phil:
  - Extend the functionality of the dApp to include the simulated exchange, so users can not only deploy contracts, but also select those contract to be able to trade them.
  - Create an API layer to allow users to interact with the Solidity contracts more easily /// Robert requested a list of examples of possible calls/specific functions of the layer (added to-do) and also called attention to points regarding the infrastructure.
- Discussion brought by Phil: processes, how to bring more collaborators, any suggestions?
  - Perfect praised the improvements on processes and guidelines.
  - Ânderson suggested to extend the questions to new collaborators, as they might be able to answer from a different perspective.
- Discussion brought by Eswara: we should use GitHub project board to visualize and manage issues from all repos in a single place.
  - Patrick suggested using the root level of MARKETProtocol GH account so we have issues from all repos centralized.
  - A discussion followed concerning tools and processes.
  - Ânderson suggested to define a process before migrating to a new tool.
