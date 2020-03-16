# d3-examples

## How To

Edit [map-cases-us.json](map-cases-us.json) and/or [us-cases-epi-chart.json](us-cases-epi-chart.json)

Run the following in your console on https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html
```
document.getElementById("cdcMaps1").src = "https://www.cdc.gov/TemplatePackage/contrib/widgets/cdcMaps/build/index.html?chost=www.cdc.gov&cpath=/coronavirus/2019-ncov/cases-updates/cases-in-us.html&csearch=CDC_AA_refVal%3Dhttps%253A%252F%252Fwww.cdc.gov%252Fcoronavirus%252F2019-ncov%252Fcases-in-us.html&chash=&ctitle=Cases%20in%20U.S.%20%7C%20CDC&wn=cdcMaps&wf=/TemplatePackage/contrib/widgets/cdcMaps/build/&wid=cdcMaps1&mMode=widget&mPage=&mChannel=&class=mb-3&host=timothybest-usds.github.io&theme=theme-cyan&configUrl=https://timothybest-usds.github.io/d3-examples/map-cases-us.json"; document.getElementById("cdcCharts2").src = "https://www.cdc.gov/TemplatePackage/contrib/widgets/cdcCharts/iframe.html?chost=www.cdc.gov&cpath=/coronavirus/2019-ncov/cases-updates/cases-in-us.html&csearch=CDC_AA_refVal%3Dhttps%253A%252F%252Fwww.cdc.gov%252Fcoronavirus%252F2019-ncov%252Fcases-in-us.html&chash=&ctitle=Cases%20in%20U.S.%20%7C%20CDC&wn=cdcCharts&wf=/TemplatePackage/contrib/widgets/cdcCharts/&wid=cdcCharts2&mMode=widget&mPage=&mChannel=&host=www.cdc.gov&displayMode=wcms&configUrl=https://timothybest-usds.github.io/d3-examples/us-cases-epi-chart.json&class=mb-3";
```
