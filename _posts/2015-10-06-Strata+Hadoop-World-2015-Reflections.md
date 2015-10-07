---
layout: post
title: Strata+Hadoop World NYC 2015 Reflections
---
Machine learning, cloud, visualization, hadoop, spark, data science, scalability, analytics, terabytes, petabytes, faster, bigger, more secure, simply better. The kind of a merry-go-round that keeps spinning in your head after you spend three days on the exhibit floor at Strata+Hadoop conference. And lots of elephants, of course.

Not only did we attend Strata with fellow colleagues from [DataArt](http://dataart.com) and [DeviceHive](http://devicehive.com), we also helped our friends at Canonical and brought our demo to their booth. Canonical was showing [Juju](http://jujucharms.com): a cloud infrastructure and service management tool. We brought our favorite demo: industrial equipment monitoring rig. No PowerPoint slides, only real stuff. A Texas Instruments SensorTag's accelerometer attached to a fan to monitor its vibration. To simulate the vibration we used a piece of duct tape attached to one of the blades to set the whole thing off balance. Sensor data was streamed using [DeviceHive](http://devicehive.com), generating time series data, which was aggregated by Spark Streaming and displayed on a nice dashboard. Everything deployed using Juju, working nicely in AWS.

While the exhibition floor had a lot of great companies pitching their awesome products, I think the main highlight of this year's event was [Spark](http://spark.apache.org). Learning Spark, running Spark, managing Spark, using Spark for this and using Spark for that. Almost everyone, big or small, was talking Spark, integrating it into their solutions or making their data accessible through Spark. In just a few years Spark has proven to be a great platform for data discovery, machine learning and cluster computing in general. Spark ecosystem will keep expanding, changing the way we work with our data, increasing velocity of data-related projects. Next generation analytics tools will surely interface with Spark or rely on Spark, allowing enterprises to push the envelope of what can be derived from their data. Next generation parallel computing tools will bring business, engineers, data scientists and devops closer together.

[Databricks](http://databricks.com) a company commercially supporting Spark, was demonstrating their data analytics product which allowed to create research notebooks and interactively write Spark jobs, run them on AWS cluster, create queries and visualize data. On top of that add Spark Streaming and you can execute your models on a live stream of data. While Databricks is hosting the landing page for the UI, your data as well as the machine to host the infrastructure to run Spark resides in your AWS environment. I'm curious to know how it will compare with Amazon's Space Needle they are unveiling at re:Invent 2015 in Las Vegas. 

Besides Spark, it is also becoming apparent, that working with data at large is no longer about a particular choice of a right database or distributed filesystem. Data platforms are coming. The world is starting to think in terms of data platforms: a set of technologies and architecture patterns designed to work together to solve a variety of data-related problems. Data platform largely defines how we access, store, stream, compute and search structured, unstructured, sensor generated data. A solid example of such a platform is [Basho Data Platform](http://basho.com/basho-data-platform/) where Basho is taking its Riak database and making it a part of something much bigger than a Key-Value store.

Personal improvement takeaways:

- Hack on public data in Spark
- Keep learning and using Scala
- Functional programming
- Functional programming
- Functional programming
