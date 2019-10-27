---
title: "README"
author: "nikeisha"
date: "26/10/2019"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

The purpose of this analysis was to identify differentially expressed proteins within the Slime secreted by the striped pyjama squid, Sepioloidea lineolata. This repository contains a complete set of R scripts and raw data required to reproduce analyses in Caruana et al ...

Setup

Before running the scripts in this repository you will need to download the raw data which is hosted on Amazon S3 rather than github.

First clone this git repository

```{bash}
git clone https://github.com/marine-omics/slineolata_quantification.git
```

Change directory so you are in the top level repository directory

```{bash}
cd slineolata_quantification
```

Download the raw data and unpack it

```{bash}
wget https://s3-ap-southeast-2.amazonaws.com/marine-omics.net/public/input_data.tgz
tar -zxvf input_data.tgz
```

