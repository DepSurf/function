# Function: <code>inc_mm_tlb_gen</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107ad36)
Location: arch/x86/include/asm/tlbflush.h:527
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8121d2b2)
Location: arch/x86/include/asm/tlbflush.h:527
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff8107daee)
Location: arch/x86/include/asm/tlbflush.h:572
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8123f180)
Location: arch/x86/include/asm/tlbflush.h:572
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff81084670)
Location: arch/x86/include/asm/tlbflush.h:573
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff812537d9)
Location: arch/x86/include/asm/tlbflush.h:573
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff81088328)
Location: arch/x86/include/asm/tlbflush.h:575
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff81265a0d)
Location: arch/x86/include/asm/tlbflush.h:575
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff81088fd8)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8127432c)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff8108b6d8)
Location: arch/x86/include/asm/tlbflush.h:238
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff812a55d2)
Location: arch/x86/include/asm/tlbflush.h:238
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff8108b728)
Location: arch/x86/include/asm/tlbflush.h:238
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff812b0a29)
Location: arch/x86/include/asm/tlbflush.h:238
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff8108c307)
Location: arch/x86/include/asm/tlbflush.h:242
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff812b6116)
Location: arch/x86/include/asm/tlbflush.h:242
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff8109bb30)
Location: arch/x86/include/asm/tlbflush.h:242
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff812f7c8c)
Location: arch/x86/include/asm/tlbflush.h:242
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff810aefa7)
Location: arch/x86/include/asm/tlbflush.h:242
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8135dace)
Location: arch/x86/include/asm/tlbflush.h:242
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff810c9347)
Location: arch/x86/include/asm/tlbflush.h:243
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff813d894d)
Location: arch/x86/include/asm/tlbflush.h:243
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff810cc9e5)
Location: arch/x86/include/asm/tlbflush.h:256
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8140ad57)
Location: arch/x86/include/asm/tlbflush.h:256
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
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
In arch/x86/mm/tlb.c (ffffffff810d507e)
Location: arch/x86/include/asm/tlbflush.h:269
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff81437487)
Location: arch/x86/include/asm/tlbflush.h:269
Inline: True
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
In arch/x86/mm/tlb.c (ffffffff81087f98)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8126c97c)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff81076bf8)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8125e9da)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff81087f48)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff8126a71c)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
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
In arch/x86/mm/tlb.c (ffffffff8108a19f)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In mm/rmap.c (ffffffff81279ec2)
Location: arch/x86/include/asm/tlbflush.h:591
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
</details>
</li>
</ul>

## Differences
