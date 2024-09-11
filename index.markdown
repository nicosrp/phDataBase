---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Plasticheal Analysis</h1>

<iframe src="OUTPUT/00_Summary/project_summary.html" width="100%" height="400" style="border:none; margin-bottom: 30px;"></iframe>

<iframe src="OUTPUT/00_Summary/project_duration_plot.html" width="100%" height="400" style="border:none; margin-bottom: 30px;"></iframe>


<h2>1 Publications</h2>
This plot shows the publication distribution based on the publishing date.
<iframe src="OUTPUT/01_Publications/Publications_per_Year.html" width="100%" height="400" style="border:none; margin-bottom: 30px;"></iframe>

The following two scatter-plots show how many days after the project start/end date a publication has been published plotted against the total publication amount of the project.
<iframe src="OUTPUT/01_Publications/scatter_plot_start_date.html" width="100%" height="400" style="border:none; margin-bottom: 20px;"></iframe>
<iframe src="OUTPUT/01_Publications/scatter_plot_end_date.html" width="100%" height="400" style="border:none; margin-bottom: 30px;"></iframe>

In this scatterplot the relation between publication output and assigned knowledgegaps is visualized.
<iframe src="OUTPUT/01_Publications/publications_vs_knowledge_gaps_plot_with_curve.html" width="100%" height="400" style="border:none; margin-bottom: 30px;"></iframe>

<h2>2 Partners, Coordinating Organizations and Respective Countries</h2>
The country-count for coordinating a plastic research project is visualized below.
<iframe src="OUTPUT/02_Organizations_And_Countries/Coordinating_Country_Counts.html" width="100%" height="500" style="border:none; margin-bottom: 20px;"></iframe>

In the following graph the involvement of organizations grouped by the respective country is plotted.
<iframe src="OUTPUT/02_Organizations_And_Countries/bar_chart_company_involvement.html" width="100%" height="400" style="border:none; margin-bottom: 20px;"></iframe>

The world map visualizes the previous involvement values.
<iframe src="OUTPUT/02_Organizations_And_Countries/world_map_company_involvement.html" width="100%" height="600" style="border:none; margin-bottom: 30px;"></iframe>

<h2>3 Categories and Plastic Types</h2>
The following plot displays the amount of projects associated with a specific plastic type.
<iframe src="OUTPUT/03_Categories/plastic_type_bar_plot.html" width="100%" height="500" style="border:none; margin-bottom: 30px;"></iframe>

In this network graph the occurence of single categories, as well as ther interconnectivity is visualized.
<iframe src="OUTPUT/03_Categories/network_graph_of_plastic_projects_categories.html" width="100%" height="500" style="border:none; margin-bottom: 30px;"></iframe>

<h2>4 Knowledge Gaps</h2>
In the following interactive Graph the knowledge gaps for all included projects are plotted. Each knowledge gap is plotted based on the project duration, so if a project runs e.g. for 2 years and starts in the second half of year x, it gets assigned a contribution of 0.5 for this year, 1 for the next year and 0.5 to the last year.
<iframe src="OUTPUT/04_KnowledgeGaps/knowledge_gaps_plot.html" width="100%" height="500" style="border:none; margin-bottom: 20px;"></iframe>

This next plot shows the share for each grouped knowedge gap over the years.
<iframe src="OUTPUT/04_KnowledgeGaps/knowledge_gaps_share.html" width="100%" height="500" style="border:none; margin-bottom: 20px;"></iframe>

<iframe src="OUTPUT/04_KnowledgeGaps/knowledge_gaps_with_total_points_secondary_yaxis.html" width="100%" height="500" style="border:none; margin-bottom: 20px;"></iframe>