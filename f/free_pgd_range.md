# Function: <code>free_pgd_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bcb90)
Location: mm/memory.c:471
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811bcb90-ffffffff811bd104: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d78e0)
Location: mm/memory.c:483
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811d78e0-ffffffff811d7ed4: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e75f0)
Location: mm/memory.c:481
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811e75f0-ffffffff811e7ba4: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2780)
Location: mm/memory.c:546
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811f2780-ffffffff811f2d5b: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209830)
Location: mm/memory.c:548
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81209830-ffffffff81209ebe: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a6a0)
Location: mm/memory.c:563
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8122a6a0-ffffffff8122acd9: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123da50)
Location: mm/memory.c:306
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8123da50-ffffffff8123e09d: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f740)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8124f740-ffffffff8124f913: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125dce0)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8125dce0-ffffffff8125deb3: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128daf0)
Location: mm/memory.c:326
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8128daf0-ffffffff8128dc51: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81298760)
Location: mm/memory.c:328
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81298760-ffffffff812988c1: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129de80)
Location: mm/memory.c:340
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8129de80-ffffffff8129dfe1: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81cbc343-ffffffff81cbc3b0: free_pgd_range.cold (STB_LOCAL)
ffffffff812df0a0-ffffffff812df221: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81e6deca-ffffffff81e6df48: free_pgd_range.cold (STB_LOCAL)
ffffffff8133f5d0-ffffffff8133f754: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff82063ed2-ffffffff82063f50: free_pgd_range.cold (STB_LOCAL)
ffffffff813b7450-ffffffff813b75f7: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff820e359c-ffffffff820e361a: free_pgd_range.cold (STB_LOCAL)
ffffffff813ec160-ffffffff813ec30a: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff821bfff1-ffffffff821c006f: free_pgd_range.cold (STB_LOCAL)
ffffffff814179d0-ffffffff81417b7a: free_pgd_range (STB_GLOBAL)
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
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f53b8)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffff8000102f53b8-ffff8000102f58e0: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0517424)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c0517424-c0517708: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bc380)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
c0000000003bc380-c0000000003bcd18: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002069b2)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffe0002069b2-ffffffe000206cea: free_pgd_range (STB_GLOBAL)
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
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256330)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81256330-ffffffff81256503: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812489c0)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812489c0-ffffffff81248f4c: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812540d0)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812540d0-ffffffff812542a3: free_pgd_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pgd_range(struct mmu_gather *tlb, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263b60)
Location: mm/memory.c:308
Inline: False
Direct callers:
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81263b60-ffffffff81263d33: free_pgd_range (STB_GLOBAL)
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
