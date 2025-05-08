<template>
  <div>
  <h1>Mvy_Snowのプロフィール</h1>
    <strong>test</strong>
      <p>本日<br>
        🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣<br>
            🍣🍣🍣<br>
            🍣🍣🍣🍣🍣🍣<br>
                   🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣🍣<br>
      </p>
  <!-- 自己紹介コーナー -->
   <em>これはテスト用文章ですtest</em>
   <br>
   <strong>これはテスト用文章ですtest</strong>
   <br>
   <i>そしてこれもテスト用文章ですtest</i>

  <!-- <abbr title="Cascading Style Sheets">CSS</abbr> (Cascading Style Sheets) を使うと、<br> -->

  <h2>自己紹介</h2>
      <p>
        こんにちは！こんにちは！見えていますか？
        <br>
        <strong>Mvy_Snow</strong>と申します。「スノー」とお呼びください。
        <br>
        現在、私はエンジニアとなるべく<abbr title="HyperText Markup Language">HTML</abbr>の学習をしています。
      </p>
  <h3>現在の目標</h3>
        <ul>
          <li>HTMLの習得</li>
          <li><abbr title="Cascading Style Sheets">CSS</abbr>への理解</li>
        </ul>

  <h4>スキル一覧</h4>
  <!-- テーブル作成、表の枠はborderが存在するが非推奨。CSSで作成可能 -->
        <table>
          <caption>
            技術スキル一覧(2025年時点)
          </caption>
          <thead>
            <tr>
            <th>スキル</th>
            <th>習熟度</th>
          </tr>
          </thead>
          <tbody>
          <tr>
            <td>母国語</td>
            <td>11</td>
          </tr>
          <tr>
            <td>重機械操作</td>
            <td>50</td>
          </tr>
          </tbody>
        </table>
  <!-- 順序無しリストここから -->
    <ul>
      <li>項目1</li>
        <ul>
            <li>sub</li>
            <li>sub2</li>
        </ul>
      <li>項目2</li>
      <li>項目3</li>
  </ul>
<!-- 順序無しリストここまで -->
<!-- ------------------------------------------------------- -->
<!-- 順序アリリスト -->
<ol>
  <li>項目1</li>
    <ol>
      <li>mimi</li>
    </ol>
  <li>項目2</li>
    <ul>
        <li>noko</li>
      </ul>
  <li>項目3</li>
</ol>
<!-- 順序アリリストここまで -->
<dl>
  <dt>スシロー</dt>
  <dd>A large feline inhabiting Bodmin Moor.</dd>

  <dt>Morgawr</dt>
  <dd>A sea serpent.</dd>

  <dt>Owlman</dt>
  <dd>A giant owl-like creature.</dd>
</dl>

  </div>
</template>