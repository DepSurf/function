# Function: <code>free_p4d_range</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2866)
Location: mm/memory.c:510
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff81209916)
Location: mm/memory.c:512
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff8122a776)
Location: mm/memory.c:527
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff8123db26)
Location: mm/memory.c:270
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff8124f837)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff8125ddd7)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128cbd0)
Location: mm/memory.c:290
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff8128cbd0-ffffffff8128cdf4: free_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81298430)
Location: mm/memory.c:292
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff81298430-ffffffff81298648: free_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d2e0)
Location: mm/memory.c:304
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff8129d2e0-ffffffff8129d4a3: free_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:303
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff812de710-ffffffff812de8f5: free_p4d_range (STB_LOCAL)
ffffffff81cbc307-ffffffff81cbc343: free_p4d_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:307
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff8133e7f0-ffffffff8133e9fc: free_p4d_range (STB_LOCAL)
ffffffff81e6de8e-ffffffff81e6deca: free_p4d_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:251
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff813b5860-ffffffff813b5a6c: free_p4d_range (STB_LOCAL)
ffffffff82063e64-ffffffff82063ea0: free_p4d_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:266
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff813eaf10-ffffffff813eb11c: free_p4d_range (STB_LOCAL)
ffffffff820e3547-ffffffff820e3583: free_p4d_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_p4d_range(struct mmu_gather *tlb, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:264
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff81417710-ffffffff8141791b: free_p4d_range (STB_LOCAL)
ffffffff821bffb5-ffffffff821bfff1: free_p4d_range.cold (STB_LOCAL)
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
In mm/memory.c (ffff8000102f5480)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (c0517534)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (c0000000003bc5b4)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffe000206a56)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff81256427)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff81248a8d)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff812541c7)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff81263c57)
Location: mm/memory.c:272
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
