# 麥塊 Python — ChatGPT 圖片生成 Prompt 清單

> **目標檔案**：`/Users/posh.lin/Documents/minecraft-python-prototype/index.html`
> **風格主軸**：兒童樂園風 + 致敬麥塊風（voxel / blocky 原創、避免商標）
> **配色**：草地綠 #4FAF3D / 天空藍 #4FB7E8 / 橘蘋橘 #FFA300 / 陽光黃 #FFD93D
> **總張數**：6 張核心圖（後續可擴）

---

## ⚠️ 重要：避版權三大原則

1. **不要寫**：「Minecraft」「Steve」「Alex」「Creeper」「Mojang」 ← 這些是商標
2. **改用**：「voxel」「blocky」「cubic」「pixelated」「sandbox-world」描述
3. **角色**：原創的「方塊風小孩」(blocky character) 而非麥塊官方角色

---

## 共用 STYLE BASELINE（所有 prompt 套用）

> Children-friendly voxel art style, bright cheerful palette, blocky cubic 3D characters and environments, soft cel-shading, clean readable composition. Inspired by sandbox-block-building games (NOT Minecraft trademarked content). Pastel green grass, bright sky blue, sunshine yellow accents, warm orange highlights. High quality digital illustration for educational landing page.

## 共用 NEGATIVE PROMPT

> Avoid: any text overlays, logos, brand names, Minecraft trademarks, Steve, Alex, Creeper, Enderman, dark/scary themes, photorealistic faces, violent imagery, low quality, blurry.

---

## A. PROLOGUE 主視覺（hero-trio）

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/hero-trio.png` |
| **位置** | PROLOGUE 首屏右側 |
| **比例** | **1024x1280（4:5 portrait）** |

### Prompt
```
Bright cheerful voxel-style illustration of three blocky cubic teenage characters (around 11-14 years old, two boys and one girl, all with simple blocky pixel-art appearance, friendly smiles) sitting together at a glowing computer setup. The center boy has dark hair and an orange t-shirt typing on the keyboard, the right girl has a ponytail and a teal hoodie pointing excitedly at the screen, the left boy wears a green cap and a yellow vest holding a coding manual.

Behind them: a colorful voxel sandbox world visible through a window — green grass blocks, blue sky with cubic clouds, a small wooden house in the distance, friendly cube-shaped animals roaming.

The computer screen shows pixelated Python code with rainbow-colored syntax (NO readable text, just colorful blocks suggesting code).

Style: cheerful 3D voxel art, bright pastel palette (grass green, sky blue, sunshine yellow, warm orange), clean cel-shading, optimized for a children's educational landing page. Vertical 4:5 composition. Characters fill 70% of frame. Warm friendly lighting.

Avoid: any text overlays, logos, Minecraft trademarks, Steve/Alex/Creeper, dark themes, photorealistic faces, scary imagery.
```

---

## B. PORTAL 橋接視覺（portal-bridge）

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/portal-bridge.png` |
| **位置** | 02 章右側 |
| **比例** | **1280x960（4:3）** |

### Prompt
```
Bright voxel-art illustration of a small blocky cubic boy character standing at the edge of a stone-block bridge, looking confidently across to a vibrant sandbox-block world on the other side. The bridge connects two areas:

LEFT (where he stands): A blank empty grey area, suggesting "stuck / boring".

RIGHT (where he's heading): A colorful sandbox-block world with green grass blocks, a friendly cubic robot helper (the "Agent") standing beside a half-built wooden structure, glowing Python code symbols (pi, brackets, gear icons) floating in the air, and a small voxel pet dog wagging its blocky tail.

In the middle of the bridge: a glowing portal frame made of orange-yellow cubic blocks, like a doorway from one world to another.

Composition: horizontal 4:3 landscape. Bright cheerful palette. Bridge in foreground, world in background. Character size: 25% of frame height.

Style: voxel art, soft cel-shading, optimistic mood, suitable for 5-9 year-old educational marketing.

Avoid: text, logos, Minecraft trademarks, dark themes, scary characters.
```

---

## C. GAMEPLAY 1：Agent 自動挖礦（gameplay-agent-mine）

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/gameplay-agent-mine.png` |
| **位置** | 03 章卡片 1 上方 |
| **比例** | **1280x720（16:9）** |

### Prompt
```
Voxel art scene showing a friendly cubic robot helper character (the "Agent" — a cute blocky robot with one bright glowing orange eye and friendly antenna) inside a deep mining tunnel. The Agent holds a glowing pickaxe and is in the middle of breaking through dark stone blocks. Behind it: a long straight tunnel extending into the distance with glowing diamonds, gold, and iron ore blocks visible in the walls. Underground torches give warm lighting. A small pile of mined resources sits behind the Agent.

The scene feels exciting and game-like, NOT scary. Bright contained lighting.

Style: 3D voxel art, cheerful kid-friendly, blocky cubic everything (rocks, ores, robot, tools). Pastel palette with glowing accents.

Horizontal 16:9 composition. Agent positioned in lower-center third. Tunnel perspective showing depth.

