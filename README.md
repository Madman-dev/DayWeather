![header](https://capsule-render.vercel.app/api?type=waving&color=ff6d1c&height=300&section=header&text=☀️DayWeather%20&fontSize=90&fontColor=ffffff)
# DayWeather 날씨 어플 ☀️

#### 기간 : 2023/09/26 ~ 2023/10/06 (10일)<br/><br/>

## 어플 소개 🤠
우리 하루의 시작과 끝을 책임지는 날씨.<br/>
출근과 퇴근을 책임지는 필수 어플이 된만큼 빠르게 필요한 정보만 제공할 수 있는 형태로 날씨 어플을 구성
<br/><br/>
✅ 지도를 통해 **지역별로 실시간 기상 상황**을 공유<br/>
> 위치에 따라 온도를 전 viewController에 제공

✅ 날씨 상황과 **온도에 따라 추천하는 OOTD** 복장<br/>
> 복잡한 데이터를 깔끔하게 보여주기 위해 UICompositionalLayout 활용<br/>
> 온도에 따라 다른 안내문 출력

✅ 일몰, 일출 **시간에 따른 맞춤 노래** 추천<br/>
✅ 현재 위치에서 찾는 **음식 추천**<br/>
> 현 위치에서 원하는 종류의 식당을 검색
> 5가지 선택지를 탭 시, 주변 식당 데이터 하단에 출력

**나의 하루를 온전히 책임지는 기상 어플, DayWeather을 소개합니다!**
<br/><br/>

## 팀 소개 🧑‍🤝‍🧑
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
<br/>

## 개발환경 👨🏻‍💻
### 담당 [FoodPairing] 개발 내용 정리
- 각 페이지별, 현재 기상 온도를 출력하고 사용자에게 해당 기상 상황을 알리는 표현과 추천 키워드를 알리는 기능 구현
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

### 음식 페어링 상세
1. reverseGeocode 좌표값을 주소로 변환하여 받은 데이터가 보이지 않는 문제
Optional 데이터로 인해 데이터를 받고 있지만 보이지 않는 문제를 디버깅을 통해 해결
2. 데이터를 많이 사용하는 지도 어플의 재활용 시도
foodPair View가 modal로 등장하며 mainView가 메모리에서 내려가지 않아 앱이 충돌 - 개별 mapView를 생성하기로
3. MVVM 디자인 패턴을 명확하게 활용하지 못한 문제
호출받는 데이터와 화면이 다양한 만큼 MVVM을 적용하기로 하였으나 낮은 이해도로 완벽하게 분리하지 못함


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
