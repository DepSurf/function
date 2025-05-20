# Function: <code>free_pud_range</code>

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
In mm/memory.c (ffffffff811bcc17)
Location: mm/memory.c:435
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff811d7967)
Location: mm/memory.c:447
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff811e7671)
Location: mm/memory.c:445
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff811f2886)
Location: mm/memory.c:477
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
In mm/memory.c (ffffffff81209959)
Location: mm/memory.c:478
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
In mm/memory.c (ffffffff8122a7b3)
Location: mm/memory.c:493
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
In mm/memory.c (ffffffff8123db63)
Location: mm/memory.c:236
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124e220)
Location: mm/memory.c:238
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff8124e220-ffffffff8124e6a0: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125c790)
Location: mm/memory.c:238
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff8125c790-ffffffff8125cc10: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128c080)
Location: mm/memory.c:256
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff8128c080-ffffffff8128c519: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81297000)
Location: mm/memory.c:258
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff81297000-ffffffff8129747a: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129ce50)
Location: mm/memory.c:270
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff8129ce50-ffffffff8129d2dc: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812de2a0)
Location: mm/memory.c:269
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff812de2a0-ffffffff812de705: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133e360)
Location: mm/memory.c:273
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff8133e360-ffffffff8133e7e3: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b53c0)
Location: mm/memory.c:217
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff813b53c0-ffffffff813b584e: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eaa60)
Location: mm/memory.c:232
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff813eaa60-ffffffff813eaef7: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417260)
Location: mm/memory.c:230
Inline: False
Direct callers:
  - mm/memory.c:free_p4d_range
```
**Symbols:**

```
ffffffff81417260-ffffffff814176f7: free_pud_range (STB_LOCAL)
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
Location: mm/memory.c:238
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
Location: mm/memory.c:238
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
Location: mm/memory.c:238
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
Location: mm/memory.c:238
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
<summary>In <code>aws</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254de0)
Location: mm/memory.c:238
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff81254de0-ffffffff81255260: free_pud_range (STB_LOCAL)
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
In mm/memory.c (ffffffff81248ad5)
Location: mm/memory.c:238
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252b80)
Location: mm/memory.c:238
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff81252b80-ffffffff81253000: free_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather *tlb, p4d_t *p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812624e0)
Location: mm/memory.c:238
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffffffff812624e0-ffffffff81262960: free_pud_range (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
