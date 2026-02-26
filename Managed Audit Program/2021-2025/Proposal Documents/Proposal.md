# Securing Critical Projects Managed Audit Program Initiative - Proposal

## Executive Summary

The Open Source Technology Improvement Fund (OSTIF) is striving to create a Managed Audit Program to secure critical projects in the open source ecosystem.  OSTIF draws on 10+ years of experience managing audits for open source projects, an international network of trust and rapport, and comprehensive support that results in improved security tooling, closed classes of bugs, and published research. The Program serves the following objectives: 

1) Creating and executing on a solution focused on going to the source of the problem and incrementally solving it. 
2) Demonstrating strong collaboration and action taken toward fulfilling the mission of securing the open source ecosystem. 
3) Recognizing the organizations funding this work to increase awareness and investment in this space. 

This document makes the case that these projects are highly relevant, that the work is valuable, and that the work has a high chance of success; resulting in a significant security boost to critical projects. 

## Objectives

1) Select Relevant Projects for Independent Review
* Data from OpenSSFs Criticality Score Project
* Data from the Linux Foundation + Harvard LISH Project - Census II
* Data from the recent Washington University Underproduction paper.
* Input directly from our advisory council
* Considering the dependency trees of leading projects
* Eliminating projects that already have help
* Eliminating projects that don’t significantly impact security

2) Scope Auditing Appropriately
* Consider only areas of code that impact security
* Do not repeat the works of others
* Time audits to cover major releases and updates
* Break large projects into smaller parts to avoid fatigue

3) Secure Funding
* Secure a grant / donation from industry partners to fund program.

4) Select the Best Audit Teams
* Competitive bidding system to keep costs down and quality up.
* Only consider highly qualified individuals with the skills to review the specific project in the proposal
* Only consider teams that are willing to work in public view

5) Conduct the Audits
* Work with the lead developers to set up a secure channel for reporting serious bugs
* Issues are reported as they are found, not in bulk
* Fixes are suggested by the security team if appropriate

6) Squash All of the Bugs
* Wait for security fixes to be applied before publishing (Maximum 90 days unless there are special circumstances)
* Security team and lead developers work together to find complete solutions

7) Publish All Results
* Results published on OpenSSF Security Reviews and OSTIF website in full, along with a synopsis
* All severe bugs are reported as CVEs to the relevant CNAs
The Project Selection Process

OSTIF has been working with Industry Partners, the Greater Open-Source Community, and the Open Source Security Foundation’s (OpenSSF) Securing Critical Projects working group to identify critical infrastructure that is in need of security review, discuss methodology to improve the existing code of these projects, and improve the long-term security posture of the teams maintaining the code. 

OSTIF’s decision-making is both data and experience driven. The organization draws insight from its advisory council and reviews published work that highlights the need and criticality of a plurality of open source projects. There are an enormous number of projects that need increased security review, but with limited resources and time, focus has to be narrowed to the projects that will have far-reaching impacts. 

OSTIF draws from five sources:

1) Data from the **Linux Foundation** and the **Laboratory for Innovation Science at Harvard** 
2) Google and OpenSSF’s **Criticality Score project**
3) Data from the recent research paper **Underproduction: An Approach for Measuring Risk in Open Source Software**
4) **Dependency trees** from leading high profile projects.
5) **The advisory council** - A diverse group of members propose projects that likely have a high impact that may be overlooked by other metrics. This includes projects that may become industry standards in the future, or special projects that do not fall into easy categorization.

## The Initial Projects
This list is not exhaustive, nor is it immutable. If any of these projects are already receiving outside security help, an endless list of projects are ready to take their place. Based on thorough analysis of project CI pipelines and security practices, as well as the tools and resources listed above, OSTIF proposes* that the following twenty-five projects are to be audited:

