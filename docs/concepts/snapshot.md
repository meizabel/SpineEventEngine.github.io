---
title: Snapshot
headline: Snapshot
bodyclass: docs
layout: docs
sidenav: doc-side-concepts-nav.html
type: markdown
---
<h2 class="top">Snapshot</h2> 

Snapshot is a state of an Aggregate. A snapshot ”sits” in between events in the history.
 
`AggregateStorage` reads events backwards until encounters a snapshot, applies it to the Aggregate, and plays trailing events.