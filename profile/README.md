```
목차
0. 프로그램 소개
1. 배포 링크
2. 위키 링크
3. 피그마 링크
4. 기술발표
5. Q&A
```
# 프로그램 소개

### 💰 coinTalk
```
코인에 대한 실시간 가격 / 차트 정보를 확인하고 차트에 드로잉툴을 이용해 이미지를 만들 수 있고
차트데이터를 저장하는 기능을 제공하고 채팅방에 공유하며 커뮤니케이션 할 수 있는 프로그램입니다.
```
# 배포 링크

[코인톡 바로가기](https://cointalk.wachsenhaus.com)  
<table>
    <tr>
        <td align="center">메인</td>
        <td align="center">거래소</td>
    </tr>
    <tr>
        <td align="center">
            <a href="https://cointalk.wachsenhaus.com/"><img  width="640px" src="https://user-images.githubusercontent.com/59411545/169392256-1c18615e-971d-44dc-b2e2-c6e9e766b069.gif" />메인</a>
        </td>
        <td align="center">
            <a href="https://cointalk.wachsenhaus.com/trade"><img  width="640px" src="https://user-images.githubusercontent.com/59411545/169392274-fcd81c85-2518-499a-a121-68fea176b2de.gif" />거래소</a>
        </td>
    </tr>
    <tr>
        <td align="center">채팅</td>
        <td align="center">뉴스</td>
    </tr>
    <tr>
        <td align="center">
            <a href="https://cointalk.wachsenhaus.com/chat"><img  width="640px" src="https://user-images.githubusercontent.com/59411545/169392289-a8ab383b-270e-4e73-9e08-ac5f6ee0e14a.gif" />채팅</a>
        </td>
        <td align="center">
            <a href="https://cointalk.wachsenhaus.com/news"><img  width="640px" src="https://user-images.githubusercontent.com/59411545/169392302-17a0cffc-88b3-4834-8e3a-238a00477e13.gif" />뉴스</a>
        </td>
    </tr>
</table>



### 배포 데모 GIF

# 위키 
[위키 바로가기](https://github.com/dduckddack-coinTalk/coinTalk/wiki)
<table>
    <tr>
        <td align="center">위키</td>
    </tr>
    <tr>
        <td align="center">
            <a href="[https://cointalk.wachsenhaus.com/](https://github.com/dduckddack-coinTalk/coinTalk/wiki)"><img  width="640px" src="https://user-images.githubusercontent.com/59411545/169443128-fd748657-96ca-40ee-b068-70f50a75c348.gif" />메인</a>
        </td>
    </tr>
</table>

### 위키 데모 GIF

# 피그마 링크

[피그마 바로가기](https://www.figma.com/proto/ONa4Cdcphe8xCPxzgPSGVV/bitthumb-frontend?page-id=0%3A1&node-id=66%3A1226&viewport=226%2C536%2C0.12&scaling=scale-down&starting-point-node-id=66%3A1226)

### 피그마 데모 GIF

***
# 사용한 기술 스택
프론트


백엔드

# 아키텍쳐
<img src="https://user-images.githubusercontent.com/57323359/169324737-fb01c8c2-ce42-4edf-abd5-8e0915addf1e.png"  />
*** 


# 요구 사항 정의 및 구현 목록
- [x] 메인 페이지 - 코인 거래량 Top5의 간단 정보를 보여준다.
- [x] 메인 페이지 - 전체 채팅 목록을 보여준다.
- [x] 거래소 - 실시간 체결 내역을 보여준다.
- [x] 거래소 - 실시간 호가창을 보여준다.
- [x] 거래소 - 코인의 초성, 영문, 심볼, 이름검색을 지원한다.
- [x] 거래소 - 코인을 브라우저에 즐겨찾기 한다.
- [x] 거래소 - 코인을 원하는 기준으로 정렬 한다.
- [x] 거래소 - 차트 1분, 10분, 30분, 1시간봉 기능
- [x] 채팅 - 로그인한 회원은 채팅을 입력할 수 있고 코인별로 구성된 채팅방에 입장할 수 있다.
- [x] 채팅 - 채팅방에 이미지를 전송하고 표시한다.
- [x] 채팅(Option) - 욕설을 필터링한다. 해당 기능은 서버가 아닌 클라이언트에서 구현한다.
- [ ] 채팅(Option) - 댓글에 좋아요를 누른다.
- [x] 회원 - 로그인 기능
- [x] 회원 - 회원가입 기능
- [x] 회원 - 회원가입시 실제 이메일을 인증한다.
- [x] 회원 - 회원의 정보를 수정한다.
- [x] 회원 - 회원의 프로필을 업로드하여 사용한다.
- [x] 회원 - 리프레쉬,액세스 토큰을 활용하여 사용자 인증을 진행한다.
- [x] 회원 - 회원 탈퇴 기능을 구현한다.
- [ ] 회원(Option) - OAuth 로그인한다.
- [ ] 회원(Option) - Recaptcha 자동 가입방지를 구현한다.
- [ ] 회원(Option) - 회원의 인기도를 구분지어 채팅방에 효과를 제공한다.
- [x] 도화지 - 차트위에 그림을 그려 서버에 이미지와,시간,코인의 종류들을 저장한다
- [x] 도화지 - 저장된 도화지 데이터를 기반으로 이미지와, 해당 시간 때의 차트 데이터를 불러온다.
- [x] 뉴스 - 코인의 뉴스들을 크롤링하여 뉴스 페이지에 보여준다.
- [x] 뉴스 - 채팅방에 최신 뉴스가 보여진다.



###### 만든이
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/"><img  width="100px" src="https://avatars.githubusercontent.com/u/59411545?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/"><img  width="100px" src="https://avatars.githubusercontent.com/u/57323359?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/"><img  width="100px" src="https://avatars.githubusercontent.com/u/73471529?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/"><img  width="100px" src="https://avatars.githubusercontent.com/u/53042885?v=4" /></a>
        </td>  
    </tr>
    <tr>
        <td align="center">최영훈</td>
        <td align="center">박철훈</td>
        <td align="center">유하얀</td>
        <td align="center">김영수</td>
    </tr>
    <tr>
        <td align="center">Front</td>
        <td align="center">User Domain</td>
        <td align="center">Chat, News Domain</td>
        <td align="center">Gateway,Kafka,Slack,Data Lake,Paper Domain</td>
    </tr>
    <tr>
        <td align="center">
            <a href="https://github.com/dduckddack-coinTalk/front">1. Front Repo</a> 
        </td>
        <td align="center">
            <a href="https://github.com/dduckddack-coinTalk/app-user">1. UserService Repo</a> 
        </td>
        <td align="center">
            <a href="https://github.com/dduckddack-coinTalk/front">1. Front Repo</a> 
            <a href="https://github.com/dduckddack-coinTalk/front">2. Front Repo</a> 
        </td>
        <td align="center">
            <a href="https://github.com/dduckddack-coinTalk/front">1. Front Repo</a> 
            <a href="https://github.com/dduckddack-coinTalk/front">2. Front Repo</a> 
            <a href="https://github.com/dduckddack-coinTalk/front">3. Front Repo</a> 
        </td>
    </tr>
</table>
