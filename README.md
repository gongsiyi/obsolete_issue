# The Pollution from Obsolete Issue Report: An Empirical Study

## Project summary

In software development, programmers use issue trackers to manage their maintenance issues and record valuable maintenance details into issue reports. Based on these issue reports, programmers have enhanced code comprehension and researchers have mined knowledge from issue reports to assist various programming tasks. Although issue reports are useful, some of them can be obsolete, in that their corresponding commits are overwritten or rolled back, with the evolution of software. The obsolete issue reports can invalidate their references and descriptions, and can have far-reaching impacts on the approaches built on them. 

To explore the distributions and the impacts of obsolete issue reports, we conduct the first empirical study to analyze obsolete issue reports. We call an issue report as obsolete one if its revisions are partially or totally removed in later commit. To measure how an issue report becomes obsolete, we define an obsolete ratio of an issue report as its deleted lines over all its modified lines. 

In this paper, we build a tool, ICLINKER, to inspect the obsolete issue reports and calculate the obsolete ratios. With ICLINKER, we analyze 70,180 commits and 46,257 issue reports that are collected from five Apache projects. Taking them as our inputs, we explore four research questions, which concern the distributions of obsolete issue reports, the impacts of programmers on obsolete ratios, the impacts of obsolete issue attributes, and the obsolete references in code comments. Our findings to these research questions enrich the knowledge on obsolete issue reports, and some are even counterintuitive. For example, we find that obsolete issue reports are mixed with other issue reports. Even recent issue reports can be obsolete, while some old issue reports keep up-to-date. As the first study on obsolete issue reports, we further analyze some directions that are worthy of more explorations.

## Our identified obsolete ratios

We identified the obsolete ratios of the issue reports from five projects. Their obsolete ratios are as follows: 
[calcite](https://github.com/gongsiyi/obsolete_issue/blob/main/calcite.txt), [cassandra](https://github.com/gongsiyi/obsolete_issue/blob/main/cassandra.txt), [derby](https://github.com/gongsiyi/obsolete_issue/blob/main/derby.txt), [hbase](https://github.com/gongsiyi/obsolete_issue/blob/main/hbase.txt), and [hive](https://github.com/gongsiyi/obsolete_issue/blob/main/hive.txt).


