<template>
  <div class="mt-4">
    <h2>基本情報</h2>
    <ul>
      <li>名前: 今川裕士（いまがわゆうじ）</li>
      <li>生年月日: 1991/09/23 おとめ座(29°)</li>
      <li>住所: 東京都品川区</li>
      <li>出身: 山形県山形市</li>
      <li>職種: Webアプリケーションエンジニア</li>
    </ul>
    <h2>SNS等</h2>
    <ul>
      <li>
        <b-icon icon="twitter" aria-hidden="true" />
        <a href="https://twitter.com/ug23_">@ug23_</a>
      </li>
      <li>
        <b-icon icon="facebook" aria-hidden="true" />
        <a href="https://www.facebook.com/ugx23/">@ugx23</a>
      </li>
      <li>
        <b-icon icon="instagram" aria-hidden="true" />
        <a href="https://www.instagram.com/ug_23/">@ug_23</a>
      </li>
      <li>
        <b-icon icon="github" aria-hidden="true" />
        <a href="https://github.com/ug23">@ug23</a>
      </li>
      <li>
        <a href="https://blog.ug23.dev">はてなブログ</a>
      </li>
    </ul>
    <h2>資格</h2>
    <ul>
      <li>応用情報技術者</li>
      <li>JSTQB Foundation Level</li>
      <li>ソフトウェア品質技術者 中級</li>
      <li>AWS認定 ソリューションアーキテクト - アソシエイト(2022年7月末迄)</li>
    </ul>
    <h2>使用技術</h2>
    <p>※印は業務経験がないもの</p>
    <h3>サーバサイド</h3>
    <ul>
      <li>PHP</li>
      <li>Ruby</li>
      <li>Scala</li>
      <li>Python ※</li>
    </ul>
    <h3>フロントエンド</h3>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>jQuery</li>
      <li>Vue.js</li>
      <li>Nuxt.js</li>
      <li>TypeScript</li>
    </ul>
    <h3>インフラ</h3>
    <ul>
      <li>AWS: EC2 ECS(Fargate) RDS S3 ElastiCache(Redis) Route53</li>
      <li>Ansible</li>
      <li>Heroku ※</li>
    </ul>
    <h3>その他</h3>
    <ul>
      <li>Embulk</li>
      <li>Salesforce Marketing Cloud連携周り</li>
      <li>HubSpot連携周り</li>
    </ul>
    <h2>ご連絡</h2>
    <p>TwitterのDMまたはMessenger.comからどうぞ</p>
  </div>
</template>

<script>
export default {
  name: 'PortfolioDescription',
}
</script>

<style lang="scss">
.navbar {
  background-color: $color-green;
  color: $color-white;
  font-size: 32px;
  padding: 0 32px;
}

.img-wrapper {
  display: float;
}

.photo {
  width: 320px;
}
</style>
