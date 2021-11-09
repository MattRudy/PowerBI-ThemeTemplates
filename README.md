# Power BI Theme Templates
[![Validate JSONs](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-validate-json.yml/badge.svg?branch=master)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-validate-json.yml)
[![Monitor Document Links](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-monitor-docs.yml/badge.svg?branch=master)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-monitor-docs.yml)
### Snippets for assembling Power BI Themes

#### [Get them here](https://github.com/mattrudy/PowerBI-ThemeTemplates) or view the visual list below

- Are you working with Themes in Power BI but confused about the visual formatting options (visualStyles)?  
- Have you struggled while trying to make sense of the [Power BI report themes documentation](https://docs.microsoft.com/en-us/power-bi/desktop-report-themes)?  
- Do you like JSON?  
- Do you like sample code?
- Do you like *other people* doing most of the labor for you?

If you answered "Yes" to any of the questions above, this repo is for *YOU*!

![Sample Power BI Shape Template](https://github.com/MattRudy/PowerBI-ThemeTemplates/blob/6f22b34e1fb13f5c9f7a49d5017bd6397268b0e4/ShapeTemplate.PNG "Sample Shape Template")

Changing colors in Power BI themes is fairly straightforward. For formatting, the wildcard(*) to make universal changes is convenient. If you want to go deeper into individual visual properties, however, it can quickly get confusing. With these sample templates, explore the individual properties available to *each* visual (as well as shapes and images). Combine the per-visual templates as needed, alter the values to correspond to your own needs, and build your own Power BI theme.

The purpose of this repository is to provide detail-level reference for each native visual in its own separate file. Look at the format options for a visual in Power BI Desktop and compare to the JSON options side by side. Copy and paste what you need from each visual's JSON to assemble a master Theme file.

Please note that the values in these sample files will appear *ugly*. Many values are not Power BI's defaults. As soon as something worked, I moved on to the next property. Please modify or remove properties in your own theme file to be what you desire.

## Global Level Template 🌎
Adjust titles, backgrounds, report page tooltips, wallpaper, and more for some or all visuals on a page or all pages.

- [Global Level](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/GlobalLevelTemplate.json)

## Available Visuals 📊

- [Area Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Area.json)
- [Azure Map](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/AzureMap.json)  
- [Button](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Button.json)
- [Card](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Card.json)
- [Clustered Bar Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/ClusteredBar.json)
- [Clustered Column Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/ClusteredColumn.json)
- [Decomposition Tree](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/DecompositionTree.json)
- [Donut Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Donut.json)
- [Esri ArcGIS Map](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/EsriArcGisMap.json)
- [Filled Map](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/FilledMap.json)
- [Funnel Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Funnel.json)
- [Gauge](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Gauge.json)
- [Hundred Percent Stacked Bar Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/HundredPercentStackedBar.json)
- [Hundred Percent Stacked Column Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/HundredPercentStackedColumn.json)
- [Image](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Image.json)
- [Key Influencers](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/KeyInfluencers.json) 
- [KPI](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/KPI.json)  
- [Line Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Line.json)
- [Line and Clustered Column Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/LineClusteredColumnCombo.json)
- [Line and Stacked Column Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/LineStackedColumnCombo.json)
- [Map](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Map.json)  
- [Matrix](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Matrix.json)
- [Multi-row Card](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/MultirowCard.json)
- [Pie Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Pie.json)
- [Q&A](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/QnA.json)  
- [Ribbon Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Ribbon.json)
- [Scatter Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/ScatterChart.json)
- [Shape](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Shape.json)
- [Shape Map](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/ShapeMap.json)
- [Slicer](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Slicer.json)
- [Stacked Area Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/StackedArea.json)
- [Stacked Bar Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/StackedBar.json)
- [Stacked Column Chart](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/StackedColumn.json)
- [Table](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Table.json)
- [Textbox](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Textbox.json)
- [Treemap](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Treemap.json)
- [Waterfall](https://github.com/mattrudy/PowerBI-ThemeTemplates/blob/master/Waterfall.json)

## How do you find theme properties? 🔍
It's possible to explore a Power BI Desktop file on your local computer to see the properties that are set, even if they aren't documented by Microsoft yet.
Check out [this great article](https://nolock.medium.com/how-to-discover-undocumented-theme-settings-in-power-bi-desktop-dcbe264351c8) for a guide on how to extract these properties.

## About this repository: ❔
For questions not answered here, you can [View the FAQ].  
If you have a question or find an issue, you can [Create a new issue].

### Areas considered "In-Scope" for this repository: ✅
1. one global-level theme template to help understand global-level settings.
1. one template per available visual, covering all default Power BI visuals as well as many custom visuals, to help understand visual-level settings.

### Areas considered "Out-of-Scope" for this repository: 🚫
1. pre-built color themes (You can find these in [Microsoft's official themes gallery])
1. Theme samples to solve specific problems such as adding outlines or hiding visual headers on every visual (You can find these samples in [mattrudy/PowerBIThemeSolutions])
1. JSON file generator for anyone who doesn't want to write their own JSON file (You can use the [JSON Generator from PowerBI.Tips])

## CI/CD and Automation 🤖
There are several helpful levels of automation that help this project stay valid over time.

When someone new adds an Issue or Pull Request to the project:
| Link to Action | Description |
|:---:|:---:|
|[![Housekeeping - Welcome New Contributors](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/housekeeping-welcome-contributors.yml/badge.svg)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/housekeeping-welcome-contributors.yml)| They are greeted, thanked, and pointed to helpful links |

When a template or file is added/edited:
| Link to Action | Description |
|:---:|:---:|
|[![Validate Docs](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-validate-docs.yml/badge.svg)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-validate-docs.yml)| Any hyperlinks are tested to make sure they are valid |
|[![Validate JSONs](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-validate-json.yml/badge.svg)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-validate-json.yml)| Any JSON files are scanned to make sure they are valid |

Every 12 hours:
| Link to Action | Description |
|:---:|:---:|
|[![Monitor RSS](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/rss-issues.yml/badge.svg)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/rss-issues.yml)| Microsoft's blog feed is scanned to check for a new Power BI Monthly Update, and if there is an issue is created to check for new visuals or properties. |

Once a week:
| Link to Action | Description |
|:---:|:---:|
|[![Monitor Docs](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-monitor-docs.yml/badge.svg)](https://github.com/MattRudy/PowerBI-ThemeTemplates/actions/workflows/tests-monitor-docs.yml)| All hyperlinks on all pages are checked to make sure no links have broken |

## Contributors 👩‍🔬
This project is only possible thanks to the contributions of the community - below is a small set of the people who have made this possible! We're also very thankful to everyone who's written blog posts with useful samples, created issues, or suggested enhancements to this repository, or helped spread the word about this resource!
Want to see your name in this list? Check out the 'How Can I Contribute' section in the [Contribution Guidelines] to get started!

<a href="https://github.com/mattrudy/powerbi-themetemplates/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mattrudy/powerbi-themetemplates" />
</a>

_Contribution list made with [contrib.rocks](https://contrib.rocks)._

[View the FAQ]: https://github.com/MattRudy/PowerBI-ThemeTemplates/blob/master/FAQ.md
[Contribution Guidelines]: https://github.com/MattRudy/PowerBI-ThemeTemplates/blob/master/CONTRIBUTING.md#how-can-i-contribute
[Create a new issue]: https://github.com/MattRudy/PowerBI-ThemeTemplates/issues/new
[Microsoft's official themes gallery]: https://community.powerbi.com/t5/Themes-Gallery/bd-p/ThemesGallery
[mattrudy/PowerBIThemeSolutions]: https://github.com/MattRudy/PowerBIThemeSolutions
[JSON Generator from PowerBI.Tips]: https://themes.powerbi.tips/properties
