+++
# Projects widget.
widget = "projects"
active = true
date = "2016-04-20T00:00:00"

title = "文档翻译"
subtitle = "doczh.cn"

# Order that this section will appear in.
weight = 63

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "translation"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

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
  name = "服务网格"
  tag = ".服务网格"

[[filter]]
  name = "Java"
  tag = ".Java"

[[filter]]
  name = "测试"
  tag = ".测试"

+++

