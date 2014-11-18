# Setup H<sub>2</sub>O World Training Sandbox

## 1. Prerequisites
  * VirtualBox
    * Provided on H<sub>2</sub>O World USB sticks, or
    * Available for [download](https://www.virtualbox.org/wiki/Downloads)

  * H<sub>2</sub>O World Training Sandbox Image (*.ova* format)
    * Provided on H<sub>2</sub>O World USB sticks, or
    * Available for [download](https://s3.amazonaws.com/h2o-release/h2o/sandbox/h2oworld-training.ova) (4GB)

> Note: You can use also your favorite virtualization tool like VMWare Fusion, VMWare Player, or Microsoft Hyper-V.

## 2. Setup Sandbox
  * Start VirtualBox
  ![VirtualBox Application](images/01_virtualbox.png)

  * Select the menu item _File > Import Appliance_
  ![VirtualBox Menu](images/02_vb_menu.png)

  * Import wizard is shown
  ![Select file](images/03_select_file.png)

  * Open provided _h2oworld-training.ova_ file from USB drive
  ![Select file](images/04_import_wizard.png)

  * Review configurations of the image file and hit Import
  ![Import Image](images/boot01.png)

## 3. Launch Sandbox
  * Select h2oworld-training item and click on _Start_ icon
  ![Manager](images/boot03.png)

  * Login screen
  ![Login](images/boot04.png)

### 3.1 Sandbox Credentials
 * user: `h2o`, password: `h2o`

> Note: To access _root_ user account, use `sudo su -` or password `h2o`.


## 4. Sandbox Content
  * [H<sub>2</sub>O v2.8.2.8 - "Maxwell"](http://h2o-release.s3.amazonaws.com/h2o/rel-maxwell/8/index.html)
  * [Sparkling Water v0.2.1-31](http://h2o-release.s3.amazonaws.com/sparkling-water/master/31/index.html)
  * [RStudio Desktop v0.98.1091](http://www.rstudio.com/products/rstudio/download/)
  * [R version 3.1.1 (2014-07-10) - "Sock it to Me"](http://www.r-project.org)
    * [H<sub>2</sub>O R package v2.8.2.8](http://h2o-release.s3.amazonaws.com/h2o/rel-maxwell/8/index.html#R)
  * [Spark v1.1.0 for Hadoop 2.4](https://spark.apache.org/downloads.html)
  * Git v1.7.1
  * Oracle JDK v1.7.0_45
  * [IntelliJ Idea 14 Community Edition](https://www.jetbrains.com/idea/download/)

