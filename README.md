<h1 align="center"><img src="assets/autored-logo2.png" style="vertical-align: middle" width="50px"> <b>AutoRed</b>: Automated Attack Generation Framework for Red Teaming of Large Language Models</h1>  


🪪 LLMs pose privacy risks by retaining sensitive information in context memory, potentially leading to unintended data exposure.

🛡️ Traditional red teaming is costly and slow. 

This work presents **AutoRed**, an innovative learning framework developed to automatically generate malicious attack scenarios for extracting sensitive information from LLMs.

**AutoRed** consists of two low level components: the _malicious prompt generator_ and the _sensitive information extractor_, along with an one high level components: the _stop point identifier_.

<h3 align="center"> TBD </h3>

- One high level policy model for decision making
- Two Low level policy for two prompt injection attack tasks:
    - Password Guessor
    - Prompt Injection Generation
- Pretrained model for reward function
- A Finite State Machine for transition between the low-level policy, triggered by high level policy

```
export PYTHONPATH="${PYTHONPATH}:<FOLDER_PATH>"
python scripts/training/train_text_generation.py --config_path scripts/training/task_configs/pi_gen/pi_supervised.yml
```
