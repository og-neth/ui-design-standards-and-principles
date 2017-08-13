# ui-design-standards-and-principles
This document outlines discussion points from personal industry experience with UI design and development for large enterprise applications that are tool centric and aims at proposing a running specification of UI design standards and principles for such large tool sets. 
# Objective
The purpose of this document is to assist in solidifying UX requirements for Product Teams (Product Managers, Business Analysts, Designers, other stake holders) during the discovery and requirements gathering process. While most Agile shops simplify requirements in their user stories and acceptance criteria. It is my belief that these processes lack an underlying organizational UX framework to approach the UI design and development. 
# User Flow Standards
Define the UI in groups or sections that relate to all tools. Users intuitively will have the same expectations if we institute user flow standards, this reduces having to re-learn a new set of tools for any new feature that is launched under any application's tool set. 

1. Actions
    1. Basic and Advanced
        - At a bare bones minimum, any tool should be operable with a basic set of actions (submit, cancel, add, set, delete). 
        - This does involve in some cases making the UI smarter in order to anticipate a user action or guide (hook) the user into adopting the behavior that is optimal to making tool use efficient. (main goal: efficiency operating the tool)
        - Advanced users should be provided the ability to ‘open’ these advanced actions/settings that they can manipulate to achieve the customized result they are seeking.
2. User Input
    1. Required, Optional and Conversional
        - At a bare bones minimum, we should only show what information we require of the user in order to successfully submit the form we are displaying to them.
        - Optional information, should be hidden and visible by providing the user the ability to enter this optional information should they wish to enter it.
        - Conversional information (information that can be updated on a frequent basis but is not required) should also be given hierarchy to promote efficient usage by the user.
        - Enable actions users can perform after making validated selections or data input (Decreases the need for unnecessary null checking and logic is written to function precisely based on the user initiated trigger.)
3. Results – also see Perceived Performance bullet point
    1. Users expect a result from their interactions with an application. This interactivity is crucial to an optimal UX.
        - Loaders to let user know application is processing their requests and actions. 
        - Loaders also freeze the page from user fat fingering or double clicking elements that can trigger application logic to process multiple times. 
    2. Error Handling
        - Any user triggered submission of any kind i.e., user entered data or user selection, will cause a request to our services and data bases to POST or GET data. The success or failure of these requests need to be communicated to the user, i.e., notification components (modal or inline).
    3. Form Validation and special cases
        - Required fields need to be validated for input and or certain patterns (.i.e., masks, emails, dates).
        - Errors should be cleared immediately after user enters valid input.
    4. Real-Time updates
        - User deletions or additions in lists or grids, need to be updated in real time. Some of this behavior comes out of the box in certain widgets in certain UI libraries, in other widgets it is configurable or is engineered from scratch. 
    5. Common Locations
        - Regardless of tools our users are interacting with, placement should be similar in layouts of common sections. For instance actions to perform on a page and or inner navigational items should have a consistent placement and design. This type of consistency increases the intuition we want from users when interacting with the tools. Common placement unifies the entire website. Style guide lines should also have placement guidelines of content/UI types.
4. Options (secondary, tertiary)
    - Any view a user visits needs to clearly define a conversion goal (CTA). Whether it is a download, a click through, a submission or another type of interaction we seek from the user. We should limit the ‘options’ or CTAs on a page so that users are clearly funneled into this conversion.
5. Perceived Performance – also see Results bullet point
    1. Intro article: [http://blog.teamtreehouse.com/perceived-performance](http://blog.teamtreehouse.com/perceived-performance)
        - Display loading iconography or progress bars (data submission, data retrieval, any action involving data over the server).
        - Lazy Loading
# Examples
## Actions - Basic and Advanced

## User Input – Required, Optional and Conversional

## Results – Error Handling

## Results – Common Locations

# Hierarchy Placement Map 
Hierarchy of content is a great strategy for setting the placement and flow of conversional goal content and call to actions. The following maps are based on a left to right language direction. Mobile is self-explanatory. 




