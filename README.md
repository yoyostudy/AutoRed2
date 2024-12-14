<h1 align="center"><img src="assets/autored-logo.png" style="vertical-align: middle" width="25px"> <b>AutoRed</b>: Automated Attack Generation Framework for Red Teaming of Large Language Models</h1>  

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
