

## how to git submodule update
when folder is empty, init submodules
```bash
git submodule update --init --remote
```

after folder is not empty, update submodules
```bash
git submodule update --remote --recursive
```

## 비디오 서비스
[snservice](https://github.com/sglee487/snservice) : 전체
- [api-server](https://github.com/sglee487/snserver) : 서버 (Spring boot(Kotlin))
- [cloud-stack(k3s)](https://github.com/sglee487/snservice-cloud-stack) : 클라우드 인프라 설정 (쿠버네티스(k3s)) 
- [client](https://github.com/sglee487/snclient) : 클라이언트 (tauri(React + redux))

<img src="https://github.com/user-attachments/assets/bb62f3f8-1499-49ab-b736-5e92bc6b1a78" width="500" />
<br/>
- 비디오 및 스트리밍 서비스 만들려고 했는데 유투브 플레이리스트 음악 듣기용으로 노선 트는 중
