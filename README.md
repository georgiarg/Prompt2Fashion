# Prompt2Fashion: An automatically generated fashion dataset

This repository contains the dataset created with the methodology presented in the paper **"Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models"** (https://github.com/georgiarg/AutoFashion.git).


## Abstract

The intersection of artificial intelligence (AI) and fashion is revolutionizing the industry by enhancing creativity, personalization, and efficiency. From designing garments to predicting trends, AI is becoming an indispensable tool for fashion designers, retailers, and marketers. However, the integration of AI into fashion faces significant challenges, particularly in evaluating AI-generated content, which often requires domain expertise to ensure relevance, style, and appeal.

In this work, we present an automatically generated fashion image dataset focused on personalization. This dataset encompasses a variety of requirements, including gender, body type, occasions, and styles, along with their combinations. By leveraging the capabilities of Large Language Models (LLMs) followed by a Diffusion Model, we offer a scalable solution for generating fashion images. Our approach eliminates the need for human intervention in designing the final outfit or even the conditioning prompt to the Diffusion Model.

The scalability of production facilitated by LLMs and Diffusion Models ensures a diverse range of fashion images can be generated efficiently. The quality guarantees provided by the LLMs in language generation, as well as the Diffusion Models in image generation, are validated by human evaluators. This validation process reflects how potential consumers perceive these AI-generated outfits, ensuring that the content is not only technically proficient but also resonates with current fashion trends and consumer preferences. 

Given that AI is making significant inroads into creative fields, it is crucial that human oversight regulates generated content. After all, fashion image synthesis frameworks are ultimately designed for experts in the field, such as fashion designers. These AI-generated images are likely to serve as preliminary steps in the creative process rather than the final product. Consequently, it is essential for AI-generated fashion content to be evaluated by individuals with domain expertise. To this end, in this work, we not only offer an open, automatically generated dataset for creatives and engineers but also emphasize the importance of involving experts in the evaluation process, based not only on the aforementioned notions but also on experimental findings.

![350691125-92e1aa8f-2e13-4c6c-8acd-719af86bd3ff](https://github.com/user-attachments/assets/578c238a-134a-4466-a6db-8228140fcba5)
## Folder Structure 

- Mistral: This folder contains the images and descriptions generated using the Mistral-7B model. There are specific subfolders for each method used (zero-shot, few-shot, chain-of-thought, RAG with PDFs and RAG with BLOGs).
- Falcon: This folder contains the images and descriptions generated using the Falcon-7B model. There are specific subfolders for each method used (zero-shot, few-shot, chain-of-thought, RAG with PDFs and RAG with BLOGs).
- Evaluation: This folder includes surveys and their results, which are crucial for filtering and assessing the generated fashion images. The surveys were designed to gather human evaluations of the images, focusing on their relevance, appeal, and adherence to fashion trends. The results can be used by researchers to filter and analyze the dataset based on these evaluations.

## Evaluation Results
### Key Findings

As presented in the paper **"Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models"** the results of the two experiments can be summarized below:

- Images Evaluation
![1stexp](https://github.com/user-attachments/assets/f29bf462-797c-49a8-ae46-539ec517a2bf)

- Descriptions Evaluation
![2ndexp](https://github.com/user-attachments/assets/d6c796f7-953b-494f-a16c-04b7cb82de5f)


### Detailed Results

For more detailed evaluation results, including individual survey responses and statistical analyses, please refer to the Evaluation folder. This folder contains the raw survey data, as well as summary reports that provide deeper insights into how the generated images were perceived by human evaluators.


## Future Work
### Hugging Face Dataset 🤗

We are currently working on creating a Hugging Face dataset that will make it easier for researchers and developers to access and utilize the Prompt2Fashion dataset. The dataset on Hugging Face will include the images, their corresponding descriptions, and metadata, allowing for seamless integration with machine learning frameworks and tools.

Stay tuned for updates on the release of this dataset!

### Excel Guide
To further assist users in navigating and utilizing the Prompt2Fashion dataset, we will also provide an Excel guide. This guide will combine the descriptions and images, offering a convenient way to explore the dataset. Each entry in the Excel file will include:

- The generated image.
- The associated description.
- Metadata such as model used (Mistral or Falcon), style category, and evaluation scores (where applicable).
  

## Citation

If you use this dataset in your research, please cite our paper:

```
@misc{argyrou2024prompt2fashion,
      title={Prompt2Fashion: An automatically generated fashion dataset}, 
      author={Georgia Argyrou and Angeliki Dimitriou and Maria Lymperaiou and Giorgos Filandrianos and Giorgos Stamou},
      year={2024}
}

```
