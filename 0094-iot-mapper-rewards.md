# HIP 94: IoT Mapping - Mappers Rewards

- Author(s): [@joecryptotoo](https://github.com/joecryptotoo), [ChatGPT](https://chat.openai.com)
- Start Date: 2023-08-10
- Category: Economic, Technical
- Original HIP PR: 
- Tracking Issue: 

## Summary

This HIP proposes revising the rewards for Mappers involved in IoT network coverage mapping, with a focus on various types of mapping activity.

## Motivation

The initial assumption was that mapping would be limited to Network Participants verifying existing coverage with dedicated mapping devices. It is now realized that a more comprehensive approach to mapping is necessary, involving both verification and discovery mapping.

## Stakeholders

- Dedicated mapping device operators will be eligible for IoT mapping rewards.

## Detailed Explanation

### Reward Points Framework for Mappers

This HIP proposes proportionally distributing rewards to all Mapper devices accumulating rewards points for contributing to any of a set of mapping tasks over a 24-hour period.

### Discovery Mapping Rewards

Identifying coverage opportunities is critical to the focus and the objective to bring the maximum amount of data to the IoT Network.

To combat participant influence due to particular or atypical behaviors, this HIP proposes attributing 30 reward points to each Mapper contributing during the 24 reward period.

### Equipment Specifications for Mappers

For mapping IoT (LoRaWAN) coverage, devices must be equipped with the following:

1. **LoRaWAN Radio:** To ensure the capability of measuring Radio signal strength within the network.
2. **GPS:** For precise location data, required for mapping tasks.
3. **ECC608 Chip:** For signing the data packets, ensuring that the data is authentic and has not been tampered with.

These specifications are necessary for accurate and secure mapping of network coverage and must be adhered to by Mappers to qualify for rewards.

### Implementation Timeline

1. **Initial Development:** Development of the necessary software tools (2 months).
2. **Mapper Onboarding:** Introduction of specialized devices to Mappers and initiation of mapping activities (1 month).
3. **Deployment of Reward System:** Implementation of the rewarding algorithm and commencement of rewards distribution (1 month).
4. **Monitoring and Adjustments:** Continuous monitoring of the mapping activities and necessary adjustments to the reward points framework based on real-world data (ongoing).

### Conclusion

This HIP proposes a comprehensive framework for rewarding Mappers in the IoT (LoRaWAN) Network. By focusing on both verification and discovery mapping, and by providing clear equipment specifications, it sets the stage for a more accurate and extensive coverage map.

The detailed implementation plan outlines a feasible path to realization.

Implementation of this proposal will not only improve the accuracy of the IoT network's coverage map but also incentivize the community to actively participate in the network's growth.

## Copyright

This document is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
