# Function: <code>should_numa_migrate_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ba380)
Location: kernel/sched/fair.c:1054
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810ba380-ffffffff810ba4a9: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd7e0)
Location: kernel/sched/fair.c:1201
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810bd7e0-ffffffff810bd902: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2d40)
Location: kernel/sched/fair.c:1325
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810c2d40-ffffffff810c2e6a: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bda10)
Location: kernel/sched/fair.c:1322
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810bda10-ffffffff810bdb39: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5700)
Location: kernel/sched/fair.c:1363
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810c5700-ffffffff810c5829: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cd0b0)
Location: kernel/sched/fair.c:1391
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810cd0b0-ffffffff810cd1d3: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5a70)
Location: kernel/sched/fair.c:1387
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810d5a70-ffffffff810d5bd5: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de510)
Location: kernel/sched/fair.c:1450
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810de510-ffffffff810de685: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8a60)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810e8a60-ffffffff810e8bd5: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3230)
Location: kernel/sched/fair.c:1419
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810f3230-ffffffff810f33a3: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1470)
Location: kernel/sched/fair.c:1426
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810f1470-ffffffff810f15e3: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3760)
Location: kernel/sched/fair.c:1423
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810f3760-ffffffff810f38d6: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110cfd0)
Location: kernel/sched/fair.c:1412
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff8110cfd0-ffffffff8110d17f: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81128b70)
Location: kernel/sched/fair.c:1415
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff81128b70-ffffffff81128d51: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81152270)
Location: kernel/sched/fair.c:1568
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff81152270-ffffffff8115278c: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81161b60)
Location: kernel/sched/fair.c:1585
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff81161b60-ffffffff8116202c: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct folio *folio, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116e630)
Location: kernel/sched/fair.c:1826
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff8116e630-ffffffff8116eaf9: should_numa_migrate_memory (STB_GLOBAL)
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
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010148920)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffff800010148920-ffff800010148ab0: should_numa_migrate_memory (STB_GLOBAL)
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
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019a300)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
c00000000019a300-c00000000019a568: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2c10)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810e2c10-ffffffff810e2d85: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1d20)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810d1d20-ffffffff810d1e95: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810def90)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810def90-ffffffff810df105: should_numa_migrate_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool should_numa_migrate_memory(struct task_struct *p, struct page *page, int src_nid, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eaad0)
Location: kernel/sched/fair.c:1408
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff810eaad0-ffffffff810eac45: should_numa_migrate_memory (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
