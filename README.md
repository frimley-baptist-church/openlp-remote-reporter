# openlp-remote-reporter

### What's this then?

It's a service that runs on a Raspberry Pi who's purpose is to connect an [OpenLP](https://openlp.org/) system and retrieve, store and analyse the service order live at the moment of checking.

The service can be configured to retrieve this data at specific times. In our case, it's the following:

* Every Sunday morning at 10:45. This ensures we collect data about all the songs used in that particular service.
* Every Sunday evening at 18:30. Ensures we collect data for each evening service.

### Why do this?

These days we need to report song usage to the CCLI. It's an ardious task to collate this manually. Running a service like this means we don't need to remind people to fill in paper reports or remember to email the office each week.
