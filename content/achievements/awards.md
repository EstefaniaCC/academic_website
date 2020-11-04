+++
# A Projects section created with the Portfolio widget.
widget = "accomplishments"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Awards"
subtitle = ""

# Date format
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["25px", "0", "20px", "0"]

# Accomplishments.
#   Add/remove as many `[[item]]` blocks below as you like.
#   `title`, `organization` and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

plugins_css = ["custom"]


[[item]]
  organization = "IEEE INFOCOM"
  organization_url = "https://infocom2019.ieee-infocom.org/"
  title = "Best Demo Paper Award"
  url = "https://www.youtube.com/watch?v=ZK08eYVMRzg"
  certificate_url = "./../publication/infocom-19/certificate.pdf"
  date_start = "2019-04-30"
  date_end = ""
  description = """
  Paper title: Addressing Bitrate and Latency Requirements for Connected Vehicles.
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZK08eYVMRzg" frameborder="0" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  """

  [[item]]
  organization = "IEEE Netsoft"
  organization_url = "https://netsoft2020.ieee-netsoft.org/"
  title = "Best Demo Paper Award"
  certificate_url = "./../publication/netsoft-2020-demo/certificate.pdf"
  date_start = "2020-07-02"
  url = "https://www.youtube.com/watch?v=F8-Vlh4J_hc"
  date_end = ""
  description = """
  Paper title: Enabling Autonomous and Connected Vehicles at the 5G Network Edge.
  <iframe width="560" height="315" src="https://www.youtube.com/watch?v=F8-Vlh4J_hc" frameborder="0" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
"""

+++
