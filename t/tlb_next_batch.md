# Function: <code>tlb_next_batch</code>

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
In mm/memory.c (ffffffff811bcb11)
Location: mm/memory.c:184
Inline: True
Inline callers:
  - mm/memory.c:__tlb_remove_page
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
In mm/memory.c (ffffffff811d648d)
Location: mm/memory.c:187
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811e63e0)
Location: mm/memory.c:187
Inline: True
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff811e63e0-ffffffff811e6450: tlb_next_batch.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811f1460)
Location: mm/memory.c:191
Inline: True
```
**Symbols:**

```
ffffffff811f1460-ffffffff811f14d3: tlb_next_batch.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81208130)
Location: mm/memory.c:192
Inline: True
```
**Symbols:**

```
ffffffff81208130-ffffffff812081a3: tlb_next_batch.isra.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812290b0)
Location: mm/memory.c:191
Inline: True
```
**Symbols:**

```
ffffffff812290b0-ffffffff81229123: tlb_next_batch.isra.68 (STB_LOCAL)
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
In mm/mmu_gather.c (ffffffff8124cafe)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff8125efb5)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff8126d7c5)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff8129d885)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff812a8c05)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff812ae0b5)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff812ef855)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff81352d47)
Location: mm/mmu_gather.c:17
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff813ccf77)
Location: mm/mmu_gather.c:18
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff814018d7)
Location: mm/mmu_gather.c:18
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff8142df97)
Location: mm/mmu_gather.c:18
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffff800010304b38)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (c0522dd8)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (c0000000003d15a4)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffe000210e24)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff81265e15)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff81258235)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff81263bb5)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
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
In mm/mmu_gather.c (ffffffff81273575)
Location: mm/mmu_gather.c:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:__tlb_remove_page_size
```
</details>
</li>
</ul>

## Differences
