# Function: <code>can_gather_numa_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *can_gather_numa_stats(pte_t pte, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81276f80)
Location: fs/proc/task_mmu.c:1409
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
**Symbols:**

```
ffffffff81276f80-ffffffff81276fcc: can_gather_numa_stats (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812a56aa)
Location: fs/proc/task_mmu.c:1518
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff812baff5)
Location: fs/proc/task_mmu.c:1511
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff812c8175)
Location: fs/proc/task_mmu.c:1523
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff812ebac4)
Location: fs/proc/task_mmu.c:1619
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff81318f9a)
Location: fs/proc/task_mmu.c:1617
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff81330047)
Location: fs/proc/task_mmu.c:1623
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff81357e7c)
Location: fs/proc/task_mmu.c:1690
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff813700ac)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b80cc)
Location: fs/proc/task_mmu.c:1671
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c9f8c)
Location: fs/proc/task_mmu.c:1741
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813d15ee)
Location: fs/proc/task_mmu.c:1739
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81422aee)
Location: fs/proc/task_mmu.c:1766
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81499c06)
Location: fs/proc/task_mmu.c:1789
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152de59)
Location: fs/proc/task_mmu.c:1820
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff815661cc)
Location: fs/proc/task_mmu.c:1824
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159e1be)
Location: fs/proc/task_mmu.c:2575
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffff800010439c0c)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054d754)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136868c)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff8135996d)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff8136615c)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In fs/proc/task_mmu.c (ffffffff81379d45)
Location: fs/proc/task_mmu.c:1697
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
