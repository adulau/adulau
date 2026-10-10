# Alexandre Dulaunoy — adulau

I break stuff and I do stuff. I enjoy people using machines in unexpected ways, and turning that curiosity into [free software](https://www.gnu.org/philosophy/free-sw.html), open data, and open specifications.

My work spans incident response, threat intelligence, vulnerability research, digital forensics, and information representation. At [CIRCL](https://www.circl.lu/), and with communities beyond it, I help build tools that analysts can inspect, run, adapt, and share.

[Website & writing](https://www.foo.be/) · [Mastodon](https://infosec.exchange/@adulau) · [Research / ORCID](https://orcid.org/0000-0002-5437-4652) · [Photography](https://www.flickr.com/photos/adulau/)

## Open source over the years

Keeping track of everything I have started, maintained, or contributed to is nearly impossible. This is a selection, built with many other people:

- **Early tools and experiments:** [hotp-js](https://github.com/adulau/hotp-js), a JavaScript HOTP implementation dating back to 2009; [Forban](https://github.com/adulau/Forban), for opportunistic file sharing on local networks without Internet access; and passive DNS and certificate-monitoring tools.
- **Long-running collaborative projects:** [cve-search](https://github.com/cve-search/cve-search), with contributions going back to 2012; [AIL](https://github.com/ail-project/ail-framework), since 2014; and the [MISP](https://github.com/MISP) ecosystem, including the taxonomy work we began in 2015. These connect software, shared knowledge, and operational security communities.
- **More recent work:** [hashlookup](https://github.com/hashlookup), [RansomLook](https://github.com/RansomLook/RansomLook), and [Vulnerability-Lookup](https://github.com/vulnerability-lookup/vulnerability-lookup), alongside new experiments in analysis, open source sustainability, and radio communication.

## Threat intelligence and collaborative analysis

I am part of the MISP core team and contribute across its software, data models, documentation, and open specifications. I also work with the [AIL Project](https://github.com/ail-project), [D4 Project](https://github.com/D4-project), and [CIRCL](https://github.com/circl) communities.

I have maintained [misp-modules](https://github.com/MISP/misp-modules) for years and also started a small MISP hackathon several years ago.

| Project | What it helps people do |
|:---|:---|
| [MISP](https://github.com/MISP/MISP) | Collect, correlate, and share threat intelligence across organisations. |
| [MISP taxonomies](https://github.com/MISP/misp-taxonomies), [galaxies](https://github.com/MISP/misp-galaxy), [objects](https://github.com/MISP/misp-objects), and [warning lists](https://github.com/MISP/misp-warninglists) | Give intelligence shared vocabularies, context, structured representations, and checks against misleading indicators. |
| [misp-modules](https://github.com/MISP/misp-modules) | Extend MISP with enrichment, import, export, and workflow actions through reusable modules that can also run independently. |
| [AIL](https://github.com/ail-project/ail-framework) | Collect and analyse unstructured information, track leaks and threats, and support investigations. |
| [Tempolocus](https://github.com/ail-project/tempolocus) | Infer likely timezones and locations from activity patterns over time, supporting analysis in AIL. |
| [D4](https://github.com/D4-project/d4-core) | Build distributed sensor networks for collecting and analysing security telemetry. |
| [RansomLook](https://github.com/RansomLook/RansomLook) | Track ransomware groups and their public activity, including leak-site publications. |
| [Threat Actor Explorer](https://github.com/adulau/threat-actor-explorer) | Explore the MISP galaxy threat-actor dataset locally in a browser. |
| [Fanything](https://github.com/fanything-project) | Explore network fingerprinting for correlation and CTI pivoting. The project and its fingerprint format are in an early, experimental phase. |

## Vulnerabilities and disclosure

I co-develop and co-maintain tools that make vulnerability information easier to find, correlate, and use, working with the [cve-search](https://github.com/cve-search) and [Vulnerability-Lookup](https://github.com/vulnerability-lookup) communities.

| Project | Focus |
|:---|:---|
| [cve-search](https://github.com/cve-search/cve-search) | Aggregate vulnerability sources and support local searches for CVEs and affected products. |
| [Vulnerability-Lookup](https://github.com/vulnerability-lookup/vulnerability-lookup) | Correlate vulnerability advisories, share sightings and comments, and support coordinated disclosure and advisory publication. |
| [git-vuln-finder](https://github.com/cve-search/git-vuln-finder) | Find potential vulnerability fixes from Git commit messages. |
| [cpe-guesser](https://github.com/cve-search/cpe-guesser) | Guess CPE identifiers from common software names. |

An earlier experiment, [SHVI allocator](https://github.com/cve-search/allocator), explored community allocation of software and hardware vulnerability identifiers. It remains part of the history of this work rather than a promise of a maintained service.

## Digital forensics and Internet infrastructure

These are tools I initially developed or maintain, from identifying known files to understanding domains, IP addresses, and encrypted network traffic.

| Project | Focus |
|:---|:---|
| [hashlookup-server](https://github.com/adulau/hashlookup-server) | Fast hash lookups against large reference datasets, used in the [CIRCL hashlookup service](https://hashlookup.circl.lu/). |
| [hashlookup-forensic-analyser](https://github.com/hashlookup/hashlookup-forensic-analyser) | Compare files in a forensic target with hashlookup and report known and unknown files. |
| [hashlookup-lib](https://github.com/hashlookup/hashlookup-lib) and [hashlookup-nsrl](https://github.com/hashlookup/hashlookup-nsrl) | Import hash records and NIST NSRL datasets into hashlookup. |
| [DomainClassifier](https://github.com/adulau/DomainClassifier) | Extract and classify domains, hostnames, and IP addresses from unstructured text. |
| [mmdb-server](https://github.com/adulau/mmdb-server) | Serve geographic and autonomous-system lookups from MaxMind-format databases, including the [GeoOpen dataset](https://cra.circl.lu/opendata/geo-open/). |
| [ptrclassify](https://github.com/adulau/ptrclassify) | Infer likely IP usage and location from reverse-DNS hostnames. |
| [ssldump](https://github.com/adulau/ssldump) | Analyse SSL/TLS traffic, with modern maintenance, JSON output, fingerprinting, and IPv6 support. |
| [netbeacon](https://github.com/adulau/netbeacon) | Check the accuracy and visibility of network capture and monitoring systems. |

Earlier work includes [pdns-qof-server](https://github.com/adulau/pdns-qof-server), [pdns-toolkit](https://github.com/adulau/pdns-toolkit), and [crl-monitor](https://github.com/adulau/crl-monitor), exploring passive DNS and the history of certificates and Internet infrastructure.

## Open standards and IETF Internet-Drafts

My standards work also includes participation in the [OASIS Cyber Threat Intelligence (CTI) Technical Committee](https://github.com/oasis-tcs/cti-stix2), which develops STIX and TAXII for representing and exchanging threat intelligence.

Working implementations and open specifications belong together. I author or co-author Internet-Drafts to document formats, make independent implementations possible, and improve interoperability. The documents below are **Internet-Drafts**; their current status and revisions are available in the IETF Datatracker.

| Specification | Purpose |
|:---|:---|
| MISP [core format](https://datatracker.ietf.org/doc/draft-dulaunoy-misp-core-format/), [taxonomy format](https://datatracker.ietf.org/doc/draft-dulaunoy-misp-taxonomy-format/), [galaxy format](https://datatracker.ietf.org/doc/draft-dulaunoy-misp-galaxy-format/), and [object template format](https://datatracker.ietf.org/doc/draft-dulaunoy-misp-object-template-format/) | Describe interoperable threat intelligence and its classification, context, and structure. [Sources and implementation context](https://github.com/MISP/misp-rfc). |
| [Passive DNS — Common Output Format](https://datatracker.ietf.org/doc/draft-dulaunoy-dnsop-passive-dns-cof/) | Give passive DNS services a common representation for their results. |
| [hashlookup format](https://datatracker.ietf.org/doc/draft-dulaunoy-hashlookup-format/) | Describe the exchange of hashlookup records and associated metadata. |
| [Programming Methodology Framework](https://datatracker.ietf.org/doc/draft-dulaunoy-programming-methodology-framework/) | Document a practical approach to software engineering. [Source](https://github.com/adulau/pmf). |
| [Open Contributions Descriptor](https://datatracker.ietf.org/doc/draft-dulaunoy-open-contributions-descriptor/) | Publish machine-readable information about an organisation's contributions to open source, open data, and open standards. |
| [Radio Image Framing Protocol](https://datatracker.ietf.org/doc/draft-dulaunoy-rifp/) | Explore image transmission over low-rate radio links, alongside the experimental [RIFP implementation](https://github.com/adulau/rifp). |

## Writing, teaching, and keeping things alive

Open source work also means documenting techniques, sharing research, teaching, and maintaining software after the initial excitement has passed.

- [The Art of Pivoting](https://github.com/adulau/the-art-of-pivoting) is my open book on finding relationships in intelligence investigations, using reproducible techniques and tools such as MISP and AIL.
- [threat-intelligence.eu](https://github.com/adulau/threat-intelligence.eu) collects open standards, documents, methodologies, and processes for threat intelligence.
- [OSSTRL](https://github.com/adulau/osstrl) explores how repository evidence can help assess open source software readiness.
- I write about security research, software, and open data on [foo.be](https://www.foo.be/), lecture on information security, and help organise [hack.lu](https://hack.lu/).
- I keep useful tools alive, including [ssldump](https://github.com/adulau/ssldump), and build small utilities such as [rss-tools](https://github.com/adulau/rss-tools). Maintenance is part of the work, even when it is less visible than a new project.

For the wider picture, browse [my repositories](https://github.com/adulau?tab=repositories) and the organisations linked above. Issues, patches, improved documentation, and new ideas are welcome in the relevant projects.
