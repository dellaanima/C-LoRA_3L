# 3L_Aiffelthon_Online_5th
안녕하세요. 온라인 5기 리서치 네 명으로 구성된 3L입니다. 

아이펠에서 진행한 졸업 과제인 아이펠톤으로 PEFT기법 중 하나인 LoRA를 통해 model compression을 진행해보았습니다. 

# Main Idea
1. Weight Decay Scheduling(WDS):
   Adapter처럼 W + BA 형태로 학습시킴과 동시에, W를 점진적으로 decay하여 학습이 진행됨에 따라 BA에 잃어버린 W 정보를 학습함.
2. Noise와 Bias:
   W의 학습 정보를 공격적으로 decay하기 위해 추가.
   Origianl Weight 와 Noise는 독립적이라는 가정하에, noise가 decayed weight를 보상.

![image](https://github.com/dellaanima/3L_Aiffelthon_Online_5th/assets/134067511/7ff16426-fc6a-40e0-9af9-47b14de71785)


# Repository 
- Project Presentations: 진행 과정을 매주 요약해서 발표를 진행.
- src: Keras 형태의 LoRA 코드와 다음 이론을 기반으로 한 Toy Project, VGG16, Bert-Tiny, Small로 진행한 실험이 정리되어있음.
## Method Applied
- Weight Decay
- Weight Decay, C_weight
- Weight Decay, Noise
- Weight Decay, C_weight, Noise

# License

# Contact 
