---
layout: page
title: Autonomous Vision-Based Line Following Robot
description: This was our final embedded systems project.
img: assets/img/embedded/embedded_cover.jpg
importance: 2
category: work
giscus_comments: false
published: true
---

## 📝 Abstract
<div class="p-4 bg-light rounded shadow-sm mb-4" markdown="1">

This project focuses on the design and development of an **autonomous line-following robot** in compliance with the **RoboCupJunior Rescue Line rules**.

---

### ⚙️ Platform & Tools
- **Hardware:** NVIDIA JetBot platform  
- **Software:** OpenCV-based vision pipeline  

---

### 🚦 Project Goal
The robot’s task was to **follow a black line on a white floor** while dynamically adapting to:  
- Turns
- Roundabouts where a direction must be taken
- Gaps and interruptions in the track

---

### 🧠 Implementation
- **Line detection & navigation:** Classical computer vision with OpenCV to preprocess inputs, find the line’s centroid, and compute steering corrections  
- **Intersection handling:** Detected green markers → triggered predefined actions (turns, U-turns)  
- **Obstacle recovery:** Integrated detection & fallback strategies to maintain continuous operation  

---

### 🎯 Key Takeaway
This project emphasizes **real-world adaptability** under competition constraints (unpredictable layouts, environmental variations).  
By relying on **efficient OpenCV algorithms**, we demonstrated that classical vision techniques can **successfully solve autonomous navigation challenges** in a competitive setting.  

</div>

## 🎥 Project Demo
<div class="card shadow-lg my-4">
  <div class="card-body text-center">
    <h5 class="card-title">Watch the Robot in Action</h5>
    <div class="embed-responsive embed-responsive-16by9">
      <iframe class="embed-responsive-item" 
              src="https://www.youtube.com/embed/fwANImeoyc8" 
              allowfullscreen></iframe>
    </div>
  </div>
</div>

## 📄 Project Report
<div class="card shadow-lg my-4">
  <div class="card-body">
    <h5 class="card-title">Read the Full Report</h5>
    <p class="card-text">Explore the methodology, experiments, and results in detail below:</p>
    <iframe 
    src="/assets/pdfjs/web/viewer.html?file=/assets/pdf/embedded_report.pdf" 
    width="100%" height="800" style="border:none;">
    </iframe>
  </div>
</div>

