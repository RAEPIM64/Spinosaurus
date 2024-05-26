# Spinosaurus Robot 
To build Spinosaurus robot and control it with CPG (Central pattern generator) ,Now we can make it walk straight only and simulate Spinosaurus's swimming that can change mode with Node-red by use MQTT

![S__10477576](https://github.com/RAEPIM64/Spinosaurus/assets/170262893/46d1bdc8-aafd-4bc1-bf9d-03c15f78dbb1)


# Table of Content




***



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




## INFORMATION 

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

His model also revealed that the center of mass of the Spinosaurus was located above the midfoot area, indicating that it could walk on both hind legs confidently. This contradicted Ibrahim's research, which suggested the center of mass was in the front part of the body, implying that this type of dinosaur had to walk on all fours. This suggests that this dinosaur likely walked on all four legs, as its hind legs were comparatively small and short when compared to its other relatives. "Its legs are short and stout," Holtz reinforced, thus supporting the original hypothesis that such legs might be more suitable for swimming.

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
