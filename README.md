## identity_dataset  

In the realm of game development, the creation of art assets is notably costly. Recent advancements in AI-based drawing techniques offer a potential solution for reducing these expenses. Yet, a significant hurdle persists: the limited controllability of these AI methods restricts their use in generating diverse character animations, which are essential for games featuring numerous characters each requiring a range of poses.  
  
This paper introduces the 'Identity Dataset', designed to facilitate the generation of multiple poses for a single character while maintaining their distinct identity and style.It significantly improves the controllability and consistency of AI-based drawing techniques. This advancement has far-reaching implications not only in game development but also in the broader field of animation. Utilizing the Identity Dataset, we anticipate a notable reduction in the costs and resources needed for art production in these industries, marking a substantial leap forward in the application of AI in creative domains.  

### Dataset Statics  

To facilitate this research, we created the Identity Dataset, comprising 14,552 unique characters. Each character has 200 different poses, resulting in approximately 3 million character images. We also generated pose estimation images using OpenPose, resulting in approximately 3 million pose images.  
Therefore, the dataset contains a total of around 6 million images, each with a size of 512x512, totaling approximately 150 GB. It's worth mentioning that the dataset includes a small portion of images with peculiar appearances or challenging poses that OpenPose couldn't recognize. To address this, we developed a detection script to remove these invalid data, which accounts for approximately 15% of the entire dataset.


### download
Baidu Netdisk
https://pan.baidu.com/s/1SV32HYmPuZjBzl_sRTdGzA 
code：x1y4 
