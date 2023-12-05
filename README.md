# ML-CyberSecurity-BackdoorAttacks

## Evaluating the Backdoored Model:

The DNN architecture used to train the face recognition model is the state-of-the-art DeepID network.

To evaluate the backdoored model, execute `eval.py` by running:

```bash
python3 eval.py <clean validation data directory> <poisoned validation data directory> <model directory>.
