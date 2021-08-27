# Responsible AI repository
Repo to capture relevant information and developments in the field of Responsible AI
=======
# Responsible-AI-wiki

A repo for a curated, but incomplete, overview of what we're [reading](#reading), [listening](#other) to, [using](#using) and [creating](#creating) related to Responsible AI.

<a name="creating"></a>
## Creating

### Responsible AI webinar series

An in-depth webinar series about the responsible use and application of AI. In this series, various invited speakers will discuss a range of topics related to the ethical, accountable, and/or sustainable use of AI. Xomnia teams up with partners, experts, and guest speakers to cover a broad range of expertise and perspectives on the field. The series aims to contribute to issues identified at various levels within companies, ranging from individual employees to data science and business teams, to boardroom meetings.

The aim is to inform, educate and support anyone who is interested in Responsible AI, by offering an overview of cutting-edge tools, methods, best practices, and lessons learned, spreading the knowledge of how to apply AI more responsibly starting now.

| Date | Topic | Description | Speakers | Link (inc recap) |
| --- | --- | --- | --- | --- |
| 2020-11-18 | Responsible IT | An overview of what we actually mean by "Responsible AI" | Nanda Piersma | https://www.xomnia.com/event/responsible-it/ |
| 2020-12-10 | Sustainable & Climate AI | We will once again dive into the sustainability theme! With Lucia Loher, Product Lead at Jina AI, and Ricardo Vinuesa, who is an Associate Professor and Affiliated Researcher in the AI Sustainability Center at KTH Royal Institute of Technology. | Lucia Loher, Ricardo Vinuesa | https://www.xomnia.com/event/sustainable-climate-ai/ |
| 2021-01-21 | Meaningful human control of AI | About AI systems that play a role in tasks that clearly contain ethical challenges. | Marc Steen, Jurriaan van Diggelen | https://www.xomnia.com/event/ai-trough-meaningful-human-control/ |
| 2021-02-10 | Sustainable & Climate AI | An appeal for sustainable AI and how we can contribute | Angela Fan, Peter van de Putten, Jeroen van der Most | https://www.xomnia.com/event/sustainable-and-climate-ai/ |
| 2021-04-15 | Ethics in Data Projects | Ethics in the design of data products and intelligent technology | Chris Detweiler, Stan Guldemond | https://www.xomnia.com/event/ethics-in-data-projects/ |
| 2021-05-20 | AI risk assessment | AI risk assessment and management in high-risk applications | Alexander Boer, Mark Roboff | https://www.xomnia.com/event/ai-risk-assessment-and-management-in-high-risk-applications/ |
| 2021-06-10 | Fair and Explainable AI | Fair and explainable AI | Hilde Weerts, Jasper van der Waa | https://www.xomnia.com/event/fair-and-explainable-ai/ |
| 2021-07-08 | AI and systems regulations | An introduction to to the proposal of an EU AI regulation and the challenges of AI optimization of new energy systems. | Joas van Ham, Pallas Agterberg | https://www.xomnia.com/event/responsible-ai-webinar-ai-and-systems-regulations/ |

<a name="reading"></a>
## Reading

### Literature

### Articles

### Blogs

<a name="using"></a>
## Using

### Tooling

####Accountable, robust, secure, reproducible, privacy-aware AI tooling
Also check out: https://github.com/EthicalML/awesome-production-machine-learning

__Responsible ML (Azure)__

https://azure.microsoft.com/en-us/services/machine-learning/responsibleml/#overview

_TO EXPAND!_

__Sagemaker pipelines (Amazon)__

https://aws.amazon.com/sagemaker/pipelines/

* purpose-built, easy-to-use continuous integration and continuous delivery (CI/CD) service for machine learning. Workflows can be shared and re-used between teams. Create, automate, and manage end-to-end ML workflows at scale.
* Automate different steps of the ML workflow, including data loading, data transformation, training and tuning, and deployment. With SageMaker Pipelines, you can build dozens of ML models a week, manage massive volumes of data, thousands of training experiments, and hundreds of different model versions. You can share and re-use workflows to recreate or optimize models, helping you scale ML throughout your organization.
* Create an audit trail of model components such as training data, platform configurations, model parameters, and learning gradients. Audit trails can be used to recreate models and help support compliance requirements.

__Mlflow__

https://mlflow.org/

