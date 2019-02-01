+++
# Opportunities widget.
# This widget displays all opportunities from `content/opportunities/`.
widget = "opportunities"
active = true
date = "2019-01-31T00:00:00"

title = "Opportunities"
subtitle = ""

# Order that this section will appear in.
weight = 60

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 0

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"
  
[[filter]]
  name = "Undergraduate"
  tag = ".undergraduate"

[[filter]]
  name = "Graduate"
  tag = ".graduate"
  
[[filter]]
  name = "Postdoc"
  tag = ".postdoc"

+++
