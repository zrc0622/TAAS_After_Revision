# HIRL
python hirl/train_all.py --agent HIRL --port {your port} --type soft --model_name {your model name} --env straight_line --random

python hirl/train_all.py --agent HIRL --port 11111 --type soft --model_name hirl_random_1 --env serpentine --random

# SAC
python hirl/train_sac.py --type ESAC --port {your port} --model_name {your model name} --env straight_line --random