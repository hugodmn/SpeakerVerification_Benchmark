# Speaker Verification Project

This project aims to test three different models for speaker verification using audio samples from the IEMOCAP dataset. We randomly selected 10 samples from each of the 5 IEMOCAP sessions, with 2 speakers from each session, resulting in a total of 50 audio samples for evaluation.

## Models

We evaluated the following three speaker verification models:

1. **ECAPA-TDN**
2. **Resnet**
3. **CAM++**

## Approach

For comparing the audio samples, we computed the cosine distance between the embeddings generated by each of the three models. The cosine distance measures the similarity between two embeddings, providing insights into the likelihood of samples being from the same speaker.

## Equal Error Rate (EER)

We report the Equal Error Rate (EER) for the predictions made by each of the three models. EER is a metric that quantifies the trade-off between false acceptance and false rejection rates for various threshold values. The following threshold values were used in our evaluation:

- 0.3
- 0.4
- 0.5
- 0.6
- 0.7

Here are the EER results for each model at different threshold values:

| Model       | Threshold 0.3 | Threshold 0.4 | Threshold 0.5 | Threshold 0.6 | Threshold 0.7 |
|-------------|---------------|---------------|---------------|---------------|---------------|
| ECAPA-TDN   | EER Value     | EER Value     | EER Value     | EER Value     | EER Value     |
| Resnet      | EER Value     | EER Value     | EER Value     | EER Value     | EER Value     |
| CAM++       | EER Value     | EER Value     | EER Value     | EER Value     | EER Value     |


