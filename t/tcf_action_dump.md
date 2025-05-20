# Function: <code>tcf_action_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct list_head *actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817485f0)
Location: net/sched/act_api.c:479
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff817485f0-ffffffff817486f1: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct list_head *actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b5710)
Location: net/sched/act_api.c:495
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff817b5710-ffffffff817b581e: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct list_head *actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e5110)
Location: net/sched/act_api.c:509
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff817e5110-ffffffff817e521e: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct list_head *actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81804c70)
Location: net/sched/act_api.c:560
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81804c70-ffffffff81804d5e: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct list_head *actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81883990)
Location: net/sched/act_api.c:576
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81883990-ffffffff81883a7e: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct list_head *actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d73e0)
Location: net/sched/act_api.c:596
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff818d73e0-ffffffff818d74ce: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819037b0)
Location: net/sched/act_api.c:760
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff819037b0-ffffffff81903898: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (0)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff8196568d-ffffffff819656b0: tcf_action_dump.cold (STB_LOCAL)
ffffffff81964960-ffffffff81964a3e: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199b4c0)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff8199b4c0-ffffffff8199b5ad: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a746f0)
Location: net/sched/act_api.c:837
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81a746f0-ffffffff81a747ff: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7d4e0)
Location: net/sched/act_api.c:843
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81a7d4e0-ffffffff81a7d5f1: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a66240)
Location: net/sched/act_api.c:856
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81a66240-ffffffff81a66350: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1f500)
Location: net/sched/act_api.c:865
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81b1f500-ffffffff81b1f610: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca7320)
Location: net/sched/act_api.c:1186
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81ca7320-ffffffff81ca7457: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e64040)
Location: net/sched/act_api.c:1212
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81e64040-ffffffff81e64177: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ec00d0)
Location: net/sched/act_api.c:1207
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81ec00d0-ffffffff81ec0207: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref, bool terse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f83280)
Location: net/sched/act_api.c:1239
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff81f83280-ffffffff81f833b7: tcf_action_dump (STB_GLOBAL)
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
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c48690)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffff800010c48690-ffff800010c487c4: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d596fc)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
c0d596fc-c0d597f8: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d45b60)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
c000000000d45b60-c000000000d45d1c: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b605a)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffe0007b605a-ffffffe0007b611e: tcf_action_dump (STB_GLOBAL)
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
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193b330)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff8193b330-ffffffff8193b41d: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f4e30)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff818f4e30-ffffffff818f4f1d: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198c4c0)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff8198c4c0-ffffffff8198c5ad: tcf_action_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_action_dump(struct sk_buff *skb, struct tc_action **actions, int bind, int ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819aed50)
Location: net/sched/act_api.c:791
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_dump
```
**Symbols:**

```
ffffffff819aed50-ffffffff819aee3d: tcf_action_dump (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct list_head *actions</code> ➡️ <code>struct tc_action **actions</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool terse</code>
</li>
</ul>
</details>
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
