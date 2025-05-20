# Function: <code>notify_rule_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8173a240)
Location: net/core/fib_rules.c:692
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff8173a240-ffffffff8173a351: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff817a63b0)
Location: net/core/fib_rules.c:764
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff817a63b0-ffffffff817a64c1: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c4811)
Location: net/core/fib_rules.c:838
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff818c4811-ffffffff818c48f9: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff817f42f0)
Location: net/core/fib_rules.c:862
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff817f42f0-ffffffff817f43ef: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8186fa50)
Location: net/core/fib_rules.c:928
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff8186fa50-ffffffff8186fb52: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c1240)
Location: net/core/fib_rules.c:1103
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff818c1240-ffffffff818c1342: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818ea050)
Location: net/core/fib_rules.c:1136
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff818ea050-ffffffff818ea152: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/fib_rules.c (0)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81939ab0-ffffffff81939bb2: notify_rule_change (STB_LOCAL)
ffffffff8193aabe-ffffffff8193aad9: notify_rule_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8196c980)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff8196c980-ffffffff8196ca75: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a40840)
Location: net/core/fib_rules.c:1142
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81a40840-ffffffff81a4092f: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a43560)
Location: net/core/fib_rules.c:1165
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81a43560-ffffffff81a4364f: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a282c0)
Location: net/core/fib_rules.c:1165
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81a282c0-ffffffff81a283af: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81add060)
Location: net/core/fib_rules.c:1165
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81add060-ffffffff81add14f: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81c5e8a0)
Location: net/core/fib_rules.c:1186
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81c5e8a0-ffffffff81c5e9c0: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e15110)
Location: net/core/fib_rules.c:1186
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81e15110-ffffffff81e15230: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e88a20)
Location: net/core/fib_rules.c:1186
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81e88a20-ffffffff81e88b40: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81f4aa30)
Location: net/core/fib_rules.c:1184
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff81f4aa30-ffffffff81f4ab50: notify_rule_change (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffff800010c13188)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffff800010c13188-ffff800010c1329c: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c0d2ab48)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
c0d2ab48-c0d2ac48: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c000000000d002d0)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
c000000000d002d0-c000000000d00458: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffe00078eb10)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffe00078eb10-ffffffe00078ebe8: notify_rule_change (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8190c950)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff8190c950-ffffffff8190ca45: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c6710)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff818c6710-ffffffff818c6805: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8195d980)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff8195d980-ffffffff8195da75: notify_rule_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void notify_rule_change(int event, struct fib_rule *rule, struct fib_rules_ops *ops, struct nlmsghdr *nlh, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8197fbd0)
Location: net/core/fib_rules.c:1135
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
**Symbols:**

```
ffffffff8197fbd0-ffffffff8197fcc5: notify_rule_change (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