MLflow is an open source platform for managing the end-to-end machine learning lifecycle. It tackles four primary functions:
* Tracking experiments to record and compare parameters and results (MLflow Tracking). The MLflow Tracking component is an API and UI for logging parameters, code versions, metrics, and output files when running your machine learning code and for later visualizing the results. MLflow Tracking lets you log and query experiments using Python, REST, R API, and Java API APIs.
* Packaging ML code in a reusable, reproducible form in order to share with other data scientists or transfer to production (MLflow Projects). An MLflow Project is a format for packaging data science code in a reusable and reproducible way, based primarily on conventions. In addition, the Projects component includes an API and command-line tools for running projects, making it possible to chain together projects into workflows. 
* Managing and deploying models from a variety of ML libraries to a variety of model serving and inference platforms (MLflow Models). An MLflow Model is a standard format for packaging machine learning models that can be used in a variety of downstream tools—for example, real-time serving through a REST API or batch inference on Apache Spark. The format defines a convention that lets you save a model in different “flavors” that can be understood by different downstream tools.
* Providing a central model store to collaboratively manage the full lifecycle of an MLflow Model, including model versioning, stage transitions, and annotations (MLflow Model Registry).  The MLflow Model Registry component is a centralized model store, set of APIs, and UI, to collaboratively manage the full lifecycle of an MLflow Model. It provides model lineage (which MLflow experiment and run produced the model), model versioning, stage transitions (for example from staging to production), and annotations.

MLflow is library-agnostic. You can use it with any machine learning library, and in any programming language, since all functions are accessible through a REST API and CLI. For convenience, the project also includes a Python API, R API, and Java API.

__TensorBoard__

https://www.tensorflow.org/tensorboard 

TensorBoard: TensorFlow's visualization toolkit. TensorBoard provides the visualization and tooling needed for machine learning experimentation:
* Tracking and visualizing metrics such as loss and accuracy
* Visualizing the model graph (ops and layers)
* Viewing histograms of weights, biases, or other tensors as they change over time
* Projecting embeddings to a lower dimensional space
* Displaying images, text, and audio data
* Profiling TensorFlow programs

__Adversarial robustness toolbox (IBM)__

https://adversarial-robustness-toolbox.readthedocs.io/en/latest/

https://github.com/Trusted-AI/adversarial-robustness-toolbox

Adversarial Robustness Toolbox (ART) is a Python library for Machine Learning Security. ART provides tools that enable developers and researchers to defend and evaluate Machine Learning models and applications against the adversarial threats of Evasion, Poisoning, Extraction, and Inference. ART supports all popular machine learning frameworks (TensorFlow, Keras, PyTorch, MXNet, scikit-learn, XGBoost, LightGBM, CatBoost, GPy, etc.), all data types (images, tables, audio, video, etc.) and machine learning tasks (classification, object detection, speech recognition, generation, certification, etc.).
 
__Neptune.AI__

https://neptune.ai/product

Metadata store for MLOps, built for research and production teams that run a lot of experiments. ML metadata store is an essential part of the MLOps stack that deals with model building metadata management. It makes it easy to log, store, display, organize, compare and query all metadata generated during ML model lifecycle. 
Experiment and model training metadata. You can log anything that happens during ML run.
Artifact metadata. For datasets, predictions or models you can log things like paths to dataset, dataset hash, feature column names, who created / modified + timestamps
Model metadata. For trained models (production or not) you can log things such as model binary or location to model asset, dataset version, links to recorded model training runs and experiments, model descriptions and so on.
You can use the metadata store to track your experiments, register your models, and more.

__Weights and Biases (WANDB)__

https://wandb.ai/

1.	Integrate quickly: Track, compare, and visualize ML experiments with 5 lines of code. Free for academic and open source projects.
2.	Visualize Seamlessly: Add W&B's lightweight integration to your existing ML code and quickly get live metrics, terminal logs, and system stats streamed to the centralized dashboard.
3.	Collaborate in real time: Explain how your model works, show graphs of how model versions improved, discuss bugs, and demonstrate progress towards milestones.
4.	Track, compare, and visualize with 5 lines of code: Add a few lines to your script to start logging results. Our lightweight integration works with any Python script.
5.	Visualize everything you are doing: See model metrics stream live into interactive graphs and tables. It is easy to see how your latest model is performing compared to previous experiments, no matter where you are training your models.
6.	Quickly find and re-run previous model checkpoints. Save everything you need to reproduce models later— the latest git commit, hyperparameters, model weights, and even sample test predictions. You can save experiment files and datasets directly to W&B or store pointers to your own storage.
7.	Monitor your CPU and GPU usage. Visualize live metrics like GPU utilization to identify training bottlenecks and avoid wasting expensive resources.
8.	Debug performance in real time. See how your model is performing and identify problem areas during training. We support rich media including images, video, audio, and 3D objects.

__Polyaxon__

https://polyaxon.com/features/

Polyaxon Features. Build, monitor, deliver and scale machine learning experiments — we're the easiest way to go from an idea to a fully deployable model, bypassing all those infrastructure headaches. A Platform for reproducible and scalable Machine Learning and Deep Learning applications. Learn more about the suite of features and products that underpin today's most innovative platform for managing data science workflows.

