+++
title = "Drone"
date = 2018-04-28T10:25:58-07:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "Documenting my hobby experience with flying computer platforms"

# Optional image to display on homepage.
image_preview = "rhombus.jpeg"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
My work with drones started in high school with the Parrot A.R. Drone and the Kinect SDK in C#. From then, I have written and rewritten extensions on the project in Java, Python, Node.js and MATLAB. And I have also interfaced the drone with different types of hardware including the LEAP motion.

## C# + KINECT

In high school, to complete my schools honors program requirement, we were required to complete a design project of our own with the guidance of a member of faculty. The only real requirement to the project is that it shows our interest in the subject. So I built a system that controls a quad-coptor through inputs from the Microsoft Kinect Sensor. This is still probably the coolest project I have completed, yet.

{{< youtube 1bWKtaloclM >}}


## MATLAB + KINECT

I rewrote the drone controller and kinect interface using MATLAB. I chose to change platforms because I was looking for more robust control over the hardware and to easily apply higher level processing (image processing, basic AI)

{{ https://github.com/hege0110/matlab-drone }}

<!-- <script src="//gist.github.com/hege0110/fcc61ae7d793c4eba30218560ab17aba.js"></script> -->
<!-- <script src="https://gist.github.com/hege0110/fcc61ae7d793c4eba30218560ab17aba.js"></script> -->
