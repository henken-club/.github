<h1 align="center">henken.club</h1>

<p align="center">
    <a href="https://discord.gg/v5AXyfuGeV">
        <img src="https://img.shields.io/discord/882910287638986762?color=7489d5&logo=discord&logoColor=ffffff" />
    </a>
</p>

## 概要

**こいつこういう本読んでそうだな〜**、**こいつこのアニメ好きそうだな〜**、そういった偏見を気軽に送り合うために開発が行われています。個人で…

### コンセプト

- https://hito-horobe.net/articles/henken-hondana

## リポジトリ

- フロントエンド
  - [web-frontend]
- バックエンド
  - [bff]
  - [main-backend]
  - [content-backend]
  - [search-backend]

<!-- lang -->

[typescript]: https://www.typescriptlang.org/
[typescript-img]: https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logoColor=white&logo=typescript

<!-- protocols -->

[graphql]: https://www.graphql.com/
[graphql-img]: https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logoColor=white&logo=graphql
[grpc]: https://www.meilisearch.com/
[grpc-img]: https://img.shields.io/badge/-gRPC-54bec6?style=flat-square

<!-- frontend -->

[react]: https://reactjs.org/
[react-img]: https://img.shields.io/badge/-React-61DAFB?style=flat-square&logoColor=white&logo=React
[nextjs]: https://nextjs.org/
[nextjs-img]: https://img.shields.io/badge/-Next.js-000?style=flat-square&logoColor=white&logo=Next.js
[urql]: https://formidable.com/open-source/urql/
[urql-img]: https://img.shields.io/badge/-urql-8196ff?style=flat-square
[storybook]: https://storybook.js.org/
[storybook-img]: https://img.shields.io/badge/-Storybook-FF4785?style=flat-square&logoColor=white&logo=Storybook
[tailwindcss]: https://storybook.js.org/
[tailwindcss-img]: https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat-square&logoColor=white&logo=TailwindCSS
[styled-components]: https://storybook.js.org/
[styled-components-img]: https://img.shields.io/badge/-styled--components-d97bb5?style=flat-square
[jest]: https://jestjs.io/
[jest-img]: https://img.shields.io/badge/-Jest-C21325?style=flat-square&logoColor=white&logo=Jest
[msw]: https://mswjs.io/
[msw-img]: https://img.shields.io/badge/-MSW-ff6a33?style=flat-square

<!-- backend -->

[nestjs]: https://nestjs.com
[nestjs-img]: https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logoColor=white&logo=nestjs
[apollo]: https://www.apollographql.com/
[apollo-img]: https://img.shields.io/badge/-Apollo-311C87?style=flat-square&logoColor=white&logo=apollo-graphql
[prisma]: https://www.prisma.io/
[prisma-img]: https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logoColor=white&logo=prisma

<!-- middleware -->

[meilisearch]: https://www.meilisearch.com/
[meilisearch-img]: https://img.shields.io/badge/-Meilisearch-F23C79?style=flat-square
[postgresql]: https://www.postgresql.org/
[postgresql-img]: https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logoColor=white&logo=postgresql

### [web-frontend]

[web-frontend]: https://github.com/henken-club/main-backend

[![typescript-img]][typescript]
[![react-img]][react]
[![nextjs-img]][nextjs]

[![urql-img]][urql]
[![graphql-img]][graphql]
[![tailwindcss-img]][tailwindcss]
[![styled-components-img]][styled-components]
[![jest-img]][jest]
[![msw-img]][msw]
[![storybook-img]][storybook]

Web フロントエンド．

### [bff]

[bff]: https://github.com/henken-club/main-backend

[![typescript-img]][typescript]
[![nestjs-img]][nestjs]

[![apollo-img]][apollo]
[![graphql-img]][graphql]

フロントエンド側と下記のバックエンド側の間に入る Apollo Gateway サーバ．認証などの処理もここで行う．

### [main-backend]

[main-backend]: https://github.com/henken-club/main-backend

[![typescript-img]][typescript]
[![nestjs-img]][nestjs]

[![apollo-img]][apollo]
[![graphql-img]][graphql]
[![grpc-img]][grpc]
[![prisma-img]][prisma]
[![postgresql-img]][postgresql]

ユーザ管理，偏見や偏見への回答に関する処理の為などのメインロジックの Apollo Federation GraphQL サーバ．

### [content-backend]

[content-backend]: https://github.com/henken-club/content-backend

[![typescript-img]][typescript]
[![nestjs-img]][nestjs]

[![apollo-img]][apollo]
[![graphql-img]][graphql]
[![grpc-img]][grpc]
[![prisma-img]][prisma]
[![postgresql-img]][postgresql]

コンテンツ及びコンテンツ同士の関係性管理の為の Apollo Federation GraphQL サーバ．

### [search-backend]

[search-backend]: https://github.com/henken-club/search-backend

[![typescript-img]][typescript]
[![nestjs-img]][nestjs]

[![apollo-img]][apollo]
[![graphql-img]][graphql]
[![grpc-img]][grpc]
[![meilisearch-img]][meilisearch]

コンテンツ及びユーザーの検索の為の Apollo Federation GraphQL サーバ．

## 参加

現在気長に一人で開発していますが，興味が合ったら[discord](https://discord.gg/v5AXyfuGeV)に入ったり，[@SnO2WMaN](https://twitter.com/SnO2WMaN)に連絡して下さい．

## ライセンス

TODO:
