# Coding apple Next.js 강의 1강~6강

https://www.youtube.com/watch?v=PCkiz2GUFg8


## Coding apple Next.js 교육과정

https://codingapple.com/course/next-js/


# 설치

```
npx create-next-app@13.2.4
```

Need to install the following packages:
create-next-app@13.2.4
Ok to proceed? (y)

√ What is your project named? ... <span style="color:red">fresh</span>  
√ Would you like to use TypeScript with this project? ... <span style="color:red">No</span> / Yes  
√ Would you like to use ESLint with this project? ... <span style="color:red">No</span> / Yes  
√ Would you like to use `src/` directory with this project? ... <span style="color:red">No</span> / Yes  
√ Would you like to use experimental `app/` directory with this project? ... <span style="color:red">No</span> / Yes  
√ What import alias would you like configured? ... @/*  
Creating a new Next.js app in [your_folder]\fresh.

Using npm.

Initializing project with template: app


Installing dependencies:
- react
- react-dom
- next


added 57 packages, and audited 58 packages in 14s

26 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Initialized a git repository.

Success! Created fresh at [your_folder]\fresh


## 버전 맞추기 (안해도 동작함)

package.json

```
  "dependencies": {  
    "next": "^13.2.4",  
    "react": "^18.2.0",  
    "react-dom": "^18.2.0"  
  }
```

## 패키지 설치
npm install

## 실행
npm run dev

## 초기 세팅

page.js

```
export default function Home() {
  return (
   <div>
    
   </div>
  )
}
```

global.css, page.modules.css 내용 지움
