# JinJinLeDao QA Dataset
## Dataset Description
**Repository**: https://github.com/tech-podcasts/JinJinLeDao_QA_Dataset

**HuggingFace**: https://huggingface.co/datasets/GanymedeNil/JinJinLeDao_QA_Dataset
### Dataset Summary
This dataset contains 18,663 Chinese question-answer pairs extracted from 281 episodes of the Chinese podcast "[JinJinLeDao](https://dao.fm/)". The subtitles were extracted using the OpenAI Whisper transcription tool, and the question-answer pairs were generated using GPT-3.5 by dividing the subtitles into blocks and prompting the model to generate questions and answers.

### Supported Tasks and Leaderboards
This dataset can be used for various natural language processing tasks, such as question answering and text generation, among others.

### Languages
The dataset is in Chinese (Mandarin).

## Dataset Structure
### Data Instances
The dataset contains 18,663 question-answer pairs.

### Data Fields
Each data instance contains the following fields:

question: The generated question based on the text block.

answer: The corresponding answer to the generated question.

episode: The title of the podcast episode from which the question-answer pair was extracted.

podcast: The name of the specific program within the "[JinJinLeDao](https://dao.fm/)" podcast where the episode was featured.

### Data Splits
The dataset does not have predefined splits. Users can split the data according to their own requirements.

## Dataset Creation
### Curation Rationale
The dataset was created to provide a resource for Chinese language natural language processing research.

### Source Data
#### Initial Data Collection and Normalization
The source data consists of 281 episodes of the Chinese podcast "[JinJinLeDao](https://dao.fm/)", which were transcribed using the OpenAI Whisper transcription tool.

#### Who are the source language producers?
The source language producers are the hosts of the "[JinJinLeDao](https://dao.fm/)" podcast.

### Annotations
#### Annotation process
The dataset was annotated using an automated process, in which GPT-3.5 was used to generate questions and answers based on text prompts.

#### Who are the annotators?
The dataset was annotated using an automated process, without human annotators.

### Personal and Sensitive Information
The dataset does not contain any personal or sensitive information, except for some user names mentioned in the audio content.

## Considerations for Using the Data
### Social Impact of Dataset
The dataset was created for academic and research purposes only.

### Discussion of Biases
As the dataset was generated using an automated process, there may be biases in the generated questions and answers.

### Other Known Limitations
The dataset was generated using an automated process, which may result in lower quality data compared to manually annotated datasets.

## Additional Information
### Dataset Curators
The dataset was curated [JinJinLeDao](https://dao.fm/) and [Hongyang Jin](https://github.com/GanymedeNil).

### Licensing Information
The dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

### Citation Information
If you use this dataset in your research, please cite the following paper:

N/A

### Contributions
Thanks to [JinJinLeDao](https://dao.fm/) for providing the data and to [Hongyang Jin](https://github.com/GanymedeNil) for curating and sharing this dataset.
