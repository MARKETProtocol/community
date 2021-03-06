<img src="https://github.com/MARKETProtocol/dApp/blob/master/src/img/MARKETProtocol-Light.png?raw=true" align="middle">

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

# Project Management

## Project Board
Issues and pull requests across all MARKET Protocol repositories are managed from a central [organization-wide MARKET Protocol project board](https://app.zenhub.com/workspace/o/marketprotocol/market.js/boards?repos=140627375,128025988,130496585,117898415,119072718,116695875,130494562,131598556,108304540,127038994,141709662,135627327,129016888).

Project boards help organize and prioritize work. Learn more about [ZenHub project boards](https://help.zenhub.com/support/solutions/43000042875).

### Column Descriptions

Each column in the project board has a distinct purpose which helps visualize and organize work.

* **Todo** - tasks that are planned but not started
* **In progress** - tasks that are assigned to specific individual(s) and are actively being worked on.
* **In review** - when you finish working on a specific issue, you must move it to this column to signalize your changes are ready to be reviewed by someone else.
* **Done** - work that is completed (and thoroughly tested). Also (see *Automation* below, this column can also include pull requests that were closed without being merged, for reasons described in the PR's comments).
* **Backlog** - work that hasn't yet been decomposed into issues, work that has issues or ambiguities that prevent it from being moved to 'todo' or work that isn't yet high enough priority to be moved to 'todo'

### Column Automation

Each column in the project board can have automations attached that help automatically surface and organize new issues. To understand what decisions about tasks need to made by humans, versus what is organized automatically, the following descriptions highlight automations currently enabled.

* **Todo** - All newly added or reopened issues and pull requests are automatically moved to this column.
* **In progress** - None. The act of explicitly moving a card here indicates that a particular person has initiated work on an item.
* **In review** - None. You must move manually move your issue to this column.   
* **Done** - All closed issues, all merged pull requests and all closed but not merged pull requests are automatically moved to this column.
* **Backlog** - No automation. See *Column Descriptions*

### Card Organization

Within each column, cards are organized by contributors. Because cards at the top of the column are more prominent than those at the bottom of the column, we prioritize cards at the top, using the following rules.

* Cards with highest priority first and lowest priority last
* Within each priority group, cards that describe bugs that affect users
* Within each priority group, cards that describe bugs that affect further development
* Cards with a bounty attached and cards that are a good first issue for new contributors to tackle.

### Issue Creation

When creating new issues, a number of attributes can be set which determine whether and how the issue appears in the project board.

#### Assignees

This attribute is self explanatory.

#### Labels

Issues are labelled to help filtering and to help organize issues within. For consistency, here's a list of currently used labels and their meaning.

* **Bounty Attached** - A task that has a gitcoin bounty associated with it.
* **Duplicate**
* **Good First Issue** - An issue that might be tackled by a new contributor.
* **Help Wanted**
* **Invalid**
* **Priority: Critical**
* **Priority: High**
* **Priority: Low**
* **Priority: Medium**
* **Status: Abandoned**
* **Status: Accepted**
* **Status: Available**
* **Status: Blocked**
* **Status: Completed**
* **Status: In Progress**
* **Status: On Hold**
* **Status: Pending**
* **Status: Review Needed**
* **Status: Revision Needed**
* **Tip Eligible**
* **Type: Bug**
* **Type: Enhancement**
* **Type: Maintenance**
* **Type: Question**

Avoid duplicate tags that don't conform with these, such as 'will tip', 'low', etc.

#### Projects

When opening new issues, *be sure to attach* the issue to the MARKET Protocol organization project. The default is 'None' which prevents the issue from appearing in the project board.

### Milestones

TBD
