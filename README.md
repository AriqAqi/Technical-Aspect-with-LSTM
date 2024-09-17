# Classification of Health App Adoption Based on Technical Aspects Using Long Short-Term Memory Algorithm

## Research Overview

In Indonesia, the rise of health applications has transformed healthcare access and quality. However, the adoption of these apps is still limited due to factors such as digital infrastructure gaps, varying IT literacy levels, and concerns about data privacy. This study aims to address these challenges by evaluating the technical factors influencing user adoption through the use of the **Long Short-Term Memory (LSTM)** algorithm.

By interviewing health app users—especially parents with children—and applying LSTM models, we classified user responses to determine which factors were most significant in encouraging or inhibiting adoption.

## Key Findings

The research compared two LSTM models (single-layer and double-layer), revealing:

- **Perceived Usefulness** was the strongest factor influencing user adoption.
- **System Quality** and **Facilitating Conditions** played significant roles in enhancing user trust and satisfaction.
- The **single-layer LSTM model** achieved the highest validation accuracy at **84.5%**, outperforming the double-layer model slightly.

These insights can be used by app developers to refine the design and functionality of health apps, ultimately leading to higher adoption rates and improved healthcare outcomes across Indonesia.

## Methodology

The study employed the **CRISP-DM** framework for data mining, involving:

- **Data Collection:** Interviews with health app users in Bandung Regency.
- **Data Preparation:** Text preprocessing using Python libraries (Keras, Sastrawi) to clean, tokenize, and transform the dataset.
- **Modeling:** LSTM models were trained using various configurations (single-layer and double-layer) and different batch sizes (8, 16, 32).
- **Evaluation:** The models were evaluated on accuracy, precision, recall, and F1-scores. The single-layer LSTM with a batch size of 16 provided the best performance.

## Key Metrics

| Model        | Training Accuracy | Validation Accuracy | Loss    |
|--------------|-------------------|---------------------|---------|
| Single-layer (batch 16) | 93%               | **84.5%**            | 0.0804  |
| Double-layer (batch 16) | 95%               | 83.5%                | 0.0772  |

## Technical Factors

We explored several technical factors that contribute to the acceptance of health applications:

- **Perceived Ease of Use** refers to an individual's perception that a specific technology can be used effortlessly and without significant effort
- **Performance Expectancy** refers to the degree of belief that utilizing an information system will enhance an individual's ability to perform tasks more effectively 
- **Effort Expectancy** refers to the level of ease with which a system can be used, which can reduce the physical effort and time required by an individual to complete their tasks
- **System Quality**  refers to the technical attributes of a system that determine its ability to produce accurate and reliable information. Poor system design can lead to limited access to the application
- **Perceived Usefulness**  refers to the level which a user believes that utilizing a system will improve their efficiency and help achieve desired goals
- **Facilitating Conditions** refers to the belief in the availability of organizational support and technological infrastructure to facilitate the system
- **Resistance to Change** describes the attitude of opposition that typically arises from technological changes
- **Technological Incapability** refers to the condition where the necessary technology to operate or use an application is not widely available or sufficient
- **Functionality** denotes the ability of a mobile health application to provide health services and information to users
- **Cost** is often the primary reason behind user reluctance to adopt mobile health applications, encompassing the costs of terminal devices, application purchases, and data traffic during application use

## Conclusion

The results indicate that focusing on improving perceived usefulness, system quality, and facilitating conditions can significantly enhance user acceptance of health applications. This study provides actionable insights for developers to optimize health app features, ensuring they meet user expectations and contribute to better healthcare accessibility in Indonesia.

