conda create --name pokey python=3.10
activate pokey
cd baselines
pip install -r requirements.txt
python run_pretrained_interactive.py
