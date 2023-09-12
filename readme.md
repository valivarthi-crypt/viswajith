# Devops Fundamentals

---

## # Core Values of Devops

1. Culture
2. Automation
3. Measure
4. Sharing

---

## # Three Principles Of Devops

- System Thinking (Concept to Cash)
- Amplifying Feedback Loops (ipofi) (Short Effective Feedback Loops)
- Continuous Experimentation and Continuous Learning (CE&L)

---

## # Devops Methodology

- People -> Process -> Tools
- Continuous Delivery (Develop->Test->Deploy -> Release(on small batches))
- Lean (Small Batches -> Work in progress limits -> Feedback Loops -> Visualization)
- Change Control (Visual Ops,CI)
- Infrastructure As A Code (Make System as Programmable)

---

## # Devops Pratices

- Incidents Command System
- Devolopers on Call
- Staus Pages (Communication)
- Blameless Postmortems
- Embedded Teams ( Add Op+Dev together )
- Cloud (IaaC)
- Andon Codes
- Dependency Injection
- Blue Green Deployments
- Chaos Monkey

---

## # Tools

- Only Ui No
- Trust + Verify
- Metrics for Feedback
- Check if well Behaved

---

## # Wall of confusion

- Develop - Operations

---

## # Communication (Blameless postmortem,Transperant Uptime)

- Prevent the similar outage,RC Analysis,Detection of Failures in Future(BP)
- a.Admit Failure b.Sound like Human c.Communication Channel d.Be Authentic

---

## # Collab

- Social Skills
- Some-one else job is easy
- Diff Skillsets together
- Optimal Team Size
- Chat Ops (Slack,Add in Push Notification) (Kuba)

---

## #Kaizen

- Plan => Do => Check => Act
- When issue just go see issue
- Not enough Time
- Fish Bone Diagram
- Its never human Its Process

---

## #Agile

- Iterative
- Frequent intervable delivarables
- No Scope of Op

---

## #Lean

- Activities that have Value,Othr - WAste
- Waste and Compli Waste
- Putting efforts on non requiremets

---

## ITIL SDLC

- Incident,Catalouge,Knowledge Management
- Waterfall,

---

## IaaC

- AWS CloudFormation
- Virtualization
- Automation
- Config Management
  - Provisioning
  - Deployment
  - Orchestration
- Functional(Defining Desired State)
- Ex : Puppet,Chef
- Image (Incremnted Form)
- Golden Image Model
- Container (Just Enough Os)
- WAR,DB -> Image
- Immutable infra and Devlivery
- Docker repo as other Repo
- Zookeper
- Tool Chain
  - Cloud Formation
  - Azure Resource Manager
  - Hashicrop Terraform
  - Ubuntu JUJU
  - Chef,Pupper,CF Engine,Ansible

---

## #Devops Foundations

- CD (Built on every Code Commit)
- CI (Integration And Acceptance Test on SC Check in)
- CDeployment (Deployed automatically to Prod).

---

## #Ci

Code -=>
Build =->
Unit Tests=-> Code Validation-=>Packaging=->Artifact

- Builds should take less time
- Commit Small Bits
- Dont leave build broken
- Trunk based development flow
- build should log and artifact

---

## #Cd

- Built once and immutable
- Auditability
