---
title: Handy Download Script - Plant Village Dataset
date: 2017-04-26
---

<article class="post-content">
    <p>Plant Village Images is an open access database of 80,000+ images of healthy and diseased crops. It is a tremendously generous effort by Penn State University and EPFL.
In order to download the images, you need to download 82 <strong>csv</strong> files segregated based on the plants with the diseases they are infected with. These files, then have the links to the actual images.
Well, the dataset is ~40GB in size. Imagine scraping 82 files where the total downloaded data amounts to ~40GB.
Moreover, the files are also infused with certain metadata which needs to be cleaned before you can scrape them.</p>

<p>You also need to sign up and create an account on the website for achieving all this. All this causes a little pain given the noble intentions behind the effort.
To make this dataset more accessible, I have pre-downloaded all the <strong>csv</strong> files, cleaned them off their metadata and written a tiny script to make scraping them much easier and interactive.</p>

<p>You can download the entire 1.7MB package <a href="https://drive.google.com/file/d/0BwrR3ZPLVYhkWmxSQTdHY3NPbU0/view">here</a>.</p>

<p>The package contains - <strong>data_csv</strong> and <strong>download.py</strong>. Run <strong>download.py</strong> from within the directory. Cheers.</p>

  </article>