*It is acknowledged that it would be almost impossible to generate a list that every single interested party agreed on. OSTIF made a good faith, fact-based effort based on the provided information. Information was prioritized by project need and relevance to security and the open source ecosystem.  Certain projects were excluded or downgraded due to resource availability and current work being done.


|   |        Project        |                    Short Description                   |                   Site                   |                   Github / Gitlab                  |           Supporting Org           |       Monetization       |      Languages      |
|:-:|:---------------------:|:------------------------------------------------------:|:----------------------------------------:|:--------------------------------------------------:|:----------------------------------:|:------------------------:|:-------------------:|
|   |        Electron       |             Cross-platform apps development            |        https://www.electronjs.org/       |        https://github.com/electron/electron        |          OpenJS Foundation         |         Donation         |   C++, TypeScript   |
|   |          Git          |                     Version Control                    |           https://git-scm.com/           |         https://github.com/git/git (mirror)        |    Software Freedom Conservancy    |         Donation         |       C, Shell      |
|   |        systemd        |               System and Service Manager               |            https://systemd.io/           |         https://github.com/systemd/systemd         |      None (Red Hat Developers)     |           None           |          C          |
|   |         rails         |        Database backed web application framework       |         https://rubyonrails.org/         |           https://github.com/rails/rails           |         Basecamp / Shopify         |             ?            |         Ruby        |
|   |         lodash        |                   JS utility library                   |            https://lodash.com/           |          https://github.com/lodash/lodash          |                None                |           None           |          JS         |
|   |      jackson-core     | JSON for Java, Streaming API + extra shared components |                   None                   |      https://github.com/FasterXML/jackson-core     |                None                |    Donation (TideLift)   |         Java        |
|   |    jackson-databind   |           JSON for Java, Data binding package          |                   None                   |    https://github.com/FasterXML/jackson-databind   |                None                |    Donation (TideLift)   |         Java        |
|   |  httpcomponents-core  |        Core components of Apache httpcomponents        |                   None                   |   https://github.com/apache/httpcomponents-client  |          Apache Foundation         |         Donation         |         Java        |
|   | httpcomponents-client |       Client components of Apache httpcomponents       |                   None                   |    https://github.com/apache/httpcomponents-core   |          Apache Foundation         |         Donation         |         Java        |
|   |      php symfony      |                PHP application framework               |           https://symfony.com/           |         https://github.com/symfony/symfony         |             Sensio Labs            |                          |         PHP         |
|   |        laravel        |                  PHP Web App Framework                 |           https://laravel.com/           |         https://github.com/laravel/laravel         |                None                |         Donation         |      PHP, Blade     |
|   |         slf4j         |                 Logging Facade for Java                |           http://www.slf4j.org/          |           https://github.com/qos-ch/slf4j          |                None                | Enterprise Support Model |      Java, HTML     |
|   |      logback-core     |               Logging framework for Java               |          http://logback.qos.ch/          |          https://github.com/qos-ch/logback         |                None                | Enterprise Support Model |      Java, HTML     |
|   |         drupal        |                Content Management System               |        https://www.drupal.org/home       |      https://git.drupalcode.org/project/drupal     |             Drupal.org             |      Referral / None     |       PHP, JS       |
|   |         joomla        |                Content Management System               |          https://www.joomla.org/         |        https://github.com/joomla/joomla-cms        |          Joomla Foundation         |    Donation / Referral   |       PHP, JS       |
|   |  gnome-power-manager  |   Power management services for various Linux distros  |             https://gnome.org            | https://gitlab.gnome.org/GNOME/gnome-power-manager |           GNOME Project ?          |           None           |        C, C++       |
|   |        reprepro       |                  Package Manager Repo                  |                   None                   |      https://salsa.debian.org/brlink/reprepro      |                None                |           None           |          C          |
|   |          ceph         |         object, block and file storage platform        |             https://ceph.io/             |            https://github.com/ceph/ceph            | Linux Foundation (ceph foundation) |        Membership        |     C++, Python     |
|   |      react native     |          Framework for Mobile App Development          |         https://reactnative.dev/         |      https://github.com/facebook/react-native      |              Facebook              |     Corporate Support    | JS, Java, C++, More |
|   |    salt (saltstack)   |                 IT Automation Platform                 |  https://docs.saltproject.io/en/latest/  |          https://github.com/saltstack/salt         |               VMWare               |     Corporate Support    |        Python       |
|   |         gatsby        |                  Fast React Framework                  |         https://www.gatsbyjs.com/        |         https://github.com/gatsbyjs/gatsby         |            gatsbyjs.com            |           SAAS           |    JS, TypeScript   |
|   |        angular        |                  Application Framework                 |            https://angular.io/           |         https://github.com/angular/angular         |               Google               |     Corporate Support    |    TypeScript, JS   |
|   |        ansible        |                 IT Automation Platform                 |         https://www.ansible.com/         |         https://github.com/ansible/ansible         |               Red Hat              |     Corporate Support    |  Python, Powershell |
|   |         guava         |                     Java Framework                     | https://opensource.google/projects/guava |           https://github.com/google/guava          |               Google               |     Corporate Support    |         Java        |
## Critical Advantages 