__ClearML__

https://www.allegro.ai/

https://clear.ml/

Experiment, orchestrate, deploy, and build data stores, all in one place. Manage all your MLOps in a unified and robust platform providing collaborative experiment management, powerful orchestration, easy-to-build data stores, and one-click model deployment. Log, share, and version all experiments and instantly orchestrate pipelines.
* built-in orchestration
* artifact and model tracking
* build, reuse and reproduce pipelines
* automate and save time
* track, log, compare, visualize, reproduce, collaborate and manage experiments.

__Comet__

https://www.comet.ml/site/data-scientists/

Track your datasets, code changes, experimentation history, and models. Comet provides insights and data to build better models, faster while improving productivity, collaboration and explainability.
* compare experiments—code, hyperparameters, metrics, predictions, dependencies, system metrics, and more—to understand differences in model performance. 
* flexible experiments and visualization suite that allows you to record, transform, compare and visualize any artifact from your code, computer or environment. 
* View, analyze, and gain insights from your model predictions. Visualize samples with dedicated modules for vision, audio, text, and tabular data to detect over-fitting and easily identify issues with your dataset. 
* Register and keep track of all of your models, all from a single location. 

__Sacred__

https://github.com/IDSIA/sacred

Sacred is a tool to help you configure, organize, log and reproduce experiments. It is designed to do all the tedious overhead work that you need to do around your actual experiment in order to:
1.	keep track of all the parameters of your experiment
2.	easily run your experiment for different settings
3.	save configurations for individual runs in a database
4.	reproduce your results
Sacred achieves this through the following main mechanisms:
1.	ConfigScopes A very convenient way of the local variables in a function to define the parameters your experiment uses.
2.	Config Injection: You can access all parameters of your configuration from every function. They are automatically injected by name.
3.	Command-line interface: You get a powerful command-line interface for each experiment that you can use to change parameters and run different variants.
4.	Observers: Sacred provides Observers that log all kinds of information about your experiment, its dependencies, the configuration you used, the machine it is run on, and of course the result. These can be saved to a MongoDB, for easy access later.
5.	Automatic seeding helps controlling the randomness in your experiments, such that the results remain reproducible.

__Crypten (Facebook)__

https://github.com/facebookresearch/CrypTen 

CrypTen is a framework for Privacy Preserving Machine Learning built on PyTorch. Its goal is to make secure computing techniques accessible to Machine Learning practitioners. It currently implements Secure Multiparty Computation as its secure computing backend and offers three main benefits to ML researchers:
1.	It is machine learning first. The framework presents the protocols via a CrypTensor object that looks and feels exactly like a PyTorch Tensor. This allows the user to use automatic differentiation and neural network modules akin to those in PyTorch.
2.	CrypTen is library-based. It implements a tensor library just as PyTorch does. This makes it easier for practitioners to debug, experiment on, and explore ML models.
3.	The framework is built with real-world challenges in mind. CrypTen does not scale back or oversimplify the implementation of the secure protocols.

__PySyft__

https://www.openmined.org/ 

OpenMined is an open-source community whose goal is to make the world more privacy-preserving by lowering the barrier-to-entry to private AI technologies.
https://github.com/OpenMined/PySyft 

Syft decouples private data from model training, using Federated Learning, Differential Privacy, and Encrypted Computation (like Multi-Party Computation (MPC) and Homomorphic Encryption (HE)) within the main Deep Learning frameworks like PyTorch and TensorFlow.
Most software libraries let you compute over the information you own and see inside of machines you control. However, this means that you cannot compute on information without first obtaining (at least partial) ownership of that information. It also means that you cannot compute using machines without first obtaining control over those machines. This is very limiting to human collaboration and systematically drives the centralization of data, because you cannot work with a bunch of data without first putting it all in one (central) place.

The Syft ecosystem seeks to change this system, allowing you to write software which can compute over information you do not own on machines you do not have (total) control over. This not only includes servers in the cloud, but also personal desktops, laptops, mobile phones, websites, and edge devices. Wherever your data wants to live in your ownership, the Syft ecosystem exists to help keep it there while allowing it to be used privately for computation.
* Federated learning: a type of remote execution wherein models are sent to remote data-holding machines (such as smart phones or IoT devices) for local training. This eliminates the need to store sensitive training data on a central server.
* On-device prediction:  a special case of remote execution wherein models are used within an application locally instead of moving a dataset to the cloud for classification.
* Multi-party computation: When a model has multiple owners, multi-party computation allows for individuals to share control of a model without seeing its contents such that no sole owner can use or train it.
* Homomorphic encryption: When a model has a single owner, homomorphic encryption allows an owner to encrypt their model so that untrusted 3rd parties can train or use the model without being able to steal it.
* Differential Privacy: ventually you must request the results of your remote (or encrypted) analysis to be revealed (i.e., statistical results, a trained model, prediction, or synthetic dataset). Differential Privacy helps us answer the question, “If I were to reveal this datapoint, what’s the maximum amount of private information I may leak?” and obfuscate the data appropriately. We extend PyTorch and Tensorflow with the ability to perform differential privacy automatically.

