- What is DevOps?
  - It's Not
    - Tools, Job Title
  - IT Cultural Movement
  - Empathy Between Dev and Ops
- The Short History Of DevOps
- DevOps Culture
  - Agile & Lean Applied To Ops
  - Ops Should Not Be A Blocker
    - Codify Your Knowledge
  - Empowering Devs With Ops
- You Can't Install DevOps
  - DevOps is A Culture Obsessed With Tools
  - DevOps Tools
    - Configuration As Code
      - Puppet, Chef, Ansible
    - Metrics Aggregation
      - Logstash/Kibana, Loggly, Graphite
    - Infrastructure As Code
      - Cloudformation, Terraform
    - Continuous Delivery
      - Jenkins
    - Virtualization
      - Vagrant/VirtualBox
      - Containerization/Docker
- Hiring DevOps
  - Don't Hire DevOps
  - Empathetic
    - Developers, Customers
  - Continuous Improvement
    - Data Nut
  - Loves Automation
  - Likes To Write Code
    - Was a developer
  - Meaningful Work > Promotions
- A Reasonably Plausible Scenario Of DevOps Culture In Action At VividCortex
  - Jim files issue in Intercom
  - Jim is missing data in graphs
  - John is on call and is alerted to the problem in HipChat
  - John impersonates Jim and verifies data is really missing
  - John checks to see when last deploy of agents happened
  - In HipChat runs ChatOps command `\last agents`
  - Command shows the last deploy was not corroliated with Jims missing data
  - John posts posts in HipChat and pings @here to see if anyone has deployed anything that might affect Jim's data.
  - Ale says that he recently deployed a change to Kafka consumers around that time frame.
  - John goes to Kibana and filters the log aggragation to logs from the Kafka consumer services.
  - John starts a +Google hangout with Ale and reviews the logs together.
  - Together they find an error in the log that is an error that he did not account for happening in producton.
  - They pair program and quickly resolve the bug in the code.
  - Ale commits his code to GitHub and merges it into masters.
  - Ale push the change to production with ChatOps command `/release agents` while John updates the customer, letting them know the issue should be fixed in a few mins.
  - Thing notifies them that the deployment to production was successful.
  - They both check the graphs in Jim's account and see that the issue is fixed.
  - John notifies Jim that their graphs are fixed.
  - Total time to resolution 15mins.
