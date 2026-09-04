Detailed Overview: LumeAir Platform
LumeAir is a modern, web-based environmental monitoring application engineered to deliver real-time air quality tracking, localized atmospheric analytics, and actionable health insights. Deployed on Google Cloud Run, it offers a scalable, low-latency experience tailored for individuals, urban planners, and health-conscious communities.

Core Features & Functionality:
1. Real-Time AQI & Pollutant Tracking:
Air Quality Index (AQI): Displays real-time AQI scores categorized by standard health impact scales (Good, Moderate, Unhealthy, Hazardous).

Particulate Matter Analysis: Tracks fine and coarse inhalable particles:

PM2.5: Fine combustion particles and smoke.

PM10: Dust, pollen, and larger airborne particles.

Gas Concentrations: Monitors key gaseous pollutants including Nitrogen Dioxide (NO 
2
 ), Sulfur Dioxide (SO 
2
 ), Carbon Monoxide (CO), and Ground-level Ozone (O 
3
 ).

2. Location-Based Environmental Intelligence:

Geolocation Detection: Automatically detects local air quality upon launch.

Search & Multi-City Comparison: Allows users to query specific cities or regions worldwide to assess air quality before traveling or planning events.

Atmospheric Context: Integrates ambient weather conditions—such as temperature, humidity, wind speed, and atmospheric pressure—which directly influence pollutant dispersion.

3. Actionable Health Recommendations:

Activity Guidance: Provides practical suggestions based on current AQI levels (e.g., advising sensitive groups to wear masks, limit prolonged outdoor exertion, or run indoor air purifiers).

Trend Awareness: Helps users identify peak pollution hours during the day to optimize outdoor activities.

Technical & Architectural Highlights:

Serverless Infrastructure: Hosted via Google Cloud Run, ensuring high availability, automatic scaling during traffic spikes, and minimal latency globally.

Responsive Frontend Design: Built with a modern client-side framework to deliver a fluid experience across desktop browsers, tablets, and smartphones.

Dynamic API Integration: Continuously fetches updated environmental datasets from global atmospheric monitoring networks to maintain data precision.

Key Use Cases:

Daily Health Planning: Individuals with respiratory conditions (such as asthma or allergies) can track particulate levels to reduce exposure.

Outdoor & Fitness Tracking: Runners and athletes can schedule training around cleaner air windows.

Urban Mobility: Travelers and commuters can compare air quality profiles across different districts or destination cities.
