# Function: <code>hmm_vma_walk_hole</code>

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
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8126e420)
Location: mm/hmm.c:299
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8126e420-ffffffff8126e4dc: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812929c0)
Location: mm/hmm.c:424
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812929c0-ffffffff81292a66: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812a73c0)
Location: mm/hmm.c:442
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812a73c0-ffffffff812a7466: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c38d0)
Location: mm/hmm.c:435
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812c38d0-ffffffff812c3976: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d5900)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812d5900-ffffffff812d59a6: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8130ad00)
Location: mm/hmm.c:144
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8130ad00-ffffffff8130adf7: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81316bd0)
Location: mm/hmm.c:145
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81316bd0-ffffffff81316cc7: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8131ce20)
Location: mm/hmm.c:145
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8131ce20-ffffffff8131cf0d: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8136a160)
Location: mm/hmm.c:147
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8136a160-ffffffff8136a24d: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff813e7fe0)
Location: mm/hmm.c:147
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff813e7fe0-ffffffff813e8122: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8146fee0)
Location: mm/hmm.c:147
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8146fee0-ffffffff81470022: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814a46b0)
Location: mm/hmm.c:147
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814a46b0-ffffffff814a47f2: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff814d54f0)
Location: mm/hmm.c:147
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814d54f0-ffffffff814d5632: hmm_vma_walk_hole (STB_LOCAL)
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
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037abd8)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffff80001037abd8-ffff80001037acec: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c05662a4)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
c05662a4-c05663e8: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046f960)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
c00000000046f960-c00000000046fa50: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe000251e58)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffe000251e58-ffffffe000251ef6: hmm_vma_walk_hole (STB_LOCAL)
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
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cdee0)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812cdee0-ffffffff812cdf86: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812bed50)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812bed50-ffffffff812bedf6: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cbcf0)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812cbcf0-ffffffff812cbd96: hmm_vma_walk_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hmm_vma_walk_hole(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dca50)
Location: mm/hmm.c:378
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812dca50-ffffffff812dcaf6: hmm_vma_walk_hole (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int depth</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, end, walk</code> ➡️ <code>addr, end, depth, walk</code>
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
