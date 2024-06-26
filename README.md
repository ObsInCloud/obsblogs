# Contribution Guide! 

ClarityPosts is hosted at : https://clarityposts.github.io/observability/

This document will help you create and format your own posts and tutorials within this project. Please follow the guidelines and use the provided templates to ensure consistency and quality.

# Folder Structure

The project is organized into the following folder structure:

```
_root_directory/
├── _tutorials/
│   ├── EBS/
│   └── peoplesoft/
├── images/
└── _posts/
     ├── 2023-12-08-oci-custom-autoscaling.md
     └── 2024-01-18-oci-kube-logging.md
```

# Creating a New Tutorial

To create a new tutorial, follow these steps:

    Choose the appropriate subdirectory under _tutorials/ based on the tutorial's subject (e.g., EBS or peoplesoft).

    Create a new markdown file with a suitable name inside the chosen subdirectory.

    Use the following template for your markdown file:

```
---
title: "Your Tutorial Title"
date: YYYY-MM-DD HH:MM:SS +TZD
categories: [Category1, Category2]
authors: 
  - name: Author-1
    image: /images/Author-1-profile.png
  - name: Author-2 
    image: /images/Author-2-profile.png
tutorial_series: Your Tutorial Series
tutorial_number: X
---
```

Template Field Descriptions

    title: The title of your tutorial.
    date: The publication date and time in the format YYYY-MM-DD HH:MM:SS +TZD (e.g., 2024-06-12 10:00:00 +1100).
    categories: A list of categories relevant to your tutorial.
    authors: 
      - name: Your name.
        image: Path to your profile image stored in the images folder.
    tutorial_series: The series to which your tutorial belongs.
    tutorial_number: The number of your tutorial in the series.

Example

Here's an example of how a tutorial markdown file should look:

For an EBS tutorial:

```
---
title: "Planning E-Business Suite"
date: 2024-06-12 10:00:00 +1100
categories: EBS OCI O&M
authors: 
  - name: Author-1
    image: /images/Author-1-profile.png
  - name: Author-2 
    image: /images/Author-2-profile.png
tutorial_series: E-Business Suite
tutorial_number: 1
---
```

If your tutorial includes images, please store them in the images folder and reference them in your markdown file using the appropriate path. Please ensure that there are no <b>Duplications</b> with the image names.

Example:

![Alt Text]({{ site.baseurl }}/images/your_image.png)

# Submitting your Posts/Blogs

It involves a similar process, refer one of the .md files under _posts directory and follow the similar structure. Note that the file name for the posts should begin with the dates
└── _posts/
     ├── 2023-12-08-oci-custom-autoscaling.md
     └── 2024-01-18-oci-kube-logging.md

# Submitting Your Tutorial

Refer [CONTRIBUTE](CONTRIBUTE.md)

Thank you for contributing !
