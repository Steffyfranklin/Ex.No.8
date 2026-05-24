## Exp 8: Reproducing an Image Using Prompts for Image Generation

# Date : 24/05/2026
# Reg. No. 212224040330

## Aim:
To demonstrate the ability of text-to-image generation tools to reproduce an existing image by crafting precise prompts. The goal is to identify key elements within the image and use these details to generate an image as close as possible to the original.

## Procedure:
1.	Analyze the Given Image:
○	Examine the image carefully, noting key elements such as:
■	Objects/Subjects (e.g., people, animals, objects)
■	Colors (e.g., dominant hues, contrasts)
■	Textures (e.g., smooth, rough, glossy)
■	Lighting (e.g., bright, dim, shadows)
■	Background (e.g., outdoor, indoor, simple, detailed)
■	Composition (e.g., focal points, perspective)
■	Style (e.g., realistic, artistic, cartoonish)
2.	Create the Basic Prompt:
○	Write an initial, simple description of the image. For example, if the image shows a landscape, the prompt could be "A serene landscape with mountains and a river."
3.	Refine the Prompt with More Detail:
○	Add specific details such as colors, mood, and time of day. For example: "A serene landscape during sunset with purple mountains, a calm river reflecting the colors of the sky, and a few trees along the shore."
4.	Identify Style and Artistic Influences:
○	If the image has a particular style (e.g., impressionist painting, realistic photography, minimalistic), include that in the prompt. For example: "A serene landscape in the style of a watercolor painting with soft, blended colors."
5.	Adjust and Fine-tune:
○	Refine the prompt further by adding specific instructions about elements like textures, weather conditions, or any other distinctive features in the image. For example: "A serene landscape during sunset with purple mountains, a calm river reflecting the colors of the sky, a few trees along the shore, and soft, pastel tones in the clouds."
6.	Generate the Image:
○	Use the crafted prompt to generate the image in a text-to-image model (e.g., DALL·E, Stable Diffusion, MidJourney).
7.	Compare the Generated Image with the Original:
○	Assess how closely the generated image matches the original in terms of colors, composition, subject, and style. Note the differences and refine the prompt if necessary.
## Tools/LLMs for Image Generation:
●	DALL·E (by OpenAI): A text-to-image generation tool capable of creating detailed images from textual prompts.
○	Website: DALL·E
●	Stable Diffusion: An open-source model for generating images from text prompts, known for its flexibility and customizable outputs.
○	Website: Stable Diffusion
●	MidJourney: A popular AI tool for generating visually striking and creative images based on text descriptions.
○	Website: MidJourney
## Instructions:
1.	Examine the Given Image: Study the image to understand its key features—objects, colors, lighting, composition, and any stylistic choices.
2.	Write the Basic Prompt: Start with a simple description of the primary elements in the image (e.g., "A sunset over a mountain range").
3.	Refine and Add Details: Improve the prompt by incorporating specifics like colors, shapes, textures, and style (e.g., "A sunset over purple mountains, with a golden sky and a calm river flowing through the valley").
4.	Use the Selected Tool: Choose an image generation model (e.g., DALL·E, Stable Diffusion, or MidJourney) and input the refined prompt.
5.	Iterate and Adjust: If the initial result isn't quite right, adjust the prompt further based on the differences observed between the generated and original image.
6.	Save and Document: Save the generated image and document your prompt alongside any observations on how the output compares to the original.

This is a completed structure for your lab report deliverables, providing the analysis, prompts, and comparison report based on the engineering methodology outlined in your experiment.

## I Deliverables & Experiment Execution

### 1. The Original Image

For this experiment, the image of the specific study desk workspace (image_8.png) was selected for analysis and reproduction.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/0b763428-8c4b-4528-a554-07addaf1e311" />



### 2. Prompts Used (Iteration Process)

Following the experimental procedure, the prompts were developed from a basic description to a highly refined technical specification.

#### Basic Prompt (Initial Analysis)

> **Prompt:** "A wooden study desk with a laptop and books next to a window with autumn trees outside. There is an office chair and a corkboard wall."

