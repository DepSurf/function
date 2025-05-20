# Function: <code>clflush_cache_range_opt</code>

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
void clflush_cache_range_opt(void *vaddr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107d870)
Location: arch/x86/mm/pageattr.c:277
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
```
**Symbols:**

```
ffffffff8107d870-ffffffff8107d8a2: clflush_cache_range_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clflush_cache_range_opt(void *vaddr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081170)
Location: arch/x86/mm/pageattr.c:278
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
```
**Symbols:**

```
ffffffff81081170-ffffffff810811a1: clflush_cache_range_opt (STB_LOCAL)
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
In arch/x86/mm/pageattr.c (ffffffff810838c7)
Location: arch/x86/mm/pageattr.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d3b9)
Location: arch/x86/mm/pat/set_memory.c:285
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d289)
Location: arch/x86/mm/pat/set_memory.c:285
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108de39)
Location: arch/x86/mm/pat/set_memory.c:293
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109d73b)
Location: arch/x86/mm/pat/set_memory.c:293
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b1012)
Location: arch/x86/mm/pat/set_memory.c:296
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cb742)
Location: arch/x86/mm/pat/set_memory.c:314
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff810ced62)
Location: arch/x86/mm/pat/set_memory.c:315
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d7442)
Location: arch/x86/mm/pat/set_memory.c:315
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In arch/x86/mm/pageattr.c (ffffffff810828c7)
Location: arch/x86/mm/pageattr.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
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
In arch/x86/mm/pageattr.c (ffffffff81071639)
Location: arch/x86/mm/pageattr.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
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
In arch/x86/mm/pageattr.c (ffffffff81082877)
Location: arch/x86/mm/pageattr.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
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
In arch/x86/mm/pageattr.c (ffffffff81084997)
Location: arch/x86/mm/pageattr.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
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
</ul>
