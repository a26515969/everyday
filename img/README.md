# 每日改變的照片

照片放這裡，然後在 index.html 的 ENTRIES 用 img 欄位指過來：

    { date: '2026-08-05', title: '洗好碗', body: '...', tags: [],
      img: 'img/0805-碗.jpg' },

多張就用陣列，還可以加一行說明：

    { ..., img: ['img/a.jpg', 'img/b.jpg'], caption: '陽台整理前後' },

檔名建議用 `日期-關鍵字.jpg`，不要有空白。
手機拍的原檔通常 3～5MB，建議先縮到寬度 1600px 以內再放進來。