Very few organizations are equipped with the network and expertise to coordinate security work at this level. Only OSTIF directly interfaces with open source projects, works with the projects’ leaders to identify opportunities, walks the project through security auditing and suggests remediation of flaws that are found. What separates us is the commitment to operate with total operational transparency: releasing all tools, research, and development for free with open source licenses. This fosters a community of trust and cooperation that is not present in other initiatives.

## Results and Lasting Impact

* **Security fixes. A lot of them**. Each OSTIF audit finds and closes multiple security issues, resulting in an immediate security improvement.

* **Security bugs that never happen**. The review process focuses on closing classes of bugs for projects. The primary goal of security audits is not to just find bugs, but to locate security problems and show the developers how the problem arose, and the tooling, development guidelines, and procedures that can prevent similar problems from reoccurring. In targeting core infrastructure projects and not only closing bugs but improving development processes, we gain a crucial long-term security benefit to the entire open source community.
* **Public documentation**. All of OSTIFs audits are published for public consumption and accountability. This gives organizations the opportunity to review the security audits and make implementation decisions based on those results. 

## PR & Media Plan

Organizations that support the program get significant coverage and recognition for funding the work. Each audit in the program produces a public report that acknowledges the sponsors and can be widely distributed and promoted. Furthermore, a blog post/press release is created for each review that includes:
1) Recognition of Sponsors
2) Testimonials from Project Maintainers and/or Security Teams
3) Summary of findings, remediations, and impact

Furthermore, all reviews will be published publicly, allowing everyone from the open source community and beyond to see results of work being done and the organization(s) that made the work possible. 

## Key Benefits to Organizations

**Tax benefits to donors**. OSTIF is an IRS 501(c)3 organization. Donations are tax deductible.

**Neutrality**. OSTIF operates as a neutral security advocate. This prevents situations where an organization is selecting their own auditors for security review, effectively reviewing themselves.

**Comprehensive assistance**. OSTIF has developed a model that considers the edge cases of open source, and can assist organizations that have no central authority, no corporate or business entity, and no bank account. Projects are walked through the entire process of scoping, auditor selection and if needed direct security assistance with patching.

**Credit to backers**. OSTIF takes care to make sure that all supporting organizations get recognition for their contributions. This means that the company logo appears on the website, the synopsis page for each sponsored project, the front page of the research documents themselves, and are mentioned on social media when projects are announced and completed.

## Supporting Evidence

For the past five years, OSTIF has been working with industry partners under it’s pilot program to complete a total of 16 projects with a total of $780,000 in funding. During this time, OSTIF organized a community of dozens of cybersecurity professionals and researchers from around the world to build a community of donors, advisors, and security resources that has prepared us to scale up to a larger, more adaptive and more comprehensive organization.

