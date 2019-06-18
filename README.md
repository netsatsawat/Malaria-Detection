# Malaria Detection

This repository demonstrates how we can simply use transfer learning with [TF Hub](https://www.tensorflow.org/hub) onto the red blood cells images. The Malaria datasets can retrieve from NIH website [here](https://ceb.nlm.nih.gov/repositories/malaria-datasets/).

## Data Format

The image is the segmented cells from the thin blood smear slide images from the Malaria Screener research activity. The initial file is stored in `zip` file, with each class stored onto different folders; namely __Parasitized__ and __Uninfected__.

## Motivation

- Malaria is still one of the deadly and most common infectious diseases.
- The most accurate way to diagnose malaria is by taking a drop of blood, smearing it on a slide, and then examining it under a microscope to look for malaria parasites inside the __red blood cells__.
- The following process requires the avaialability of microscope, electricity, and trained medical staffs to look at the slides. The process is also time-consuming as the staff can only look at one slide at a time.
- With the advancement of Deep Learning (Machine learning), it can help optimizing the process by looking at the slide images instead.

<br>
Below is the sample of red blood cells (no infection and with infection):

<img src="https://github.com/netsatsawat/Malaria-Detection/raw/master/img/malaria_microscope_stages2.jpg" width="500" height="300" />
