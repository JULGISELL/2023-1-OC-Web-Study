# 2주차 과제 
## git의 명령어 (add,commit,push)
### - add
Working directory에서 일어난 변화를 Staging Area에 쌓아두기(옮기기) 위해 사용하는 명령어. 명확하게는 "변화들 중 다음 커밋에 포함시킬 변화들을 모아두기"로 기억.
 ### - commit
 Staging Area에 쌓인 변화를 논리적으로 엮어내어 이름을 붙여주고 Local Repository에 저장하는 명령어. 다양한 변화들이 일어났을때 알기 쉽게 하기 위하여 사용.
 ### - push
 Local Repository에 커밋한 내용을 Remote Repository로 옮기는 명령어. push를 통해 내 컴퓨터에서 일어난 일을 공통의 외부 저장소로 보내 작업을 공유.
 ## <br> git fetch와 full의 차이점 
git fetch와 git full은 모두 Remote Repository의 (변경)내용을 가져오는데 사용. 다만 **git fetch는 가져온 변경내용이 Local Repository에 영향을 주지 않고** 변경사항을 '확인'만 할 수 있고, **git full은 가져온 변경내용이 Local Repository에 저장(병합)된다**.  
따라서 git full을 사용할 때는 이미 Local Repository에 commit된 내용과 충돌하여 파일이 손상될 수 있으므로 git fetch를 통해 변경사항을 먼저 확인한 후 Local Repository가 깨끗한 상태에서 사용하는 것이 좋다.