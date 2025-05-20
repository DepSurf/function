# Function: <code>clflushopt</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106c1d8)
Location: arch/x86/include/asm/special_insns.h:196
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range
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
In arch/x86/mm/pageattr.c (ffffffff8106c046)
Location: arch/x86/include/asm/special_insns.h:234
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range
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
In arch/x86/mm/pageattr.c (ffffffff8106fc66)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range
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
In arch/x86/mm/pageattr.c (ffffffff8106f386)
Location: arch/x86/include/asm/special_insns.h:217
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range
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
In arch/x86/mm/pageattr.c (ffffffff81074726)
Location: arch/x86/include/asm/special_insns.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range
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
In arch/x86/mm/pageattr.c (ffffffff81077196)
Location: arch/x86/include/asm/special_insns.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range
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
In arch/x86/mm/pageattr.c (ffffffff8107d893)
Location: arch/x86/include/asm/special_insns.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range_opt
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
In arch/x86/mm/pageattr.c (ffffffff81081193)
Location: arch/x86/include/asm/special_insns.h:227
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:clflush_cache_range_opt
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
In arch/x86/mm/pageattr.c (ffffffff810838dc)
Location: arch/x86/include/asm/special_insns.h:203
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d3ce)
Location: arch/x86/include/asm/special_insns.h:213
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d29e)
Location: arch/x86/include/asm/special_insns.h:215
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108de4e)
Location: arch/x86/include/asm/special_insns.h:215
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109d754)
Location: arch/x86/include/asm/special_insns.h:203
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b102b)
Location: arch/x86/include/asm/special_insns.h:204
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cb75b)
Location: arch/x86/include/asm/special_insns.h:204
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
In arch/x86/mm/pat/set_memory.c (ffffffff810ced7b)
Location: arch/x86/include/asm/special_insns.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d745b)
Location: arch/x86/include/asm/special_insns.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c80da7)
Location: arch/x86/include/asm/special_insns.h:183
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_virt_range
  - drivers/gpu/drm/drm_cache.c:drm_clflush_virt_range
  - drivers/gpu/drm/drm_cache.c:drm_clflush_page
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
In arch/x86/mm/pageattr.c (ffffffff810828dc)
Location: arch/x86/include/asm/special_insns.h:203
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
In arch/x86/mm/pageattr.c (ffffffff8107164e)
Location: arch/x86/include/asm/special_insns.h:203
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
In arch/x86/mm/pageattr.c (ffffffff8108288c)
Location: arch/x86/include/asm/special_insns.h:203
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
In arch/x86/mm/pageattr.c (ffffffff810849ac)
Location: arch/x86/include/asm/special_insns.h:203
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
```
</details>
</li>
</ul>

## Differences
