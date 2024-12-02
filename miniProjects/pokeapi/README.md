# 📝 기본 요구 사항

## 1. **리액트 프로젝트 설정**

1. **Vite를 사용해 리액트 프로젝트 생성**:
   - Vite를 사용하여 새로운 리액트 프로젝트를 설정합니다.

## 2. **Redux Toolkit 설정**

1. **RTK 폴더 생성**:
   - `RTK` 폴더를 생성하고, 포켓몬 정보를 비동기적으로 가져오는 로직을 구현합니다.
2. **비동기 데이터 로딩**:
   - `fetchAPI`를 사용하여 포켓몬의 이름, 이미지(앞면/뒷면), 설명을 받아옵니다.
   - `Array.from`을 사용하여 1부터 151까지의 포켓몬 ID 배열을 생성하고, `Promise.all`을 사용하여 모든 포켓몬 정보를 비동기적으로 로드합니다.
3. **슬라이스 파일 생성**:
   - 포켓몬 데이터를 관리할 Redux 슬라이스 파일을 생성합니다.
4. **스토어 파일 생성**:
   - Redux 스토어를 설정할 파일을 생성하고, 슬라이스를 스토어에 통합합니다.

## 3. **패키지 설치 및 설정**

1. **Tailwind CSS 설치**:
   - Tailwind CSS를 프로젝트에 설치하고 설정합니다.
2. **React Router DOM 설치**:
   - `react-router-dom`을 설치하여 페이지 라우팅 기능을 추가합니다.

## 4. **페이지 및 라우팅 설정**

1. **페이지 폴더 생성**:
   - `pages` 폴더를 생성하고, 다음 페이지 컴포넌트를 생성합니다:
     - `Main`: 포켓몬 정보 카드를 표시합니다.
     - `Detail`: 선택된 포켓몬의 상세 정보를 표시합니다.
     - `Search`: 파일을 생성합니다.
     - `Favorites`: 파일을 생성합니다.
2. **라우팅 설정**:
   - `routes`와 `Route` 컴포넌트를 사용하여 애플리케이션의 페이지 라우팅을 설정합니다.

## 5. **UI 구성**

1. **메인 페이지**:
   - 포켓몬 정보를 카드 형태로 표시합니다.
   - 포켓몬 정보를 받아오고, `map`을 사용하여 각 포켓몬의 사진과 이름을 렌더링합니다.
   - 포켓몬 정보를 섹션으로 묶어서 반환합니다.
2. **디테일 페이지**:
   - 선택된 포켓몬의 ID를 사용하여 해당 포켓몬의 상세 정보를 가져오고 표시합니다.