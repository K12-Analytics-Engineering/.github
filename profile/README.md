## Welcome! 👋🏽

K12 Analytics Engineering is a project maintained by [Marcos Alcozer](https://www.alcozer.dev). The goals are to clearly communicate best practices around analytics engineering in K12 education, help data folks in school districts upskill themselves, and have fun doing it. This project exists as both open-source and cloud options. This means you will find open-source code to implement all parts of what you see below.

### Cloud
The cloud version of the project creates the relationship shown below. Alcozer Consulting takes on the responsibility of infrastructure as well as the extract and load work. This mean you, the data person at your district, recieve all your source data in BigQuery along with access to a dbt Cloud project so you can focus on the SQL that transforms the data into reporting tables needed by your reports and dashboards.

![managed](/assets/managed.png)

### Connectors
In addition to the solution above, the syncs below are also offered.

* [NWEA MAP to Ed-Fi Sync](https://docs.google.com/document/d/e/2PACX-1vTU5he-xvv99-Mw0hNVXjLdmlUCEDkoFgOdc9A8O1QXwUo1w6uN2wItgzLSA94nu20G4ymlECb6fmsA/pub)
    * The NWEA MAP to Ed-Fi connector from K12 Analytics Engineering retrieves a district's NWEA MAP assessment results nightly and sends the updated assessment scores to an Ed-Fi API.
* [Ed-Fi API to BigQuery Sync](https://docs.google.com/document/d/e/2PACX-1vS0Q_EY2xy_UlOFl6cJM-_BBDlsvYVgenE--MjP3mRbfDcI-BLORb6UPbUQM1enc6EWsO6TKHlGPm_z/pub)
    * The Ed-Fi API to BigQuery connector from K12 Analytics Engineering replicates your district's Ed-Fi data from your Ed-Fi API to BigQuery.
