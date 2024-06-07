# OMG Platform

## Scope

* Users can set up an account using email or use; 
    * OAUTH/Wallet to login or;
    * login with email/password. 

## Tasks

- [ ] Integrate email and password in UI 
    * 4 hours
- [ ] Look for plugins in payload to support OAUTH
    * Blocked
    * 24 - 32 hours

## Blocker
- [ ] Missing designs for registrations
- [ ] Exhaustive list of OAUTH options 

## Scope

* Ability to associate their account with their wallets and also change which wallets should be associated with their account for investments.
    * Support for EVM, Solana, BTC

## Tasks

- [ ] Change flow to associate wallets to login
    * Blocked
    * 12 hours
- [ ] Create BTC Auth flow 
    * 4 hours

## Blockers
* Missing pages to connect wallets to accounts

## Scope

* Ability to connect socials (X, Linkedin, Reddit, Telegram, YouTube).

## Tasks

- [ ] OAUTH for the following: X, Linkedin, Reddit, Telegram, Youtube
    - 12 hours

## Scope 

* Manage security settings such as change of password and set up 2FA.

## Tasks

- [ ] 2FA Flow
    - 12 hours

## Scope

* View of all available raises and detailed information via opportunities dashboard:
    * All current investable projects, which should contain
        * Project name and logo
        * Round type (Angel, Pre-seed, Seed, Private, Community, Public)
        * Total raise amount and how much is raised
        * Timeframe for the raise (Deadlines)
        * Vesting period
        * Cliff
        * Fully diluted valuation
        * Market cap on launch
        * Button for contribution that activates a pop-up which should contain
        * Dropdown for currency selection
        * Input field for amount to invest
        * Information about % platform handling fee
        * Calculation of their actual invested amount
        * Checker for ToS
        * Button to confirm their contribution
        * Project description subpage per project (accessible via dashboard for each project) which should contain above mentioned information as well as:
            * Team,
            * Research, 
            * Blogs, 
            * Decks/presentations,
            * Disclaimers, 
            * and other associated information fields.
    * View of all available claims for projects that the user has invested in via claims    dashboard with crucial information per project container such as:
    * Project name and logo
    * Round type (Angel, Pre-seed, Seed, Private, Community, Public)
    * Vesting period
    * Next unlocks
    * Current ROI %
    * Claim button to initiate claim of unlocked tokens.

## Tasks

- [X] Able to view all the raises in the opportunity dashboard
- [X] Able to view project name, logo, round type, total raise amount and how much is raised, timeframe from the raise, vesting period, cliff
- [X] Able to view Team, Research, Blogs, Decks/Presentations
- [X] Able to contribute on ETH and SOL
- [X] Able to claim on ETH
- [ ] Search deals
    * 1 hour
- [ ] In Payload Admin Dashboard, allow admins to submit CSV to generate Claims
    * 4 hours
- [ ] In Payload Admin Dashboard, allow admins to download contributions based on opportunities
    * 4 hours
- [ ] Deploy SOL Contribute function to production
    * 1 hour
- [ ] Contribute with multitokens
    * Need to migrate contracts on SOL and ETH
    * Migrate old database records to take array of accepted currencies
    * 32 hours
- [ ] UI Changes
    * Blocked
    *  32 hours
- [ ] Filters
    * Blocked
    * 2 hours
- [ ] Graphs in profile page
    * 8 hours

## Blockers

* Missing designs for next unlocks
* Missing designs for filters and exhaustive list
* Missing designs for ToS
* Missing designs for % platform handling fee
* Missing designs for calculation of their actual invested amount
* Missing designs for disclaimers
* Explaination of how BTC contribution and claims work

## Scope

* Emails from activities:
    * Confirmation of contribution amount.
    * Notification 1 week before TGE of invested project tokens.
    * Notification of claimed token amount from projects. 

## Tasks

- [ ] Email SMTP
    * 1 hour
- [ ] Send Email Confirmation after contributions
    * Blocked
    * 1 hour
- [ ] Scheduler Daily to send emails based on TGE 1 week before
    * Blocked
    * 1 hour
- [ ] Send Email Confirmation after claim
    * Blocked
    * 1 hour

## Blockers

* Missing Email templates for confirmations of contributions and claims, 1 week before TGE

## Scope

* Application form pop-up via button (cta) with input fields sent to OMGinvest email:
    * First Name
    * Last Name
    * Email
    * Discord handle or TG ID
    * Linkedin (If applicable)
    * Project Name
    * Where is your project based out of
    * Project Description
    * Project Website
    * Project main social link
    * Drag and drop for files (Decks, Tokenomics, Roadmap)
    * Additional information (Backers, accolades etc)
    * Where did you hear about OMG

## Scope

* Guilds application from pop-up via button (cta) with input fields sent to OMGinvest email:
    * First Name
    * Last Name
    * Email
    * Discord handle or TG ID
    * Linkedin (If applicable)
    * Community/Investment group Name
    * Community/Investment group Description
    * Is your company/project incorporated
    * Community/Investment group Website (If applicable)
    * Community/Investment group main social link
    * General ticket size per investment
    * How much has your group raised for projects so far (Ballpark number)
    * Drag and drop for files (Decks etc)
    * Additional information (Notable members, accolades etc)
    * Where did you hear about OMG

