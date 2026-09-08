# GPT-6 Astra Universal Scan → Blender → Playable 3D Mini-Game

> Inspired by Harry's demo: 360 photos of NVIDIA DGX Spark → 16 min high-fidelity Blender model → `dgx-spark-rooftop-market` playable town

靈感來自 哈利說 實測：用 GPT-6 Astra 16分鐘把 DGX Spark 建模成 Blender 高精度模型，再變成可玩的 Spark 小市集。

[中文版說明往下看](#中文)

---

## EN

### Workflow
1.  **Shoot** 360° photos with a scale reference (ruler / coin / A4)
2.  **Prompt 1:** Photos → High-fidelity PBR Blender model
3.  **Prompt 2:** Model → Playable isometric Three.js + React mini-game

### Shooting Checklist
- Must: front / back / left / right / top / bottom / 4x 45° angles
- Details: Logo / I/O ports / holes / material / emissive / buttons / seams
- Pro tips: stable light / plain background / no strong reflections / focus every shot / include scale reference

### Quick Start
Copy `prompts/prompt-1-blender.md` to GPT-6 Astra (Computer Use mode), then `prompts/prompt-2-game.md`.

Examples in `examples/`:
- ThinkPad → cyber night market
- Coffee Machine → cozy cafe town

### Key to Success
Photo completeness > Scale reference > Computer-use permission > Blender / Web env ready

---

## 中文

### 流程
1. 360度拍照 (含尺度參考物)
2. Prompt 1: 照片 → Blender 高精度 PBR 模型
3. Prompt 2: 模型 → Three.js + React 可玩的 Isometric 小遊戲

### 拍攝規格
必拍：正面 / 背面 / 左右 / 頂底 / 四個 45度角
特寫：Logo / 接口 / 開孔 / 材質 / 發光處 / 按鍵 / 接縫
重點：光線穩定 / 背景單純 / 不要強反光 / 每張都對焦 / 放尺 / 硬幣 / A4 當尺度參考

### 快速開始
把 `prompts/prompt-1-blender.md` 貼給 GPT-6 Astra (電腦操作模式)，完成後再貼 `prompts/prompt-2-game.md`

### 成功關鍵
照片完整度 > 尺度參考 > 電腦操作權限 > Blender / Web 環境就緒

---

## Prompts
- `prompts/prompt-1-blender.md`
- `prompts/prompt-2-game.md`

## License
MIT

