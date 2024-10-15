# AI & Generative AI Applications with AWS 🚀

Explore and implement powerful **AI and Machine Learning** solutions using **Amazon Web Services (AWS)**. This repository demonstrates how to build end-to-end solutions using AWS's comprehensive tools for both **Machine Learning** and **Generative AI**.

`Amazon Bedrock`, `Amazon SageMaker`, `Amazon CodeWhisperer`, `AWS Trainium`, `AWS Inferentia`, `Amazon Polly`, `Natural Language Processing (NLP)`, `Text Generation`, `Image Recognition`, `Generative AI Models`, `AWS Lambda`, `Amazon Rekognition`, `Multimodal Content Generation`, `Large Language Models (LLMs)`, `Custom AI Solutions`

## Contents 📚

| 🏷 **Title**       | 📄 **Description**     | 🛠 **Technology/Library**    | 🔗 **Link**     |
|--------------------|------------------------|-----------------------------|-------------------|
| **First Generations with Amazon Bedrock** | Introduction to Amazon Bedrock for generating customized, powerful responses. Learn how to prompt models to create tailored content. | `Amazon Bedrock`, `Content Generation`, `Model Prompting` | [Notebook Link](notebook/first_generations_amazon_bedrock.ipynb) |



## AWS Development Environment Setup:

To run the code in these files in your own environment, you will need to install some Python dependencies and have access to an AWS environment.

### Steps to Set Up AWS Development Environment:

1. **Create an AWS Account and an IAM User**  
   Follow this guide for more details: [AWS Account Setup Guide](https://docs.aws.amazon.com/SetUp/latest/UserGuide/setup-overview.html)

2. **Generate Access Keys for Your IAM User**  
   For more information, see here: [Creating Access Keys](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey)

3. **Install the AWS CLI**  
   Follow this guide for more details: [AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

4. **Configure AWS CLI**  
   Run `aws configure` with your access keys, and set the default region to `'us-west-2'` for this code. For more information, see here: [Configuring AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html#cli-configure-files-methods)

5. **Use Boto3 for AWS SDK in Python**  
   Boto3 is the AWS SDK for Python, which allows your locally run code to interact with your AWS account. For more information, see: [Boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)

### Requirements File

This code was developed and tested on **Python 3.11**.

```bash
boto3==1.28.68
```

## Hardware Acceleration with AWS 🚀

AWS offers specialized hardware for AI workloads:

- **AWS Trainium**: Custom-designed for efficient training of machine learning models, reducing training time and cost.
- **AWS Inferentia**: Optimized for high-performance and cost-effective inference, accelerating machine learning models in production.

## Credits 🙌

Special thanks to the AWS and AI community for their contributions and support.

## Contributing 🤝

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.