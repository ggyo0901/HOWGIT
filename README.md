# GIT
Test1
로 하나의 프로그램을 같이 제작할 수 있게 만들어 줌
    https://github.com
    
터미널 
    경로 이동 할 수 있는 방법
    cd 하위 폴더ㅓ
        (하위폴더 이동)
    cd.. 상위 폴더로나가기

Git 에러 해결
    Author identity unknown
    </p>
    <ol>
        <li>git init
            프로젝트 내에 로컬(개인서버) 저장소 생성
            할떄 원하는 주소가안나오면 하나씩 하위 폴더로 들어가려면 cd명령어로 하나씩들어간다
           ex) cd frontend2  --->cd Day04
            하나씩 상위폴더로 나갈떄는 cd..사용
        </li>
        <li>git add
            깃에 버전 관리할 파일을 선택(깃에 올릴 파일 선택,stage 올림)
            git add . (변화가 있는 애들은 모두 스테이징)
        </li>
        <li>
            git commit -m "커밋할 메시지"
        하나의 버전으로 만들어서 관리 (저장)
        </li>
        <li>
            git remote add origin "깃허브주소"
        로컬 저장소에 깃허브 저장소 주소 설정
        </li>
        <li>
            git push -u origin master/main
        만든 버전(커밋)을 깃허브에 올리는것(밀어넣다)
        </li>
        <li>
            git pull origin master/main
        깃허브에 업데이트 된 내용을 받는 것
        </li>
        <li>git clone
            깃허브에 올라와있는 다른 파일들 내려받기(처음)</li>
    </ol>
