# Research Data Collection Use Case

## Scenario Overview

A university research team uses their **CivilScout** account to request aerial survey data to study animal species distribution in a specific geographic area. This case demonstrates how CivilAirspace facilitates collaboration between CivilScouts, airspace owners, and drone operators.

![Aerial Survey Data](../images/AerialSurveyData.png)

## Workflow

### 1. Research Request Submission
The university research team, through their **CivilScout** interface:
- Specifies geographic boundaries of the study area.
- Defines required flight altitudes.
- Sets data collection frequency (e.g., daily, weekly).
- Details image/sensor requirements (e.g., thermal imaging, LiDAR).
- Outlines project timeline.
- Provides research budget parameters.

### 2. Network Response
The **CivilAirspace** network automatically:
- Identifies relevant airspace zones.
- Locates participating airspace owners.
- Calculates optimal flight paths for drones.
- Estimates data collection costs based on project parameters.
- Generates default licensing terms for data usage.

### 3. Airspace Owner Association
Airspace owners receive automated notifications when their airspace is requested for research operations:
- Owners can temporarily associate their airspace with the project using ad-hoc agreements.
- Default terms are presented to all parties involved (airspace owners, drone operators, CivilScouts).
- Owners can modify or accept terms directly through the app.
- Smart contracts manage group consensus and finalize agreements.

### 4. Service Agreement
The **Service Agreement** outlines the terms for all parties involved:
- **Access schedules**: When drones can access the airspace.
- **Compensation rates**: Payment rates for drone operators and airspace owners.
- **Data usage rights**: Licensing terms for collected data.
- **Collection parameters**: Specific requirements for data collection (e.g., resolution, sensor type).
- **Quality requirements**: Minimum standards for data quality.
- **Delivery timeline**: Deadlines for data submission and verification.

### 5. Operational Execution
Qualified drone operators bid on collection tasks:
- The network coordinates flight operations based on the approved service agreement.
- Real-time monitoring of data collection ensures compliance with quality standards and regulations.
  - **[Remote ID Verification](../docs/Remote_ID_Verification.md)**: Ensures that all drones meet Remote ID requirements during operations.
  - **[LAANC Authorization Check](../docs/LAANC_Authorization_Check.md)**: Confirms that flights in controlled airspace have received proper LAANC approval before takeoff.
- Quality assurance checks are performed during and after flight operations to verify compliance with the service agreement.

### 6. Value Distribution
Smart contracts manage value distribution among participants:
- Research team payments are automatically processed through CIVIL tokens or other supported currencies.
- Airspace owner compensation is distributed based on usage terms.
- Drone operator fees are calculated based on the amount of data collected and operational costs.
- Network service fees cover infrastructure maintenance (e.g., control towers, credentialing nodes).
- Data verification rewards are distributed to nodes that ensure compliance and data quality.

### 7. Data Delivery
Once the data is verified and stored on IPFS:
- Access is granted to the research team through secure links managed by smart contracts.
- Usage rights are transferred according to the licensing terms agreed upon in the service agreement.
  - **Data Provenance**: All collected data includes provenance records that detail who generated it and when it was collected. This ensures transparency and traceability for future use cases or citations in research papers.

![How to Initiate Research](../images/HowtoInitiateResearch.png)

## Benefits

### For Researchers
Researchers benefit from streamlined access to high-quality aerial survey data:
- **Streamlined Data Acquisition**: The CivilAirspace network automates many aspects of data collection, making it easier for researchers to acquire the information they need without managing logistics themselves.
- **Quality Assurance**: All collected data undergoes strict quality checks before delivery to ensure it meets predefined standards.
- **Clear Pricing**: Transparent pricing models allow researchers to plan their budgets effectively based on project scope and requirements.
- **Simplified Coordination**: The platform handles coordination between drone operators and airspace owners automatically, reducing administrative overhead for researchers.
- **Verified Data Provenance**: Researchers can trust that all delivered data includes provenance records that verify its authenticity.

### For Airspace Owners
Airspace owners benefit from passive income opportunities by allowing drones to operate in their airspace:
- **Automated Licensing**: Smart contracts handle licensing agreements between airspace owners and drone operators automatically.
- **Fair Compensation**: Owners receive compensation based on usage rates defined in service agreements with researchers or drone operators.
- **Usage Tracking**: Owners can track how their airspace is being used through real-time dashboards within the app.

### For Drone Operators
Drone operators gain access to pre-vetted customers and streamlined workflows:
- **Pre-Vetted Customers**: Operators can bid on projects submitted by trusted CivilScouts (e.g., research teams), ensuring they work with reliable clients who have clear project goals and budgets.
- **Optimized Routes**: AI-powered route planning helps operators optimize flight paths based on weather conditions, airspace availability, and regulatory requirements (e.g., Remote ID compliance).
- **Quality Verification**: Operators receive rewards for maintaining high-quality standards during data collection, incentivizing them to deliver top-tier results consistently.

