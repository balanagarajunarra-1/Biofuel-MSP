## Abstract of the Project
<div align='justify'>
The aviation sector plays a crucial role in quickly moving people and goods around the world. It also greatly helps in the economic growth and social integration of countries. As the industry continues to experience rapid growth, there is a tendency for an increase in emissions associated with the industry. 

Sustainable aviation fuel (SAF) presents a way to reduce the environmental effects of the aviation industry by providing a clean-burning, renewable substitute for conventional jet fuel. SAF can be produced from diverse processes and feedstocks. Fast pyrolysis (FP) is a promising thermochemical process for SAF production due to its advantages including low-cost feedstocks, faster reaction times, and simpler technology, making it more cost-effective and scalable compared to other thermochemical processes. However, the preliminary estimation of the economic viability of FP for SAF production is complex and tedious requiring detailed process models and several assumptions. Moreover, the relationship between the feedstock properties and the minimum selling price of fuel (MSP) is often challenging to estimate. 

To address these challenges, the present study developed a data-driven framework for preliminary estimation of the MSP of SAF from FP. The target output feature is MSP. To enhance model accuracy and predictions, synthetic data was created using Generative Adversarial Networks (GAN) and Variational Autoencoders (VAE), and hyperparameter optimization was conducted using Grid Search. Five surrogate models were evaluated: linear regression, gradient boost regression (GBR), random forest (RF), extreme boost regression (XGBoost), and Elastic net. GBR and RF showed the most promise based on metrics like R², RMSE, and MAE for both original and synthetic datasets. Specifically, GBR achieved a Train R² of 0.9999 and a Test R² of 0.9277, while RF had Train and Test R² scores of 0.9789 and 0.9255, respectively. 

The use of data from the VAE notably enhanced model accuracy. Additionally, a publicly available GUI has been developed for researchers to estimate the MSP of Sustainable Aviation Fuel (SAF) based on biomass properties, plant capacity, and location.
</div>

## Follow This QR CODE to test the GUI of Deployed Model
![alt text](https://github.com/balanagarajunarra-1/Biofuel-MSP/blob/31bad13ecf9d9f8ce270936ca8721441974c1b2e/app/QR%20CODE.jpeg)
