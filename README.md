# 3D-Vision-ONNX-Models


### PointNet

- git clone --recurse-submodules https://github.com/anchitmulye/3D-Vision-ONNX-Models.git
- python utils/prepare_data.py --task download
- python utils/prepare_data.py --task convert
- python main.py --task train --num_category 40 --epoch 1 --use_cpu
- python main.py --task test --checkpoint log/classification/2026-05-19_20-46/checkpoints/best_model.pth --log_dir 2026-05-19_20-46 --use_cpu
- python onnx/export_classification.py --checkpoint log/classification/2026-05-19_20-46/checkpoints/best_model.pth --model pointnet_cls
