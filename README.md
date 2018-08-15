# UiPath Objects into QueueItems
## Inspiration
When scaling up with RPA we started to automate more complex processes - and their data structure also got a bit more complex. We needed to store more complex data structure within the queue items to deal with our requirements.

## What it does
We serialize / deserialize objects so we can store in Orchestrator non primitive types as well.

## How we built it
We built this in UiPath making use of the Newtonsoft library.

## Video demo
[![UiPath Objects into QueueItems](https://img.youtube.com/vi/GB9Kdq3b-AE/0.jpg)](https://www.youtube.com/watch?v=GB9Kdq3b-AE "UiPath Objects into QueueItems")