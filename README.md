# webAssembly_in_action !
### 웹어셈블리가 지원하는(지원 예정인) 언어들
1. C/C++   
2. 어셈블리스크립트는 타입스크립트를 받아 웹어셈블리로 변환하는 새로운 컴파일러임. 타입스크립트가 이미 정형언어이고 이미 자바스크립트로
트랜스파일된다는 점에서 타입스크립트를 변환하는 것은 일리가 있다.
3. TeaVM은 자바를 자바스크립트로 트랜스파일하는 툴로서, 지금은 웹어셈블리도 생성한다.
4. 고(Go)언어는 1.11 버전부터 가비지 수집기를 컴파일된 웹어셈블리 모듈의 일부로 포함하여 포팅하는 실험을 진행중이다.
5. 파이어다이드(Pyodide)는 파이썬의 과학 기술 계산 스택(넘파이(Numpy), 판다스(Pandas), 맷플롯립(MatPlotlib))의 코어 패키지를 포함한
파이썬 런타임이다.
6. 블레이저(Blazor)는 C#을 웹어셈블리에 가져오기 위해 마이크로소프트사에서 실험중인 웹 프레임워크이다.


[웹어셈블리로 컴파일 가능한 언어와 자체 VM을 갖고 있는 언어를 정리해놓은 사이트](https://github.com/appcypher/awesome-wasm-langs)

### 실행환경
window wsl2 Ubuntu 18.04 LTS

```bash
    cd emsdk
    git pull
    ./emsdk install latest
    ./emsdk activate latest
    source ./emsdk_env.sh
    emcc -v
```
테스트 버전은 2.0.15임 
