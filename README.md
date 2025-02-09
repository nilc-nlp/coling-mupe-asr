# MuPe Life Stories Dataset
A new publicly available dataset consisting of 289 life story interviews (365 hours), featuring a broad range of speakers varying in age, education, and regional accents.


## Dataset
| Hugging Face |
| ------------ |
| [https://huggingface.co/datasets/nilc-nlp/CORAA-MUPE-ASR](https://huggingface.co/datasets/nilc-nlp/CORAA-MUPE-ASR) |
| [https://huggingface.co/datasets/nilc-nlp/CORAA-MUPE-ASR-GZ](https://huggingface.co/datasets/nilc-nlp/CORAA-MUPE-ASR-GZ) (zip and csv files)|

## Model
| Hugging Face |
| ------------ |
| [https://huggingface.co/nilc-nlp/distil-whisper-coraa-mupe-asr](https://huggingface.co/nilc-nlp/distil-whisper-coraa-mupe-asr) |


## Citation
Leal, S.E.; Candido Junior, A.; Marcacini, R.; Casanova, E.; Gonçalves, O.; Soares, A.; Lima, R.; Gris, L.; Aluísio, S.M. MuPe Life Stories Dataset: Spontaneous Speech in Brazilian Portuguese with a Case Study Evaluation on ASR Bias against Speakers Groups and Topic Modeling. Proceedings of the 31st International Conference on Computational Linguistics (COLING) (2025).

````
@inProceedings{Leal2025Coling,
author={Sidney Leal
   and Arnaldo Candido Jr.
   and Ricardo Marcacini
   and Edresson Casanova
   and Odilon Gonçalves
   and Anderson Soares
   and Rodrigo Lima
   and Lucas Gris
   and Sandra Alu{\'i}sio,
title={MuPe Life Stories Dataset: Spontaneous Speech in Brazilian Portuguese with a Case Study Evaluation on ASR Bias against Speakers Groups and Topic Modeling},
booktitle={Proceedings of the 31st International Conference on Computational Linguistics (COLING)},
year={2025}
}
````

## Sponsors / Funding

This work was carried out at the Center for Artificial Intelligence (C4AI-USP), with support by the São Paulo Research Foundation (FAPESP grant #2019/07665-4) and by the IBM Corporation. This project was also supported by the Ministry of Science, Technology and Innovation, with resources of Law No. 8.248, of October 23, 1991, within the scope of PPI-SOFTEX, coordinated by Softex and published Residence in TIC 13, DOU 01245.010222/2022-44. This work has been partially supported by Advanced Knowledge Center in Immersive Technologies (AKCIT/CEIA), with financial resources from the PPI IoT/Manufatura 4.0 / PPI HardwareBR of the MCTI, signed with EMBRAPII.

## Metadata:
- **audio_id**: Sequential id for the interview;
- **audio_name**: Unique code for the interview;
- **file_path**: Wav audio file path;
- **speaker_type**: R is the interviewee, P/1 is interviewer 1, P/2 is interviewer 2 and so on;
- **speaker_code**: Unique code for the speaker;
- **speaker_gender**: Gender of the speaker;
- **education**:  Education level of the interviewee, filled only when speaker_type = 'R';
- **birth_state**: Birth state (region) of the interviewee, filled only when speaker_type = 'R';
- **birth_country**: Birth country of the speaker;
- **age**: Age of the interviewee, calculated with recording_year minus year of birth, filled only when speaker_type = 'R';
- **recording_year**: The year when the audio was recorded;
- **audio_quality**: Can be high or low;
- **start_time**: The start time in the original complete audio file;
- **end_time**: The end time in the original complete audio file;
- **duration**: The duration of the segment;
- **normalized_text**: Text normalized in lowercase and without punctuation marks;
- **original_text**: Text before normalization.


# Examples
Because of files size, the dataset is available at huggingface. But here all the csv's files with metadata for training, validation and test subsets, and a sample for the audio files.

![image](https://github.com/user-attachments/assets/9f053d3c-49dc-493b-9add-a9bcff3042d7)

![image](https://github.com/user-attachments/assets/0603b084-64fa-4231-89fc-1d045d5808d3)
