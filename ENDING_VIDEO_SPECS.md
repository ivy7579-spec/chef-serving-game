# 破關動畫影片規格

每支影片放在 `assets` 資料夾，檔名需與下方一致。遊戲會依玩家選擇的今日料理自動播放對應影片；如果檔案尚未放入，會先播放目前通用影片。

## 統一規格

- 格式：MP4
- 比例：16:9 橫式
- 尺寸：1280 x 720
- 長度：5-6 秒
- 風格：手繪水彩、溫暖餐桌、完成料理特寫、無字幕、無 logo
- 節奏：
  - 0-1 秒：完成料理特寫，熱氣、光澤、桌面氛圍
  - 1-3.5 秒：筷子、湯匙或叉子夾起一口料理
  - 3.5-5 秒：手部享用，表現好吃與滿足
  - 5-6 秒：回到完成料理與溫暖桌面

## 對應檔名

| 菜色 | 影片檔名 | 畫面重點 |
| --- | --- | --- |
| 咖哩飯 | `ending-curry-rice.mp4` | 湯匙挖起白飯與金黃咖哩，醬汁濃稠發亮 |
| 蔬菜燉飯 | `ending-veggie-risotto.mp4` | 湯匙舀起米粒、蘑菇與櫛瓜，起司微微牽絲 |
| 番茄奶香義麵 | `ending-tomato-cream-pasta.mp4` | 叉子捲起番茄奶香義麵，麵條帶光澤 |
| 黑胡椒牛肉飯 | `ending-black-pepper-beef-rice.mp4` | 筷子夾起牛肉與白飯，黑胡椒醬汁閃亮 |
| 三杯塔香雞丁 | `ending-three-cup-chicken.mp4` | 筷子夾起雞丁，九層塔飄出香氣 |
| 鮮蝦蛋炒飯 | `ending-shrimp-fried-rice.mp4` | 湯匙舀起炒飯與鮮蝦，米飯粒粒分明 |
| 香煎蔬菜豆腐 | `ending-pan-fried-veggie-tofu.mp4` | 筷子夾起金黃豆腐，蔬菜色彩明亮 |
| 南瓜濃湯 | `ending-pumpkin-soup.mp4` | 湯匙舀起濃湯，奶油線條與熱氣柔和 |
| 海鮮粉絲豆腐煲 | `ending-seafood-vermicelli-tofu-pot.mp4` | 筷子夾起粉絲與海鮮，煲鍋熱氣上升 |
| 薑絲大腸 | `ending-ginger-intestine.mp4` | 筷子夾起大腸與薑絲，酸香熱炒感 |
| 雞肉奶油燉白菜 | `ending-creamy-chicken-napa.mp4` | 湯匙舀起雞肉白菜與奶油湯汁，口感溫柔 |
| 紅酒燉牛肉 | `ending-red-wine-beef.mp4` | 叉子叉起燉牛肉，紅酒醬汁深色光澤 |

## 通用生成提示詞

```text
1280x720 horizontal 16:9, 6 seconds, warm hand-drawn watercolor food animation.
A completed [dish name] on a cozy dining table, steam rising gently, glossy sauce and appetizing details.
0-1 seconds: close-up of the finished dish with warm table atmosphere.
1-3.5 seconds: a hand with chopsticks, spoon, or fork picks up a generous bite.
3.5-5 seconds: the hand enjoys the bite, showing satisfaction and deliciousness.
5-6 seconds: return to the finished dish on the warm dining table.
No text, no logo, no subtitles, elegant restaurant lighting, joyful and satisfying mood.
```
