---
title: 'Robust Phase-based BLE Localization with a Single Multi-Antenna Receiver and Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Georgios Andreadis
  - Panos N. Alevizos
  - Aggelos Bletsas

date: '2025-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *15th International Conference on Indoor Positioning and Indoor Navigation 2025*
publication_short: In *IPIN 2025*

abstract: This study presents a neural network approach for static Bluetooth Low Energy (BLE) localization, utilizing phase measurements and carrier frequency per data packet, captured from multi-antenna receiver(s). Traditional phase-based deterministic techniques fail to accurately estimate the position of a tag with a \emph{single} multi-antenna receiver with closely spaced antennas. Our approach addresses this limitation by leveraging neural networks that capture the non-linear distribution of the carrier phase offset (CPO) and filter out noise, enabling robust localization with just one multi-antenna receiver. Among the two neural network architectures tested, the Long Short-Term Memory (LSTM) model demonstrated notable resilience against phase noise and achieved higher accuracy during high-rate tag transmissions compared to the FeedForward (FF) model. Both architectures were trained on simulated or real data, and subsequently tested on real data, with both models outperforming deterministic techniques in scenarios where the latter either excelled or failed to estimate the tag's position.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: 'https://github.com/geoandrs/ble-dataset'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
slides: ""
---