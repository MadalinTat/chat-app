# Falcon-7b-Instruct: Chat App 𓅃

![Falcon](falcon-llm.jpeg)

This is a simple UI chat using the Falcon-7b-instruct model.
It was created using the Langchain and Chainlit frameworks.

- [Falcon](https://huggingface.co/tiiuae/falcon-7b-instruct) - the official HuggingFace model card for Falcon-7b-Instruct
- [Langchain](https://python.langchain.com/docs/get_started/introduction.html) - documentation
- [Chainlit](https://docs.chainlit.io/overview) - UI documentation

Read more about the Falcon model: [link](https://falconllm.tii.ae/)

## Use the chat:
1. Fork this repository:

   ```
   https://github.com/MadalinTat/falcon7b-instruct-chat.git
   
   cd falcon7b-instruct-chat
   ```
   
2. Rename example.env to .env and then place your token in the file. Get your Hugging Face API Token from [here](https://huggingface.co/settings/tokens).
   
   ```
   HUGGINGFACE_API_TOKEN = your-huggingface-api-token-here
   ```
   
3. Run the following command in the terminal to install the necessary packages:
   
   ```
   pip install -r requirements.txt
   ```
   
4. Run the following command and start chatting!

   ```
   chainlit run app.py -w
   ```

## Soon

I am planning to work more on this app:
- [ ] Extend the capabilities of Langchain 🦜
- [ ] Extra UI features 🕹️
- [ ] Ability to create tasks and complete them 📝 [BabyAGI inspired](https://github.com/yoheinakajima/babyagi/)
- [ ] Blog post about how I built and thought through everything ✏️
- [ ] Fine-tune Falcon 7b 🪇
- [ ] Implement the fined-tuned model ⚙️
- [ ] Blog post about fine-tuning ✏️