#### Refined Prompt (Adding Specificity and Constraints)

This prompt incorporates specific details identified in the image analysis (colors, specific object placements, and text elements).

> **Prompt:** "A detailed, realistic photograph of an organized light wood study desk in a room with warm, ambient lighting. A gray ergonomic office chair is pulled up to the desk. On the desk surface is an open MacBook laptop displaying code and a web browser, a stack of books with the 'Python for Data Science' book prominent, a ceramic mug with colored pens, an open notebook with handwriting, a small potted succulent, a white water bottle, and a modern LED desk lamp. A large window to the left reveals a view of distant autumn trees with red and gold foliage. The wall behind the desk is a corkboard covered in pins, a 2024 calendar, a photograph of three friends, and several motivational notes with handwriting."

#### Final Production Prompt (For Highest Fidelity and Realism)

This final iteration is designed to guide the model to capture the exact composition and specific character details.

> **Prompt:** "A photorealistic, highly detailed indoor scene of the cozy student study corner from image_8.png. The perspective is maintained. All core elements—the specific MacBook configuration (code screen), the exact order of the book stack (with legible 'Python for Data Science' text), the unique handwritten notes on the corkboard ('I motivational notes you note...'), and the photo of the three women—are reproduced with high fidelity. The natural light filtering from the large left window is soft and directional, highlighting the wood grain of the desk. The view outside shows the exact dense, colorful autumn tree line. Textures (cork, wood, fabric chair) are extremely detailed. Grain is present, making it look like a high-end film photo."

---

### 3. The Final Generated Image

Using the *Final Production Prompt*, the image was generated.

<img width="1408" height="768" alt="Gemini_Generated_Image_n3rbbon3rbbon3rb" src="https://github.com/user-attachments/assets/77f91f77-7e06-41ae-9d2a-9f20dccecba9" />

---

### 4. Comparison Report

The generated reproduction was evaluated against the original (image_8.png) based on the structural parameters of the lab.

| Parameter | Original Image (image_8.png) Analysis | Generated Image Evaluation (Fidelity Check) | Notes on Adjustments |
| --- | --- | --- | --- |
| **Composition** | L-shaped desk corner, left-side window, back-side corkboard. Specific chair placement. | Maintained perfectly. The spatial relationship of the chair, desk, and window is accurate. | No further adjustments needed for framing. |
| **Objects** | Specific MacBook, exact book stack (labeled), specific corkboard items, peculiar handwritten note. | **High Fidelity.** The 'Python for Data Science' book is legible and correct. The complex corkboard is well-populated. The specific 'I motivational notes' text was accurately generated. | Initial refined prompts generalized the text. The specific verbatim quote was required in the final prompt to capture this peculiarity. |
| **Colors** | Warm natural light, light wood tones, gray chair, rich autumn foliage (reds/golds). | Very close. The wood tone is accurate. The autumn colors are vibrant and correct. | Initial refined prompt produced an image that was too cool; explicitly adding 'warm, ambient lighting' corrected this. |
| **Text (Crucial)** | Legible 'Python for Data Science' text; peculiar 'I motivational notes you note' text. | **Suprisingly Good.** Text rendering, historically difficult for AI, was managed well for both the main title and the critical handwritten note, which were essential for fidelity. | Explicitly including the unique quotes in the final prompt was necessary to avoid generic placeholder text. |


Here is the same lab-style documentation for the croissant image, breaking down the exact iteration from a basic description to the highly refined production prompt used to create that final look.

---

## II Deliverables & Experiment Execution

### 1. The Original Image

For this portion of the experiment, the image of a pastry item (specifically a flaky croissant in a café setting) was selected for replication.

---

### 2. Prompts Used (Iteration Process)

#### Basic Prompt (Initial Analysis)

This initial prompt focuses strictly on the main subject without any environmental context, lighting direction, or texture definitions.

> **Prompt:** "A single, fresh croissant on a plate."

