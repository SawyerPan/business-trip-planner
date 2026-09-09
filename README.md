# business-trip-planner

面向国内多城市商务出差的 Codex Skill。它会围绕固定约见时间、跨城衔接、差旅标准、酒店通勤距离和机型偏好，生成可直接执行的点到点行程。

## 包含内容

- `SKILL.md`：技能入口与规划规则
- `agents/openai.yaml`：Codex 界面元数据
- `references/company-locations.md`：可复用的企业与拜访地点
- `references/personal-locations.md`：已脱敏的个人地点标识

## 安装

```bash
git clone git@github.com:SawyerPan/business-trip-planner.git "$HOME/.agents/skills/business-trip-planner"
```

安装后可通过 `$business-trip-planner` 显式调用，也可在商务出差规划场景中自动匹配。

## 隐私约定

不要向仓库提交家庭住址、联系人、订单号、企业协议价或其他敏感信息。个人地址应只在需要规划具体路线的当前会话中提供，默认不持久化。