__Securiti__

https://securiti.ai/

Identify any sensitive data across your organization in structured and unstructured systems. Automate data privacy, security & governance. 
* Collect and catalog all data assets 
* Discover hundreds of personal & sensitive data attributes such as name, address, credit card number, social security number, medical record number and many more in any structured & unstructured databases. 
* Detect special attributes that require disclosure under GDPR. For example: race, religion etc.
* Detect personal data attributes specific to regions such as EU, Latin America and Asia Pacific. Ex: passport numbers, bank account numbers etc.
* Automate privacy-by-design, DPIA, Article 30 reports, based on sensitive data intelligence.
* Fulfill data subject rights automatically and maintain proof of compliance.
* Collaborate and track all assessments in one place.
* Use data aligned with cookie consent and universal consent.
* Continuously monitor and remediate data asset security posture
* Identify external and internals risks to data. Risk Engine for Scoring, Attribution & Visualization
* Policy based protections and alerts for the distributed multicloud data

__Privitar__

https://www.privitar.com/

De-Identify data at massive scale. Safely drive data through your analytics and data science operations. 
* Data privacy platform
* Centralized privacy policy management 
* Data masking, tokenization, generalization, perturbation, redaction, substitution and encryption

__Collibra__

https://www.collibra.com/

* Intuitive and contextual search, which uses modern technology to search across all locations, data sources and more, so users can find what they’re looking for in a matter of seconds. Built into the holistic platform, the contextual search provides visibility across all of Collibra’s products and includes filters, facets, and other methods of narrowing search criteria.
* Access organization’s trusted, governed data wherever they happen to be working. Whether it’s through integrations with your existing tools and products or through native applications, you can ensure your users have access to the data they need, when they need it, in the easiest way possible.
* Range of capabilities to manage all of your data stewardship needs. It is simple enough that every data citizen can find the data they need, evaluate its quality and use it effectively in their role. Collibra’s Data Stewardship enables your teams to join forces with subject matter experts and data owners across the organization through role-based dashboards and interactive views.
* Data Catalog empowers business users to quickly discover and understand data that matters so they can generate impactful insights that drive business value
* Data governance. Questions around data’s quality and relevance are increasingly difficult for modern enterprises to answer. Collibra Data Governance helps organizations understand their ever-growing amounts of data in a way that scales with growth and change, so that teams can trust and use their data to improve their business.
* Data lineage. Data lineage reveals how data transforms through its life cycle across interactions with systems, applications, APIs and reports. Collibra Data Lineage automatically maps relationships between data to show how data flows from system to system and how data sets are built, aggregated, sourced and used, providing complete, end-to-end lineage visualization. 
* Data privacy. Collibra delivers privacy from a Data Intelligent foundation that centralizes, automates and guides privacy workflows. Privacy by design is embedded into a single platform, enabling teams across departments to collaborate and operationalize privacy. By awakening the value of data, Collibra accelerates an organization’s ability to address global regulatory requirements. 
* Data quality. Data teams are often constrained by manual rule writing and management, with limited data connectivity and a siloed view of data quality. With predictive, continuous and self-service data quality, organizations can centralize and automate data quality workflows to gain better control over their end-to-end data pipelines and streamline analytics processes across the enterprise.

__Zama (beta)__

https://zama.ai/ 

Open Source framework for securing AI applications in the cloud. 
Using homomorphic encryption, Zama enables any trained network, regardless of its architecture or training method, to run inference on encrypted user data. 

__Differential privacy kit__

https://medium.com/uber-security-privacy/differential-privacy-open-source-7892c82c42b6

__Adversarial patch tricking models__

https://www.youtube.com/watch?v=c_5EH3CBtD0 and https://securityintelligence.com/how-can-companies-defend-against-adversarial-machine-learning-attacks-in-the-age-of-ai/

__Lifecycle analysis and governance__

https://www.mimecast.com/blog/most-healthcare-data-breaches-now-caused-by-email/  

The process and infrastructure to store the training data, accuracy, documentation, trained model, orchestration of the model, inference results and beyond.

__Deeploy__

https://www.deeploy.ml/

TO EXPAND

#### Explainability, interpretability, transparency

__InterpretML (Azure)__

https://interpret.ml/ 

https://github.com/interpretml/interpret

