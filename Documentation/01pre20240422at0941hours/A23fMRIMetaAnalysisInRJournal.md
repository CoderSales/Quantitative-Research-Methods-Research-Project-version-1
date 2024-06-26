# [fMRI-Meta-Analysis-in-R-Journal](https://journal.r-project.org/archive/2014/RJ-2014-020/RJ-2014-020.pdf)

Google Search: [site: https://journal.r-project.org/archive/ fmri](https://www.google.com/search?q=site%3A+https%3A%2F%2Fjournal.r-project.org%2Farchive%2F+fmri&newwindow=1&sca_esv=288b86a47c11e67b&sca_upv=1&sxsrf=ACQVn0_HhgMPrY5Yc2tEh0-rKyNlh6ruCg%3A1713191146571&source=hp&ei=6jgdZvbxH7yDhbIPkea90A4&iflsig=ANes7DEAAAAAZh1G-p2HeJjQfo6rgh3BCeETTN1Zx00o&ved=0ahUKEwj2juKttsSFAxW8QUEAHRFzD-oQ4dUDCBY&uact=5&oq=site%3A+https%3A%2F%2Fjournal.r-project.org%2Farchive%2F+fmri&gs_lp=Egdnd3Mtd2l6IjFzaXRlOiBodHRwczovL2pvdXJuYWwuci1wcm9qZWN0Lm9yZy9hcmNoaXZlLyBmbXJpSLdpUABYwGdwAHgAkAEAmAFqoAGUBqoBBDExLjG4AQPIAQD4AQL4AQGYAgGgAnDCAgUQIRigAZgDAJIHAzAuMaAHgwo&sclient=gws-wiz)

[The R Journal: article published in 2014, volume 6:2](https://journal.r-project.org/archive/2014/RJ-2014-020/index.html)

[Coordinate-Based Meta-Analysis of fMRI Studies with R by Andrea Stocco](https://journal.r-project.org/archive/2014/RJ-2014-020/RJ-2014-020.pdf)

____

## Attempt to Run Code

### Code

```r
library(fmri)
```

### Code and Error

```r
> library(fmri)
Error in library(fmri) : there is no package called ‘fmri’
```

____

Google Search: [r install fmri](https://www.google.com/search?q=r+install+fmri&oq=r+install+fmri&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQRRhAMgYIAhBFGEDSAQgyODIzajBqN6gCALACAA&sourceid=chrome&ie=UTF-8)

____

[fmri: Analysis of fMRI Experiments](https://cran.r-project.org/web/packages/fmri/index.html)

____

Google Search: [how to install r package from file](https://www.google.com/search?q=how+to+install+r+package+from+file&oq=how+to+install+r+package+from+file&gs_lcrp=EgZjaHJvbWUyCggAEEUYFhgeGDkyCAgBEAAYFhgeMggIAhAAGBYYHjIKCAMQABiABBiiBDIKCAQQABiABBiiBDIGCAUQRRhA0gEINTA4N2owajeoAgCwAgA&sourceid=chrome&ie=UTF-8)

```r
install.packages(path_to_file, repos = NULL, type="source")
```

[How do I install an R package from source? | StackOverflow](https://stackoverflow.com/questions/1474081/how-do-i-install-an-r-package-from-source)

____

```r
> install.packages("C:/Users/steph/Downloads/fmri_1.9.12.tar.gz", repos = NULL, type="source")
WARNING: Rtools is required to build R packages but is not currently installed. Please download and install the appropriate version of Rtools before proceeding:

https://cran.rstudio.com/bin/windows/Rtools/
Installing package into ‘C:/Users/steph/AppData/Local/R/win-library/4.3’
(as ‘lib’ is unspecified)
ERROR: dependencies 'metafor', 'aws', 'oro.nifti' are not available for package 'fmri'
* removing 'C:/Users/steph/AppData/Local/R/win-library/4.3/fmri'
Warning in install.packages :
  installation of package ‘C:/Users/steph/Downloads/fmri_1.9.12.tar.gz’ had non-zero exit status

```

____

```r
install.packages("metafor")
```

[The metafor Package | A Meta-Analysis Package for R | Download and Installation](https://www.metafor-project.org/doku.php/installation)

____

Google Search: [r install aws](https://www.google.com/search?q=r+install+aws&oq=r+install+aws&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yCAgCEAAYFhgeMg0IAxAAGIYDGIAEGIoFMgoIBBAAGIAEGKIEMgYIBRBFGEAyBggGEEUYQNIBCDM0MDRqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8)

[AWS S3 Client Package](https://cran.r-project.org/web/packages/aws.s3/readme/README.html)

____

[key management service](https://us-east-1.console.aws.amazon.com/kms/home?region=us-east-1#/kms/home)

better:

[Authentication and access control for AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/control-access.html)

aws:

[Running R on AWS](https://aws.amazon.com/blogs/big-data/running-r-on-aws/)

____

[Creating a cluster with earlier AMI versions of Amazon EMR](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-3x-create.html)

[Installing applications with earlier AMI versions of Amazon EMR](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-3x-install-apps.html)

[Amazon EMR 2.x and 3.x AMI versions](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-release-3x.html)

[Statistical Analysis with Open-Source R and RStudio on Amazon EMR](https://aws.amazon.com/blogs/big-data/statistical-analysis-with-open-source-r-and-rstudio-on-amazon-emr/)

[Running R on AWS](https://aws.amazon.com/blogs/big-data/running-r-on-aws/)

[how to configure r aws](https://www.google.com/search?q=how+to+configure+r+aws&oq=how+to+configure+r+aws&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQRRhA0gEINTE3NmowajeoAgCwAgA&sourceid=chrome&ie=UTF-8)

Google Search: [aws s3 r](https://www.google.com/search?q=aws+s3+r&oq=aws+s3+r&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIGCAYQRRg8MgYIBxBFGDzSAQg0NTAyajBqN6gCALACAA&sourceid=chrome&ie=UTF-8)

[cloudyr/aws.s3](https://github.com/cloudyr/aws.s3)



[Console Home](https://us-east-1.console.aws.amazon.com/console/home?nc2=h_ct&src=header-signin&region=us-east-1)

[aws cli](https://www.google.com/search?q=waws+cli&oq=waws+cli&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIPCAEQABgKGIMBGLEDGIAEMgkIAhAAGAoYgAQyCQgDEAAYChiABDIJCAQQABgKGIAEMgkIBRAAGAoYgAQyCQgGEAAYChiABDIJCAcQABgKGIAEMgkICBAAGAoYgAQyCQgJEAAYChiABNIBCDE4MDZqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8)

[Install or update to the latest version of the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
