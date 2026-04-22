# research-ppt-review

更符合中国宝宝体质的学术研究 PPT 审稿与改进建议 Skill。

这是一个面向 **Claude Code / Anthropic Skills** 的学术 PPT review skill，主要用于帮助毕业生、博士生、硕士生、青年教师或研究人员，对学术汇报 PPT 进行系统性审查，并给出更符合中文学术答辩、组会汇报、求职面试、博后申请等场景的修改建议。

本 Skill 不只是检查文字内容，还强调结合 PPT 的**页面结构、图文关系、信息密度、逻辑顺序和视觉呈现**进行综合 review，尤其适合“临近毕业、正在求职、想快速改进汇报 PPT”的使用场景。

---

## 适用场景

本 Skill 适用于但不限于以下场景：

- 本科 / 硕士 / 博士毕业答辩 PPT
- 预答辩 PPT
- 组会汇报 PPT
- 学术会议报告 PPT
- 博后申请汇报 PPT
- 青年教师面试汇报 PPT
- 项目申请或结题答辩 PPT
- 个人学术成果展示 PPT

---

## 安装方式

将本仓库克隆到你的 Claude Code skills 目录下，或放到你自己的 skills 管理路径中，操作命令如下：

```bash
git clone https://github.com/wuzhy1ng/research-ppt-review.git
cd research-ppt-review
mkdir -p ~/.claude/skills/    # 创建Skills目录，如果不存在的话
cp -r research-ppt-review ~/.claude/skills/
```

## 使用方法
1. 将ppt放在某个空目录下
2. 在该目录下启动claude code，并执行：

```bash
/research-ppt-review 请给该目录下的文件xxx（你的ppt文件名）提供改进建议
```

---

## 后记

**本Skill浓缩了Up CS读博以来，所有PPT修改经验**。
个人经验仅供参考。
