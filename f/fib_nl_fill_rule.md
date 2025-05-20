# Function: <code>fib_nl_fill_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff81739d10)
Location: net/core/fib_rules.c:560
Inline: True
Direct callers:
  - net/core/fib_rules.c:dump_rules
  - net/core/fib_rules.c:notify_rule_change
```
**Symbols:**

```
ffffffff81739d10-ffffffff8173a06b: fib_nl_fill_rule.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff817a5ff0)
Location: net/core/fib_rules.c:630
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff817a5ff0-ffffffff817a63a1: fib_nl_fill_rule.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff817d4ad0)
Location: net/core/fib_rules.c:702
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff817d4ad0-ffffffff817d4f01: fib_nl_fill_rule.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff817f3ea0)
Location: net/core/fib_rules.c:726
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff817f3ea0-ffffffff817f42e8: fib_nl_fill_rule.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff8186f600)
Location: net/core/fib_rules.c:792
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff8186f600-ffffffff8186fa4d: fib_nl_fill_rule.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c0d40)
Location: net/core/fib_rules.c:959
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff818c0d40-ffffffff818c1240: fib_nl_fill_rule.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff818e9b50)
Location: net/core/fib_rules.c:958
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff818e9b50-ffffffff818ea04d: fib_nl_fill_rule.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (0)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff819395a0-ffffffff81939aa1: fib_nl_fill_rule.isra.0 (STB_LOCAL)
ffffffff8193aaa4-ffffffff8193aabe: fib_nl_fill_rule.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff8196c460)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff8196c460-ffffffff8196c975: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a40310)
Location: net/core/fib_rules.c:964
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81a40310-ffffffff81a40831: fib_nl_fill_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (0)
Location: net/core/fib_rules.c:987
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81a43010-ffffffff81a43559: fib_nl_fill_rule (STB_LOCAL)
ffffffff81c31b23-ffffffff81c31b3b: fib_nl_fill_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (0)
Location: net/core/fib_rules.c:987
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81a27d70-ffffffff81a282b7: fib_nl_fill_rule (STB_LOCAL)
ffffffff81c23dec-ffffffff81c23e04: fib_nl_fill_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (0)
Location: net/core/fib_rules.c:987
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81adcb10-ffffffff81add057: fib_nl_fill_rule (STB_LOCAL)
ffffffff81d37ce3-ffffffff81d37cfb: fib_nl_fill_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (0)
Location: net/core/fib_rules.c:1008
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81c5e060-ffffffff81c5e598: fib_nl_fill_rule (STB_LOCAL)
ffffffff81f046b4-ffffffff81f046cc: fib_nl_fill_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e14880)
Location: net/core/fib_rules.c:1008
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81e14880-ffffffff81e14dd8: fib_nl_fill_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e88190)
Location: net/core/fib_rules.c:1008
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81e88190-ffffffff81e886e8: fib_nl_fill_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81f4a1a0)
Location: net/core/fib_rules.c:1006
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff81f4a1a0-ffffffff81f4a6f8: fib_nl_fill_rule (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffff800010c12d00)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffff800010c12d00-ffff800010c13184: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_nl_fill_rule(struct sk_buff *skb, struct fib_rule *rule, u32 pid, u32 seq, int type, int flags, struct fib_rules_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c0d2a624)
Location: net/core/fib_rules.c:957
Inline: False
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
c0d2a624-c0d2ab48: fib_nl_fill_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (c000000000cffcb0)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
c000000000cffcb0-c000000000d002cc: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffe00078e76a)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffe00078e76a-ffffffe00078eb10: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff8190c430)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff8190c430-ffffffff8190c945: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c61f0)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff818c61f0-ffffffff818c6705: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff8195d460)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff8195d460-ffffffff8195d975: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (ffffffff8197f6b0)
Location: net/core/fib_rules.c:957
Inline: True
Direct callers:
  - net/core/fib_rules.c:notify_rule_change
  - net/core/fib_rules.c:dump_rules
```
**Symbols:**

```
ffffffff8197f6b0-ffffffff8197fbc5: fib_nl_fill_rule.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
