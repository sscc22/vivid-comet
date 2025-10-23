---
title: "유니티 힌지 조인트 사용시 주의점"
authors:
- admin

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: target5_hinge.GetComponent<HingeJoint>().axis = target5_hinge.GetComponent<HingeJoint>().axis;

  위 코드를 보면 이상하다

  컴포넌트를 가져와서 그대로 컴포넌트에 대입했다

  아무런 일도 하지 않을 것 같지만 이걸 해줘야 바보같은 유니티 힌지가 자신의 각도를 인식한다 안하면 그냥 지 맘대로 정해버린다.

# Summary. An optional shortened abstract.
summary: 위 코드를 보면 이상하다 컴포넌트를 가져와서...

tags:
- 유니티활용

featured: true

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
- type: preprint
  provider: arxiv
  id: 1512.04133v1
- type: code
  url: https://github.com/HugoBlox/hugo-blox-builder
- type: slides
  url: https://www.slideshare.net/
- type: dataset
  url: "#"
- type: poster
  url: "#"
- type: source
  url: "#"
- type: video
  url: https://youtube.com
- type: custom
  label: Custom Link
  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
