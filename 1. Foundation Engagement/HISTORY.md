Below is a brief overview of the background documents that Amin, the product owner from PIC, put together. You can view them on the [Google Drive account](https://drive.google.com/drive/folders/0B2stDO5hLAHkR09EZFNMOUo3anc). There’s a lot of detail, but they’re all worth reading. 

## Background (based on a discussion paper developed on August, 2017) 
2017 is the first time performance.gov will need to be updated in response to a presidential transition. *The current site meets certain compliance requirements, but does not give agencies a compelling tool to tell their story or update their content on a regular basis.* 

## Product Vision 
- [This document](https://drive.google.com/drive/u/0/folders/0B2stDO5hLAHkVlhNU3BxVTVHeEU) lays out a detailed vision for the new performance.gov: 
	- *Clear communication of priorities and results* - should help the admin communicate its goals and priorities and the results achieved. It should be able to reflect changes in the priorities and objectives without impacting the underlying performance data. 
	- *Increased transparency* - make federal data more accessible and transparent for a variety of audiences. Make it easier for people to access the performance of government. 
- _Guiding principles_: 
	- *More focused on data* - the existing site included significant exploratory narrative around objectives and indicators, but the data was difficult to access and only existed in the context of priority goals. The new site should focus more on acting as an accessible and searchable long-term repository for performance data across govert and the data should be independent of changes in priorities. 
	- *API-driven*: The site must also enable machine readable data as well as provide an API layer so that external users can harness the data. 
	- *Better integrated with spending & other datasets* - Congress in particular is interested in better integration of performance data with spending and financial data (e.g., USASpending.gov). 
	- Better user experience for both internal (admins?) and external audiences (consumers?) 
	- *Legal compliance* - the GPRA Modernization ACT of 2010 (see below) lays out the framework and statutory requirements for the new performance.gov. 
	- Minimize reporting burden - the site will leverage technology and infrastructure to the extent possible to allow for the sharing of data across systems and existing agency APIs. 
- A minimum viable product (MVP) will be in place by February, 2018, with a strategy and concrete steps to further develop a more robust site over time. 
	- The site will likely not support much more than the posting of links and PDFs by Feb, although the PIC and OMB teams ask that agencies weigh in on *what the reporting model might look like as we move towards implementing a broader vision.
		- **As is described in the document, it is unclear if agencies have the capabilities to meet more robust reporting models. This could be a key constraining factor for the emerging product vision.** 

### Other drivers (policy & deadlines): 

- *Government Performance and Results Act (GPRA) of 1993* - requires each agency to produce a strategic plan every three years, an annual performance report each february, and annual performance report. 
- *GPRA Modernization Act of 2010* - a variety of reforms aimed at modernizing the government's nearly two-decade old performance management framework. Requires agencies to update their Strategic Plan every four years. Congress also included transparency provisions in GPRAMA, which makes OMB responsible for: 
	- Priority goals - establish a single federal website that provides updates on cross-agency and agency priority goals, including quarterly measures and milestones
	- Federal program inventory - develop a consolidated list of fed govt programs for inclusion on the site; and
	- Agency performance plans and reports - making available all agency strategic plans, annual performance plans, and annual performance reports on this website in a "searchable and machine-readable format"
- *[GAO Report](http://www.gao.gov/assets/680/679395.pdf)* Summary of findings
	- While OMB Has Enhanced Performance.gov, Further Actions Could Make It More Useful
	- OMB, GSA, and the PIC Collect Some Customer Feedback but Have Not Engaged Broader Audiences
	- OMB and GSA Conducted a Usability Test, but Key Actions Remain Unaddressed
	- OMB and the PIC Have Made Progress in Tracking Additional Performance Measures, but Have Yet to Establish Goals
	- Our Prior Reports Found Performance.gov Does Not Consistently Meet GPRAMA Requirements
	- OMB Does Not Have a Strategic Plan for the Future of Performance.gov
	- OMB and the PIC Do Not Have a Customer Outreach Strategy
	- Performance.gov Does Not Inform Users of Latest Updates
	- OMB Has Not Incorporated Social Media into Its Customer Outreach
	- Performance.gov Is Accessible on Mobile Devices, but OMB Has Not Yet Determined Whether to Pursue Mobile Applications
	- OMB and the PIC Do Not Have a Plan to Maintain Archived Data
- Agencies are updating their goals and objectives for release in February 2018 along with the President’s next budget submission to Congress. A new variant of performance.gov is needed by then. 
- Demos
	- https://www.youtube.com/watch?v=AVA7aRAVJIo
	- https://www.youtube.com/watch?v=OqChFe4YLxA
- Re-design Attempt
	- Google Drive: https://drive.google.com/drive/folders/0B2stDO5hLAHkOEdVVFpmTlVFSjg
	- Prototype: https://projects.invisionapp.com/share/8SCPNF7BQ#/screens/245111677_Homepage
	- Wireframes: https://projects.invisionapp.com/share/JNBRWI8UC#/screens/234426288




### Key stakeholders / Prospective users:
- White House & OMB has the responsibility of implementing the GPRA modernization act legislation. 
- Federal agencies - all agencies are responsible for meeting the requirements of GPRAMA and for providing input to OMB to best present a coherent performance story for the federal programs they manage. 
- Congress - general and committee members looking for broad and or specific areas of focus regarding federal performance and programs
- General public - those interested in learning more about the federal govt and those looking for agency program information. 
- Special interest groups - media, academia, scientists, researchers, evaluators, contractors, advocacy groups, think tanks, etc.
- Check out more detail on personas and stakeholders [here](https://drive.google.com/drive/u/1/folders/0B2stDO5hLAHkUzdjTWhVS1IxS0U): 
	- Basically this says that they want to focus on the management layer within agencies that struggles to extract value/meaning from the performance data reported internally. They sit at the middle of the reporting ecosystem. 

## Usability insights for the current performance.gov site: 

- General pain points observed:
	- Difficulty finding content through search and lack of confidence in search results
		- Search produces poor results, with results seemingly not being connected to search terms  
	- Purpose of site is not clear 
		- Who is the intended audience? 
		- Who owns the site? 
		- What can I do with the site? 
		- Accessibility issues for people with disabilities (508 compliance) 
		- Broken links
			- "Why am I going to performance.gov if i’m just being misdirected to external links 
		- Difficulty finding and interpreting data 
- Data insights 
	- Page views for performance.gov is comparable to 18F.gov, although the number of unique page views is considerably less. 
	- Most usage comes from new visitors (62% compared to 37%)  - people don’t seem to come back to the site after their first visit.
- UI/Data Mapping 
	- Amin has prepared a really helpful overview of where certain elements in the current UI come from. It’s worth checking out [here](https://drive.google.com/drive/u/0/folders/0B2stDO5hLAHkWjM1T29uUlVSUWM). 
- Publication process 
	- Read about it [here](https://drive.google.com/drive/u/0/folders/0B2stDO5hLAHkWUlucVhlTzZ0dzQ). 
	- Basically it involves a lot of people and steps and is no way "self service"
	- There are also different reporting cadences, each of which requires information to flow through different channels: 
		- Quarterly - both cross-agency priority goals and agency priority goals are updated quarterly. Cross-agency goals are submitted via email to the PIC team for review, while agency goals are submitted through PREP. 
		- Annual
		- Ad hoc - agencies can update previously submitted data. These are made at the discretion of the agency and published outside of the quarterly update process. 
