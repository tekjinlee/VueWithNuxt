# VueWithNuxt

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

### `assets`

css, image, font와 같은 리소스들을 포함한다.

### `components`

애플리케이션에서 사용될 컴포넌트들을 포함하며 해당 경로에 위치된 컴포넌트들은 Nuxt.js의 비동기 데이터 함수인 asyncData또는 fetch를 사용할 수 없다.

### `layouts`

애플리케이션 전체에 대한 레이아웃을 포함한다. 기본으로 default.vue가 생성되어 있을 것이고 상황에 맞게 layout을 생성할 수 있다.

해당 디렉토리는 이름을 변경할 수 없다.


### `pages`

실제 애플리케이션의 페이지 구성을 포함하며 해당 디렉토리의 구조에 따라 router가 자동으로 생성된다.

해당 디렉토리는 이름을 변경할 수 없다.

### `plugins`

애플리케이션에 바인딩 될 외부 혹은 내부 plugins를 포함한다.plugins는 애플리케이션이 인스턴스 화 되기 전에 실행하며 전역적으로 구성 요소를 등록하고 함수 또는 상수를 삽입할 수 있다.

### `static`

해당 디렉토리는 정적인 파일들을 포함한다. 구성에 따라서 html, Javascript 파일도 포함 시킬 수 있다.

해당 디렉토리는 이름을 변경할 수 없다.

### `store`

애플리케이션에서 사용될 vuex store 파일들을 포함한다. 기본적으로 비활성화 상태이고 store 디렉토리에 index.js 파일을 작성하면 store가 활성화된다.
구성에 따라서 모듈 형태의 store를 형성할 수 있다.

해당 디렉토리는 이름을 변경할 수 없다.


