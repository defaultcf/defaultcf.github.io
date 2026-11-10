---
layout: default
---

<header>
  <div class="blur"></div>
  <div class="header-inner">
    <h1>default.cf</h1>
  </div>
</header>

<main>
  <section>
    <h2>こんにちは</h2>
    <p>defaultcf です。ウェブの技術と Virtual YouTuber が好きです。</p>
    <p>最近は VR にハマっています。</p>
  </section>

  <section>
    <h2>経歴</h2>
    <ul>
      <li>2015年3月、北海道札幌月寒高校 卒業</li>
      <li>2015年4月～2021年3月、公立はこだて未来大学</li>
      <li>2021年4月～2022年9月、株式会社GIG</li>
      <li>2022年10月～、サイボウズ株式会社</li>
    </ul>
  </section>

  <section>
    <h2>好きなもの</h2>
    <ul>
      <li>ウェブの技術
        <ul>
          <li>フロントエンドからインフラまで</li>
        </ul>
      </li>
      <li>Virtual YouTuber
        <ul>
          <li>角巻わため</li>
          <li>鈴原るる</li>
          <li>でびでび・でびる</li>
          <li>シスター・クレア</li>
        </ul>
      </li>
      <li>VR
        <ul>
          <li>VRChat</li>
        </ul>
      </li>
    </ul>
  </section>

  <section>
    <h2>ブログ</h2>
    <p>
      <a href="https://default.cf/blog/">default.cf/blog</a>
    </p>
    <ul>
      {% assign entry = site.data.feed.feed.entry | slice: 0, 5 %}
      {% for feed in entry %}
        <li>
          {{ feed.updated | date: "%Y-%m-%d" }}:
          <a href="{{ feed.id }}">{{ feed.title }}</a>
        </li>
      {% endfor %}
    </ul>
  </section>

  <section>
    <h2>各種リンク</h2>
    <div class="links">
      <div>
        <a href="https://github.com/defaultcf" target="_blank" rel="noopener">
          <span class="icon">🐙</span><p>GitHub</p>
        </a>
      </div>
      <div>
        <a href="https://twitter.com/defaultcf" target="_blank" rel="noopener">
          <span class="icon">🐦</span><p>Twitter</p>
        </a>
      </div>
      <div>
        <a href="https://keybase.io/defaultcf" target="_blank" rel="noopener">
          <span class="icon">🔑</span><p>Keybase</p>
        </a>
      </div>
      <div>
        <a href="https://scrapbox.io/defaultcf" target="_blank" rel="noopener">
          <span class="icon">📝</span><p>Scrapbox</p>
        </a>
      </div>
      <div>
        <a href="https://www.wantedly.com/id/defaultcf" target="_blank" rel="noopener">
          <span class="icon">💼</span><p>Wantedly</p>
        </a>
      </div>
    </div>
  </section>
</main>
