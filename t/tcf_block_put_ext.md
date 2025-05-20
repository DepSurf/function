# Function: <code>tcf_block_put_ext</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f780)
Location: net/sched/cls_api.c:339
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff8187f780-ffffffff8187f8ac: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2ed1)
Location: net/sched/cls_api.c:664
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff818d2cc0-ffffffff818d2e63: tcf_block_put_ext.part.35 (STB_LOCAL)
ffffffff818d2e70-ffffffff818d2e86: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ff8b1)
Location: net/sched/cls_api.c:1119
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff818ff800-ffffffff818ff846: tcf_block_put_ext.part.52 (STB_LOCAL)
ffffffff818ff850-ffffffff818ff866: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81960121)
Location: net/sched/cls_api.c:1497
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81960070-ffffffff819600c0: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffff819600c0-ffffffff819600d6: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81997201)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81997150-ffffffff819971a0: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffff819971a0-ffffffff819971b6: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6f520)
Location: net/sched/cls_api.c:1374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81a71260-ffffffff81a712b0: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a79ce0)
Location: net/sched/cls_api.c:1375
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81a79c40-ffffffff81a79c90: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a62edc)
Location: net/sched/cls_api.c:1375
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81a62e40-ffffffff81a62e90: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b1c24c)
Location: net/sched/cls_api.c:1376
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81b1c1b0-ffffffff81b1c200: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca1afb)
Location: net/sched/cls_api.c:1393
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81ca1a40-ffffffff81ca1aa6: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5d72b)
Location: net/sched/cls_api.c:1395
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81e5d660-ffffffff81e5d6c6: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebc06b)
Location: net/sched/cls_api.c:1500
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81ebbfa0-ffffffff81ebc006: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7f130)
Location: net/sched/cls_api.c:1520
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81f7f130-ffffffff81f7f1c3: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffff800010c44364)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffff800010c44280-ffff800010c442e8: tcf_block_put_ext.part.0 (STB_LOCAL)
ffff800010c442e8-ffff800010c44330: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (c0d54edc)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
c0d54e20-c0d54e70: tcf_block_put_ext.part.0 (STB_LOCAL)
c0d54e70-c0d54e94: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (c000000000d3f80c)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
c000000000d3f730-c000000000d3f7ac: tcf_block_put_ext.part.0 (STB_LOCAL)
c000000000d3f7b0-c000000000d3f7cc: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b274e)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffe0007b268e-ffffffe0007b26ea: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffe0007b26ea-ffffffe0007b2726: tcf_block_put_ext (STB_GLOBAL)
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
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81937071)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81936fc0-ffffffff81937010: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffff81937010-ffffffff81937026: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f0b71)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff818f0ac0-ffffffff818f0b10: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffff818f0b10-ffffffff818f0b26: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81988201)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81988150-ffffffff819881a0: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffff819881a0-ffffffff819881b6: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_put_ext(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819aa471)
Location: net/sched/cls_api.c:1411
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff819aa3c0-ffffffff819aa410: tcf_block_put_ext.part.0 (STB_LOCAL)
ffffffff819aa410-ffffffff819aa426: tcf_block_put_ext (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
