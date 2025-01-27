# QC_SANE

## Requirements:
* Python_version>3.7
* gym==0.15.3
* mujoco-py==2.0.2.5
```bash
pip install -r qc_sane_requirement.txt
```
## To train model
```bash
cd stable-baselines3
python tests/test_qc_sane.py
```

## Reference:
- [1] Github Source: https://github.com/combra-lab/pop-spiking-deep-rl

- [2] Research Paper: https://arxiv.org/abs/2010.09635

## To cite QC_SANE in publications:

```bibtex
@article{gupta2021qc_sane,
  title={QC\_SANE: Robust Control in DRL Using Quantile Critic With Spiking Actor and Normalized Ensemble},
  author={Gupta, Surbhi and Singal, Gaurav and Garg, Deepak and Jagannathan, Sarangapani},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2021},
  publisher={IEEE}
}
```
