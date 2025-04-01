# Large Language Model for Sentiment Analysis

## Overview
This project focuses on fine-tuning a Transformer-based Large Language Model (LLM) for sentiment analysis. The model incorporates advanced mechanisms such as **Grouped Query Attention** and **Sparse Mixture of Experts** to enhance efficiency and accuracy in **PyTorch** with **Generative AI** techniques.

## Key Features
- **Fine-Tuned Transformer-Based LLM**: Improved sentiment classification by training a specialized language model.
- **Grouped Query Attention**: Enhanced query processing speed and efficiency.
- **Sparse Mixture of Experts**: Optimized computational performance while maintaining accuracy.
- **Achieved 68.4% Accuracy**: Surpassed baseline models with efficient memory utilization.
- **21% Faster than Vanilla GPT-2**: Significant improvement in inference speed with PyTorch implementation.


## Results
| Model                 | Accuracy | Speed Improvement |
|----------------------|----------|------------------|
| Vanilla GPT-2        | 47.4%    | -                |
| Grouped Query LLM    | 68.4%    | 21% Faster       |

## Future Work
- Implement additional optimizations for inference speed.
- Experiment with different model architectures.
- Deploy the model as an API for real-time sentiment analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
