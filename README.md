 Here is a summary of the project report in the form of a README file with a diagram:

# Dialogue Summarization Chatbot

This project involved building a dialogue summarization chatbot using the FLAN-T5 large language model. 

## Approach
![image](https://github.com/DBhardwaj21/Chatbot-Using-Flan-T5-base/assets/114652053/a73a5ead-1346-4a63-b8f9-82fccfcf0f86)




- The [KNKarthick DialogSum dataset](https://huggingface.co/datasets/knkarthick/dialogsum) from HuggingFace was used for training and evaluation. This contains dialogues and human-written summaries.

- The pre-trained FLAN-T5 model was fine-tuned on the dataset to create a dialogue summarization model. Hyperparameter tuning was done to improve performance.

- The model's summaries were evaluated using ROUGE scores against the human baselines. Additional techniques like prompt engineering, instruction tuning, and adapter tuning were applied to further enhance the model's summarization capabilities.

- A chatbot interface was built using Gradio to allow users to test the model by entering a dialogue and getting back a summary.

## Key Outcomes

- Fine-tuning FLAN-T5 on the DialogSum dataset produced a chatbot that can summarize dialogues well, outperforming generic FLAN-T5.

- Techniques like prompt engineering, instruction tuning, and adapter tuning led to noticeable boosts in the model's ROUGE scores.

- The chatbot provides an easy way for users to test the model's summarization live.

## Future Work

- Expand the dataset size and diversity to improve generalizability.

- Experiment with more advanced prompt engineering strategies.

- Try training custom adapter modules specialized for dialogue summarization.

- Deploy the chatbot as a web application.

Overall, this project demonstrated how large language models can be effectively leveraged for dialogue summarization through fine-tuning and lightweight customization techniques.