Avoid: text, code overlays, scary monsters, dark themes, Minecraft trademarks, Steve/Creeper.
```

---

## D. GAMEPLAY 2：Agent 自動建造（gameplay-agent-build）

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/gameplay-agent-build.png` |
| **位置** | 03 章卡片 2 上方 |
| **比例** | **1280x720（16:9）** |

### Prompt
```
Voxel art scene of a friendly cubic robot helper Agent placing colorful wooden blocks to build a small castle wall in a sunny grass field. The Agent has a glowing orange eye and small antenna, holding a glowing yellow construction wand. Half the castle is built (10 blocks high, partial wall), the other half showing where the Agent is currently placing blocks — with floating ghost-block previews showing the next moves.

Around the scene: bright green voxel grass, blue cubic sky, fluffy white square clouds, a few colorful flowers, a small voxel sheep and cow in the background.

Style: cheerful kid-friendly voxel art, bright daylight, optimistic mood. The Agent is the clear focal point, working diligently.

Horizontal 16:9 composition. Bright sunny atmosphere.

Avoid: text, code, scary themes, photorealistic, Minecraft trademarks.
```

---

## E. GAMEPLAY 3：修復世界（gameplay-repair）

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/gameplay-repair.png` |
| **位置** | 03 章卡片 3 上方 |
| **比例** | **1280x720（16:9）** |

### Prompt
```
Voxel art scene showing a friendly cubic Agent robot in front of a partly-damaged voxel house. There's a big crater / hole in the wall (from a hypothetical explosion, but shown gently — just missing blocks, NOT scary fire or destruction). The Agent is holding a glowing repair tool / wand, and golden cube blocks are floating from its hand toward the gap, magically filling in the damaged area.

The house: small cottage style, wooden voxel construction, with intact roof, garden in front. The repair scene shows progress — half the hole is already filled with golden glowing blocks.

Style: cheerful kid-friendly, NOT post-apocalyptic. Like a magical repair, not actual damage. Bright daylight, hopeful atmosphere.

Horizontal 16:9 composition. House in left half, Agent and golden blocks in right half.

Avoid: text, fire, smoke, scary themes, dark colors, Minecraft trademarks.
```

---

## F. GAMEPLAY 4：自製寵物（gameplay-pet）

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/gameplay-pet.png` |
| **位置** | 03 章卡片 4 上方 |
| **比例** | **1280x720（16:9）** |

### Prompt
```
Adorable voxel art scene of a small blocky cubic boy character walking through a green grass field, followed by a cute cubic puppy / dog made of brown and white blocks. The puppy is happily wagging its blocky tail, looking up at its owner with big black square eyes.

Around the boy's head: small glowing code symbols (Python brackets, heart icons, "follow" speech bubble — but NO actual readable text, just abstract icons) floating, suggesting the boy programmed the puppy.

Background: voxel grass field, blue sky, distant mountains made of cubic stone, a few floating cube clouds.

Style: warm, heartfelt, kid-friendly voxel art. The bond between boy and pet is the emotional focus. Bright cheerful palette.

Horizontal 16:9 composition. Boy and pet in foreground center.

Avoid: text overlays, scary themes, dark colors, photorealistic, Minecraft trademarks.
```

---

## G. (選配) OG 社群分享圖

| 項目 | 內容 |
|---|---|
| **檔名** | `assets/og-minecraft-python.png` |
| **比例** | **1200x630（1.91:1）** |

### Prompt
```
Wide horizontal voxel-style social media banner for a children's coding course. LEFT 40%: Three blocky cubic teen characters (2 boys, 1 girl) standing together with happy smiles, holding glowing tablets/laptops showing colorful Python symbols. RIGHT 60%: Bold large Chinese title "麥塊 Python" in vibrant orange #FFA300 with golden glow and the English subtitle "MINECRAFT × PYTHON · 5-9 年級線上互動課" below.

Background: bright voxel sandbox world with green grass blocks, blue sky, soft sunny atmosphere, scattered orange and yellow particles like glowing pixels.

Style: cheerful, kid-friendly, bright voxel illustration with crisp readable poster typography. Designed for FB / LINE social preview cards.

Aspect 1.91:1 (1200x630).

Avoid: scary themes, Minecraft trademarks, illegible text, dark colors.
```

---

## 跑圖順序建議（依優先級）

| 優先級 | 編號 | 理由 |
|---|---|---|
| **P0 必跑** | A hero-trio | 首屏視覺、決定第一印象 |
| **P0 必跑** | G og-minecraft-python | SEO 社群分享卡 |
| **P1** | C-F gameplay 4 張 | 03 章「他會做什麼」整章靠這 4 張支撐 |
| **P2** | B portal-bridge | 02 章視覺強化（沒有也能用 placeholder） |

---

## 跑完後存到資料夾

```
/Users/posh.lin/Documents/minecraft-python-prototype/assets/
├── hero-trio.png
├── portal-bridge.png
├── gameplay-agent-mine.png
├── gameplay-agent-build.png
├── gameplay-repair.png
├── gameplay-pet.png
└── og-minecraft-python.png
```

跑完後告訴我，我會：
1. 確認檔案到位
2. 把 HTML 裡的 placeholder 換成 `<img>`
3. 跑 preflight
4. push 到 OrangeApple-Lab/oa-page-minecraft-python
5. 通知數位長部署
