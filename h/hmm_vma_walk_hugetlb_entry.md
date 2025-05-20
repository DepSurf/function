# Function: <code>hmm_vma_walk_hugetlb_entry</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c3c10)
Location: mm/hmm.c:785
Inline: False
```
**Symbols:**

```
ffffffff812c3c10-ffffffff812c3ef7: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d59b0)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffffffff812d59b0-ffffffff812d5c34: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8130b620)
Location: mm/hmm.c:458
Inline: False
```
**Symbols:**

```
ffffffff8130b620-ffffffff8130b827: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff813174e0)
Location: mm/hmm.c:468
Inline: False
```
**Symbols:**

```
ffffffff813174e0-ffffffff81317713: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8131d1e0)
Location: mm/hmm.c:468
Inline: False
```
**Symbols:**

```
ffffffff8131d1e0-ffffffff8131d410: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hmm.c (0)
Location: mm/hmm.c:476
Inline: False
```
**Symbols:**

```
ffffffff8136a570-ffffffff8136a7aa: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
ffffffff81cc371a-ffffffff81cc374a: hmm_vma_walk_hugetlb_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hmm.c (0)
Location: mm/hmm.c:472
Inline: False
```
**Symbols:**

```
ffffffff813e8130-ffffffff813e83ad: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
ffffffff81e75e25-ffffffff81e75e55: hmm_vma_walk_hugetlb_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hmm.c (0)
Location: mm/hmm.c:471
Inline: False
```
**Symbols:**

```
ffffffff81470040-ffffffff814702b8: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
ffffffff82068677-ffffffff820686b1: hmm_vma_walk_hugetlb_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hmm.c (0)
Location: mm/hmm.c:473
Inline: False
```
**Symbols:**

```
ffffffff814a4810-ffffffff814a4a85: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
ffffffff820e7f4c-ffffffff820e7f86: hmm_vma_walk_hugetlb_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hmm.c (0)
Location: mm/hmm.c:473
Inline: False
```
**Symbols:**

```
ffffffff814d5840-ffffffff814d5ae8: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
ffffffff821c4c8b-ffffffff821c4cc5: hmm_vma_walk_hugetlb_entry.cold (STB_LOCAL)
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
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037b208)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffff80001037b208-ffff80001037b43c: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046fa50)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
c00000000046fa50-c00000000046fe30: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe00025218a)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffffffe00025218a-ffffffe000252326: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
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
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cdf90)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffffffff812cdf90-ffffffff812ce214: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812bee00)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffffffff812bee00-ffffffff812bf092: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cbda0)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffffffff812cbda0-ffffffff812cc024: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hmm_vma_walk_hugetlb_entry(pte_t *pte, long unsigned int hmask, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dcb00)
Location: mm/hmm.c:726
Inline: False
```
**Symbols:**

```
ffffffff812dcb00-ffffffff812dcd6f: hmm_vma_walk_hugetlb_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
