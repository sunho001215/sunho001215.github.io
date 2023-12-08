---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
> **Optimizing the Response Time for ROS Tasks in Multi-Core Processors**  
> *Sunho Kim<sup>*</sup>, Hayeon Park, Chang-Gun Lee*  
> *IEEE/ACM International Symposium on Distributed Simulation and Real-Time Applications (DS-RT), 2023*  
> *[Google Scholar](https://scholar.google.com/scholar?hl=ko&as_sdt=0%2C5&q=Optimizing+the+Response+Time+for+ROS+Tasks+in+Multi-Core+Processors&btnG=)*  
> <details>
> <summary>Click to toggle details</summary>
>
> <p><b>Abstract</b> <br>
> This paper presents methods to optimize the response time of ROS (Robot Operating System), a widely utilized open-source meta-operating system in robotic software development. Despite its popularity, ROS lacks real-time capabilities, making it unsuitable for real-time control and difficult to use in embedded systems. Recently, DAG (Directed Acyclic Graph) task scheduling algorithms have gained much attention, but they are challenging to apply in the current design of ROS. In this work, we analyze that there are three major challenges in ROS; (i) misalignment delay, (ii) message delivery mechanism using TCP/IP, and (iii) multiple overlapping instances of a single task. We first calculate the new response time bound considering misalignment delay and propose an optimization technique using it to solve the first problem. Furthermore, we address the remaining challenges by assigning priority to the nodes of the DAG and ksoftirqd processes. Our experiments using random tasks show significant improvement, outperforming the state-of-art methods. In addition, our methods are validated through testing autonomous driving software on embedded systems, proving their real-world applicability.</p> 
> 
> <p><b>Photo</b> <br>
> Singapore, October 4, 2023 <br>
> <img src='/images/DS-RT_2023.jpg' width="450"/> <br>
> </p> 
> </details>
  
> **Autoware Controller Interface for Actual Vehicle Driving**  
> *Sunho Kim<sup>*</sup>, Dongmin Shin, Chang-Gun Lee*  
> *Korea Computer Congress (KCC), 2022*  
> *[Google Scholar](https://scholar.google.com/scholar?hl=ko&as_sdt=0%2C5&q=%EC%8B%A4%EC%B0%A8+%EC%A3%BC%ED%96%89%EC%9D%84+%EC%9C%84%ED%95%9C+Autoware+%EC%BB%A8%ED%8A%B8%EB%A1%A4%EB%9F%AC+%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4&btnG=)*  
> <details>
> <summary>Click to toggle details</summary>
>
> <p><b>Abstract (English Version)</b> <br>
> Autoware is an open-source software for autonomous driving based on the Robot Operating System (ROS), providing various functions necessary for autonomous operation. To implement Autoware in an actual vehicle, an additional controller interface is required between the Autoware output and the vehicle's CAN input. This paper proposes a controller interface that includes a PID-based acceleration controller and a conversion function between steering wheel angle and vehicle steering angle. By utilizing this, we demonstrate the feasibility of real-vehicle operation and compare the linear model and the piecewise linear model through experiments. The results show that the controller interface incorporating the piecewise linear model offers better path-following performance and stability.</p> 
>  
> <p><b>Remarks</b> <br>
> This paper received the Participation Award at the KCC Undergraduate Thesis Award 2022.</p>
> 
> </details>
