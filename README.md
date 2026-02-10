# Dlthon_01_Motocycle_Night_Ride
---
## 레포지토리 사용법
1. 귀하께서 현재 사용중인 개발환경의 터미널을 이용하여 레포지토리를 받을 폴더로 진입해주세요.
2. `git clone https://github.com/Stray-Weights/Dlthon_01_Motocycle_Night_Ride` 를 입력하여 레포지토리 폴더를 받아주세요.
3. 레포지토리 폴더가 받아지면 터미널에서 `cd Dlthon_01_Motocycle_Night_Ride` 를 입력하여 레포지토리 폴더 내부로 들어가신 후 개발해주시면 됩니다. (셀에서 작업하시거나 터미널 종류에 따라 %cd, "./경로" 등 입력코드가 바뀔 수 있으므로 문제가 있을시 ai에 물어보시면 좋습니다.)

### - 작업하실 시작하실 때 항상 지켜주셔야 할 점이 있습니다.
### - 항상 이 순서를 지켜주세요!
```
git pull origin main      # (중요! 저장소의 업데이트 사항을 가져오면서 시작합니다.)
git add .                 # (내 수정사항을 내 로컬저장소에 스테이징합니다.)
git commit -m "메시지"     # (스테이징한 사항들을 커밋하여 확정짓습니다.)
git push origin main      # (로컬저장소에서 커밋된 사항을 팀 레포지토리로 보냅니다.)
```
각자의 이름의 폴더에서 작업할 것이기 때문에 동료의 파일을 수정할 일이 적겠지만 혹시 모르니 산출물을 push 하실때는 팀원들에게 먼저 알린 후 push 해주시기 바랍니다.
알릴 수 없는 경우에는 commit만으로 로컬저장소에 안전히 저장되므로 commit을 최대한 활용해주시면 됩니다.

궁금하신 사항이 있으실 경우 언제든 저희들끼리 질문을 공유해서 해결하면 좋겠습니다.
---
## 레포지토리 구조
```
Dlthon_01_Motocycle_Night_Ride
├── data(폴더, .gitignore 파일에 의해 무시됩니다.)
│   ├── imagess(폴더, 각자의 로컬에 학습데이터 이미지들이 png파일로 들어있을 것입니다.)
│   ├── COCO_motorcycle (pixel).json
│   └── www.acmeai.tech ODataset 1 - Motorcycle Night Ride Dataset
├── jongha(폴더)
├── mulim(폴더)
├── hangah(폴더)
├── aain(폴더)
├── final_work(최종 산출물 파일 폴더)
└── README.md
```

