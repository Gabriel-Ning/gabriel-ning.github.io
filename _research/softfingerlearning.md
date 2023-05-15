---
title: "Autoencoding a Soft Touch to Learn Grasping Underwater"
layout: single-portfolio
excerpt: "<img src='/images/research/overview.png' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "research/overview.png"
---




## Manuscript in preparation
<figure>
  <img src="/images/research/overview.png" alt="">
  <figcaption>Overview of the soft finger visual-tactile learning across air and water using SVAE. (a) Design of the sensorized soft finger where the camera board is sealed with a silicon layer on top. (b) The integrated amphibious gripper is transformed by replacing the fingertip of a Robotiq Hand-E gripper with the sensorized soft finger with omni-directional grasping adaptations. The Hand-E gripper has an Ingress Protection (IP) rating of IP67, which is suitable for our underwater experiment in a tank without extra waterproofing. (c) The scheme of the visual-tactile learning which takes an image of the deformed metamaterial as input and reconstruct the image and predicts the force and torque simultaneously. (d) The amphibious gripper is mounted on a Franka Emika Panda robot arm to execute force control tasks in the air and underwater</figcaption>
</figure>

<b><i>Abstract: </i></b>Robots play a critical role as the physical agent of human operators in exploring the ocean. However, it remains challenging to grasp objects reliably while fully submerging under a highly pressurized fluidic environment with little visible light, mainly due to the fluidic interference on the interactive physics at the finger and object surfaces. This study proposes a soft visual-tactile learning approach using a Supervised Variational Autoencoder(SVAE) to estimate the 6D force and torque (FT) of an adaptive finger design made from meta-materials when grasping underwater. We fix a high-framerate camera inside the finger network to track its whole-body deformation while interacting with physical objects. We train an SVAE model to
establish a series of latent variables for accurate 6D force and torque estimation against commercial FT sensors. The sensorized soft finger enables us to perform reactive grasping under the water with tactile intelligence. Our results extend the use of SVAE in tactile perception for soft, delicate, and reactive grasping under the water, paving the pathway for future research in learning-based grasping intelligence for underwater robotics.


[Preprint](/files/pdf/research/IEEE/draft.pdf){: .btn--research}
[GitHub Repo](https://github.com/Gabriel-Ning/SoftFingerSvae){: .btn--research} 
[Supplemental Video](){: .btn--research}
[Dataset](https://drive.google.com/file/d/19CmZHYsDnuvNeUjVXZHiOqFZsTBYsM9z/view?usp=sharing){: .btn--research}
