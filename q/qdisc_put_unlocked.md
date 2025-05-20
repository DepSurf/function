# Function: <code>qdisc_put_unlocked</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f70d0)
Location: net/sched/sch_generic.c:1009
Inline: False
```
**Symbols:**

```
ffffffff818f70d0-ffffffff818f7101: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819567f0)
Location: net/sched/sch_generic.c:1004
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff819567f0-ffffffff81956823: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198cc90)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff8198cc90-ffffffff8198ccc3: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a64d80)
Location: net/sched/sch_generic.c:996
Inline: False
```
**Symbols:**

```
ffffffff81a64d80-ffffffff81a64db5: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6ceb0)
Location: net/sched/sch_generic.c:983
Inline: False
```
**Symbols:**

```
ffffffff81a6ceb0-ffffffff81a6cee5: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a556c0)
Location: net/sched/sch_generic.c:1027
Inline: False
```
**Symbols:**

```
ffffffff81a556c0-ffffffff81a556f5: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0e240)
Location: net/sched/sch_generic.c:1053
Inline: False
```
**Symbols:**

```
ffffffff81b0e240-ffffffff81b0e275: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c95c90)
Location: net/sched/sch_generic.c:1095
Inline: True
```
**Symbols:**

```
ffffffff81c95c90-ffffffff81c95cd4: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e51840)
Location: net/sched/sch_generic.c:1091
Inline: True
```
**Symbols:**

```
ffffffff81e51840-ffffffff81e51884: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81ead090)
Location: net/sched/sch_generic.c:1099
Inline: True
```
**Symbols:**

```
ffffffff81ead090-ffffffff81ead0d4: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6fb30)
Location: net/sched/sch_generic.c:1103
Inline: True
```
**Symbols:**

```
ffffffff81f6fb30-ffffffff81f6fb74: qdisc_put_unlocked (STB_GLOBAL)
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
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c382c0)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffff800010c382c0-ffff800010c38314: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4a4c4)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
c0d4a4c4-c0d4a508: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d31180)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
c000000000d31180-c000000000d311e8: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a9638)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffe0007a9638-ffffffe0007a9688: qdisc_put_unlocked (STB_GLOBAL)
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
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192cb00)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff8192cb00-ffffffff8192cb33: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e6600)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff818e6600-ffffffff818e6633: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197dc90)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff8197dc90-ffffffff8197dcc3: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qdisc_put_unlocked(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a0200)
Location: net/sched/sch_generic.c:999
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff819a0200-ffffffff819a0233: qdisc_put_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