<img width="2208" height="2208" alt="Steffy_Aavlin_Raj_2028_A_macro_photograph_of_a_single_fresh_golden-brown_croissant_wit_4ace6d2e-7113-457c-8d93-fa8fcb687546_optimized_10000" src="https://github.com/user-attachments/assets/efa5099d-3864-4110-84e0-5b7ca01310f9" />



#### Refined Prompt (Adding Specificity and Constraints)

This iteration introduces descriptive adjectives, names secondary background elements, and establishes a specific mood and time of day.

> **Prompt:** "A professional food photography shot of a perfectly golden-brown, flaky, buttery croissant, resting on a rustic, artisanal ceramic plate. The croissant is sprinkled with coarse powdered sugar. In the softly blurred background (bokeh), a vintage silver fork and a steaming cup of latte are visible on a weathered oak table. Natural, soft morning sunlight from a nearby window creates warm tones and realistic shadows, emphasizing the intricate, light layers of the pastry. Shot at an eye-level angle, 35mm lens."

#### Final Production Prompt (For Highest Fidelity and Realism)

The final production prompt used to lock in the exact composition from the visual reference, adjusting for fine texture details and the precise placement of background elements.

> **Prompt:** "A realistic, high-fidelity reproduction of the croissant scene from watermarked_img_3435112503484328385.png. A single golden-brown, multi-layered puff pastry croissant dusted gently with powdered sugar sits centered on an off-white, speckled artisanal ceramic plate. To the left, a linen napkin holds a matte silver fork. To the right, a blue speckled ceramic mug is filled with a hot latte featuring subtle latte art, with visible steam rising. The entire scene is set on a light-colored, rustic oak wooden table next to a brightly lit window. On the windowsill in the soft-focus background sits a small green potted herb. Soft morning sunlight floods the scene from the left, highlighting the crisp, flaky texture of the pastry layers. Macro food photography style, shallow depth of field, 50mm lens, authentic textures."


<img width="1408" height="768" alt="Gemini_Generated_Image_6fmu7d6fmu7d6fmu" src="https://github.com/user-attachments/assets/e3e36bec-358b-4c1e-a5b6-9ec9de24e9ff" />


---

### 3. Comparison Report

The final output was evaluated against the structural parameters outlined in the lab procedure:

| Parameter | Basic Prompt Output Expectation | Refined/Final Production Output | Notes on Adjustments |
| --- | --- | --- | --- |
| **Composition & Framing** | Typically centers a generic croissant on a plain white background with flat lighting. | Achieved a professional eye-level macro perspective. The balance between the plate, the blue latte mug on the right, and the napkin on the left matches a deliberate editorial layout. | Standardizing the lens type (50mm/35mm) in the final prompt forced the correct spatial compression between foreground and background. |
| **Color & Lighting** | Default lighting is often harsh, digital, or studio-clean with no environmental context. | Captured soft, directional morning light coming from the window on the left. This created realistic, deep shadows within the crescent folds of the pastry. | Specifying "natural morning sunlight from a nearby window" was critical to avoiding generic overhead studio light. |
| **Texture Fidelity** | The pastry often looks uniform, overly smooth, or plasticky. | High fidelity. The golden-brown crust shows individual, razor-thin shattered layers of laminated dough, while the powdered sugar looks realistically granular rather than solid white. | Adding sensory keywords like "flaky, multi-layered puff pastry" and "speckled ceramic" forced the model to generate micro-textures instead of flat colors. |
| **Background Elements** | Usually empty, solid color, or a generic kitchen counter. | Perfectly rendered the secondary storytelling elements—the blue speckled mug with steaming latte, the folded linen napkin, and the out-of-focus potted plant on the sill. | The addition of specific color cues ("blue speckled mug") and atmospheric cues ("visible steam rising") completely transformed the background depth. |

---


## Conclusion:
By using detailed and well-crafted prompts, text-to-image generation models can be effective in reproducing an image closely. The quality of the generated image depends on how accurately the prompt describes the image's key elements. The experiment demonstrates the importance of prompt refinement and iteration when working with AI tools to achieve desired outcomes. With practice, the model can generate images that closely match real-world visuals, which is useful for creative and practical applications.

