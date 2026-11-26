# VAGU-T

VAGU-T is a dataset for understanding anomalous events in videos and locating them in time. It includes examples in which a model requests a closer look at a video segment and uses the returned frames to explain what happened.

The annotations are split across four JSON files, `data-01.json` through `data-04.json`. Read them in numerical order. Each record has an `id` and a `messages` list containing the conversation and references to the video and sampled frames.

To request the original videos, please contact the corresponding author at the email address listed in the paper.
