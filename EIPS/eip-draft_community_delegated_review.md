---
title: Community Delegated Review Group for EIPs
description: Introduces volunteer review groups for all EIPs.
author: Nima Rasooli (@EmperorOrokuSaki)
discussions-to: <URL>
status: Draft
type: Meta
created: 2024-08-06
requires: 1
---

## Abstract

This Meta EIP proposes the creation of a Community Delegated Review Group (CDRG) that is responsible for reviewing all EIPs. The CDRG does not have any special powers to reject or approve EIPs but ensures that a group of volunteered individuals thoroughly reads and provides feedback on each proposal.

## Motivation

The aim is to enhance the review process for EIPs by ensuring that every proposal is read and reviewed by a dedicated group of community members during both the early review stages and the Last Call stage. This improves the quality of feedback, helps identify potential issues or improvements before final approval, and avoids indefinite delays that can result in stagnation.

## Specification

The key words "**MUST**", "**MUST NOT**", "**REQUIRED**", "**SHALL**", "**SHALL NOT**", "**SHOULD**", "**SHOULD NOT**", "**RECOMMENDED**", "**NOT RECOMMENDED**", "**MAY**", and "**OPTIONAL**" in this document are to be interpreted as described in RFC 2119 and RFC 8174.

1. **Formation of the Community Delegated Review Group (CDRG):**
   - The CDRG **MUST** consist of volunteers from the Ethereum Magicians forum who are active members and have demonstrated experience with the EIP process.
   - Members of the CDRG **MUST** be selected through a community nomination and voting process, conducted every three months on the Ethereum Magicians forum.
   - A rotation system **MUST** be implemented to periodically refresh the group and distribute the workload evenly among members.

2. **Role and Responsibilities:**
   - The primary role of the CDRG is to review EIPs during both the early review stages and the Last Call stage.
   - CDRG members **MUST** provide detailed feedback and ensure that all aspects of the proposal have been thoroughly considered.
   - The CDRG **MUST NOT** have the power to approve or reject EIPs; their role is purely advisory.
   - CDRG members **MUST** adhere to guidelines and training provided to standardize the review process and maintain consistent quality.

3. **Review Process:**
   - EIPs **MUST** be assigned to CDRG members for review during the early review stages to provide initial feedback and identify potential issues early on. At least one member of the group **SHOULD** provide reviews in the early review stage of new EIPs.
   - During the Last Call stage, all CDRG members **MUST** conduct a final review and provide additional feedback.
   - Each CDRG member **MUST** be responsible for reading and providing feedback on a subset of EIPs during the early review stages, ensuring coverage of all proposals.
   - Feedback from CDRG members **MUST** be documented and made publicly available to ensure transparency.
   - The group **MUST** have regular meetings, at least one per month, to ensure that nothing is blocked and continuous updates are being provided. The group **MAY** have more meetings if needed.
   - It is in the group's own power to split responsibilities in the review stage of each EIP, but for Last Call, all members **SHOULD** provide reviews.

4. **Community Engagement:**
   - The CDRG **MUST** hold regular meetings (at least once a month) to discuss ongoing reviews and gather collective insights.
   - These meetings **MUST** be open to the public, and minutes **MUST** be recorded and published for community reference.
   - The benefits of thorough reviews in improving proposal quality **MUST** be highlighted, and support **MUST** be provided to authors throughout the process.

5. **Accountability and Reporting:**
   - CDRG members are **REQUIRED** to submit regular reports on their review activities, including the number of EIPs reviewed and the nature of feedback provided.
   - A report summarizing the CDRG's activities and impact **MUST** be published every three months for community review.
   - Performance metrics and regular evaluations **MUST** be implemented every three months to ensure CDRG members are meeting their responsibilities effectively.

6. **Evaluation and Adjustments:**
   - The effectiveness of the CDRG **MUST** be evaluated every three months based on community feedback and the quality of reviews provided.
   - Adjustments to the CDRG process and structure **MUST** be made as needed to ensure continued effectiveness and community alignment.

## Rationale

This design works because of its compatibility with the current flow of the EIP process as specified in [EIP-1](./eip-1.md). The Community Delegated Review Group (CDRG) is introduced as an additional layer of review during both the early review stages and the Last Call stage, complementing the existing review mechanisms without altering the fundamental structure of the EIP process. The CDRG's advisory role ensures that the final decision-making power remains unchanged, thereby maintaining the integrity of the current process. This approach aligns with the principles and procedures outlined in EIP-1, ensuring seamless integration and enhancing the overall efficiency and transparency of the review process.

## Backwards Compatibility

No backward compatibility issues found.

## Security Considerations

Needs discussion.

## Copyright

Copyright and related rights waived via [CC0](../LICENSE.md).
