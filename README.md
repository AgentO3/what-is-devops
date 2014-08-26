- What is DevOps?
  - A Job Title?
    - A recruiter would like you to think that.
  - A Tool?
    - A vendor would like you to think that.
  - A Team?
    - A corporation would like you to think that.
  - It's An IT Cultural Movement
  - Empathy Between Dev and Ops
  - & Beyond
    - The Customer
    - Sales & Business
  - How?
    - Sharing, Communicating, Collaborating
  - Why?
    - To Be A Highly Effective IT Organization
    - Respond Quickly To Customers Needs
    - Respond Quickly To Buinsess Needs
    - Save Marrages
      - # of Servers != Sysadmins
    - Ops Is Not The Fire Department
      - Capacity planning
      - Problem prevention

- Intro
  - Developer doing ops @VividCortex
  - Helping Make Awesome
  - Home Brewing
  - Specal Thanks
    - Debrah & Neon Guild

- DevOps Culture
  - Agile & Lean As Applied To Ops
  - Ops Should Not The Blocker
    - Codify Your Knowledge
    - Remove The Humans
      - Don't worry robots won't replace you
  - Ops For Everyone
    - Empower Others
  - Building Bridges Not Silos
  - Mutual Interest in Learning & Growing

- That's Nothing New!
  - Your right!, & It's ok
  - "It's all been done before." - The Barenaked Ladies
  - IT & Programming is as driven by trend as the fashion industry is.

- The Short History Of DevOps

- You Can't Install DevOps
  - DevOps is A Culture With A Tool Obession
  - Tools of The Trade
    - Configuration As Code
      - Puppet, Chef, Ansible
    - Metrics Aggregation
      - Logstash/Kibana, Loggly, VividCortex (who put that there?)
    - Infrastructure As Code
      - Cloudformation, Terraform
    - Continuous Delivery
      - Jenkins
    - Virtualization
      - Vagrant/VirtualBox
      - Containerization/Docker
      - AWS, Digial Ocean, Linode
    - PaaS (Platform as a Service)
      - Heroku, Google App Engine, Deis

- Enacting Cultural Change
  - Aligning Incentives Across The Organization
    - Don't reward on ticket time
  - Start Small
    - Automate a simple task
    - Apply to dev environment first
  - Measure Results
    - Release in a (day, week, month)
    - Time till problem diagnoses
    - Time till problem resolution
  - Learn From Mistakes
  - Be The Spokesperson
    - Cite real world examples
  - Build A Community
    - Start a
      - Mailing list
      - Book club
      - Excuse to drink beer
    
- Hiring DevOps
  - Don't Worry About DevOps Titles
  - Effective Communicator
    - Empathetic
      - Developers, Customers, Sales
  - Continuous Improvement
    - Data Nut
    - Loves learning
  - History of Automation
  - Likes To Write Code
    - A developer who was a sysadmin
    - A sysadmin who was a developer
  - Values Meaningful Work

- A Reasonably Plausible Scenario Of DevOps In Action At VividCortex
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

- The End

- Excited now? Want more?
  - Join DevOpsCV (I'm the organizer)
  - First meetup Oct 8th
    - Vince Rivellino - DevOps @RoomKey
  - Nathen Harvey [Technical Community Manager at Chef] - TBA
  - You! - TBA
