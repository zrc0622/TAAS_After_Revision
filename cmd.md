# BC
```
python hirl/train_all.py --agent BC --port {your port} --model_name {your model name} --env straight_line --random --plot
```

## 实例
```
python hirl/train_all.py --agent BC --port 11111 --model_name bc_random_1 --env straight_line --random --plot
```

---

# HIRL
```
python hirl/train_all.py --agent HIRL --port {your port} --type soft --model_name {your model name} --env straight_line --random --plot
```

## 实例
```
python hirl/train_all.py --agent HIRL --port 11111 --type soft --model_name hirl_random_1 --env serpentine --random --plot
```

---

# E-SAC
```
python hirl/train_sac.py --type ESAC --port {your port} --model_name {your model name} --env straight_line --random --plot
```

## 实例
```
```

# SAC
```
python hirl/train_sac.py --type SAC --port {your port} --model_name {your model name} --env straight_line --random --plot
```