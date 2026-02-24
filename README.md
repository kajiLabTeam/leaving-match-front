## production
leaving-match

## development
main ブランチの vercel
https://leaving-match.vercel.app/

<!-- これは [Next.js](https://nextjs.org) を用いたプロジェクトです. 
[`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app) パッケージを用いて作成されています. -->

## 環境構築

1. leaving-match-backend の環境構築を行う

2. leaving-match-front をクローンする

3. .env.local ファイルをディレクトリ直下に配置する

4. 
```
npm run dev
```

5. http://localhost:3000 で開く
app/page.tsx が表示されます

<!-- First, run the development server: -->

<!-- ```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
``` -->
<!-- 
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel. -->

<!-- 
## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!
-->

<!-- ## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details. -->


## ファイル構成
leaving-match-front<br>
 　├─ .github/workflows/ # 定期実行するGitHub Actionsの設定<br>
　 ├─ public<br>
　 │      ├─ image.png # 背景画像ファイル<br>
　 │      └─ sounds # 通知音声のファイル<br>
　 ├─ src/<br>
　 │      ├─ app/ # ルーティングおよび画面遷移制御<br>
 　│      ├─ components/ # 実際に表示する画面を返すファイル<br>
 　│      ├─ jobs/ # 定期実行されるファイル<br>
　 │      ├─ lib/ # 外部（本プロジェクトのバックエンド含む）APIとの通信<br>
　 │      ├─ pages/api/ # lib/ のAPI呼び出し処理をラップするAPIハンドラー<br>
　 │      ├─ styles/ # CSS ファイル<br>
 　│      ├─ types/ # API から取得するデータや内部で扱う際の型<br>
　 │      └─ utils/ # ロジックファイル<br>
　 ├─ .env.local (引き継ぎ)<br>
　 └─ README.md<br>

- 各ファイルの詳細はesa (https://kjlb.esa.io/posts/9425) を確認

## その他

audio in this system Created By ondoku3.com
音声合成機能には「音読さん」を利用しています．
