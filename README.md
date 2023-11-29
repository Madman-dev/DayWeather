![header](https://capsule-render.vercel.app/api?type=waving&color=ff6d1c&height=300&section=header&text=☀️DayWeather%20&fontSize=90&fontColor=ffffff)

# DayWeather 날씨 어플 ☀️

#### 기간 : 2023/09/26 ~ 2023/10/06 (10일)
<br/>

## 어플 소개
우리 하루의 시작과 끝을 책임지는 날씨.<br/>
회사원의 출근을 책임지는 필수 어플로 의미있는 하루의 시작을 돕는 날씨 어플은 현대인의 필수품이 되었습니다.<br/>
출근 전 빠르게 찾아보는 어플인만큼 불필요한 정보를 덜어 사용자에게 제공하고자 했습니다.<br/>
<br/>
지도를 통해 지역별로 실시간 기상 상황을 공유하고 날씨 상황과 온도에 따라 추천하는 OOTD 복장부터<br/>
일몰, 일출 시간에 따른 맞춤 노래 추천과 언제든 쉽게 받을 수 있는 음식 추천까지

나의 하루를 온전히 책임지는 기상 어플,
DayWeather을 소개합니다!
<br/>

## 구성원
<div align="center">

## 🧑‍🤝‍🧑 Team Members (구성원)
<table>
  <tbody>
    <tr>
     <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/2rang2">
       <img src="https://avatars.githubusercontent.com/u/139103064?v=4" width="100px;" alt="2rang2"/>
       <br />
         <sub>
           <b>이랑</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
     <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/cheshire0105">
       <img src="https://avatars.githubusercontent.com/u/106953561?v=4" width="100px;" alt="조계성"/>
       <br />
         <sub>
           <b>조계성</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
    </td>
      <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/Oong2">
       <img src="https://avatars.githubusercontent.com/u/101612441?v=4" width="100px;" alt="김기호"/>
       <br />
         <sub>
           <b>김기호</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
    </td>
      <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/Madman-dev">
       <img src="https://avatars.githubusercontent.com/u/119504454?v=4" width="100px;" alt="이동준"/>
       <br />
         <sub>
           <b>이동준</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
    </td>
      </tbody>
  </table>
</div>

</div>

## 개발환경
### 주요 개발 기능
- 현재 위치에 따라 맵에서 핀 찍어주기
- 각 페이지별, 현재 기상 온도를 출력하고 사용자에게 해당 기상 상황을 알리는 표현과 추천 키워드를 알리는 기능 구현
- 기상 컨디션(온도)에 따라 음악 추천 기능 구현
- 기상 컨디션(온도)에 따라 알맞는 옷 추천 기능 구현<br/>
  compositionalLayout을 이용한 여러 옷 관련 정보 보여주기<br/>
  section별로 소개 텍스트 노출
- 위치에 따라 알맞는 음식 추천 기능 구현<br/>
  collectionView를 이용해 다양한 메뉴 정보 보여주기<br/>
  tableView를 이용해 검색된 인근 식당 정보 보여주기<br/>
  <br/>
  총 5가지 메뉴의 식당을 검색할 수 있도록 정리 ✅<br/>
  선택된 메뉴의 이름과 위치가 보일 수 있도록 정리 ✅<br/>
  맵에서 탭할 경우, 해당 위치의 infoWindow 팝업 ✅<br/>
- UserDefault를 이용한 사용자 데이터 관리

### 화면구성/기능별 분담
- 메인[맵]페이지 : 조계성
- 서브[음원 페어링] 페이지 : 이랑
- 서브[옷 페어링] 페이지 : 김기호
- 서브[음식 페어링] : 이동준


## 와이어프레임
### Wire Frame
<img width="262" alt="Screenshot 2023-10-06 at 4 04 59 PM" src="https://github.com/NabaeCamp/DayWeather/assets/119504454/8dc8a738-fc88-47ad-b504-8a704c8fca11">
<img width="262" alt="Screenshot 2023-10-06 at 4 05 14 PM" src="https://github.com/NabaeCamp/DayWeather/assets/119504454/c17cc895-95ec-4c3e-ad2c-19b24cedc026">
<img width="262" alt="Screenshot 2023-10-06 at 4 06 25 PM" src="https://github.com/NabaeCamp/DayWeather/assets/119504454/b16d8b41-61d7-4935-a2d8-ce232e49fe8e">
<img width="262" alt="Screenshot 2023-10-06 at 4 06 42 PM" src="https://github.com/NabaeCamp/DayWeather/assets/119504454/0d95d03e-daa7-49f3-b2c3-ac6d61f62326">
<img width="262" alt="Screenshot 2023-10-06 at 4 07 28 PM" src="https://github.com/NabaeCamp/DayWeather/assets/119504454/645d8bca-acab-4ecc-aff6-9664e4aee013">

#### [👆🏻👆🏻 깊게 한번 알아보기](https://www.figma.com/file/YIN3FybTTWXQV1Bv3jkOYQ/Untitled?type=design&mode=design&t=MYzn7h3lqIlYJxo0-0)
<br/>

## Git Convention
<img width="666" alt="Screenshot 2023-10-06 at 4 11 52 PM" src="https://github.com/NabaeCamp/DayWeather/assets/119504454/8c136a2c-8c67-4129-bf5f-26ffd8afd66f">
