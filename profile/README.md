# Musinsa Observer

Musinsa Observer는 무신사에서 사용자가 관심 있는 패션 제품을 쉽게 검색하고, 즐겨찾기하고, 가격 변동을 모니터링할 수 있는 iOS 앱과 웹 사이트입니다.  
Musinsa Observer is an iOS app and website that allows users to easily search for fashion items on Musinsa, save favorites, and monitor price changes.

이 앱은 패션 아이템의 현재 가격은 물론 과거 가격 추이도 확인할 수 있어, 사용자가 더 현명한 구매 결정을 내릴 수 있도록 돕습니다. 현재 TestFlight에서 출시되어 있습니다.  
The app helps users make smarter purchasing decisions by showing current prices and past price trends of fashion items. It is currently available on TestFlight.

---

## 📖 목차 | Table of Contents

- [Persona](#persona)  
- [Milestone](#milestone)  
- [Challenge & Solution](#challenge--solution)  
- [주요 기능](#주요-기능) | Features  
- [기술 스택](#기술-스택) | Tech Stack  
- [How To?](#how-to)  
- [Progress Status](#progress-status)  
- [Contact](#contact)  

---

## Persona

**패션과 유행에 관심이 많은 대학생 A씨**  
- SNS에서 유명한 패션 트렌드를 참고하며 다양한 아이템을 구입하려 함.  
- 대학생이기에 예산이 제한되어 할인 상품을 주로 구매.

---

## Milestone

**패션 피플들이 예산을 아끼며 현명하게 소비할 수 있도록 돕자.**  
"Let's help fashion enthusiasts save money and shop wisely."

---

## Challenge & Solution

### iOS
- **문제**: 기존의 그래프 라이브러리는 유연성이 부족하거나 성능 문제를 일으켜, 사용자가 원하는 정확하고 매끄러운 그래프를 제공하기 어려웠습니다.  
- **해결책**: CoreAnimation을 활용해 직접 가격 변동 그래프를 그리도록 구현했습니다.

### Backend
- **문제**: 보안과 관리의 유연성 때문에 익숙한 방식이던 JWT 토큰 대신 세션으로 전환해야 했습니다.  
- **해결책**: 세션 기반 인증으로 전환하여 Spring Security를 통해 유연한 사용자 인증 및 관리 방식을 구축했습니다.

---

## 주요 기능 | Features

1. **패션 아이템 검색 | Search Fashion Items**
   - 사용자는 관심 있는 패션 아이템을 검색창에 입력하여 결과를 확인할 수 있습니다.
   - Users can search for fashion items using the search bar on the home screen.

2. **즐겨찾기 기능 | Add to Favorites**
   - 관심 있는 아이템을 찜 목록에 추가하여 저장할 수 있습니다.
   - Save items of interest to the favorites list.

3. **가격 변동 그래프 | Price Trend Graph**
   - 아이템 상세 페이지에서 가격 변동 그래프를 확인할 수 있습니다.
   - View a graph of price changes on the item detail page.

4. **가격 하락 알림 | Price Drop Notifications**
   - 찜한 아이템의 가격이 하락하면 푸시 알림을 받을 수 있습니다.
   - Receive push notifications when the price of a favorite item drops.

5. **찜 목록 | Favorites List**
   - 찜한 아이템들을 한곳에서 조회하고 관리할 수 있습니다.
   - View and manage your favorite items in one place.

---

## 기술 스택 | Tech Stack

- **iOS**: Swift, SwiftUI, CoreAnimation  
- **Frontend**: React
- **Backend**: Spring Boot, JPA, Spring Security  
- **Authentication**: OAuth2, 세션 기반 인증(Session-Based Authentication)  
- **Deployment**: AWS EC2, GitHub Actions

---

## How To?

1. **애플 로그인을 통해 간단하게 로그인하세요.(iOS 앱 한정)**
   Log in easily using Apple Sign-In.(Available exclusively on iOS)
2. **홈 화면의 검색창에 관심 있는 패션 아이템을 검색하세요.**  
   Search for fashion items using the search bar on the home screen.
3. **검색 결과에서 원하는 아이템을 선택하세요.**  
   Select an item from the search results.
4. **상세 페이지에서 관심 있는 아이템을 찜 목록에 추가하고 가격 변동 그래프를 확인하세요.(iOS 앱 한정)**  
   Add items to your favorites list and view their price trend graph on the detail page.(Available exclusively on iOS)
5. **가격이 하락하면 푸시 알림이 뜹니다.(iOS 앱 한정)**  
   Receive push notifications when the price drops.(Available exclusively on iOS)
6. **찜 목록에서 저장한 상품들을 확인하세요.(iOS 앱 한정)**  
   Check your saved items in the favorites list.(Available exclusively on iOS)

---

## Contact

프로젝트 관련 문의는 아래 이메일로 연락 부탁드립니다:  
For inquiries about the project, please contact:

📧 **andrewkimswe@gmail.com**  
