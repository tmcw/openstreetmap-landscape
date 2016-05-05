# openstreetmap-landscape

Writing about mapping is like dancing about architecture.

---

Herein lies a summary of OpenStreetMap, from my perspective, unavoidably including some of my own insights, but not primarily a piece of opinion but just of writing lots of context quickly. Here goes.

## Organizations

**OpenStreetMap Foundation** The closest organization to OpenStreetMap is the OpenStreetMap Foundation, but it is relatively laissez-faire: the Foundation holds the trademark and the database rights to the dataset, manages 'working groups' and helps manage the membership. The Foundation does not directly support any software development.

**Humanitarian OpenStreetMap Team (HOT)** HOT was founded around the Haiti earthquake and represents one of the bastions of the humanitarian angle of OpenStreetMap. It's relatively well-run, as a 503c with a continuous board of directors. HOT also sponsors a great deal of software development in the service of its efforts. HOT is very interested in the "mapping party" idea, and mapping as a response to disasters.

**American Red Cross**: The Red Cross does a lot of different things, but OSM is a big effort: the Red Cross both sponsors mapping parties (like HOT) and it assists with software development, especially for tools that are useful for disaster situations, like offline mapping or task-specific editors.

## Companies

**CloudMade** was the first instance of building a company around OpenStreetMap: it included Steve Coast, the founder of OpenStreetMap, and they built specialized editors and services around OSM maps. The company eventually pivoted and no longer focuses on that kind of work.

**Mapbox** is a current effort to build a company around OpenStreetMap, open source, open data in general. Disclosure: I work there. Mapbox used Knight Foundation grants to build a redesign of osm.org and build iD, the default web editor for OpenStreetMap. It now uses its SaaS business to justify more work on OSM.

**Maps.me** is a consumer application built around OpenStreetMap, based in Moscow. They develop an open-source rendering engine and an offline map application, that recently grew to include an OSM editor that has had early success boosting the popularity of editing OpenStreetMap.

**Development Seed** is a company that was previously joined with Mapbox that builds around open source and open data. Disclosure, I used to work there. Development Seed is often involved in the implementation of tools for the Red Cross and others.

**Stamen** is a company that does projects similar to Development Seed as well as Knight Foundation projects, and has been involved in building OpenStreetMap-associated technology like Cascadenik.

**Mapzen** is an open-source mapping lab based out of the Samsung Accelerator. It sponsors the development of several open source projects related to OpenStreetMap, like geocoding, rendering, and routing engines.

## Informal groups

**osmlab** is a GitHub organization that's an anarchic alternative to the OpenStreetMap organization, with liberal membership rules. It has no formal governance or topic, other than an association with OpenStreetMap.

**osmcode** is a group of GitHub projects mainly led by Jochen Topf, a talented developer who works on low-level OpenStreetMap-related tools, especially for processing data.

## Software

The OpenStreetMap website is written with Ruby on Rails. OpenStreetMap data is stored in Postgres and PostGIS.

There are many editors that connect to OpenStreetMap via its API, which is partially written in C++ for performance.

OpenStreetMap provides many different kinds of data exports, through planet.openstreetmap.org as well as 'replication feeds' that allow other websites to create mirrors of its data in near realtime. Third parties build additional layers on top of these feeds to reprocess and extract different views of the data.

## Buzzwords

**Armchair mapping** is mapping places where you aren't - it is said in contrast to _surveying_, where you travel to the places you map. Armchair mapping is fueled by the availability of satellite imagery, street photos, historical, and government sources. It is almost necessary for large and sparse countries but limited in granularity since some details aren't visible from above.

**Imports** are when large existing datasets are loaded into OpenStreetMap. The earliest edits were all by hand, and this human pace of addition often leads to fewer systematic errors. Imports have been helpful in getting large, sparse countries on the map, but are controversial for quality problems.

**ODbL** is the license for OpenStreetMap data. It is an alternative to the conventional terms of copyright: instead of maintaining exclusive ownership, it mandates that data is shared. ODbL is the second license used by OpenStreetMap, after Creative Commons. When the project switched licenses, users needed to agree on the switch, and when some opted-out their data needed to be removed from the map.

## Countries

UK: OpenStreetMap started in the UK with Steve Coast. It was motivated by the UK's government mapping service, Ordnance Survey: Ordnance Survey used taxes to map the country but sold the maps back to citizens. The map in the UK was seeded by taxi GPS traces and has been predominently built through survey, rather than armchair mapping.

US: OpenStreetMap in the US had a large event of the TIGER import. Unlike the Ordnance Survey, America had an open and compatible data source called the TIGER/line dataset. This data was imported en masse to America, which led to a quick buildup in coverage, but the import had quality problems that took years to fix.

## Places people hang out

**[User Diaries](http://www.openstreetmap.org/diary)** are traditional blog-format posts built into OpenStreetMap itself. They're usually used for announcements or reports from mapping parties or other events.

**[Mailing lists](https://lists.openstreetmap.org/listinfo)** are the oldest form of OpenStreetMap communication. Most popular is the `talk` list. Mailing lists have the highest level of pedantry of any form of communication.

**[The OpenStreetMap Forum](http://forum.openstreetmap.org/)** is usually forgotten by English-language users of OpenStreetMap but is popular in other languages.

**[IRC](http://wiki.openstreetmap.org/wiki/IRC)** is like the mailing lists - it features a lot of old-timers and a lot of snark - but is faster and less restrained.

**[OpenStreetMap Help](https://help.openstreetmap.org/)** is similar to StackOverflow but only for OpenStreetMap. It's the best place to get questions answered.
