# Function: <code>device_private_entry_to_pfn</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff8121a5c1)
Location: include/linux/swapops.h:127
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:127
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (ffffffff81262b79)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (ffffffff81271329)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (ffffffff812a19f6)
Location: include/linux/swapops.h:125
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:125
Inline: True
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
In mm/page_vma_mapped.c (ffffffff812ad2b3)
Location: include/linux/swapops.h:125
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:125
Inline: True
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
In mm/page_vma_mapped.c (ffffffff812b23f7)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:132
Inline: True
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:152
Inline: True
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
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:152
Inline: True
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
In mm/page_vma_mapped.c (c0000000003d5280)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:152
Inline: True
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
In mm/page_vma_mapped.c (ffffffff81269979)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (ffffffff8125bbe6)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (ffffffff81267719)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
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
In mm/page_vma_mapped.c (ffffffff812770a9)
Location: include/linux/swapops.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
</details>
</li>
</ul>

## Differences
