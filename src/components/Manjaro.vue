<template>
    <div class="wrapper">
      <header class="padding">
        <h1>{{ $t("header.whyWeLove") }}</h1>
      </header>
      <article class="padding">
        <h2>{{ $t("header.punctuality") }}</h2>
        <div class="article-main">
          <p>{{ $t("text.TLS1") }}<sup>[1] [2]</sup></p>
          <p>{{ $t("text.TLS2") }}<sup>[3]</sup></p>
          <p>{{ $t("text.TLS3") }}<sup>[4]</sup></p>
        </div>
        <aside class="article-aside">
          <p>
            <a href="https://web.archive.org/web/20181012040231/https://manjaro.github.io/expired_SSL_certificate/">{{ $t("ref") }} #1</a><br>
            <a href="https://web.archive.org/web/20150409040851/https://manjaro.github.io/expired_SSL_certificate/">{{ $t("ref") }} #2</a><br>
            <a href="https://web.archive.org/web/20181112113901/https://manjaro.github.io/SSL-Certificate-Expired/">{{ $t("ref") }} #3</a><br>
            <a href="https://web.archive.org/web/20191107140857/https://forum.manjaro.org/t/manjaro-org-certificate/109375?u=orajnam">{{ $t("ref") }} #4</a><br>
          </p>
        </aside>
      </article>
      <article class="padding">
        <h2>{{ $t("header.honesty") }}</h2>
        <div class="article-main">
          <p>{{ $t("text.purge") }}</p>
        </div>
      </article>
      <article class="padding">
        <h2>{{ $t("header.perfectionism") }}</h2>
        <div class="article-main">
          <p>{{ $t("text.script") }}<sup>[5]</sup></p>
          <p>{{ $t("text.vulnerability") }}<sup>[6] [7]</sup></p>
        </div>
        <aside class="article-aside">
          <p>
            <a href="https://gitlab.manjaro.org/packages/core/manjaro-system/blob/master/manjaro-update-system.sh">{{ $t("ref") }} #5</a><br>
            <a href="https://www.cvedetails.com/cve/CVE-2018-15912/">{{ $t("ref") }} #6</a><br>
            <a href="https://lists.manjaro.org/pipermail/manjaro-security/2018-August/000785.html">{{ $t("ref") }} #7</a><br>
          </p>
        </aside>
      </article>
      <article class="padding">
        <h2>{{ $t("header.machiavellianism") }}</h2>
        <div class="article-main">
          <p>{{ $t("text.partialUpdates") }}<sup>[8]</sup></p>
          <p>{{ $t("text.dbLock") }}<sup>[9]</sup></p>
          <p>{{ $t("text.rmModules") }}<sup>[10]</sup></p>
          <p>{{ $t("text.pacmanGrep") }}<sup>[11]</sup></p>
        </div>
        <aside class="article-aside">
          <p>
            <a href="https://forum.manjaro.org/t/pamac-introducing-our-own-aur-support/17924">{{ $t("ref") }} #8</a><br>
            <a href="https://gitlab.manjaro.org/packages/core/manjaro-system/blob/3b806753e245b7ec7e18bb674e916e28d751a429/manjaro-update-system.sh#L48">{{ $t("ref") }} #9</a><br>
            <a href="https://forum.manjaro.org/t/usr-lib-modules-getting-deleted-on-boot/49984/11">{{ $t("ref") }} #10</a><br>
            <a href="https://gitlab.manjaro.org/packages/core/manjaro-system/blob/3b806753e245b7ec7e18bb674e916e28d751a429/manjaro-update-system.sh#L45">{{ $t("ref") }} #11</a><br>
          </p>
        </aside>
      </article>
      <article class="padding">
        <h2>{{ $t("header.tldr") }}</h2>
        <div class="article-main">
          <p>{{ $t("text.install") }}</p>
          <p>{{ $t("text.rolling") }}</p>
          <p>{{ $t("text.stable") }}</p>
        </div>
      </article>
    </div>
</template>
