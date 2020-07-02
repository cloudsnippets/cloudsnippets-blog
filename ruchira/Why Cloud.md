# Why Cloud?

The early useful computers were big and expensive.  They were built and used by governments, corporations and universities.  They were used for large projects, business and research.

Then came personal computers.  They were less expensive and you could have them in your home.  A lot of people learned to program computers and also used them for creative pursuits.  They could now do spreadsheets, desktop publishing and games.

Slightly bigger, faster, more powerful and more expensive computers that were called ***workstations*** were then introduced and they also were used by governments, corporations and universities.  Since they were groups of people, i.e. organizations, they needed to network these computers and they did.

These organizations and the software they used evolved to the point that the workstations were now providing organization-wide services and these workstations were centralized in a data center inside the organization.  Then they needed to work with multiple locations, i.e., branches, and these workstations were providing services to the branches via private networks.  The public network was cheaper and many shifted.

Data centers were an expensive luxury and prohibited smaller companies from competing directly with the big players.  This gave opportunity for new big players who supplied an alternative to data centers across the Internet.  You could rent hardware, i.e. servers, across the Internet.  This was called ***Infrastructure as a Service (IaaS)***.  You could purchase ***virtual machines*** of an arbitrary specification.  This allowed organizations to outsource the management and maintenance of the workstations to an outside organization.

This opened up the possibility for organizations and individuals to create software that would run on rented servers and serve customers across the Internet.  Now we were serving people outside our organization, i.e. customers, across the Internet with software we created and ran on rented infrastructure.  This was called ***Software as a Service (SaaS)***.  Now we were doing cloud computing.

> **Cloud Computing**

> The practice of using a network of remote servers hosted on the Internet to store, manage, and process data, rather than a local server or a personal computer.

Earlier, consumers had to buy and install the software on their machines.  Updates has to be installed and also added cost to the equation.  ***SaaS enabled the centralization of software deployment***.  Now software could be updated in one location for all the users.  Even complex technical changes could be made without affecting the users and their data.  Now consumers would pay a subscription fee, usually monthly, and use the software service.

With rentable hardware available from providers large and small, individuals and organizations of all sizes and shapes could compete across the globe on the Internet.  They competed to win customers for software services that were designed and created to appeal to market segments of their choice.  This drove waves of bottom up innovation and the quality of software improved.  ***Software development as a discipline evolved rapidly***.

Innovation in software design, creativity and usefulness of the software were now the key criteria for competition.  If your service was good, you got more customers and you scaled up your hardware.  You could easily shift to more powerful hardware at the vendor where you rented hardware.  *Individuals were now empowered to create useful services on the Internet and the better players in terms of creativity, innovation and entrepreneurship fared much better than the others*.  ***Capitalism was now available on the Internet***.

The rented servers and large players had chosen their own operating systems and proprietary additions.  A renting player was often locked-in into their ***IaaS provider*** and also had to provide other required third party software themselves.

The big players then realized the need to rent not only the hardware and the operating system, but also provide additional services such as databases.  This relieved developers from infrastructure considerations while also allowing them to manage the ***full software development cycle*** on the rented facility.  This was called ***Platform as a Service (PaaS)***.

Containerization ([***Docker***](https://docker.com) et al.) eased the lives of the developers and systems administrators by providing a standardized target to which the developed software could be aimed.  However, the coordination and management, i.e. orchestration, of these individual services were done on the platform was not standardized.

There were players on the ***PaaS marketplace*** and the individuals and organizations were often locked-in to a provider owing to the proprietary ways in which the software had to be developed and deployed.  Migration from vendor to vendor as the software needed to scale and price-based selection were inhibited.

[***Kubernetes***](http://kubernetes.io) is an answer to this problem.  Kubernetes is a whole ***cloud operating system*** that can run with any ***PaaS vendor***.  Developers can target Kubernetes during design and development and then run on any vendor's platform.

More players can now innovate and the ecosystem is improved.  People's lives get better!

#### Related Snippets

1. [What is Cloud Computing?](https://cloudsnippets.io/2020/06/27/what-is-cloud-computing/)
