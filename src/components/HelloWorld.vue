<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})
</script>

<template>
  <h1>{{ msg }}</h1>

  <p class="explain">東京工業大学デジタル創作同好会traP所属 B1<br/>普段はgolangを使用してtraP内の部内サービスJomon version2の開発のバックエンドを担当。<br/>(フロントエンドも担当予定)<br/>このwebサイトはvue + viteを使用しています。</p>
  <a href="https://github.com/shota-aa">自分のgithub</a>
  <h1>関わったプロジェクト</h1>

  <h3 class="one">Ⅰ. traP 21-hackathon-winter: 場所法支援アプリPalamoの作成</h3>
  <a href="https://hackathon-21-winter-18.github.io/frontend/">Palamo</a>
  <br/>
  <p class="inline">github:&ensp;</p>
  <a href="https://github.com/hackathon-21-winter-18">https://github.com/hackathon-21-winter-18</a>
  
  <p class="one">アプリ説明：</p>
  <p class="explain">場所法(Method of Loci)とは自分の知っている場所に覚えたいものを当てはめることで効率よく暗記ができる記憶術で、単純暗記を最も効率良く行うことができる方法の一つとして認められています。その場所の画像と単語の組み合わせを保存し、いつでも見返せるようにしました。また使用画像と単語を埋め込む地点の情報(Template)や単語を埋め込んだ後の記憶の宮殿(Palace)は共有可能で、公開されたものは自分の物として保存することができます。これを可能とするAPIはハッカソン中に実装されていて、他にもissueに書き込まれた機能を実装予定です。基本機能はフロントエンドが現在開発途中ですが、いずれ上記のurlから基本機能を全て使用できるようになります。</p>
  <p class="one">自分が担当したこと：</p>
  <p class="explain">バックエンド(golang)が自分を含めて2人、フロントエンド&デザインが他3人という役割分担で取り組みました。バックエンドのメンバーのもう1人はweb制作未経験だったため、私は仕事の割り振り、API、DB設計、API実装、開発環境構築、バックエンドのデプロイなど幅広く作業を行いました。</p>
  
  <h3 class="two">Ⅱ. traPの部内サービス Jomon version2 の開発</h3>
  <p class="inline">github:&ensp;</p>
  <a href="https://github.com/traPtitech/Jomon">https://github.com/traPtitech/Jomon</a>

  <p class="two">アプリ説明：</p>
  <p class="explain">traPの部内サービスである、部費管理webサービスJomonのversion 2のバックエンドでの開発の一部に携わっています。goのORMであるentを用いた開発をしていて、テスト駆動開発をしています。</p>

  <br/>
  <p class="two">自分が開発した部分のPR：</p>
  <p class="explain">部内SNSサービスtraQのUserをGroupのメンバーに追加、修正、削除とメンバーを取得するAPIを作成しました。</p>
  <a href="https://github.com/traPtitech/Jomon/pull/443">https://github.com/traPtitech/Jomon/pull/443</a>
  <br/>
  <p class="explain">部費の申請書(Request)が発行、修正された時に部内SNSサービスtraQへ通知をする機能を開発しています。また、Requestを取得、追加、修正、削除をするAPIを開発しています。</p>
  <a href="https://github.com/traPtitech/Jomon/pull/485">https://github.com/traPtitech/Jomon/pull/485</a>
  
  <h3 class="three">Ⅲ. その他制作物</h3>
  <p class="inline">vueとgolangを用いてDB操作の練習をしました。</p>
  <a href="https://github.com/shota-aa/naro-todolist">vue</a>
  <a>&ensp;</a>
  <a href="https://github.com/shota-aa/naro-go-database">golang</a>


</template>

<style scoped>

.inline {
  display: inline-block;
}
.explain {
  margin-right: 20%;
  margin-left: 20%;
}
h3 {
  margin-top: 50px;
}
.one {
  color: blue;
}
.two {
  color: red;
}
.three {
  color: green;
}

</style>
