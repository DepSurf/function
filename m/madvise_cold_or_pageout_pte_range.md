# Function: <code>madvise_cold_or_pageout_pte_range</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81284d70)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffffffff81284d70-ffffffff8128584c: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812b6f50)
Location: mm/madvise.c:301
Inline: False
```
**Symbols:**

```
ffffffff812b6f50-ffffffff812b7a56: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c1e90)
Location: mm/madvise.c:306
Inline: False
```
**Symbols:**

```
ffffffff812c1e90-ffffffff812c298f: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c8d50)
Location: mm/madvise.c:306
Inline: False
```
**Symbols:**

```
ffffffff812c8d50-ffffffff812c980f: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:308
Inline: False
```
**Symbols:**

```
ffffffff8130dd60-ffffffff8130e82e: madvise_cold_or_pageout_pte_range (STB_LOCAL)
ffffffff81cbe84f-ffffffff81cbe86b: madvise_cold_or_pageout_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:323
Inline: False
```
**Symbols:**

```
ffffffff813770f0-ffffffff81377f1c: madvise_cold_or_pageout_pte_range (STB_LOCAL)
ffffffff81e708a1-ffffffff81e708bd: madvise_cold_or_pageout_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:337
Inline: False
```
**Symbols:**

```
ffffffff813f46f0-ffffffff813f5802: madvise_cold_or_pageout_pte_range (STB_LOCAL)
ffffffff820658ca-ffffffff820658e6: madvise_cold_or_pageout_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:343
Inline: False
```
**Symbols:**

```
ffffffff81427cb0-ffffffff8142855d: madvise_cold_or_pageout_pte_range (STB_LOCAL)
ffffffff820e50ad-ffffffff820e50c9: madvise_cold_or_pageout_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:324
Inline: False
```
**Symbols:**

```
ffffffff814614c0-ffffffff81461e0f: madvise_cold_or_pageout_pte_range (STB_LOCAL)
ffffffff821c228a-ffffffff821c22a6: madvise_cold_or_pageout_pte_range.cold (STB_LOCAL)
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
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffff80001031f0f0)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffff80001031f0f0-ffff80001031fa40: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c05379e0)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
c05379e0-c0537cc8: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f3af0)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
c0000000003f3af0-c0000000003f4c74: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe000220ba8)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffffffe000220ba8-ffffffe000220e16: madvise_cold_or_pageout_pte_range (STB_LOCAL)
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
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8127d3c0)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffffffff8127d3c0-ffffffff8127de9c: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8126f230)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffffffff8126f230-ffffffff8126fcc0: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8127b160)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffffffff8127b160-ffffffff8127bc3c: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8128ad30)
Location: mm/madvise.c:300
Inline: False
```
**Symbols:**

```
ffffffff8128ad30-ffffffff8128b810: madvise_cold_or_pageout_pte_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