Under this pilot program OSTIF has located **twenty-six severe bugs** (bugs that would have a CVSS score of “high” or “critical” rating.) This is notable because the pilot program has been chronically underfunded and both project scopes and timelines had to be narrowed to meet budget demands. Additionally, not all projects produce bugs that are reportable to CNAs, such as audits of alpha software or reviews that cover policies and practices such as our work with the Linux Kernel team.

Below are two specific success stories of open source projects that saw marked improvement due to the resources provided by OSTIF.

**OpenSSL** is among the top security libraries in the world with billions of installs, and is utilized billions of times per day. In 2016, the HeartBleed vulnerability was discovered, endangering critical systems around the world. In the wake of this incident, many industry partners came together to improve the funding and security posture of OpenSSL in order to help the project minimize the risk of another major security incident.

In 2018, after two years of increased funding and development from the Core Infrastructure Initiative, OpenSSL had thousands of hours of increased developer time and resources at its disposal. Despite this, the team did not have the resources required to have an independent security review of version 1.1.1, which was in early beta. This additional code was mission critical, because it implemented TLS v1.3, new standardized encryption technology. 

OSTIF and the OpenSSL team worked together to secure funding from the community, define a scope for a security review, and conduct an audit of both all of the new TLS 1.3 code, and the new Pseudorandom Number Generator (PRNG). Because of this effort, OpenSSL found and closed 15 potential security problems, and the PRNG received upgrades that both improved performance and randomness for the library.

A second example is Unbound DNS, a project managed by NLNetLabs.

**Unbound DNS** is a secure Domain Name Server (DNS) that provides both the encryption of DNS queries, and authentication of DNS responses to increase both the privacy and security of connected clients. It is a dependency for many security and privacy projects, because the service hardens key infrastructure within those projects against common vectors of attack. Key groups like the Let’s Encrypt project rely on Unbound DNS for security.

The Unbound project, despite being well staffed, did not have the knowledge nor the resources to execute a thorough independent security review of their source code. Working together, the OSTIF and Unbound team raised the funds required and conducted a thorough security audit. This audit resulted in 48 changes, including 5 high severity issues and a critical flaw that allowed full Remote Code Execution (RCE) for Unbound users utilizing the IPSEC module.

Since 2015, the OSTIF team has been honing processes to secure projects while causing the least amount of disruption to their work. Through building this infrastructure it was found that: in general, bug bounty programs generated too many low quality reports, and that many projects have no security resources at all. This allowed for multiple methods to set up audit teams for success and improve results. Furthermore, we’ve learned that diversity of talent and matching the skills of the audit team with the perceived areas of opportunity for a particular project yield substantially greater security gains with a similar budget. This is an ongoing process, and OSTIF is continually evaluating and updating our policies and techniques based on new challenges and new research.

## Funding Requirements

**Projects**

For the purposes of this section, a “project” is defined as a complete security review of an open source project: including scoping, RFP review, audits, remediation/patching and one or more published papers. Some projects are broken down into multiple sub-projects and will have multiple research papers published for a single “project.” (Example: systemd is broken down into seven sub-projects and there would be a total of seven papers for the systemd “project.”)

**Program Needs**

OSTIF requires a total of **$2.3 million per year** to operate efficiently. The organization can operate on a lower budget than this, but will exhaust funds before the end of the fiscal year, and revert efforts to fundraising activities until additional funding can be raised to continue. At approximately $2.3 million, OSTIF can work exclusively on projects and forward-looking strategy without spending time and resources on fundraising activities.

**Scaling**

OSTIF is formulated to be able to scale with funding in order to build an adaptive permanent organization. With committed long-term funding, OSTIF can hire additional staff and greatly expand the number of projects that can be completed each year. 


If funding remains after all goals are met, additional projects will be selected to receive security review and work will continue until the funds are exhausted.





