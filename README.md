# Graduation_Project
Text to Art Generation

# Introduction
The AI art apps generate images by simply typing a brief description of what we want to see, no matter what we type, the app will generate something visually compelling that matches our prompt in often surprisingly opposite ways. This sort of AI-generated artwork is becoming higher quality and more accessible. Past examples of these sorts of text-to-image models have included research-orientated programs like DALL-E and VQGAN+CLIP, as well as more specialized commercial projects like Art breeder (which is particularly good at creating portraits of fictional beings and people). Generally, programs like these are trained on vision datasets — huge libraries of images that are tagged based on objects and scenery.

# Scope
We focus on model architecture and learning paradigms to learn more about the strengths and weaknesses of generative models applied in text-to-image. We also try to organize these works to show development over the years. Also, we mention top-powered tools and applications that are used at present. Finally, we emphasize existing and future challenges. 

# objectives
Images are more attractive compared to text. Visual aids can deliver information more directly. Visual content grabs the attention and keeps people engaged. Key activities such as presentation, learning, and all involve visual Communication to some degree. If designed well, it offers numerous benefits.

# Generative Models
* Generative models allow to synthesize novel data that is different from the real data but still looks just as realistic. A designer could train a generative model on images of cars and then let the resulting generative AI computationally dream up novel cars with different looks, accelerating the artistic prototyping process.
* There are Four types of generative models, GAN, VAE, Flow-based models, and Diffusion models. They have shown great success in generating high-quality samples, but each has some limitations of its own.

![image](https://user-images.githubusercontent.com/63797979/182920524-381d8414-a61d-48d6-8378-3e10721ac879.png)

# Our model
* Based on CLIP + VQGAN from Taming Transformers.
* various CLIP models (incl. multi-language from SBERT).
* optimization with SIREN

# Results (Before Optimization & After Optimization)

VQGAN_model = "imagenet_f16-16384" , model = "ViT-B/32" , style = "Classicism"


Prompt = 'أزهار جميلة'
   
Before

![image](https://user-images.githubusercontent.com/63797979/182921602-2d025877-7958-495c-9168-824171be54bc.png)
    
After

![image](https://user-images.githubusercontent.com/63797979/182921663-bf9a6ffb-9392-4d8c-a46f-4e9840e67b9c.png)


Prompt = 'cosmic crystals of jelly and fire flowers'

Before

![image](https://user-images.githubusercontent.com/63797979/182921793-d94a9fb4-3954-4610-ba80-b526f6f1d754.png)


After

![image](https://user-images.githubusercontent.com/63797979/182921811-5c2f56a0-3cc1-4cd6-a5e7-d0817cc873a3.png)



2)	VQGAN_model = "sflckr"
model = "ViT-B/32"
style = "Post-Impressionism"

Prompt = 'Victorian house on hill'

Before 

![image](https://user-images.githubusercontent.com/63797979/182922098-bdcb0ea0-c4b9-44b3-a61d-3ffcacde73ad.png)



After

![image](https://user-images.githubusercontent.com/63797979/182922120-6ca30c66-ea7c-4856-a70f-1ad95ce9fde5.png)




