---
title: Publications
permalink: "/publications/"
layout: archive
author_profile: true
---

<!--
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

### Dissertation
- **W. Wang**. (2018) Adaptive Control of Personalized Driver Assistance Systems. *Ph.D., Mechanical Engineering, Beijing Institute of Technology*


<table style="width:100%">
    <thead>
		<tr>
			<th width="25%">Highlight</th>
			<th width="15%">Authors</th>
			<th width="38%">Title</th>
			<th width="2%">Year</th>
			<th width="20%">Journal/Proceedings</th>
		</tr>
    </thead>
	<tbody>
    <tr id="wang2022local" class="entry">
          <td>
        <div class="polaroid">
          <img src="../images/research/wang2022local.png" width="600" class="research_img">
          <!-- <div class="container">
          Local Prior Sensitivity
          </div> -->
        </div>
      </td>
          <td><strong>W. Wang</strong>, L. Sun</td>
      <td>
        Local Prior Sensitivity Analysis with Gradient Descent Search for Nonparametric Bayesian Learning<br>
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('wang2022local','abstract')">Abstract</a>]
                  [<a href="javascript:toggleInfo('wang2022local','bibtex')">BibTeX</a>] 
                  <!-- [<a href="https://ieeexplore.ieee.org/abstract/document/8956222">PDF</a>] -->
                  <!-- [<a href="https://arxiv.org/pdf/2007.00648">arXiv</a>] -->
                  <!-- [<a href="http://tps.uwstarlab.org/">Website</a>] -->
                  <!-- [<a href="https://zhiyongcui.com/blog/2020/07/16/graph-markov-network.html">Post</a>] -->
                  <!-- [<a href="https://github.com/zhiyongc/GraphMarkovNetwork">Code</a>] -->
                  <!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a>] -->
              </p>
        </td>
      <td>2022</td>
          <td>The Montreal AI Symposium 2022</td>
        </tr>
        <tr id="abs_wang2022local" class="abstract noshow">
          <td colspan="5"><div align="justify"> <b>Abstract</b>: The sensitivity of Bayesian analysis is mainly influenced by data (or observations), sampling distribution, and prior parameters. Inappropriate prior specifications can lead to distorted findings for influential observations and uncertainty of the sampling model. This paper mainly focuses on providing a computationally efficient gradient search approach to analyze the prior sensitivity of nonparametric Bayesian models. For the nonparametric Bayesian model with a hierarchical scheme for the prior hyperparameters, it requires robustness, i.e., an apolitically ideal Bayesian model should be lower sensitive to its prior distribution. However, there exist some challenges due to its hierarchical schemes. One is the model complexity, the hierarchical framework has led to the development of increasingly intricate models. The other one is the uninterpretability, the parameters within deeper layers in the hierarchical model are challenging to interpret. Generally, there are two approaches to analyzing the sensitivity of Bayesian models: formal and informal. Formal approaches use considerable theoretical advances (e.g., geometric approach) but are rarely used in everyday practice due to their high-computational cost and absence of software implementation. Informal approaches repetitively rerun models with ad-hoc modified based on prior parameter values and checked the posterior densities. Usually, non-sensitivity and robustness are claimed if the posterior subjectively do not differ much. The sensitive analysis could be local or global. The global one usually applies a class of all priors compatible with the elicited prior information and computes the range of posteriors as prior varies over the class. The local one focuses on the rate of change in posterior density to the changes in the prior, which is usually easier to compute than global. </div></td>
        </tr>
        <tr id="bib_wang2022local" class="bibtex noshow">
          <td colspan="5"><b>BibTeX</b>:
                <pre>@inproceedings{wang2022local,
                      title={Local Prior Sensitivity Analysis with Gradient Descent Search for Nonparametric Bayesian Learning},
                      author={Wang, Wenshuo and Sun, Lijun},
                      booktitle={The Montreal AI Symposium 2022},
                      year={2022}
                      }
                </pre>
        </td>
    </tr>
		<tr id="wang2022action" class="entry">
      		<td>
				<!-- <img src="../images/research/cui2020establishing.png" width="600" class="single_img"> -->
				<div class="polaroid">
				  <img src="../images/research/wang2022action.png" width="600" class="research_img">
				  <!-- <div class="container">
				  Active Inference and Optimization
				  </div> -->
				</div>
			</td>
       		<td><strong>W. Wang</strong>, C. Zhang, L. Sun</td>
			<td>
				An Action-Induced Model through Active Inference with Variational Bounds and Optimization
        <br>
				<!-- (<span style="color:darkred;">ASA TSIG Student Paper Award</span>)  -->
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2022action','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2022action','bibtex')">BibTeX</a>] 
              		<!-- [<a href="https://ieeexplore.ieee.org/abstract/document/8956222">PDF</a>] -->
              		<!-- [<a href="https://arxiv.org/abs/1912.05457">arXiv</a>]
                  [<a href="https://zhiyongcui.com/blog/2020/07/16/graph-markov-network.html">Post</a>]
                  [<a href="https://github.com/zhiyongc/GraphMarkovNetwork">Code</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a>] -->
            	</p>
    		</td>
 			<td>2022</td>
        	<td>The Montreal AI Symposium 2022</td>
        </tr>
        <tr id="abs_wang2022action" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Modeling the action-reaction mechanism of human agents in interactive scenarios such as human drivers in real traffic is challenging. Rational human agents usually negotiate with others by actively perceiving information about the world via proactively taking specific actions that influence the world. For instance, in real traffic, human drivers make tentative attempts before decisively switching lanes as a way to signify their intention of lane switch and tease out the intentions of other vehicles in the adjoining lanes. However, it is still unclear (i) why a tentative behavior is efficient and matters in human interactions and (ii) how it could be modeled in an interpretable learning framework. This paper provides a new framework for modeling the process of generating actions by humans in interactive scenarios using active inference with the free energy theory. The hypothesis is that humans execute tentative behaviors to reduce the sensory uncertainties arising from people's quantity of possible outcomes, enabling them to make efficient decisions. We show a proof of concept that the process by that humans take tentative actions in interaction can be viewed as an optimization problem over variational bounds.  </div></td>
      	</tr>
        <tr id="bib_wang2022action" class="bibtex noshow">
          <td colspan="5"><b>BibTeX</b>:
                <pre>@inproceedings{wang2022action,
                      title={An Action-Induced Model through Active Inference with Variational Bounds and Optimization},
                      author={Wang, Wenshuo and Zhang, Chengyuan and Sun, Lijun},
                      booktitle={The Montreal AI Symposium 2022},
                      year={2022}
                    }
                  </pre>
      </td>
    </tr>
    <tr id="wang2022social" class="entry">
          <td>
        <!-- <img src="../images/research/cui2020establishing.png" width="600" class="single_img"> -->
        <div class="polaroid">
          <img src="../images/research/wang2022social.jpg" width="600" class="research_img">
          <!-- <div class="container">
          Social Interaction
          </div> -->
        </div>
      </td>
          <td><strong>W. Wang</strong>, L. Wang, C. Zhang, C. Liu, L. Sun</td>
      <td>
        Social Interactions for Autonomous Driving: A Review and Perspectives<br>
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('wang2022social','abstract')">Abstract</a>]
                  [<a href="javascript:toggleInfo('wang2022social','bibtex')">BibTeX</a>] 
                  <!-- [<a href="https://ieeexplore.ieee.org/abstract/document/8956222">PDF</a>] -->
                  [<a href="https://arxiv.org/abs/2208.07541">arXiv</a>]
                  <!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a>] -->
              </p>
        </td>
      <td>2022</td>
          <td>Foundations and Trends in Robotics (Under review)</td>
        </tr>
        <tr id="abs_wang2022social" class="abstract noshow">
          <td colspan="5"><div align="justify"> <b>Abstract</b>: No human drives a car in a vacuum; she/he must negotiate with other road users to achieve their goals in social traffic scenes. A rational human driver can interact with other road users in a socially-compatible way through implicit communications to complete their driving tasks smoothly in interaction-intensive, safety-critical environments. This paper aims to review the existing approaches and theories to help understand and rethink the interactions among human drivers toward social autonomous driving. We take this survey to seek the answers to a series of fundamental questions: 1) What is social interaction in road traffic scenes? 2) How to measure and evaluate social interaction? 3) How to model and reveal the process of social interaction? 4) How do human drivers reach an implicit agreement and negotiate smoothly in social interaction? This paper reviews various approaches to modeling and learning the social interactions between human drivers, ranging from optimization theory, deep learning, and graphical models to social force theory and behavioral & cognitive science. We also highlight some new directions, critical challenges, and opening questions for future research.</div></td>
        </tr>
        <tr id="bib_wang2022social" class="bibtex noshow">
          <td colspan="5"><b>BibTeX</b>:
                <pre>@article{wang2022social,
                      title={Social Interactions for Autonomous Driving: A Review and Perspective},
                      author={Wang, Wenshuo and Wang, Letian and Zhang, Chengyuan and Liu, Changliu and Sun, Lijun},
                      journal={arXiv preprint arXiv:2208.07541},
                      year={2022}
                      }
                </pre>
      </td>
    </tr>
    <tr id="wang2022cv" class="entry">
      <td>
        <!-- <img src="../images/research/cui2020establishing.png" width="600" class="single_img"> -->
        <div class="polaroid">
          <img src="../images/research/wang2022cv.png" width="600" class="research_img">
          <!-- <div class="container">
          Gated Graph Wavelet RNN
          </div> -->
        </div>
      </td>
      <td>N. Ma, J. Fan, <strong>W. Wang</strong>, et al.</td>
      <td>
        Computer vision for road imaging and pothole detection: A state-of-the-art review of systems and algorithms<br>
        <!-- <span class="style_award">
          (Winner of Best Student Paper)
        </span> -->
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('wang2022cv','abstract')">Abstract</a>]
                  [<a href="javascript:toggleInfo('wang2022cv','bibtex')">BibTeX</a>] 
                  [<a href="https://arxiv.org/abs/2204.13590">PDF</a>]
                  <!-- [<a href="https://arxiv.org/abs/1802.07007">arXiv</a>] -->
                  <!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a> -->
              </p>
      </td>
      <td>2022</td>
      <td>Transportation Safety and Environment</td>
      </tr>
        <tr id="abs_wang2022cv" class="abstract noshow">
          <td colspan="5"><div align="justify"> <b>Abstract</b>: Computer vision algorithms have been prevalently utilized for 3-D road imaging and pothole detection for over two decades. Nonetheless, there is a lack of systematic survey articles on state-of-the-art (SoTA) computer vision techniques, especially deep learning models, developed to tackle these problems. This article first introduces the sensing systems employed for 2-D and 3-D road data acquisition, including camera(s), laser scanners, and Microsoft Kinect. Afterward, it thoroughly and comprehensively reviews the SoTA computer vision algorithms, including (1) classical 2-D image processing, (2) 3-D point cloud modeling and segmentation, and (3) machine/deep learning, developed for road pothole detection. This article also discusses the existing challenges and future development trends of computer vision-based road pothole detection approaches: classical 2-D image processing-based and 3-D point cloud modeling and segmentation-based approaches have already become history; and Convolutional neural networks (CNNs) have demonstrated compelling road pothole detection results and are promising to break the bottleneck with the future advances in self/un-supervised learning for multi-modal semantic segmentation. We believe that this survey can serve as practical guidance for developing the next-generation road condition assessment systems.</div></td>
        </tr>
        <tr id="bib_wang2022cv" class="bibtex noshow">
          <td colspan="5"><b>BibTeX</b>:
                <pre>@article{ma2022computer,
                      title={Computer vision for road imaging and pothole detection: A state-of-the-art review of systems and algorithms},
                      author={Ma, Nachuan and Fan, Jiahe and Wang, Wenshuo and Wu, Jin and Jiang, Yu and Xie, Lihua and Fan, Rui},
                      journal={arXiv preprint arXiv:2204.13590},
                      year={2022}
                    }
                </pre>
            </td>
        </tr>
  	<!-- <tr id="bib_cui2019graph" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{cui2019graph,
  title={Graph Markov Network for Traffic Forecasting with Missing Data},
  author={Cui, Zhiyong and Lin, Longfei and Pu, Ziyuan and Wang, Yinhai},
  journal={arXiv preprint arXiv:1912.05457},
  year={2019}
}</pre>
			</td>
      	</tr> -->
      	<tr id="wang2022instance" class="entry">
      		<td>
				<div class="polaroid">
				  <img src="../images/research/wang2022instance.png" width="600" class="research_img">
				</div>
			</td>
       		<td>C. Lu, C. Lv, <strong>W. Wang</strong>, et al. </td>
			<td>
				Instance-Level Knowledge Transfer for Data-Driven Driver Model Adaptation With Homogeneous Domains<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2022instance','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('cui2019graph','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9745808">PDF</a>]
              		<!-- [<a href="https://arxiv.org/abs/1912.05457">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a>] -->
              		<!-- [<a href="https://zhiyongcui.com/TRAFFIX_Web/">Website</a>] -->
              		<!-- [<a href="http://c2smart.engineering.nyu.edu/2019/04/19/an-artificial-intelligence-platform-for-network-wide-congestion-detection-and-prediction-using-multi-source-data-2/">Project</a>] -->
              		<!-- [<a href="http://c2smart.engineering.nyu.edu/wp-content/uploads/2019/07/Transportation_AI%20Platform_FinalReport_C2SMART_Wang.pdf">Report</a>] -->
            	</p>
    		</td>
 			<td>2022</td>
        	<td>IEEE Transactions on Intelligent Transportation Systems </td>
        </tr>
        <tr id="abs_wang2022instance" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Driver model adaptation (DMA) plays an essential role for driving behaviour modelling when there is a lack of sufficient data for training the new model. A new data-driven DMA method is proposed in this paper to realise the instance-level knowledge transfer between individual drivers. Using the importance-weighted transfer learning (IWTL), the data collected from one driver (source driver) can be directly used to train the model of another driver (target driver). Under the framework of IWTL, the relationship between two different drivers can be modelled by the importance weight (IW). Two estimation methods Kullback-Leibler (KL) Divergence and least-squares (LS), are used to estimate IW for each data instance by modelling the importance-weight function as a radial basis function (RBF). Experiments based on the driving simulator and real vehicle are carried out to test the performance of TL for steering behaviour adaptation during the overtaking manoeuvre. The experimental results show that the TL method can transfer the knowledge observed from one driver to another when training the new driver model without sufficient data by keeping the modelling error at a low level.</div></td>
      	</tr>
      	<tr id="bib_wang2022instance" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{lu2022instance,
                    title={Instance-Level Knowledge Transfer for Data-Driven Driver Model Adaptation With Homogeneous Domains},
                    author={Lu, Chao and Lv, Chen and Gong, Jianwei and Wang, Wenshuo and Cao, Dongpu and Wang, Fei-Yue},
                    journal={IEEE Transactions on Intelligent Transportation Systems},
                    year={2022},
                    publisher={IEEE}
                  }
                </pre>
          </td>
      	</tr>
		<tr id="wang2021social" class="entry">
      		<td>
				<!-- <img src="../images/research/cui2020establishing.png" width="600" class="single_img"> -->
				<div class="polaroid">
				  <img src="../images/research/wang2021social.png" width="600" class="research_img">
				</div>
			</td>
       		<td>H. Wang, <strong>W. Wang*</strong>, S. Yuan, X. Li, L. Sun</td>
			<td>
				On Social Interactions of Merging Behaviors at Highway On-Ramps in Congested Traffic<br>
				<!-- <span class="style_award">
					(Winner of Best Student Paper)
				</span> -->
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2021social','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2021social','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9511791">PDF</a>]
              		<!-- [<a href="https://arxiv.org/abs/1811.04745">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a> -->
            	</p>
    		</td>
 			<td>2021</td>
        	<td>IEEE Transportation on Intelligent Transportation Systems</td>
        </tr>
        <tr id="abs_ma2020forecasting" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Merging at highway on-ramps while interacting with other human-driven vehicles is challenging for autonomous vehicles (AVs). An efficient route to this challenge requires exploring and exploiting knowledge of the interaction process from demonstrations by humans. However, it is unclear what information (or environmental states) is utilized by the human driver to guide their behavior throughout the whole merging process. This paper provides quantitative analysis and evaluation of the merging behavior at highway on-ramps with congested traffic in a volume of time and space. Two types of social interaction scenarios are considered based on the social preferences of surrounding vehicles: courteous and rude. The significant levels of environmental states for characterizing the interactive merging process are empirically analyzed based on the real-world INTERACTION dataset. Experimental results reveal two fundamental mechanisms in the merging process: 1) Human drivers select different states to make sequential decisions at different moments of task execution; and 2) the social preference of surrounding vehicles can impact variable selection for making decisions. It implies that efficient decision-making design should filter out irrelevant information while considering social preference to achieve comparable human-level performance. These essential findings shed light on developing new decision-making approaches for AVs.</div></td>
      	</tr>
      	<tr id="bib_wang2021social" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{wang2021social,
                    title={On social interactions of merging behaviors at highway on-ramps in congested traffic},
                    author={Wang, Huanjie and Wang, Wenshuo and Yuan, Shihua and Li, Xueyuan and Sun, Lijun},
                    journal={IEEE Transactions on Intelligent Transportation Systems},
                    volume = {23},
                    number = {8},
                    pages = {11237--11248},
                    year={2021},
                    publisher={IEEE}
                  }
                </pre>
			    </td>
      	</tr>
      	<tr id="wang2021leverage" class="entry">
      		<td>
				<!-- <img src="../images/research/cui2020establishing.png" width="600" class="single_img"> -->
				<div class="polaroid">
				  <img src="../images/research/wang2021leverage.png" width="600" class="research_img">
				</div>
			</td>
       		<td>S. Yang, <strong>W. Wang*</strong>, J. Xi</td>
			<td>
				Leveraging Human Driving Preferences to Predict Vehicle Speed<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2021leverage','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2021leverage','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9511318">PDF</a>] 
              		<!-- [<a href="https://arxiv.org/abs/1802.07007">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">Code</a>] -->
            	</p>
    		</td>
 			<td>2021</td>
        	<td>IEEE Transportation on Intelligent Transportation Systems</td>
        </tr>
        <tr id="abs_wang2021leverage" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Accurate speed prediction is practically critical to eco-safe driving for intelligent vehicles. Existing research only makes vehicles adapt to the dynamic driving environment while rarely considering the influence of human driving preferences. This paper proposes a learning-based model to leverage human driving preferences into speed prediction. We first designed an Oriented Hidden Semi-Markov Model (Oriented-HSMM) to learn and predict the driver’s driving preference sequences while considering traffic flow influence. Then, we developed an optimal speed prediction algorithm to retrieve the smooth speed trajectories with maximal likelihood based on the estimated driving preferences. Finally, we evaluated the proposed model using the Next Generation Simulation (NGSIM) data compared to its counterparts that do not consider driving preferences. Experimental results demonstrate that our proposed Oriented-HSMM method reaches the best results and achieves a satisfying performance with a low mean absolute error (4.16 km/h) and root mean square error (5.08 km/h) at a 200 m prediction horizon.</div></td>
      	</tr>
      	<tr id="bib_wang2021leverage" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{yang2021leveraging,
                      title={Leveraging human driving preferences to predict vehicle speed},
                      author={Yang, Sen and Wang, Wenshuo and Xi, Junqiang},
                      journal={IEEE Transactions on Intelligent Transportation Systems},
                      volume = {23},
                      number = {8},
                      pages = {11137--11147},
                      year={2021},
                      publisher={IEEE}
                    }
                </pre>
			</td>
      	</tr>
      	<tr id="wang2021spatio" class="entry">
      <td>
				<img src="../images/research/wang2021spatio.png" width="600" class="single_img">
			</td>
       		<td>C. Zhang, J. Zhu, <strong>W. Wang*</strong>, J. Xi </td>
			<td>
				Spatiotemporal Learning of Multivehicle Interaction Patterns in Lane-Change Scenarios<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2021spatio','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2021spatio','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9357407">PDF</a>]
              		<!-- [<a href="https://arxiv.org/abs/1811.04745">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a> -->
            	</p>
    		</td>
 			<td>2021</td>
        	<td> IEEE Transactions on Intelligent Transportation Systems </td>
        </tr>
        <tr id="abs_wang2021spatio" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Interpretation of common-yet-challenging inter- action scenarios can benefit well-founded decisions for autonomous vehicles. Previous research achieved this using their prior knowledge of specific scenarios with predefined models, limiting their adaptive capabilities. This paper describes a Bayesian nonparametric approach that leverages continuous (i.e., Gaussian processes) and discrete (i.e., Dirichlet processes) stochastic processes to reveal underlying interaction patterns of the ego vehicle with other nearby vehicles. Our model relaxes dependency on the number of surrounding vehicles by developing an acceleration-sensitive velocity field based on Gaussian processes. The experiment results demonstrate that the velocity field can represent the spatial interactions between the ego vehicle and its surroundings. A discrete Bayesian nonparametric model, integrating Dirichlet processes and hidden Markov models, is developed to learn the interaction patterns over the temporal space by segmenting and clustering the sequential interaction data into interpretable granular patterns automatically. We then evaluate our approach in the highway discretionary lane-change scenarios using the highD dataset collected from real-world settings. Results demonstrate that our proposed Bayesian nonparametric approach provides an insight into the complicated discretionary lane-change interactions of the ego vehicle with multiple surrounding traffic participants based on the interpretable interaction patterns and their transition properties in temporal relationships. Our proposed approach sheds light on efficiently analyzing other kinds of multi-agent interactions, such as vehicle-pedestrian interactions.</div></td>
      	</tr>
      	<tr id="bib_wang2021spatio" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{zhang2021spatiotemporal,
                    title={Spatiotemporal learning of multivehicle interaction patterns in lane-change scenarios},
                    author={Zhang, Chengyuan and Zhu, Jiacheng and Wang, Wenshuo and Xi, Junqiang},
                    journal={IEEE Transactions on Intelligent Transportation Systems},
                    volume = {23},
                    number = {7},
                    pages = {6446--6459},
                    year={2021},
                    publisher={IEEE}
                    }
                </pre>
			</td>
      	</tr>
      	<tr id="wang2021uncover" class="entry">
      		<td>
				<!-- <img src="../images/research/cui2020establishing.png" width="600" class="single_img"> -->
				<div class="polaroid">
				  <img src="../images/research/wang2021uncover.png" width="600" class="research_img">
				</div>
			</td>
       		<td>H. Wang, <strong>W. Wang*</strong>, S. Yuan, X. Li </td>
			<td>
				Uncovering Interpretable Internal States of Merging Tasks at Highway On-Ramps for Autonomous Driving Decision-Making<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2021uncover','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2021uncover','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9512609">PDF</a>]
              		<!-- [<a href="https://arxiv.org/abs/1508.06033">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a> -->
            	</p>
    		</td>
 			<td>2021</td>
        	<td>IEEE Transactions on Automation Science and Engineering</td>
        </tr>
        <tr id="abs_wang2021uncover" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Humans make daily routine decisions based on their internal states in intricate interaction scenarios. This article presents a probabilistically reconstructive learning approach to identify the internal states of multivehicle sequential interactions when merging at highway on-ramps. We treated the merging task's sequential decision as a dynamic, stochastic process and then integrated the internal states into a hidden Markov model (HMM)-Gaussian mixture regression (GMR) model, a probabilistic combination of an extended GMR and HMM. We also developed a variant of the expectation-maximization (EM) algorithm to estimate the model parameters and verified it based on a real-world dataset. Experiment results reveal that three interpretable internal states can semantically describe the interactive merge procedure at highway on-ramps. This finding provides a basis for developing an efficient model-based decision-making algorithm for autonomous vehicles (AVs) in a partially observable environment.</div></td>
      	</tr>
      	<tr id="bib_wang2021uncover" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{wang2021uncovering,
                      title={Uncovering interpretable internal states of merging tasks at highway on-ramps for autonomous driving decision-making},
                      author={Wang, Huanjie and Wang, Wenshuo and Yuan, Shihua and Li, Xueyuan},
                      journal={IEEE Transactions on Automation Science and Engineering},
                      year={2021},
                      publisher={IEEE}
                    }
                </pre>
			      </td>
      	</tr>
      	<tr id="wang2021learning" class="entry">
      		<td>
				<!-- <img src="../images/research/liang2018deep.png" width="600" class="single_img"> -->
				<div class="polaroid">
				  <img src="../images/research/wang2021learning.png" width="600" class="research_img">
				</div>
			</td>
       		<td><strong>W. Wang</strong>, C. Zhang, P. Wang, C.-Y. Chan </td>
			<td>
				Learning Representations for Multi-Vehicle Spatiotemporal Interactions with Semi-Stochastic Potential Fields<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2021learning','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2021learning','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9304849">PDF</a>]
              		<!-- [<a href="https://arxiv.org/abs/1801.03818">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a> -->
            	</p>
    		</td>
 			<td>2020</td>
        	<td>2020 IEEE Intelligent Vehicles Symposium (IV'20)</td>
        </tr>
        <tr id="abs_wang2021learning" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Reliable representation of multi-vehicle interactions in urban traffic is pivotal but challenging for autonomous vehicles due to the volatility of the traffic environment, such as roundabouts and intersections. This paper describes a semi-stochastic potential field approach to represent multi-vehicle interactions by integrating a deterministic field approach with a stochastic one. First, we conduct a comprehensive evaluation of potential fields for representing multi-agent intersections from the deterministic and stochastic perspectives. For the former, the estimates at each location in the region of interest (ROI) are deterministic, which is usually built using a family of parameterized exponential functions directly. For the latter, the estimates are stochastic and specified by a random variable, which is usually built based on stochastic processes such as the Gaussian process. Our proposed semi-stochastic potential field, combining the best of both, is validated based on the INTERACTION dataset collected in complicated real-world urban settings, including intersections and roundabout. Results demonstrate that our approach can capture more valuable information than either the deterministic or stochastic ones alone. This work sheds light on the development of algorithms in decision-making, path/motion planning, and navigation for autonomous vehicles in the cluttered urban settings.</div></td>
      	</tr>
      	<tr id="bib_wang2021learning" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@inproceedings{wang2020learning,
                    title={Learning Representations for Multi-Vehicle Spatiotemporal Interactions with Semi-Stochastic Potential Fields},
                    author={Wang, Wenshuo and Zhang, Chengyuan and Wang, Pin and Chan, Ching-Yao},
                    booktitle={2020 IEEE Intelligent Vehicles Symposium (IV)},
                    pages={1935--1940},
                    organization={IEEE}
                  }
                </pre>
			    </td>
      	</tr>
      	<tr id="wang2020clustering" class="entry">
      		<td>
				<img src="../images/research/wang2020clustering.png" width="600" class="single_img">
    			</td>
       		<td><strong>W. Wang</strong>, A. Ramesh, et al. </td>
			<td>
				Clustering Driving Encounter Scenarios Using Connected Vehicle Trajectories<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2020clustering','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2020clustering','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/8995532">PDF</a>]
              		<!-- [<a href="https://arxiv.org/abs/1801.02143">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Stacked_Bidirectional_Unidirectional_LSTM">Code</a>] -->
            	</p>
    		</td>
 			<td>2020</td>
        	<td>IEEE Transactions on Intelligent Vehicles</td>
        </tr>
        <tr id="abs_wang2020clustering" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Classification and analysis of driving behaviors offer in-depth knowledge to make an efficient decision for autonomous vehicles. This paper aims to cluster a wide range of driving encounter scenarios based only on multi-vehicle GPS trajectories. Towards this end, we propose a generic unsupervised learning framework comprising of two layers: feature representation layer and clustering layer. In the feature representation layer, we combine the deep autoencoders with a distance-based measure to map the sequential observations of driving encounters into a computationally tractable space, which quantifies the spatiotemporal interaction characteristics of two vehicles. The clustering algorithm is then applied to the extracted representations to cluster homogeneous driving encounters into groups. Our proposed generic framework is then evaluated using 2,568 naturalistic driving encounters. Experimental results show that our proposed generic framework incorporated with unsupervised learning can cluster multi-trajectory data into distinct groups. These clustering results could benefit the decision-making and design of autonomous vehicles</div></td>
      	</tr>
      	<tr id="bib_wang2020clustering" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{wang2020clustering,
                      title={Clustering of driving encounter scenarios using connected vehicle trajectories},
                      author={Wang, Wenshuo and Ramesh, Aditya and Zhu, Jiacheng and Li, Jie and Zhao, Ding},
                      journal={IEEE Transactions on intelligent vehicles},
                      volume={5},
                      number={3},
                      pages={485--496},
                      year={2020},
                      publisher={IEEE}
                    }
                </pre>
			</td>
      	</tr>
      	<tr id="wang2020understanding" class="entry">
      		<td>
				<div class="polaroid">
				  <img src="../images/research/wang2020understanding.png" width="600" class="research_img">
				</div>
			</td>
       		<td><strong>W. Wang</strong>, W. Zhang, J. Zhu, D. Zhao </td>
			<td>
				Understanding v2v driving scenarios through traffic primitives<br>		   
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('wang2020understanding','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('wang2020understanding','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/9184261">PDF</a>]
              		<!-- [<a href="http://www.uwdrive.net/">Website</a>] -->
              		<!-- [<a href="https://www.youtube.com/watch?v=uzOl3cNoLvc">Video</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Graph_Convolutional_LSTM">code</a> -->
            	</p>
    		</td>
 			<td>2020</td>
        	<td>IEEE Transactions on Intelligent Transportation Systems</td>
        </tr>
        <tr id="abs_wang2020understanding" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Understanding driver interaction behavioral semantics has potential benefits to autonomous car’s decision-making design. This article presents a framework of analyzing various encountering behaviors through decomposing driving encounter sequential data into small building blocks, called traffic primitives, using a Bayesian nonparametric learning (BNPL) approach. This framework offers a flexible way to gain semantic insights into complex driving encounters without any prerequisite knowledge of interaction behavior categories. Its effectiveness is then validated using 976 naturalistic driving encounters from which more than 4000 traffic primitives were learned with the BNPL approach. After that, a dynamic time warping method integrated with k-means clustering is then developed to cluster all these extracted traffic primitives into groups. Experimental results identify 20 kinds of traffic primitives capable of representing the essential components of driving encounters in our database. Based on the results, we conclude that the proposed primitive-based analysis could prove useful for autonomous vehicle applications.</div></td>
      	</tr>
      	<tr id="bib_wang2020understanding" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@article{wang2020understanding,
                    title={Understanding v2v driving scenarios through traffic primitives},
                    author={Wang, Wenshuo and Zhang, Weiyang and Zhu, Jiacheng and Zhao, Ding},
                    journal={IEEE Transactions on Intelligent Transportation Systems},
                    volume={23},
                    number={1},
                    pages ={610--619},
                    year={2020},
                    publisher={IEEE}
                  }
                </pre>
		      </td>
      	</tr>
      	<tr id="cui2015vision" class="entry">
      		<td>
				<img src="../images/research/cui2015vision.gif" width="600" class="single_img">
				<!-- <div class="polaroid">
				  <img src="../images/research/cui2015vision.gif" width="600" class="research_img">
				  <div class="container">
				  Rear Light Recognition
				  </div>
				</div> -->
			</td>
       		<td><strong>Z. Cui</strong>, S. Yang, H. Tsai</td>
			<td>
				A vision-based hierarchical framework for autonomous front-vehicle taillights detection and signal recognition<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('cui2015vision','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('cui2015vision','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/7313248">PDF</a>]
              		[<a href="https://www.youtube.com/watch?v=CPfXCHWMZW8">Video</a>]
              		<!-- [<a href="https://arxiv.org/abs/1801.02143">arXiv</a>] -->
              		[<a href="https://github.com/zhiyongc/Vehicle-Rear-Light-Data">Data</a>]
            	</p>
    		</td>
 			<td>2015</td>
        	<td>IEEE International Conference on Intelligent Transportation Systems (ITSC)</td>
        </tr>
        <tr id="abs_cui2015vision" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: Automatically recognizing rear light signals of front vehicles can significantly improve driving safety by automatic alarm and taking actions proactively to prevent rear-end collisions and accidents. Much previous research only focuses on detecting brake signals at night. In this paper, we present the design and implementation of a robust hierarchical framework for detecting taillights of vehicles and estimating alert signals (turning and braking) in the daytime. The three-layer structure of the vision-based framework can obviously reduce both false positives and false negatives of taillight detection. Comparing to other existing work addressing nighttime detection, the proposed method is capable of recognizing taillight signals under different illumination circumstances. By carrying out contrast experiments with existing state-of-the-art methods, the results show the high detection rate of the framework in different weather conditions during the daytime.</div></td>
      	</tr>
      	<tr id="bib_cui2015vision" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@inproceedings{cui2015vision,
  title={A vision-based hierarchical framework for autonomous front-vehicle taillights detection and signal recognition},
  author={Cui, Zhiyong and Yang, Shao-Wen and Tsai, Hsin-Mu},
  booktitle={2015 IEEE 18th International Conference on Intelligent Transportation Systems},
  pages={931--937},
  year={2015},
  organization={IEEE}
}</pre>
			</td>
      	</tr>
      	<tr id="cui2014characterizing" class="entry">
      		<td>
				<img src="../images/research/cui2014characterizing.png" width="600" class="single_img">
				<!-- <div class="polaroid">
				  <img src="../images/research/cui2015vision.gif" width="600" class="research_img">
				  <div class="container">
				  Rear Light Recognition
				  </div>
				</div> -->
			</td>
       		<td><strong>Z. Cui</strong>, S. Yang, H. Tsai</td>
			<td>
				Characterizing channel fading in vehicular visible light communications with video data<br>
              	<p class="infolinks"> 
              		[<a href="javascript:toggleInfo('cui2014characterizing','abstract')">Abstract</a>]
              		[<a href="javascript:toggleInfo('cui2014characterizing','bibtex')">BibTeX</a>] 
              		[<a href="https://ieeexplore.ieee.org/abstract/document/7013353">PDF</a>]
              		<!-- [<a href="https://www.youtube.com/watch?v=CPfXCHWMZW8">Video</a>] -->
              		<!-- [<a href="https://arxiv.org/abs/1801.02143">arXiv</a>] -->
              		<!-- [<a href="https://github.com/zhiyongc/Vehicle-Rear-Light-Data">Data</a> -->
            	</p>
    		</td>
 			<td>2014</td>
        	<td>IEEE Vehicular Networking Conference (VNC)</td>
        </tr>
        <tr id="abs_cui2014characterizing" class="abstract noshow">
        	<td colspan="5"><div align="justify"> <b>Abstract</b>: There is no prior work in characterizing fading caused by vehicle mobility in vehicular visible light communications (V2LC). Different from a radio frequency (RF) communication link, the path loss of a V2LC link is dictated by not only the transmitter-receiver (T-R) distance, but also the irradiance angle and the incidence angle, which have large variation when the vehicles are in motion. In this paper, we took a novel approach to take a first look at the problem. Utilizing the video data obtained from a dashboard camera and computer vision techniques, we are able to estimate the relative location and angle parameters of neighboring vehicles with great level of detail. These parameters are then used to derive a time function of path loss, with which the autocorrelation and the channel coherence time are calculated. Our results show that V2LC links have much slower channel time variation compared to RF V2V links: the coherence time is at least an order larger.</div></td>
      	</tr>
      	<tr id="bib_cui2014characterizing" class="bibtex noshow">
        	<td colspan="5"><b>BibTeX</b>:
              	<pre>@inproceedings{cui2014characterizing,
  title={Characterizing channel fading in vehicular visible light communications with video data},
  author={Cui, Zhiyong and Wang, Chenqi and Tsai, Hsin-Mu},
  booktitle={2014 IEEE Vehicular Networking Conference (VNC)},
  pages={226--229},
  year={2014},
  organization={IEEE}
}</pre>
			</td>
      	</tr>
	</tbody>
</table>

## Teaching

<table style="width:100%">
  <thead>
    <tr>
      <th width="100%">&nbsp;</th>
    </tr>
  </thead>
</table>

<!-- 
### Refereed Journal Publications
1. Yang H, Ke R, **Cui Z**\*, Wang Y\*, Murthy K. (2021) Towards a Real-time Smart Parking Information Management and Prediction (SPIMP) System by Attributes Representation Learning. *International Journal of Intelligent Systems*
1. Pu Z, **Cui, Z**\*, Tang, J., Wang, S., Wang, Y. (2021) Multi-Modal Traffic Speed Monitoring: A Real-Time System Based on Passive Wi-Fi and Bluetooth Sensing Technology. *IEEE Internet of Things Journal*
1.	**Cui Z**, Lin L, Pu Z, Wang Y\*. (2020) Graph Markov Network for Traffic Forecasting with Missing Data. *Transportation Research Part C: Emerging Technologies* (<span style="color: blue;">ASA TSIG Student Paper Award</span>) \[[doi](https://doi.org/10.1016/j.trc.2020.102671)\] \[[arXiv](https://arxiv.org/abs/1912.05457)\] \[[post](https://zhiyongcui.com/blog/2020/07/16/graph-markov-network.html)\] \[[code](https://github.com/zhiyongc/GraphMarkovNetwork)\] 
1.	**Cui Z**, Ke R, Pu Z, Wang Y\*. (2020) Stacked Bidirectional and Unidirectional LSTM Recurrent Neural Network for Forecasting Network-wide Traffic State with Missing Values. *Transportation Research Part C: Emerging Technologies* \[[doi](https://doi.org/10.1016/j.trc.2020.102674)\]
1.	**Cui Z**, Ke R, Pu Z, Ma X, Wang Y\*. (2020) Learning Traffic as a Graph: A Gated Graph Wavelet Recurrent Neural Network for Network-scale Traffic Prediction. *Transportation Research Part C: Emerging Technologies* \[[doi](https://doi.org/10.1016/j.trc.2020.102620)\]
1.	**Cui Z**, Henrickson K, Ke R, Wang Y\*. (2019) Traffic Graph Convolutional Recurrent Neural Network: A Deep Learning Framework for Network-Scale Traffic Learning and Forecasting. *IEEE Transaction on Intelligent Transportation Systems* \[[arXiv](https://arxiv.org/abs/1802.07007)\] \[[code](https://github.com/zhiyongc/Graph_Convolutional_LSTM)\] \[[data](https://github.com/zhiyongc/Seattle-Loop-Data)\]
1.	**Cui Z**, Long Y\*. (2019) Perspectives on Stability and Mobility of Transit Passenger’s Travel Behaviour through Smart Card Data. *IET Intelligent Transport Systems* \[[doi](https://doi.org/10.1049/iet-its.2019.0212)\] \[[arXiv](https://arxiv.org/abs/1508.06033)\]
1.	**Cui Z**, Henrickson K, Biancardo S, Pu Z, Wang Y\*. (2019) Establishing a Multi-Source Data Integration Framework for Transportation Data Analytics. *Journal of Transportation Engineering, Part A: Systems* \[[doi](https://doi.org/10.1061/JTEPBS.0000331)\]
1.	Ma X, Li Y, **Cui Z**\*, Wang Y. (2020) Forecasting Transportation Network Speed Using Deep Capsule Networks with Nested LSTM Models. *IEEE Transaction on Intelligent Transportation Systems* \[[doi](https://ieeexplore.ieee.org/document/9069477)\]
1.  Pu Z, **Cui Z**, Wang S, Wang Y\*. (2020) Time-Aware Gated Recurrent Unit Networks for Road Surface Friction Prediction Using Historical Data. *IET Intelligent Transport Systems* \[[doi](https://ieeexplore.ieee.org/document/9049501)\]
1.	Pu Z, Zhu M, Li W, **Cui Z**, Guo X, Wang Y\*. (2020) Monitoring Public Transit Ridership Flow by Passively Sensing Wi-Fi and Bluetooth Mobile Devices. *IEEE Internet of Things Journal* \[[doi](https://doi.org/10.1109/JIOT.2020.3007373)\]
1. Zhu M, Zhu W, Lutin, J, **Cui Z**, Wang Y. (2020) Developing a Practical Method to Compute State-Level Bus Occupancy Rate. Journal of Transportation Engineering 
1.	Zhang J, Chen F\*, **Cui Z**, Guo Y, Zhu Y. (2020) Deep learning Architecture for Short-term Passenger Flow Forecasting in Urban Rail Transit. *IEEE transaction on Intelligent Transportation Systems* \[[arXiv](https://arxiv.org/abs/1912.12563)\]
1.	Ke R, Li W, **Cui Z**, Wang Y\*. (2020) Two-Stream Multi-Channel Convolutional Neural Network (TM-CNN) for Multi-Lane Traffic Speed Prediction Considering Traffic Volume Impact. *Transportation Research Record* \[[doi](https://doi.org/10.1177/0361198120911052)\]
1.	Ke R, Feng S, **Cui Z**, Wang Y\*. (2020) An advanced framework for microscopic and lane-level macroscopic traffic parameters estimation from UAV video. *IET Intelligent Transport Systems* \[[doi](https://digital-library.theiet.org/content/journals/10.1049/iet-its.2019.0463)\]
1.	Wang Y, **Cui Z**. (2019) The Development of Smart Transportation in Urgent Need of Transportation Data Science (in Chinese). *Urban Transport of China*, 17(3), 8-10. \[[doi](https://doi.org/10.13813/j.cn11-5141/u.2019.0301)\]
1.	Liang Y, **Cui Z**, Tian Y, Chen H, Wang Y\*. (2018) A Deep Generative Adversarial Architecture for Network-Wide Spatial-Temporal Traffic State Estimation. *Transportation Research Record*, 2672(45), 87-105. \[[doi](https://doi.org/10.1177/0361198118798737)\] \[[arXiv](https://arxiv.org/abs/1801.03818)\]
1.	Ke R, Li Z, Kim S, Ash J, **Cui Z**, Wang Y\*. (2017) Real-time bidirectional traffic flow parameter estimation from aerial videos. *IEEE Transactions on Intelligent Transportation Systems*, 18(4), 890-901. \[[doi](https://doi.org/10.1109/TITS.2016.2595526)\]
1.	Chen X, Li Z, Wang Y, **Cui Z**, Shi C, Wu H\*. (2017). Evaluating the impacts of grades on vehicular speeds on interstate highways. *PloS one*, 12(9), e0184142. \[[doi](https://10.1371/journal.pone.0184142)\]


### Refereed Conference Proceedings
1. **Cui Z**, et. al. (2021) Traffic Performance Score for Measuring the Impact of COVID-19 on Urban Mobility. Transportation Research Board 100th Annual Meeting
1. Ke R, **Cui Z**, Chen Y, Zhu M, Wang Y. (2021) IoT System for Real-Time Near-Crash Detection for Automated Vehicle Testing. Transportation Research Board 100th Annual Meeting
1. Pu Z, **Cui Z**, Wang S, Yang H, Wang Y. (2021) Multi-Modal Traffic Speed Monitoring: A Real-Time System Based on Passive Wi-Fi and Bluetooth Sensing Technology. Transportation Research Board 100th Annual Meeting
1. Yin S, Wang J, **Cui Z**, Wang Y. (2020) Attention-Enabled Network-level Traffic Speed Prediction. IEEE International Smart Cities Conference (ISC2) (<span style="color: blue;">Best Paper Award</span>) 
1.	**Cui Z**, Lin L, Pu Z, Wang Y. (2020) Graph Markov Network for Traffic Forecasting with Missing Data. *Transportation Research Board 99th Annual Meeting* 
1.	**Cui Z**, Fu M, Zhu M, Ban X, Wang Y. (2020) Transportation Artificial Intelligence Platform for Traffic Forecasting. *Transportation Research Board 99th Annual Meeting*
1.	**Cui Z**, Henrickson K, Ke R, Dong X, Wang Y. (2019) High-Order Graph Convolutional Recurrent Neural Network: A Deep Learning Framework for Network-Scale Traffic Learning and Forecasting. *Transportation Research Board 98th Annual Meeting* 
1.	**Cui Z**, Henrickson K, Pu Z, Guo G, Wang Y. (2019) A New Multi-Source Traffic Data Integration Framework for Traffic Analysis and Performance Measurement. *Transportation Research Board 98th Annual Meeting*.
1.	**Cui Z**, Ke R, Wang Y. (2017) Deep Bidirectional and Unidirectional LSTM Recurrent Neural Network for Network-wide Traffic Speed Prediction. *ACM SIGKDD International Workshop on Urban Computing* (UrbComp) \[[arXiv](https://arxiv.org/abs/1801.02143)\] \[[code](https://github.com/zhiyongc/Stacked_Bidirectional_Unidirectional_LSTM)\] \[[data](https://github.com/zhiyongc/Seattle-Loop-Data)\]
1.	**Cui Z**, Zhang S, Henrickson K, Wang Y. (2016) New progress of DRIVE Net: An E-science transportation platform for data sharing, visualization, modelling, and analysis. *IEEE International Smart Cities Conference* (ISC2), (pp. 1-2).
1.	**Cui Z**, Long Y, Ke R, Wang, Y. (2015) Characterizing evolution of extreme public transit behavior using smart card data. *IEEE International Smart Cities Conference* (ISC2), (pp. 1-6).
1.	**Cui Z**, Long Y. (2015) Perspectives on Stability and Mobility of Passenger’s Travel Behaviour through Smart Card Data. *ACM SIGKDD International Workshop on Urban Computing* (UrbComp). (presented without copyright) \[[arXiv](https://arxiv.org/abs/1508.06033)\]
1.	**Cui Z**, Yang S W, Tsai H M (2015) A vision-based hierarchical framework for autonomous front-vehicle taillights detection and signal recognition. *IEEE International Conference on Intelligent Transportation Systems* (ITSC), (pp. 931-937). \[[data](https://github.com/zhiyongc/Vehicle-Rear-Light-Data)\] \[[demo](https://www.youtube.com/watch?v=CPfXCHWMZW8)\]
1.	**Cui Z**, Wang C, Tsai H M. (2014) Characterizing channel fading in vehicular visible light communications with video data. *IEEE Vehicular Networking Conference* (VNC), (pp. 226-229).\[[doi](https://doi.org/10.1109/VNC.2014.7013353)\]
1. **Cui Z**, Yang S W, Wang C, Tsai H M. (2014) On addressing driving inattentiveness: Robust rear light status classification using hierarchical matching pursuit. *IEEE 17th International Conference on Intelligent Transportation Systems* (ITSC), (pp. 2243-2244).
1.	Ke R, Li W, **Cui Z**, Wang Y. (2020) Two-Stream Multi-Channel Convolutional Neural Network (TM-CNN) for Multi-Lane Traffic Speed Prediction Considering Traffic Volume Impact. *Transportation Research Board 99th Annual Meeting* 
1.	Pu Z, Guo X, **Cui Z**, Zhu M, Wang Y. (2020) Mining Public Transit Ridership Flow and Origin-Destination Information from Wi-Fi and Bluetooth Sensing Data. *Transportation Research Board 99th Annual Meeting* 
1.	Ke R, Feng S, **Cui Z**, Wang Y. (2019) An Advanced Framework for Traffic Parameters Estimation from UAV Video. *Transportation Research Board 98th Annual Meeting* (No. 19-02564).
1.	Ke R, Li W, **Cui Z**, Wang Y. (2018) Multi-Lane Traffic Pattern Learning and Forecasting Using Convolutional Neural Network. *COTA International Symposium on Emerging Trends in Transportation* (ISETT).
1.	Wang X, MacKenzie D, **Cui Z**. (2017) Complement or Competitor? Comparing car2go and Transit Travel Times, Prices, and Usage Patterns in Seattle. *Transportation Research Board 96th Annual Meeting* (No. 17-06234).
1.	Pu Z, Li Z, Zhu W, **Cui Z**, Wang Y. (2017) Evaluating Safety Effects of Variable Speed Limit System using Empirical Bayesian Before-After Analysis. *Transportation Research Board 96th Annual Meeting* (No. 17-05863).
1.	Gao Y, Swaminathan K, **Cui Z**, Su, L. (2015) Predictive Traffic Assignment: A New Method and System for Optimal Balancing of Road Traffic. *IEEE 18th International Conference on Intelligent Transportation Systems* (ITSC), (pp. 400-407).


<!--1.	Pu Z, **Cui Z**, Vaa T, Wang S, Wang Y. (2020) Road Surface Friction Prediction Based on Gated Recurrent Unit Networks Using 1istorical Data with Missing Values. *Transportation Research Board 99th Annual Meeting* (accepted)-->

## Patents
1.	Wang Y, Ban X, **Cui Z**, Zhu M. (2019) An artificial intelligence platform for network-wide congestion detection and prediction using multi-source data. Connected Cities and Smart Mobility (C2SMART) Research Report (USDOT award number: 69A3551747124)\[[url](http://c2smart.engineering.nyu.edu/2019/04/19/an-artificial-intelligence-platform-for-network-wide-congestion-detection-and-prediction-using-multi-source-data-2/)\]\[[report](http://c2smart.engineering.nyu.edu/wp-content/uploads/2019/07/Transportation_AI%20Platform_FinalReport_C2SMART_Wang.pdf)\]\[[dataset](https://zenodo.org/record/3258904#.Xc2oKldKiUk)\]
2.	Wang Y, **Cui Z**, Henrickson, K. (2018) Pilot Testing of SHRP2 Reliability Data and Analytical Products: Washington. SHRP2 Reliability Project L38 Report.
3.	Hallenbeck M, Ishimaru J, **Cui Z**, Wang Y, Wright D, Zhang W, Henrickson K. (2017) Implementing the Routine Computation and Use of Roadway Performance Measures Within WSDOT. SHRP2 PM Software Research Report. (Grant number: Agreement T1461, Task 16)
4.	Wang Y, Ke R, Zhang W, **Cui Z**, Henrickson K. (2016) Digital roadway interactive visualization and evaluation network applications to WSDOT operational data usage. Washington State Department of Transportation (WSDOT) Research Report (Report number: WA-RD 854.1).\[[report](https://www.wsdot.wa.gov/research/reports/fullreports/854.1.pdf)\] -->
