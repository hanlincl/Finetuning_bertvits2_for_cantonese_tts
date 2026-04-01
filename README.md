# Finetuning_bertvits2_for_cantonese_tts
This project focuses on fine-tuning the Bert-VITS2 framework to develop a robust Text-to-Speech (TTS) model specifically optimized for Cantonese speech synthesis. The system integrates the HKCantonese Models developed by Chenzi Xu to ensure precise phonetic transcription and linguistic alignment.

To ensure reproducibility, the required dataset—comprising training and validation subsets of WAV audio and text files—must be stored in the user’s Google Drive: https://drive.google.com/file/d/1gubwNvT0rSz75GnAQplKZkK9-dBLK-06/view?usp=drive_link

This research develops a Cantonese Text-to-Speech (TTS) system specifically targeting the Canton (Liwan) dialect by leveraging the Bert-VITS2 framework, an advanced iteration of the VITS2 architecture. The training corpus is derived from the Liwan sub-dataset of China’s National Project of Protection of Language Resources (CPLR). Phonetic alignment is achieved using HKCantonese Models and the Montreal Forced Aligner (MFA) to process WAV files and TextGrid annotations.

While the model has been trained, the inference and synthesis phase remains a work in progress. Future evaluation of the synthesized speech will involve Mean Opinion Score (MOS) and Comparative Mean Opinion Score (CMOS) tests conducted by native Cantonese speakers, assessing three key dimensions: articulatory precision, prosodic naturalness, and voice quality.

Due to the procedural complexity and certain technical constraints, some initially anticipated features were not fully implemented. For a comprehensive account of the methodology, encountered challenges, and current progress, please refer to the detailed PDF report uploaded to this repository.

References:

[1]	International Telecommunication Union (ITU). (1994). ITU-T Recommendation P.85: A method for subjective performance assessment of the quality of speech voice output devices. Geneva: ITU.

[2]	Lee, J. L. (2015–). PyCantonese: Cantonese Linguistics in Python. Accessed 31/03/2026. (Available at Github: https://github.com/jacksonllee/pycantonese)

[3]	Snow, D. (2010). Hong Kong and modern diglossia. International Journal of the Sociology of Language, 2010(206).

[4]	State Language Commission of People’s Republic of China. (2015). China’s National Project for the Protection of Language Resources. Accessed 31/03/2026. (Available at https://zhongguoyuyan.cn/)

[5]	Viswanathan, M. , & Viswanathan, M. . (2005). Measuring speech quality for text-to-speech systems: development and assessment of a modified mean opinion score (mos) scale. Computer Speech & Language, 19(1), 55-83.

[6]	Xu, Chenzi. (2023). HKCantonese Model. Accessed 31/03/2026. (Available at Github: https://github.com/chenchenzi/HKCantonese_models/tree/main)