# Function: <code>native_local_ptep_get_and_clear</code>

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
In mm/memory.c (ffffffff811bd9da)
Location: arch/x86/include/asm/pgtable.h:697
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d915b)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811eef7e)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e85ed)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811ff8e0)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3713)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
```
```
In mm/madvise.c (ffffffff8120a5eb)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120b077)
Location: arch/x86/include/asm/pgtable.h:958
Inline: True
```
```
In mm/madvise.c (ffffffff812235e5)
Location: arch/x86/include/asm/pgtable.h:958
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122be74)
Location: arch/x86/include/asm/pgtable.h:1009
Inline: True
```
```
In mm/madvise.c (ffffffff812467d3)
Location: arch/x86/include/asm/pgtable.h:1009
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123f28c)
Location: arch/x86/include/asm/pgtable.h:1034
Inline: True
```
```
In mm/madvise.c (ffffffff8125abfa)
Location: arch/x86/include/asm/pgtable.h:1034
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81250bcb)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
```
```
In mm/madvise.c (ffffffff81275a8c)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125f1a6)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
```
```
In mm/madvise.c (ffffffff81284a5c)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128f57f)
Location: arch/x86/include/asm/pgtable.h:1014
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812b6c48)
Location: arch/x86/include/asm/pgtable.h:1014
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129a08a)
Location: arch/x86/include/asm/pgtable.h:1010
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e16)
Location: arch/x86/include/asm/pgtable.h:1010
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129f2ae)
Location: arch/x86/include/asm/pgtable.h:1010
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9c8f)
Location: arch/x86/include/asm/pgtable.h:1010
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e0515)
Location: arch/x86/include/asm/pgtable.h:981
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ecaf)
Location: arch/x86/include/asm/pgtable.h:981
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81340b94)
Location: arch/x86/include/asm/pgtable.h:979
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81376f7b)
Location: arch/x86/include/asm/pgtable.h:979
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b8b2e)
Location: arch/x86/include/asm/pgtable.h:997
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff813f4412)
Location: arch/x86/include/asm/pgtable.h:997
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ed766)
Location: arch/x86/include/asm/pgtable.h:998
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81427bee)
Location: arch/x86/include/asm/pgtable.h:998
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff81418d45)
Location: arch/x86/include/asm/pgtable.h:1220
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81461403)
Location: arch/x86/include/asm/pgtable.h:1220
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812577f6)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
```
```
In mm/madvise.c (ffffffff8127d0ac)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124a17d)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8126ef2d)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255596)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
```
```
In mm/madvise.c (ffffffff8127ae4c)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265045)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa25)
Location: arch/x86/include/asm/pgtable.h:1054
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
</ul>

## Differences
