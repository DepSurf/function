# Function: <code>task_numa_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ba570)
Location: kernel/sched/fair.c:2081
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810ba570-ffffffff810bb2aa: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd9d0)
Location: kernel/sched/fair.c:2194
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810bd9d0-ffffffff810be737: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2f30)
Location: kernel/sched/fair.c:2326
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810c2f30-ffffffff810c3a19: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bdc10)
Location: kernel/sched/fair.c:2322
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810bdc10-ffffffff810be643: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5900)
Location: kernel/sched/fair.c:2374
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810c5900-ffffffff810c6324: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cd2b0)
Location: kernel/sched/fair.c:2402
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810cd2b0-ffffffff810cdd2b: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5cb0)
Location: kernel/sched/fair.c:2348
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810d5cb0-ffffffff810d7069: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de7a0)
Location: kernel/sched/fair.c:2436
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810de7a0-ffffffff810ded41: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8cf0)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810e8cf0-ffffffff810e9291: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f34f0)
Location: kernel/sched/fair.c:2623
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810f34f0-ffffffff810f380c: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1730)
Location: kernel/sched/fair.c:2637
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810f1730-ffffffff810f1a4c: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3a20)
Location: kernel/sched/fair.c:2634
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810f3a20-ffffffff810f3d30: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110d2c0)
Location: kernel/sched/fair.c:2623
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8110d2c0-ffffffff8110d63d: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81128ec0)
Location: kernel/sched/fair.c:2641
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81128ec0-ffffffff81129269: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81152910)
Location: kernel/sched/fair.c:2836
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81152910-ffffffff81152ce7: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811621b0)
Location: kernel/sched/fair.c:2836
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff811621b0-ffffffff8116259e: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116ec80)
Location: kernel/sched/fair.c:3065
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8116ec80-ffffffff8116f06e: task_numa_fault (STB_GLOBAL)
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
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010148c38)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffff800010148c38-ffff8000101491b4: task_numa_fault (STB_GLOBAL)
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
In mm/memory.c (0)
Location: include/linux/sched/numa_balancing.h:26
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019a760)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
c00000000019a760-c00000000019af38: task_numa_fault (STB_GLOBAL)
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
In mm/memory.c (0)
Location: include/linux/sched/numa_balancing.h:26
Inline: True
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
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2ea0)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810e2ea0-ffffffff810e3441: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1fb0)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810d1fb0-ffffffff810d2546: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df220)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810df220-ffffffff810df7c1: task_numa_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_numa_fault(int last_cpupid, int mem_node, int pages, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ead60)
Location: kernel/sched/fair.c:2394
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810ead60-ffffffff810eb39b: task_numa_fault (STB_GLOBAL)
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
