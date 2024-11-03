# A Dataset on Peering Policies of Autonomous Systems

## Introduction
The Internet's performance hinges on how Autonomous Systems (ASes) choose their peering partners. 
While ASes document their peering requirements and preferences in policy documents, the unstructured 
nature of these texts has limited their systematic analysis. 
This dataset contains structured dataset that was extracted
from the policy documents using natural language processing.

The dataset accompanies the paper below.

## What's in a Peering Policy Document?

📋 **General Requirements**
- 24/7 Network Operations Center
- Updated PeeringDB records
- MANRS compliance
- Internet Routing Registry usage

🌐 **Traffic Specifications**
- Volume thresholds for IXP and PNI
- Ingress/egress traffic ratio requirements
- Geographic coverage rules
- Multi-location connection mandates

🔒 **Routing & Restrictions**
- Route acceptance criteria
- Best/shortest exit routing policies
- Customer peering limitations
- Transit customer minimums

📝 **Administrative**
- Contract requirements
- Paid peering options
- Peering relationship terms


# Description of extracted data

| Field | Description |
|-------|-------------|
| peeringdb | Requires updated PeeringDB |
| manrs | Requires MANRS |
| noc | Requires NOC |
| rpki | Requires RPKI |
| irr | Requires IRR |
| min_coverage | Min. required peering locations |
| traffic_ratio | Desired traffic ratio |
| traffic_vol | Min vol for IXP peering |
| pni_volume | Min vol for PNI |
| routing_practice | Routing practice e.g shortest/best-exit |
| which_routes | Routes that can be advertised |
| No customer | Does not peer w/ customer |
| No customer of customer | No peering w/ customers |
| consistent_route | Requires same routes to be advertised |

## References
To read more about the methodology used or to cite this dataset,
please see;
