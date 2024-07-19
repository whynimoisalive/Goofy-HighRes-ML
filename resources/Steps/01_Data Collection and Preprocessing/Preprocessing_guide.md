1. **Atmospheric Correction:**
    - Atmospheric correction is crucial for removing atmospheric effects (such as scattering and absorption) from remote sensing images. It ensures that the observed radiance values are consistent and comparable across different images.

   - NASA's Atmospheric Correction Tool (ACT): [Link](https://atmosphere.nasa.gov/atmospheric-correction-tool)
   - Py6S: A Python interface for the 6S Radiative Transfer Model used in atmospheric correction: [GitHub](https://github.com/robintw/Py6S)
   
   - One popular tool for atmospheric correction is **MAJA (MACCS-ATCOR Joint Algorithm)**. It's specifically designed for Sentinel-2 imagery and performs both atmospheric correction and cloud detection¹. You can find the [GitHub repository for MAJA here](https://github.com/CNES/MAJA).
   - Additionally, the **SIAC (Sensor Invariant Atmospheric Correction)** method is useful for correcting sensor-specific effects in satellite imagery. The [SIAC GitHub repository](https://github.com/MarcYin/SIAC) provides an implementation.

2. **Radiometric Calibration:**
   - Radiometric Calibration Handbook by NASA: [Link](https://calvalportal.ceos.org/wordpress/wp-content/uploads/2018/03/CEOS-Radiometric-Calibration-Handbook.pdf)
   - PyRadiomics: A Python package for radiomic feature extraction in medical imaging: [GitHub](https://github.com/Radiomics/pyradiomics)
   - Radiometric calibration ensures that pixel values in an image correspond to physical quantities (e.g., reflectance). For this, you might want to explore the **ARCSI (Atmospheric and Radiometric Correction of Satellite Imagery)** software. It provides a command-line tool for atmospheric correction and radiometric calibration of Earth observation imagery⁴. You can find the [ARCSI GitHub repository here](https://github.com/remotesensinginfo/arcsi).

3. **Orthorectification:**
   - ESA SNAP (Sentinel Application Platform) for orthorectification of satellite images: [Link](https://step.esa.int/main/toolboxes/snap/)
   - Orfeo Toolbox (OTB): Open-source library for satellite image processing including orthorectification: [GitHub](https://github.com/orfeotoolbox/otb)
   - Orthorectification corrects geometric distortions caused by terrain relief and sensor viewing angles. An excellent tool for orthorectifying images from drone or aerial surveys is **OpenDroneMap**. The [orthorectify module in OpenDroneMap](https://github.com/OpenDroneMap/orthorectify) allows you to orthorectify individual images based on an existing reconstruction.

4. **Co-registration of Multi-source Data:**
    - Co-registering data from different sources (e.g., optical, SAR, LiDAR) ensures spatial alignment. While there isn't a specific GitHub repository for this task, you can achieve it using tools like **GDAL (Geospatial Data Abstraction Library)** or **QGIS**. These tools provide functionalities for georeferencing and aligning different datasets.
   - GDAL (Geospatial Data Abstraction Library): Tools for geospatial data transformation and co-registration: [GitHub](https://github.com/OSGeo/gdal)
   - ESA SNAP: Provides tools for co-registration of optical, SAR, and LiDAR data: [Link](https://step.esa.int/main/toolboxes/snap/)

5. **Image Contrast Enhancement and Noise Reduction:**
    - For enhancing image contrast and reducing noise, consider exploring image processing libraries such as **OpenCV** or **scikit-image** (Python-based). While these libraries don't have specific repositories for remote sensing, they offer a wide range of functions for image enhancement and noise reduction.
   - OpenCV: Open-source computer vision library with functions for image enhancement and noise reduction: [GitHub](https://github.com/opencv/opencv)
   - ImageJ: An open-source image processing program with plugins for contrast enhancement and noise reduction: [Link](https://imagej.net/)

6. **Research Papers:**
   - SCI-HUB + ieexplore: Search for specific research papers on topics like "atmospheric correction," "radiometric calibration," etc.: [IEEE Xplore](https://ieeexplore.ieee.org/)


---
Source: Conversation with Copilot, 19/7/2024
(1) Remote Sensing Data Preprocessing Technology | SpringerLink. https://link.springer.com/chapter/10.1007/978-981-99-0703-8_2.
(2) Processing and Applications of Remotely Sensed Data. https://link.springer.com/referenceworkentry/10.1007/978-3-319-23386-4_92.
(3) Digital Image Acquisition: Preprocessing and Data Reduction. https://link.springer.com/referenceworkentry/10.1007/978-1-4419-7671-0_46.
(4) Fundamentals of Remote Sensing Imaging and Preliminary Analysis - Springer. https://link.springer.com/referenceworkentry/10.1007/978-3-319-23386-4_46.
(5) GitHub - raghavkhanna/radical: radiometric camera calibration. https://github.com/raghavkhanna/radical.
(6) Implementation of radiometric calibration techniques - GitHub. https://github.com/wiennat/radcalib.
(7) GitHub - taketwo/radical: Tools for radiometric calibration of consumer .... https://github.com/taketwo/radical.
(8) radiometric-calibration · GitHub Topics · GitHub. https://github.com/topics/radiometric-calibration.
(9) atmospheric-correction · GitHub Topics · GitHub. https://github.com/topics/atmospheric-correction.
(10) atmospheric-correction · GitHub Topics · GitHub. https://github.com/topics/atmospheric-correction?l=python&o=desc&s=updated.
(11) atmospheric-correction · GitHub Topics · GitHub. https://github.com/topics/atmospheric-correction?o=desc&s=updated.
(12) Software to automate the production of optical analysis ready ... - GitHub. https://github.com/remotesensinginfo/arcsi.
(13) cr0wst/spring-boot-multiple-datasource - GitHub. https://github.com/cr0wst/spring-boot-multiple-datasource.
(14) Merge Multiple Git Repositories without Breaking File History. https://blog.akshaykaushik.eu.org/merge-multiple-git-repositories-without-breaking-file-history.
(15) GitHub - a1k0r/multi-data-source: Node.js library for multiple data .... https://github.com/a1k0r/multi-data-source.
(16) github - Add collaborator to many repositories at once - Stack Overflow. https://stackoverflow.com/questions/52378563/add-collaborator-to-many-repositories-at-once.
(17) Orthorectify images from ODM reconstruction - GitHub. https://github.com/OpenDroneMap/orthorectify.
(18) GitHub - bchao1/awesome-image-rectification: A curated list of image .... https://github.com/bchao1/awesome-image-rectification.
(19) GitHub - fh2019ustc/Awesome-Document-Image-Rectification: A .... https://github.com/fh2019ustc/Awesome-Document-Image-Rectification.
(20) GitHub - shallowlearn/gwarp: Software to create true ortho photos of .... https://github.com/shallowlearn/gwarp.
(21) GitHub - leftfield-geospatial/orthority: Orthorectify drone, aerial and .... https://github.com/leftfield-geospatial/orthority.
(22) undefined. https://theia.cnes.fr.
(23) undefined. https://hub.docker.com/r/mundialis/arcsi/.
(24) undefined. https://dev.to/cr0wst/multiple-jpa-data-sources-with-spring-boot-and-kotlin-1861.
(25) undefined. https://github.com/your-username/combined-repo.git.
