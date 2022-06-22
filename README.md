# puppeteer-crawler-sample
Puppeteerで開発したクローラ

```sh
puppeteer-crawler-sample
    |
    |---crawler
    |    |---phpCrawler.php -> PHP-curlクローラ
    |    |---puppCrawler.js -> Puppeteerクローラ
    |    |...
    |
    |---frontend -> ReactJSプロジェクト
    |    |---public
    |    |    |---index.html -> HTMLファイル
    |    |    |---...
    |    |
    |    |---src
    |    |    |---App.tsx -> 記事リストを含むコンポーネント
    |    |    |---...
    |    |
    |    |...  
    |      
    |---README.md
```

# How to run

### Frontend
```sh
cd frontend
npm ci
npm start
```

### Crawler
```sh
cd crawler
npm ci

# Puppeteer crawler
npm run pupp-crawler

# PHP-curl crawler
npm run php-crawler
```