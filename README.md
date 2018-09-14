# :snowflake: :whale: awesome-AI-kubernetes
Tools for AI, DL, ML, CV, DS, Analytics baked in the oven to be Native on [Kubernetes](http://kubernetes.io/)

*"The wind and the waves are always on the side of the ablest navigator."* [Edmund Gibbon, Historian](http://www.seasky.org/quotes/sea-quotes-ocean-ships-sailing.html)

---

For this list, I am focused on AI/ML/Data Science OSS Tools that run in an infinitely scaleable Kubernetes environment. Another list that shares some scaling orchestration resources in a more general way is [Awesome Machine Learning Operations](https://github.com/axsauze/awesome-machine-learning-operations)

You might also be looking for something far less specific and here are some suggestions:

**Kubernetes** 

- a general purpose Kubernetes list, [awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)
- [Awesome Helm](https://github.com/cdwv/awesome-helm)
- [Awesome Operators](https://github.com/operator-framework/awesome-operators)
- [Awesome Docker](https://github.com/veggiemonk/awesome-docker)
- [container-security-awesome](https://github.com/kai5263499/container-security-awesome)
- [Awesome Linux Containers](https://github.com/Friz-zy/awesome-linux-containers)

**Spark**

- [Awesome Spark](https://github.com/awesome-spark/awesome-spark)
- [Awesome Apache Spark Packages](https://github.com/Mageswaran1989/awesome-ApacheSpark-collections)
- [Awesome Scala](https://github.com/lauris/awesome-scala)

**AI/ML**

- [awesome-AIOps](https://github.com/linjinjin123/awesome-AIOps)
- [Awesome Julia](https://github.com/greister/Awesome-Julia)
- [Awesome R](https://github.com/qinwf/awesome-R)
- [Awesome Bioinformatics](https://github.com/shenwei356/awesome/blob/master/bioinformatics.md)
- [Awesome Recurrent Neural Networks](https://github.com/kjw0612/awesome-rnn)
- [Awesome Reinforcement Learning](https://github.com/aikorea/awesome-rl)
- [Awesome Artificial Intelligence](https://github.com/owainlewis/awesome-artificial-intelligence)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [Awesome StarCraft AI](https://github.com/SKTBrain/awesome-starcraftAI)
- [Awesome Quantum Machine Learning](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning)
- [Awesome AI](https://github.com/hades217/awesome-ai)
- [Awesome Feature Engineering for Machine Learning](https://github.com/aikho/awesome-feature-engineering)
- [Awesome WindowsML ONNX Models](https://github.com/ChangweiZhang/Awesome-WindowsML-ONNX-Models)
- [Awesome-ONNX-Models](https://github.com/ChangweiZhang/Awesome-ONNX-Models)
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow)
- [Awesome Blockchain AI](https://github.com/steven2358/awesome-blockchain-ai)
- [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
- [Awesome Deep Learning Resources](https://github.com/guillaume-chevalier/Awesome-Deep-Learning-Resources)
- [awesome-nlp](https://github.com/keon/awesome-nlp)
- [Awesome-Pytorch-list](https://github.com/bharathgs/Awesome-pytorch-list)
- [awesome-ai-services](https://github.com/sekwiatkowski/awesome-ai-services)
- [awesome_list_ai_bot_programming](https://github.com/stuffyjumpy/awesome_list_ai_bot_programming)
- [Machine Learning & Deep Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials)
- [Awesome Machine Learning On Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code)
- [awesome-machine-learning-interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)
- [Awesome Interpretable Machine Learning](https://github.com/lopusz/awesome-interpretable-machine-learning)
- [Awesome-AutoML](https://github.com/hibayesian/awesome-automl-papers)
- [Awesome H2O](https://github.com/h2oai/awesome-h2o)
- [Awesome MXNet](https://github.com/chinakook/Awesome-MXNet)
- [Awesome Bots](https://github.com/hackerkid/bots)
- [Awesome ChatOps](https://github.com/exAspArk/awesome-chatops)



**Other**

- [Awesome Apache Airflow](https://github.com/jghoman/awesome-apache-airflow)
- [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)
- [Awesome-BigData](https://github.com/Harshakvarma/Awesome-BigData)
- [awesome-datasets](https://github.com/datasciencethgrp/awesome-datasets)
- [Awesome Analytics](https://github.com/onurakpolat/awesome-analytics)
- [Awesome Data Science](https://github.com/bulutyazilim/awesome-datascience)
- [Awesome Pipeline](https://github.com/pditommaso/awesome-pipeline)
- [Awesome Nextflow](https://github.com/nextflow-io/awesome-nextflow)
- [awesome-etl](https://github.com/pawl/awesome-etl)
- [Awesome Business Intelligence](https://github.com/thenaturalist/awesome-business-intelligence)



---

**Note:** Although many OSS projects are another octopus arm of mega-tech-corps like Google and Microsoft, we all benefit and in particular many smaller OSS projects represent a lot of volunteer effort by many individuals supporting OSS represented in this list. If you agree and when you can, please consider giving feedback to the authors, perhaps even testing their code and filing issue reports/feature requests and it is pretty easy to hit the Star button for their project. If your favorite project is missing from this list, please let me know.

---

Kubernetes means **Helmsman** and originated with Google's Borg:

> "Its development and design are heavily influenced by Google's Borg system, and many of the top contributors to the project previously worked on Borg. The original codename for Kubernetes within Google was Project Seven, a reference to Star Trek character Seven of Nine that is a 'friendlier' Borg. The seven spokes on the wheel of the Kubernetes logo is a nod to that codename."  https://en.wikipedia.org/wiki/Kubernetes

**Note:** I will attempt to sprinkle in various salty sea references in this document with perhaps some borg ones as well to stay with the spirit of the Kubernetes naming genesis...

### Helmsman of a Great Ship

*"The duties of the ruler are like those of the helmsman of a great ship. From his lofty position, he makes slight movements with his hands, and the ship, of itself, follows his desires and moves. This is the way whereby the one may control the ten thousand and by quiescence may regulate activity."* [Han Fei](https://www.brainyquote.com/quotes/han_fei_875664)

---


# ML designed for Kubernetes (i.e. Native Kube)

*"If you want to build a ship, don't drum up the men to gather wood, divide the work and give orders. Instead, teach them to yearn for the vast and endless sea."* [Antoine de Saint Exupery](https://quotabulary.com/famous-quotes-about-sea-sailing)

---

[Kubeflow](http://kubeflow.org/)  Cloud Native platform for machine learning. https://github.com/kubeflow/kubeflow

[Kubeflow Labs](https://github.com/Azure/kubeflow-labs) Train and Serve TensorFlow Models at Scale with Kubernetes and Kubeflow on Azure

---

[Seldon Core](https://www.seldon.io/) Seldon Core is an open source platform for deploying machine learning models on Kubernetes https://github.com/SeldonIO/seldon-core

---

[Pachyderm](http://pachyderm.io/) Pachyderm is a tool for production data pipelines. If you need to chain together data scraping, ingestion, cleaning, munging, wrangling, processing, modeling, and analysis in a sane way, then Pachyderm is for you. If you have an existing set of scripts which do this in an ad-hoc fashion and you're looking for a way to "productionize" them, Pachyderm can make this easy for you. https://github.com/pachyderm/pachyderm

---

[Fabric for Deep Learning - FfDL, pronounced fiddle](https://developer.ibm.com/patterns/deploy-and-use-a-multi-framework-deep-learning-platform-on-kubernetes/)  Deep Learning Platform offering TensorFlow, Caffe, PyTorch etc. as a Service on Kubernetes. This repository contains the core services of the FfDL (Fabric for Deep Learning) platform. FfDL is an operating system "fabric" for Deep Learning. https://github.com/IBM/FfDL

FfDL is a collaboration platform for:

- Framework-independent training of Deep Learning models on distributed hardware
- Open Deep Learning APIs
- Common instrumentation
- Running Deep Learning hosting in user's private or public cloud

---

[PolyAxon](https://polyaxon.com/) Welcome to Polyaxon, a platform for building, training, and monitoring large scale deep learning applications.Polyaxon deploys into any data center, cloud provider, or can be hosted and managed by Polyaxon, and it supports all the major deep learning frameworks such as Tensorflow, MXNet, Caffe, Torch, etc. Polyaxon makes it faster, easier, and more efficient to develop deep learning applications by managing workloads with smart container and node management. And it turns GPU servers into shared, self-service resources for your team or organization https://github.com/polyaxon/polyaxon

---

[Machine Learning Container Templates](https://github.com/IntelAI/mlt) from [IntelAI](http://ai.intel.com/) - mlt aids in the creation of containers for machine learning jobs. It does so by making it easy to use container and kubernetes object templates.

# ML that is adapted for Kubernetes

*“Impossible” is a word that humans use far too often."* [Seven of Nine](http://quotegeek.com/television-quotes/star-trek-voyager/)

---

[Pipeline.AI](https://github.com/PipelineAI/pipeline) PipelineAI: Real-Time Enterprise AI Platform https://pipeline.ai - Quickstart for Kubernetes: https://github.com/PipelineAI/pipeline/tree/master/docs/quickstart/kubernetes

---

[Helm Charts Apache Kafka](https://github.com/Landoop/kafka-helm-charts) Kubernetes Helm charts for Apache Kafka and Kafka Connect and other components for data streaming and data integration. [Stream-reactor](https://github.com/Landoop/stream-reactor) and Kafka Connectors any environment variable beginning with CONNECT is used to build the Kafka Connect properties file, the Connect cluster is started with this file in distributed mode.

---

[Bigdata Playground](https://github.com/Chabane/bigdata-playground) A complete example of a big data application using : Kubernetes, Apache Spark SQL/Streaming/MLib, Apache Flink, Kafka Streams, Apache Beam, Scala, Python, Apache Kafka, Apache Hbase, Apache Parquet, Apache Avro, Apache Storm, Twitter Api, MongoDB, NodeJS, Angular, GraphQL - The aim is to create a disposable Hadoop/HBase/Spark/Flink/Beam/ML stack where you can test your jobs locally or to submit them to the Yarn resource manager. We are using Docker to build the environment and Docker-Compose to provision it with the required components (Next step using Kubernetes). Along with the infrastructure, We are check that it works with 4 projects that just probes everything is working as expected. The boilerplate is based on a sample search flight web application.

---

[Datalayer](https://github.com/datalayer/datalayer) Big Data Science on Kubernetes in the Cloud. https://datalayer.io Datalayer is building a Simple, Collaborative and Multi Cloud platform for Big Data Scientists. https://docs.datalayer.io 

# Can Spark still be Master of the Sea?


*"Would'st thou," so the helmsman answered, "Learn the secret of the sea? Only those who brave its dangers Comprehend its mystery!"* [Henry Wadsworth Longfellow](http://quotes.yourdictionary.com/helmsman)

```
"Gentile or Jew
 O you who turn the wheel and look to windward,
 Consider Phlebas, who was once handsome and tall as you" 
 ```
 [The Waste Land by T.S. Eliot](https://www.poetryfoundation.org/poems/47311/the-waste-land)

---

**Note:** Kubernetes support was integrated into Spark with the 2.3 release. It is still incomplte and missing several important features, but it is a top priority for the Spark team.

---

[Spark Operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) Kubernetes operator for specifying and managing the lifecycle of Apache Spark applications on Kubernetes. Spark Operator aims to make specifying and running Spark applications as easy and idiomatic as running other workloads on Kubernetes. It uses Kubernetes custom resources for specifying, running, and surfacing status of Spark applications. For a complete reference of the custom resource definitions, please refer to the API Definition. For details on its design, please refer to the design doc. It requires Spark 2.3 and above that supports Kubernetes as a native scheduler backend.

---

[Multi cloud Spark application service on PKS](https://github.com/SnappyDataInc/spark-on-k8s) An Integrated and collaborative cloud environment for building and running Spark applications on PKS/Kubernetes. This project provides a streamlined way of deploying, scaling and managing Spark applications. Spark 2.3 added support for Kubernetes as a cluster manager. This project leverages Helm charts to allow deployment of common Spark application recipes - using Apache Zeppelin and/or Jupyter for interactive, collaborative workloads. It also automates logging of all events across batch jobs and Notebook driven applications to log events to shared storage for offline analysis. This project is a collaborative effort between SnappyData and Pivotal.

---

[Sparknetes](https://github.com/hypnosapos/sparknetes) Spark on kubernetes. Based on official documentation of spark 2.3 at https://spark.apache.org/docs/2.3.0/running-on-kubernetes.html

---

[HDFS on Kubernetes](https://github.com/apache-spark-on-k8s/kubernetes-HDFS) Repository holding helm charts for running Hadoop Distributed File System (HDFS) on Kubernetes. See [charts/README.md](https://github.com/apache-spark-on-k8s/kubernetes-HDFS/blob/master/charts/README.md) for how to run the charts. See [tests/README.md](https://github.com/apache-spark-on-k8s/kubernetes-HDFS/blob/master/tests/README.md) for how to run integration tests for HDFS on Kubernetes.

---

[Apache Spark Helm Chart](https://github.com/helm/charts/tree/master/stable/spark) This chart will do the following:
- 1 x Spark Master with port 8080 exposed on an external LoadBalancer
- 3 x Spark Workers with HorizontalPodAutoscaler to scale to max 10 pods when CPU hits 50% of 100m
- 1 x Zeppelin with port 8080 exposed on an external LoadBalancer
- All using Kubernetes Deployments

---

[Helm Chart for Spark Operator](https://github.com/helm/charts/tree/master/incubator/sparkoperator) This is the Helm chart for the Spark-on-Kubernetes Operator. Prerequisites: The Operator requires Kubernetes version 1.8 and above because it relies on garbage collection of custom resources. If customization of driver and executor pods (through mounting custom configMaps and volumes) is desired, then the Mutating Admission Webhook needs to be enabled and it only became beta in Kubernetes 1.9.

The chart can be installed by running:
```
$ helm repo add incubator http://storage.googleapis.com/kubernetes-charts-incubator
$ helm install incubator/sparkoperator
```
By default, the operator is installed in a namespace called "spark-operator". It would be created if it does not exist.

---

[Kubernetes official examples](https://github.com/kubernetes/examples/tree/master/staging/spark) - (Not up to date) Following this example, you will create a functional Apache Spark cluster using Kubernetes and Docker. You will setup a Spark master service and a set of Spark workers using Spark's standalone mode [Spark on GlusterFS example](https://github.com/kubernetes/examples/tree/master/staging/spark/spark-gluster) (Also, not up to data) This guide is an extension of the standard Spark on Kubernetes Guide and describes how to run Spark on GlusterFS using the Kubernetes Volume Plugin for GlusterFS - The setup is the same in that you will setup a Spark Master Service in the same way you do with the standard Spark guide but you will deploy a modified Spark Master and a Modified Spark Worker ReplicationController, as they will be modified to use the GlusterFS volume plugin to mount a GlusterFS volume into the Spark Master and Spark Workers containers. Note that this example can be used as a guide for implementing any of the Kubernetes Volume Plugins with the Spark Example. There is also a [video available](https://youtu.be/xyIaoM0-gM0) that provides a walkthrough for how to set this solution up






# Spark on OKD

[Rad Analytics Spark Operator](https://github.com/radanalyticsio/spark-operator) ConfigMap and CRD based approach for managing the Spark clusters in Kubernetes or OpenShift.

---

[OpenShift Spark](https://github.com/radanalyticsio/openshift-spark) This repository contains several files for building Apache Spark focused container images, targeted for usage on OpenShift Origin. [tutorial-sparkpi-java-vertx](https://github.com/radanalyticsio/tutorial-sparkpi-java-vertx) A Java implementation of SparkPi using Vert.x 3 - This application is an example tutorial for the radanalytics.io community. It is intended to be used as a source-to-image (s2i) application.

# Some Utils and Accessories


---

[Helm Chart for Elastic-Fluentd-Kibana logging](https://github.com/cdwv/efk-stack-helm) Helm chart to deploy a working logging solution using the ElasticSearch - Fluentd - Kibana stack on Kubernetes


---

[Draft](https://draft.sh/) A tool for developers to create cloud-native applications on Kubernetes https://github.com/Azure/draft Draft makes it easier for developers to build applications that run on Kubernetes by doing two main things:
- The draft create command gives developers the artifacts they need to build and run their applications in Kubernetes
- The draft up command builds the container image for an application and deploys it to Kubernetes

[Draft Pack Repository Plugin](https://github.com/draftcreate/draft-pack-repo) Draft Pack Repository Plugin (or draft pack-repo for short) enables users to fetch, list, add and remove pack repositories to bootstrap all of their internal and external projects. It is incredibly opinionated on how to fetch, list, add and remove these repositories whereas Draft core does not care about these concepts.  This also enables the Draft community to come up alternative forms of pack repositories by implementing their own plugin for fetching down these packs, so it made sense to initially spike the tooling as an entirely separate project.

---

# The Other Category

---

[podder-ai](https://github.com/podder-ai) has some tangentialy conncected material that appears to be working towards a coherent Kubernetes ML system. [Kubeb](https://github.com/podder-ai/kubeb) Kubeb (Cubeb or Cubeba) provide CLI to build and deploy a web application to Kubernetes environment Kubeb use Docker & Helm chart for Kubernetes deployment [pipeline-framework](https://github.com/podder-ai/pipeline-framework) pipeline-framework is a platform to schedule and monitor workflows based on [Apache Airflow](https://airflow.apache.org/) [pipeline-generator](https://github.com/podder-ai/pipeline-generator) Generator code for pipeline-framework. [pipeline-framework-sample](https://github.com/podder-ai/pipeline-framework-sample) This is sample project of pipeline-framework, started from pipeline-generator, and sample task is based on poc-base-sample.[poc-base-sample](https://github.com/podder-ai/poc-base-sample)Sample task implementation for Podder.ai pipeline framework. How to implement a task using poc-base repository [poc-base](https://github.com/podder-ai/poc-base) Boilerplate project for creating python task using the Pipeline-framework.

---

