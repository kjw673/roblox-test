# Roblox Maps

Roblox Studio에서 만든 맵 파일을 보관하는 저장소입니다.

## 맵 저장하기

1. Roblox Studio에서 맵을 연 뒤 **File → Save to File**을 선택합니다.
2. `maps/` 폴더에 알아보기 쉬운 이름으로 저장합니다. 예: `maps/obby.rbxlx`
3. 가능하면 XML 형식인 `.rbxlx`를 사용하세요. GitHub에서 변경 내용을 비교하기 쉽습니다. `.rbxl`도 저장할 수 있지만 바이너리 파일이라 변경점 비교가 어렵습니다.

맵을 여러 개 만들면 각각 별도 파일로 저장하세요.

```text
maps/
├── obby.rbxlx
└── lobby.rbxlx
```

## 변경 사항 올리기

저장소 폴더에서 명령 프롬프트(CMD)를 열고 실행합니다.

```cmd
git add .
git commit -m "Add a new map"
git push
```

이 저장소는 비공개로 만들어졌습니다. 다른 사람에게 링크를 보내도 초대하지 않으면 내용을 볼 수 없습니다.