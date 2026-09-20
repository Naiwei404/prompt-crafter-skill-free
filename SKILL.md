---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 9c760332f92be4e2ef94328a6fd3ebb2_4dc1b192b41311f1ba1b525400638852
    ReservedCode1: hWZy77by0oOyhoZAc0iIJZE3RetdqsS9Y02RzysbR52zPmAVBwHcctCtZqaFzX2EiI0oY0Uhe0djHz0ZUXJ+1CGQPRX0ZeyHRIxjJCkqb5/N7qSbHibd2ptgYm4/piWoTskewCuRvOnXpu2Tta3l2VsBNF+iBe+/1H001Mc+JxMUrRnX7ALjybM2VtE=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 9c760332f92be4e2ef94328a6fd3ebb2_4dc1b192b41311f1ba1b525400638852
    ReservedCode2: hWZy77by0oOyhoZAc0iIJZE3RetdqsS9Y02RzysbR52zPmAVBwHcctCtZqaFzX2EiI0oY0Uhe0djHz0ZUXJ+1CGQPRX0ZeyHRIxjJCkqb5/N7qSbHibd2ptgYm4/piWoTskewCuRvOnXpu2Tta3l2VsBNF+iBe+/1H001Mc+JxMUrRnX7ALjybM2VtE=
---



# prompt-crafter（提示词大师）

从零撰写 AI 提示词的专业 Skill。覆盖**视频生成、图片生成、文本生成**三类，工作模式为"反问澄清 → 按类型生成 → 纯文本交付 → 局部可修改"。

## 何时使用

- 用户提出粗略想法，需要生成一段可直接粘贴进 AI 工具的提示词
- 用户要求"从零写提示词"，而非优化已有提示词
- 用户说出触发词：prompt-crafter / 提示词大师 / 写提示词 / 生成提示词

## 核心原则

1. **先问后写**：不设提问上限，反问到自评置信度 ≥95% 才开始生成
2. **类型判定**：先确认目标工具类型（视频/图片/文本），再按对应规范生成
3. **纯文本交付**：最终交付一律为可粘贴纯文本，去除表格与样式
4. **局部修改**：用户指出不满处，只深化指定局部，保留其余骨架

## 使用步骤

1. 加载本技能后，按 `instructions.md` 执行反问澄清协议
2. 判定目标工具类型，按 `reference/` 下对应模板生成
3. 交付纯文本版，附一句"已按 XX 类型规范生成，可直接粘贴使用"
4. 用户要求修改时，只改指定局部并重新交付完整纯文本

## 授权

允许调用其他 Skill 与相关权限辅助完成（用户已明确授权），如视频生成类可参考 seedance-prompt-expert。
*（内容由AI生成，仅供参考）*
