---
title: 'Modelling the Effects of Vegetation on Urban Air Quality Based on Multiple Environmental Data Sources'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Michael Smith
  - Chengzhi Peng 

# Author notes (optional)
author_notes:
  - "First author"
  - "Second author"
  - "Co-responding author"

date: '2023-12-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Conference paper']

# Publication name and optional abbreviated publication name.
publication: 'Sustainable Cities: Pioneering Approaches to Green Urbanism and Climate Resilience'
#publication_short: In *ICW*

abstract: Air pollution is one of the biggest threats to public health worldwide. Vegetation has been shown to have some impact on urban air quality. Quantifying the effects of vegetation on air pollutant levels in urban areas is challenging due to the complex configurations of real cities. Such knowledge and methods are essential to urban vegetation planning and design that aims to improve urban air quality. Using high-resolution computational fluid dynamics (CFD) simulation to control a large set of variables is one of the existing methods to quantify vegetation effects. However, CFD simulation is often limited by the computing resources available for detailed modelling of the entire sphere of a real urban environment. This paper presents an alternative modelling framework for assessing vegetation effects on urban air quality based on the real urban environment data, collected from multiple data sources including satellite and ground-based sensing and imaging. First, based on the Multiangle Imaging Spectroradiometer (MISR) satellite aerosol optical depth (AOD) datasets and air pollutants datasets supplied by ground monitoring stations, a Random Forest based method is applied to generate distribution of PM2.5 concentrations at a high spatial resolution covering a large urban area. Then, an urban grid based clustering of non-vegetation related urban form (e.g., road length) is performed. Next, among the urban clusters, a deep learning image segmentation method is applied to a large set of street view images to capture the vegetation morphology characteristics for tracking the relationship with PM2.5 concentrations. The modelling framework was first tested with Harbin, a major city in northeast China suffering poor air quality. This research aims to provide a more effective and robust approach to quantifying the impact of urban vegetation on air quality in real urban environments.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Green Urbanism (GU) - 7th edition

# Display this page in the Featured widget?
featured: true     #这个是控制是否显示在精选出版物中的，true就是展示，false就是不展示

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: ''
url_code: 'https://github.com/11Mengxue/Pilot-Study'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: 'Top'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}





