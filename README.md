# Awesome-Mobility-Analytics

## Top Mobility Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Transportation Analytics, Traffic & Origin-Destination Insights, Multimodal Mobility, Location Intelligence & Urban Movement Data*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobility Analytics**. These systems analyze how people and vehicles move—using location data, sensors, cameras, and models—to deliver insights on traffic volumes, origin-destination patterns, mode share, congestion, transit performance, and urban mobility for planners, agencies, and private operators.



**Examples** include StreetLight Data, Replica, INRIX, UrbanLogiq, Populus, Numina, Citilabs, Cuebiq, TransitScreen, and Steer (the category leaders).



**Open-source emphasis**: Commercial mobility analytics platforms dominate large-scale, privacy-compliant location data products. Open-source activity is strong in video-based traffic analysis, multimodal trip planning, transport modeling, and research toolkits. This section lists every major relevant project and building block found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[StreetLight Data](https://www.streetlightdata.com/)**  

  Leading mobility analytics platform providing empirically derived vehicle, bicycle, and pedestrian metrics, origin-destination insights, and roadway performance analytics from anonymized location data.



- **[Replica](https://www.replicahq.com/)**  

  Platform delivering detailed, modeled mobility and activity data for urban planning, transportation, and built-environment decision making.



- **[INRIX](https://inrix.com/)**  

  Global mobility intelligence provider offering traffic speeds, travel times, roadway analytics, parking/curb insights, and real-time/historical mobility data.



- **[UrbanLogiq, Populus, Numina](https://www.urbanlogiq.com/)**  

  Platforms focused on multimodal analytics, curb and shared-mobility management, and computer-vision-based traffic and pedestrian counting.



- **[Citilabs, Cuebiq, TransitScreen, Steer](https://www.citilabs.com/)**  

  Solutions covering transportation modeling, location intelligence, real-time transit information displays, and mobility consulting/analytics services.



- **[Other commercial mobility analytics platforms](https://www.streetlightdata.com/)**  

  Additional providers of traffic, OD, mode-share, and urban movement data products for public agencies and private sector use cases.



## Open-Source GitHub Projects



- **[OpenTrafficCam](https://github.com/OpenTrafficCam)**  

  Fully integrated open-source framework for video-based traffic recording and automated analysis. Includes camera hardware (OTCamera), object detection/tracking (OTVision), and traffic metrics from trajectories (OTAnalytics).



- **[OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner)**  

  Leading open-source multi-modal trip planner supporting scheduled public transport, walking, cycling, and mobility services. Built on GTFS and OpenStreetMap; widely used for routing and accessibility analysis.



- **[Mobility (transport modelling package)](https://github.com/mobility-team/mobility)**  

  Open-source Python package for modelling how people move in a territory—synthetic population, daily activity patterns, multimodal networks, and scenario comparison (focused on regions with suitable open data).



- **[Conveyal traffic-tools & related engines](https://github.com/conveyal/traffic-tools)**  

  Collection of open tools for roadway traffic analysis, including engines that convert GPS traces into aggregate speed measures and related traffic operations utilities.



- **[Video & computer-vision traffic projects](https://github.com/search?q=traffic+detection+OR+vehicle+tracking+OR+pedestrian+counting+open+source)**  

  Community repositories for detecting and tracking vehicles, cyclists, and pedestrians from camera feeds to generate counts and trajectories.



- **[GTFS & transit analytics tools](https://github.com/search?q=GTFS+analytics+OR+transit+performance)**  

  Open libraries and pipelines for processing GTFS feeds, measuring transit performance, and supporting accessibility studies.



- **[Urban mobility & OD research code](https://github.com/search?q=origin+destination+OR+mobility+analytics+OR+traffic+simulation)**  

  Academic and civic projects for origin-destination estimation, traffic simulation, and mobility pattern analysis from open or collected data.



- **[GIS & network analysis stacks](https://github.com/search?q=OSMnx+OR+transport+network+analysis)**  

  Open geospatial tools (e.g., OSMnx and related) for extracting and analyzing street networks that underpin many mobility studies.



### Additional Strong Open-Source Options



- **Video analytics pipelines**: OpenTrafficCam or custom CV models for local traffic counting and classification.

- **Multimodal routing & accessibility**: OpenTripPlanner for itinerary generation and equity/accessibility metrics.

- **Transport demand modeling**: Mobility package and similar tools for scenario-based travel demand estimation.

- **Probe/GPS processing**: Open engines that turn location traces into speed and volume estimates.

- **Open data foundations**: GTFS, OpenStreetMap, and public sensor feeds as inputs to custom analytics.

- Composable stacks: OpenStreetMap + GTFS + OpenTripPlanner + local sensor/CV data + open visualization (Kepler.gl, etc.).



**Frameworks for building custom systems**:  

There is no single open-source product that fully replicates the scale, privacy-compliant location data products, and polished analytics of StreetLight, Replica, or INRIX.  

Strong open building blocks include **OpenTrafficCam** (video-based analysis), **OpenTripPlanner** (multimodal routing and accessibility), transport modeling packages such as **Mobility**, and general GIS/network tools.  

These enable local, transparent, and cost-effective mobility studies—especially when combined with open data.  

Commercial platforms remain essential for nationwide/global coverage, validated big-data products, and enterprise support. Many agencies and researchers use open tools for specific corridors or research while relying on commercial data products for comprehensive regional analytics.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Mobility analytics often relies on location data that raises privacy and ethical considerations. Ensure compliance with applicable data-protection laws and ethical guidelines when collecting or processing movement data.

- Open-source tools provide transparency and local control but typically require data collection infrastructure, calibration, and analytical expertise. Commercial platforms supply ready-made, large-scale datasets and support. Choose according to geographic scope, data needs, budget, and capacity.



---



**Made for transportation planners, traffic engineers, urban data scientists, and mobility product teams.**  

Let's expand open, reproducible tools for understanding movement while recognizing the scale and coverage that leading commercial mobility analytics platforms deliver.