Open-source package that incorporates state-of-the-art machine learning interpretability techniques. With this package, you can train interpretable glassbox models and explain blackbox systems. InterpretML helps you understand your model's global behavior, or understand the reasons behind individual predictions.
* Glass-box models are interpretable due to their structure. Examples include: Explainable Boosting Machines (EBM), Linear models, and decision trees. Glass-box models produce lossless explanations and are editable by domain experts.
* Black-box models are challenging to understand, for example deep neural networks. Black-box explainers can analyze the relationship between input features and output predictions to interpret models. Examples include LIME and SHAP.
* Supports global as well as local explanations, and things like subset prediction explanations as well as feature impact analysis.
* Supported techniques:
  * Explainable Boosting	glassbox model
  * Decision Tree	glassbox model
  * Decision Rule List	glassbox model
  * Linear/Logistic Regression	glassbox model
  * SHAP Kernel Explainer	blackbox explainer
  * LIME	blackbox explainer
  * Morris Sensitivity Analysis	blackbox explainer
  * Partial Dependence	blackbox explainer

__AI Explainability 360 (IBM)__

https://aix360.mybluemix.net/ 

https://github.com/Trusted-AI/AIX360 

Open-source library that supports interpretability and explainability of datasets and machine learning models. The AI Explainability 360 Python package includes a comprehensive set of algorithms that cover different dimensions of explanations along with proxy explainability metrics.

