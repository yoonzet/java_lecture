## 이클립스에서 자바 프로그램을 작성하는 순서

1. 프로젝트를 생성한다. (메뉴 File> New > Java Project)
2. 클래스를 생성한다. (프로젝트 이름 위에서 우클릭> New > Class)
3. 소스파일의 작성 후 저장(자동 컴파일됨)
4. 실행 (메뉴 Run> Run)

---

## Build 관련 메뉴 설명

Build란? → 소스 파일(*.java)로부터 프로그램을 만들어 내는 전 과정

Project > **Build All**

workspace의 모든 프로젝트를 빌드

Project > **Build Project**
현재 프로젝트를 빌드(변경된 소스 파일만 새로 컴파일)

Project > **Clean**
이전 빌드의 정보를 모두 삭제 (모든 소스 파일을 새로 컴파일)

간혹 프로그램이 실행이되지 않을 때 clean - build project 순으로 처리하면 문제가 해결되기도 한다.

Project > **Build Automatically**

소스 파일을 변경 후, 저장할 때마다 자동 컴파일
