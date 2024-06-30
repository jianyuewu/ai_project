# AI_project  
Study with some basic AI knowledge.  

# Recommended Environment Setup  
We can use Google Colab directly, or simply set up with an Nvidia RTX 4090 for better data security. If we need super high performance with the A100/A800/H800, can refer to:   
![alt text](gpu/images/8x-a100-node-hw-topo.png)  
1. CPU:   
    Model: Intel® Xeon® Platinum 8458P Processor  
    Quantity: 2  
2. Memory:   
    Type: DDR5-6400  
    Capacity per Module: 64 GB  
    Quantity: 32  
    Total Memory: 2 TB (64 GB * 32)  
3. Disk:  
    Primary Storage:  
        Type: NVMe  
        Form Factor: 2.5-inch  
        Capacity: 15.36 TB  
        Quantity: 2  
    Secondary Storage:  
        Type: SATA  
        Form Factor: 2.5-inch  
        Capacity: 480 GB  
        Quantity: 2  
4. GPU: Suitable for heavy computational tasks and machine learning workloads.  
    Model: NVIDIA A100  
    Quantity: 8  
5. RAID Controller: Enhances data redundancy and performance.  
    Model: PCIe 4.0 RAID Controller  
    Type: 3908  
    Cache: 4 GB  
    Quantity: 1  
6. DPU Card:  
    Primary DPU:  
        Network Speed: 400 Gbps  
        Model: NVIDIA ConnectX-7 (MCX75310AAS-NEAT)  
        Quantity: 8  
    Secondary DPU:  
        Network Speed: 25 Gbps  
        Ports: 2  
        Quantity: 1  

# Clone code  
git clone --recurse-submodules -j8 https://github.com/jianywu/ai_project   

# References   
https://resources.nvidia.com/en-us-tensor-core   
https://arthurchiao.art/blog/gpu-data-sheets/#3-comparison-of-a100a800h100h800910bh200   
