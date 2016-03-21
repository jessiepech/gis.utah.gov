---
layout: post
status: publish
published: true
title: Updates To Political Districts & Voting Precincts datasets April 2015
author:
  display_name: mheagin
  login: mheagin
  email: mheagin@utah.gov
  url: ''
author_login: mheagin
author_email: mheagin@utah.gov
wordpress_id: 17286
wordpress_url: http://gis.utah.gov/?p=17286
date: '2015-04-29 14:16:45 -0600'
date_gmt: '2015-04-29 20:16:45 -0600'
categories:
- Data
- SGID Blog
- Standards
tags: []
---
<p><strong>Utah Political Districts:</strong></p>
<p><a href="{{ "/data/political/2012-2021-house-senate-congressional-districts/" | prepend: site.baseurl }}">Political districts for state-level offices</a> (Congressional, State House, State Senate, and State Board of Education) are available as a GIS data layers. These districts are for elections and ongoing representation.</p>
<p>The updated political district boundaries, originally formed from 2010 Census Block files have been adjusted by AGRC, working together with the Utah Legislature, the Lt. Governor's Elections Office and the County Clerks' offices to increase the geographic accuracy.</p>
<p>Specifically, </p>
<ol>
<li>County Boundary lines between Salt Lake and Summit, in the Parleys Summit area were adjusted to fit a subdivision in Summit County ;</li>
<li>The U. S. Congress Districts 1 and 2 boundaries were adjusted to fit the Country Boundary in that same area;</li>
<li>The Utah Senate Districts 2 and 19 boundaries were adjusted to fit the Country Boundary in that same area</li>
</ol>
<p><strong>New Utah Voting Precincts:</strong></p>
<p><a href="{{ "/data/political/voter-precincts/" | prepend: site.baseurl }}">Political.VistaBallotAreas, a statewide GIS data layer</a> depicting voting precinct and subprecinct boundaries is also available. This dataset is compiled from the County Clerks and is actively used in the 26 of 29 counties that have adopted a GIS-based process to manage precinct-to-residence assignment within VISTA, the statewide voter registration database.</p>
<p>Precincts can be formed (and subprecinct divisions eliminated) by performing a gis 'dissolve' operation on the Precinct field. This dataset has not yet been edited to eliminate very small gap and overlap slivers and or to align to the highest resolution of the county boundaries.</p>
<p>Utah is one of only several states to integrate GIS functionality into elections management, a task that requires data standards, coordination, and geospatial services and infrastructure for accurately locating addresses and making spatial queries.</p>
<p>This dataset is expected to change annually as counties need to realign precincts to agree with local boundary changes and to divide precincts whose voter count grows over the course of the year to exceed the maximum number of voters allowed per precinct (currently 1250 voters) <strong>Current data has been updated through April 29, 2015.</strong></p>