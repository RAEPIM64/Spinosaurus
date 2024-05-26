
# Spinosaurus Robot 
To build Spinosaurus robot and control it with CPG (Central pattern generator) ,Now we can make it walk straight only and simulate Spinosaurus's swimming that can change mode with Node-red by use MQTT

![S__10477576](https://github.com/RAEPIM64/Spinosaurus/assets/170262893/46d1bdc8-aafd-4bc1-bf9d-03c15f78dbb1)

CPG:
![S__9076811](https://github.com/RAEPIM64/Spinosaurus/assets/170262893/304825e9-e724-4b9a-9ef8-d5784d02f5c6)

# Table of Content

 [- Installation](#installation)
 [- Equipment](#equipment)
 [- Information Spinosarus](#information-spinosarus)
 [- Knowledge Used](#knowledge-used)
 [-Creator](#creator)

#  Installation

You can dowload zip file or clone git if you clone 
```
$ git clone https://github.com/RAEPIM64/Spinosaurus.git
```
and download App FT SCServo Debug for set ID and test servo in this link
```
[https://drive.google.com/file/d/1DVRHQHyxRBQxg2RzepRRYOwxh_MZ8BRK/view?usp=sharing](https://drive.google.com/file/d/1DVRHQHyxRBQxg2RzepRRYOwxh_MZ8BRK/view?usp=sharing&fbclid=IwZXh0bgNhZW0CMTAAAR1AdpLxrLi_YDJDw-I-IniXlgR8_LQISvUO_7QfSJW-138dyteWFjs00qI_aem_Abzb_r22SMQ5YWgRU3LF7pyYxg3UtsBBndQoEcDhzgrmJVOEEcsK6cGQ53ErZJKbrpN6G8AKQXhdj9AKQ4fza5jj)
```

# Equipment
***Hardware***
 1. Arduino uno R4
 2. Board drive Urt-1
 3. Step Down LM2596
 4. Battery
 5. Servo (Feetech SCS15)
 6. LED

***Software***

 1. Arduino IDE
 2. FT SCServo Debug V1.9.8
 3. MQTT Websocket
 4. Node-Red




## Information Spinosarus

https://github.com/RAEPIM64/Spinosaurus/assets/170262893/48a70506-3c3e-4873-8ff2-c4b60fb484f9

***Topic***

 1. Skull
 2. Calibrated phylogeny of Spinosaurus
 3. The tail of a Spinosaurus
 4. Legs of Spinosaurus
 5. Muscle of Spinosaurus

***Spinosarus***

 1. ***Skull***

![enter image description here](https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Spinosaurus_new_skull.jpg/600px-Spinosaurus_new_skull.jpg)

The Spinosaurus’s carapace is narrow and tall on the sides, differing from the straight carapace of a crocodile, which has narrow ridges when viewed from the top

The Spinosaurus differs from a crocodile in several ways. Spinosaurus has a long, narrow snout with openings near the tip of its mouth. These openings are sensory nerves directly connected to the brain. These sensory nerves help in hunting underwater prey. With just a slight movement, Spinosaurus can detect the prey's location

The Spinosaurus would plunge the tip of its snout into the water and sweep it back and forth. Once it detected movement, it would immediately attack.

Resources:
```
https://th.wikipedia.org/wiki/%E0%B8%AA%E0%B9%84%E0%B8%9B%E0%B9%82%E0%B8%99%E0%B8%8B%E0%B8%AD%E0%B8%A3%E0%B8%B1%E0%B8%AA
```

 2. **Calibrated phylogeny of Spinosaurus**

The analysis of paleoanatomy updates of Spinosaurus distinguishes two steps in the evolution of hunting and display behaviors. We depict significant changes in the skeletal framework, emphasizing modifications at the cranial end of the torso to enhance neck flexion (the second vertebrae in lateral and anterior views). Below is Tyrannosaurus allosaurus frazilis (Madsen, 1976); in the middle is Spinosaurus chinensis Suchomimus tenerensis (MNBH GAD70); above is Spinosaurus.
![enter image description here](https://iiif.elifesciences.org/lax:80092/elife-80092-fig8-v1.tif/full/617,/0/default.webp)

In his quest for answers, Henderson constructed a three-dimensional model of a Sphinx based on the findings of Ibrahim's discovery in 2014. He focused particularly on its dorsal fin, which weighed up to a hundred pounds and spanned several feet in length. Additionally, he also developed simulated models of an Allicerator and a Penguinator to further validate and enhance the completeness of the model.

Resources:
```
https://elifesciences.org/articles/80092
```

 3. **The tail of a Spinosaurus**

The Spinosaurus has a large tail resembling a fish's fin, extending from the base to the tip of the tail, enabling it to swim gracefully. Many scientists have experimented with the tail of Spinosaurus using three-dimensional models to test its efficiency. They found that its tail is highly flexible compared to other theropod dinosaurs, allowing it to swim freely. The walking behavior of Spinosaurus remains speculative; it may have walked on two hind legs and also used them for swimming, as its hind legs have flat, paddle-like foot claws suitable for swimming. There is also speculation that it may have had webbing between its toes


![enter image description here](https://iiif.elifesciences.org/lax:80092/elife-80092-fig4-v1.tif/full/617,/0/default.webp)

(A) Tail in S. aegyptiacus showing overlap of individual neural spines (red) with more posterior vertebral segments.

(B) Sail structure in the green basilisk (CT-scan enlargement) and in vivo form and coloration of the median head crest and sail (Basiliscus plumifrons FMNH 112993).

(C) Structure of the tail fluke in a urodele, mosasaur, crocodilian, and whale.

(D) Centrum proportions along the tail in the northern crested new

Resources:
```
https://elifesciences.org/articles/80092
```

 4. **Legs of a Spinosaurus**

After the discovery of the hind limbs of Spinosaurus in 2014, it was found that these hind limbs were short, making it difficult for the dinosaur to stand on two legs. Additionally, it was found that its feet were paddle-shaped, similar to those of a duck, which would not be suitable for running or chasing prey on land. Therefore, it is speculated that they were more likely adapted for swimming

![enter image description here](https://iiif.elifesciences.org/lax:80092/elife-80092-fig6-v1.tif/full/617,/0/default.webp)

His model also revealed that the center of mass of the Spinosaurus was located above the midfoot area, indicating that it could walk on both hind legs confidently. This contradicted Ibrahim's research, which suggested the center of mass was in the front part of the body, implying that this type of dinosaur had to walk on all fours. This suggests that this dinosaur likely walked on all four legs, as its w,jhind legs were comparatively small and short when compared to its other relatives. "Its legs are short and stout," Holtz reinforced, thus supporting the original hypothesis that such legs might be more suitable for swimming.

Resources:
```
https://elifesciences.org/articles/80092
```

 5. **Muscle of Spinosaurus**

Spinosaurus was the largest bipedal carnivorous dinosaur ever discovered. Lived during the middle Cretaceous period (about 100 million years ago) in North Africa. Its body structure is characterized by a long, slender skull, sharp teeth, a long tail, and large dorsal paddles.

Spinosaurus' muscles were complex and powerful. This allows it to hunt large prey and survive in a variety of environments.


**Neck Muscles:** Spinosaurus had very strong neck muscles. This allows him to rotate his head quickly and accurately. This is very important for hunting. This is because it helped the Spinosaurus capture its prey quickly and accurately.

**Jaw Muscles:** Spinosaurus had very powerful jaw muscles. This allowed it to bite down on large prey. Spinosaurus is thought to have been able to bite down on prey with more than 1,300 pounds of pressure per square inch. which is greater than the bite force of Tyrannosaurus rex

**Leg Muscles:** Spinosaurus had very strong leg muscles. This allowed it to chase its prey quickly and powerfully. Spinosaurus' legs were long and strong. This allowed it to run faster than other two-legged carnivorous dinosaurs

**Tail Muscles:** Spinosaurus had very strong tail muscles. This allowed it to control its large tail. The Spinosaurus' tail was long and flexible. This allows it to be used to balance itself while swimming, attack prey, or defend itself from enemies.

**Chest Muscles:** Spinosaurus had large chest muscles that helped it breathe efficiently.

**Abdominal Muscles:** Spinosaurus had strong abdominal muscles that helped it digest food and maintain its internal organs.

**Head Muscles:** Spinosaurus had facial muscles that helped it eat, capture prey, and express itself. 

## Knowledge Used

 - **Central Pattern Generators (CPGs):**

This structure is located at the spinal cord and it usually comprises of two neural populations which produce an alternating output of spikes. Eventually, these output spikes are used to activate the muscles fibers.

This approach of using CPGs can be borrowed to create locomotion in robotics. There are several possibilities to implement a CPG: using coupled-oscillators, using Artificial  [Neural Networks]"Learn more about Neural Networks from ScienceDirect's AI-generated Topic Pages")  (ANNs) or using Spiking Neural Networks (SNNs)

Resources:
```
https://www.sciencedirect.com/science/article/pii/S0925231222008165
```

 

 - **Spring**

The K value of a spring, also known as Nij, is a value used to indicate the force or weight that causes the spring to stretch or contract. It has units of Kg/mm, N/mm or Lbs/in, such as K = 3Kg/mm showing that when A weight of 3 kilograms is pressed against this spring and it will collapse 1 millimeter. The K value will be written on the spring coil area. The K value of each type of spring is not the same. This will depend on the stiffness of the spring as well. The more stiff the spring, the higher the K value will be. For springs that are weak, the K value will also be low. The choice of use should be mainly based on the K value of the spring. In order to get the spring that is most suitable for the job.

The calculation formula is **k= F/s**

(F is the force in Newtons (N), s is the contraction distance of the spring. Must be in mm)

The K value is used in units of kg/mm ​​(Kg/mm), newtons/mm (N/mm) and pounds/inch (Lbs/in), where 1 Kg/mm is equal to 56. Lbs/in and 9.86 N/mm, these values ​​will directly affect the softness of the suspension.

**Each type of spring**

**Torsion Springs:** A rebound spring is a spring that receives pressure or compressive force in a circumferential manner. The appearance is independent. There is no fixed format. The shape of the spring can be designed to suit the job very well. Spring springs are suitable for work on spare parts for machinery, automobiles, spare parts for various electrical appliances.

**Tension Springs:** A tension spring is a spring used to receive tension. This type of spring is special in that the coiling pattern of the spring is denser than other types of springs. Both ends are hooks or loops. To be used for hooking or hanging with other equipment. Behavior when pulling force The spring will extend the same distance.

**Compression Springs:** A compression spring, also known as a pressure spring, is a spring used for receiving pressure or pressure. By the nature of the wire strands, they have the same distance apart. Most of the work that uses compression springs is automotive spare parts. Industrial machinery, furniture, electrical appliances, etc.

**Disc spring rings (Disc Springs):** Disc spring ring or disc spring ring It looks similar to a nut washer, but the ring , spring , and plate are curved. Suitable for work that requires high strength. Good for use in narrow spaces. The installation can be placed in a variety of workpieces. Allows for force to be received from many directions.

**Spring selection and precautions**

Selection of springs You should choose from a reliable quality manufacturer. Manufactured according to standards (JIS). In addition, factors in selecting the spring that is appropriate for the job must be considered as follows. You must know how much pressure the spring you want will be able to withstand. Choose from large sizes or the size of the spring insert hole Make it a suitable size for the length of the spring's collapse and its service life.

Precautions when using springs are: When it's time to change the springs, the entire set should be replaced. You should not change them one by one. Because the pressure will be uneven, it may damage the machine. Do not modify or cause the spring to change its original shape. And do not use the spring that is in the maximum collapse stage. Because the spring wire may be hit and broken.

Resources:
```
https://th.misumi-ec.com/th/pr/recommend_category/spring201901/
```
```
https://ozysuspensions.in.th/guru-detail.php?id=55
```
# Creator
  
Junior from Panyapiwat Intitude of Managment, faculty of Engineering and Technology, majoring in Robotic and Automation (RAE)

 
