Apache Spot (Incubating)

Apache Spot is open source software for leveraging insights from flow and packet analysis. It helps enterprises and service providers gain insight on their computing environments through transparency of service delivery and identification of potential security threats or attacks happening among resources operating at cloud scale.

While current threat intelligence tools help, identifying unknown threats and attacks remains a challenge. Apache Spot provides tools to accelerate companies’ ability to expose suspicious connections and previously unseen attacks using flow and packet analysis technologies.


Overview
With the arrival of big data platforms, security organizations can now make data-driven decisions about how they protect their assets. Records of network traffic, captured as network flows, are often stored and analyzed for use in network management. An organization can use this same information to gain insight into what channels corporate information flows through.

By taking into account additional context such as prevalent attacks and key protocols to the organization, the security team can develop a strategy that applies the right amount of per-channel risk mitigation based on the value of the data flowing through it. For an organization, we call this “the port perspective”.

There are two vectors that all organizations should evaluate:

A “wide enough, deep enough” protection strategy that involves both edge prevention and sophisticated detection of unusual behavior

A deep inspection of key protocols using methods that can scale to the volume of data flowing across that channel

While inspecting specific, unique flows of data that may be important for individual organizations, all organizations can realize significant risk reduction from analysis of network flows and DNS (domain name service) replies.

Apache Spot by leveraging strong technology in both Big Data and Scientific Computing disciplines is a solution intended to support this strategy by focusing on “hard security problems” detecting events such as lateral movement, side-channel data escapes, insider issues, or stealthy behavior in general.

Telemetry
Flows.
DNS (pcaps).
Proxy.
Parallel Ingest Framework
Open source decoders.
Load data in Hadoop.
Data transformation.
Machine Learning
Filter billion of events to a few thousands.
Unsupervised learning.
Operational Analytics
Visualization.
Attack heuristics.
Noise filter.
Try the Apache Spot UI with example data:
Running Demo on Docker

Install Docker for your platform
Run the container: docker run -it -p 8889:8889 apachespot/spot-demo
visit http://localhost:8889/files/ui/flow/suspicious.html#date=2016-07-08 in your browser to get started
For the full instructions visit the spot on Docker hub

Getting Started
Apache Spot can be installed by following our installation manual. To get started, check out the installation instructions in the documentation.

Documentation (Developer Guide)
Apache Spot functionality is divided into different modules, go to each module for developer documentation:

spot-ingest
spot-ml
spot-oa
spot-setup
Community Support
Our Central repository for our Apache Spot solution is found here. If you find a bug, have question or something to discuss please contact us:

Create an Issue.
Go to our Slack channel.
Contributing to Apache Spot
Help us improve Apache Spot!

Apache Spot is Apache 2.0 licensed and accepts contributions via GitHub pull requests. Please follow the next steps and join our community.

Contributing to Apache Spot code
Fork the repo of the module that you wish to commit to.
Create a Branch, we use topic branches for our commits.
Push your commit(s) to your repository.
Create a pull request to the original repo in Apache Spot organization.
Commit Guidelines
Bug fixes should be a single commit.
Please be clear with the commit messages about what you are fixing or adding to the code base. If you code is addressing an open issue please add the reference to the issue in the comments with: Fix: Issue's URL.
Merge approval
Apache Spot maintainers use +1 in a comment on the code review to indicate acceptance, at least 3 "+1" from maintainers are required to approve the merge. If you have any question or concern please feel free to add a comment in your pull request or branch and tag any of the maintainers.

Licensing
Apache Spot is licensed under the Apache License, Version 2.0. See LICENSE for the full license text.

spot-nfdump License
Maintainers
@EverLoSa@EverLoSa	@ledalima@ledalima	@rabarona@rabarona	@daortizh@daortizh
@natedogs911@natedogs911	@NathanSegerlind @NathanSegerlind	@moy8011@moy8011
Thanks


Apache Spot is open source software for leveraging insights from flow and packet analysis. It helps enterprises and service providers gain insight on their computing environments through transparency of service delivery and identification of potential security threats or attacks happening among resources operating at cloud scale.

While current threat intelligence tools help, identifying unknown threats and attacks remains a challenge. Apache Spot provides tools to accelerate companies’ ability to expose suspicious connections and previously unseen attacks using flow and packet analysis technologies.


Overview
With the arrival of big data platforms, security organizations can now make data-driven decisions about how they protect their assets. Records of network traffic, captured as network flows, are often stored and analyzed for use in network management. An organization can use this same information to gain insight into what channels corporate information flows through.

By taking into account additional context such as prevalent attacks and key protocols to the organization, the security team can develop a strategy that applies the right amount of per-channel risk mitigation based on the value of the data flowing through it. For an organization, we call this “the port perspective”.

There are two vectors that all organizations should evaluate:

A “wide enough, deep enough” protection strategy that involves both edge prevention and sophisticated detection of unusual behavior

A deep inspection of key protocols using methods that can scale to the volume of data flowing across that channel

While inspecting specific, unique flows of data that may be important for individual organizations, all organizations can realize significant risk reduction from analysis of network flows and DNS (domain name service) replies.

Apache Spot by leveraging strong technology in both Big Data and Scientific Computing disciplines is a solution intended to support this strategy by focusing on “hard security problems” detecting events such as lateral movement, side-channel data escapes, insider issues, or stealthy behavior in general.

Telemetry
Flows.
DNS (pcaps).
Proxy.
Parallel Ingest Framework
Open source decoders.
Load data in Hadoop.
Data transformation.
Machine Learning
Filter billion of events to a few thousands.
Unsupervised learning.
Operational Analytics
Visualization.
Attack heuristics.
Noise filter.
Try the Apache Spot UI with example data:
Running Demo on Docker

Install Docker for your platform
Run the container: docker run -it -p 8889:8889 apachespot/spot-demo
visit http://localhost:8889/files/ui/flow/suspicious.html#date=2016-07-08 in your browser to get started
For the full instructions visit the spot on Docker hub

Getting Started
Apache Spot can be installed by following our installation manual. To get started, check out the installation instructions in the documentation.

Documentation (Developer Guide)
Apache Spot functionality is divided into different modules, go to each module for developer documentation:

spot-ingest
spot-ml
spot-oa
spot-setup
Community Support
Our Central repository for our Apache Spot solution is found here. If you find a bug, have question or something to discuss please contact us:

Create an Issue.
Go to our Slack channel.
Contributing to Apache Spot
Help us improve Apache Spot!

Apache Spot is Apache 2.0 licensed and accepts contributions via GitHub pull requests. Please follow the next steps and join our community.

Contributing to Apache Spot code
Fork the repo of the module that you wish to commit to.
Create a Branch, we use topic branches for our commits.
Push your commit(s) to your repository.
Create a pull request to the original repo in Apache Spot organization.
Commit Guidelines
Bug fixes should be a single commit.
Please be clear with the commit messages about what you are fixing or adding to the code base. If you code is addressing an open issue please add the reference to the issue in the comments with: Fix: Issue's URL.
Merge approval
Apache Spot maintainers use +1 in a comment on the code review to indicate acceptance, at least 3 "+1" from maintainers are required to approve the merge. If you have any question or concern please feel free to add a comment in your pull request or branch and tag any of the maintainers.

Licensing
Apache Spot is licensed under the Apache License, Version 2.0. See LICENSE for the full license text.

spot-nfdump License
Maintainers
@EverLoSahttps@EverLoSa	@ledalima@ledalima	@rabarona@rabarona	@daortizh@daortizh
@natedogs911@natedogs911	@NathanSegerlind @NathanSegerlind	@moy8011@moy8011
Thanks
