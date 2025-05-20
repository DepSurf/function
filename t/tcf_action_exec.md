# Function: <code>tcf_action_exec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, const struct list_head *actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81747400)
Location: net/sched/act_api.c:405
Inline: True
```
**Symbols:**

```
ffffffff81747400-ffffffff81747473: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b45d0)
Location: net/sched/act_api.c:423
Inline: True
```
**Symbols:**

```
ffffffff817b45d0-ffffffff817b4647: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e3e80)
Location: net/sched/act_api.c:431
Inline: True
```
**Symbols:**

```
ffffffff817e3e80-ffffffff817e3ef7: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818037d0)
Location: net/sched/act_api.c:460
Inline: True
```
**Symbols:**

```
ffffffff818037d0-ffffffff818038c8: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81881cc0)
Location: net/sched/act_api.c:473
Inline: True
```
**Symbols:**

```
ffffffff81881cc0-ffffffff81881dbb: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d5510)
Location: net/sched/act_api.c:493
Inline: True
```
**Symbols:**

```
ffffffff818d5510-ffffffff818d55fb: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819020f0)
Location: net/sched/act_api.c:620
Inline: True
```
**Symbols:**

```
ffffffff819020f0-ffffffff819021db: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffff819655da-ffffffff819655f0: tcf_action_exec.cold (STB_LOCAL)
ffffffff81963550-ffffffff81963673: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffff8199c158-ffffffff8199c16e: tcf_action_exec.cold (STB_LOCAL)
ffffffff8199a0d0-ffffffff8199a1f3: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff81a72740)
Location: net/sched/act_api.c:663
Inline: True
```
**Symbols:**

```
ffffffff81a72630-ffffffff81a72735: tcf_action_exec.part.0 (STB_LOCAL)
ffffffff81a74fb7-ffffffff81a74fcd: tcf_action_exec.part.0.cold (STB_LOCAL)
ffffffff81a72740-ffffffff81a72767: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7b300)
Location: net/sched/act_api.c:704
Inline: True
```
**Symbols:**

```
ffffffff81a7b1f0-ffffffff81a7b2f5: tcf_action_exec.part.0 (STB_LOCAL)
ffffffff81c32247-ffffffff81c3225d: tcf_action_exec.part.0.cold (STB_LOCAL)
ffffffff81a7b300-ffffffff81a7b327: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:717
Inline: True
```
**Symbols:**

```
ffffffff81c24530-ffffffff81c24546: tcf_action_exec.cold (STB_LOCAL)
ffffffff81a63f70-ffffffff81a640a3: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:717
Inline: True
```
**Symbols:**

```
ffffffff81d392bb-ffffffff81d392e4: tcf_action_exec.cold (STB_LOCAL)
ffffffff81b1d2f0-ffffffff81b1d44b: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:1032
Inline: False
```
**Symbols:**

```
ffffffff81f05a8e-ffffffff81f05ab0: tcf_action_exec.cold (STB_LOCAL)
ffffffff81ca4590-ffffffff81ca470e: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e60f70)
Location: net/sched/act_api.c:1058
Inline: False
```
**Symbols:**

```
ffffffff81e60f70-ffffffff81e61102: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebcf80)
Location: net/sched/act_api.c:1053
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_classify
```
**Symbols:**

```
ffffffff81ebcf80-ffffffff81ebd115: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f80180)
Location: net/sched/act_api.c:1074
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_classify
```
**Symbols:**

```
ffffffff81f80180-ffffffff81f80309: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c46b00)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffff800010c46b00-ffff800010c46c8c: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d57d20)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
c0d57d20-c0d57e54: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d43f00)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
c000000000d43f00-c000000000d44158: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b50cc)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffe0007b50cc-ffffffe0007b5208: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffff8193bfc8-ffffffff8193bfde: tcf_action_exec.cold (STB_LOCAL)
ffffffff81939f40-ffffffff8193a063: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffff818f5ac8-ffffffff818f5ade: tcf_action_exec.cold (STB_LOCAL)
ffffffff818f3a40-ffffffff818f3b63: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffff8198d158-ffffffff8198d16e: tcf_action_exec.cold (STB_LOCAL)
ffffffff8198b0d0-ffffffff8198b1f3: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_action_exec(struct sk_buff *skb, struct tc_action **actions, int nr_actions, struct tcf_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:647
Inline: True
```
**Symbols:**

```
ffffffff819af9e8-ffffffff819af9fe: tcf_action_exec.cold (STB_LOCAL)
ffffffff819ad940-ffffffff819ada63: tcf_action_exec (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nr_actions</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, actions, res</code> ➡️ <code>skb, actions, nr_actions, res</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct list_head *actions</code> ➡️ <code>struct tc_action **actions</code>
</li>
</ul>
</details>
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
