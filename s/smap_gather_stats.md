# Function: <code>smap_gather_stats</code>

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
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132e400)
Location: fs/proc/task_mmu.c:714
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8132e400-ffffffff8132e4d1: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813561a0)
Location: fs/proc/task_mmu.c:737
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813561a0-ffffffff81356273: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136ea50)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8136ea50-ffffffff8136eadc: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b5ff0)
Location: fs/proc/task_mmu.c:729
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813b5ff0-ffffffff813b607c: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c90fa)
Location: fs/proc/task_mmu.c:733
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813c7bf0-ffffffff813c7ca9: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813d01c7)
Location: fs/proc/task_mmu.c:733
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813ce8b0-ffffffff813ce969: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff814217e7)
Location: fs/proc/task_mmu.c:749
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8141fc10-ffffffff8141fccc: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8149863f)
Location: fs/proc/task_mmu.c:768
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81497b40-ffffffff81497c0b: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152c991)
Location: fs/proc/task_mmu.c:779
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8152bfe0-ffffffff8152c0a8: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff815657a3)
Location: fs/proc/task_mmu.c:776
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff815643a0-ffffffff81564468: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159c975)
Location: fs/proc/task_mmu.c:771
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8159a9f0-ffffffff8159aab8: smap_gather_stats.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010438650)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffff800010438650-ffff800010438700: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c05ffd2c)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c05ffd2c-c05ffdd4: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054b150)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c00000000054b150-c00000000054b244: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d2524)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffe0002d2524-ffffffe0002d25b0: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81367030)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81367030-ffffffff813670bc: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81357cd0)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81357cd0-ffffffff81357d5c: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81364b00)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81364b00-ffffffff81364b8c: smap_gather_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void smap_gather_stats(struct vm_area_struct *vma, struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81378570)
Location: fs/proc/task_mmu.c:753
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81378570-ffffffff813785fc: smap_gather_stats (STB_LOCAL)
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