## Tasks

- [ ] Create UI for form submissions
    * 1 hour
- [ ] Create record for forms
    * Blocked

## Blockers
* Missing designs for both forms

## Scope

* Profile level system to track progress in performing tasks and activities tied to the platform itself or via third-party platforms. (create the functionality but we will decide to switch it on at a later stage (this will at the later stage be rewarding users with achievements and badges, which is OOS atm))

## Tasks
- [ ] Admin Badges creations and awarding badges based on conditions set in admin dashboard
    * Blocked
    * 32 - 48 hours

Blockers
* Exhaustive list of tasks and activities

## Scope

* Investment Seasons (First iteration can be manual, subsequent seasons should be created   through dashboarding on admin side, also OOS)

## Tasks

- [ ] Create Seasons record in backend
    * Blocked
    * 16 hours


## Blockers
* Explaination of how seasons work and the hierarchy in terms of everything

## Scope

* Progress bar for ranks (if possible we can use the base functionality from the profile level system here) which will be based off of investment activity in-season and a backend system for tracking and distribution of rewards based off of:
    * Investment Seasons Leaderboard which will focus on metrics such as:
    * Invested amount within season which is translated into points, current thinking is 1 USD = 1 Point

## Tasks

- [ ] Create scripts to create statistics for past contributions
    * 1 hour
- [ ] Track after contributions
    * Handled by above
- [ ] UI Changes
    * 8 hours

## Scope

* Multichain payment options and settlement for payments: USDT, USDC, ETH, SOL, and OMG token (upcoming feature) Suggest using Spark.xyz

## Tasks

- [ ] Investiage Spark DOCs and see how it fits with the current system
    * 2 hours
- [ ] Migrate existing systems to use SPARK
    * 32 - 48 hours

## Scope

* Profile settings and customization which should allow the user to manage:
    * PFP (Profile Picture), 
    * display name, 
    * bio
    * categories of interest
    * ability to see wallet balance, 
    * P&L, 
    * return on investments (ROI), 
    * how much user contributed via investing on the platform, 
    * how many deals user invested in, 
    * What tier the user currently holds in OMG.

## Tasks

- [ ] Create Profile Record with the associated fields
    * Blocked
- [ ] Snapshot USD value at different points 
    * 1 hour
- [ ] Implement graphs to show contributions / claims / PnL
    * 4 hours
- [ ] Implement wallet tracker of tokens (from platform)
    * 8 hours
- [ ] Implement profiles page
    * 4 hours
- [ ] Exhange feature
    * Blocked

## Blockers

- Missing designs for Profile Form
- Missing feature explaination for exchange

## Scope

* Website theme toggling between dark and light versions. 

## Tasks

- [ ] Migrate existing styles to support themes
    * 8 hours

## Blockers

- [ ] Exhaustive list of all the colors and their counter part

## Scope

* Referral program functionality with referral link generation and tracking capabilities.  

## Tasks

- [ ] Create unique referral codes
    * 1 hour
- [ ] Track referral codes in signup 
    * 1 hour

## Blockers

- [ ] Missing designs for referrals in profile page
- [ ] Missing designs for referral during sign up
 
## Scope

* Create and manage raises, which should include:
    * Project name and logo
    * Team
    * Research
    * Blogs
    * Decks/presentations
    * Disclaimers
    * and other associated information fields.

## Tasks 

- [X] Can create / manage raises including project name and logo, team, research
- [ ] Implement submission decks / presentations
    * 1 hour
- [ ] Implement blogs
    * 1 hour
- [ ] Implement submissions of disclaimers
    * 1 hour

## Blocker
- [ ] Gather scope around how blog submissions work
- [ ] Gather scope around how disclaimers are submitted

## Scope

* Multiple round functionality with input fields for:
    * Total raise amount
    * Timeframe for the raise(s) (Deadlines)
    * Vesting period(s)
    * Cliff(s)
    * Fully diluted valuation(s)
    * Market cap on launch
    * Different wallet addresses for the different stages of the raise
    * Publishing of project to the platform for users to start investing
    * Overview of applications from Projects and Guilds to approve or reject, 
    * Overview to manage user contributions/investments.
*  Approve and remove other administrators and guild owners. 

## Tasks
- [ ] Migrate current application from ADMIN/USER role to ADMIN/USER/SUPERADMIN
    * 2 hours
- [ ] Close access and authorisation based on role
    * 1 hour
- [ ] Approval of applications
    * 1 hour
- [ ] Approval / Removal of adminstrators and guild owners based on access control
    * 1 hour

## Scope
* Landing Page

## Tasks
- [ ] Use payload to load the content
    - 2 hours
- [ ] Implement the landing page with integration with payload CMS
    - 12 hours

## Scope
* Reskin

## Tasks
- [ ] Some of this should be done with the theming
- [ ] Implement the new designs
    * 32 - 48 hours

## General Blockers
* Missing designs for Portfolio
* Missing designs for Pledges
* Missing feature for Upgrade
* Missing designs in Settings
* Missing designs in History
* Missing designs in Community
* Missing designs in News
* Missing designs in Support
* Explaination on how notifications work 
* Missing scope of how Guilds
    * How do you join the guild?
    * How do you access the guild page?
    * Missing My Guild Page
* Missing Top Investors Page