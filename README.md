# Next.js와 MongoDB를 활용한 CRUD 만들기

[Step-by-Step] 기초 가이드 북

이 가이드는 Next.js와 MongoDB를 활용해 CRUD 애플리케이션을 처음부터 완성하는 방법을 다룹니다. 기초 개념 설명부터 코드 작성 및 구현 과정까지 단계별로 따라 할 수 있어, 초보자도 쉽게 접근할 수 있습니다. 웹 개발에 관심 있는 분들이 데이터베이스와 프레임워크의 통합 방법을 이해하고 실습할 수 있도록 돕는 실전형 입문서입니다.

## 기술 정보

- Node.js
- Next.js
- Tailwindcss

### 시작하기

```bash
npx create-next-app@latest next-curd
```

```bash
✔ Would you like to use TypeScript? … No
✔ Would you like to use ESLint? … Yes
✔ Would you like to use Tailwind CSS? … Yes
✔ Would you like your code inside a `src/` directory? … No
✔ Would you like to use App Router? (recommended) … Yes
✔ Would you like to use Turbopack for next dev? … Yes
✔ Would you like to customize the import alias (@/* by default)? … No
```

```
npm run dev
```

## 라이브러리

- Mongoose : Node.js와 MongoDB를 연결하기 위한 라이브러리
- React Icons : 다양한 아이콘을 쉽게 사용할 수 있는 라이브러리

```bash
npm i mongoose
npm i react-icons
```
