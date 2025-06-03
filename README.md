# NEURAL-STYLE-TRANSFER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHRAVYA S

*INTERN ID*: CT04DN317

*DOMAIN*: Artificial Intelligence

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

# TASK DESCRIPTION

 Neural Style Transfer
Neural Style Transfer (NST) is a computer vision technique that combines the content of one image with the artistic style of another using deep learning. In this task, we implemented a NST model using a pre-trained VGG19 neural network to generate stylized images that blend the content of a photograph with the style of an artwork.

The process involves three main components:
Content Image – the photograph to which we want to apply an artistic style.
Style Image – the artwork whose style we want to extract (e.g., brushstrokes, color palette).
Generated Image – the output image which visually resembles the content image but mimics the style image’s artistic traits.
The NST algorithm works by passing these images through a deep convolutional neural network (VGG19). The network extracts high-level features from various layers:
Content representation is derived from deeper layers of the network.
Style representation is captured using Gram matrices of feature maps from multiple layers.
A loss function is computed by measuring how different the content and style features of the generated image are from the original content and style images. This loss is minimized using optimization techniques such as gradient descent, and the generated image is iteratively updated to produce a stylized result.
Our implementation uses TensorFlow and includes loading and preprocessing images, extracting features using VGG19, defining content and style loss, and training a generated image through multiple epochs. The final output is saved and displayed as a stylized image.

Applications of Neural Style Transfer
Neural Style Transfer has a wide range of real-world applications in both creative industries and technology:

Digital Art Creation
Artists and designers can create new artwork by blending famous painting styles (e.g., Van Gogh, Picasso) with original photos. NST enables non-artists to produce visually compelling pieces easily.

Photo and Video Filters
Social media platforms (like Instagram, TikTok, and Snapchat) use NST-based filters to apply artistic effects to photos and videos in real-time.

Content Personalization
NST allows users to personalize visual content such as profile pictures, wallpapers, or posters by applying unique artistic styles.

Advertising and Marketing
Brands use stylized visuals to create memorable, artistic marketing materials. NST can help align brand identity with specific aesthetics.

Film and Animation
NST can be used in movie production to apply stylized visuals to scenes, creating specific moods or artistic themes without manual editing.

Augmented and Virtual Reality
Stylized environments in AR/VR can enhance user experience, making virtual spaces feel like oil paintings, comic books, or other visual styles.

Fashion and Interior Design
Designers use NST to visualize patterns and textures on clothing, fabrics, or interior spaces by applying artistic patterns to product prototypes.

By combining the power of convolutional neural networks with artistic creativity, Neural Style Transfer bridges the gap between technology and art, enabling new forms of expression and user interaction.

# OUTPUT 

![Image](https://github.com/user-attachments/assets/b3a23e69-16fe-495d-87e4-1ba7f10817ee)

![Image](https://github.com/user-attachments/assets/67fe0055-7483-4f81-a025-dc7981d07295)
