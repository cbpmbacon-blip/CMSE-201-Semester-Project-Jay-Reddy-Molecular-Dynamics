# CMSE-201-Semester-Project-Jay-Reddy-Molecular-Dynamics

## What is this?
This is a low fidelity molecular dynamics (MD) python script that models a gas trapped in a box. The program uses pytorch to speed up tensor calculations through parallel computing on the GPU with CUDA. Molecular interactions are calculated the Lennard-Jones potential (A mathematical approximation for van-der-waal's forces) and assigned to particles with kinematic loops v

This code is in no way completely optimized or efficient. This also worked for my computer with my specs, I cannot guarantee it will work as well with yours. I encourage you to tinker with the code and try to find out what I'm doing and find a better way to do it. I'll post some resources below that really helped me get a good understanding of how these things function in the broader scope --- what all actually needs to be accounted for. 

### MY PC SPECS:
OS: Windows 11 Home \
CPU: Intel(R) Core(TM) Ultra 9 285H (2nd Gen) \
RAM: 32 GB LPDDR5 RAM (Soldered) \
Intel(R) AI Boost \
GPU: 5070Ti Laptop GPU (12GB VRAM) 

### GOOD RESOURCES TO CHECK OUT (THEY HELPED IMMENSELY):
https://pythoninchemistry.org/sim_and_scat/intro \
https://courses.grainger.illinois.edu/mse485/fa2019/Homework2.html \
https://tutorial.pyvista.org/tutorial/00_intro/index.html \
https://docs.pytorch.org/docs/2.14/index.html \
https://www.youtube.com/watch?v=iSEAidM-DDI \ 
https://www.youtube.com/watch?v=ipRnvs7_CxA \ 
https://www.youtube.com/watch?v=ChQbBqndwIA 
