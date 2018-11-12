# GIT~~~다시

1. 먼저 github 서버에서 먼저 저장소를 생성
2. 내컴퓨터에 github 자료를 복제(clone)
   1. 복제시에는 폴더내부에 아무것도 없어야
   2. 복제할 폴더명과 동일하면 복제되지 않는다.
   3. 복제가 되더라도 기존자료와 충돌
   4. 사용하고 있는 깃폴더내부에 다른 깃자료를 복제하는 것은 권장하지X
3. 복제후, 자료를 올릴때에는 항상 깃공유영역의 최상단에서 처리

```sh
$ gitClone (master)         //여기가 최상단
```

4. 깃공유(설정)가 되어있지않은 폴더에서는 깃으로 자료를 보낼수가 없다!

```shell
$ gitClone   // 깃허브와 연동이 되어있지 않은 위치이기때문에 아무것도 되지 않는다!!
```

---

우리가 할일 1

1. 저장소를 생성(홈페이지를 만드는 것이라면!!) : **README.md 생성버튼 체크**

2. git clone 으로 자료를 복제

3. 자료를 담기전에 `.gitignore`파일을 생성해서 올리지 않을 자료를 체크

   ```.gitignore
   ## 보내지 않을 자료 리스트
   **/*.psd
   **/*.ai
   **/work/
   ```

4. `git branch gh-pages && git checkout gh-pages` 입력하여 브랜치생성 및 이동

5. 복제된 폴더에 필요한 자료를 담는다.(gh-pages branch를 확인하세요~)

6. 깃허브와 연동하면된다.

   1. **git add** 폴더명
   2. **git commit -m "첨부자료내용"**
   3. git add 폴더명
   4. git commit -m "첨부자료 내용"
   5. ....
   6. 위처럼 반복으로 사용하는 이유는 **정확성**과 한번에 너무많은자료, 너무 무거운자료는 올라가지 않기에 나눠서 전송
   7. **git push**

7. github 페이지에서 branch로 확인

8. setting페이지에서 기본을(branch메뉴) gh-pages로 변경(주 목적이기때문에...)

9. option메뉴에서 주소를 찾아서 확인

   


