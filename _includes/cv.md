Boyo is currently working as a Research Assistant at National Taiwan University, Taipei. He broadly studies foundational topics in machine learning. His previous researches mainly focus on building up a reliable system for disaster management using computer vision techniques. He received his BS and MS in Computer Science from [National Taiwan University](https://www.csie.ntu.edu.tw/main.php) in 2016 and 2018, respectively, advised by [Hsuan-Tien Lin](https://www.csie.ntu.edu.tw/~htlin/). Before leaving for ph.D., In 2019, he works at [Appier](https://www.appier.com/) for about one year to acquire experiences in the industry, where he developed a data-intensive API server, handling large-scale data with graphQL.


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3">September 2016 - July 2018</td>
    <td>
        <strong>M.S.</strong> in Computer Science and Information Engineering
        <br>
      National Taiwan University, Taipei, Taiwan
    </td>
  </tr>
  <tr>
    <td class="col-md-3">September 2012 - July 2016</td>
    <td>
        <strong>B.S.</strong> in Computer Science and Information Engineering
        <br>
      National Taiwan University, Taipei, Taiwan
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Working Experience
<table class="table table-hover">
  <tr>
    <td class='col-md-5'>January 2019 - November 2019</td>
    <td>
      <strong>Appier</strong>, Taipei, Taiwan, Software Engineer
    </td>
  </tr>
  <tr>
    <td class='col-md-5'>September 2018 - December 2018</td>
    <td>Military Service in Taiwan.</td>
  </tr>
  <tr>
    <td class='col-md-5'>July 2017 - August 2017</td>
    <td><strong>Yahoo</strong>, Taipei, Taiwan, Software Engineer Intern</td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Publications

<table class="table table-hover">
  <tr>
  <td class="col-md-3"><img src="images/publications/chen2018rotation.png"/></td>
  <td>
      <strong>Rotation-blended CNNs on a new open dataset for tropical cyclone image-to-intensity regression</strong><br>
      <strong>Boyo Chen</strong>, Buo-Fu Chen, Hsuan-Tien Lin<br>
      KDD 2018<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2018rotation").toggle()'>abs</a>] [<a href='https://www.csie.ntu.edu.tw/~htlin/paper/doc/kdd18tcir.pdf' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2018rotation" style="text-align: justify; display: none" markdown="1">
  Tropical cyclone (TC) is a type of severe weather systems that occur in tropical regions. Accurate estimation of TC intensity is crucial for disaster management. Moreover, the intensity estimation task is the key to understand and forecast the behavior of TCs better. Recently, the task has begun to attract attention from not only meteorologists but also data scientists. Nevertheless, it is hard to stimulate joint research between both types of scholars without a benchmark dataset to work on together. In this work, we release a such a benchmark dataset, which is a new open dataset collected from satellite remote sensing, for the TC-image-to-intensity estimation task. We also propose a novel model to solve this task based on the convolutional neural network (CNN). We discover that the usual CNN, which is mature for object recognition, requires several modifications when being used for the intensity estimation task. Furthermore, we combine the domain knowledge of meteorologists, such as the rotation- invariance of TCs, into our model design to reach better performance. Experimental results on the released benchmark dataset verify that the proposed model is among the most accurate models that can be used for TC intensity estimation, while being relatively more stable across all situations. The results demonstrate the potential of applying data science for meteorology study.
  </div>

  In this work, we apply <strong>specialized</strong> CNN to tropical cyclone intensity regression tasks, set up a remarkable benchmark for disaster management of tropical cyclones. The proposed framework is used for forecasting in <a href="https://www.cwb.gov.tw/eng/">Central Weather Bureau, Taiwan</a>.
  </td>
  </tr>

  <tr>
  <td class="col-md-3"><img src="images/publications/chen2019estimating.png"/></td>
  <td>
      <strong>Estimating Tropical Cyclone Intensity by Satellite Imagery Utilizing Convolutional Neural Networks</strong><br>
      Buo-Fu Chen, <strong>Boyo Chen</strong>, Hsuan-Tien Lin<br>, Russell L. Elsberry
      KDD 2018<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2019estimating").toggle()'>abs</a>] [<a href='https://journals.ametsoc.org/waf/article/34/2/447/291' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2019estimating" style="text-align: justify; display: none" markdown="1">
  Accurately estimating tropical cyclone (TC) intensity is one of the most critical steps in TC forecasting and disaster warning/management. For over 40 years, the Dvorak technique (and several improved versions) has been applied for estimating TC intensity by forecasters worldwide. However, the operational Dvorak techniques primarily used in various agencies have several deficiencies, such as inherent subjectivity leading to inconsistent intensity estimates within various basins. This collaborative study between meteorologists and data scientists has developed a deep-learning model using satellite imagery to estimate TC intensity. The conventional convolutional neural network (CNN), which is a mature technology for object classification, requires several modifications when being used for directly estimating TC intensity (a regression task). Compared to the Dvorak technique, the CNN model proposed here is objective and consistent among various basins; it has been trained with satellite infrared brightness temperature and microwave rain-rate data from 1097 global TCs during 2003–14 and optimized with data from 188 TCs during 2015–16. This paper also introduces an upgraded version that further improves the accuracy by using additional TC information (i.e., basin, day of year, local time, longitude, and latitude) and applying a postsmoothing procedure. An independent testing dataset of 94 global TCs during 2017 has been used to evaluate the model performance. A root-mean-square intensity difference of 8.39 kt (1 kt ≈ 0.51 m s−1) is achieved relative to the best track intensities. For a subset of 482 samples analyzed with reconnaissance observations, a root-mean-square intensity difference of 8.79 kt is achieved.
  </div>

  In this journal work, we verified and concluded our work in 2018. The report was published by <strong>Weather and Forecasting</strong>, the best journal in the related field.
  </td>
  </tr>

  <tr>
  <td class="col-md-3"><img src="images/publications/chen2021real.png"/></td>
  <td>
      <strong>Real-time Tropical Cyclone Intensity Estimation by Handling Temporally Heterogeneous Satellite Data</strong><br>
      <strong>Boyo Chen</strong>, Buo-Fu Chen, Yun-Nung Chen
      Under review of AAAI2021<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2021real").toggle()'>abs</a>] [<a href='https://arxiv.org/abs/2010.14977' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2021real" style="text-align: justify; display: none" markdown="1">
  Analyzing big geophysical observational data collected by multiple advanced sensors on various satellite platforms promotes our understanding of the geophysical system. For instance, convolutional neural networks (CNN) have achieved great success in estimating tropical cyclone (TC) intensity based on satellite data with fixed temporal frequency (e.g., 3 h). However, to achieve more timely (under 30 min) and accurate TC intensity estimates, a deep learning model is demanded to handle temporally-heterogeneous satellite observations. Specifically, infrared (IR1) and water vapor (WV) images are available under every 15 minutes, while passive microwave rain rate (PMW) is available for about every 3 hours. Meanwhile, the visible (VIS) channel is severely affected by noise and sunlight intensity, making it difficult to be utilized. Therefore, we propose a novel framework that combines generative adversarial network (GAN) with CNN. The model utilizes all data, including VIS and PMW information, during the training phase and eventually uses only the high-frequent IR1 and WV data for providing intensity estimates during the predicting phase. Experimental results demonstrate that the hybrid GAN-CNN framework achieves comparable precision to the state-of-the-art models, while possessing the capability of increasing the maximum estimation frequency from 3 hours to less than 15 minutes.
  </div>
  Due to the limitation of satellites, the previous work of estimating Tropical Cyclone(TC) intensity can only obtain data once every 3 hours. In this work, we use Generative Adversarial Networks to handle missing data. As a result, the frequency for estimating the TC intensity improved from once per <strong>3 hours</strong> to once per <strong>15 minutes</strong>.
  </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Teaching Experience

<table class="table table-hover">
  <tr>
    <td class='col-md-2'>2016 fall</td>
    <td>
      <strong>Machine Learning Foundations</strong>, TA<br>
      About 100 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mlfound16fall">course link</a>
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>2017 spring</td>
    <td>
      <strong>Machine Learning Techniques</strong>, TA<br>
      About 130 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mltech17spring">course link</a>
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>2017 fall</td>
    <td>
      <strong>Machine Learning Foundations</strong>, TA<br>
      About 260 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mlfound17fall">course link</a>
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>2018 spring</td>
    <td>
      <strong>Machine Learning Techniques</strong>, TA<br>
      About 200 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mltech18spring">course link</a>
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Skills

<table class="table table-hover">
  <tr>
    <td class='col-md-3'>Proficient</td>
    <td>
      Python programming.<br>
      Machine learning algorithms and applications.<br>
      Data-intensive applications.
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>Intermediate</td>
    <td>
      C/C++ programing.<br>
      Document-oriented databases, such as MongDB.<br>
      Build and maintain Restful API and GraphQL API.<br>
      Distributed computing with Apache Spark.
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>With Primary Knowledge</td>
    <td>
      CICD: Jenkins, Docker, Kubernates.<br>
      Relation-oriented databases such as PostgreSQL and MySQL.<br>
      Object-oriented programming using Java, Android.
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Life

<table class="table table-hover">
  <tr>
    <td class='col-md-3'>I married my wife on July 27, 2018.</td>
    <td class='col-md-1'>
      <a href="/images/wedding_large.png">
        <img src="images/wedding.png"/>
      </a>
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>We have two cats, one daughter.</td>
    <td class='col-md-1'>
      <a href="/images/family.png">
        <img src="images/family.png"/>
      </a>
    </td>
  </tr>
</table>
