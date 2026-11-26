# VAGU-T-DATASAT
`data.json` contains the VAGU-T dataset for video anomaly understanding and temporal grounding.

VAGU-T is a dataset for understanding anomalous events in videos and locating them in time. It includes examples in which a model requests a closer look at a video segment and uses the returned frames to explain what happened.

The annotations are provided in `data.json`. Each record has an `id` and a `messages` list containing the conversation and references to the video and sampled frames.

To request the original videos, please contact the corresponding author at the email address listed in the paper.
