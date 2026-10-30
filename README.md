# Jacob Lehner — Coastal Geospatial & Machine Learning Portfolio

Geospatial data scientist working with LiDAR elevation data, remote sensing and deep learning to map and track how coastlines change. PhD, Earth Sciences (University of Windsor, 2025); Project Manager, Coastal Erosion Planning and Response Act (CEPRA) program, Texas General Land Office.

📚 [Google Scholar](https://scholar.google.com/citations?user=bqUO7qIAAAAJ&hl=en&oi=ao) · 💼 [LinkedIn](https://www.linkedin.com/in/jacob-lehner-116a2380) · ✉️ jdavislehner@gmail.com

---

## Projects

### 1. Deep-learning landform segmentation from LiDAR
DeepLabV3+ model that maps beach, dune, hummock and backbarrier landforms from elevation data (~97.8% accuracy), then applied to 18 years of surveys to track dune change.

<img src="01-landform-segmentation-deeplab/figures/deeplab-multi-year-predictions.png" width="750" alt="DeepLabV3+ predictions across survey years">

**Python · TensorFlow/Keras · DeepLabV3+ · watershed segmentation** → [Project folder](01-landform-segmentation-deeplab/)

---

### 2. Unsupervised dune classification with a masked autoencoder
Self-supervised model that compresses 1,800 dune elevation samples from 12 coastal sites, then clusters them into 16 distinct dune shape types.

<img src="02-dune-morphology-autoencoder/figures/dbscan-clusters.png" width="650" alt="UMAP clusters">


**Python · TensorFlow · masked autoencoder · UMAP · DBSCAN** → [Project folder](02-dune-morphology-autoencoder/)

---

### 3. 3D ridge-and-swale mapping of barrier islands
A method that uses surface-normal vectors to pull ridges and swales out of a LiDAR elevation model in both directions, exposing dune structures that profile-based methods miss. *Published in Geomorphology (2024).*

<img src="03-ridge-swale-3d/figures/variable-morphologies.png" width="600" alt="Ridge and swale patterns on Padre Island">

**GIS · terrain analysis · multi-scale moving windows** → [Project folder](03-ridge-swale-3d/)

---

### 4. Comparing and explaining landform classifiers
Neural network, random forest and decision tree compared for landform mapping from LiDAR and aerial imagery (random forest ~98.7%, neural network ~97.7%), with SHAP values showing which inputs drive each prediction.

<img src="04-landform-classifier-comparison/figures/shap-feature-importance.png" width="600" alt="SHAP feature importance">

**R · keras · random forest · rpart · SHAP** → [Project folder](04-landform-classifier-comparison/)

---

### 5. Current research interests
Current research interests are aimed at large scale tool development for whole coast analysis, inter- and intra-site representative power of barrier island morphology, and translating alongshore resistance/resilience variability in barrier dune systems translates to evolution and potential management practices. → [Project folder](05-current-research-interests/)


---

## Selected collaborative research

#### Machine learning analysis of rip current warnings and rescues
Houser, C., **Lehner, J.**, Wernette, P., and Cherry, N. (2019). *Natural Hazards and Earth System Sciences*, 19, 2541–2549. 

#### Comparing dune toe extraction methods
Smith, A., **Lehner, J.**, Wills, C., Johnson, G. and Houser, C. (2025). *Science of the Total Environment*, 979, 179277. 

#### Separating real erosion and deposition from data uncertainty
Wernette, P., **Lehner, J.**, and Houser, C. (2020). *Geomorphology*, 355, 107083. 

#### Hurricane Harvey impacts on beach-dune morphology
Wernette, P., Houser, C., **Lehner, J.**, and Weymer, B. (2020). *Geomorphology*, 358, 107119. 

**Perspective:** Houser, C., **Lehner, J.**, and Smith, A. (2022). The field geomorphologist in a time of machine learning and artificial intelligence. *Annals of the American Association of Geographers*. 

📚 Full publication list: [Google Scholar](https://scholar.google.com/citations?user=bqUO7qIAAAAJ&hl=en&oi=ao)

---

*Code in this repository is research code written during my PhD. It is shared to show methods and workflow and is not a packaged library. Source LiDAR data are publicly available from NOAA Digital Coast / USACE JALBTCX.*
<!-- Co-authored work. Each entry states my contribution. -->
<!-- FIGURE: add collaborative/rip-current-ml.png -->
<!-- *My role: [e.g., built the ML models and ran the analysis]* -->
