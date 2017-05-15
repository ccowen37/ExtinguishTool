## Synopsis

The Extinguish Tool is a web-based mapping tool focuses on HUD public housing developments that must become smoke-free environments within 18 months of February 3, 2017. The tool provides maps and other visuals about the economic impact of different tobacco cessation interventions would create given local estimates of smokers among information, as well as locations of public housing and health facilities, and demographics of the target population. The maps are meant to help public housing agencies, state and local health departments, and other users to quickly locate, identify and assist smokers in public housing access tobacco cessation services. 

## Site Coding 

The main page (https://chhs.gatech.edu/smokefree) displays our main map, which initializes with a map created in Leaflet. All layers and datasets can be toggled on and off; the initialization shows a county average heat map of public housing smoker estimates as well as Public Housing locations. All point datasets (public housing and health facilities) are loaded via API from their respective sources, with more details provided in the website. 

For the other pages–Smoking Estimates, Medicaid Data, and Quitline Data–the maps and charts are created using D3.js. The data driving the visuazilations comes from various sources, including government sources, a Medicaid dataset accessed through Georgia Tech, and public housing smoker estimates created by the team using small area estimation. More details can be found in the website.  

## Visit

Please visit https://chhs.gatech.edu/smokefree to see the web tool live.  

## Contributors

This project was created as a part of a student senior design project at the Georgia Institute of Technology, collaborating with the Centers for Disease Control and Prevention (CDC). The GT team includes: Aaron Ahn, Kristie Choe, Vishal Mummigatti, Connor Owen, Diem "Dineise" Tran, Jose Rodriguez, Divya Vedula, and Jiali Zhao. 

Many people helped make this project happen, and all can be found in the "About" page of the website (https://chhs.gatech.edu/smokefree/about.html)

-------
The CDC Office of Smoking and Health and the CDC Office of the Associate Director for Science provided expertise and guidance for the development of the Extinguish tool in the support of the implementation of HUD’s Smoke-free policy. However, CDC does not endorse private products, services or enterprises.




 

