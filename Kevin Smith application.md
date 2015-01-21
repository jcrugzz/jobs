Kevin "Schmidty" Smith
----------------------
I originally attended Cal Poly San Luis Obipso for a computer science major, but discovered that if
you only show up to your programming classes, they eventually get sick of you and kick you out. My
experimentation since then was originally focused on python, but as I became more interested in
frameworks like `twisted` I realized that javascript and Node.js was what I really wanted to learn.
Somehow I have always focused too much on diving deep into a server-side engineering problem to
produce many projects that could be assembled into a believable job application.

Since becoming interested in javascript I began to do more visible work. I wrote a chrome browser
extension for message encryption and client-secured cryptographic sessions. I hacked up a web
framework and partially prototyped a complicated social networking site. I also took up fencing and
got good enough at it to work as a coach.

In January 2014 I thought I had caught my break. The father of one of my young fencing students
recommended me to a developer position with the Fiehn Lab at UCDavis. I was hired as a full-stack
developer: Node.js backed by MongoDB, with native javascript on the client, working alone. In the
first month I implemented (in Node) a batching server which indexed the location of kilotons of lost
files, called out for groups of filenames related to a "study id" and streamed these file batches
out as gzipped tarballs. My other assignment was only carried to the prototype stage due to budget
problems.

The lab was participating in several enormous external studies and persuant to this we were
preparing to take inventory of thousands of pages of final results being sent in by collaborating
labs. As part of our grant we were required to produce a method for curating these results, and the
PI took the problem pretty seriously. Unfortunately, the graduate students doing most of the daily
work lose their taste for rigour by the hundredth time they have to fill out the same endless
questionaire.

I therefor needed a system which would organize data entry for groups of related items. This system
had to produce arbitrarily-searchable data on a curated/redactable final set. I was supposed to
support "up to a thousand people" and index millions of records, but without needing appreciable
money to operate or more than 6U on the overstrained racks. As for overall configurability, I was
told that "we have no idea how we will be doing any of this in ten years."

At the end of six months I produced a prototype called SALAAM - Spectrum Analysis Laboratory Access
And Management. This system was a node-webkit application and less-featureful webapp which managed a
hierarchy of realtime-collaboratively-editable nodes of JSON data. Data inherited leafward, allowing
information relevant to subsections of an experiment to effortlessly flow toward the appropriate
result documents. For data enforcement and curation purposes, these nodes could contain schema nodes
which could fill and/or restrict keys in leafward children.

An additional tool allowed the configuration of simplified input interfaces for accepting uploads
from collaborating labs. Uploaded and lightly configured files were assigned to be children of a
configured node, automatically inheriting more information. If all relevant schema were met and, a
record's inherited data was fully compiled and projected into the final result set.

The prototype was rushed and architecturally indefensible, but I'm proud to say I met the entire
feature list. I even made [these cute icons](http://i.imgur.com/A7xqsWT.png) for the tree nodes,
many of which aren't even hideous. Unfortunately I was still told that money could not be found to
cover my position.

Since losing that job I have sought to assemble a better portfolio while applying lessons learned in
developing SALAAM. It is my continuing goal to engineer the next generation of high-performance
webapps in Node.js and MongoDB.

Open Source Contributions
=========================
 * SALAAM/NAMES-DB was to be released under gplv3
 * [Contributed to forever-monitor](https://github.com/foreverjs/forever-monitor/pull/70) in my first ever github pull request.
 * [mingydb](https://github.com/shenanigans/node-mingydb) fully-automatic minification layer for MongoDB.
 * [fauxmongo](https://github.com/shenanigans/node-fauxmongo) reference implementation for MongoDB. Applies database operations to local documents.
 * [doczar](https://github.com/shenanigans/node-doczar) documentation generator for Node.js and beyond.
 * [cachew](https://github.com/shenanigans/node-cachew) simple caching primitives.

Upcoming Releases
=================
 * [likeness](https://github.com/shenanigans/node-likeness) JSON validation and transform library.
 * `waxwork` backwards-and-forwards ODM. A Mongoose alternative. This lib was the reason for creating `fauxmongo` and `likeness`.
 * `substation` webapp framework. Obfuscates REST and Socket.io onto a unified set of handler scripts.

The Future
==========
Although I'm comfortable building up a project independently, I'm getting pretty tired of working
alone *all the time.* It would be **extremely** exciting to collaborate with other passionate
engineers. I especially look forward to working with a team that has deep knowledge and experience I
can ~~steal~~ benefit from as a developer.

Much as I believe in my work, I don't want to create a private Schmidtyverse. Node is an open tool
and its greatest strength is its community. The best way for me to respect the work on which mine
relies is to engage that community, cooperate, and hopefully build something "bigger than all of
us."
