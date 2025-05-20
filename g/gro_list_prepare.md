# Function: <code>gro_list_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171b22f)
Location: net/core/dev.c:4130
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81783aaf)
Location: net/core/dev.c:4402
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1017)
Location: net/core/dev.c:4423
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d13c7)
Location: net/core/dev.c:4637
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184b4d7)
Location: net/core/dev.c:4777
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81895899)
Location: net/core/dev.c:4907
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b7530)
Location: net/core/dev.c:5415
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81903385)
Location: net/core/dev.c:5425
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81936135)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct list_head *gro_list_prepare(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00900)
Location: net/core/dev.c:5731
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81a00900-ffffffff81a00c36: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct list_head *gro_list_prepare(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00d10)
Location: net/core/dev.c:5832
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81a00d10-ffffffff81a01046: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gro_list_prepare(const struct list_head *head, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e74e0)
Location: net/core/dev.c:5954
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
```
**Symbols:**

```
ffffffff819e74e0-ffffffff819e78a9: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gro_list_prepare(const struct list_head *head, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a981f0)
Location: net/core/dev.c:5924
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81a981f0-ffffffff81a985f2: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gro_list_prepare(const struct list_head *head, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81c539c0)
Location: net/core/gro.c:353
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81c539c0-ffffffff81c53ddb: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gro_list_prepare(const struct list_head *head, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e09170)
Location: net/core/gro.c:364
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81e09170-ffffffff81e094d0: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gro_list_prepare(const struct list_head *head, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e7b930)
Location: net/core/gro.c:325
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81e7b930-ffffffff81e7bc93: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gro_list_prepare(const struct list_head *head, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81f3bbb0)
Location: net/core/gro.c:325
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
```
**Symbols:**

```
ffffffff81f3bbb0-ffffffff81f3bfe3: gro_list_prepare (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd47b8)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceed64)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb3898)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075e5c6)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d6105)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ff45)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81927135)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81948786)
Location: net/core/dev.c:5348
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct list_head *head</code>
</li>
<li>
<b>Param removed. </b>
<code>struct napi_struct *napi</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct list_head *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
