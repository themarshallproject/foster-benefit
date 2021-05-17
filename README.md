# Foster care benefits policies by state

In collaboration with NPR, The Marshall Project [investigated the practice of states collecting federal benefits](https://www.themarshallproject.org/2021/04/22/foster-care-agencies-take-thousands-of-dollars-owed-to-kids-most-children-have-no-idea), including social security and survivors' benefits, on behalf of foster children. In many states, the money collected goes into state coffers, often used to fund the child's own care.

The data was compiled from a combination of sources:

* A 2018 survey by nonprofit research group Child Trends (CT), which asked states to report how much they received annually from these sources
* A Marshall Project/NPR survey of states regarding the use of private contractors in securing these funds
* A Marshall Project/NPR survey of states related to where the funds end up and whether children are notified


## The data file includes these fields:

* \`contractor\`: the private firm that helps collect benefits for the state, collected by NPR and The Marshall Project.
* \`source\`: how NPR and The Marshall Project reporters determined whether a state takes funds.
* \`ssi_income\`: total Social Security income reported to CT.
* \`ss_disability\`: total disability insurance income reported to CT.
* \`ss_survivors_benefits\`: total survivors' benefits income reported to CT.
* \`ss_total\`: The sum of \`ssi_income\` + \`ss_disability\` + \`ss_survivors_benefits\`, calculated from CT columns. This is the number we used for [our investigation](https://www.themarshallproject.org/2021/04/22/foster-care-agencies-take-thousands-of-dollars-owed-to-kids-most-children-have-no-idea).
* \`veterans_admin\`: Benefit issued by the Veterans Administration, as reported to CT.
* \`child_support\`: Child support to the foster children, as reported to CT.
* \`total\`: Total amount of money the state took from foster children in 2018, as reported to CT.
* \`other_sources\`: Other benefits that the state took from foster children, as reported to CT.
* \`agency_name\`: The agency responsible for foster care service.
* \`agency_url\`: A link to the responsible agency's contact page.

This data was used for the story [Foster Care Agencies Take Thousands of Dollars Owed to Kids, Most Children Have No Idea](https://www.themarshallproject.org/2021/04/22/foster-care-agencies-take-thousands-of-dollars-owed-to-kids-most-children-have-no-idea) by Eli Hager.
