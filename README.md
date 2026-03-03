# changing-a-tax-return---personal-income-tax COP

*description of the COP*

**COP timeframe** 2026-02-17 - 2026-05-26

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/changing-a-tax-return---personal-income-tax](https://cra-proto.github.io/changing-a-tax-return---personal-income-tax)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-03

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Income tax)
    node4(Personal income tax)
    node5(After filing a tax return)
    node6(Changing a tax return)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node4 --> node6
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/income-tax.html" _blank
    click node4 "https://www.canada.ca/en/services/taxes/income-tax/personal-income-tax.html" _blank
    click node5 "https://www.canada.ca/en/services/taxes/income-tax/personal-income-tax/after-you-file.html" _blank
    click node6 "https://www.canada.ca/en/services/taxes/income-tax/personal-income-tax/after-you-file/change-return.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node6 inscope
    classDef ismoved fill:#eab308,color:#000
    class node6 ismoved
```
