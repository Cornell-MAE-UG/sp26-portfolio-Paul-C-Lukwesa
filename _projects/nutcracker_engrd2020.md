---
layout: project
title: Nut_Cracker
description: Finding unknown dimensions of nut cracker given the load
image: /assets/images/nutcracker.jpg
---

Problem Statement and Objective
- Design problem: Imagine you have a macadamia nut that you want to crack open by hand using a simple lever nut cracker.
Given: required load to crack nut: 222.18 kg
Grip strength: 40kg
Size of nut: 2cm
Find: Dimensions of nutcracker

Approach:
FBD,
![Nutcracker-1 2](https://github.com/user-attachments/assets/706a519c-b15b-400d-85e7-d9cf54a7d0a5)

Moment Balance at the origin, nutcracker joint
Balance at the origin, nutcracker joint  
Determine length (L) ratio  
Determine height (H) ratio  

Using the nutcracker joint as origin:

$$
\begin{aligned}
\sum M &= l_c \times F_i - l_n \times F_n = 0 \\
\frac{l_c}{l_n} &= \frac{F_n}{F_i} \\
&= \frac{22.18 \text{ kg}}{40 \text{ kg}} \\
&= 5.55
\end{aligned}
$$
  
Because of similar triangles,  
$\frac{l_c}{l_n} = \frac{H_c}{H_n} = 5.55$

$$
\begin{aligned}
H_c &= 5.55 H_n \\
&= 5.55 \cdot 2 \text{ cm} \\
&= 11.11 \text{ cm}
\end{aligned}
$$
 
Looking at a generic nutcracker,  
$l_n \approx 4 \text{ cm}$  
so  
$l_c = 22.22 \text{ cm}$

Solution credit: Dr. Ritz, Cornell University, ENGRD 2020 Spring26