The algorithms in the toolkit are primarily intended for high-stakes applications of machine learning from data that support decision making with humans in the loop, either as the decision makers, the subjects of the decisions, or as regulators of the decision making processes. Other modes of AI such as knowledge graph induction or planning, and even other modes of machine learning such as reinforcement learning are not appropriate settings in which to use AIX360. 
* Data explanation (ProtoDash (Gurumoorthy et al., 2019), Disentangled Inferred Prior VAE (Kumar et al., 2018))
* Local post-hoc explanation (ProtoDash (Gurumoorthy et al., 2019), Contrastive Explanations Method (Dhurandhar et al., 2018), Contrastive Explanations Method with Monotonic Attribute Functions (Luss et al., 2019), LIME (Ribeiro et al. 2016, Github), SHAP (Lundberg, et al. 2017, Github))
* Local direct explanation (Teaching AI to Explain its Decisions (Hind et al., 2019))
* Global direct explanation (Boolean Decision Rules via Column Generation (Light Edition) (Dash et al., 2018), Generalized Linear Rule Models (Wei et al., 2019))
* Global post-hoc explanation (ProfWeight (Dhurandhar et al., 2018)
* Supported explainability metrics (Faithfulness (Alvarez-Melis and Jaakkola, 2018), Monotonicity (Luss et al., 2019))

__What if tool (Google People and AI Research)__

https://pair-code.github.io/what-if-tool/

https://github.com/pair-code/what-if-tool

Visually probe the behavior of trained machine learning models, with minimal coding.
A key challenge in developing and deploying responsible Machine Learning (ML) systems is understanding their performance across a wide range of inputs.
Using WIT, you can test performance in hypothetical situations, analyze the importance of different data features, and visualize model behavior across multiple models and subsets of input data, and for different ML fairness metrics.
The What-If Tool can work with any python-accessible model in Notebook environments, and will work with most models hosted by TF-serving in Tensorboard.
The What-If Tool supports:
* binary classification*
* multi-class classification
* regression tasks
Fairness optimization strategies are available only with binary classification models due to the nature of the strategies themselves.
In the What-If Tool, Counterfactuals are datapoints that are most similar to a selected datapoint, but are classified differently by a model.
For binary classification models, counterfactuals are the most similar datapoint to a selected datapoint that is predicted in the opposite class or label by a model.
For regression models, counterfactuals are calculated when the difference in prediction score between the selected datapoint and a candidate counterfactual is equal or greater to the “counterfactual threshold”. The counterfactual threshold default is set to the standard deviation of the prediction values and can be adjusted by the user.
For multi-class models, the counterfactual is the most similar datapoint to a selected datapoint, but is classified as any class other than the selected datapoint’s class.

__Tensorwatch__

https://github.com/microsoft/tensorwatch

TensorWatch is a debugging and visualization tool designed for data science, deep learning and reinforcement learning from Microsoft Research. It works in Jupyter Notebook to show real-time visualizations of your machine learning training and perform several other key analysis tasks for your models and data.
TensorWatch is designed to be flexible and extensible so you can also build your own custom visualizations, UIs, and dashboards. Besides traditional "what-you-see-is-what-you-log" approach, it also has a unique capability to execute arbitrary queries against your live ML training process, return a stream as a result of the query and view this stream using your choice of a visualizer (we call this Lazy Logging Mode).
When you write to a TensorWatch stream, the values get serialized and sent to a TCP/IP socket as well as the file you specified. From Jupyter Notebook, we load the previously logged values from the file and then listen to that TCP/IP socket for any future values. The visualizer listens to the stream and renders the values as they arrive.
Ok, so that's a very simplified description. The TensorWatch architecture is actually much more powerful. Almost everything in TensorWatch is a stream. Files, sockets, consoles and even visualizers are streams themselves. A cool thing about TensorWatch streams is that they can listen to any other streams. This allows TensorWatch to create a data flow graph. This means that a visualizer can listen to many streams simultaneously, each of which could be a file, a socket or some other stream. You can recursively extend this to build arbitrary data flow graphs. TensorWatch decouples streams from how they get stored and how they get visualized.

__Rulex__

https://www.rulex.ai/rulex-explainable-ai-xai/

Explainable AI produces transparent, easily understandable models. Using a series of if-then statements, Rulex automatically produces self-explanatory logic for all decisions. Rulex rulesets make it possible to explain a decision directly to the customer or provide customer service agents with the ability to look up the reason for a decision.
Why eXplainable AI is more transparent than black box?
The problem with conventional AI is very simple: it’s unexplainable. Conventional AI relies on machine learning algorithms such as neural networks and others that have one key feature in common: they produce “black box” predictive models, meaning they’re mathematical functions that cannot be understood by people, even mathematicians.
Rulex’s core machine learning algorithm, the Logic Learning Machine (LLM), works in an entirely different way from conventional AI. Rather than producing a math function, it produces conditional logic rules that predict the best decision choice, in plain language that is immediately clear to process professionals. Rulex rules make every prediction fully self-explanatory.
And unlike decision trees and other algorithms that produce rules, Rulex rules are stateless and overlapping, meaning one rule can cover many cases, and many rules can cover a single case. This allows for fewer, simpler rules and provides broader coverage at the same time.
Rulex calculates the coverage and accuracy of each rule, making it easy to select the most effective decision rules. Also, proven heuristic human rules can be added to the predictive model, allowing a seamless blend of human and artificial intelligence. Human rules are also rated for coverage and accuracy, allowing Rulex to easily evaluate the quality of the decision rules in use and reduce false positives.

__MindsDB__

https://mindsdb.com/

https://github.com/mindsdb/mindsdb 

MindsDB's is an Explainable AutoML framework for developers. MindsDB is an automated machine learning platform that allows anyone to gain powerful insights from their data. With MindsDB, users can get fast, accurate, and interpretable answers to any of their data questions within minutes. A predictive layer for existing databases that enables rapid prototyping & deployment of ML Models from your database. Significantly reducing the time and cost of machine learning workflows.

__Intuitive confidence measure__

TO DO

__Contrastive explanations__

https://pythonrepo.com/repo/MarcelRobeer-ContrastiveExplanation-python-deep-learning-model-explanation 

Contrastive Explanation provides an explanation for why an instance had the current outcome (fact) rather than a targeted outcome of interest (foil). These counterfactual explanations limit the explanation to the features relevant in distinguishing fact from foil, thereby disregarding irrelevant features. The idea of contrastive explanations is captured in this Python package ContrastiveExplanation. Example facts and foils are:
Machine Learning (ML) type	Problem	Explainable AI (XAI) question	Fact	Foil
Classification	Determine type of animal	Why is this instance a cat rather than a dog?	Cat	Dog
Regression analysis	Predict students' grade	Why is the predicted grade for this student 6.5 rather than higher?	6.5	More than 6.5
Clustering	Find similar flowers	Why is this flower in cluster 1 rather than cluster 4?	Cluster 1	Cluster 4

__Explainerdashboard__

https://medium.com/value-stream-design/making-ml-transparent-and-explainable-with-explainerdashboard-49953ae743dd 

https://github.com/oegedijk/explainerdashboard 

https://www.youtube.com/watch?v=1nMlfrDvwc8

This package makes it convenient to quickly deploy a dashboard web app that explains the workings of a (scikit-learn compatible) machine learning model. The dashboard provides interactive plots on model performance, feature importances, feature contributions to individual predictions, "what if" analysis, partial dependence plots, SHAP (interaction) values, visualisation of individual decision trees, etc.
You can also interactively explore components of the dashboard in a notebook/colab environment (or just launch a dashboard straight from there). Or design a dashboard with your own custom layout and explanations (thanks to the modular design of the library). And you can combine multiple dashboards into a single ExplainerHub.
Dashboards can be exported to static html directly from a running dashboard, or programmatically as an artifact as part of an automated CI/CD deployment process.
 

#### Fairness, bias tooling

__AI Fairness 360 (IBM)__

http://aif360.mybluemix.net/ 

https://github.com/Trusted-AI/AIF360 

Supported bias mitigation algorithms
* Optimized Preprocessing (⦁	Calmon et al., 2017)
* Disparate Impact Remover (⦁	Feldman et al., 2015)
* Equalized Odds Postprocessing (⦁	Hardt et al., 2016)
* Reweighing (⦁	Kamiran and Calders, 2012)
* Reject Option Classification (⦁	Kamiran et al., 2012)
* Prejudice Remover Regularizer (⦁	Kamishima et al., 2012)
* Calibrated Equalized Odds Postprocessing (⦁	Pleiss et al., 2017)
* Learning Fair Representations (⦁	Zemel et al., 2013)
* Adversarial Debiasing (⦁	Zhang et al., 2018)
* Meta-Algorithm for Fair Classification (⦁	Celis et al.. 2018)
* Rich Subgroup Fairness (⦁	Kearns, Neel, Roth, Wu, 2018)
* Exponentiated Gradient Reduction (⦁	Agarwal et al., 2018)
* Grid Search Reduction (⦁	Agarwal et al., 2018, ⦁	Agarwal et al., 2019)
Supported fairness metrics
* Comprehensive set of group fairness metrics derived from selection rates and error rates including rich subgroup fairness
* Comprehensive set of sample distortion metrics
* Generalized Entropy Index (⦁	Speicher et al., 2018)
* Differential Fairness and Bias Amplification (⦁	Foulds et al., 2018)
* Bias Scan with Multi-Dimensional Subset Scan (⦁	Zhang, Neill, 2017)

__Fairlearn__

https://fairlearn.org/

https://github.com/fairlearn/fairlearn

Fairlearn is an open-source, community-driven project to help data scientists improve fairness of AI systems.
* A Python library for fairness assessment and improvement (fairness metrics, mitigation algorithms, plotting, etc.)
The Fairlearn tookit can assist in assessing and mitigation unfairness in Machine Learning models. It’s impossible to provide a sufficient overview of fairness in ML in this Quickstart tutorial, so we highly recommend starting with our User Guide. Fairness is a fundamentally sociotechnical challenge and cannot be solved with technical tools alone. They may be helpful for certain tasks such as assessing unfairness through various metrics, or to mitigate observed unfairness when training a model. Additionally, fairness has different definitions in different contexts and it may not be possible to represent it quantitatively at all.
* Metrics for assessing which groups are negatively impacted by a model, and for comparing multiple models in terms of various fairness and accuracy metrics.
* Algorithms for mitigating unfairness in a variety of AI tasks and along a variety of fairness definitions.

__What if tool (Google People and AI Research)__

https://pair-code.github.io/what-if-tool/

https://github.com/pair-code/what-if-tool

Visually probe the behavior of trained machine learning models, with minimal coding.
A key challenge in developing and deploying responsible Machine Learning (ML) systems is understanding their performance across a wide range of inputs.
Using WIT, you can test performance in hypothetical situations, analyze the importance of different data features, and visualize model behavior across multiple models and subsets of input data, and for different ML fairness metrics.
The What-If Tool can work with any python-accessible model in Notebook environments, and will work with most models hosted by TF-serving in Tensorboard.
The What-If Tool supports:
* binary classification*
* multi-class classification
* regression tasks
Fairness optimization strategies are available only with binary classification models due to the nature of the strategies themselves.

In the What-If Tool, Counterfactuals are datapoints that are most similar to a selected datapoint, but are classified differently by a model.
* For binary classification models, counterfactuals are the most similar datapoint to a selected datapoint that is predicted in the opposite class or label by a model.
* For regression models, counterfactuals are calculated when the difference in prediction score between the selected datapoint and a candidate counterfactual is equal or greater to the “counterfactual threshold”. The counterfactual threshold default is set to the standard deviation of the prediction values and can be adjusted by the user.
* For multi-class models, the counterfactual is the most similar datapoint to a selected datapoint, but is classified as any class other than the selected datapoint’s class.

__Sagemaker clarify (Amazon)__

https://aws.amazon.com/sagemaker/clarify/

Provides machine learning developers with greater visibility into their training data and models so they can identify and limit bias and explain predictions.
Biases are imbalances in the training data or prediction behavior of the model across different groups, such as age or income bracket. Biases can result from the data or algorithm used to train your model. For instance, if an ML model is trained primarily on data from middle-aged individuals, it may be less accurate when making predictions involving younger and older people. The field of machine learning provides an opportunity to address biases by detecting them and measuring them in your data and model. You can also look at the importance of model inputs to explain why models make the predictions they do.
Amazon SageMaker Clarify detects potential bias during data preparation, after model training, and in your deployed model by examining attributes you specify. For instance, you can check for bias related to age in your initial dataset or in your trained model and receive a detailed report that quantifies different types of possible bias. SageMaker Clarify also includes feature importance graphs that help you explain model predictions and produces reports which can be used to support internal presentations or to identify issues with your model that you can take steps to correct.
* Identify imbalances in data
* Check trained models for bias
* Monitor model for bias
* Understand model
* Monitor model for changes in behavior
* explain individual model predictions

__ML Fairness gym (Google)__

https://github.com/google/ml-fairness-gym

ML-fairness-gym is a set of components for building simple simulations that explore the potential long-run impacts of deploying machine learning-based decision systems in social environments. As the importance of machine learning fairness has become increasingly apparent, recent research has focused on potentially surprising long term behaviors of enforcing measures of fairness that were originally defined in a static setting. Key findings have shown that under specific assumptions in simplified dynamic simulations, long term effects may in fact counteract the desired goals. Achieving a deeper understanding of such long term effects is thus a critical direction for ML fairness research. ML-fairness-gym implements a generalized framework for studying and probing long term fairness effects in carefully constructed simulation scenarios where a learning agent interacts with an environment over time. This work fits into a larger push in the fair machine learning literature to design decision systems that induce fair outcomes in the long run, and to understand how these systems might differ from those designed to enforce fairness on a one-shot basis.

Using fairness-gym in your research

ML-fairness-gym brings reinforcement learning-style evaluations to fairness in machine learning research. Here is a suggested pattern for using the ML-fairness-gym as part of the research process. Others may be added here as we continue to grow.

Evaluating a proposed ML algorithm

Here are suggested steps when evaluating a proposed new fair ML algorthm:
* Choose a simulation environment.
* Decide on metrics that you would like to measure for that environment.
* Choose baseline agents and choose what reward functions they will optimize.
* Write an agent that uses your new algorithm.
* Compare metrics between your baseline agents and your fair agent. Some utilities for building experiments are provided in run_util.py. For example, run_simulationis a simple function that runs an experiment and returns metric measurements.
* Explore parameter settings in your simulation environment - are there different regimes?

We provide some implementations of environments, agents, and metrics, but they are by no means comprehensive. Feel free to implement your own and contribute to ML-fairness-gym!

__Aequitas__

https://dssg.github.io/aequitas/

Aequitas is an open-source bias audit toolkit for data scientists, machine learning researchers, and policymakers to audit machine learning models for discrimination and bias, and to make informed and equitable decisions around developing and deploying predictive tools.
Aequitas will help you:
* Understand where biases exist in your model(s)
* Compare the level of bias between groups in your sample population (bias disparity)
* Visualize absolute bias metrics and their related disparities for rapid comprehension and decision-making
Our goal is to support informed and equitable action for both machine learnining practitioners and the decision-makers who rely on them.

#### Risk, value, and stakeholder modeling

These tools are more process / project related tools. Potentially interesting for POs, ATs, PMs and the likes.
Aanpak begeleidingsethiek https://ecp.nl/project/aanpak-begeleidingsethiek/
* Deda https://dataschool.nl/deda/ 
* ALTAI https://digital-strategy.ec.europa.eu/en/library/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment
* Value-sensitive design (https://mitpress.mit.edu/books/value-sensitive-design)
* Ethical toolkit for development of AI applications (https://repository.tudelft.nl/islandora/object/uuid%3Ab5679758-343d-4437-b202-86b3c5cef6aa )
* Judgment call the game (http://houseofmethods.com/pdf/microsoft-judgment-call.pdf) 
* Deon. https://deon.drivendata.org/ Data Science Ethics Checklist, that you can integrate in your code and also produces a badge as a add to your project documentation. Includes questions regarding data collection, data storage, analysis, modeling, and more.
* Google model cards. https://modelcards.withgoogle.com/about . A foundation for documenting, explaining, and registring your models for other people to understand and inspect. Includes things like, goals, metrics, limitations, tools, benchmarks, fairness, and privacy.

####Sustainable AI

__Jina AI__

https://jina.ai/ 

https://github.com/jina-ai/jina

Jina🔊 allows you to build search-as-a-service powered by deep learning in just minutes.

All data types - Large-scale indexing and querying of any kind of unstructured data: video, image, long/short text, music, source code, PDF, etc.

Fast & cloud-native - Distributed architecture from day one, scalable & cloud-native by design: enjoy containerizing, streaming, paralleling, sharding, async scheduling, HTTP/gRPC/WebSocket protocol.

Save time - The design pattern of neural search systems, from zero to a production-ready system in minutes.

Own your stack - Keep end-to-end stack ownership of your solution, avoid integration pitfalls you get with fragmented, multi-vendor, generic legacy tools.

### Frameworks

<a name="other"></a>
## Other

### Podcasts
