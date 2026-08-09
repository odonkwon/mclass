pipeline {
    agent any // 어떤 에이전트(실행 서버)에서든 실행 가능
    tools {  // tools : jenkins tools에 등록된 도구 사용
        maven 'maven 3.9.12' // Jenkins Tools에 등록한 이름과 정확히 일치해야 함
        }
    stages {  // stages : 실제 자동 빌드를 수행하는 단계정의
        stage('Git Checkout') {  // 수행단계구분
            steps {
                    // Jenkins가 연결된 Git 저장소에서 최신 코드 체크아웃
                        //Jenkins가 연결된 Git저장소에서 최신 코드 체크아웃
                        checkout scm
            }
        }
    }
}        