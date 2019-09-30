Assignment
==========

_Goal_ – How many will attend? -- Predicting Event Attendance

Attached is a small dataset of Meetup events (“cancelled”, “past”,
“upcoming”) from 2018/09/25 through 2018/12/31. The goal of this task is
to predict – How many “yes” rsvps will an event get? In other words we
want to learn how many users are likely to attend the future events?

Predicting event attendance in event-based social networks is an
interesting research challenge focused towards social event scheduling
that analyzes social event participation. There are variety of factors
that may influence attendance - such as event’s content, context, social
factors, past group attendance, other meta-attributes including temporal
and spatial features.

This is a deliberately open-ended problem and doesn’t have a single
solution. For instance, one way to frame the problem is - if there’s a
high participation for events related to a topic, there may also be
higher attendance for future events related to this topic. There may
also be cases where high attendance is correlated to specific derived
features for example if an event offers “free food” or “open bar”
mentions in event description.

We mainly wish to see how you approach the problem given this data and
in the allotted time; and the steps you took for evaluating to your
solution.

Questions to answer:
====================
1\. What is the basic idea or intuition to frame “How many will attend?”
problem

2\. Describe your approach – incl. steps taken for data preparation,
modelling and evaluation.

3\. If you’d like to show us a visualization for exploring the dataset or
an interesting case study, you could do that.

4\. If you were unable to complete your code in the allotted 2-3 hours,
please describe what more you originally intended to implement.

5\. If you had a few weeks(say 4-8) to do this task, what other
approaches would you try and implement for this problem?

_Datafile_: meetup-events-20180925\_20181231.tsv.gz

Dataset description:
====================
The dataset is provided in the form of a tsv file containing 54850
events spread over 5590 Meetup groups. The data is utf-8 encoded. The
first line contains the column headers. For detailed description of
fields (columns) please refer to
<https://www.meetup.com/meetup_api/docs/:urlname/events/#list>

Note that the field – “yes\_rsvp\_count” indicates event participation.

Submission
==========
Please submit all your code and any answer documents/Readmes as a
compressed attachment (zip) in this email thread
