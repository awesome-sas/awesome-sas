# awesome-sas

An opinionated, high-signal collection of links for the SAS programming language and the wider ecosystem around working SAS programmers and administrators.

This list favors:

- official documentation and support pages
- durable community archives
- hard-to-find legacy references that are still technically useful
- open-source tooling that helps modern SAS development

## Contents

- [Getting Started](#getting-started)
- [Official Documentation](#official-documentation)
- [SAS Best Practices, Guidelines, and Tips](#sas-best-practices-guidelines-and-tips)
- [Knowledge, Notes, and Samples](#knowledge-notes-and-samples)
- [Core Programming References](#core-programming-references)
- [Macro Libraries](#macro-libraries)
- [ODS, Reporting, and Graphics](#ods-reporting-and-graphics)
- [Communities and Discussion](#communities-and-discussion)
- [Conference Proceedings and Archives](#conference-proceedings-and-archives)
- [Blogs and Expert Writing](#blogs-and-expert-writing)
- [Testing and Quality](#testing-and-quality)
- [Open Source, Editors, and Integration](#open-source-editors-and-integration)
- [Third-Party Tools and Frameworks](#third-party-tools-and-frameworks)
- [Stored Processes and Web Apps](#stored-processes-and-web-apps)
- [Administration and Operations](#administration-and-operations)
- [Learning and Training](#learning-and-training)
- [Books](#books)
- [Video](#video)
- [Hard-to-Find Gems](#hard-to-find-gems)

## Getting Started

- [Base SAS Support](https://support.sas.com/en/software/base-sas-support.html) - Best official starting point for tutorials, tip sheets, support content, and links into the programming docs.
- [SAS Programming: SAS 9.4 and SAS Viya 3.5](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=pgmsashome&docsetTarget=home.htm) - Main programming help center for classic SAS 9.4 environments.
- [SAS Programming: SAS Viya Platform](https://go.documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=default&docsetId=pgmsaswlcm) - Main programming help center for modern Viya-based workflows.
- [SAS Studio Support](https://support.sas.com/en/software/studio-support.html#documentation) - Central hub for SAS Studio documentation and support material.
- [SAS Enterprise Guide Support](https://support.sas.com/en/software/enterprise-guide-support.html#documentation) - Central hub for Enterprise Guide documentation and support material.
- [Video Tutorials](https://video.sas.com/category/videos/how-to-tutorials) - Official SAS video catalog.
- [SAS OnDemand for Academics](https://www.sas.com/en_us/software/on-demand-for-academics.html) - Free cloud-hosted SAS access for students and self-learners; no installation required.
- [SAS Programming 1: Essentials](https://support.sas.com/edu/schedules.html?crs=PROG1) - Canonical entry course for new SAS programmers.

## Official Documentation

- [SAS Documentation](https://support.sas.com/en/documentation.html) - Top-level documentation hub across SAS products.
- [SAS Programming: SAS 9.4 and SAS Viya 3.5](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=pgmsashome&docsetTarget=home.htm) - Primary help center for SAS programming.
- [SAS Programming: SAS Viya Platform](https://go.documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=default&docsetId=pgmsaswlcm) - Programming docs for Viya compute, CAS-facing work, and modern tooling.
- [All SAS Procedures (by name)](https://go.documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/allprodsproc/procedures.htm) - Fastest way to browse PROC documentation by name.
- [Install Center](https://support.sas.com/en/documentation/install-center.html) - Installation and configuration docs.
- [System Requirements](https://support.sas.com/en/documentation/system-requirements.html) - Platform requirements for Base SAS and related products.
- [Third-Party Software Reference](https://support.sas.com/en/documentation/third-party-software-reference.html) - Required third-party software and compatibility notes.
- [Browse All Product Support Pages](https://support.sas.com/en/software/all-products-support.html) - Product-by-product support index.
- [Base SAS Support](https://support.sas.com/en/software/base-sas-support.html) - Especially useful as a curated index for programmers.
- [SAS Technical Papers](https://support.sas.com/en/technical-papers.html) - Official paper index that links into technical content without forcing a product search.

## SAS Best Practices, Guidelines, and Tips

These links are a compact starting point for writing cleaner, safer, and easier-to-maintain SAS code.

### Core coding habits

- [How the DATA Step Works: A Basic Introduction](https://documentation.sas.com/?docsetId=basess&docsetTarget=n053a58fwk57v7n14h8x7y7u34y4.htm&docsetVersion=9.4) - Understand compile time vs. execution time, implicit retain behavior, and why statement order matters.
- [About SAS DATA Step Statements](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=lestmtsref&docsetTarget=n0plmmtqil8l65n1nxq92k8m35ij.htm) - Essential reference for precise statement behavior.
- [SAS 9.4 Language Reference: Concepts](https://documentation.sas.com/doc/en/lrcon/9.4/titlepage.htm) - Strong conceptual foundation for SAS program flow and language behavior.
- [SAS 9.4 DATA Step Statements: Reference](https://documentation.sas.com/doc/en/lestmtsref/9.4/titlepage.htm) - Exact syntax and semantics for statements.
- [SAS 9.4 Functions and CALL Routines: Reference](https://documentation.sas.com/doc/en/lefunctionsref/9.4/titlepage.htm) - Best source when choosing the right function instead of reinventing logic.
- [SAS 9.4 Formats and Informats: Reference](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/leforinforref/titlepage.htm) - Critical for robust input parsing and readable output.

### DATA step, SQL, and macro guidance

- [Getting Started with the Macro Facility](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=mcrolref&docsetTarget=p1ccprwibo8gvqn1q6zinvjlzuut.htm) - Good starting point for macro design and macro variable handling.
- [SAS 9.4 Macro Language: Reference](https://documentation.sas.com/doc/en/mcrolref/9.4/titlepage.htm) - Use this when writing reusable macro code and avoiding macro resolution bugs.
- [Introduction to the SQL Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=sqlproc&docsetTarget=p07v6ho0hymhfvn1jboqfe38jnox.htm) - Useful for knowing where PROC SQL is strong and where it is not.
- [Comparing PROC SQL with the SAS DATA Step](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=sqlproc&docsetTarget=p015vwpsg8pas3n135iy1t43o1mc.htm) - Practical guidance for choosing the right tool.
- [PROC SQL Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/Tipsheet_sql.pdf) - Handy quick reference for common SQL patterns.
- [SAS Macro Language Processing Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/Tipsheet_macro.pdf) - Great for understanding macro compilation and execution.
- [Hash Object Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/hash-tip-sheet.pdf) - Excellent for fast lookups in DATA step workflows.

### Reporting and output

- [A Quick Start to Using ODS](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=odsug&docsetTarget=n0i2aw12zfiwnon1qxkpxu04ip1w.htm) - Good starting point for consistent output control.
- [Overview: SGPLOT Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=grstatproc&docsetTarget=p1t32i8511t1gfn17sw07yxtazad.htm) - Modern graphing best practices.
- [ODS Graphics Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/TipSheet_ODSGraphics.pdf) - Compact reminder for graph output choices.
- [ODS Excel Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/ODS_Excel_Dest_tips.pdf) - Helpful for polished Excel deliverables.

### Learning and examples

- [DATA Step Samples](https://support.sas.com/en/knowledge-base/data-step-samples.html) - Practical examples for arrays, BY-group processing, file I/O, and MERGE.
- [Graphics Samples Gallery](https://support.sas.com/en/knowledge-base/graph-samples-gallery.html) - Good reference for high-quality output examples.
- [The DO Loop](https://blogs.sas.com/content/iml/) - Excellent for algorithmic thinking and statistical programming patterns.
- [The SAS Dummy](https://blogs.sas.com/content/sasdummy/) - Practical workflow advice and productivity tips.
- [SAS Communities Library](https://communities.sas.com/t5/SAS-Communities-Library/tkb-p/library) - Broad archive of applied SAS articles.


## Knowledge, Notes, and Samples

- [SAS Knowledge](https://support.sas.com/en/knowledge-base.html) - Main entry point for notes, KB articles, sample notes, and support content.
- [Installation SAS Notes](https://support.sas.com/en/search.html?q=Installation%20Note) - Installation-specific notes.
- [Problem SAS Notes](https://support.sas.com/en/search.html?q=Problem%20Note) - Problem and defect-oriented support notes.
- [Usage SAS Notes](https://support.sas.com/en/search.html?q=Usage%20Note) - Usage guidance and common gotchas.
- [Sample SAS Notes](https://support.sas.com/en/search.html?q=Sample%20kb) - Official sample programs hidden inside the notes system.
- [DATA Step Samples](https://support.sas.com/en/knowledge-base/data-step-samples.html) - Curated examples for arrays, BY-group work, file I/O, MERGE, and more.
- [Graphics Samples Gallery](https://support.sas.com/en/knowledge-base/graph-samples-gallery.html) - One of the best official sources for graphics examples with code.
- [Browse Samples](https://support.sas.com/kb/?ct=51000&qm=3&la=en&qt=contenttype:%22Sample%22&col=suppprd) - Older but still useful sample browser.
- [Downloads](https://support.sas.com/downloads/index.htm) - Software downloads and supporting files.
- [Hot Fixes](https://tshf.sas.com/techsup/download/hotfix/hotfix.html) - Official hot fix catalog.
- [Maintenance Releases](https://support.sas.com/en/technical-support/maintenance/sas-maintenance-process.lang.html) - How SAS maintenance works.
- [All Maintenance Resources](https://support.sas.com/en/technical-support/maintenance.lang.html) - Maintenance overview and supporting links.

## Core Programming References

- [How the DATA Step Works: A Basic Introduction](https://documentation.sas.com/?docsetId=basess&docsetTarget=n053a58fwk57v7n14h8x7y7u34y4.htm&docsetVersion=9.4) - One of the most important official explanations for understanding execution flow.
- [About SAS DATA Step Statements](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=lestmtsref&docsetTarget=n0plmmtqil8l65n1nxq92k8m35ij.htm) - Entry point into DATA step statements.
- [Getting Started with the Macro Facility](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=mcrolref&docsetTarget=p1ccprwibo8gvqn1q6zinvjlzuut.htm) - Official macro entry page.
- [Introduction to the SQL Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=sqlproc&docsetTarget=p07v6ho0hymhfvn1jboqfe38jnox.htm) - Official PROC SQL starting point.
- [Comparing PROC SQL with the SAS DATA Step](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=sqlproc&docsetTarget=p015vwpsg8pas3n135iy1t43o1mc.htm) - Useful when deciding between DATA step and PROC SQL.
- [LIBNAME Statement Syntax](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=lestmtsglobal&docsetTarget=n1nk65k2vsfmxfn1wu17fntzszbp.htm) - Essential reference for library assignment.
- [Overview: PROC IMPORT](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=acpcref&docsetTarget=p0mqdq52ktqgjjn1vseqoiuyt3v1.htm) - Canonical import reference.
- [Overview: EXPORT Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=proc&docsetTarget=p09k160vk93xxhn171zz1z6551w2.htm) - Canonical export reference.
- [Overview: MEANS Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=proc&docsetTarget=n0k7qr5c2ah3stn10g1lr5oytz57.htm) - Core descriptive stats procedure reference.
- [Overview: FREQ Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=procstat&docsetTarget=procstat_freq_overview.htm) - Core frequency and tabulation reference.
- [Overview: PRINT Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=proc&docsetTarget=p1dlh3svb4rrasn14h8jm6nyrj5o.htm) - Simple but indispensable output reference.
- [Overview: REPORT Procedure](https://documentation.sas.com/doc/de/pgmsascdc/9.4_3.5/proc/p0bqogcics9o4xn17yvt2qjbgdpi.htm) - Main production reporting procedure; more powerful than PRINT and more concise than hand-coded ODS.
- [SAS Formats and Informats: Reference](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/leforinforref/titlepage.htm) - Complete format and informat reference; often needed alongside function and statement docs but harder to find.
- [PROC SQL Joining Two Tables](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=sqlproc&docsetTarget=n00fjmxaad37mgn1rszsatq472zs.htm#n00fjmxaad37mgn1rszsatq472zs) - Useful direct example page.

## Macro Libraries

- [SAS Macro Repository](https://cu-anschutz-dos-corp.github.io/sas-macros/) - Maintained DOS-CORP autocall library with documentation and raw source files.
- [SASjs Core](https://core.sasjs.io/) - MIT-licensed production-ready macro library for SAS application development.
- [SAS Utility Macros](https://github.com/sasutils/macros) - General-purpose SAS utility macros with browsable documentation and many small helpers.
- [SASJedi/sas-macros](https://github.com/SASJedi/sas-macros) - Selected reusable macros from a personal library, with built-in help text.
- [SAS Macros for Statistics and Graphics](https://github.com/friendly/SAS-macros) - Large historical collection of statistical and graphics macros.
- [SAS Packages Framework](https://github.com/yabwon/SAS_PACKAGES) - Framework for sharing reusable SAS code as versioned packages.
- [Paul's SAS Utility Macros Toolbox](https://github.com/paul-canals/toolbox) - Large documented utility macro toolbox with autocall-style organization.
- [SAS Macro Utilities](https://github.com/Steve0verton/sas-macro-util) - Small utility macro collection with an autocall directory layout.

## ODS, Reporting, and Graphics

- [ODS R&D Page](https://support.sas.com/rnd/base/ods/index.html) - Hidden-feeling SAS R&D microsite full of ODS references, subtopics, and papers.
- [SAS Output Delivery System Support](https://support.sas.com/en/software/output-delivery-system-support.html) - Official ODS support hub.
- [A Quick Start to Using ODS](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=odsug&docsetTarget=n0i2aw12zfiwnon1qxkpxu04ip1w.htm) - Fast way into ODS basics.
- [Overview: SGPLOT Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=grstatproc&docsetTarget=p1t32i8511t1gfn17sw07yxtazad.htm) - Main entry to modern SAS graphing.
- [Graphically Speaking](https://blogs.sas.com/content/graphicallyspeaking/) - Official blog focused on ODS Graphics and GTL.
- [Visual Index to Graphically Speaking](https://support.sas.com/rnd/datavisualization/graphicallyspeakingindex/) - Easier way to browse that blog by visual example.
- [Graphics Samples Gallery](https://support.sas.com/en/knowledge-base/graph-samples-gallery.html) - Official graph examples with code.
- [ODS and Base Reporting Community](https://communities.sas.com/t5/ODS-and-Base-Reporting/bd-p/ods_base_reporting) - Practical Q&A for ODS, PROC REPORT, and reporting output.
- [Graph Template Language Tip Sheet](https://support.sas.com/rnd/app/ODSGraphics/TipSheet_GTL.pdf) - Compact GTL reference.
- [ODS Graphics Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/TipSheet_ODSGraphics.pdf) - Good quick-reference sheet.
- [ODS Excel Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/ODS_Excel_Dest_tips.pdf) - Helpful when exporting polished Excel output.
- [SAS Visual Analytics Gallery](https://communities.sas.com/t5/SAS-Visual-Analytics-Gallery/tkb-p/vagallery) - Useful design and reporting examples beyond classic Base SAS output.
- [Robert Allison's SAS Graphics Examples](https://robslink.com/SAS/Home.htm) - SAS/Graph and ODS examples

## Communities and Discussion

- [SAS Programming](https://communities.sas.com/t5/SAS-Programming/bd-p/programming) - Most active SAS programming Q&A board.
- [SAS Procedures](https://communities.sas.com/t5/SAS-Procedures/bd-p/sas_procedures) - Procedure-specific questions and edge cases.
- [SAS Studio](https://communities.sas.com/t5/SAS-Studio/bd-p/sas_studio) - Editor and workflow support.
- [SAS Enterprise Guide](https://communities.sas.com/t5/SAS-Enterprise-Guide/bd-p/sas_eg) - Enterprise Guide help and workflow discussions.
- [Graphics Programming](https://communities.sas.com/t5/Graphics-Programming/bd-p/sas_graph) - Graphics and visual output discussions.
- [ODS and Base Reporting](https://communities.sas.com/t5/ODS-and-Base-Reporting/bd-p/ods_base_reporting) - Reporting-specific Q&A.
- [SAS/IML Software and Matrix Computations](https://communities.sas.com/t5/SAS-IML-Software-and-Matrix/bd-p/sas_iml) - IML questions and examples.
- [Developers](https://communities.sas.com/t5/Developers/bd-p/developers) - APIs, integrations, and developer tooling.
- [SAS Code Examples](https://communities.sas.com/t5/SAS-Code-Examples/tkb-p/code-samples) - Community-hosted code examples with practical usage patterns.
- [Ask the Expert](https://communities.sas.com/t5/Ask-the-Expert/tkb-p/askexpert) - Webinar archive and expert answers.
- [SAS User Groups](https://communities.sas.com/t5/SAS-User-Groups/gh-p/sas-users-group-leaders) - Official community hub for user groups.
- [SAS-L Mailing List Archive](https://marc.info/?l=sas-l&r=1&w=2) - Deep archive for obscure behaviors and real-world troubleshooting.
- [Stack Overflow SAS tag](https://stackoverflow.com/questions/tagged/sas) - Useful for concrete, practical debugging and style patterns.

## Conference Proceedings and Archives

- [Past Conference Proceedings: 1976-onward](https://communities.sas.com/t5/SAS-Communities-Library/Past-Conference-Proceedings-1976-onward/ta-p/863480) - Official master index of SAS.ONE, SUGI, SAS Global Forum, SAS Explore, and SAS Innovate proceedings.
- [Lex Jansen SAS Proceedings and More](https://www.lexjansen.com/) - Best searchable cross-conference paper archive in the SAS ecosystem.
- [SUGI and SAS Global Forum at Lex Jansen](https://www.lexjansen.com/sugi/) - Direct path to the classic paper archive.
- [PharmaSUG at Lex Jansen](https://www.lexjansen.com/pharmasug/) - Essential archive for clinical and life sciences SAS work.
- [PHUSE EU Connect at Lex Jansen](https://www.lexjansen.com/phuse/) - Strong source for regulated-industry programming content.
- [PHUSE US Connect at Lex Jansen](https://www.lexjansen.com/phuse-us/) - More PHUSE material, especially useful for pharma and submissions work.
- [WUSS at Lex Jansen](https://www.lexjansen.com/wuss/) - Western Users of SAS Software proceedings.
- [SESUG at Lex Jansen](https://www.lexjansen.com/sesug/) - SouthEast SAS Users Group proceedings.
- [MWSUG at Lex Jansen](https://www.lexjansen.com/mwsug/) - MidWest SAS Users Group proceedings.
- [NESUG Archive at Lex Jansen](https://www.lexjansen.com/nesug/) - Historic NorthEast users group content with many programming gems.
- [Tech Report Archive](https://communities.sas.com/t5/Tech-Report-Archive/tkb-p/tech-report-archive) - Easy-to-miss archive of older SAS technical writing.
- [SAS-L Mailing List Archive](https://marc.info/?l=sas-l&r=1&w=2) - Deep historical archive for obscure issues, legacy behavior, and hard debugging problems.
- [SAS Technical Papers](https://support.sas.com/en/technical-papers.html) - Strong source for tuning, design patterns, and edge-case lessons.


## Blogs and Expert Writing

- [The DO Loop](https://blogs.sas.com/content/iml/) - Rick Wicklin's long-running official blog on statistical programming, algorithms, and SAS/IML.
- [Graphically Speaking](https://blogs.sas.com/content/graphicallyspeaking/) - Official visualization and ODS Graphics blog.
- [The SAS Dummy](https://blogs.sas.com/content/sasdummy/) - Chris Hemedinger's practical SAS blog with many workflow and programming posts.
- [Programming Tips Topic](https://blogs.sas.com/content/topic/programming-tips/) - Official SAS blogs filtered to programming-oriented content.
- [Learn SAS Topic](https://blogs.sas.com/content/topic/learn-sas/) - Official learning-oriented blog roll.
- [SAS Communities Library](https://communities.sas.com/t5/SAS-Communities-Library/tkb-p/library) - Broad archive of technical articles from SAS staff and community experts.
- [UCLA OARC SAS Library](https://stats.oarc.ucla.edu/sas/library/) - Dense, preserved collection of SAS tutorials, notes, and linked papers.
- [SAS Tips from the Community](https://communities.sas.com/t5/SAS-Tips-from-the-Community/bd-p/sastips) - Small, practical community tips.
- [Research and Science from SAS](https://communities.sas.com/t5/Research-and-Science-from-SAS/tkb-p/science) - Research-oriented articles and technical material.

## Testing and Quality

- [SASUnit](https://github.com/HMS-Analytical-Software/SASUnit) - Mature unit-testing framework for SAS programs, with assertions, coverage, batch execution, and generated test documentation.
- [FUTS (outdated)](https://github.com/ocd-jacobs/futs) - FUTS (Framework for Unit Testing SAS programs). Has not seen any updates for a very long time.
- [SAS Programming Community](https://communities.sas.com/t5/SAS-Programming/bd-p/programming) - Good place to find edge cases, log diagnostics, and real-world failure patterns worth testing.

## Open Source, Editors, and Integration

- [SAS Developer Portal](https://developer.sas.com/) - Official developer hub for APIs, integration, and programming on Viya.
- [Open Source Software from SAS](https://sassoftware.github.io/) - Official gateway to SAS-owned GitHub projects and developer tooling.
- [SAS on GitHub](https://github.com/sassoftware) - Main SAS GitHub organization.
- [SASPy Documentation](https://sassoftware.github.io/saspy/) - Official Python-to-SAS bridge.
- [Python SWAT Documentation](https://sassoftware.github.io/python-swat/) - Official Python client for CAS.
- [SAS Extension for Visual Studio Code](https://sassoftware.github.io/vscode-sas-extension/) - Official VS Code documentation for SAS editing and execution.
- [SAS Code Examples Repository](https://github.com/sassoftware/sas-code-examples) - Official repository of runnable SAS examples.
- [SAS MCP Server](https://github.com/sassoftware/sas-mcp-server) - Model Context Protocol server for executing SAS code on Viya.
- [SAS Viya REST APIs](https://developer.sas.com/rest-apis) - Canonical reference for all Viya REST endpoints; essential starting point for any integration or automation work.
- [SAS Software Organization Support Page for SASPy](https://support.sas.com/en/software/saspy.html) - Product support entry for SASPy.

## Third-Party Tools and Frameworks

- [SASjs](https://sasjs.io/) - End-to-end framework and documentation hub for building and deploying SAS applications.
- [SASjs Adapter](https://github.com/sasjs/adapter) - Client-side library for bidirectional SAS and JavaScript communication.
- [SASjs CLI](https://cli.sasjs.io/) - Command-line tooling for build, deploy, test, and documentation workflows.
- [SASjs Server](https://github.com/sasjs/server) - Open-source server for running stored programs and building web apps on Base SAS.
- [SASPAC](https://github.com/SASPAC) - Community archive for reusable SAS packages.

## Stored Processes and Web Apps

Stored processes are the classic SAS 9 web-application pattern. In SAS Viya, the successor is the Job Execution Service (JES), where jobs replace stored processes for web-facing execution.

- [Jobs: Stored processes in Viya](https://blogs.sas.com/content/sgf/2020/02/28/jobs-stored-processes-in-viya/) - SAS blog post explaining the stored-process-to-Jobs mapping in Viya.
- [Migration of Stored Processes to SAS Viya Jobs](https://communities.sas.com/t5/SAS-Communities-Library/Migration-of-Stored-Processes-to-SAS-Viya-Jobs/ta-p/821103) - Community library article with migration guidance from SAS 9 stored processes to Viya jobs.
- [Unlocking Performance: Compute Tasks are The New Fast Execution Path for Stored Processes in SAS Viya](https://communities.sas.com/t5/SAS-Communities-Library/Compute-Tasks-are-The-New-Fast-Execution-Path-for-Stored/ta-p/976582) - Performance-oriented writeup on faster execution paths for stored-process-style workloads in Viya.
- [Debugging a stored-process problem](https://blogs.sas.com/content/sgf/2021/10/20/debugging-a-stored-process-problem/) - Practical guide to logs, failure modes, and diagnosis when a stored process misbehaves.
- [Controlling Stored Process Execution through Request Initialization Code Injection](https://blogs.sas.com/content/sgf/2017/07/28/controlling-stored-process-execution-through-request-initialization-code-injection/) - Advanced execution-control pattern for enforcing the right server context and request behavior.
- [Pick a Display, Any Display - The Power of _odsdest in Stored Processes](https://blogs.sas.com/content/sastraining/2005/10/20/pick-a-display-any-display-the-power-of-_odsdest-in-stored-processes/) - Useful output-formatting technique for reusable stored processes that emit HTML, PDF, or RTF.
- [Backup or copy all components of your stored process before making changes](https://blogs.sas.com/content/sastraining/2012/06/06/backup-or-copy-all-components-of-your-stored-process-before-making-changes/) - Simple but important change-management advice before editing deployed stored processes.

## Administration and Operations

- [Install Center](https://support.sas.com/en/documentation/install-center.html) - Installation docs.
- [System Requirements](https://support.sas.com/en/documentation/system-requirements.html) - Deployment prerequisites.
- [Third-Party Software Reference](https://support.sas.com/en/documentation/third-party-software-reference.html) - Compatibility dependencies.
- [SAS Hot Fix Announcements](https://communities.sas.com/t5/SAS-Hot-Fix-Announcements/bg-p/hf) - Hot-fix news in community form.
- [Administration and Deployment](https://communities.sas.com/t5/Administration-and-Deployment/bd-p/sas_admin) - Main admin Q&A board.
- [Architecture](https://communities.sas.com/t5/Architecture/bd-p/architecture) - Architecture-focused community board.
- [SAS Viya Release Updates](https://communities.sas.com/t5/SAS-Viya-Release-Updates/tkb-p/releaseupdates) - Release update stream for Viya.
- [Moving to SAS Viya](https://communities.sas.com/t5/Moving-to-SAS-Viya/bd-p/move2viya) - Migration-oriented content and lessons learned.
- [SAS Viya Workbench: Getting Started](https://communities.sas.com/t5/SAS-Viya-Workbench-Getting/tkb-p/viya-workbench-get-started) - Good entry for Workbench-specific setup and usage.
- [General Technical Support](https://support.sas.com/en/technical-support.html#contact) - Contact and support entry points.
- [Update a Support Request](https://support.sas.com/en/technical-support/update-a-support-request.lang.html) - Support case management.
- [Open a Support Case](https://service.sas.com/csm?id=sc_category&sys_id=1b8611d5c3921200b0449f2974d3ae12&catalog_id=-1&spa=1) - Direct case opening path.
- [Checklist of SAS 9 Administration Tasks](https://support.sas.com/resources/papers/Platform-Administration-Tasks.pdf) - Legacy SAS 9 administration checklist and task reference.
- [SAS Viya Administration Checklist](https://github.com/sassoftware/viya4-admin-checklist) - SAS-owned checklist for recurring Viya platform administration tasks.
- [SAS Viya Administration Resource Kit](https://github.com/sassoftware/viya4-ark) - SAS-owned tools for pre-install assessment, deployment reports, LDAP validation, and log downloads.
- [SAS Viya Monitoring for Kubernetes](https://github.com/sassoftware/viya4-monitoring-kubernetes) - Official SAS toolset for metric monitoring, alerts, and log aggregation.
- [SAS Viya Deployment](https://github.com/sassoftware/viya4-deployment) - SAS-owned Ansible automation for baseline setup and Viya deployment management.
- [SAS Viya Orders CLI](https://github.com/sassoftware/viya4-orders-cli) - CLI for downloading Viya order assets needed by administrators and deployers.
- [SAS Viya Platform Operations Guide](https://go.documentation.sas.com/?cdcId=itopscdc&cdcVersion=default&docsetId=itopswlcm&docsetTarget=home.htm) - Official operations documentation hub for Kubernetes-based Viya.
- [SAS Viya Forge](https://viyaforge.sas.com/en/) - Reference Architectures, Best Practices, Guides and Tools for SAS Viya
- [WORKtop](https://github.com/Boemska/worktop) - Lightweight monitoring utility for SASWORK and SASUTIL directories.
- [Stack Overflow SAS tag](https://stackoverflow.com/questions/tagged/sas) - Fast community troubleshooting for concrete SAS questions.

## Learning and Training

- [SAS OnDemand for Academics](https://www.sas.com/en_us/software/on-demand-for-academics.html) - Free cloud-hosted SAS access for students and self-learners; no installation required.
- [SAS Viya for Learners](https://www.sas.com/en_us/software/viya-for-learners.html) - Free cloud access to SAS Viya for students and educators, including SAS Studio, Visual Analytics, and machine learning tools.
- [SAS Viya Workbench for Learners](https://www.sas.com/en_us/software/viya-workbench-for-learners.html) - Free tier of SAS Viya Workbench for individual learners; provides a local VS Code-based environment for SAS and Python programming on Viya.
- [SAS Programming 1: Essentials](https://support.sas.com/edu/schedules.html?crs=PROG1) - Standard starting course for SAS programmers.
- [SAS Programming 2: Data Manipulation Techniques](https://support.sas.com/edu/schedules.html?crs=PROG2) - Follow-on course for practical data work.
- [Tutorialspoint SAS Tutorial](https://www.tutorialspoint.com/sas/index.htm) - Straightforward beginner tutorial index.
- [Listen Data SAS Tutorials](https://www.listendata.com/p/sas-tutorials.html) - Practical SAS tutorial index with examples.
- [Advanced Programming](https://communities.sas.com/t5/Advanced-Programming/bd-p/advanced_programming) - Community training board around advanced programming topics.
- [Free e-Learning](https://support.sas.com/edu/elearning.html?ctry=us&productType=library) - Official free course catalog.
- [Training Overview](https://www.sas.com/en_us/training/overview.geo.html) - SAS training home.
- [Certification](https://www.sas.com/en_us/certification.geo.html) - Official certification portal.
- [Knowledge Badges](https://learn.sas.com/?sas_product_types_2%5b%5d=knowledge%20badge&orderbykey=text&itemstyle=narrow) - Lightweight credentialing paths for specific SAS skills.
- [SAS Tips from the Community](https://communities.sas.com/t5/SAS-Tips-from-the-Community/bd-p/sastips) - Quick wins and practical lessons.
- [Course Case Studies and Challenges](https://communities.sas.com/t5/Course-Case-Studies-and/tkb-p/training_library) - Practice material and training exercises.
- [SAS Software YouTube Channel](https://www.youtube.com/@SASSoftware) - Official product demos, announcements, and event sessions.
- [SAS Users YouTube Channel](https://youtube.com/sasusers) - Tutorials and community content.

## Books

- [SAS Books](https://support.sas.com/en/books.html) - Official SAS books catalog.
- [The Little SAS Book, Sixth Edition](https://www.sas.com/store/books/categories/getting-started/the-little-sas-book-a-primer-sixth-edition/prodBK_73044_en.html) - Classic beginner-friendly book.
- [Learning SAS by Example](https://www.sas.com/store/books/categories/getting-started/learning-sas-by-example-a-programmer-s-guide-second-edition/prodBK_71442_en.html) - Practical, example-heavy SAS book.
- [Fundamentals of Programming in SAS: A Case Studies Approach](https://www.sas.com/store/books/categories/getting-started/fundamentals-of-programming-in-sas-a-case-studies-approach/prodBK_71342_en.html) - Useful for structured learning through examples.
- [SAS Certified Specialist Prep Guide: Base Programming Using SAS 9.4](https://www.sas.com/store/books/categories/certification-guide/sas-certified-specialist-prep-guide-base-programming-using-sas-9-4/prodBK_72102_en.html) - Good exam-oriented reference.
- [SAS Certified Professional Prep Guide: Advanced Programming Using SAS 9.4](https://www.sas.com/store/books/categories/certification-guide/sas-certified-professional-prep-guide-advanced-programming-using-sas-9-4/prodBK_73006_en.html) - Advanced certification-oriented reference.

## Video

- [SAS Video Tutorials](https://video.sas.com/category/videos/how-to-tutorials) - Official how-to video catalog; broad coverage across products and tasks.
- [SAS Software YouTube Channel](https://www.youtube.com/@SASSoftware) - Official product demos, announcements, and event recordings.
- [SAS Users YouTube Channel](https://youtube.com/sasusers) - Community tutorials and user-contributed content.
- [Into the Viya Verse](https://www.youtube.com/playlist?list=PLncvHGGelzhX1hMwfEHA2eBQOFgV1FfSZ) - SAS Viya-focused video series and walkthroughs.
- [Ask the Expert Webinar Archive](https://communities.sas.com/t5/Ask-the-Expert/tkb-p/askexpert) - Recordings of expert-led webinars covering a wide range of SAS topics.
- [SAS Global Forum Recordings](https://communities.sas.com/t5/SAS-Global-Forum-Proceedings/tkb-p/proceedings-2021) - Presentation recordings from SAS Global Forum.

## Hard-to-Find Gems

- [SAS 9.4 Functions and CALL Routines: Reference](https://documentation.sas.com/doc/en/lefunctionsref/9.4/titlepage.htm) - The function bible, much faster to browse than broad help-center search when you already know what you need.
- [SAS 9.4 Formats and Informats: Reference](https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/leforinforref/titlepage.htm) - The companion book to the function reference; indispensable for data representation and input parsing work.
- [Base SAS 9.4 Procedures Guide](https://documentation.sas.com/doc/en/proc/9.4/titlepage.htm) - Excellent one-book style entry into core procedures.
- [SAS 9.4 Macro Language: Reference](https://documentation.sas.com/doc/en/mcrolref/9.4/titlepage.htm) - Direct macro reference book rather than a general search result.
- [SAS 9.4 Statements: Reference](https://documentation.sas.com/doc/en/lestmtsref/9.4/titlepage.htm) - Useful when you need exact statement behavior.
- [SAS 9.4 Language Reference: Concepts](https://documentation.sas.com/doc/en/lrcon/9.4/titlepage.htm) - Still one of the best places for understanding how SAS works, not just memorizing syntax.
- [SAS 9.4 ODS User's Guide](https://documentation.sas.com/doc/en/odsug/9.4/titlepage.htm) - Direct ODS book link for reporting-heavy work.
- [ODS R&D Page](https://support.sas.com/rnd/base/ods/index.html) - Packed with links that are hard to rediscover from the main docs.
- [Tech Report Archive](https://communities.sas.com/t5/Tech-Report-Archive/tkb-p/tech-report-archive) - Older SAS writing that often explains practical tasks more directly than current docs.
- [Past Conference Proceedings: 1976-onward](https://communities.sas.com/t5/SAS-Communities-Library/Past-Conference-Proceedings-1976-onward/ta-p/863480) - Official bridge into very old proceedings.
- [SAS What's New Index](https://criptic.github.io/SAS-Whats-New/index.html) - Community-maintained index of SAS version changes and feature history, useful when tracking when behavior or features appeared.
- [Hash Object Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/hash-tip-sheet.pdf) - Compact, printable reference for one of the most powerful advanced SAS features.
- [SAS Macro Language Processing Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/Tipsheet_macro.pdf) - Quick macro mental model refresher.
- [PROC SQL Tip Sheet](https://support.sas.com/content/dam/SAS/support/en/products-solutions/base-sas/tip-sheets/Tipsheet_sql.pdf) - Handy compact SQL quick reference.
- [PROC Python for SAS 9.4](https://documentation.sas.com/doc/en/bicdc/9.4/whatsdiff/n1udrpx1gk6fk7n1r34p5rca7r6a.htm) - Configuration for PROC PYTHON in SAS 9.4

## Contributing

Pull requests that add durable, high-signal resources are welcome.

Good additions usually have at least one of these properties:

- they are canonical official references
- they solve real programming or administration problems
- they are hard to find but still relevant
- they have stood the test of time in the SAS community

Please avoid low-value marketing pages, duplicate links to the same content, and thin pages with little technical substance.
