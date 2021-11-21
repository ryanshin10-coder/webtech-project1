# webtech-project1
Project: Franken-showcase of web tech
Due Tuesday November 30th 11:55pm

Create an SPA that features some interactive data with d3. Try to use this SPA as an exploration of code/tech examples to refer to later. This means writing comments for your future self that will help you understand what you did. Also, you may be able to add this to your portfolio.

Your SPA project must have:
- A project git : github or heroku
- A READ_ME.txt file with (in this order)
. your name and email
. Project Check-list
. a git log --all
- A server.js (nodejs) file that serves an index.html written with
. that runs by “node server.js”
. external link: https://localhost:3000 views your SPA (index.html…)
- A d3 data display component using
. updatable data that is originally from a JSON file
. a join with enter, exit and transitions
- A non trivial css file with
. Hover/focus/active codes
. Borders with rounded corners
. Gradient backgrounds
- A least one unicode Emojis
- A non-d3 svg that contains at least one:
. circle, path, rect, text element
- HTML elements must include a least one
. Button, H1, list (either ul or ol), link, image
- Javascript arrow functions
. use at least one
- In comments, show
. links to original sources / where you found the code
for my files, you can just refer to them by name (eg. data4njq.html)
. indicate how much different your code
Fulfilling the Project Check-list will be 80% of your grade with the last 20% based on the quality, value and creativity of work. Each entry in the check-list must indicate line-numbers that are responsible for fulfilling the entry and where applicable must be at some point visible in the SPA. An example of the Check-list will be provided before the project is due.
# git
git: local repository
github: remote repository

git: commit (local save)
github: push (remote upload)

master, branch

- Basic Usage -
1. repository creation (git: git init, github: create new repository)
2. git add Filename or *.extention / git add . (all files)
3. git commit -m "message"
4. git status : check
5. git remote add origin https://github.com/Username/RepositoryName
6. git push origin(remote) master or git push origin bran01
7. git pull (git pull origin(remote) master)
8. git clone [url] : download to local
9. git checkout master
10. git merge bran01
11. git log
12. git grep
13. git remote : 원격 저장소 목록 표시, -v: 세부 목록, add(#5), rm
14. git reset -soft HEAD ^ 

- Basic Concept -


![image](https://user-images.githubusercontent.com/68491757/142261040-39ae4e21-6c12-4e4d-9ad2-9a31265bbe04.png)




- Branch -

git branch : branch check
git checout -b bran01 (git branch bran01 & git checkout bran01)
git branch -d bran01 : delete branch

==========================
# MARKDOWN
MARKDOWN 정리, 실습 for README.md

# 1. 제목(글머리) 작성
# H1 제목  
## H2 부제목
### H3 소제목
#### H4 제목4
##### H5 제목5
###### H6 제목6


# 2. 번호 없는 리스트 작성
* 리스트1
  - 리스트2
    + 리스트3
    
# 3. 번호 있는 리스트 작성
1. 리스트1
2. 리스트2
3. 리스트3 

# 4. 이텔릭체(기울어진 글씨) 작성
*텍스트*

# 5. 굵은 글씨 작성
**텍스트**

# 6. 인용
> 인용1

> 인용2
>> 인용안의 인용

# 7. 수평선 넣기

---
  
# 8. 링크 달기
(1) 인라인 링크  

[블로그 주소](https://lsh424.tistory.com/)

(2) 참조 링크  

[블로그 주소][blog]

[blog]: https://lsh424.tistory.com/

# 9. 이미지 추가하기
![이탈리아 포지타노](https://user-images.githubusercontent.com/31477658/85016059-f962aa80-b1a3-11ea-8c91-dacba2666b78.jpeg)

### 이미지 사이즈 조절
<img src="https://user-images.githubusercontent.com/31477658/85016059-f962aa80-b1a3-11ea-8c91-dacba2666b78.jpeg"  width="700" height="370">

### 이미지 파일로 추가하기
<img src="Capri_Island.jpeg" width="700">

# 10. 코드블럭 추가하기

```swift
public struct CGSize {
  public var width: CGFloat
  public var heigth: CGFloat
  ...
}
```

# etc

**텍스트 굵게**  
~~텍스트 취소선~~

### [개행]  

스페이스바를 통한 문장개행  
스페이스바를 통한 문장개행  

br태그를 사용한 문장개행
<br>
<br>
br태그를 사용한 문장개행


### [체크박스]

다음과 같이 체크박스를 표현 할 수 있습니다. 
* [x] 체크박스
* [ ] 빈 체크박스
* [ ] 빈 체크박스

### [이모지 넣기]
❤️💜💙🤍

### [표 넣기]
|왼쪽 정렬|가운데 정렬|오른쪽 정렬| 
|:---|:---:|---:| 
|내용1|내용2|내용3| 
|내용1|내용2|내용3| 

<br>

### 정리내용
[정리 내용 보기](https://lsh424.tistory.com/37)
