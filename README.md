# GitHub 실습 가이드 📘
</br>

이 저장소는 GitHub의 기본적인 기능인 커밋, 머지, 브랜치를 연습하기 위한 가이드입니다. `test.txt` 파일을 사용하여 각 기능을 실습해 보겠습니다. 실습하기 전 GitHub 웹 인터페이스나 Gitbash(추천)와 같은 Git 커밋이 가능한 도구나 플랫폼이 필요합니다. </br>

## 시작하기 전에 🚀
</br>
- 이 저장소를 자신의 계정으로 포크(Fork)하세요.</br>
- 포크한 저장소를 자신의 로컬 컴퓨터로 클론(Clone)합니다.</br>

`git clone https://github.com/yeajongcheol/GitPractice`
</br>

</br>

## 브랜치 생성 및 변경사항 적용하기 🌿

</br>

1. 새로운 브랜치를 생성합니다.</br>
`git branch new-branch`

</br>

2. 생성한 브랜치로 이동합니다.</br>
`git checkout new-branch`
</br>

3. 'test.txt' 파일을 열고 추가적인 내용을 기록합니다.
</br>
   
4. 변경사항을 커밋합니다.</br>
`git add test.txt`
`git commit -m "Add more text to test.txt on new-branch"`

</br>

5. 변경사항을 원격 브랜치에 푸시합니다.</br>
`git push --set-upstream origin new-branch`

</br>

</br>

## 머지하기 🔄
</br>

1. 'master' 브랜치로 이동합니다.</br>
`git checkout master`
</br>

2. 새로운 브랜치의 변경사항을 master 브랜치에 머지합니다.</br>
`git merge new-branch`
</br>

3. 머지된 변경사항을 원격 저장소에 푸시합니다.</br>
`git push`
</br>

</br>

## 완료 🎉
여기까지 브랜치 생성 및 머지 기능을 연습해 보았습니다. 수고하셨습니다!

</br>

## ❓참고자료
</br>

[Gitbash 초기설정 참고](https://dev-play.tistory.com/entry/Git-Git-hub-%EC%99%84%EC%A0%84-%EC%B4%88%EB%B3%B4%EC%9E%90-%EC%82%AC%EC%9A%A9%EB%B2%95-Git-bash-%ED%99%9C%EC%9A%A9)

[레알 쉬운 깃허브 협업하기](https://youtu.be/IT41djAKUgg?si=kClqgFkmkP0eSEFD)


