# KON Mainnet
## 개요
- 일단은 openethereum으로 만들었음
- smartcontract 기반 PoA로 전환 예정
- 기타 설정 추가 중...

## Install
```bash
git submodule update --init --recursive
cd openethereum
# 해당 폴더 README 따라서 openethereum 컴파일 or Openethereum 최신리눅스 빌드 바이너리 파일 다운로드
# https://github.com/openethereum/openethereum/releases/tag/v3.2.6
```

Config 파일의 경우 Openethereum Config 파일 위치 찾아서 연동
1. conf.toml로 bootnode 등 셋팅
2. genesis.json으로 KON mainnet data injection
[설정 셋팅](https://openethereum.github.io/Configuring-OpenEthereum)


## 관련 자료
- 익스플로러(Blockscout) : https://explorer.kon-wallet.com/
