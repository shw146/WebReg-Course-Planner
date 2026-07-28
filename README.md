# WebReg Course Planner Accessibility Revisions

This is project is based on the legacy WebReg Course Planner made by SahirSSharma found on github at https://github.com/SahirSSharma/WebReg-Course-Planner

It is important to note that since the beginning of this project (7/28) the original has been moved to https://tritonplan.com/ 

The goal of this fork is to identify, justify, and create revisions to the original site in order to comply with accessibility standards. The rest of this document will entail a list of these revisions.

## Revisions
1. Various div tags have been replaced with custom tags and CSS has been edited to reflect the same. Most importantly opens compatibility with screen readers.
2. Classes changed to IDs because they were only being used once in the entire document. Done for semantic understanding. Lines 99-105 and various other locations
3. mig-hd elements changed to h2 to better reflect semantic meaning. Lines 108 and 121
4. Bold inline tags have been changed to strong tags to better reflect the semantics of the sentences. Helps with screen reader support. Lines 124 and 126
5. Footer text color changed from a light gray to black. Since this is just a legacy site, there's not a lot of reason to adhere to a color palette, so it makes more sense to change the bad contrast for accessibility. CSS file line 914
6. Wrapped top area in a header element for semantic meaning and to enable easy site traversal by screen readers. Lines 52 to 83
7. Moved footer outside of main as per W3 specification and allows for easy screen reader traversal. Lines 141 to 147