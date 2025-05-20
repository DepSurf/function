# Function: <code>smaps_pte_entry</code>

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
In fs/proc/task_mmu.c (ffffffff812788c3)
Location: fs/proc/task_mmu.c:482
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff812a529a)
Location: fs/proc/task_mmu.c:523
Inline: True
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
In fs/proc/task_mmu.c (ffffffff812babf3)
Location: fs/proc/task_mmu.c:516
Inline: True
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
In fs/proc/task_mmu.c (ffffffff812c7dac)
Location: fs/proc/task_mmu.c:517
Inline: True
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
In fs/proc/task_mmu.c (ffffffff812ebdfc)
Location: fs/proc/task_mmu.c:523
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff813197ad)
Location: fs/proc/task_mmu.c:523
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff813303ca)
Location: fs/proc/task_mmu.c:498
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff813581fc)
Location: fs/proc/task_mmu.c:521
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff8137042c)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b8180)
Location: fs/proc/task_mmu.c:494
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813b8180-ffffffff813b83dc: smaps_pte_entry.isra.0 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff813c98e0)
Location: fs/proc/task_mmu.c:494
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813c98e0-ffffffff813c9adf: smaps_pte_entry.isra.0 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff813d09d0)
Location: fs/proc/task_mmu.c:491
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813d09d0-ffffffff813d0bcc: smaps_pte_entry.isra.0 (STB_LOCAL)
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
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:502
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81421250-ffffffff81421469: smaps_pte_entry.isra.0 (STB_LOCAL)
ffffffff81cc7f45-ffffffff81cc7f7a: smaps_pte_entry.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void smaps_pte_entry(pte_t *pte, long unsigned int addr, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8149a380)
Location: fs/proc/task_mmu.c:524
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8149a380-ffffffff8149a5df: smaps_pte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void smaps_pte_entry(pte_t *pte, long unsigned int addr, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152f370)
Location: fs/proc/task_mmu.c:536
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8152f370-ffffffff8152f5e8: smaps_pte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void smaps_pte_entry(pte_t *pte, long unsigned int addr, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81567630)
Location: fs/proc/task_mmu.c:533
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81567630-ffffffff815678a6: smaps_pte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void smaps_pte_entry(pte_t *pte, long unsigned int addr, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159fe40)
Location: fs/proc/task_mmu.c:525
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8159fe40-ffffffff815a00e6: smaps_pte_entry (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffff80001043a0fc)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smaps_pte_entry(pte_t *pte, long unsigned int addr, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c06009b8)
Location: fs/proc/task_mmu.c:524
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c06009b8-c0600cf4: smaps_pte_entry (STB_LOCAL)
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
In fs/proc/task_mmu.c (c00000000054df90)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffe0002d3196)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff81368a0c)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff81359cbc)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff813664dc)
Location: fs/proc/task_mmu.c:524
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In fs/proc/task_mmu.c (ffffffff8137981c)
Location: fs/proc/task_mmu.c:524
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
