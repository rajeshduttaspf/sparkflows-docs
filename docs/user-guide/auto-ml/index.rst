AutoML
=====================

AutoML aims to automate all the tasks involved in developing and deploying machine learning models, from cleaning the raw data all the way through to parameter optimization.
As well as making data scientists much more productive, AutoML tools can be used by non-experts to run the same dataset against combinations of hundreds or even thousands of different algorithms simultaneously to arrive at the optimal AI model. Contrast that scenario with a data scientist hand coding to create a data pipeline, build the model, do all the testing and then run the dataset against a handful of algorithms.

Fire provide the option to create the AutoML experiments by selecting the data and type of package. Each experiment will provide the leaderboard with different models & the hyperparameters used in the experiments.All experiments can be compared to decide the best fit for that particular use case.

.. figure:: ../../_assets/auto-ml/automl-steps.png
      :alt: auto-ml
      :width: 90%
      


By default in fire AutoML function is disabled.And once is enabled in the fire configuration, user's can see the option to create the automl experiments in project page.

.. figure:: ../../_assets/auto-ml/automl-exp-page.png
      :alt: auto-ml
      :width: 90%
      

Currently fire supports H2O and Pycaret AutoML packages.
--------------------------------------------


.. panels::
    :container: container-lg pb-2

    :doc:`/user-guide/auto-ml/h2o`

    H2O AutoML packge is used in experiments.

    ---

    :doc:`/user-guide/auto-ml/pycaret`

    Pycaret AutoML package is used in experiments.


.. toctree::
   :hidden:

   h2o.rst
   pycaret.rst
   



Model Comparison
------------------

* Select 2 AutoML experiment to compare accross model and then click on the compare button to view and compare executions of different experiment.

.. figure:: ../../_assets/auto-ml/ml-compare-1.PNG
      :alt: auto-ml
      :width: 90%
      
      
* Select execution of 2 different experiment to compare
      
* Clicking the compare button will display the comparison among the two models

.. figure:: ../../_assets/auto-ml/ml-compare-2.PNG
      :alt: auto-ml
      :width: 90%
      
      
.. figure:: ../../_assets/auto-ml/ml-compare-3.PNG
      :alt: auto-ml
      :width: 90%
      
* On clicking model name we can view the model details

.. figure:: ../../_assets/auto-ml/ml-compare-4.PNG
      :alt: auto-ml
      :width: 90%      


